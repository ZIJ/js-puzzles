js-puzzles
==========

```javascript
var a = 1;
(function(){
    console.log(a);
    var a = 2;    
})();
```

```javascript
for (var i = 0; i < 10; i+=1){
    setTimeout(function(){
        console.log(i);
    }, 10);
}
```
