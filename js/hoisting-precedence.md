# Hoisting name-resolution order

The name resolution order is as follows: 

1. language-defined (`this`, `arguments`)
2. formal parameters (arguments of a function)
3. function declarations
4. variable declarations

Important: Once defined, names are never overwritten, except in the case of multiple formal parameters sharing a name causing the last to take hold

