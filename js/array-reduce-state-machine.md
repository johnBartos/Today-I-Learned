## Using `Array.prototype.reduce` as a state machine

`Array.prototype.reduce` can be used as a state machine - the previousValue argument represents the current state,
while the currentValue argument represents the current input.

```javascript
const stateFunc = (cur, prev) => {..};
const input = [1, 2, 3];
let initialState = {};
const result = input.reduce(stateFunc, initialState);
```
