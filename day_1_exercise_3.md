## HTML Exercise: Build a small web page!

By knowing how to look up stuff about HTML, you know enough to build a web page!

## **YOUR GOAL:** Build a small web page about your favorite book / movie / animal / music / artist / sports team...

Whatever you want!

*Reminder:* Click the auto-update button on the HTML display tool in your browser!

#### **Your web page should have:**
* At least 2 headings, one `h1` and one `h2` or `h3` to separate out pieces of the information on the page.

* At least 1 un-ordered / bulletpoint list with some information.

* Space out your text using line breaks or paragraphs -- whatever you want!

* Include a hyperlink to the WiTNY website with the text *Made at WiTNY Summer Guild* -- like this: [Made at WiTNY Summer Guild](http://www1.cuny.edu/sites/women-in-technology/).
  * The URL is: `http://www1.cuny.edu/sites/women-in-technology/`

* Finally, embed a gif in the page with the `id` attribute `first-gif`. (See below!)

* *Add any other structure or styling you want!*
  * Check out the examples and see if you can model after those
  * Talk to each other, a lot -- most programmers learn almost everything by talking to people they work with and friends. It's too hard to learn on your own!
  * If you have questions about using any HTML tags, or trying to work with colors, let an instructor know and we'll help you out!

* Download the file onto your computer when you are done by clicking the little icon that looks like this: <img src="https://www.dropbox.com/s/0ahdpfytzy6h4ei/Screenshot%202018-06-12%2014.25.56.png?dl=0"> at the top of the page (<img src="https://www.dropbox.com/s/iqalx69kucg7f9b/Screenshot%202018-06-12%2014.26.25.png?dl=0">)

### How to embed a gif in your web page

1. Go to [giphy](https://giphy.com/) -- `giphy.com` -- and search for whatever you want. Cats? Los Angeles Lakers? Black Panther?

2. When you find a gif you want, put your cursor on it, and click on the little paper-clip looking icon, like this:

![Image of link icon to click on](https://www.dropbox.com/s/x3orli7y6y961b9/Screenshot%202018-06-12%2014.33.20.png)

That will automatically *copy* the link of the gif.

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

Remember, `img` tags don't need to have a second tag the way most other HTML tags do, because it's just rendering the image -- not doing anything about *text* on the page.

There is other stuff you can add into the HTML -- for example, to make it accessible for Screen Readers, software tools that people use on computers if they are blind or can't see the screen well.

OK, almost done --

We want to identify this picture specifically with what's called an `id` attribute, so later, we could write some code that makes this gif -- have a red border, or disappear when you click a button! (We'll get to that stuff later.)

Edit the HTML so it looks like this (your URL will be different from this one, of course, because it's the URL for the gif YOU chose):


```
<img id="first-gif" src="https://media.giphy.com/media/3oKIPaSkwgwHz5wpZC/giphy.gif">
```

And done! Check out the output.

Note that you won't see anything representing that `first-gif` id. That's a behind-the-scenes thing for you, the programmer -- so you, or someone else, can do more specific things with the web page you created!
