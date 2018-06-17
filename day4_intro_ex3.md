
## **Exercise 3 - JavaScript + HTML interaction**

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

#### Questions to answer & stuff to try

* The data that appears in this page is pretty boring. What could you change -- what's inside the `h1` tags? The `h3` tags? To make it more interesting?

* What about the JavaScript -- this program adds 5 and 6 together to get 11. What is something that would be cool and interesting to make a JavaScript program come up with or calculate to have show up on a page?

* See how in the JavaScript, it includes the code `document.getElementById("demo")`? **document** stands for the whole web page. **getElementById("demo")** means -- refer only to the part of the HTML on this web page that has the special id attribute **demo**. So we only change one little bit! The `getElementById` function is something else JavaScript has that is super useful for making web pages and products like this.

* Just like before, copy this web page and program into the [online tool](https://www.tutorialrepublic.com/codelab.php?topic=html&file=simple-document) on the left side. Then, **Try to add JavaScript code to this program that puts the word Hello!! on the page, below 11.** HINT: Check out that `<p id="new-para"></p>` bit of code -- right now the Javascript doesn't do anything with that, does it? But it could...

* **HARD CHALLENGE** Try to add JavaScript code to the program to show the result of adding 7 to the date (e.g. if it was the 2nd of July, what should show up should be **9**).

  * Check out Exercise 1 for clues!

  * Consider: why might you want to do a calculation like this? Dream up a situation where something like this might be useful.

  * Talk about this with your coding partner: Maybe you added 7 to the date and you got a number like... 36. That's never going to be a correct date. Why did that happen? How do you think you could fix the problem? If you've got time, you can try... 

    * (This is *super* challenging -- and a really good preview of hard problems people face in Computer Science.)
