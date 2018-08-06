## HTML Examples

**Remember:** Use the [CodeLAB tool](http://bit.ly/codelabtool) (**http://bit.ly/codelabtool**) to copy and paste these examples to try them out.

### Table of Contents: Below, you'll find examples of...

* Formatting
  * Bold
  * Italic
  * Underlined
  * Paragraphs
  * Headers
  * Lists
* Links
* Images
  * Specific example: gifs

---

### Formatting

#### Bold

```html
<!DOCTYPE html>
<html>
<head>
</head>

<body>

<b>This text is bold.</b> But this text is not.

</body>
</html>
```

#### Italic

```html
<!DOCTYPE html>
<html>
<head>
</head>

<body>

<i>This text is italicized.</i> This text is not.

</body>
</html>
```

#### Underlined

```html
<!DOCTYPE html>
<html>
<head>
</head>

<body>

You might underline the title of a book, like this: <u>Harry Potter</u>

</body>
</html>
```

#### Paragraphs

```html
<!DOCTYPE html>
<html>
<head>
</head>

<body>

<p>Each of these lines</p>
<p>is on a different paragraph</p>

<p>But check this out.
  Still the same line!!</p>

</body>
</html>
```

#### Headers

```html
<!DOCTYPE html>
<html>
<head>
</head>

<body>

<h1>Header 1, the main header, is the largest</h1>

<h2>There are sub headers like this one.</h2>

<p>Headers are more distinctive and usually bigger than normal text, like this.</p>

<h3>They go all the way down to 6. This is an h3</h3>

<h6>Here's an example of the smallest possible header</h6>

</body>
</html>
```

#### Lists

```html
<!DOCTYPE html>
<html>
<head>
</head>

<body>

<h2>To create lists...</h2>

<ul>
  <li>One item in an un-ordered list</li>
  <li>Bulletpoints</li>
  <li>And so on, one for each item</li>
</ul>

<h3>Or you might want a numbered list -- aka an ORDERED list</h3>

<ol>
  <li>Item 1: HTML is super useful</li>
  <li>Spacing doesn't actually matter, but it makes it easier to read</li>
  <li>And it's important for other humans to understand your HTML</li>
  <li>In lists, you can have as many items as you want. Just remember to close your tags pairs correctly!</li>
</ol>


</body>
</html>
```

### Links

Here are a couple examples of how to create a **hyperlink** in HTML:

```html
<!DOCTYPE html>
<html>
<head>
</head>

<body>

<a href="http://www.google.com">Text to click on</a>

<a href="http://bit.ly/codelabtool">This is a link to the code lab tool</a>

</body>
</html>
```

**NOTE:** Links sometimes *behave* a little bit weirdly in codelab, because you're basically trying to go to a link INSIDE a preview -- so it's like a page inside another webpage! Still, this is how you do it.

The only pieces you can change? The URL inside the quotes, and the text *in between* the tags. The rest has to stay the same for it to work.

### Images

Examples of putting an image in a web page:

```html
<!DOCTYPE html>
<html>
<head>
</head>

<body>

<img src="https://media.giphy.com/media/W3QKEujo8vztC/giphy.gif">

<img src="https://i.ytimg.com/vi/I7jgu-8scIA/maxresdefault.jpg"


</body>
</html>
```

Note that the image has to **live online** -- and have a specific location online -- in order for this to work. So what goes in quotes after the `src`. which means "source", is always a URL here.

Note also that because there's no text data for images, it's just *one* tag to make 1 image show up -- different from all the other examples of tags you've seen, like bold or headers or hyperlinks, where you had to have a *pair* of tags around text.

[Here is an explanation (click here) of how to put a gif in a web page from Giphy.com](howto_gif.md)

### Other sites with even more examples

* [Tutorial Republic resources](https://www.tutorialrepublic.com/html-examples.php) - This is the same site that the CodeLAB tool is from, so it will look familiar
* [w3Schools resources](https://www.w3schools.com/Html/) - CAREFUL -- this tool LOOKS a lot like CodeLAB, but it is VERY easy to lose your work with this website. You can check out the examples here, but you should make sure to paste them into the **CodeLAB** tool you are using.

#### Note

You can "nest" tags, or use pairs of tags together, but this can get complicated and confusing -- remember, always change one thing and then try it, talk through it, draw things out, and ask for help if you are confused about how something works.
