## **Exercise 1**

Take a look at this Javascript code. What do you think it does?

Do you notice any *new* function names that you haven't seen before? What is your guess about what they do?

(For a reminder of try it out, keep reading the exercise!)

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

To see that JavaScript code run, how will you need to put those two things together? Where specifically should you put the JavaScript code inside this HTML?

By default, JavaScript code that is inside `<script>` **tags** at the top of an HTML web page will run *right when the web page loads in a web browser*. Which, on many computers, but not all, happens so fast we humans can't even blink before it happens!

That's pretty much what will happen here.

Go to [this web page](https://www.tutorialrepublic.com/codelab.php?topic=html&file=simple-document), the same online tool you used on Monday! Make sure to click the **Auto-update** box in the lower right corner so it's easy to automatically see the result of what you type.

### How to copy and paste code in the online tool

* Delete everything in the left box, all the text!

* Copy and paste that HTML in.
  * (Remember: Highlight the HTML here on this page, go to Edit -> Copy in the top menu, or hold the Control button and just press the **C** key once. Then, go to the online Tutorial Republic page. Click in the left box, which shouldn't have anything in it anymore. Then in the top menu, go to Edit -> Paste, OR hold the Control button again and press the **P** key once.)

* THEN, copy and paste the JavaScript code from above -- *right* after the first `<script>` tag in the HTML, and see what happens.

* Is there something else you want to try with this code? Try it out! Make a change or two in the online tool, and see what happens.

---

This is an example of putting pieces together when you build websites with code -- one of the trickiest parts, but also one of the most important, after you keep learning about new tricks for building things.
