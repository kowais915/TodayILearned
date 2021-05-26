# Spread Operator in JavaScript

Javascript ES6 has this feature that let's you use the content of an array or an object rather than the array/object itself.
```javascript
//let's say we have an array

const randomNumbers = [1,4,2,55,23,2,1];

let adder = (a,b,c,e,f,g,h) =>{
    let sum = a+b+c+d+e+f+g+h;
    return sum;
}

const result = adder(...randomNumbers); //using the spread operator

console.log(result); //outputs the sum

```

