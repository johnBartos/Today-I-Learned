## How `this` is assigned

1. Default binding - standalone function invocation
  - binds to global object (`window`)
  - undefined when strict

2. Implicit Binding - context object for function reference
  - object owns the function
  - object is bound to `this`

3. Implicitly Lost - implicitly bound function looses binding
  - falls back to default
  - e.g doFoo(obj.foo)

4. Explicit binding - bind, call, apply
  - manually set specified `this`
  - __cannot be overwritten except by new__

5. new - constructor call
  - `this` set to newly constructed object after being `[[Prototype]]` linked

6. `=>`
  - `this` is lexically bound and cannot be overwritten, even by `new`
  
Order of precedence goes `=>`, `new`, explicit, implicit, implicitly lost === default
