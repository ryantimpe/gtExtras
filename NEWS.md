# gtExtras (development version)

# gtExtras 0.2.4

* Added a `NEWS.md` file to track changes to the package.

## Bug Fixes
* Use `gt_index` to prevent incorrect ordering of rows with `gt_plt_bar_pct()` per [StackOverflow report](https://stackoverflow.com/questions/71313688/gtextras-column-showing-in-wrong-order-in-gt-table-when-grouped?noredirect=1#comment126232993_71313688)

* Remove `keep_column` argument for `gt_plt_bullet`, this functionality is able to be achieved with `gt_duplicate_column()` upstream. This also solves naming confusion as seen in [issue 37](https://github.com/jthomasmock/gtExtras/issues/37)