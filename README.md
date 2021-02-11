# coup-pp
- Compiled
- Functional
- 4 spaces
- Ownership
- Known Types: Int, Float, Char, String (A list of chars)
- Static typing
- snake_case functions
- snake_case variables
- PascalCase types
- Haskell style function application
- Yes Generics
- No type inference

```
add.Int(x.Int, y.Int) <- x + y
// Can also be
add.Int(x.Int, y.Int) <- x.Int + y.Int
// When they can be inferred, type annotations (.Int) are only required in function signatures

// You could also do this, but that's cursed
function_1.Int(x.Int, x.Float) <- some_other_function(x.Int, x.Float)
```
