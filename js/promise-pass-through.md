# Promise.then(..) pass-through when not a function

If `.then(..)` is not called with a function, it will be skipped and the value of the previous promise will be passed through.

`Promise.resolve('foo').then(Promise.resolve('bar')).then((result) => { console.log(result); }); // foo`  
