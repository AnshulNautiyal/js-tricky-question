## Want to Contribute?

Check this [How to edit md file?](https://guides.github.com/features/mastering-markdown/)


> Question 1
```javascript

function foo(a){
  demo();
  function demo(){
   console.log('Inside Demo function'); 
  }
}
foo();
foo(undefined);
foo(function(){ 
    console.log('Inside Anonymous function'); 
});

```
> Question 2
```javascript
setTimeout(function(){
    console.log('Inside 1');
    setTimeout(function(){
        console.log('Inside 2');
    },1000)
},1000);

setTimeout(function(){
    console.log('Inside 3');
},1000)

```
> Question 3
```javascript
const arr = ['1000','2000','3000',3000];

for(var i =0 ; i< arr.length;arr++){
    setTimeout(function(){
        console.log(` value at ${i} index: ${arr[i]} `);
},1000)
}
```