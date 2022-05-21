# Welcome to Code With Mezcla

Visit:

`https://try.turing.edu/mezcla/`

and follow the sections in the Welcome section to get set up.

---

# Goals

- Build and customize an [interactive website](https://mezcla-checkpoint-3.turingschool.repl.co)
- Gain _exposure_ and familiarity with some HTML, CSS, and JavaScript
- Determine if coding is something you enjoy doing and want to pursue further
- Meet other Latin@s working in tech and curious about tech

---

# What to Expect

- Welcome and Setup (1 hour)
- Instruction (2 hours and 30 minutes)
- Lunch Sessions (1 hour)
- Group Challenge (1 hour and 30 minutes)
- Presentations and Wrap-Up (1 hour)

12:30 MT as a hard-ish stop for the morning.

---

# Online Learning Norms

- Ask your questions and share your code!
- Mute your microphone unless you’re the main speaker.
- Keep your camera on during class.
- Disconnected? Jump back on! The host or TA will resume the session shortly.


---

# Asking Questions

Want to get my attention during the workshop?

* Raise your hand
* Type your question in the chat
* Come off mute and ask!

---

# Replit.com

![inline](./assets/replit-interface.png)

---

# Warm-Up Activity

See Mezcla site for a scavenger hunt!

---

# Share Out!

* **Zoom Chat**
* **Raise Hand**

---

# BREAK

---

# Breakout Introductions

In alphabetical order by first name, please share:

* Your name
* Your pronouns
* Your location
* Why did you decide to join this workshop today?

---

# Overview Reminder

- Welcome and Setup (1 hour)
- Instruction (2 hours and 30 minutes)
- Lunch Sessions (1 hour)
- Group Challenge (1 hour and 30 minutes)
- Presentations and Wrap-Up (1 hour)

---

# Programming Languages

What will we use to build a web page?

* HTML
* CSS
* JavaScript

Three things!

---

# HTML


* HTML wraps and describes the content we see on a page.
* HTML says "That's a paragraph! That's a bulleted list! That's a heading!"
* Can think of HTML as the skeleton of our webpage.

---

# CSS

* CSS defines the look and feel of a webpage
* CSS says "That paragraph should be blue! That header should be big! Those images go on the left!"
* If HTML is the skeleton, CSS is our skin, hair, clothes, style, etc.

---

# JavaScript

* JavaScript lets users interact with a page.
* JavaScript says "The user clicked something! Let's display a dropdown!"
* JavaScript is the brain and muscles of our webpage.

---

# Be Nice to Yourself

* This might be your very first day working with code.
* Learning is often uncomfortable!

---

# What to do when things break

- Did you spell everything correctly? Capitalization matters!
- Do you have closing symbols for every opening symbol? Every opening bracket needs a matching closing bracket.
- Do the colors follow a predictable pattern? If the colors are consistent and then all of the sudden change, it could be a clue that something isn't quite right.

---

# Project Setup

See Mezcla site to get set up for the upcoming sections!

---

# HTML

HTML is our skeleton.

---

# Tour the Existing HTML

See replit.com to tour the HTML together.

---

# Explore to Learn:

- What line numbers in the HTML file are responsible for the text displayed in the browser?
- What organizational structures do you notice?
- Try commenting out a line of code! Highlight a section of the code and use `cmd + /` to comment out that line. Then click the green `Run` button. What happens? Highlight it again and use the same keyboard shortcut to undo it!
- What might be the purpose of the `class` that appears on some of the elements?

---

# Breakout

See Mezcla site.

Work together!

---

# HTML Summary

- Elements that live inside of the `body` tags will be displayed on the page.
- We can nest elements inside of other elements to create structure within the HTML.
- Classes allow us to give each element a specific label so that we can reference that element later.
- The number of elements and the content inside of the elements in the HTML file usually have a 1-to-1 correlation with what we see in the browser.

---

# CSS

CSS allows us to "dress up" the content on our page.

---

# Tour the Existing CSS

Replit

---

# Explore to Learn

- On line 2 of the `style.css` file, change `#db8a74` to `goldenrod`
- On line 8, change `#fac9b8` to `white`
- On line 12, change `70%` to `40%`
- On line 18, change `30px` to `50px`

---

# Add a New CSS Rule

Don't want the definitions visible when the page first loads.

Add: `visible: none;` to the last line of the `.card-text` CSS rule

---

# Setting up for the future

We also want to add these CSS rules:

```css
.show-text .card-text {
  display: block;
}
.show-text .card-btn {
  transform: rotate(180deg);
}
```

Question: why don't these impact the way our page is displayed yet?

---

# Checkpoint

See the Mezcla site for a checkpoint!

---

# Breakout

See Mezcla site.

---

# CSS Summary

- CSS allows us to target an element and write specific rules for it to follow.
- Based on the type of rule, CSS will expect different values.
- For example, `goldenrod` or a hex code for a color and `10px` or `50%` for a measurement.
- We don't need to memorize all the rules.

---

# Reflect

* Before JavaScript, websites used to be built with only HTML and CSS.
* You can still build a site that delivers value without JavaScript!

---

# JavaScript

JavaScript is the part of the code that controls user interaction.

---

# Data Types

Data types are *types* of *things*. E.g. strings and numbers.

```js
// A string example
'I am a string!'
"I can hold emojis: 💥🦄✨, lots of spaces:     , and special characters: $#@%"

// Numbers
4 + 2
7 * 3
```

---

# Variables

Variables allow us to store information in a container with a label.
We can then use that label to reference the contents of that container.

In JavaScript, we declare variables using the `var` keyword:

```js
var firstName = 'Sal';
var age = 21;
var school = 'Turing School of Software & Design';
```

---

# console.log()

The `console.log()` method to print the data we are working with out to the console in replit.

```js
var firstName = 'Sal';
var age = 21;
console.log(firstName);
console.log(age);
```

---

# Arrays

Arrays are collections of items that belong together.

* For example, we could have an array of strings, where each string is a friend's name.
* We could have an array of numbers, one number for each friend's age.

```js
var friends = ["Jessica", "Jerome", "Jorge", "Chema"]
var ages = [21, 23, 22, 25]
```

---

# Why arrays?

Arrays allow us to do things multiple times, for each *element* of the array.

```js
"Hi, Jessica!"
"Hi, Jerome!"
"Hi, Jorge!"
"Hi, Chema!"
```

We would use the method `forEach` allows us to do the same thing to each element of an array.

---

# Breakout: Variables

See Mezcla page.

---

# JavaScript Summary

- Variables allow us to store information in a container with a label.
- Arrays are a collection of items that belong together.

----

# Event Listeners

[Fork this replit](https://replit.com/@turingschool/javascript-event-listeners#index.html)

- How many HTML elements are creating the elements that appear in the browser?
- Which HTML element already has a class on it? What would be a good name for a class on the other elements?

We'll share out in a moment.

---

# Accessing an HTML Element with JavaScript

We can use JavaScript to access an HTML element and store it in a variable.

* We know variables can point to information to reference later.
* Variables can also point to *parts of the HTML*.
* We use the JavaScript method `document.querySelector` to access that element.

---

# Steps

For example, if we want a variable to represent the `h1` heading at the top of our page, we need to do two things:

1. Add a class to the `h1` element in the HTML.
2. Use the JavaScript method `document.querySelector` to access that element.

---

# Code

```html
<!-- HTML code -->
<h1 class="heading">Puppy Facts</h1>
```

```js
// JS code
var title = document.querySelector('.heading');

console.log(title.innerText);
// "Puppy Facts" will print out to the console
```

---

# Example

If you look the script.js file in our practice replit, you'll notice that those two lines of code are already in there.

- What happens when you run the code?
- What do you think line 10 is doing?

---

# Practice

Our JavaScript "talking to" our HTML code!

Go ahead and follow the directions in your `script.js` file to create a variable for every HTML element, console.log the values, and then reassign the values.

---

# Event Listeners

* When something happens (e.g. when a user clicks on a button)
* Do something (e.g. change the text that is displayed in a header)

We want the content to only change **when the user clicks the button**.

---

# Example

```html
<!-- HTML code -->
<h1 class="header">Puppy Facts</h1>
<button>Change the topic!</button>
```

```js
// JS code
var title = document.querySelector('.header');
var btn = document.querySelector('button');

btn.addEventListener('click', function () {
  title.innerText = "Kitten Facts";
})
```

---

# Breakout: Event Listeners

See Mezcla site!

---

## JavaScript Event Listeners Summary

- We can access an HTML element using the document.querySelector JavaScript method.
- Event listeners allow us to wait for a user action to change something on the page.

---

# Interactive Buttons

We're going to use what we learned about event listeners to make our buttons interactive.

For this next part of the project, watch me first

---

# Steps

See Mezcla Site!

---

# Breakout: Interactive Buttons

---

# JavaScript Interactions Summary

- Everything that changes dynamically on the screen as the user interacts with the web page is all written in JavaScript! It’s a powerful tool and one of the most popular programming languages in the world right now.
- You likely have some gaps in fully understanding the final solution - again, that is OKAY - the goal of this was not to go deep, but spark some curiosity for what is possible!

---

# Survey

See Mezcla Site!
