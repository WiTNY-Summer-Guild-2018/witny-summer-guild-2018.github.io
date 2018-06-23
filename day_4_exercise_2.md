## Introduction to jQuery & more interactive JavaScript

[BACK TO THURSDAY](https://witny-summer-guild-2018.github.io/thursday)

### What IS jQuery, anyway, and why do we care?

It's what's called a "library" in programming -- a bunch of tools that you can use in a programming language that all come together in one big package.

You write a little bit in a web page, for example, that means 'in any JavaScript code we write in this program, it's OK to use the fancy jQuery tools'. This is always the same -- you just look up what to write, or it's provided for you!

Near the top of the HTML, you have to include this line:

```html
<script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
```

That means "Include the jQuery library for use in any programs on this web page. The library lives *here* at this URL, so I'm pointing you to it, programs!"

Then you can use all the special jQuery tools, just by copying and pasting that. It usually goes right after the `<title> </title>` tags of HTML, or if you don't have a title, right near the top after `<html>`.

### So what's an example of a jQuery tool a programmer can use?

*One* of the things jQuery lets you do is write a very simple syntax for something that is complicated if you don't have jQuery.

Remember the code from [this exercise](day4_intro_ex3.md):

```html
<!DOCTYPE html>
<html>
  <body>

    <h1>My First Web Page</h1>

    <h3>Beginning information</h3>
    <p>My First Paragraph</p>

    <p id="demo"></p>

    <p id="new-para"></p>

    <script>
      document.getElementById("demo").innerHTML = 5 + 6;
    </script>

  </body>
</html>
```

This piece of the code:

```javascript
document.getElementById("demo")
```

can be REPLACED with this even simpler code if you are using jQuery in the program:

```javascript
$("#demo")
```

much easier to type!

### OK, but realistically, how do you use this in a program?

**To answer that question, we have to go back a couple steps first.**

Let's think back to [this exercise](day_1_exercise_4.md) from Monday, first. You saw some code that looks like this:

```javascript
<html>
<script>
  function show_day_of_week() {
    var today = new Date();
    var day_of_week = today.getDay();
    alert(day_of_week);
  }
</script>
<body onload="show_day_of_week()">Hello everyone</body>
</html>
```

---

**In your group:** Try to come up with 1 sentence that describes what happens in that code again! How can you explain this as briefly as possible?

When you've come up with that sentence, share it with a coach for feedback on it.

*Coming up with "simple" sentences to describe what happens in code is a really challenging skill -- writing documentation so other people can understand your code, for example, is a really important job, and it's really hard sometimes!*

---

OK, so with that code, you had to look at a couple complicated pieces to figure out where the code you knew about should go:

```javascript
var today = new Date();
var day_of_week = today.getDay();
alert(day_of_week);
```

That's the kind of code you've been writing so far!

To make that run in the web page, you have to put that code inside this bigger structure that you see in the code above -- inside a function, a named collection of actions. There had to be some special markers in the HTML to make the JavaScript code run as soon as the web page loaded.

When you write code with JavaScript and jQuery, you have another type of structure that you put your code inside.


((TBA DIAGRAM of this with arrows and pointers as in notebook...))

```javascript
$(function(){

  // all the code that should go here

});
```

And inside that structure, where `// all the code that should go here` is, you can also use this special `$` character -- to point to parts of the HTML structure and change them!

Just like the code

```JavaScript
document.getElementById("demo").innerHTML = 5 + 6;
```

did -- AKA

```javascript
$(#demo).innerHTML = 5 + 6;
```

### OK... this is weird.

**Let's look at a small example.**

You might remember a little bit from Monday where you were changing some colors with HTML, using some special stuff called "CSS"...

If you want to do something like,

#### "hey, take the data inside the `<h1>` tag and make it blue"

you could write that in code like this, using special jQuery tools to make it easier to write:

```javascript
$("h1").css('color','blue');
```

And we know we need a whole big structure for the page to make that work -- gotta put the code we write inside the structure that will make it work when the web page loads, and will let us use special jQuery syntax to make it easier to write interactive code. You'll see that in the examples, and we'll point it out!

The important thing to note is that THAT ^ line of code is what makes what you want happen.

What do you need to know to write that?

* The tag that the data should go in: `h1`
* There's a function called `css` in jQuery that lets you change the color
* To use the `css` function you have to put two **inputs** in the parentheses, separated by a comma! Like this: `.css('color', 'blue')`
* If you wanted the color to be red, instead, there's only ONE small part of that code you would change: instead of `"blue"`, you would put `"red"`

Those last 3 things? You learn them from reading documentation, or from someone telling you. There's no way to just figure it out!

Reading and putting puzzle pieces together is a huge part of programming -- again, it's not always a lot of computers. Mostly just finding information and thinking about it!

### OK, but seriously, why do we care?

In [the third exercise from earlier](day4_intro_ex3.md), you used JavaScript to put data inside the HTML.

Basically, jQuery allows you to use this same idea -- but using the jQuery "library" for a program in a web page gives you some tools that do a lot of the extra 'programming work' for you, and a lot of useful **functions** (for things like causing text to disappear, or move, or change colors) so it's even easier to write code that does interactive stuff.

#### AND

Up till now we've seen JavaScript code run when a web page loads.

But sometimes, you might want code to run on a different event -- e.g. when a user *clicks* with the mouse in a certain place.

For example... [code like this](https://www.tutorialrepublic.com/codelab.php?topic=jquery&file=execute-a-function-on-click-event).

Here's the HTML and the code, simplified a little so ALL it does is have text that disappears if you click on it, no colors or anything:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Executing a Function on Click Event in jQuery</title>
  <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
  <script type="text/javascript">
    $(document).ready(function(){
        $("p").click(function(){
            $(this).slideUp();
        });
    });
  </script>
</head>
<body>
    <p>Click on me and I'll disappear.</p>
    <p>Click on me and I'll disappear.</p>
    <p>Click on me and I'll disappear.</p>
</body>
</html>
```

Note that some of the code examples you see in this online website tool are quite complex -- they include a bunch of extra stuff that you don't really *need*. One of the hardest things about programming, sometimes, is figuring out what exactly you need and what you don't.

But that's what we're here to help for!
