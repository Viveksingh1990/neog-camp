Functional Practice Question Set 3
Instructions:
Make use of .filter(), .find() and .reduce() methods.
You can make use of basic methods such as .length, toLowerCase(), toUpperCase() if needed.
Do NOT use for-loops.
1. Write an ES6 function that takes an array of objects representing cars with properties make,
model, and year. Return the first car object that is a Toyota and the year is after 2010.
const cars = [
{ make: 'Toyota', model: 'Corolla', year: 2010 },
{ make: 'Honda', model: 'Civic', year: 2012 },
{ make: 'Toyota', model: 'Camry', year: 2015 },
{ make: 'Ford', model: 'Mustang', year: 2018 },
]
// Your code here
const toyotaCar = findToyotaCar(cars)
console.log(toyotaCar)
// Output: { make: "Toyota", model: "Camry", year: 2015 }
COPY
2. Write an ES6 function that takes an array of objects containing car information (make, model,
year) and returns an array with only the cars that were made after the year 2012.
const cars = [
{ make: 'Toyota', model: 'Corolla', year: 2010 },
{ make: 'Honda', model: 'Civic', year: 2012 },
{ make: 'Toyota', model: 'Camry', year: 2015 },
{ make: 'Ford', model: 'Mustang', year: 2018 },
]
// Your code here
const getCars = getCarDetails(cars)
console.log(getCars)
// Output: [{ make: "Toyota", model: "Camry", year: 2015 }, { make: "Ford", model: "Musta
COPY
3. Write an ES6 function that takes an array of objects representing products with properties name,
price, and category. Return the first product object that is in the category "electronics".
const products = [
{ name: 'Toothbrush', price: 29, category: 'health' },
{ name: 'Coffee Maker', price: 99, category: 'home' },
{ name: 'iPad', price: 799, category: 'electronics' },
{ name: 'Smartwatch', price: 199, category: 'electronics' },
]
// Your code here
const electronicsProduct = findElectronicsProduct(products)
console.log(electronicsProduct)
// Output: { name: "iPad", price: 799, category: "electronics" }
COPY
4. Write an ES6 function that takes an array of objects representing products with properties name,
price and category. Return all the products object that are in the category "electronics".
const products = [
{ name: 'Toothbrush', price: 29, category: 'health' },
{ name: 'Coffee Maker', price: 99, category: 'home' },
{ name: 'iPad', price: 799, category: 'electronics' },
{ name: 'Smartwatch', price: 199, category: 'electronics' },
]
// Your code here
const electronicProducts = getAllElectronicProducts(products)
console.log(electronicProducts)
// Output: [{ name: "iPad", price: 799, category: "electronics" }, { name: "Smartwatch",
COPY
5. Write an ES6 function that takes an array of objects containing student information (name, age,
grade) and returns an array with only the students who have a grade above a certain value.
const students = [
{ name: 'Alice', age: 16, grade: 90 },
{ name: 'Bob', age: 17, grade: 80 },
{ name: 'Charlie', age: 15, grade: 95 },
{ name: 'David', age: 16, grade: 85 },
]
// Your code here
const highGradeStudents = filterStudentsByGrade(students, 85)
console.log(highGradeStudents)
// Output: [{ name: "Alice", age: 16, grade: 90 }, { name: "Charlie", age: 15, grade: 95
COPY
6. Write an ES6 function that takes an array of objects representing books with properties title,
author and pageCount. Return the first book object that has more than 500 pages.
const books = [
{
title: 'The Lord of the Rings',
author: 'J.R.R. Tolkien',
pageCount: 1178,
},
{
{ title: 'To Kill a Mockingbird', author: 'Harper Lee', pageCount: 281 },
title: "The Hitchhiker's Guide to the Galaxy",
author: 'Douglas Adams',
pageCount: 193,
},
{
title: 'The Name of the Wind',
author: 'Patrick Rothfuss',
pageCount: 662,
},
]
// Your code here
const bookWithMoreThan500Pages = findBookWithMoreThan500Pages(books)
console.log(bookWithMoreThan500Pages)
// Output: { title: "The Lord of the Rings", author: "J.R.R. Tolkien", pageCount: 1178 }
COPY
7. Write an ES6 function that takes an array of objects containing customer information (name,
age, gender) and returns an array with only the customers who are of gender Male.
const customers = [
{ name: 'John', age: 25, gender: 'Male' },
{ name: 'Jane', age: 30, gender: 'Female' },
{ name: 'Bob', age: 40, gender: 'Male' },
{ name: 'Alice', age: 35, gender: 'Female' },
]
// Your code here
const maleCustomers = getMaleCustomers(customers)
console.log(maleCustomers)
// Output: [{ name: 'John', age: 25, gender: 'Male' }, { name: 'Bob', age: 40, gender: 'M
COPY
8. Write an ES6 function that takes an array of objects containing game information (title,
developer, genre) and returns an array with all the games of a certain genre.
const games = [
{
title: 'The Witcher 3: Wild Hunt',
developer: 'CD Projekt Red',
genre: 'RPG',
},
{
title: 'Grand Theft Auto V',
developer: 'Rockstar North',
genre: 'Action',
},
{
{ title: 'Portal 2', developer: 'Valve Corporation', genre: 'Puzzle' },
title: 'The Legend of Zelda: Breath of the Wild',
developer: 'Nintendo',
genre: 'Adventure',
},
]
// Your code here
const filteredGames = filterByGenre(games, 'RPG')
console.log(filteredGames)
// Output: [{title: "The Witcher 3: Wild Hunt", developer: "CD Projekt Red", genre: "RPG"
COPY
9. Write an ES6 function that takes an array of objects containing car information (make, model,
year) and returns an array with only the car model that were made after the year 2012.
const cars = [
{ make: 'Toyota', model: 'Corolla', year: 2010 },
{ make: 'Honda', model: 'Civic', year: 2012 },
{ make: 'Toyota', model: 'Camry', year: 2015 },
{ make: 'Ford', model: 'Mustang', year: 2018 },
]
// Your code here
const carModels = getCarModel(cars)
console.log(carModels)
// Output: ["Camry", "Mustang"]
COPY
10. Write an ES6 function that takes an array of objects representing books with properties title,
author and pageCount. Return the all book titles that have more than 700 pages.
const books = [
{
title: 'The Lord of the Rings',
author: 'J.R.R. Tolkien',
pageCount: 1178,
},
{
{ title: 'To Kill a Mockingbird', author: 'Harper Lee', pageCount: 281 },
title: "The Hitchhiker's Guide to the Galaxy",
author: 'Douglas Adams',
pageCount: 193,
},
{
title: 'The Name of the Wind',
author: 'Patrick Rothfuss',
pageCount: 662,
},
]
// Your code here
const booksWithMoreThan700Pages = getTitlesWithMoreThan700Pages(books)
console.log(booksWithMoreThan700Pages)
// Output: ["The Lord of the Rings"]
COPY
11. Write an ES6 function that takes an array of numbers and returns the sum of all the even
numbers in the array using the reduce function.
const numbers = [12, 23, 4, 2, 11, 21]
// Your code here
console.log(sumOfEvenNumbers(numbers))
// Output: 18
COPY
12. Write an ES6 function that takes an array of objects representing students with properties name
and score, and returns the average score of all the students using the reduce function.
const students = [
{ name: 'John', score: 80 },
{ name: 'Jane', score: 90 },
{ name: 'Bob', score: 75 },
{ name: 'Alice', score: 85 },
]
// Your code here
console.log(getAverageScore(students))
// Output: 82.5
COPY
13. Write an ES6 function that takes an array of objects representing products with properties name,
price, and quantity, and returns the total cost of all the products using the reduce function.
const products = [
{ name: 'Shirt', price: 20, quantity: 2 },
{ name: 'Pants', price: 30, quantity: 1 },
{ name: 'Shoes', price: 50, quantity: 1 },
{ name: 'Hat', price: 10, quantity: 3 },
]
// Your code here
console.log(getTotalCost(products))
// Output: 150
COPY
14. Write an ES6 function that takes an array of strings and returns a single string that is the
concatenation of all the strings using the reduce function.
const strings = ['Hello', ' ', 'world', '!']
// Your code here
console.log(concatenateStrings(strings))
// Output: "Hello world!"
COPY
15. Write an ES6 function that takes an array of numbers and returns the minimum number using
the reduce function.
const numbers = [10, 5, 8, 3, 6]
// Your code here
console.log(getMinimumNumber(numbers))
// Output: 3
