## JavaScript code - Exercise

Take a look at the following code. Copy it into the codelab tool **[http://bit.ly/codelabtool](http://bit.ly/codelabtool)** and try it out. What happens?

```html
<html>
<script>
    var today = new Date(); // creates a new Date thing saved in a variable called today
    var day_of_week = today.getDay();
    alert(day_of_week);
</script>
<body>Hello everyone</body>
</html>
```

OK... Note that:

Say today is Thursday.

If Sunday is represented by `0`, Monday by `1`, Tuesday by `2` ... then Thursday is represented by the number `4`! Knowing that...

Now, how would you describe what this code is doing?

**How can you edit this code so that, instead of showing a number in the alert, it shows "It's Thursday!" if you run it on Thursday?**

*You should make it so that if you run it on Monday, it will show 'It's Monday!', on Tuesday it will show 'It's Tuesday!', and so on ...*

**HINT:** Remember conditional statements? If ____ , then ??? ... How can you frame those in English, write/draw out your idea, and then translate it to code? Tricky!
