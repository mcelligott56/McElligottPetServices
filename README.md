<html>
<head>
<title><strong>Introduction</strong></title>
</head>

<body>
My name is Denis McElligott. This is my first GitHub Project. Let me know what you think.

<p>A script on this page starts this clock:</p>
<p id="demo"></p>

<script>
var myVar=setInterval(function(){myTimer()},1000);

function myTimer()
{
var d=new Date();
var t=d.toLocaleTimeString();
document.getElementById("demo").innerHTML=t;
}
</script>

</body>
</html>

</html>
