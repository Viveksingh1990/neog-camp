# ES6+ Practice Question Set 2
Instructions: Avoid usage of in-built methods in javaScript. You can make use of basic methods such as .length, toLowerCase(), toUpperCase(), push() if needed. Make use of for-loops and if-else statements wherever needed.

1. Create an object person with two properties, "name" and "age" and then updates the "age"
property to a new value. Initial age should be 30.
```js
// Your code here
console.log(person.age) // Output: 35
```
3. Write a function that takes an object car and returns true if the car is a sports car (i.e. has a
horsepower property greater than or equal to 300)
```js
//Your ES6 code here
const car1 = { make: 'Porsche', model: '911', horsepower: 450 }
const car2 = { make: 'Toyota', model: 'Camry', horsepower: 200 }
console.log(isSportsCar(car1)) // true
console.log(isSportsCar(car2)) // false
```
4. Write a function that takes an object person and a number num as arguments and returns true if
the person's age plus num is greater than 21. Otherwise, it should return false.
```js
// Your ES6 code here
const person1 = { name: 'Ajay', age: 20 }
console.log(isEligible(person1, 1)) // false
console.log(isEligible(person1, 2)) // true
```
5. Write a function that takes an object blog and returns true if the blog has more than 1000 views
(i.e. has a views property greater than 1000)
```js
// Your ES6 code here
const blog1 = {
title: 'How to Learn JavaScript',
author: 'John Doe',
views: 1430,
}
const blog2 = {
title: '10 Reasons to Start a Blog',
author: 'Jane Smith',
views: 500,
}
console.log(getViews(blog1)) // true
console.log(getViews(blog2)) // false
```
6. Swap the values of two variables using array destructuring.
```js
let a = 1
let b = 2
// Your ES6 Code here
console.log(a) // 2
console.log(b) // 1
```
7. Convert this function into ES6 with least amount of characters.
```js
function add(a = 30, b = 0) {
return a + b
}
console.log(add(2, 3))
```
8. Write an ES6 function combineObjects with least amount of characters which merges two
objects into one.
```js
// Your ES6 function here
const obj1 = { a: 1, b: 2 }
const obj2 = { c: 3, d: 4 }
const combinedObj = combineObjects(obj1, obj2)
console.log(combinedObj)
// Expected Output: {a: 1, b: 2, c: 3, d: 4}
```
9. Convert the function getData, into an ES6 function with last amount of characters.
Hint: Destructuring
```js
function getData(person) {
const name = person.name
const address = person.address.city
console.log(name) // John Doe
console.log(address) // New York
}
const person = {
name: 'John Doe',
address: {
city: 'New York',
state: 'NY',
}
},
getData(person)
```
10. Write a function that takes a string as input and returns the string in all uppercase letters.
```js
// Youe ES6 code here
console.log(stringToUpperCase('hello')) // "HELLO"
```
11. Write a function that takes two strings as input and concatenates them together.
```js
// Your ES6 code here
console.log(concatenateStrings('hello', 'world')) // "helloworld"
```
12. Write a function that takes an array and returns the last element in the array.
```js
// Your ES6 code here
console.log(lastElement([1, 2, 3, 4, 5])) // 5
```
13. Write a function that takes an array and returns the first element of the array.
```js
// Your ES6 code here
console.log(firstElement([1, 2, 3, 4, 5])) // 1
```
14. Write a function that takes an array and a number and returns the sum of first element and the
number.
```js
// Your ES6 code here
console.log(sumFirstElement([1, 2, 3], 5)) // 6
```
15. Write a function that takes an array and returns the sum of first and last element.
```js
// Your ES6 code here
console.log(sumFirstAndLast([1, 2, 3, 4, 8])) // 9
```
16. Write a function that takes an object representing a person's information (name, age,
occupation) and returns a template literal that includes the person's name and age in a
sentence.
```js
// Your ES6 code here
const person1 = { name: 'John', age: 25, occupation: 'Software Engineer' }
const person2 = { name: 'Jane', age: 45, occupation: 'Data Analyst' }
console.log(personInfo(person1)) // Expected output: "John is 25 years old."
console.log(personInfo(person2)) // Expected output: "Jane is 45 years old."
```
