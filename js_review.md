### JavaScript programs (and HTML)

First, take a look at the following pieces of code that you're answering some questions about. Note that these programs ON THEIR OWN won't run.

They have to be inside a web page to run -- and we have to set everything up so that it runs when the page loads.

There are LOT of different ways to set up JavaScript programs so that they run. But this is the first one you'll see, here.

First, just the code in the JavaScript programs.

**<u>Code (1 - WON'T RUN ON ITS OWN)</u>**

```javascript
var num = 4;

if (num == 5) {
  alert("This is five!");
}
else {
  alert("This is not five!");
};
```


**<u>Code (2 - WON'T RUN ON ITS OWN)</u>**

```javascript
var num = 4;

if (num > 5) {
  alert("Big number!");
}
else {
  alert("Small number!");
};
```

The NEXT sets of code will each run, because they are correctly included in web pages made with HTML.

**Code (1), inside a web page to run**

```html
<html>
<script>
  var num = 4;

  if (num == 5) {
    alert("This is five!");
  }
  else {
    alert("This is not five!");
  };
</script>
<h1>Hello world</h1>
</html>
```

**Code (2), inside a web page to run**

```html
<html>
<script>
  var num = 4;

  if (num > 5) {
    alert("Big number!");
  }
  else {
    alert("Small number!");
  };
</script>
<h1>Hello world</h1>
</html>
```

**More challenging Code (3) -- with new structures and new functions**

*If you want to jump a bit ahead of where we are right now*

[Check out this code and info](challenge_js.md)

---

#### NOTE:

If you copy and paste (if you don't remember how to do that, [check out this resource](copy_and_paste.md)) each WHOLE chunk of code as the only the in the left side of the [online tool](https://www.tutorialrepublic.com/codelab.php?topic=html&file=simple-document), you'll see the code run!

It may or may not have an exciting result, but it will definitely run.

You can find the [online tool](https://www.tutorialrepublic.com/codelab.php?topic=html&file=simple-document) -- the same tool you wrote your websites in! -- HERE: [https://www.tutorialrepublic.com/codelab.php?topic=html&file=simple-document](https://www.tutorialrepublic.com/codelab.php?topic=html&file=simple-document)

Remember that this tool does NOT auto-save, but you CAN download the file with your work in it as an `.html` file. (We have not worked with these, but this is the only way to save your work!)

Also note that when you are running JavaScript programs, sometimes it's nice NOT to click auto-update -- so you know that you will see the NEW result when you type something new once you click **Show Update**.
