# Some Facts about Code, Node, Express, React

## Overview

What highlights can you come up with to share with the class?
-See team entry. Late to add.

- codecademy - provides a bit more code defintion, Jessica
- w3schools.com - helps as a reference in overall Javascript, Alvin
- css-tricks.com - helps with more css, a good walk through, Rob
- Javascript for Dummies book - a good beginner's guide, Alejandro

- codewithmosh.com - his free videos on Youtube are older, pay website is more recent
- Youtube - in general, can be searched for videos on various subjects


What do you really like? What can you find for fun facts related to any of these topics online?

## Cohort Highlights

1. React Components and modular code- great way to break out our thoughts and our code. Makes it more easily readable for others (and ourselves a few weeks later!)

2. HTTP debuggers files. Can easily tell if your code is working or not.

3. JSX: HTML and Javascript living in harmony together. Example:
const element = <h1>Hello, world!</h1>;

4. Something I went out and learned on my own to add onto what we learned in class (basic JS) ... recursion. Example code snippit from the week we tackled some algorithms:

```
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
```

5. .filter has to be a predicate method --> it will drop things off that are false.

7. Whenever we are working in a node project, we should always use the command "npm init". NPM stands for node package manager, and it is a really cool tool we use to ship node. I love how the package.json file automatically appears when you run this command!

8. We will all be MERN web developers by the end of this cohort! Or "Full Stack" :) 

----

1. [Markdown Guide] (https://www.markdownguide.org/basic-syntax/)

2. Commit messages written in the imperative

3. Engineering communication habits, like how to describe what specific problems and what we've already tried, effective problem parsing. 

4.  ![XKCD, Funny things for everything.] (https://imgs.xkcd.com/comics/real_programmers.png)

5. Playing with the new dog age formula: 

```
function dogHumanYears()  {
	let humanAge = 0;
	let dogAge = 0;

	humanAge = 16 * Math.ln * (dogAge) + 31};`
```

6. The mac key shortcut for clearing the terminal is `ctrl + l`

7. I'm currently working on a few personal projects like a powerlifter calorie builder and reactive workout journal, a roommate bill collater hub, and a pomodoro light changing app. 

8. Also, @JR, IT'S NATIONAL DOG DAY.

----

- Commit message development

- Understanding the engineering of data

- Understanding how data to relates front-end and back-end

- group work on problems in class

- 10-10-10 challenges

- Slack ask-for-help channel

- edabit.com

- phone apps to study while waiting in line etc:

* Grasshopper

* JavaScript Quiz

* W3schools

- The most fun part for Erick is using npm packages!

- API integrations such as Auth0 and google apps.

- We can transfer our React knowledge to make IoS apps via React Native.

- I had a side project where I made a hex color randomizer that showed the color in the background 
   and provided its hex code on screen.

- An anonymous vegan baconator has achieved a fully hosted full stack web app!

- There are other types of stacks to learn, such as JAMstack which sounds delicious.

- Weekly challenges have been very helpful as practice.

- Slack is a ton of knowledge and helps connect at anytime outside of class hours.

- I'm very proud of my portfolio template (Although I haven't added the actual data yet)

<https://hollisjamison.github.io>

- Also proud of my week 12 homework that I managed to leverage React + Bootstrap + Express + MongoDB + Heroku for a full stack deployed "app"

<https://week-12-homework.herokuapp.com/>

Also outside of class I put together an Express + EJS movie site which allows you to search for movies and displays movie posters and IMDB info

<https://github.com/hollisjamison/movie-passport>

- We can transfer our React knowledge to make IoS apps via React Native.

- I had a side project where I made a hex color randomizer that showed the color in the background and provided its hex code on screen.

- An anonymous vegan baconator has achieved a fully hosted full stack web app!

- There are other types of stacks to learn, such as JAMstack which sounds delicious.

1. After completing the React tutorial and successfully re-creating the tic-tac-toe game, I find React very interesting and am excited to learn more and implement it in the future!

---- 

1. React storefront pulling in and showing data from another port such as week 10 API store manager.  Fetch() function

Fun fact: The meaning of a response code from the server varies from API to API, and oftentimes checking response.ok might not be enough. For example, some APIs will return a 200 response even if your API key is invalid. Always read the API documentation!

<https://www.sitepoint.com/introduction-to-the-fetch-api/>

2. I like how easy it is to setup tables in react using bootstrap

<https://react-bootstrap.github.io/components/carousel/>

I like the carousel where the component cycle through the slides

