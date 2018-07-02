
---

### let
```js
if(true){
  // If you use var then the variable is available
  // globally versus let which makes the variable
  // available only in the block
  // let x = 10;
  var x = 10;
  document.write("x = " + x + "<br />");
}

// x is undefined here
document.write("x = " + x + "<br />");
 
// If you use let in a block with the same name
// it won't effect the value outside of the block
 
var y = 10
 
if(true){
  let y = 20
}
 
document.write("y = " + y + "<br />");
``` 

---

### const
