<!DOCTYPE html>
<html>
<body>

<style>
body {
	background-color: #4287f5;
}
</style>

<center>
<img src='https://www.gifimage.net/wp-content/uploads/2018/11/gif-mario-bloc-4.gif' alt='guess' align='middle' class='center'/>
</center>

<center>
<button type = "button" onclick="location.reload();">Try Again</button>

<button type = "button" onclick="window.location.href = 'tp781802.github.io';">Back to Home</button>
</center>

<script>
var number = Math.floor(Math.random() * 10);
var guess = parseInt(prompt('Take a guess (1-10): '));

if (number == guess) {
	alert('You won!')
}
	
if (number != guess) {
	alert('You lost, the right number was ' + number)
}
</script>

</body>
</html>
