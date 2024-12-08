Functional Practice Question Set 4
Instructions:
Make use of .reduce() method in this set.
You can make use of basic methods such as .length, toLowerCase(), toUpperCase() if needed.
Do NOT use for-loops.
1. Given an array, write an ES6 function that returns the total length of all the strings in an array.
const strings = ['apple', 'banana', 'cherry', 'date', 'blueberry']
// Your code here
console.log(totalLength(strings))
// Output: 30
COPY
2. Write an ES6 function sumSquares that takes an array of numbers and returns the sum of the
squares of all the numbers in the array
const numbers = [1, 2, 3, 4, 5]
// Your code here
console.log(sumSquares(numbers))
// Output: 55
COPY
3. Write an ES6 function that calculates and returns the total value of all items in an array of
objects.
const items = [
{ name: 'Item 1', price: 10 },
{ name: 'Item 2', price: 20 },
{ name: 'Item 3', price: 30 },
]
// Your code here
console.log(totalValue(items))
// Output: 60
COPY
4. Write an ES6 function that takes an array of strings as input and concatenates them into a single
string.
// Your code here
console.log(concatStrings(['this', 'is', 'fun'])) // Output: 'thisisfun'
COPY
5. Write an ES6 function to multiply and return all the elements of a given array.
const numbers = [1, 2, 3, 4, 5]
// Your code here
console.log(product(numbers))
// Output: 120
COPY
6. Write an ES6 function that takes an array of strings and returns the longest string.
const strings = ['neogcamp', 'Haule Haule', 'code', 'Batman', 'Awesome']
// Your code here
console.log(longestString(strings))
// Output: 'Haule Haule'
COPY
7. Write an ES6 function that takes an array of objects with name and age property, and returns the
name of the oldest person.
const people = [
{ name: 'Jeena', age: 25 },
{ name: 'Priya', age: 30 },
{ name: 'Naina', age: 45 },
]
// Your code here
console.log(oldestPersonName(people))
// Output: 'Naina'
COPY
8. Write an ES6 function that takes an array of objects representing people with properties name
and age, and returns an object with the average age of all the people.
const people = [
{ name: 'Alice', age: 25 },
{ name: 'Bob', age: 30 },
{ name: 'Charlie', age: 35 },
{ name: 'David', age: 40 },
]
// Your code here
console.log(getAverageAge(people))
// Output: { averageAge: 32.5 }
COPY
9. Write an ES6 function that takes an array of objects representing products with properties name,
price, and quantity, and returns an object with the most expensive product.
const products = [
{ name: 'Bread', price: 10, quantity: 2 },
{ name: 'Clips', price: 20, quantity: 5 },
{ name: 'Knife', price: 30, quantity: 1 },
{ name: 'Slipper', price: 40, quantity: 3 },
]
// Your code here
console.log(findMostExpensiveProduct(products))
// { name: "Slipper", price: 40, quantity: 3 }
COPY
10. Write an ES6 function that takes an array of strings and returns an object with the count of each
string.
const fruits = [
'apple',
'banana',
'banana',
'cherry',
'apple',
'apple',
'banana',
]
// Your code here
console.log(countStrings(fruits))
// Output: { 'apple': 3, 'banana': 3, 'cherry': 1 }
