# edxtestrepo
<html>
<head>
<title> Simple Interest and Compound Interest</title>
</head>
<body>
<table>
<tr>
<td>Amount <input type="text" name="a" id="first" placeholder="Enter principal"/> </td>
</tr>
<tr>
<td> Rate of Interest<input type="text" name="b" id="second" placeholder="Enter rate of interest(%) "/> </td>
</tr>
<tr>
<td> No of Years<input type="text" name="c" id="third" placeholder="Enter time period"/> </td>
</tr>
<tr>
<td> <button onclick = "simple_interest()" >Compute</button> </td>
</tr>
</table>
<div id="num"> </div>
</body>
<script type="text/javascript">
function simple_interest()
{
var p,t,r,si,ci;
p = document.getElementById ("first").value;
t = document.getElementById ("third").value;
r = document.getElementById ("second").value;
si = parseInt((p*t*r)/100 );
amount = p*Math.pow((1 +r/100),t );
document.getElementById ('num').innerHTML ="Simple interest : "+si;
}
</script>
<p>&copy; Everyone Can Get Rich</p>
</html>
