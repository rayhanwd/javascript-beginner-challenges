# Javascript beginner challenges:
----------

#### 1. Can you guess what the output of this code will be?
```javascript
const a = [1, 2, 3];
const b = a;
b.push(4);

console.log(a);

```
#### 2. Can you guess what the output of this code will be?
```javascript
const a = 10;
const b = a;
a = 20;

console.log(b);

```
#### 3. Can you guess what the output of this code will be?
```javascript
const obj1 = { a: 10 };
const obj2 = obj1;
obj1.a = 20;

console.log(obj2.a);

```
#### 4. Can you guess what the output of this code will be?
```javascript
let x = 10;
let y = 20;
[x, y] = [y, x];

console.log(x, y);

```
#### 5. Can you guess what the output of this code will be?
```javascript
const arr1 = [1, 2, 3];
const arr2 = arr1.slice();
arr2.push(4);

console.log(arr1);

```
#### 6. Can you guess what the output of this code will be?
```javascript
let num = 10;
let str = 'Hello World';
let bool = true;

console.log(typeof num, typeof str, typeof bool);

```
#### 7. Can you guess what the output of this code will be?
```javascript
const obj = { a: 10 };
const objCopy = Object.assign({}, obj);

console.log(objCopy);

```
#### 8. Can you guess what the output of this code will be?
```javascript
const arr = [1, 2, 3];
const arrCopy = [...arr];

console.log(arrCopy);

```
#### 9. Can you guess what the output of this code will be?
```javascript
const obj = { a: 10 };
const objCopy = JSON.parse(JSON.stringify(obj));

console.log(objCopy);

```
#### 10. Can you guess what the output of this code will be?
```javascript
const arr1 = [1, 2, 3];
const arr2 = [4, 5, 6];
const arr3 = [...arr1, ...arr2];

console.log(arr3);

```
#### 11. Can you guess what the output of this code will be?
```javascript
let x = 10;
let y = x++;
let z = ++x;

console.log(x, y, z);

```
#### 12. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
arr.length = 0;

console.log(arr);

```
#### 13. Can you guess what the output of this code will be?
```javascript
let arr1 = [1, 2, 3];
let arr2 = [4, 5, 6];
let arr3 = arr1.concat(arr2);

console.log(arr3);

```
#### 14. Can you guess what the output of this code will be?
```javascript
let num = 10;
num.toString = function() { return 'twenty' };

console.log(num.toString());

```
#### 15. Can you guess what the output of this code will be?
```javascript
let obj = { a: 10 };
Object.freeze(obj);
obj.a = 20;

console.log(obj.a);

```
#### 16. Can you guess what the output of this code will be?
```javascript
let x = 10;
let y = '20';
let z = x + y;

console.log(z);

```
#### 17. Can you guess what the output of this code will be?
```javascript
let str = 'Hello World';
str = str.replace('World', 'JavaScript');

console.log(str);

```
#### 18. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
arr.forEach(function(item) {
  item += 1;
});

console.log(arr);

```
#### 19. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let sum = arr.reduce(function(acc, item) {
  return acc + item;
}, 0);

console.log(sum);

```
#### 20. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let newArr = arr.map(function(item) {
  return item * 2;
});

console.log(newArr);

```
#### 21. Can you guess what the output of this code will be?
```javascript
let str = 'Hello World';
let newStr = str.split('').reverse().join('');

console.log(newStr);

```
#### 22. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let filteredArr = arr.filter(function(item) {
  return item > 1;
});


let arr = [1, 2, 3];
let filteredArr = arr.filter(function(item) {
  return item > 1;
});

console.log(filteredArr);

```
#### 23. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let slicedArr = arr.slice(1, 2);

console.log(slicedArr);

```
#### 24. Can you guess what the output of this code will be?
```javascript
let str = 'Hello World';
let upperCaseStr = str.toUpperCase();

console.log(upperCaseStr);

```
#### 25. Can you guess what the output of this code will be?
```javascript
let num = 10;
let bool = Boolean(num);

console.log(bool);

```
#### 26. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
arr.pop();

console.log(arr);

```
#### 27. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
arr.shift();

console.log(arr);

```
#### 28. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
arr.splice(1, 1, 4);

console.log(arr);

```
#### 29. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let slicedArr = arr.slice();

console.log(slicedArr);

```
#### 30. Can you guess what the output of this code will be?
```javascript
let obj = { a: 10 };
delete obj.a;

console.log(obj);

```
#### 31. Can you guess what the output of this code will be?
```javascript
let obj = { a: 10 };
obj.b = 20;

console.log(Object.keys(obj));

```
#### 32. Can you guess what the output of this code will be?
```javascript
let obj = { a: 10 };
Object.keys(obj).forEach(function(key) {
  console.log(key, obj[key]);
});

```

#### 33. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let reversedArr = arr.reverse();

console.log(reversedArr);

```
#### 34. Can you guess what the output of this code will be?
```javascript
let str = 'Hello World';
let newStr = str.substring(1, 4);

console.log(newStr);

```
#### 35. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let lastElement = arr[arr.length - 1];

console.log(lastElement);

```
#### 36. Can you guess what the output of this code will be?
```javascript
let str = 'Hello World';
let hasWorld = str.includes('World');

console.log(hasWorld);

```
#### 37. Can you guess what the output of this code will be?
```javascript
let obj = { a: 10 };
let hasA = 'a' in obj;

console.log(hasA);

```
#### 38. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let hasOne = arr.includes(1);

console.log(hasOne);

```
#### 39. Can you guess what the output of this code will be?
```javascript
let str = 'Hello World';
let newStr = str.replace(/l/g, 'x');

console.log(newStr);

```
#### 40. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let firstElement = arr[0];

console.log(firstElement);

```
#### 41. Can you guess what the output of this code will be?
```javascript
let str = 'Hello World';
let newStr = str.charAt(0);

console.log(newStr);

```
#### 42. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let newArr = arr.map(function(item) {
  return item + 1;
}).filter(function(item) {
  return item > 2;
});

console.log(newArr);

```
#### 43. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let lastTwoElements = arr.slice(-2);

console.log(lastTwoElements);

```
#### 44. Can you guess what the output of this code will be?
```javascript

let arr1 = [1, 2, 3];
let arr2 = [4, 5, 6];
let mergedArr = arr1.concat(arr2);

console.log(mergedArr);

```
#### 45. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let squaredArr = arr.map(function(item) {
  return item * item;
});

console.log(squaredArr);

```
#### 46. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let isEven = arr.every(function(item) {
  return item % 2 === 0;
});

console.log(isEven);

```
#### 47. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let oddArr = arr.filter(function(item) {
  return item % 2 !== 0;
});

console.log(oddArr);

```
#### 48. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let firstTwoElements = arr.slice(0, 2);

console.log(firstTwoElements);

```
#### 49. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let hasFour = arr.includes(4);

console.log(hasFour);

```
#### 50. Can you guess what the output of this code will be?
```javascript
let str = 'Hello World';
let newStr = str.split('').reverse().join('');

console.log(newStr);

```
#### 51. Can you guess what the output of this code will be?
```javascript

let num1 = 5;
let num2 = 10;
let sum = num1 + num2;

console.log(sum);

```
#### 52. Can you guess what the output of this code will be?
```javascript
let num1 = 5;
let num2 = 10;
let difference = num2 - num1;

console.log(difference);

```
#### 53. Can you guess what the output of this code will be?
```javascript
let num1 = 5;
let num2 = 10;
let product = num1 * num2;

console.log(product);

```
#### 54. Can you guess what the output of this code will be?
```javascript
let num1 = 5;
let num2 = 10;
let quotient = num2 / num1;

console.log(quotient);

```
#### 55. Can you guess what the output of this code will be?
```javascript
let num1 = 5;
let num2 = 10;
let remainder = num2 % num1;

console.log(remainder);

```
#### 56. Can you guess what the output of this code will be?
```javascript
let str1 = 'Hello';
let str2 = 'World';
let concatenatedStr = str1 + ' ' + str2;

console.log(concatenatedStr);

```
#### 57. Can you guess what the output of this code will be?
```javascript
let str = 'Hello World';
let uppercaseStr = str.toUpperCase();

console.log(uppercaseStr);

```
#### 58. Can you guess what the output of this code will be?
```javascript
let str = 'Hello World';
let lowercaseStr = str.toLowerCase();

console.log(lowercaseStr);

```
#### 59. Can you guess what the output of this code will be?
```javascript
let str = '   Hello World    ';
let trimmedStr = str.trim();

console.log(trimmedStr);

```
#### 60. Can you guess what the output of this code will be?
```javascript
let str = 'Hello World';
let slicedStr = str.slice(0, 5);

console.log(slicedStr);

```
#### 61. Can you guess what the output of this code will be?
```javascript
let str = 'Hello World';
let indexOfLetterW = str.indexOf('W');

console.log(indexOfLetterW);

```
#### 62. Can you guess what the output of this code will be?
```javascript
let str = 'Hello World';
let replacedStr = str.replace('World', 'Javascript');

console.log(replacedStr);

```
#### 63. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
arr.push(4);

console.log(arr);

```
#### 64. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
arr.pop();

console.log(arr);

```
#### 65. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
arr.unshift(0);

console.log(arr);

```
#### 66. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
arr.shift();

console.log(arr);

```
#### 67. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let reversedArr = arr.reverse();

console.log(reversedArr);

```
#### 68. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let sortedArr = arr.sort();

console.log(sortedArr);

```
#### 69. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let slicedArr = arr.slice(0, 2);

console.log(slicedArr);

```
#### 70. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let joinedArr = arr.join('-');

console.log(joinedArr);

```
#### 71. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let reversedArr = arr.reverse();

console.log(reversedArr);

```
#### 72. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let copiedArr = [...arr];

console.log(copiedArr);

```
#### 73. Can you guess what the output of this code will be?
```javascript

let obj = {name: 'John', age: 30};
let name = obj.name;
let age = obj.age;

console.log(name, age);

```
#### 74. Can you guess what the output of this code will be?
```javascript
let obj = {name: 'John', age: 30};
obj.email = 'john@example.com';

console.log(obj);

```
#### 75. Can you guess what the output of this code will be?
```javascript
let obj = {name: 'John', age: 30};
delete obj.age;

console.log(obj);

```
#### 76. Can you guess what the output of this code will be?
```javascript
let obj1 = {name: 'John'};
let obj2 = {age: 30};
let mergedObj = {...obj1, ...obj2};

console.log(mergedObj);

```
#### 77. Can you guess what the output of this code will be?
```javascript
let num = 5;
let square = num ** 2;

console.log(square);

```
#### 78. Can you guess what the output of this code will be?
```javascript
let num = 5;
let cube = num ** 3;

console.log(cube);

```
#### 79. Can you guess what the output of this code will be?
```javascript
let num = 5;
let isEven = num % 2 === 0;

console.log(isEven);

```
#### 80. Can you guess what the output of this code will be?
```javascript
let num = 5;
let isOdd = num % 2 !== 0;

console.log(isOdd);

```
#### 81. Can you guess what the output of this code will be?
```javascript
let num = 5;
let absoluteNum = Math.abs(-num);

console.log(absoluteNum);

```
#### 82. Can you guess what the output of this code will be?
```javascript
let num = 5.1234;
let roundedNum = Math.round(num);

console.log(roundedNum);

```
#### 83. Can you guess what the output of this code will be?
```javascript
let num = 5.1234;
let floorNum = Math.floor(num);

console.log(floorNum);

```
#### 84. Can you guess what the output of this code will be?
```javascript
let num = 5.1234;
let ceilNum = Math.ceil(num);

console.log(ceilNum);

```
#### 85. Can you guess what the output of this code will be?
```javascript
let num1 = 5;
let num2 = 10;
let maxNum = Math.max(num1, num2);

console.log(maxNum);

```
#### 86. Can you guess what the output of this code will be?
```javascript
let num1 = 5;
let num2 = 10;
let minNum = Math.min(num1, num2);

console.log(minNum);

```
#### 87. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let filteredArr = arr.filter(num => num > 1);

console.log(filteredArr);

```
#### 88. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let mappedArr = arr.map(num => num ** 2);

console.log(mappedArr);

```
#### 89. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let reducedArr = arr.reduce((acc, num) => acc + num, 0);

console.log(reducedArr);

```
#### 90. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let foundNum = arr.find(num => num > 1);

console.log(foundNum);

```
#### 91. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let includesNum = arr.includes(2);

console.log(includesNum);

```
#### 92. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let someNum = arr.some(num => num > 1);

console.log(someNum);

```
#### 93. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let everyNum = arr.every(num => num > 1);

console.log(everyNum);

```
#### 94. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let sortedArr = arr.sort((a, b) => b - a);

console.log(sortedArr);

```
#### 95. Can you guess what the output of this code will be?
```javascript

let arr = [1, 2, 3];
let sortedArr = arr.sort((a, b) => a - b);

console.log(sortedArr);

```
#### 96. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let slicedArr = arr.slice(1);

console.log(slicedArr);

```
#### 97. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let splicedArr = arr.splice(1, 1);

console.log(arr, splicedArr);

```
#### 98. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let joinedArr = arr.join('-');

console.log(joinedArr);

```
#### 99. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let reversedArr = arr.reverse();

console.log(reversedArr);

```
#### 100. Can you guess what the output of this code will be?
```javascript
let str = 'hello';
let upperCaseStr = str.toUpperCase();

console.log(upperCaseStr);

```
#### 101. Can you guess what the output of this code will be?
```javascript
let str = 'HELLO';
let lowerCaseStr = str.toLowerCase();

console.log(lowerCaseStr);

```
#### 102. Can you guess what the output of this code will be?
```javascript
let str = 'hello world';
let firstChar = str.charAt(0);

console.log(firstChar);

```
#### 103. Can you guess what the output of this code will be?
```javascript
let str = 'hello world';
let substring = str.substring(0, 5);

console.log(substring);

```
#### 104. Can you guess what the output of this code will be?
```javascript
let str = 'hello world';
let slicedString = str.slice(0, 5);

console.log(slicedString);

```
#### 105. Can you guess what the output of this code will be?
```javascript
let str = 'hello world';
let indexOfChar = str.indexOf('o');

console.log(indexOfChar);

```
#### 106. Can you guess what the output of this code will be?
```javascript
let str = 'hello world';
let lastIndexOfChar = str.lastIndexOf('o');

console.log(lastIndexOfChar);

```
#### 107. Can you guess what the output of this code will be?
```javascript
let str = 'hello world';
let replacedStr = str.replace('o', 'a');

console.log(replacedStr);

```
#### 108. Can you guess what the output of this code will be?
```javascript
let str = 'hello world';
let includesStr = str.includes('world');

console.log(includesStr);

```
#### 109. Can you guess what the output of this code will be?
```javascript
let date = new Date();
let year = date.getFullYear();

console.log(year);

```
#### 110. Can you guess what the output of this code will be?
```javascript
let date = new Date();
let month = date.getMonth();

console.log(month);

```
#### 111. Can you guess what the output of this code will be?
```javascript
let date = new Date();
let day = date.getDate();

console.log(day);

```
#### 112. Can you guess what the output of this code will be?
```javascript
let date = new Date();
let hours = date.getHours();

console.log(hours);

```
#### 113. Can you guess what the output of this code will be?
```javascript
let date = new Date();
let minutes = date.getMinutes();

console.log(minutes);

```
#### 114. Can you guess what the output of this code will be?
```javascript
let date = new Date();
let seconds = date.getSeconds();

console.log(seconds);

```
#### 115. Can you guess what the output of this code will be?
```javascript
let date = new Date();
let time = date.getTime();

console.log(time);

```
#### 116. Can you guess what the output of this code will be?
```javascript
let date = new Date();
let dateString = date.toDateString();

console.log(dateString);

```
#### 117. Can you guess what the output of this code will be?
```javascript
let date = new Date();
let timeString = date.toTimeString();

console.log(timeString);

```
#### 118. Can you guess what the output of this code will be?
```javascript
let date = new Date();
let dateTimeString = date.toLocaleString();

console.log(dateTimeString);

```
#### 119. Can you guess what the output of this code will be?
```javascript
let num = 5;
let strNum = num.toString();

console.log(strNum);

```
#### 120. Can you guess what the output of this code will be?
```javascript
let str = '5';
let numStr = parseInt(str);

console.log(numStr);

```
#### 121. Can you guess what the output of this code will be?
```javascript

let str = '5.4';
let numStr = parseFloat(str);

console.log(numStr);

```
#### 122. Can you guess what the output of this code will be?
```javascript
let num = 5.4;
let fixedNum = num.toFixed(2);

console.log(fixedNum);

```
#### 123. Can you guess what the output of this code will be?
```javascript
let num = 5.4;
let numString = num.toString();

console.log(numString);

```
#### 124. Can you guess what the output of this code will be?
```javascript
let num = 5.4;
let absoluteNum = Math.abs(num);

console.log(absoluteNum);

```
#### 125. Can you guess what the output of this code will be?
```javascript
let num = -5.4;
let ceilNum = Math.ceil(num);

console.log(ceilNum);

```
#### 126. Can you guess what the output of this code will be?
```javascript
let num = 5.4;
let floorNum = Math.floor(num);

console.log(floorNum);

```
#### 127. Can you guess what the output of this code will be?
```javascript
let num = 5.6;
let roundNum = Math.round(num);

console.log(roundNum);

```
#### 128. Can you guess what the output of this code will be?
```javascript
let num = 5;
let powNum = Math.pow(num, 2);

console.log(powNum);

```
#### 129. Can you guess what the output of this code will be?
```javascript
let num = 2;
let sqrtNum = Math.sqrt(num);

console.log(sqrtNum);

```
#### 130. Can you guess what the output of this code will be?
```javascript
let num1 = 5;
let num2 = 10;
let maxNum = Math.max(num1, num2);

console.log(maxNum);

```
#### 131. Can you guess what the output of this code will be?
```javascript
let num1 = 5;
let num2 = 10;
let minNum = Math.min(num1, num2);

console.log(minNum);

```
#### 132. Can you guess what the output of this code will be?
```javascript
let num1 = 1;
let num2 = 100;
let randomNum = Math.floor(Math.random() * (num2 - num1 + 1)) + num1;

console.log(randomNum);

```
#### 133. Can you guess what the output of this code will be?
```javascript
let obj1 = { name: 'John', age: 25 };
let obj2 = { name: 'Jane', gender: 'female' };
let mergedObj = { ...obj1, ...obj2 };

console.log(mergedObj);

```
#### 134. Can you guess what the output of this code will be?
```javascript
let obj = { name: 'John', age: 25 };
let objKeys = Object.keys(obj);

console.log(objKeys);

```
#### 135. Can you guess what the output of this code will be?
```javascript
let obj = { name: 'John', age: 25 };
let objValues = Object.values(obj);

console.log(objValues);

```
#### 136. Can you guess what the output of this code will be?
```javascript
let obj = { name: 'John', age: 25 };
let objEntries = Object.entries(obj);

console.log(objEntries);

```
#### 137. Can you guess what the output of this code will be?
```javascript
let str = 'hello';
let strLength = str.length;

console.log(strLength);

```
#### 138. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let arrLength = arr.length;

console.log(arrLength);

```
#### 139. Can you guess what the output of this code will be?
```javascript
let obj = { name: 'John', age: 25 };
let objLength = Object.keys(obj).length;

console.log(objLength);

```
#### 140. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let newArr = arr.map(num => num * 2);

console.log(newArr);

```
#### 141. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let sum = arr.reduce((total, num) => total + num, 0);

console.log(sum);

```
#### 142. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let filteredArr = arr.filter(num => num > 1);

console.log(filteredArr);

```
#### 143. Can you guess what the output of this code will be?
```javascript

let arr = [1, 2, 3];
let foundIndex = arr.findIndex(num => num === 2);

console.log(foundIndex);

```
#### 144. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let slicedArr = arr.slice(1, 3);

console.log(slicedArr);

```
#### 145. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
arr.splice(1, 1);

console.log(arr);

```
#### 146. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let reversedArr = arr.reverse();

console.log(reversedArr);

```
#### 147. Can you guess what the output of this code will be?
```javascript
let arr1 = [1, 2, 3];
let arr2 = [4, 5, 6];
let concatenatedArr = arr1.concat(arr2);

console.log(concatenatedArr);

```
#### 148. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let includesNum = arr.includes(2);

console.log(includesNum);

```
#### 149. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let everyNum = arr.every(num => num > 0);

console.log(everyNum);

```
#### 150. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let someNum = arr.some(num => num > 2);

console.log(someNum);

```
#### 151. Can you guess what the output of this code will be?
```javascript
let str = 'hello';
let upperCaseStr = str.toUpperCase();

console.log(upperCaseStr);

```
#### 152. Can you guess what the output of this code will be?
```javascript
let str = '   hello   ';
let trimmedStr = str.trim();

console.log(trimmedStr);

```
#### 153. Can you guess what the output of this code will be?
```javascript
let str = 'hello';
let charArray = str.split('');

console.log(charArray);

```
#### 154. Can you guess what the output of this code will be?
```javascript
let str = 'hello';
let reversedStr = str.split('').reverse().join('');

console.log(reversedStr);

```
#### 155. Can you guess what the output of this code will be?
```javascript
let str = 'hello';
let replacedStr = str.replace('h', 'H');

console.log(replacedStr);

```
#### 156. Can you guess what the output of this code will be?
```javascript
let date = new Date();
let year = date.getFullYear();

console.log(year);

```
#### 157. Can you guess what the output of this code will be?
```javascript
let date = new Date();
let month = date.getMonth();

console.log(month);

```
#### 158. Can you guess what the output of this code will be?
```javascript
let date = new Date();
let dayOfWeek = date.getDay();

console.log(dayOfWeek);

```
#### 159. Can you guess what the output of this code will be?
```javascript
let date = new Date();
let hours = date.getHours();

console.log(hours);

```
#### 160. Can you guess what the output of this code will be?
```javascript
let date = new Date();
let minutes = date.getMinutes();

console.log(minutes);

```
#### 161. Can you guess what the output of this code will be?
```javascript
let date1 = new Date('2021-03-10');
let date2 = new Date('2022-03-10');
let differenceInMilliseconds = Math.abs(date2 - date1);

console.log(differenceInMilliseconds);

```
#### 162. Can you guess what the output of this code will be?
```javascript
let date = new Date();
let dateInMilliseconds = date.getTime();

console.log(dateInMilliseconds);

```
#### 163. Can you guess what the output of this code will be?
```javascript
let num1 = 10;
let num2 = 20;
let sum = num1 + num2;

console.log(sum);

```
#### 164. Can you guess what the output of this code will be?
```javascript
let str1 = 'hello';
let str2 = 'world';
let concatenatedStr = str1 + ' ' + str2;

console.log(concatenatedStr);

```
#### 165. Can you guess what the output of this code will be?
```javascript
let num = 10;
let numPlusOne = ++num;

console.log(numPlusOne);

```
#### 166. Can you guess what the output of this code will be?
```javascript

let num = 10;
let numMinusOne = --num;

console.log(numMinusOne);

```
#### 167. Can you guess what the output of this code will be?
```javascript
let num1 = 10;
let num2 = '5';
let sum = num1 + num2;

console.log(sum);

```
#### 168. Can you guess what the output of this code will be?
```javascript
let num1 = 10;
let num2 = '5';
let sum = num1 + parseInt(num2);

console.log(sum);

```
#### 169. Can you guess what the output of this code will be?
```javascript
let num1 = 10;
let num2 = '5.5';
let sum = num1 + parseFloat(num2);

console.log(sum);

```
#### 170. Can you guess what the output of this code will be?
```javascript
let num = 10;
let squaredNum = Math.pow(num, 2);

console.log(squaredNum);

```
#### 171. Can you guess what the output of this code will be?
```javascript
let num = 2.456;
let roundedNum = num.toFixed(2);

console.log(roundedNum);

```
#### 172. Can you guess what the output of this code will be?
```javascript
let num = -10;
let absoluteNum = Math.abs(num);

console.log(absoluteNum);

```
#### 173. Can you guess what the output of this code will be?
```javascript
let num1 = 10;
let num2 = 20;
let biggerNum = Math.max(num1, num2);

console.log(biggerNum);

```
#### 174. Can you guess what the output of this code will be?
```javascript
let num1 = 10;
let num2 = 20;
let smallerNum = Math.min(num1, num2);

console.log(smallerNum);

```
#### 175. Can you guess what the output of this code will be?
```javascript
let num = -10;
let positiveNum = Math.abs(num);

console.log(positiveNum);

```
#### 176. Can you guess what the output of this code will be?
```javascript
let num1 = 10;
let num2 = 20;
let difference = Math.abs(num1 - num2);

console.log(difference);

```
#### 177. Can you guess what the output of this code will be?
```javascript
let num = 10.56;
let roundedNum = Math.round(num);

console.log(roundedNum);

```
#### 178. Can you guess what the output of this code will be?
```javascript
let num = 10.56;
let roundedNum = Math.ceil(num);

console.log(roundedNum);

```
#### 179. Can you guess what the output of this code will be?
```javascript
let num = 10.56;
let roundedNum = Math.floor(num);

console.log(roundedNum);

```
#### 180. Can you guess what the output of this code will be?
```javascript
let str = 'hello';
let strLength = str.length;

console.log(strLength);

```
#### 181. Can you guess what the output of this code will be?
```javascript
let str = 'hello';
let firstChar = str.charAt(0);

console.log(firstChar);

```
#### 182. Can you guess what the output of this code will be?
```javascript
let str = 'hello';
let lastChar = str.charAt(str.length - 1);

console.log(lastChar);

```
#### 183. Can you guess what the output of this code will be?
```javascript
let str = 'hello';
let substr = str.substring(1, 4);

console.log(substr);

```
#### 184. Can you guess what the output of this code will be?
```javascript
let str = 'hello';
let indexOfChar = str.indexOf('l');

console.log(indexOfChar);

```
#### 185. Can you guess what the output of this code will be?
```javascript
let str = 'hello';
let reversedStr = str.split('').reverse().join('');

console.log(reversedStr);

```
#### 186. Can you guess what the output of this code will be?
```javascript
let obj = {name: 'John', age: 30};
let objKeys = Object.keys(obj);

console.log(objKeys);

```
#### 187. Can you guess what the output of this code will be?
```javascript
let obj = {name: 'John', age: 30};
let objValues = Object.values(obj);

console.log(objValues);

```
#### 188. Can you guess what the output of this code will be?
```javascript
let obj = {name: 'John', age: 30};
let objEntries = Object.entries(obj);

console.log(objEntries);

```
#### 189. Can you guess what the output of this code will be?
```javascript

let obj1 = {name: 'John', age: 30};
let obj2 = {country: 'USA', city: 'New York'};
let mergedObj = {...obj1, ...obj2};

console.log(mergedObj);

```
#### 190. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let newArr = arr.map(num => num * 2);

console.log(newArr);

```
#### 191. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let sum = arr.reduce((total, num) => total + num, 0);

console.log(sum);

```
#### 192. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let filteredArr = arr.filter(num => num > 1);

console.log(filteredArr);

```
#### 193. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let hasTwo = arr.includes(2);

console.log(hasTwo);

```
#### 194. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let hasFour = arr.includes(4);

console.log(hasFour);

```
#### 195. Can you guess what the output of this code will be?
```javascript
let arr1 = [1, 2, 3];
let arr2 = [4, 5, 6];
let concatenatedArr = arr1.concat(arr2);

console.log(concatenatedArr);

```
#### 196. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let reversedArr = arr.reverse();

console.log(reversedArr);

```
#### 197. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let slicedArr = arr.slice(0, 2);

console.log(slicedArr);

```
#### 198. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
arr.splice(1, 1, 4);

console.log(arr);

```
#### 199. Can you guess what the output of this code will be?
```javascript
let arr = [1, 2, 3];
let sortedArr = arr.sort();

console.log(sortedArr);

```
#### 200. Can you guess what the output of this code will be?
```javascript
let str = 'hello';
let strArray = Array.from(str);

console.log(strArray);

```
#### 201. Can you guess what the output of this code will be?
```javascript
let str = 'hello';
let strArray = [...str];

console.log(strArray);

```

