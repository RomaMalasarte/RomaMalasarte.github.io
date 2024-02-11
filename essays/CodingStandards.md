---
layout: essay
type: essay
title: "Clean code creates invincible systems"
# All dates must be YYYY-MM-DD format!
date: 2024-02-08
published: true
labels:
  - Javascript
  - ESLint 
---

## _Journey to clean and clear coding_
It was not until I embarked on the challenging journey of taking the ICS212 Programming Structures course, where I found myself most frustrated with the intricacies of proper coding standards. After writing pieces of code, I would run pylint, a python tool renowned for checking code quality and errors. As I hit enter, I would get a large list of errors that ranged from indentation, extra spaces, incorrect declarations, among others. It was a bit irritating to see but at the same time served a certain satisfaction in the midst of annoyance. It was akin to untangling a bunch of knots. Intially it is overwhelming, but extremely satisfying once the list of errors start to reduce. Over time, the coding standard becomes second nature and it allows me to grow in the craft.

## _Not Cool Code and Cool Code_
Every person that codes has their own style of writing code, but it is crucial that we (as coders) can differentiate good and bad coding standards. Here is an example of bad coding standard, a.k.a not cool code. The following examples are referenced from one of our in class coding assignments:

```
// Not cool code
const t = [1,  2,  3,  4];

function aa(n) {
var t =  0;
for (var i =  0; i < n.length; i++) {
  t += n[i];
}
return t;
}

console.log(aa(t));
```



Here lies a symphony of sloppinesss. Right off the bat, we can see that the indentation is off and it acquires poor naming conventions. Although this code is on the simpler side, some folks who read this code will have to think super hard about what the function's purpose is from the start. Is the purpose of this code aa? Like, what does that mean? This code also uses var, which is function-scoped, we should not be using var. This code also returns a result with no context or explanation, not even comments are present. One may say... not cool dude.

```
// Cool Code
const testNums = [1, 2, 3, 4];

function sumForLoop(nums) {
  let total = 0;
  for (const num of nums) {
    total += num;
  }
  return total;
}

console.log(sumForLoop(testNums));
```


A beacon of enlightenment. You can see the difference between the bad coding standards we analyzed and good coding standards such as this one. With the help of the descriptive naming conventions, we can figure out that this code has a function sumForLoop that calculates the sum of an array numbers using a for loop. The indentation of this code allows for readability and has proper usage of keywords such as let and const. Following good coding standards can make code seem like a sentence. With consistent and clear documentation, this code can be deemed as invincible!

## _Snaps for ESLint_
After a week of learning and utilizing ESLint and IntelliJ, I can say that ESLint is a valuable tool when it comes to adhereing to coding standards. When I am doing a WOD, I think that ESLint reduces my stress of having to fix the structural errors myself. It allows me to discover the issues with my code as early as the start of a key to the end (literally). When I am well aware that my code is not formatted well, or the logic is weird, ESLint got my back. 
