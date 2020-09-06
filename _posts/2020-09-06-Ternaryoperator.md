---
layout: post
title:  "Ternary operator"
date: 2020-09-06 14:14:02 +0100
permalink: /ternaryoperator/
categories: javascript
---

**Make Your Code Cleaner with JavaScript Ternary Operator**

Consider the code below, how can it be made cleaner and shorter?  By using a ternary operator.  This example uses the voting age in the UK.

```javascript
var age = 18;
var canVote;
if (age >= 18) {       //equal to or greater than.
    canVote = 'Yes!';
} else {
    canVote = 'No, sorry.';
}
console.log(`Am I able to vote? ${canVote}`);  

//console output: Am I able to vote? Yes!
```

Now we will use interpolation.

```javascript
var age = 19;
var canVote = age >= 18 ? 'Yes!' : 'No, sorry';

console.log(`Am I able to vote? ${canVote}`);
```

The general syntax of ternary looks like this:
```javascript
condition ? expression_1 : expression_2;
```
