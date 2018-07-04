The following code is to DEBUG.

Ideally, the page structure should look like this:

![Image of the page]()

And player 2 should win with **scissors**.

But that's not quite what happens as-is...



```html
<!DOCTYPE html>

<head>

<title>Rock Paper Scissors Game</title>

<script>
	  var playerOne = "paper";
    var playerTwo = "scissors";

    if (playerOne == "rock" & playerTwo == "scissors") {
        alert("Player One wins - with rock!");
    }
  	if (playerOne == "scissors" & playerTwo == "rock") {
          alert("Player Two wins - with rock!");
      }
      if (playerOne == "paper" & playerTwo == "rock") {
          alert("Player One wins - with paper!");
      }
      if (playerOne == "rock" & playerTwo == "paper") {
          alert("Player Two wins - with paper!");
      }
      if (playerOne == "paper" & playerTwo == "scissors") {
          alert("Player Two wins - with scissors!");
      }
      if (playerOne == "scissors" & playerTwo == "paper") {
          alert("Player One wins - with scissors!");
      }  
</script>
</head>
<body>
    <h1>Rock Paper Scissors!</h1>
    <p>The JavaScript program in this page should make a Rock Paper Scissors game happen... <br><b>super fast!</b></p>

    <h2>There are two players...</h2>

    <ul>
        <li>Player 1</li>
        <li>Player 2</li>
    </ul>
</body>
</html>
```
