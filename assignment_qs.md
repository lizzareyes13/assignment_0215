// problem 1
// Write a function 'transformFirstAndLast' that takes in an array, and returns an object with:
// 1) the first element of the array as the object's key, and
// 2) the last element of the array as that key's value.

// Example input:
// ['Queen', 'Elizabeth', 'Of Hearts', 'Beyonce']

// Function's return value (output):
// {
//   Queen : 'Beyonce'
// }

// Do not change the input array. Assume all elements in the input array will be of type 'string'.

// Note that the input array may have a varying number of elements. Your code should flexibly accommodate that.
// Do not use restricted methods such as Object.keys();

// E.g. it should handle input like:
// ['Kevin', 'Bacon', 'Love', 'Hart', 'Costner', 'Spacey']

// Function's return value (output):
// {
//   Kevin : 'Spacey'
// }

// Starter Code
// function transformFirstAndLast(array) {
//   // your code here
// }

// Problem 2
// Write a function called "getAllKeys" which returns an array of all the input object's keys.
// Example input:
// {
//   name : 'Sam',
//   age : 25,
//   hasPets : true
// }

// Function's return value (output) :
// ['name', 'age', 'hasPets']

// Do not use "Object.keys" to solve this prompt.

// Note that your function should be able to handle any object passed in it.

// E.g. it should also handle an input like:
// {
//   a : 'a',
//   number : 11,
//   hungry : true,
//   grammyWins : 1
// }

// Function's return value (output):
// ['a', 'number', 'hungry', 'grammyWins']

// Starter Code:
// function getAllKeys(obj) {
//   // your code here
// }

// Problem 3
// Write a function 'fromListToObject' which takes in an array of arrays, and returns an object with each pair of elements in the array as a key-value pair.

// Example input:
// [['make', 'Ford'], ['model', 'Mustang'], ['year', 1964]]

// Function's return value (output):
// {
//   make : 'Ford'
//   model : 'Mustang',
//   year : 1964
// }

// Do not change the input string. Assume that all elements in the array will be of type 'string'.

// Note that the input may have a different number of elements than the given sample.
// For instance, if the input had 6 values instead of 4, your code should flexibly accommodate that.

// Starter Code:
// function fromListToObject(array) {
//   // your code here
// }

// Problem 4
// Write a function called "listAllValues" which returns an array of all the input object's values.

// Example input:
// {
//   name : 'Krysten',
//   age : 33,
//   hasPets : false
// }

// Function's return value (output):
// ['Krysten', 33, false]

// Note that the input may have a different number of keys and values than the given sample.

// E.g. it should also handle an input like:
// {
//   a : 'a',
//   number : 11,
//   hungry : true,
//   grammyWins : 1
// }

// Function's return value (output):
// ['a', 11, true, 1]

// Starter Code
// function listAllValues(obj) {
//   // your code here
// }

// Problem 5
// Write a function called "isPersonOldEnoughToDrinkAndDrive".

// Given a "person" object, that contains an "age" property, "isPersonOldEnoughToDrinkAndDrive" returns whether the given person is old enough to legally drink and drive in the United States.

// Notes:
// * The legal drinking age in the United States is 21.
// * The legal driving age in the United States is 16.
// * It is always illegal to drink and drive in the United States.

// var obj = {
//   age: 45
// };
// var output = isPersonOldEnoughToDrinkAndDrive(obj);
// console.log(output); // --> false

// Starter Code :
// function isPersonOldEnoughToDrinkAndDrive(person) {
//   // your code here
// }

// Problem 6
// Write a function called "extend".

// Given two objects, "extend" adds properties from the 2nd object to the 1st object.

// Notes:
// * Add any keys that are not in the 1st object.
// * If the 1st object already has a given key, ignore it (do not overwrite the property value).
// * Do not modify the 2nd object at all.

// var obj1 = {
//   a: 1,
//   b: 2
// };
// var obj2 = {
//   b: 4,
//   c: 3
// };

// extend(obj1, obj2);
// console.log(obj1); // --> {a: 1, b: 2, c: 3}
// console.log(obj2); // --> {b: 4, c: 3}

// Starter Code :
// function extend(obj1, obj2) {
//   // your code here
// }
