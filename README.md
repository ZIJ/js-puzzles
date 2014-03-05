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

```javascript
var car1 = {
    brand: 'audi',
    model: 'a3',
    year: 2010
};
var car2 = copy(car1, {
    year: 2011
});
console.log(car1, car2);
function copy(obj, props){
    var copy = obj;
    for (var key in props) {
        copy[key] = props[key];   
    }
    return copy;
};
```
