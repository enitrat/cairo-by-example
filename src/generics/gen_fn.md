# Functions

The same set of rules can be applied to functions: a type `T` becomes
generic when preceded by `<T>`.

Using generic functions sometimes requires explicitly specifying type parameters. This may be the case if the function is called where the return type
is generic, or if the compiler doesn't have enough information to infer
the necessary type parameters.

A function call with explicitly specified type parameters looks like:
`fun::<A, B, ...>()`.

```cairo,editable
{{#include ../../listings/generics/gen_fn/src/lib.cairo}}
```

### See also:

[functions][fn] and [`struct`s][structs]

[fn]: ../fn.md
[structs]: ../custom_types/structs.md
