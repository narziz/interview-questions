# JS Interview Questions

#### Q1. Which operator returns true if the two compared values are not equal?

1. `<>`
2. `~`
3. `==!`
4. `!==`


#### Q2. When would the final statement in the code shown be logged to the console? When would 'results shown' be logged to the console?

```js
let modal = document.querySelector('#result');
setTimeout(function () {
  modal.classList.remove('hidden');
}, 10000);
console.log('Results shown');
```

1. after 10 second
2. after results are received from the HTTP request
3. after 10000 seconds
4. immediately


#### Q3. Which Object method returns an iterable that can be used to iterate over the properties of an object?

1. `Object.get()`
2. `Object.loop()`
3. `Object.each()`
4. `Object.keys()`


#### Q4. What will be logged to the console?

```js
var a = ['dog', 'cat', 'hen'];
a[100] = 'fox';
console.log(a.length);
```

1. 101
2. 3
3. 4
4. 100


#### Q5. What is the result of running this statement?

```javascript
console.log(typeof 42);
```

1. `'float'`
2. `'value'`
3. `'number'`
4. `'integer'`


#### Q6. Which method converts JSON data to a JavaScript object?

1. `JSON.fromString();`
2. `JSON.parse()`
3. `JSON.toObject()`
4. `JSON.stringify()`


#### Q7. When would you use a conditional statement?

1. When you want to reuse a set of statements multiple times.
2. When you want your code to choose between multiple options.
3. When you want to group data together.
4. When you want to loop through a group of statement.


#### Q8. What would be the result in the console of running this code?

```js
for (var i = 0; i < 5; i++) {
  console.log(i);
}
```

1. 1 2 3 4 5
2. 1 2 3 4
3. 0 1 2 3 4
4. 0 1 2 3 4 5


#### Q9. What is the value of dessert.type after executing this code?

```js
const dessert = { type: 'pie' };
dessert.type = 'pudding';
```

1. pie
2. The code will throw an error.
3. pudding
4. undefined


#### Q10. Which Variable-defining keyword allows its variable to be accessed (as undefined) before the line that defines it?

1. all of them
2. `const`
3. `var`
4. `let`


#### Q11. Which of the following values is not a Boolean false?

1. `Boolean(0)`
2. `Boolean("")`
3. `Boolean(NaN)`
4. `Boolean("false")`


#### Q12. How would you reference the text 'avenue' in the code shown?

```js
let roadTypes = ['street', 'road', 'avenue', 'circle'];
```

1. roadTypes.2
2. roadTypes\[3\]
3. roadTypes.3
4. roadTypes\[2\]


#### Q13. Which of the following is not a keyword in JavaScript?

1. `this`
2. `catch`
3. `function`
4. `array`


#### Q14. For the following class, how do you get the value of 42 from an instance of X?

```js
class X {
  get Y() {
    return 42;
  }
}
var x = new X();
```

1. `x.get('Y')`
2. `x.Y`
3. `x.Y()`
4. `x.get().Y`


#### Q15. What is the result of running this code?

```js
sum(10, 20);
diff(10, 20);
function sum(x, y) {
  return x + y;
}

let diff = function (x, y) {
  return x - y;
};
```

1. 30, ReferenceError, 30, -10
2. 30, ReferenceError
3. 30, -10
4. ReferenceError, -10


#### Q16. What does the following expression evaluate to?

```js
[] == [];
```

1. True
2. undefined
3. []
4. False


#### Q17. What type of scope does the end variable have in the code shown?

```javascript
var start = 1;
if (start === 1) {
  let end = 2;
}
```

1. conditional
2. block
3. global
4. function


#### Q18. What will the value of y be in this code:

```js
const x = 6 % 2;
const y = x ? 'One' : 'Two';
```

1. One
2. undefined
3. TRUE
4. Two


#### Q19. Which keyword is used to create an error?

1. `throw`
2. `exception`
3. `catch`
4. `error`


#### Q20. Which statement references the DOM node created by the code shown?

```html
<p class="pull">lorem ipsum</p>
```

1. `Document.querySelector('class.pull')`
2. `document.querySelector('.pull');`
3. `Document.querySelector('pull')`
4. `Document.querySelector('#pull')`


#### Q21. What value does this code return?

```js
let answer = true;
if (answer === false) {
  return 0;
} else {
  return 10;
}
```

1. 10
2. true
3. false
4. 0


#### Q22. Which choice is an incorrect way to define an arrow function that returns an empty object?

1. => `({})`
2. => `{}`
3. => `{ return {};}`
4. => `(({}))`


#### Q23. Which expression evaluates to true?

1. `[3] == [3]`
2. `3 == '3'`
3. `3 != '3'`
4. `3 === '3'`


#### Q24. Which of these is a valid variable name?

1. 5thItem
2. firstName
3. grand total
4. function


#### Q25. Which method cancels event default behavior?

1. `cancel()`
2. `stop()`
3. `preventDefault()`
4. `prevent()`


#### Q26. Which method do you use to attach one DOM node to another?

1. `attachNode()`
2. `getNode()`
3. `querySelector()`
4. `appendChild()`


#### Q27. What statement can be used to skip an iteration in a loop?

1. `break`
2. `pass`
3. `skip`
4. `continue`


#### Q28. Which choice is valid example for an arrow function?

1. `(a,b) => c`
2. `a, b => {return c;}`
3. `a, b => c`
4. `{ a, b } => c`


#### Q29. How do you add a comment to JavaScript code?

1. `! This is a comment`
2. `# This is a comment`
3. `\\ This is a comment`
4. `// This is a comment`


#### Q30. What is the result of running the statement shown?

```javascript
let a = 5;
console.log(++a);
```

1. 4
2. 10
3. 6
4. 5


#### Q31. Which statement selects all img elements in the DOM tree?

1. `Document.querySelector('img')`
2. `Document.querySelectorAll('<img>')`
3. `Document.querySelectorAll('img')`
4. `Document.querySelector('<img>')`


#### Q32. Which event is fired on a text field within a form when a user tabs to it, or clicks or touches it?

1. focus
2. blur
3. hover
4. enter


#### Q33. What is the output of this code?

```javascript
var obj;
console.log(obj);
```

1. `ReferenceError: obj is not defined`
2. `{}`
3. `undefined`
4. `null`


#### Q34. What will this code log to the console?

```js
const foo = [1, 2, 3];
const [n] = foo;
console.log(n);
```

1. 1
2. undefined
3. NaN
4. Nothing--this is not proper JavaScript syntax and will throw an error.


#### Q35. How do you remove the property name from this object?

```js
const foo = {
  name: 'Albert',
};
```

1. delete name from foo;
2. delete foo.name;
3. del foo.name;
4. remove foo.name;


#### Q36. What is the difference between the `map()` and the `forEach()` methods on the Array prototype?

1. There is no difference.
2. The `forEach()` method returns a single output value, whereas the `map()` method performs operation on each value in the array.
3. The map() methods returns a new array with a transformation applied on each item in the original array, whereas the `forEach()` method iterates through an array with no return value.
4. The `forEach()` methods returns a new array with a transformation applied on each item in the original array, whereas the `map()` method iterates through an array with no return value.


#### Q37. If your app receives data from a third-party API, which HTTP response header must the server specify to allow exceptions to the same-origin policy?

1. Security-Mode
2. Access-Control-Allow-Origin
3. Different-Origin
4. Same-Origin


#### Q38. What is the output of this code?

```js
let rainForests = ['Amazon', 'Borneo', 'Cerrado', 'Congo'];
rainForests.splice(0, 2);
console.log(rainForests);
```

1. `["Amazon","Borneo","Cerrado","Congo"]`
2. `["Cerrado", "Congo"]`
3. `["Congo"]`
4. `["Amazon","Borneo"]`


#### Q39. What will this code print?

```js
const obj = {
  a: 1,
  b: 2,
  c: 3,
};

const obj2 = {
  ...obj,
  a: 0,
};

console.log(obj2.a, obj2.b);
```

1. Nothing, it will throw an error
2. 0 2
3. undefined 2
4. undefined 2


#### Q40. What is the output of this code?

```js
let x = 6 + 3 + '3';
console.log(x);
```

1. 93
2. 12
3. 66
4. 633



### Answers
- Q1: 4, Q2: 4, Q3: 4, Q4: 1, Q5: 3, Q6: 2, Q7: 2, Q8: 3, Q9: 3, Q10: 3,
- Q11: 4, Q12: 4, Q13: 4, Q14: 2, Q15: 2, Q16: 4, Q17: 2, Q18: 4, Q19: 1, Q20: 2,
- Q21: 1, Q22: 2, Q23: 2, Q24: 2, Q25: 3, Q26: 4, Q27: 4, Q28: 1, Q29: 4, Q30: 3,
- Q31: 3, Q32: 1, Q33: 3, Q34: 1, Q35: 2, Q36: 3, Q37: 2, Q38: 2, Q39: 2, Q40: 1,
