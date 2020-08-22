<html>
<head>
</head>
<body>
<script>
function selection()
{
var z=document.forms.genders;

for(i=0;i<z.length;i++){
if(z[i].checked==true)
return true;
}

document.getElementById("rone").innerHTML="Select any one option";
return false;


var t=document.forms.bawa;
for(i=0;i<t.length;i++){
if(t[i].checked==true)
return true;
}
document.getElementById("pp").innerHTML="Atlease select any one";
return false;
}
</script>
<form name="forms" onsubmit="return selection()">
Gender<input type="radio" value="Male" name="genders">Male
<input type="radio" value="Female" name="genders">Female
<input type="radio" value="Other" name="genders">Other
<p id="rone" style="color: red"> </p>
</br>
SELECT<input type="checkbox" name="bawa" value="share">share
<input type="checkbox" name="bawa" value="comment">comment
<input type="checkbox" name="bawa" value="like">like
<input type="checkbox" name="bawa" value="block">block</br></br>

<p id="pp"> </p>

<input type="submit" value="submit">

</form>
</body>
</html>
