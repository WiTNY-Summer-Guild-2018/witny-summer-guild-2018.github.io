## Introduction to coding concepts and structures

OK. HTML lets you create a web page's structure.

Scratch let you make complex programs that had visible results.

**JavaScript** is another programming language -- and the JavaScript programming language is a specially nice tool for making web pages interactive, and making stuff happen that humans can interact with, see, etc, on a website.

### What is JavaScript, anyway?

* What is it used for?
* How is it different from HTML?
* How is it different from Scratch?
* Or other programming languages that you haven't seen this week?

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

#### For example...

---

### Control statements & functions

A lot of programming languages, like Scratch, and JavaScript, have ways of controlling *when* something happens in a program. One common useful one is called **conditional statements**, AKA **conditionals**.

JavaScript has syntax to get comfortable with to make *conditional statements* work in a program, but the ideas are what's really important.

IF ...

OTHERWISE, ...


JavaScript also has syntax for what are called **functions** -- a bit of code that groups a bunch of actions in a program together, and, when you *invoke* the function, you're basically telling the program to do the whole group of actions at once.

Another reason functions are great is because sometimes there are functions built in to programming languages you can *invoke* -- to make complicated actions happen. For example, showing data to you in a little text box! This is complicated, behind the scenes. But JavaScript has a function (called `alert`) that just lets you show things in a text box pretty easily! So you can do a complicated thing, with just a little bit of code.

You'll see more examples of this shortly.

(Always remember, if you encounter a **syntax error** when you write or run code, there are a lot of good ways to figure out what's going on, and fix it, together.)

---

### Let's run some code with *people*

#### Conditionals example: if/else

* *If your first name has an 'a' in it...*

(Asking a bunch of individuals -- running the code each time)


#### Functions example: dancing the grapevine

* Remember the peanut butter sandwich problem? We could use this idea for that problem, too...

---

### A group function -- function called `new_group`

*A group of actions to perform -- to get a result!*

* Start in your teams
* If your team name is longer than 12 letters, sort yourselves by first name, alphabetically A-Z, standing... *(for example)*
* Else (otherwise), sort yourselves by height, shortest to tallest *(for example)*
* If you're in the first three (the three shortest, or the three earliest in the alphabet by first name) people in your group, you should go one group clockwise

Now you have new groups of about the same size as your old ones!

We'll perform this function several times during the week so you can talk about things with some folks who aren't on your main team -- just like functions are useful in code...

---

### JavaScript code -- a breakout exercise

*Run the group function once* -- Now, in your new group:

**Note** the `==` syntax -- that means "equal to", while just one `=` in JavaScript code is really different from math -- it means *i'm storing the data on the right of this equals sign in the name on the left!* Just like when we moved the table...  that was like using one equals sign (`=`)!

Discuss:
- **What will this first code, Code (1), show to the user when it runs? How did you figure that out?**
- **What part of this code could you change to make the code to show something different?**

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

Discuss:
- **What will this second (next) code, Code (2), show to the user when it runs? How did you figure that out?**
- **What part of this code could you change for the code to show something different?**

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

**Notes:**

* the code `new Date()` turns into data that represents a *day* -- whatever day it currently is! (So today, it'd have the information **Monday, June 25th, 2018**... for example.) You can use functions -- collections of actions -- to get pieces of that information -- like the day of the week, or the month...
* one of those functions is the `getDay` function, which returns (gives as its result) a number: 0, 1, 2, 3, 4, 5, or 6.
  * 0 means Sunday, 1 means Monday, 2 means Tuesday... and so on!

**Here's some new code, using tools JavaScript provides:**

Given the above information, what do you expect this code to show you? (Discuss in groups.)

```javascript
var today = new Date(); // creates a new Date thing saved in a variable called today
var day_of_week = today.getDay(); // *Invoking* the getDay function with the data stored in the today variable -- to get # info about what day it is!

alert(day_of_week);
```

**Now: After understanding that new code with the JavaScript date tools that you're given, and having practiced your if/else statements...**

* Make a plan in your group: How can you write some code to show you, with the `alert` function, not just a number, like `2`, but the right name of the weekday, like `Tuesday`! How can you write the code so it will work EVERY day -- tomorrow it'll show `Wednesday`, the day after, `Thursday`, and so on!

* Try writing that code -- on your dry erase board! (Later we'll actually see it run.)

  * Most programming -- not even about computers
  * Just about solving problems
  * Computers happen to be a useful tool to show things, save things, type things, communicate with, and do computations with -- but *programming* isn't all about computers!

---

### Try it out...

Let's take a look at how all of this goes together.

Click on [this link](https://www.tutorialrepublic.com/codelab.php),

delete everything in the left box,

and copy and paste the following code into the left box,

in order to try it out:

```javascript
<html>
<script>
  function show_day_of_week() {
    var today = new Date(); // creates a new Date thing saved in a variable called today
    var day_of_week = today.getDay();
    alert(day_of_week);
    // Here is where you could put the code you just wrote, to make it work, and show the actual name of the day!
  }
</script>
<body onload="show_day_of_week()">Hello everyone</body>
</html>
```

OK: What's going on here?

**Try to list three things that are different about this code than the code you've seen before.**

1. ____________
2. ____________
3. ____________

**CHALLENGE:** Each time you identify something that's different about this from the code you saw in the exercise just before, that alerted `2` -- big, or small -- why do you think it's different? What's useful about this code? What are some clues?

This is really tricky! It's like a puzzle + detective work.
