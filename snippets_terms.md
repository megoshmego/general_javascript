
1. `alert()`: Displays an alert box with a message and an OK button.
```javascript
alert("Hello, world!");
```

1. `prompt()`: Displays a dialog box that prompts the visitor for input.
```javascript
let name = prompt("What's your name?");
console.log(name);
```

1. `console.log()`: Outputs a message to the web console.
```javascript
console.log("Hello, world!");
```

1. `parseInt()`: Converts a string to an integer.
```javascript
let str = "123";
let num = parseInt(str);
console.log(num); // Output: 123
```

1. `parseFloat()`: Converts a string to a floating-point number.
```javascript
let str = "123.45";
let num = parseFloat(str);
console.log(num); // Output: 123.45
```

1. `isNaN()`: Determines whether a value is an illegal number.
```javascript
console.log(isNaN(123)); // Output: false
console.log(isNaN('Hello')); // Output: true
```

1. `isFinite()`: Determines whether a value is a finite, legal number.
```javascript
console.log(isFinite(123)); // Output: true
console.log(isFinite(Infinity)); // Output: false
```

1. `Number()`: Converts an object's value to a number.
```javascript
let bool = true;
console.log(Number(bool)); // Output: 1
```

1. `String()`: Converts an object's value to a string.
```javascript
let num = 123;
console.log(String(num)); // Output: "123"
```

1.  `Boolean()`: Converts an object's value to a boolean.
```javascript
let str = "Hello";
console.log(Boolean(str)); // Output: true
```

1.  `encodeURI()`: Encodes a URI.
```javascript
let uri = "https://www.example.com/?hello=world";
console.log(encodeURI(uri)); // Output: "https://www.example.com/?hello=world"
```

1.  `decodeURI()`: Decodes a URI.
```javascript
let uri = "https://www.example.com/?hello=world";
console.log(decodeURI(uri)); // Output: "https://www.example.com/?hello=world"
```

1.  `encodeURIComponent()`: Encodes a URI component.
```javascript
let uriComponent = "hello world";
console.log(encodeURIComponent(uriComponent)); // Output: "hello%20world"
```

1.  `decodeURIComponent()`: Decodes a URI component.
```javascript
let uriComponent = "hello%20world";
console.log(decodeURIComponent(uriComponent)); // Output: "hello world"
```

1.  `eval()`: Evaluates a string of JavaScript code.
```javascript
let str = "console.log('Hello, world!')";
eval(str); // Output: "Hello, world!"
```

1.  `Array.isArray()`: Determines whether the passed value is an array.
```javascript
let arr = [1, 2, 3];
console.log(Array.isArray(arr)); // Output: true
```

1.  `Array.from()`: Creates a new array instance from an array-like or iterable object.
```javascript
let str = "Hello";
console.log(Array.from(str)); // Output: ["H", "e", "l", "l", "o"]
```

1.  `Array.of()`: Creates a new array instance with a variable number of arguments.
```javascript
console.log(Array.of(1, 2, 3)); // Output: [1,

 2, 3]
```

19. `Array.prototype.push()`: Adds one or more elements to the end of an array.
```javascript
let arr = [1, 2, 3];
arr.push(4);
console.log(arr); // Output: [1, 2, 3, 4]
```

20. `Array.prototype.pop()`: Removes the last element from an array.
```javascript
let arr = [1, 2, 3];
arr.pop();
console.log(arr); // Output: [1, 2]
```

21. `Array.prototype.shift()`: Removes the first element from an array.
```javascript
let arr = [1, 2, 3];
arr.shift();
console.log(arr); // Output: [2, 3]
```

22. `Array.prototype.unshift()`: Adds one or more elements to the beginning of an array.
```javascript
let arr = [1, 2, 3];
arr.unshift(0);
console.log(arr); // Output: [0, 1, 2, 3]
```

23. `Array.prototype.concat()`: Merges two or more arrays.
```javascript
let arr1 = [1, 2, 3];
let arr2 = [4, 5, 6];
console.log(arr1.concat(arr2)); // Output: [1, 2, 3, 4, 5, 6]
```

24. `Array.prototype.join()`: Joins all elements of an array into a string.
```javascript
let arr = ["Hello", "world!"];
console.log(arr.join(" ")); // Output: "Hello world!"
```

25. `Array.prototype.slice()`: Returns a shallow copy of a portion of an array.
```javascript
let arr = [1, 2, 3, 4, 5];
console.log(arr.slice(1, 3)); // Output: [2, 3]
```


Sure, here are examples for the methods you listed:

26. `Array.prototype.splice()`: Changes the contents of an array by removing or replacing existing elements.
```javascript
let arr = [1, 2, 3, 4, 5];
arr.splice(2, 1, 'a'); // Start at index 2, remove 1 element and add 'a'
console.log(arr); // Output: [1, 2, 'a', 4, 5]
```

27. `Array.prototype.map()`: Creates a new array with the results of calling a provided function on every element.
```javascript
let arr = [1, 2, 3];
let newArr = arr.map(x => x * 2); // Multiply each element by 2
console.log(newArr); // Output: [2, 4, 6]
```

28. `Array.prototype.filter()`: Creates a new array with all elements that pass the test implemented by the provided function.
```javascript
let arr = [1, 2, 3, 4, 5];
let newArr = arr.filter(x => x > 3); // Keep elements greater than 3
console.log(newArr); // Output: [4, 5]
```

29. `Array.prototype.reduce()`: Executes a reducer function on each element of the array, resulting in a single output value.
```javascript
let arr = [1, 2, 3, 4, 5];
let sum = arr.reduce((a, b) => a + b); // Sum all elements
console.log(sum); // Output: 15
```

30. `Array.prototype.find()`: Returns the value of the first element in the provided array that satisfies the provided testing function.
```javascript
let arr = [1, 2, 3, 4, 5];
let found = arr.find(x => x > 3); // Find first element greater than 3
console.log(found); // Output: 4
```

31. `Array.prototype.findIndex()`: Returns the index of the first element in the array that satisfies the provided testing function.
```javascript
let arr = [1, 2, 3, 4, 5];
let index = arr.findIndex(x => x > 3); // Find index of first element greater than 3
console.log(index); // Output: 3
```

32. `Array.prototype.includes()`: Determines whether an array includes a certain value.
```javascript
let arr = [1, 2, 3, 4, 5];
console.log(arr.includes(3)); // Output: true
console.log(arr.includes(6)); // Output: false
```

33. `Array.prototype.indexOf()`: Returns the first index at which a given element can be found in the array.
```javascript
let arr = [1, 2, 3, 4, 5];
console.log(arr.indexOf(3)); // Output: 2
```

34. `Array.prototype.lastIndexOf()`: Returns the last index at which a given element can be found in the array.
```javascript
let arr = [1, 2, 3, 2, 1];
console.log(arr.lastIndexOf(2)); // Output: 3
```

35. `Array.prototype.every()`: Tests whether all elements in the array pass the test implemented by the provided function.
```javascript
let arr = [1, 2, 3, 4, 5];
console.log(arr.every(x => x > 0)); // Output: true
```

36. `Array.prototype.some()`: Tests whether at least one element in the

 array passes the test implemented by the provided function.
```javascript
let arr = [1, 2, 3, 4, 5];
console.log(arr.some(x => x > 4)); // Output: true
```

37. `Array.prototype.sort()`: Sorts the elements of an array in place and returns the array.
```javascript
let arr = [5, 1, 4, 2, 3];
arr.sort();
console.log(arr); // Output: [1, 2, 3, 4, 5]
```

38. `Array.prototype.reverse()`: Reverses the order of the elements of an array.
```javascript
let arr = [1, 2, 3, 4, 5];
arr.reverse();
console.log(arr); // Output: [5, 4, 3, 2, 1]
```

39. `Array.prototype.fill()`: Changes all elements in an array to a static value, from a start index to an end index.
```javascript
let arr = [1, 2, 3, 4, 5];
arr.fill('a', 1, 3); // Fill array with 'a' from index 1 to 3
console.log(arr); // Output: [1, 'a', 'a', 4, 5]
```

40. `Array.prototype.copyWithin()`: Shallow copies part of an array to another location in the same array and returns it, without modifying its size.
```javascript
let arr = [1, 2, 3, 4, 5];
arr.copyWithin(0, 3); // Copy elements from index 3 to index 0
console.log(arr); // Output: [4, 5, 3, 4, 5]
```

Sure! Here are examples of how you might use these methods:

41. `Date.now()`: Returns the number of milliseconds elapsed since January 1, 1970 00:00:00 UTC.
```javascript
console.log(Date.now()); // Output: 1673001783311
```

42. `Date.prototype.getDate()`: Returns the day of the month (from 1-31) for the specified date.
```javascript
let date = new Date();
console.log(date.getDate()); // Output: current day of the month
```

43. `Date.prototype.getDay()`: Returns the day of the week (from 0-6) for the specified date.
```javascript
let date = new Date();
console.log(date.getDay()); // Output: current day of the week
```

44. `Date.prototype.getFullYear()`: Returns the year of the specified date according to local time.
```javascript
let date = new Date();
console.log(date.getFullYear()); // Output: current year
```

45. `Date.prototype.getHours()`: Returns the hour (from 0-23) in the specified date according to local time.
```javascript
let date = new Date();
console.log(date.getHours()); // Output: current hour
```

46. `Date.prototype.getMinutes()`: Returns the minutes (from 0-59) in the specified date according to local time.
```javascript
let date = new Date();
console.log(date.getMinutes()); // Output: current minute
```

47. `Date.prototype.getSeconds()`: Returns the seconds (from 0-59) in the specified date according to local time.
```javascript
let date = new Date();
console.log(date.getSeconds()); // Output: current second
```

48. `Date.prototype.setTime()`: Sets the Date object to the time represented by a number of milliseconds since January 1, 1970, 00:00:00 UTC.
```javascript
let date = new Date();
date.setTime(1673001783311);
console.log(date); // Output: the date and time represented by 1673001783311
```

49. `Date.prototype.toISOString()`: Returns a string in simplified extended ISO format (ISO 8601), which is always 24 or 27 characters long (YYYY-MM-DDTHH:mm:ss.sssZ or ±YYYYYY-MM-DDTHH:mm:ss.sssZ, respectively).
```javascript
let date = new Date();
console.log(date.toISOString()); // Output: current date and time in ISO format
```

50. `Date.prototype.toLocaleDateString()`: Returns a string with a language sensitive representation of the date portion of this date.
```javascript
let date = new Date();
console.log(date.toLocaleDateString()); // Output: current date in local format
```

51. `Math.round()`: Returns the value of a number rounded to the nearest integer.
```javascript
console.log(Math.round(5.4)); // Output: 5
```

52. `Math.floor()`: Returns the largest integer less than or equal to a given number.
```javascript
console.log(Math.floor(5.9)); // Output: 5
```

53. `Math.ceil()`: Returns the smallest integer greater than or equal to a given number.
```javascript
console.log(Math.ceil(5.1)); // Output: 6
```

54. `Math.random()`: Returns a floating-point, pseudo-random number in the range 0–1 (inclusive of 0, but not 1) with approximately uniform distribution over that range.
```javascript
console.log(Math.random()); // Output: random number between 0 and 1
```

55. `Math.abs()`: Returns the absolute value of a number.


```javascript
console.log(Math.abs(-5)); // Output: 5
```

56. `Math.pow()`: Returns the base to the exponent power, that is, base^exponent.
```javascript
console.log(Math.pow(2, 3)); // Output: 8
```

57. `Math.sqrt()`: Returns the square root of a number.
```javascript
console.log(Math.sqrt(16)); // Output: 4
```

58. `Math.min()`: Returns the smallest of zero or more numbers.
```javascript
console.log(Math.min(5, 1, 4, 2, 3)); // Output: 1
```

59. `Math.max()`: Returns the largest of zero or more numbers.
```javascript
console.log(Math.max(5, 1, 4, 2, 3)); // Output: 5
```

60. `Math.PI`: Represents the ratio of the circumference of a circle to its diameter, approximately 3.14159.
```javascript
console.log(Math.PI); // Output: 3.141592653589793
```


Sure, here are some examples:

61. `String.prototype.toUpperCase()`: Converts a string to uppercase letters.
```javascript
console.log('hello world'.toUpperCase()); // Output: HELLO WORLD
```

62. `String.prototype.toLowerCase()`: Converts a string to lowercase letters.
```javascript
console.log('HELLO WORLD'.toLowerCase()); // Output: hello world
```

63. `String.prototype.charAt()`: Returns the character at the specified index in a string.
```javascript
console.log('hello'.charAt(1)); // Output: e
```

64. `String.prototype.charCodeAt()`: Returns a number that is the UTF-16 code unit value at the given index.
```javascript
console.log('hello'.charCodeAt(1)); // Output: 101
```

65. `String.prototype.concat()`: Concatenates the string arguments to the calling string and returns a new string.
```javascript
console.log('hello'.concat(' world')); // Output: hello world
```

66. `String.prototype.includes()`: Determines whether one string may be found within another string, returning true or false as appropriate.
```javascript
console.log('hello world'.includes('world')); // Output: true
```

67. `String.prototype.indexOf()`: Returns the index within the calling String object of the first occurrence of the specified value, or -1 if not found.
```javascript
console.log('hello world'.indexOf('world')); // Output: 6
```

68. `String.prototype.lastIndexOf()`: Returns the index within the calling String object of the last occurrence of the specified value, or -1 if not found.
```javascript
console.log('hello world world'.lastIndexOf('world')); // Output: 12
```

69. `String.prototype.repeat()`: Constructs and returns a new string which contains the specified number of copies of the string on which it was called, concatenated together.
```javascript
console.log('hello '.repeat(3)); // Output: hello hello hello 
```

70. `String.prototype.replace()`: Returns a new string with some or all matches of a pattern replaced by a replacement.
```javascript
console.log('hello world'.replace('world', 'everyone')); // Output: hello everyone
```

71. `String.prototype.search()`: Executes a search for a match between a regular expression and this String object.
```javascript
console.log('hello world'.search(/world/)); // Output: 6
```

72. `String.prototype.slice()`: Extracts a section of a string and returns it as a new string, without modifying the original string.
```javascript
console.log('hello world'.slice(0, 5)); // Output: hello
```

73. `String.prototype.split()`: Splits a String object into an array of string by separating the string into substrings, using a specified separator string to determine where to make each split.
```javascript
console.log('hello world'.split(' ')); // Output: ["hello", "world"]
```

74. `String.prototype.trim()`: Trims whitespace from the beginning and end of the string. Part of the ECMAScript 5 standard.
```javascript
console.log('   hello world   '.trim()); // Output: "hello world"
```

75. `RegExp.prototype.test()`: Executes a search for a match between a regular expression and a specified string. Returns true or false.
```javascript
console.log(/world/.test('hello world')); // Output: true
```

76. `RegExp.prototype.exec()`: Executes a search for a match in a specified string. Returns a result array, or null.
```javascript
console.log(/world/.exec('hello world')); // Output: ["world

", index: 6, input: "hello world", groups: undefined]
```

77. `JSON.stringify()`: Converts a JavaScript value to a JavaScript Object Notation (JSON) string.
```javascript
console.log(JSON.stringify({ hello: 'world' })); // Output: '{"hello":"world"}'
```

78. `JSON.parse()`: Parses a JSON string, constructing the JavaScript value or object described by the string.
```javascript
console.log(JSON.parse('{"hello":"world"}')); // Output: {hello: "world"}
```

79. `Function.prototype.bind()`: Creates a new function that, when called, has its this keyword set to the provided value, with a given sequence of arguments preceding any provided when the new function is called.
```javascript
const obj = { x: 42 };
const getX = function() { return this.x; };
const boundGetX = getX.bind(obj);
console.log(boundGetX()); // Output: 42
```


Sure, here are examples for the next set of JavaScript concepts:

80. `Function.prototype.call()`: Calls a function with a given this value and arguments provided individually.
```javascript
function greet(msg, lang) { console.log(`${msg} from ${lang}`); }
greet.call(null, 'Hello', 'JavaScript'); // Output: Hello from JavaScript
```

81. `Function.prototype.apply()`: Calls a function with a given this value, and arguments provided as an array (or an array-like object).
```javascript
function greet(msg, lang) { console.log(`${msg} from ${lang}`); }
greet.apply(null, ['Hello', 'JavaScript']); // Output: Hello from JavaScript
```

82. `Object.prototype.hasOwnProperty()`: Returns a boolean indicating whether the object has the specified property as its own property (as opposed to inheriting it).
```javascript
let obj = { greeting: 'Hello' };
console.log(obj.hasOwnProperty('greeting')); // Output: true
```

83. `Object.prototype.isPrototypeOf()`: Tests for an object in another object's prototype chain.
```javascript
let obj1 = {};
let obj2 = Object.create(obj1);
console.log(obj1.isPrototypeOf(obj2)); // Output: true
```

84. `Object.prototype.propertyIsEnumerable()`: Returns a Boolean indicating whether the specified property is enumerable and is the object's own property.
```javascript
let obj = { greeting: 'Hello' };
console.log(obj.propertyIsEnumerable('greeting')); // Output: true
```

85. `Object.keys()`: Returns an array of a given object's own enumerable property names, iterated in the same order that a normal loop would.
```javascript
let obj = { greeting: 'Hello', language: 'JavaScript' };
console.log(Object.keys(obj)); // Output: ["greeting", "language"]
```

86. `Object.values()`: Returns an array of a given object's own enumerable property values, in the same order as that provided by a `for...in` loop.
```javascript
let obj = { greeting: 'Hello', language: 'JavaScript' };
console.log(Object.values(obj)); // Output: ["Hello", "JavaScript"]
```

87. `Object.entries()`: Returns an array of a given object's own enumerable string-keyed property `[key, value]` pairs.
```javascript
let obj = { greeting: 'Hello', language: 'JavaScript' };
console.log(Object.entries(obj)); // Output: [["greeting", "Hello"], ["language", "JavaScript"]]
```

88. `Object.assign()`: Copies the values of all enumerable own properties from one or more source objects to a target object. It will return the target object.
```javascript
let obj = { greeting: 'Hello' };
let newObj = Object.assign({}, obj, { language: 'JavaScript' });
console.log(newObj); // Output: { greeting: 'Hello', language: 'JavaScript' }
```

89. `Object.create()`: Creates a new object, using an existing object as the prototype of the newly created object.
```javascript
let obj = { greeting: 'Hello' };
let newObj = Object.create(obj);
console.log(newObj.greeting); // Output: Hello
```

90. `Object.freeze()`: Freezes an object: other code can't delete or change any properties.
```javascript
let obj = { greeting: 'Hello' };
Object.freeze(obj);
obj.greeting = 'Hi'; // this will have no effect
console.log(obj.greeting); // Output: Hello
```

91. `Object.seal()`: Prevents other code from deleting properties and makes all existing properties non-configurable. Values can still be changed as long as they

 are writable.
```javascript
let obj = { greeting: 'Hello' };
Object.seal(obj);
obj.greeting = 'Hi'; // this will work
delete obj.greeting; // this will have no effect
console.log(obj.greeting); // Output: Hi
```

92. `Number.isNaN()`: Determines whether the passed value is NaN and its type is Number. More reliable than the original global `isNaN()`.
```javascript
console.log(Number.isNaN(NaN)); // Output: true
```

93. `Number.isInteger()`: Determines whether the passed value is an integer.
```javascript
console.log(Number.isInteger(42)); // Output: true
```

94. `Number.parseFloat()`: Parses an argument and returns a floating point number.
```javascript
console.log(Number.parseFloat('42.42')); // Output: 42.42
```

95. `Number.parseInt()`: Parses a string argument and returns an integer.
```javascript
console.log(Number.parseInt('42')); // Output: 42
```

96. `Promise.prototype.then()`: Returns a Promiseents: callback functions for the success and failure cases of the Promise.
```javascript
let p = Promise.resolve('Hello Promise');
p.then(value => console.log(value)); // Output: Hello Promise
```

97. `Promise.prototype.catch()`: Appends a rejection handler callback to the promise, and returns a new promise resolving to the return value of the callback if it is called, or to its original fulfillment value if the promise is instead fulfilled.
```javascript
let p = Promise.reject('Promise failed');
p.catch(reason => console.log(reason)); // Output: Promise failed
```

98. `Promise.prototype.finally()`: Appends a handler to the promise, and returns a new promise that is resolved when the original promise is resolved. The handler is called when the promise is settled, whether fulfilled or rejected.
```javascript
let p = Promise.resolve('Hello Promise');
p.finally(() => console.log('Promise settled')); // Output: Promise settled
```

99. `Promise.all()`: Returns a promise that either fulfills when all of the promises in an iterable have fulfilled or rejects as soon as one of the promises in the iterable rejects.
```javascript
let p1 = Promise.resolve('Hello');
let p2 = Promise.resolve('Promise');
Promise.all([p1, p2]).then(values => console.log(values)); // Output: ["Hello", "Promise"]
```

100. `Promise.race()`: Returns a promise that fulfills or rejects as soon as one of the promises in an iterable fulfills or rejects, with the value from that promise.
```javascript
let p1 = Promise.resolve('Hello');
let p2 = new Promise((resolve, reject) => setTimeout(reject, 100, 'Promise'));
Promise.race([p1, p2]).then(value => console.log(value)); // Output: Hello
```

Sure, here are examples for the next set of JavaScript concepts:

101. `push()`: Adds new items to the end of an array, and returns the new length.
```javascript
let arr = ['Hello'];
arr.push('JavaScript');
console.log(arr); // Output: ['Hello', 'JavaScript']
```

102. `pop()`: Removes the last element from an array and returns that element.
```javascript
let arr = ['Hello', 'JavaScript'];
arr.pop();
console.log(arr); // Output: ['Hello']
```

103. `shift()`: Removes the first item of an array.
```javascript
let arr = ['Hello', 'JavaScript'];
arr.shift();
console.log(arr); // Output: ['JavaScript']
```

104. `unshift()`: Adds new items to the beginning of an array, and returns the new length.
```javascript
let arr = ['Hello'];
arr.unshift('JavaScript');
console.log(arr); // Output: ['JavaScript', 'Hello']
```

105. `concat()`: Joins two or more arrays, and returns a copy of the joined arrays.
```javascript
let arr1 = ['Hello'];
let arr2 = ['JavaScript'];
let arr3 = arr1.concat(arr2);
console.log(arr3); // Output: ['Hello', 'JavaScript']
```

106. `join()`: Joins all elements of an array into a string.
```javascript
let arr = ['Hello', 'JavaScript'];
console.log(arr.join(' ')); // Output: 'Hello JavaScript'
```

107. `slice()`: Selects a part of an array, and returns the new array.
```javascript
let arr = ['Hello', 'JavaScript', 'How', 'Are', 'You'];
console.log(arr.slice(1, 3)); // Output: ['JavaScript', 'How']
```

108. `splice()`: Adds/Removes items to/from an array, and returns the removed item(s).
```javascript
let arr = ['Hello', 'JavaScript', 'How', 'Are', 'You'];
arr.splice(2, 0, 'Good');
console.log(arr); // Output: ['Hello', 'JavaScript', 'Good', 'How', 'Are', 'You']
```

109. `indexOf()`: Search the array for an element and returns its position.
```javascript
let arr = ['Hello', 'JavaScript', 'How', 'Are', 'You'];
console.log(arr.indexOf('JavaScript')); // Output: 1
```

110. `lastIndexOf()`: Search the array for an element, starting at the end, and returns its position.
```javascript
let arr = ['Hello', 'JavaScript', 'How', 'Are', 'JavaScript', 'You'];
console.log(arr.lastIndexOf('JavaScript')); // Output: 4
```

111. `forEach()`: Calls a function for each array element.
```javascript
let arr = ['Hello', 'JavaScript'];
arr.forEach(item => console.log(item)); // Output: Hello JavaScript
```

112. `map()`: Creates a new array with the result of calling a function for each array element.
```javascript
let arr = [1, 2, 3, 4];
let newArr = arr.map(item => item * 2);
console.log(newArr); // Output: [2, 4, 6, 8]
```

113. `filter()`: Creates a new array with every element in an array that pass a test.
```javascript
let arr = [1, 2, 3, 4];
let newArr = arr.filter(item => item > 2);
console.log(newArr); // Output: [3, 4]
```

114. `reduce()`: Reduce the values of an array

 to a single value (going left-to-right).
```javascript
let arr = [1, 2, 3, 4];
let result = arr.reduce((total, value) => total + value);
console.log(result); // Output: 10
```

115. `reduceRight()`: Reduce the values of an array to a single value (going right-to-left).
```javascript
let arr = [1, 2, 3, 4];
let result = arr.reduceRight((total, value) => total - value);
console.log(result); // Output: -2
```



Sure, here are examples for the next set of JavaScript Array methods:

116. `some()`: Check if some array values pass a test.
```javascript
let arr = [1, 2, 3, 4];
let result = arr.some(item => item > 2);
console.log(result); // Output: true
```

117. `every()`: Check if all array values pass a test.
```javascript
let arr = [1, 2, 3, 4];
let result = arr.every(item => item > 0);
console.log(result); // Output: true
```

118. `find()`: Returns the value of the first element in an array that pass a test.
```javascript
let arr = [1, 2, 3, 4];
let result = arr.find(item => item > 2);
console.log(result); // Output: 3
```

119. `findIndex()`: Returns the index of the first element in an array that pass a test.
```javascript
let arr = [1, 2, 3, 4];
let result = arr.findIndex(item => item > 2);
console.log(result); // Output: 2
```

120. `includes()`: Check if an array contains the specified item.
```javascript
let arr = [1, 2, 3, 4];
let result = arr.includes(2);
console.log(result); // Output: true
```

121. `sort()`: Sorts the elements of an array.
```javascript
let arr = [1, 3, 2, 4];
arr.sort();
console.log(arr); // Output: [1, 2, 3, 4]
```

122. `reverse()`: Reverses the order of the elements in an array.
```javascript
let arr = [1, 2, 3, 4];
arr.reverse();
console.log(arr); // Output: [4, 3, 2, 1]
```

123. `fill()`: Fill the elements in an array with a static value.
```javascript
let arr = [1, 2, 3, 4];
arr.fill(0);
console.log(arr); // Output: [0, 0, 0, 0]
```

124. `copyWithin()`: Copies array elements within the array, to and from specified positions.
```javascript
let arr = [1, 2, 3, 4];
arr.copyWithin(0, 2, 4);
console.log(arr); // Output: [3, 4, 3, 4]
```

125. `entries()`: Returns a key/value pair Array Iteration Object.
```javascript
let arr = ['a', 'b', 'c'];
let iterator = arr.entries();
console.log(iterator.next().value); // Output: [0, 'a']
```

126. `keys()`: Returns a Array Iteration Object, containing the keys of the original array.
```javascript
let arr = ['a', 'b', 'c'];
let iterator = arr.keys();
console.log(iterator.next().value); // Output: 0
```

127. `values()`: Returns a Array Iteration Object, containing the values of the original array.
```javascript
let arr = ['a', 'b', 'c'];
let iterator = arr.values();
console.log(iterator.next().value); // Output: 'a'
```