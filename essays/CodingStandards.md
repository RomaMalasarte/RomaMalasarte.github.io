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
It was not until the ICS212 Programming Structures course, where I was most frustrated with proper coding standards. After writing code, I would run pylint (a python tool used for checking code quality and errors), I would get a large list of errors such as indentation, extra spaces, incorrect declarations, etc. It was irritating to see, but at the same time satisfying. I would have to admint, it was satisfying in the sense that once I get over the overwhelming-ness of the list of errors, and seeing the list reduce made me feel accomplished. Over time, the coding standard becomes second nature and it is important to keep in mind as we create lines of code.

## _Analyzing Not Cool Code and Cool Code_
Every person that codes has their own style of writing code, but it is crucial that we (as coders) can differentiate good and bad coding standards. Here is an example of bad coding standard, a.k.a Not cool code. This was referenced from one of our in class coding assignments:

<img width="350px" class="rounded float-start pe-4" src="../img/not cool code.png">

Right of the bat, the indentation is off and it acquires poor naming conventions. Those who read this code will have to think super hard about what the function's purpose is. Is the purpose of this code aa? Like, what does that mean? This code also uses var. It returns a result with no context or explanation, not even comments are present. One may say... not cool dude.

<img width="350px" class="rounded float-start pe-4" src="../img/cool code.png">

You can see the difference between the bad code we analyzed and this one. With the help of the descripting naming conventions, we can figure out that this code has a function sumForLoop that calculates the sum of an array numbers using a for loop. The indentation of this code allows for readability and has proper usage of keywords such as let and const. Following good coding standards can make code seem like a sentence 


## _Learning Style_
After a week of learning and utilizing ESLint and IntelliJ, I can say that ESLint is a valuable tool when it comes to adhereing to coding standards. When I am doing a WOD, I think that ESLint reduces my stress of having to fix the structural errors myself. It allows me to discover the issues with my code as early as the start of a key to the end (literally). When I am well aware that my code is not formatted well, or the logic is weird, ESLint got my back. 
