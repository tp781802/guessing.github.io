<!DOCTYPE html>
<html>
<body>

<img src='	'>

<button type = "button" onclick="location.reload();">Try Again</button>

<button type = "button" onclick="window.location.href = 'website.html';">Back to Home</button>

<script>

var number = Math.floor(Math.random() * 10);
var guess = parseInt(prompt('Take a guess (1-10): '));

if (number == guess) {
	alert('Winner')
}
	
if (number != guess) {
	alert('Loser, the right number was ' + number)
}
</script>

</body>
</html>
