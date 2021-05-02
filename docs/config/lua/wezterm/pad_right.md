# wezterm.pad_right(string, min_width)

*Since: nightly builds only*

Returns a copy of `string` that is at leasst `min_width` columns
(as measured by [wezterm.column_width](column_width.md)).

If the string is shorter than `min_width`, spaces are added to
the right end of the string.

For example, `wezterm.pad_righ("o", 3)` returns `"o  "`.

See also: [wezterm.truncate_left](truncate_left.md), [wezterm.pad_left](pad_left.md).


