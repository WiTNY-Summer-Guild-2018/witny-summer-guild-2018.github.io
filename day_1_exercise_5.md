## Coding... with files!

Up till now you've been coding in this nice tool in your web browser.

This is super useful, and a lot of developers use tools like this to try out code and practice what they want to build -- just like we are doing here.

But usually, programs are saved in files.

JavaScript, the programming language, and HTML, the mark-up language for web page structure, are often written in the same file!

Depending upon what programming language you are using, there are different ways to make it *run* -- to see the output, result.

### Seeing HTML results with files

For HTML files, that's not a programming language -- it's a way of structuring the page. There are two different kinds of software programs you can open HTML files in:

* A **text editor**.
  * You have one called Sublime Text on your machine! Text editors are like Microsoft Word, except they have special ability to show your code in useful colors, just like that online tool.
  * And they can save files with all different *file types*, which is what tells *your computer* what kind of file it is (is it a file with HTML, and maybe JavasScript? or is it a file with Scratch programming in it? or is it an essay you wrote in Word? etc.)
  * So a text editor will show your HTML code. Just like the left side of the online tool we've been using.

* A **web browser**, just like you use to browse the internet.
  * Web browsers have tools to "interpret" HTML structure, and show the result -- it looking nice -- just like the *right* side of the online tool.


### Remember that website you built?

You clicked on that icon to save the file, but we haven't gone back to that yet.

* Finding the file in your file system

* Opening it up in a text editor (Sublime Text)

  * Wow!

* Opening it up in a browser (Google Chrome)

  * WOW!


### For an extra special trick... (more files)

Let's go back to that complicated JavaScript we were just talking about.

Remember this complicated program?


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

* Open up Sublime Text
* Create a new file in the program
* Copy that code from above
* Paste it into your empty file in Sublime Text!
* Save the file in Sublime Text as the file name `first_javascript_program.html`
  * Note that the end of the name, the *file extension*, has to be `.html` -- because one of the most common ways to get JavaScript to run is to
    * Put JavaScript inside a *script* in an HTML file
    * Write code so that *when the page loads in the web browser*, that's when the JavaScript program will run, to show you output!

* If you've still got time... (if not, that's okay!)
  * Now *edit* that file -- write in the code that you were working on to show the name of the day of the week!
  * Open up the file in Google Chrome, and see what happens!
  * Don't worry if nothing happens, or it doesn't seem to work -- that happens to everyone! You should expect that -- we'll talk about how to fix problems a lot this week.
