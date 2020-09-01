# Java-Script-Function-Types
In this short explanation about 3 function types that you must know for JavaScript.

# 3 Types of JavaScript Function

## 1. Function Hoisting
Function Hoisting is default action of JavaScript. It will automatically move the declarations to the top of scope.
So, no matter where you write your functions you can use the functions before you declared it.

This is an example code of Function Hoisting
```
var arr = [8, 3, 5, 1, 10]

arr.sort(compare) 

function compare(a,b){
    if(a < b) { return -1 }
    else if (a > b) { return +1 }
    else { return 0}
}
console.log(arr)

```

## 2. Anonymous Function
Anonymous function is a function that we can declare by write it in some expresssion without any function name.
An anonymous will started automatically without being called.

This is an example code of Anonymous Function
```
var arr = [8, 3, 5, 1, 10]

arr.sort(function (a,b){
    if(a < b) { return -1 }
    else if (a > b) { return +1 }
    else { return 0}
})
console.log(arr)

```

## 3. Arrow Function
Arrow function has a very short syntax. These function is really good  for non-method functions.
And don't forget that they cannot be used as constructors. This function will work similar to anonymous function.
For this one you don't have to put " function " at the first and this function will use " => " as a return.


This is an example code of Arrow Function
```

var arr = [8, 3, 5, 1, 10]
arr.sort((a, b)=>{return a - b}); 
console.log(arr);

```

