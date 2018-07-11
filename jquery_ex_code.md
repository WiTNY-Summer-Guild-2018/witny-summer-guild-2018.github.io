## jQuery Example code

JavaScript code -- with JQuery! A LOT like the code from [Coding Exercise 3](day4_intro_ex3.md), but DIFFERENT:

```html
<!DOCTYPE html>
<html>
  <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
  <body>

    <h1>My First Web Page</h1>

    <h3>Beginning information</h3>
    <p>My First Paragraph</p>

    <p id="demo"></p>

    <p id="new-para"></p>

    <script>
      $(function() {

        $("#demo").text(5 + 6);


      });
    </script>

  </body>
</html>
```
