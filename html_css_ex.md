## HTML & CSS Examples

Here are some examples of HTML and CSS together.

Note that the CSS *always* goes inside `<style>` tags.

Check out each of these examples, one at a time, and look at what they do.

Then try to make 1 change, and try it! a couple times.

**Remember:** Use the [CodeLAB tool](http://bit.ly/codelabtool) (**http://bit.ly/codelabtool**) to copy and paste these examples into, to try them out.


```html
<!DOCTYPE html>
<html>
<head>
  <style>
    h1{
        color: blue;
    }
  </style>
</head>

<body>

<h1>To create lists...</h1>

<ul>
  <li>One item in an un-ordered list</li>
  <li>Bulletpoints</li>
  <li>And so on, one for each item</li>
</ul>
</body>

</html>
```

```html
<!DOCTYPE html>
<html>
<head>
  <style>
    body{
      background: green;
    }
    h3{
        color: pink;
    }
    p{
      color: yellow;
      background: black;
    }
  </style>
</head>

<body>

<h3>More stuff</h3>

<p>Here is one paragraph.</p>

<p> Here is another paragraph.</p>

</body>
</html>
```

Also note that the way the CSS is structured refers to specific tags. Every time a css block starts with `h1`, for example, that refers to everything on the web page that is inside an `h1` tag. (There are ways to get more specific, but we'll look at those later!)

Finally, note that by typing the colors, like "pink" or "green" -- is one specific shade of those colors. There IS a way to get specific about what shade -- we'll take a look at that later as well!
