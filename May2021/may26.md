# Variables, Methods & functions in Javascript
## const and let

When you define a variable with const in javascript, you can't change it's value. However, when you define it with let, you can change it later.


## The Map Method
Map is a method in JS that takes each element of an array and does something to it (depending on the function passed to the map). Also, it is important to note that map creates a completely new array which means that the original array is unchanged.

```javascript

const arr = [1,33,14,3,2,1,3,11,334,2,21];
const newArr = arr.map(val=>val*3); //val is each element of the array. Map takes the element and multiply it with 3.
console.log(newArr); 

```
## Objects

Objects are used when you want to store data about a particular thing. For example, you might want to store some properties of a student, say, his GPA or major. You can accomplish this with Objects
```Javascript
const student ={
    "name":"Owais",
    "faculty" : "Computer Engineering",
    "Reg Number" : "2019xxx"
    'age':20,
}
```
## Accessing & Modefiying Objects
You can modeify objects by using the dot & [ ] notation.
```javascript

console.log(student.name); //prints owais
console.log(student['Reg Number']);//prints reg number

```