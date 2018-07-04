
### How to embed a gif in your web page

1. Go to [giphy](https://giphy.com/) -- `giphy.com` -- and search for whatever you want. Cats? Los Angeles Lakers? Black Panther?

2. When you find a gif you want, put your cursor on it, and click on the little paper-clip looking icon, like this:

![Image of link icon to click on](imgs/linkicon.png)

That will automatically *copy* the link of the gif.

**NOTE:** Your link should look kind of like this: `https://media.giphy.com/media/3oKIPaSkwgwHz5wpZC/giphy.gif` -- a link that describes where THAT GIF lives on the internet, so you can have it show up in your web page. It's easy to find a link like this, too: **https://giphy.com/gifs/marvelstudios-michael-b-jordan-black-panther-3oKIPaSkwgwHz5wpZC** -- and while that WILL let you see the gif on the internet, that's a link to a giphy.com web page -- NOT the link where the gif lives. So if you try to use that one, it won't show up.

(Behind the scenes, it's like: "That's not the place an image or gif lives! That's another web page! Can't show that as image data." So you want to be careful to get the link in the right way.)

3. Go back to your HTML browser window.

4. Click in the text box, and THEN, either click **Edit -> Paste** in the menu, OR, on your keyboard, hold the **Control** button and hit the **P** button. You should see the link you just copied (something sort of like this  `https://media.giphy.com/media/3oKIPaSkwgwHz5wpZC/giphy.gif` ) appear in the text box.

5. Now you need to write HTML to make the gif show up on the web page -- what's called "rendering" the gif. OK!

Wherever you want the gif to be, write the following little bit of HTML:

```
<img src="">
```

That's all!

Then, that URL you copied and pasted?

Copy it again (highlight it, and go Edit > Copy, or **Control** + the key **C**), and paste it *in-between* the quotation marks in that HTML.

**NOTE:** Instructions that tell you what to click, or what to type, can be super confusing if you've never seen them before! They're ALSO a great thing to get used to that can be really confusing in a CS course -- but as soon as you get used to it, will be no problem. *Don't hesitate to ask us if you find instructions confusing! It's GOOD to figure out that they don't make sense -- that's what CS is all about. And a TA or instructor will help you -- that's what we're here for!*

Remember, `img` tags don't need to have a second tag the way most other HTML tags do, because it's just rendering the image -- not doing anything about *text* on the page, so the tags don't need to go on *both sides of* any text.

There is other stuff you can add into the HTML -- for example, to make it accessible for Screen Readers, software tools that people use on computers if they are blind or can't see the screen well.

OK, almost done --

*We want to identify this picture specifically with what's called an `id` attribute, so later, we could write some code that makes this gif -- have a red border, or disappear when you click a button! (We'll get to that stuff later.)* You'll see more about why this is so cool and important later. For now, you won't see any difference in what the image looks like just because you give it a special ID.

**SO, to do this**, you should edit your HTML so it looks like this (*your URL will be different from this one, of course, because it should be the URL for the gif YOU chose*):


```
<img id="first-gif" src="https://media.giphy.com/media/3oKIPaSkwgwHz5wpZC/giphy.gif">
```

And done! Check out the output on the right side of the online tool.

<img src="https://media.giphy.com/media/11sBLVxNs7v6WA/giphy.gif">

Note that you won't see anything representing that `first-gif` id on the page. What you see on the page shouldn't change at all. That `id` is a behind-the-scenes thing for you, the programmer -- so you, or someone else, can do more specific things with the web page you created!

[BACK TO MONDAY](https://witny-summer-guild-2018.github.io/monday)
