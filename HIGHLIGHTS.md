# Some Facts about Code, Node, Express, React

## Overview

What highlights can you come up with to share with the class?

What do you really like? What can you find for fun facts related to any of these topics online?

## Cohort Highlights

1. React Components and modular code- great way to break out our thoughts and our code. Makes it more easily readable for others (and ourselves a few weeks later!)

2. HTTP debuggers files. Can easily tell if your code is working or not.

3. JSX: HTML and Javascript living in harmony together. Example:
const element = <h1>Hello, world!</h1>;

4. Something I went out and learned on my own to add onto what we learned in class (basic JS) ... recursion. Example code snippit from the week we tackled some algorithms:

function fibonacci (index) {
  // if the index input is 2 or less, start with the first two numbers in the fibonacci sequence, which is 1
  if (index <= 2) {
    return 1
  } else {
    // then, if larger than 2, return the previous two indexes added up together
 return fibonacci(index - 1) + fibonacci(index - 2);
  }
}
console.log(fibonacci(4));

5. .filter has to be a predicate method --> it will drop things off that are false.

7. Whenever we are working in a node project, we should always use the command "npm init". NPM stands for node package manager, and it is a really cool tool we use to ship node. I love how the package.json file automatically appears when you run this command!

8. We will all be MERN web developers by the end of this cohort! Or "Full Stack" :) 

