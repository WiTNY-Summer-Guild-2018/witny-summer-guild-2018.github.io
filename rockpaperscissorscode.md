Here's some code to play Rock Paper Scissors in JavaScript. Copy and paste this code into our online tool to see it run.

```html
<!DOCTYPE html>
<head>
<title>Rock Paper Scissors Game</title>

<script>
	var playerOne = "rock";
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
    <p>The JavaScript program in this page should make a Rock Paper Scissors game happen... super fast!</p>
</body>
</html>                            
```
