# loop

Cairo provides a `loop` keyword to indicate an infinite loop.

The `break` statement can be used to exit a loop at anytime, whereas the
`continue` statement can be used to skip the rest of the iteration and start a
new one.

A limitation of `loop`s is that they cannot be labeled nor nested.

```cairo,editable
{{#include ../../listings/flow_control/loop_listing/src/lib.cairo}}
```
