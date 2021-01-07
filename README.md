<!doctype html>
<html lang="en">
<title>Rick Rolled</title>
<head>
<h1 style="color:blue;">Hi</h1>
</head>
<body style="background-color:yellow;">
<h1 style="color:red;">Never Gonna Give You Up - Rick Ashley(the man)</h1>
<b style="color:green;">Lol get Rick Rolled</b>
<p>
<a href="https://www.youtube.com/watch?v=DLzxrzFCyOs">Click Here</a>
</p>
<p>Hate the color?</p>
<script>
var colors = ["red", "blue", "green", "yellow", "purple", "orange", "pink"];
    var colorIndex = 0;
    function changeColor() {
        var col = document.getElementById("body");
        if( colorIndex >= colors.length ) {
            colorIndex = 0;
        }
        col.style.backgroundColor = colors[colorIndex];
        colorIndex++;
    }
</script>
    <body id='body'>
    <button onclick="changeColor();">Change color</button>
    </body>
<p>
<img src="The Man.jpg" alt="Rick Himself" width="1000" height="600">
</p>
<p style="color:yellow">Wow you found me</p>
</body>
</html>
