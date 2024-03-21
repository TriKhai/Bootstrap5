
`{property}{sides}-{breakpoint}-{size}`

Where `property` is one of:
- `m` - for classes that set `margin`
- `p` - for classes that set `padding`

Where `sides` is one of:
- `t` - for classes that set `margin-top` or `padding-top`
- `b` - for classes that set `margin-bottom` or `padding-bottom`
- `s` - (start) for classes that set `margin-left` or `padding-left` in LTR, `margin-right` or `padding-right` in RTL
- `e` - (end) for classes that set `margin-right` or `padding-right` in LTR, `margin-left` or `padding-left` in RTL
- `x` - for classes that set `both *-left and *-right`
- `y` - for classes that set `both *-top and *-bottom`
- blank - for classes that set a `margin` or `padding` on `all 4 sides` of the element

Where size is one of:
- `0` - for classes that eliminate the margin or padding by setting it to `0`
- `1` - (by default) for classes that set the margin or padding to $spacer * `.25`
- `2` - (by default) for classes that set the margin or padding to $spacer * `.5`
- `3` - (by default) for classes that set the margin or padding to $spacer
- `4` - (by default) for classes that set the margin or padding to $spacer * `1.5`
- `5` - (by default) for classes that set the margin or padding to $spacer * `3`
- `auto` - for classes that set the margin to `auto`