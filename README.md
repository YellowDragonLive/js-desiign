#  js-desiign
单例模式
```
const getSingle = function( fn ){
  let result;
    return function(){
      return result || ( result = fn.apply(this, arguments ))
    }
}
```
