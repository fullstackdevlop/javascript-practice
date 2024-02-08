# Array Questions

### 1. How can I remove a specific item from an array in JavaScript?

```javascript
// Input
const array = [2, 5, 9];

// Output
console.log(array); // [(2, 9)];
```

[Answer](https://stackoverflow.com/questions/5767325/how-can-i-remove-a-specific-item-from-an-array-in-javascript)

[See Also](https://stackoverflow.com/questions/3954438/how-to-remove-item-from-array-by-value)

### 2. How do I check if an array includes a value in JavaScript?

```javascript
// Check if the array includes the value 3
const array = [1, 2, 3, 4, 5];

// Output
true;
```

[Answer](https://stackoverflow.com/questions/237104/how-do-i-check-if-an-array-includes-a-value-in-javascript)

### 3. Loop (for each) over an array in JavaScript

```javascript
// Use forEach method
const array = [1, 2, 3, 4, 5];
```

[Answer](https://stackoverflow.com/questions/9329446/loop-for-each-over-an-array-in-javascript)

### 4. Loop through an array in JavaScript

```javascript
// Use for, for...of, forEach, map loops
const array = [1, 2, 3, 4, 5];
```

[Answer](https://stackoverflow.com/questions/3010840/loop-through-an-array-in-javascript)

### 5. How to insert an item into an array at a specific index?

```javascript
// Insert the value 10 at index 2
const array = [1, 2, 3, 4, 5];

// Output
console.log(array); // [1, 2, 10, 3, 4, 5]
```

[Answer](https://stackoverflow.com/questions/586182/how-to-insert-an-item-into-an-array-at-a-specific-index)

### 6. Sort array of objects by string property value

```javascript
// Input
const array = [
  { country: "India", code: "91" },
  { country: "France", code: "33" },
  { country: "Austria", code: "43" },
  { country: "Italy", code: "39" },
];

// Output
console.log(array);
[
  { country: "Austria", code: "43" },
  { country: "France", code: "33" },
  { country: "India", code: "91" },
  { country: "Italy", code: "39" },
];
```

[Answer](https://stackoverflow.com/questions/1129216/sort-array-of-objects-by-string-property-value)

[Sell Also](https://stackoverflow.com/questions/6712034/sort-array-by-firstname-alphabetically-in-javascript)

```javascript
var homes = [
  {
    h_id: "1",
    city: "Bevery Hills",
    state: "CA",
    zip: "90210",
    price: "319250",
  },
  {
    h_id: "2",
    city: "Dallas",
    state: "TX",
    zip: "75201",
    price: "162500",
  },
  {
    h_id: "3",
    city: "New York",
    state: "NY",
    zip: "00010",
    price: "962500",
  },
];
```

[Sell Also](https://stackoverflow.com/questions/979256/sorting-an-array-of-objects-by-property-values)

### 7. Get all unique values in a JavaScript array (remove duplicates)

```javascript
// Input
const array = [1, 2, 3, 2, 4, 5, 1];

// Output
console.log(array); // [1, 2, 3, 4, 5]
```

> Using for loop, Set, filter and indexOf, reduce etc.

[Answer](https://stackoverflow.com/questions/1960473/get-all-unique-values-in-a-javascript-array-remove-duplicates)

[Sell Also](https://stackoverflow.com/questions/9229645/remove-duplicate-values-from-js-array)

### 8. Checking if a key exists in a JavaScript object?

```javascript
// Input
const obj = { name: "John", age: 30 };

// Output
true or false
```

[Answer](https://stackoverflow.com/questions/1098040/checking-if-a-key-exists-in-a-javascript-object)

### 9. How to merge two arrays in JavaScript and de-duplicate items

```javascript
// Input
const array1 = ["Vijendra", "Singh"];
const array2 = ["Singh", "Shakya"];

// Output
var array3 = ["Vijendra", "Singh", "Shakya"];
```

[Answer](https://stackoverflow.com/questions/1584370/how-to-merge-two-arrays-in-javascript-and-de-duplicate-items)

### 10. How can I add new array elements at the beginning of an array in JavaScript?

```javascript
// Input
const array = [23, 45, 12, 67];

// Output
console.log(Array); // [34, 23, 45, 12, 67];
```

[Answer](https://stackoverflow.com/questions/8073673/how-can-i-add-new-array-elements-at-the-beginning-of-an-array-in-javascript)

### 11. How to randomize (shuffle) a JavaScript array?

```javascript
// Input
const array = ["a", "b", "c", "d"];

// Output
console.log(Array); // ["b", "a", "d", "c"] ....
```

[Answer](https://stackoverflow.com/questions/2450954/how-to-randomize-shuffle-a-javascript-array)

### 12. Find object by id in an array of JavaScript objects.

```javascript
// Input
const array = [{'id':'73','foo':'bar'},{'id':'45','foo':'bar'} ...];

// Output
console.log(Array); // {'id':'45','foo':'bar'}
```

[Answer](https://stackoverflow.com/questions/7364150/find-object-by-id-in-an-array-of-javascript-objects)

### 13. How do I check if a variable is an array in JavaScript?

[Answer](https://stackoverflow.com/questions/767486/how-do-i-check-if-a-variable-is-an-array-in-javascript)

### 14. How to create an array containing 1...N without loop?

```javascript
const foo = [];

for (let i = 1; i <= N; i++) {
  foo.push(i);
}
```

[Answer](https://stackoverflow.com/questions/3746725/how-to-create-an-array-containing-1-n)

### 15. How to extend an existing JavaScript array with another array, without creating a new array?

```javascript
// Input
const a = [1, 2, 3];
const b = [5, 4, 3];

// Output
console.log(a); // [1, 2, 3, 5, 4, 3];
```

[Answer](https://stackoverflow.com/questions/1374126/how-to-extend-an-existing-javascript-array-with-another-array-without-creating)

### 16. How to append something to an array?

```javascript
// Input
const array = ["Hi", "Hello", "Bonjour"];

// Output
console.log(array); // ["Hi", "Hello", "Bonjour", "Hola"];
```

[Answer](https://stackoverflow.com/questions/351409/how-to-append-something-to-an-array)

### 17. How do I empty an array in JavaScript?

```javascript
// Input
const array = [1, 2, 3, 4, 5];

// Output
console.log(array); // [];
```

[Answer](https://stackoverflow.com/questions/1232040/how-do-i-empty-an-array-in-javascript)

### 18. Find the min/max element of an array in JavaScript

```javascript
// Input
const array = [100, 0, 10, 50, 20];

// Output
array.min(); //=> 0
array.max(); //=> 100
```

[Answer](https://stackoverflow.com/questions/1669190/find-the-min-max-element-of-an-array-in-javascript)

### 19. Remove empty elements from an array in Javascript

```javascript
// Input
const array = [1, 2, , 3, , -3, null, , 0, , undefined, 4, , 4, , 5, , 6, , , ,];

// Output
console.log(array); // [1, 2, 3, -3, 4, 4, 5, 6]
```

[Answer](https://stackoverflow.com/questions/281264/remove-empty-elements-from-an-array-in-javascript)

### 20. Merge/flatten an array of arrays

```javascript
// Input
const array = [["$6"], ["$12"], ["$25"], ["$25"], ["$18"], ["$22"], ["$10"]];

// Output
console.log(array); // ["$6", "$12", "$25", ...]
```

[Answer](https://stackoverflow.com/questions/10865025/merge-flatten-an-array-of-arrays)

### 21. Getting a random value from a JavaScript array

```javascript
// Input
const array = ["January", "February", "March", "April", "May", "June", "July"];

// Output
console.log(array); // ["February"] ...
```

[Answer](https://stackoverflow.com/questions/4550505/getting-a-random-value-from-a-javascript-array)

[Sell Also](https://stackoverflow.com/questions/5915096/get-a-random-item-from-a-javascript-array)

### 22. Copy array by value

```javascript
const arr1 = ["a", "b", "c"];
const arr2 = arr1;
arr2.push("d"); // Now, arr1 = ['a','b','c','d']
```

[Answer](https://stackoverflow.com/questions/7486085/copy-array-by-value)

### 23. How can I add a key/value pair to a JavaScript object?

```javascript
// Input
const obj = { key1: value1, key2: value2 };

// Output
const obj = { key1: value1, key2: value2, key3: value3 };
```

[Answer](https://stackoverflow.com/questions/1168807/how-can-i-add-a-key-value-pair-to-a-javascript-object/1168814#1168814)

### 24. How do I test for an empty JavaScript object?

```javascript
const a = {};
```

[Answer](https://stackoverflow.com/questions/679915/how-do-i-test-for-an-empty-javascript-object/32108184#32108184)

### 25. Get the last item in an array

```javascript
// Input
const array = ["a", "b", "c", "d"];

// Output
console.log(array); // "d"
```

[Answer](https://stackoverflow.com/questions/3216013/get-the-last-item-in-an-array)

[Sell Also](https://stackoverflow.com/questions/9050345/selecting-last-element-in-javascript-array)

### 26. How can I create a two dimensional array in JavaScript?

[Answer](https://stackoverflow.com/questions/966225/how-can-i-create-a-two-dimensional-array-in-javascript)

### 27. From an array of objects, extract value of a property as array

```javascript
// Input
const objArray = [
  { foo: 1, bar: 2 },
  { foo: 3, bar: 4 },
  { foo: 5, bar: 6 },
];

// Output
console.log(objArray); // [ 1, 3, 5 ]
```

[Answer](https://stackoverflow.com/questions/19590865/from-an-array-of-objects-extract-value-of-a-property-as-array)

### 28. Copy array items into another array

```javascript
// Input
var arrayA = [1, 2];
var arrayB = [3, 4];

// Output
console.log(newArray); // [ 1, 2, 3, 4 ]
```

[Answer](https://stackoverflow.com/questions/4156101/copy-array-items-into-another-array)

### 29. Why is using "for...in" for array iteration a bad idea?

```javascript
// Why not use with arrays
for...in
```

[Answer](https://stackoverflow.com/questions/500504/why-is-using-for-in-for-array-iteration-a-bad-idea)

### 30. Deleting array elements in JavaScript - delete vs splice

```javascript
// Why not use with arrays
const array = ["a", "b", "c", "d"];

delete array[1];
//  or
array.splice(1, 1);
```

[Answer](https://stackoverflow.com/questions/500606/deleting-array-elements-in-javascript-delete-vs-splice)

### 31. Simplest code for array intersection in javascript

```javascript
// Input
const array1 = [1, 2, 3, 4, 5];
const array2 = [3, 4, 5, 6, 7];

// Output
[3, 4, 5];
```

[Answer](https://stackoverflow.com/questions/1885557/simplest-code-for-array-intersection-in-javascript)

### 32. How to determine if a JavaScript array contains an object with an attribute that equals a given value

```javascript
// Check id 21 exists in array
const array = [
  {
    id: 21,
    label: "Banana",
  },
  {
    id: 22,
    label: "Apple",
  }, // ....
];

// Output
true or false
```

[Answer](https://stackoverflow.com/questions/8217419/how-to-determine-if-a-javascript-array-contains-an-object-with-an-attribute-that)

### 33. How to compare arrays in JavaScript?

```javascript
var a1 = [1, 2, 3];
var a2 = [1, 2, 3];
console.log(a1 == a2); // Returns false
console.log(JSON.stringify(a1) == JSON.stringify(a2)); // Returns true
```

[Answer](https://stackoverflow.com/questions/7837456/how-to-compare-arrays-in-javascript)

### 34. Split array into chunks

```javascript
// Input
const array = ["a", "b", "c", "d", "e"];

// Output
[["a", "b"], ["c", "d"], ["e"]];
```

[Answer](https://stackoverflow.com/questions/8495687/split-array-into-chunks)

### 35. Most efficient way to create a zero filled JavaScript array?

```javascript
// Output
[0, 0, 0, 0, 0];
```

[Answer](https://stackoverflow.com/questions/1295584/most-efficient-way-to-create-a-zero-filled-javascript-array)

### 36. Check if an array contains any element of another array in JavaScript

```javascript
// Target Array
["apple", "banana", "orange"];

// Check if other arrays contain any one of the target array elements.

["apple","grape"] //returns true;
.
["apple","banana","pineapple"] //returns true;

["grape", "pineapple"] //returns false;
```

[Answer](https://stackoverflow.com/questions/16312528/check-if-an-array-contains-any-element-of-another-array-in-javascript)

### 37. What’s the difference between "Array()" and "[]" while declaring a JavaScript array?

```javascript
var myArray = new Array();

// And
var myArray = [];
```

[Answer](https://stackoverflow.com/questions/931872/what-s-the-difference-between-array-and-while-declaring-a-javascript-ar)

### 38. How to get the difference between two arrays in JavaScript?

```javascript
var array1 = ["a", "b"];
var array2 = ["a", "b", "c", "d"];

// need ["c", "d"]
```

[Answer](https://stackoverflow.com/questions/1187518/how-to-get-the-difference-between-two-arrays-in-javascript)

### 39. JavaScript set object key by variable

```javascript
// Input
var key = "name";
var person = {};

// Output
console.log(person); // {"name" : "John"}
```

[Answer](https://stackoverflow.com/questions/11508463/javascript-set-object-key-by-variable)

### 40. Get JavaScript object from array of objects by value of property

```javascript
// Input
var array = [
  { id: 1, name: "John" },
  { id: 2, name: "Jane" },
  { id: 3, name: "Doe" },
];

// Output
{ id: 2, name: 'Jane' },
```

[Answer](https://stackoverflow.com/questions/13964155/get-javascript-object-from-array-of-objects-by-value-of-property)

### 41. How to export JavaScript array info to csv (on client side)?

```javascript
const rows = [
  ["name1", "city1", "some other info"],
  ["name2", "city2", "more info"],
];
```

[Answer](https://stackoverflow.com/questions/14964035/how-to-export-javascript-array-info-to-csv-on-client-side)

### 42. How to store objects in HTML5 localStorage/sessionStorage

```javascript
var testObject = { one: 1, two: 2, three: 3 };
```

[Answer](https://stackoverflow.com/questions/2010892/how-to-store-objects-in-html5-localstorage-sessionstorage)

### 43. Best way to find if an item is in a JavaScript array?

```javascript
// Input
const array = [1, 2, 3, 4, 5];
const itemToFind = 3;

//Output: true
```

[Answer](https://stackoverflow.com/questions/143847/best-way-to-find-if-an-item-is-in-a-javascript-array)

### 44. How to initialize an array's length in JavaScript?

[Answer](https://stackoverflow.com/questions/4852017/how-to-initialize-an-arrays-length-in-javascript)

### 45. Easy way to turn JavaScript array into comma-separated list?

```javascript
// Input
const array = [1, 2, 3, 4, 5];

//Output
1, 2, 3, 4, 5;
```

[Answer](https://stackoverflow.com/questions/201724/easy-way-to-turn-javascript-array-into-comma-separated-list)

### 50. Fastest way to duplicate an array in JavaScript - slice vs. 'for' loop

```javascript
// Input
const originalArray = [1, 2, 3, 4, 5];
const duplicatedArray = [];

//Output
console.log(duplicatedArray); // [1, 2, 3, 4, 5];
```
