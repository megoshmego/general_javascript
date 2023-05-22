Sure, here you go:

1. `alert()`
```javascript
alert("Hello, world!");
```
2. `prompt()`
```javascript
let name = prompt("What's your name?");
console.log(name);
```
3. `console.log()`
```javascript
console.log("Hello, world!");
```
4. `parseInt()`
```javascript
let str = "123";
let num = parseInt(str);
console.log(num);
```
5. `parseFloat()`
```javascript
let str = "123.45";
let num = parseFloat(str);
console.log(num);
```
6. `isNaN()`
```javascript
console.log(isNaN(123));
console.log(isNaN('Hello'));
```
7. `isFinite()`
```javascript
console.log(isFinite(123));
console.log(isFinite(Infinity));
```
8. `Number()`
```javascript
let bool = true;
console.log(Number(bool));
```
9. `String()`
```javascript
let num = 123;
console.log(String(num));
```
10. `Boolean()`
```javascript
let str = "Hello";
console.log(Boolean(str));
```
11. `encodeURI()`
```javascript
let uri = "https://www.example.com/?hello=world";
console.log(encodeURI(uri));
```
12. `decodeURI()`
```javascript
let uri = "https://www.example.com/?hello=world";
console.log(decodeURI(uri));
```
13. `encodeURIComponent()`
```javascript
let uriComponent = "hello world";
console.log(encodeURIComponent(uriComponent));
```
14. `decodeURIComponent()`
```javascript
let uriComponent = "hello%20world";
console.log(decodeURIComponent(uriComponent));
```
15. `eval()`
```javascript
let str = "console.log('Hello, world!')";
eval(str);
```
16. `Array.isArray()`
```javascript
let arr = [1, 2, 3];
console.log(Array.isArray(arr));
```
17. `Array.from()`
```javascript
let str = "Hello";
console.log(Array.from(str));
```
18. `Array.of()`
```javascript
console.log(Array.of(1, 2, 3));
```
19. `Array.prototype.push()`
```javascript
let arr = [1, 2, 3];
arr.push(4);
console.log(arr);
```
20. `Array.prototype.pop()`
```javascript
let arr = [1, 2, 3];
arr.pop();
console.log(arr);
```
21. `Array.prototype.shift()`
```javascript
let arr = [1, 2, 3];
arr.shift();
console.log(arr);
```
22. `Array.prototype.unshift()`
```javascript
let arr = [1, 2, 3];
arr.unshift(0);
console.log(arr);
```
23. `Array.prototype.concat()`
```javascript
let arr1 = [1, 2, 3];
let arr2 = [4, 5, 6];
console.log(arr1.concat(arr2));
```
24. `Array.prototype.join()`
```javascript
let arr = ["Hello", "world!"];
console.log(arr.join(" "));
```
25. `Array.prototype.slice()`
```javascript
let arr = [1, 2, 3, 4, 5];
console.log(arr.slice(1, 3));
```
26. `Array.prototype.splice()`
```javascript
let arr = [1, 2, 3, 4, 5];
arr.splice(2, 1, 'a');
console.log(arr);
```
27. `Array.prototype.map

()`
```javascript
let arr = [1, 2, 3];
let newArr = arr.map(x => x * 2);
console.log(newArr);
```
28. `Array.prototype.filter()`
```javascript
let arr = [1, 2, 3, 4, 5];
let newArr = arr.filter(x => x > 3);
console.log(newArr);
```
29. `Array.prototype.reduce()`
```javascript
let arr = [1, 2, 3, 4, 5];
let sum = arr.reduce((a, b) => a + b);
console.log(sum);
```
30. `Array.prototype.find()`
```javascript
let arr = [1, 2, 3, 4, 5];
let found = arr.find(x => x > 3);
console.log(found);
```
31. `Array.prototype.findIndex()`
```javascript
let arr = [1, 2, 3, 4, 5];
let index = arr.findIndex(x => x > 3);
console.log(index);
```
32. `Array.prototype.includes()`
```javascript
let arr = [1, 2, 3, 4, 5];
console.log(arr.includes(3));
console.log(arr.includes(6));
```
33. `Array.prototype.indexOf()`
```javascript
let arr = [1, 2, 3, 4, 5];
console.log(arr.indexOf(3));
```
34. `Array.prototype.lastIndexOf()`
```javascript
let arr = [1, 2, 3, 2, 1];
console.log(arr.lastIndexOf(2));
```
35. `Array.prototype.every()`
```javascript
let arr = [1, 2, 3, 4, 5];
console.log(arr.every(x => x > 0));
```
36. `Array.prototype.some()`
```javascript
let arr = [1, 2, 3, 4, 5];
console.log(arr.some(x => x > 3));
```
37. `Array.prototype.sort()`
```javascript
let arr = [3, 1, 4, 1, 5, 9];
arr.sort((a, b) => a - b);
console.log(arr);
```
38. `Array.prototype.reverse()`
```javascript
let arr = [1, 2, 3, 4, 5];
arr.reverse();
console.log(arr);
```
39. `Array.prototype.fill()`
```javascript
let arr = new Array(5);
arr.fill('a');
console.log(arr);
```
40. `Array.prototype.copyWithin()`
```javascript
let arr = [1, 2, 3, 4, 5];
arr.copyWithin(0, 3);
console.log(arr);
```
Understood. Here are the examples you requested:

41. `Date.now()`
```javascript
console.log(Date.now());
```
42. `Date.prototype.getDate()`
```javascript
let date = new Date();
console.log(date.getDate());
```
43. `Date.prototype.getDay()`
```javascript
let date = new Date();
console.log(date.getDay());
```
44. `Date.prototype.getFullYear()`
```javascript
let date = new Date();
console.log(date.getFullYear());
```
45. `Date.prototype.getHours()`
```javascript
let date = new Date();
console.log(date.getHours());
```
46. `Date.prototype.getMinutes()`
```javascript
let date = new Date();
console.log(date.getMinutes());
```
47. `Date.prototype.getSeconds()`
```javascript
let date = new Date();
console.log(date.getSeconds());
```
48. `Date.prototype.setTime()`
```javascript
let date = new Date();
date.setTime(1673001783311);
console.log(date);
```
49. `Date.prototype.toISOString()`
```javascript
let date = new Date();
console.log(date.toISOString());
```
50. `Date.prototype.toLocaleDateString()`
```javascript
let date = new Date();
console.log(date.toLocaleDateString());
```
51. `Math.round()`
```javascript
console.log(Math.round(5.4));
```
52. `Math.floor()`
```javascript
console.log(Math.floor(5.9));
```
53. `Math.ceil()`
```javascript
console.log(Math.ceil(5.1));
```
54. `Math.random()`
```javascript
console.log(Math.random());
```
55. `Math.abs()`
```javascript
console.log(Math.abs(-5));
```
56. `Math.pow()`
```javascript
console.log(Math.pow(2, 3));
```
57. `Math.sqrt()`
```javascript
console.log(Math.sqrt(16));
```
58. `Math.min()`
```javascript
console.log(Math.min(5, 1, 4, 2, 3));
```
59. `Math.max()`
```javascript
console.log(Math.max(5, 1, 4, 2, 3));
```
60. `Math.PI`
```javascript
console.log(Math.PI);
```
61. `String.prototype.toUpperCase()`
```javascript
console.log('hello world'.toUpperCase());
```
62. `String.prototype.toLowerCase()`
```javascript
console.log('HELLO WORLD'.toLowerCase());
```
63. `String.prototype.charAt()`
```javascript
console.log('hello'.charAt(1));
```
64. `String.prototype.charCodeAt()`
```javascript
console.log('hello'.charCodeAt(1));
```
65. `String.prototype.concat()`
```javascript
console.log('hello'.concat(' world'));
```
66. `String.prototype.includes()`
```javascript
console.log('hello world'.includes('world'));
```
67. `String.prototype.indexOf()`
```javascript
console.log('hello world'.indexOf('world'));
```
68. `String.prototype.lastIndexOf()`
```javascript
console.log('hello world world'.lastIndexOf('world'));
```
69. `String.prototype.repeat()`
```javascript
console.log('hello '.repeat(3));
```
70. `String.prototype.replace()`
```javascript
console.log('hello world'.replace('world', 'everyone'));
```
71. `String.prototype.search()`
```javascript
console.log('hello world'.search(/world/));
```
72. `String.prototype.slice()`
```javascript
console.log('hello world'.slice(0, 5));
```
73. `String.prototype.split()`
```javascript
console.log('hello

 world'.split(' '));
```
74. `String.prototype.substr()`
```javascript
console.log('hello world'.substr(0, 5));
```
75. `String.prototype.substring()`
```javascript
console.log('hello world'.substring(0, 5));
```
76. `String.prototype.trim()`
```javascript
console.log(' hello world '.trim());
```
77. `String.prototype.valueOf()`
```javascript
console.log('hello world'.valueOf());
```

Sure, here are the examples of those methods and functions in JavaScript:

68. `String.prototype.lastIndexOf()`
```javascript
console.log('hello world world'.lastIndexOf('world'));
```
69. `String.prototype.repeat()`
```javascript
console.log('hello '.repeat(3));
```
70. `String.prototype.replace()`
```javascript
console.log('hello world'.replace('world', 'everyone'));
```
71. `String.prototype.search()`
```javascript
console.log('hello world'.search(/world/));
```
72. `String.prototype.slice()`
```javascript
console.log('hello world'.slice(0, 5));
```
73. `String.prototype.split()`
```javascript
console.log('hello world'.split(' '));
```
74. `String.prototype.trim()`
```javascript
console.log(' hello world '.trim());
```
75. `RegExp.prototype.test()`
```javascript
console.log(/world/.test('hello world'));
```
76. `RegExp.prototype.exec()`
```javascript
console.log(/world/.exec('hello world'));
```
77. `JSON.stringify()`
```javascript
console.log(JSON.stringify({key: 'value'}));
```
78. `JSON.parse()`
```javascript
console.log(JSON.parse('{"key":"value"}'));
```
79. `Function.prototype.bind()`
```javascript
let greet = function(name) {
  console.log(`Hello ${name}`);
};
let boundGreet = greet.bind(null, 'world');
boundGreet();
```
80. `Function.prototype.call()`
```javascript
let greet = function(name) {
  console.log(`Hello ${name}`);
};
greet.call(null, 'world');
```
81. `Function.prototype.apply()`
```javascript
let greet = function(name) {
  console.log(`Hello ${name}`);
};
greet.apply(null, ['world']);
```
82. `Object.prototype.hasOwnProperty()`
```javascript
let obj = {key: 'value'};
console.log(obj.hasOwnProperty('key'));
```
83. `Object.prototype.isPrototypeOf()`
```javascript
function Parent() {}
function Child() {}
Child.prototype = new Parent();
console.log(Parent.prototype.isPrototypeOf(new Child()));
```
84. `Object.prototype.propertyIsEnumerable()`
```javascript
let obj = {key: 'value'};
console.log(obj.propertyIsEnumerable('key'));
```
85. `Object.keys()`
```javascript
let obj = {key1: 'value1', key2: 'value2'};
console.log(Object.keys(obj));
```
86. `Object.values()`
```javascript
let obj = {key1: 'value1', key2: 'value2'};
console.log(Object.values(obj));
```
87. `Object.entries()`
```javascript
let obj = {key1: 'value1', key2: 'value2'};
console.log(Object.entries(obj));
```
88. `Object.assign()`
```javascript
let obj1 = {key1: 'value1'};
let obj2 = {key2: 'value2'};
console.log(Object.assign(obj1, obj2));
```
89. `Object.create()`
```javascript
let proto = {key: 'value'};
let obj = Object.create(proto);
console.log(obj.key);
```
90. `Object.freeze()`
```javascript
let obj = {key: 'value'};
Object.freeze(obj);
console.log(Object.isFrozen(obj));
```
91. `Object.seal()`
```javascript
let obj = {key: 'value'};
Object.seal(obj);
console.log(Object.isSealed(obj));
```
92. `Number.isNaN()`
```javascript
console.log(Number.isNaN(NaN));
```


93. `Number.isInteger()`
```javascript
console.log(Number.isInteger(1));
```
94. `Number.parseFloat()`
```javascript
console.log(Number.parseFloat('1.23'));
```
95. `Number.parseInt()`
```javascript
console.log(Number.parseInt('123'));
```
96. `Promise.prototype.then()`
```javascript
Promise.resolve('hello world').then(value => console.log(value));
```
97. `Promise.prototype.catch()`
```javascript
Promise.reject('hello world').catch(value => console.log(value));
```
98. `Promise.prototype.finally()`
```javascript
Promise.resolve('hello world').finally(() => console.log('Finished!'));
```
99. `Promise.all()`
```javascript
Promise.all([Promise.resolve(1), Promise.resolve(2)]).then(values => console.log(values));
```
100. `Promise.race()`
```javascript
Promise.race([Promise.resolve(1), Promise.resolve(2)]).then(value => console.log(value));
```

For the array methods, remember that they need to be called on arrays:

101. `push()`
```javascript
let arr = ['hello'];
arr.push('world');
console.log(arr);
```
102. `pop()`
```javascript
let arr = ['hello', 'world'];
arr.pop();
console.log(arr);
```
103. `shift()`
```javascript
let arr = ['hello', 'world'];
arr.shift();
console.log(arr);
```
104. `unshift()`
```javascript
let arr = ['world'];
arr.unshift('hello');
console.log(arr);
```
105. `concat()`
```javascript
let arr1 = ['hello'];
let arr2 = ['world'];
console.log(arr1.concat(arr2));
```
106. `join()`
```javascript
let arr = ['hello', 'world'];
console.log(arr.join(' '));
```
107. `slice()`
```javascript
let arr = ['hello', 'world'];
console.log(arr.slice(1));
```
108. `splice()`
```javascript
let arr = ['hello', 'world'];
arr.splice(1, 0, 'there');
console.log(arr);
```
109. `indexOf()`
```javascript
let arr = ['hello', 'world'];
console.log(arr.indexOf('world'));
```
110. `lastIndexOf()`
```javascript
let arr = ['hello', 'world', 'hello'];
console.log(arr.lastIndexOf('hello'));
```
111. `forEach()`
```javascript
['hello', 'world'].forEach(item => console.log(item));
```
112. `map()`
```javascript
console.log(['hello', 'world'].map(item => item.toUpperCase()));
```
113. `filter()`
```javascript
console.log([1, 2, 3, 4].filter(num => num > 2));
```
114. `reduce()`
```javascript
console.log([1, 2, 3, 4].reduce((a, b) => a + b, 0));
```
115. `reduceRight()`
```javascript
console.log([[0, 1], [2, 3], [4, 5]].reduceRight((a, b) => a.concat(b)));
```
116. `some()`
```javascript
console.log([1, 2, 3, 4].some(num => num > 3));
```
117. `every()`
```javascript
console.log([1, 2, 3, 4].every(num => num > 0));
```
118. `find()`
```javascript
console.log([1, 2, 3, 4].find(num

 => num > 2));
```
119. `findIndex()`
```javascript
console.log([1, 2, 3, 4].findIndex(num => num > 2));
```
120. `includes()`
```javascript
console.log([1, 2, 3, 4].includes(3));
```
121. `sort()`
```javascript
console.log(['b', 'a', 'c'].sort());
```
122. `reverse()`
```javascript
console.log(['a', 'b', 'c'].reverse());
```
123. `fill()`
```javascript
console.log(new Array(3).fill('a'));
```
124. `copyWithin()`
```javascript
console.log([1, 2, 3, 4, 5].copyWithin(0, 3));
```
125. `entries()`
```javascript
console.log([...['a', 'b'].entries()]);
```
126. `keys()`
```javascript
console.log([...['a', 'b'].keys()]);
```
127. `values()`
```javascript
console.log([...['a', 'b'].values()]);
```
