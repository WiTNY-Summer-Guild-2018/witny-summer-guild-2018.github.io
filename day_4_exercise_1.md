Remember the [JavaScript exercises]() we practiced on Monday? Here are a few more!

For each one, you should

* Get together with someone else and talk it through.

* Ask yourselves: what do you know about this code right now? What does it do?

* Try it out!

* Then change something about it. Make a prediction about what will happen as a result of that change. Then try it out! Were you right? Were you wrong? Write that down (on a piece of paper, or a dry erase board...)! This is key to learning about JavaScript, or any kind of programming!

* Each exercise asks you to try something specific. Try it out -- but most importantly, talk about it! For each one -- is it working? Or not? What do you think might be wrong? It's easy to be incorrect about that -- that's part of the detective process of coding.

* Recommendation: we've given you links to the same online tool you used on Monday -- we recommend this just for trying stuff out, but remember, whatever you do in the online tool, you could also write and save in your own file in a text editor!

---

**Exercise 1**

Take a look at this Javascript code. What do you think it does?

To try it out, see below!

```javascript
var today_day = new Date();
var weekday_num = today_day.getDay();
var date_num = today_day.getDate();
var year_num = today_day.getFullYear();
if (weekday_num == 0) {
  alert("Today is a Sunday")
}
if (weekday_num == 1) {
  alert("Today is a Monday")
}
if (weekday_num == 2) {
  alert("Today is a Tuesday")
}
if (weekday_num == 3) {
  alert("Today is a Wednesday")
}
if (weekday_num == 4) {
  alert("Today is a Thursday")
}
if (weekday_num == 5) {
  alert("Today is a Friday")
}
if (weekday_num == 6) {
  alert("Today is a Saturday")
}

alert("It is day " + date_num + " of the month");

alert("It is the year " + year_num);
```

Now, take a look at this HTML to make the structure of a web page, which you've seen something very similar to before!

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Simple HTML document</title>
</head>
<script>

</script>

<body>
  <h1>Hello World!</h1>
</body>
</html>   
```

To see that JavaScript code run, how will you need to put those two things together?

By default, JavaScript code that is inside `<script>` **tags** at the top of an HTML web page will run *right when the web page loads in a web browser*. Which, on many computers, but not all, happens so fast we humans can't even blink before it happens!

That's pretty much what will happen here.

Go to [this web page](https://www.tutorialrepublic.com/codelab.php?topic=html&file=simple-document), the same online tool you used on Monday! Make sure to click the **Auto-update** box in the lower right corner so it's easy to automatically see the result of what you type.

* Delete everything in the left box, all the text!

* Copy and paste that HTML in.
  * (Remember: Highlight the HTML here on this page, go to Edit -> Copy in the top menu, or hold the Control button and just press the **C** key once. Then, go to the online Tutorial Republic page. Click in the left box, which shouldn't have anything in it anymore. Then in the top menu, go to Edit -> Paste, OR hold the Control button again and press the **P** key once.)

* THEN, copy and paste the JavaScript code from above -- *right* after the first `<script>` tag in the HTML.

This is an example of putting pieces together when you build websites with code -- one of the trickiest parts, but also one of the most important, after you keep learning about new tricks for building things.

---

**Exercise 2**

As you heard about on Monday, there are TONS of kinds of structure you can do with HTML -- and unfortunately, we don't have anything like enough time to cover them all! Here's a useful one, though: creating a *button* to click on a page.

Check out this HTML:

```html
<!DOCTYPE html>
<head>
    <title>Example of HTML button</title>
</head>
<body>
	<h1>Hello world!</h1>
  <br>
  <button id="btn-one">Click on me</button>
</body>
</html>  
```

To see what the result looks like, go back to [this link]() to see the online tool -- delete everything in the left box, and copy and paste in THIS HTML, just like you did before.

Or, you can open up a new file in the Sublime Text program, and copy this HTML in, and save it as a file name like `new_html_button.html` -- make sure the name ends with **.html**! THEN,

Open up your Chrome web browser, go to File -> Open, and select the file called `new_html_button.html` from your file system. (Then you should be able to see the results in your browser!)

Wow -- a button. *Don't worry that clicking on the button doesn't do anything -- that's EXACTLY what is supposed to happen.*

* **Change the HTML code to make the button display something else -- besides "Click on me".** What do you have to change to make that happen?

* **You'll notice that there's a special id attribute in the <button> tag.** Why might you want to identify parts of a page structure with an *id* -- do you remember what we talked about on Monday? (Go on to the next exercise for more on this.)


*Also note...*

The button is pretty cool. But you can't do anything with it! (Yet.)

Learning how to use special JavaScript tricks (and, if you keep programming, a lot more tricks in JavaScript, HTML, and other languages of all kinds) can help you -- for example -- write code that makes something happen when you click a button (instead of just when the page loads!).

We're going to be looking at an example or two like that a little bit later today, too.

---

**Exercise 3 - JavaScript + HTML interaction**

Remember when you worked with Scratch, and you had to tell the Scratch program what made the program *start* running?

For example, clicking the green flag icon!

And then, with JavaScript code, if it is included in the *script* -- code -- part of an HTML web page, that code runs... as soon as the page is loaded.

So far, most of the JavaScript code you've seen just shows you things with the special `alert()` function provided in the JavaScript programming language, that you can run to see those nice text boxes that appear with info in them.

But you can also write JavaScript code that changes what shows up on the web page -- the data inside the HTML tags, so it looks almost as if the result of the JavaScript program is *automatically* there.

It's not really -- the JavaScript program runs right when the web page loads. But that's *so fast*, a human can barely notice it (without using special tools to slow it down, anyway).

Check out this web page with a JavaScript program inside `<script>` tags:

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

#### Questions

* The data that appears in this page is pretty boring. What could you change -- what's inside the `h1` tags? The `h3` tags? To make it more interesting?

* What about the JavaScript -- this program adds 5 and 6 together to get 11. What is something that would be cool and interesting to make a JavaScript program come up with or calculate to have show up on a page?

* See how in the JavaScript, it includes the code `document.getElementById("demo")`? **document** stands for the whole web page. **getElementById("demo")** means -- refer only to the part of the HTML on this web page that has the special id attribute **demo**. So we only change one little bit! The `getElementById` function is something else JavaScript has that is super useful for making web pages and products like this.

* Just like before, copy this web page and program into the [online tool](https://www.tutorialrepublic.com/codelab.php?topic=html&file=simple-document) on the left side. Then, **Try to add JavaScript code to this program that puts the word Hello!! on the page, below 11.** HINT: Check out that `<p id="new-para"></p>` bit of code -- right now the Javascript doesn't do anything with that, does it? But it could...

* **HARD CHALLENGE** Try to add JavaScript code to the program to show the result of adding 7 to the date (e.g. if it was the 2nd of July, what should show up should be **9**).

  * Check out Exercise 1 for clues!
  * Consider: why might you want to do a calculation like this?
  * Talk about this with your coding partner: Maybe you added 7 to the date and you got a number like... 36. That's never going to be a correct date. Why did that happen? How do you think you could fix the problem?
    * (This is super challenging -- and a really good preview of hard problems people face in Computer Science.)
