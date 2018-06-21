## Introduction to coding concepts and structures

OK. HTML lets you create a web page's structure.

Scratch let you make complex programs that had visible results.

**JavaScript** is another programming language -- and the JavaScript programming language is a specially nice tool for making web pages interactive, and making stuff happen that humans can interact with, see, etc, on a website.

### What is JavaScript, anyway?

* What is it used for?
* How is it different from HTML?
* How is it different from Scratch?
* Or other programming languages that you haven't seen this week?

JavaScript is a programming language you can learn, but it is only one of many.

One of the special things about JavaScript is that a common way to get JavaScript programs to run -- and the one we are going to see today -- is that you can use some special syntax to put them inside a web page that is built with HTML.

First, before we look at the program RUNNING, we're going to look at the ideas behind the code.

---

### Variables in programming languages

* Variables are like names of data
  * Always unique in a program
  * `Jackie`, `Rachel` ... but not OK to have another `Jackie`. Gotta be `Jackie_1` or something else.
  * Some rules about variable names in JavaScript, what the names for data can be (otherwise, your program will give you an error that basically means *ENHHHH, try again*):
    * can't start with a number,
    * only punctuation they can include is `_` (underscores),
    * no spaces
* Remember: Your team names?
* Remember: Your 'Castle' (table location) names?
* Key idea about variables: you can *change* the data attached to that name.

#### For example... let's run some code with people & stuff

---

### Conditional statements

A lot of programming languages, like Scratch, and JavaScript, have ways of controlling *when* something happens in a program. One common useful one is called **conditional statements**, AKA **conditionals**.

JavaScript has syntax to get comfortable with to make *conditional statements* work in a program, but the ideas are what's really important.

IF ...

OTHERWISE, ...

#### For example... let's run some code with people

* Explain what the program should do, exactly
  * People aren't quite as good at doing exactly specific things as computers are...
  * That's part of why programming is so useful!


#### What might this code look like in JavaScript?

```javascript
var first_name = "rachel"

if ("r" in first_name) {
  alert("Hello");
}
if ("r" !in first_name) {
  alert("Clapping my hands");
}
```
or

```javascript
var first_name = "jackie"

if ("r" in first_name) {
  alert("Hello");
}
if ("r" !in first_name) {
  alert("Clapping my hands");
}
```

But in each one of these cases -- these 2 different programs in JavaScript programming language -- something different would happen.

##### Grab a new coding partner in your group -- this time, for talking

* Why do you think something different happens in these two different programs? Come up with an idea.

* Pick two parts of the *syntax* -- the characters and structure of what is typed in those programs -- that you think are confusing. There are probably a LOT -- you've never seen this before! (We expect, anyway!) But pick a couple, and we'll talk about a bunch of them in a little bit.

* Write down those two things that you think are confusing on a post-it note. (Not one of your special 2 post-its, of course.) When you're all set, put the green sticky notes on your computer, and come up to the front and drop your sticky notes here so we can read through them!

##### Some stuff to think about

* Curly braces `{ }`
* Parentheses `( )`
* Where do things go???
* The `!` sign
* The `=` sign
* And more...

##### Discussion


### Functions

JavaScript also has syntax for what are called **functions** -- a bit of code that groups a bunch of actions in a program together.

When you *invoke* the function, you're basically telling the program to do the whole group of actions at once.

Another reason functions are great is because sometimes there are functions built in to programming languages you can *invoke* -- to make complicated actions happen. For example, showing data to you in a little text box!

This is complicated, behind the scenes. But JavaScript has a function (called `alert`) that just lets you show things in a text box pretty easily! So you can do a complicated thing, with just a little tiny bit of code that *invokes* a function.

You'll see more examples of this shortly.

(Always remember, if you encounter a **syntax error** when you write or run code, there are a lot of good ways to figure out what's going on, and fix it, together.)


#### Functions example: dancing the grapevine

* Remember the peanut butter sandwich problem? We could use this idea for that problem, too...

**THE GRAPEVINE DANCE**

* right foot right
* left foot forward
* left foot right
* right foot back
* right foot right
* left foot back
* left foot right
* right foot forward
* right foot right

...


Here's some example code in JavaScript syntax... but it won't really work -- even though JavaScript can do tons and tons of things, it can't move human beings' arms and legs. :)


```javascript
do_the_grapevine("jackie");
do_the_grapevine("rob");
```

#### Questions & some things to think about

* Parentheses
* Function input -- `jackie` or `rob`
* Function name -- what's that about?
  * (Someone picked it, but there are some rules)

---

### A [group function](group_function.md) -- function called `new_group`

*A group of actions to perform -- to get a result!*

* Start in your teams
* If your team name is longer than 12 letters, sort yourselves by first name, alphabetically A-Z, standing... *(for example)*
* Else (otherwise), sort yourselves by height, shortest to tallest *(for example)*
* If you're in the first three (the three shortest, or the three earliest in the alphabet by first name) people in your group, you should go one group clockwise

Now you have new groups of about the same size as your old ones!

We'll perform this function several times during the week so you can talk about things with some folks who aren't on your main team -- just like functions are useful in code...

Let's run it a few times now!

Here's what the code might look like in JavaScript... (pretty different from Scratch!)

```javascript
new_group();
new_group();
new_group();
```

---

### An example of writing and running some JavaScript code

*Run the group function once*

-- Now, in your new group, pick a new partner!

First hang on -- we'll all do an example together.

**Note** the `==` syntax -- that means "equal to", while just one `=` in JavaScript code is really different from math -- it means *i'm storing the data on the right of this equals sign in the name on the left!* Just like when we moved the table...  that was like using one equals sign (`=`)!

Let's run this code, Code (1), in the online tool.

**<u>Code (1)</u>**

```javascript
var num = 4;

if (num == 5) {
  alert("This is five!");
}
else {
  alert("This is not five!");
};
```

What was going on here?

Questions?

Now...

Discuss with your partner/group, and write your answers to QUESTION 1 and to QUESTION 2 on post-it notes.

When you're all done, talk about what you and your partner came up with with everyone sitting at your pod. Do you agree? Do y'all have some different ideas about what might happen and what you could change?

See code 2 and questions below!

- QUESTION 1: **What will this second (next) code, Code (2), show to the user when it runs? How did you figure that out?**
- QUESTION 2: **What part of this code could you change for the code to show something different?**

**<u>Code (2)</u>**

```javascript
var num = 4;

if (num > 5) {
  alert("Big number!");
}
else {
  alert("Small number!");
};
```

----

### Another programming exercise

As you know now, JavaScript is a programming language.

But most programmers and computer scientists DON'T spend most of their time typing. They spend it thinking, talking, solving problems.

So we're not going to do a lot of typing of code yet. Instead, write it on the white board!

#### Intro to Pseudocode

* A super useful tool for problem solving as a programmer
* Structure + English -- worry about syntax later


#### Notes

* the code `new Date()` turns into data that represents a *day* -- whatever day it currently is!

  * So today, it'd have the information **Monday, June 25th, 2018**... for example.

  * You can use functions -- collections of actions -- to get pieces of that information -- like the day of the week, or the month... Though sometimes the *syntax* for using or *invoking* them is a little bit different from what you saw before.

* one of those functions is the `getDay` function, which returns (gives as its result) a number: 0, 1, 2, 3, 4, 5, or 6.

  * 0 means Sunday, 1 means Monday, 2 means Tuesday... and so on!

##### Here's some new code, using tools JavaScript provides:

Given the above information, what do you expect this code to show you?

```javascript
var today = new Date(); // creates a new Date thing saved in a variable called today
var day_of_week = today.getDay(); // *Invoking* the getDay function with the data stored in the today variable -- to get # info about what day it is!

alert(day_of_week);
```

**Now: After understanding that new code with the JavaScript date tools that you're given, and having practiced your if/else statements... (remember the exercises from earlier!)**

* Make a pseudocode plan with a coding partner:

How can you write some code to show you, with the `alert` function, not just a number, like `2`, but the right name of the weekday, like `Tuesday`! How can you write the code so it will work EVERY day -- tomorrow it'll show `Wednesday`, the day after, `Thursday`, and so on! (Today it should only show `Monday`, but if you ran the code tomorrow, it should show `Tuesday`.)

HINT: What should be true IF it shows Monday?
HINT: What function did we see in JavaScript that shows a text box with information?

* Try writing that code -- on your dry erase board! Don't worry if you don't know the right syntax, but think about what you will need to look up later! (Later we'll actually see code that does this run.)

  * Most programming -- not even about computers
  * Just about solving problems
  * Computers happen to be a useful tool to show things, save things, type things, communicate with, and do computations with -- but *programming* isn't all about computers!

---

### (If time) Trying it out...

Let's take a look at how all of this goes together.

Click on [this link](https://www.tutorialrepublic.com/codelab.php),

delete everything in the left box,

and [copy and paste](copy_and_paste.md) the following code into the left box (click that link for instructions how to copy and paste if you want them),

in order to try it out.

There's a whole lot here you've never seen before! It's pretty complicated. But we can break it apart into smaller, easier pieces.

First, try it out by copying and pasting it into the online tool.

```javascript
<html>
<script>
  function show_day_of_week() {
    var today = new Date();
    var day_of_week = today.getDay();
    alert(day_of_week);
  };
</script>
<body onload="show_day_of_week()">Hello everyone</body>
</html>
```

*Grab a coding partner...*

**Try to list three things that are different about this code than the code you've seen before.**

1. ____________
2. ____________
3. ____________

Write them down on the provided worksheet!

**CHALLENGE:** Each time you identify something that's different about *this* code from the code you saw in the exercise just before, that we ran together, that alerted `2` -- something big that's different, or something small -- also think about *why* it's different. Why do you think this has stuff the other code from before doesn't have? What's going on?

What are some clues you can identify -- why would we write *this* code instead of just what we had before?

Wasn't what we had before a little clearer, with less junk all around it?

This is really tricky! It's like a puzzle + detective work.
