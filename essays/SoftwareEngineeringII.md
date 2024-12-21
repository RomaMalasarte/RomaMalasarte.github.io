---
layout: essay
type: essay
title: "Giving Software Engineering II a chance"
# All dates must be YYYY-MM-DD format!
date: 2024-12-20
published: true
labels:
  - Meteor
  - React
  - App Development 
---

As I reflect on my experience with software engineering this past fall semester, I can say that the most memorable part was working in a team and gaining the real world experience of a software engineer. The structured approach of the course was something I genuinely appreciated, as it introduced me to a more disciplined way of thinking about computer programming. Beyond the technical skills, the course emphasized teamwork and collaboration. 

## About the Client: SPIRE Hawaii
For our semester project we collaborated with SPIRE Hawaii, a company specializing in accounting and advisory services. Their mission was clear for this project. They hoped to achieve autonomy with their accounting and fiscal data. The challenge? SPIRE relies on Microsoft Excel to manage their financials, but they envisioned something far more dynamic and user-friendly—an application that could forecast their organization's value over time.

When we first met with the client, they walked us through their vision. They wanted a tool that could not only streamline their financial processes but also provide a forecase of the value of the organization overtime. In many ways, it reminded me of tools like QuickBooks, but tailored specifically to their unique needs. To begin, we had to understand the current scope and identify the gaps in their workflow. This set the stage for our semester journey.

## My Role: Frontend Development and Leadership
As part of an eight-person team, my primary focus was on frontend development. One of my proudest contributions was the design of the landing page, which served as the application's first impression. Here's a snapshot of the page I worked on:

Insert landing page photo

In addition to frontend work, I took on the responsibility of coordinating group meetings. With such a large team, maintaining clear communication and setting regular touchpoints was essential. I valued how our group embraced flexibility and initiative, consistently addressing blockers, setting priorities, and meeting deadlines. We weren’t just a team; we were problem-solvers, learning to adapt and support each other.

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
