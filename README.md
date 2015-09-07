# PR1_Zyankina_Individual
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" type= "text/css" href="css/style.css">
<script type = "text/javascript">
var r=0;

setInterval(function() {
    var l = document.getElementById("js-rotor");
    l.style.transform="rotate("+r*10+"deg)";
    l.style.borderColor="rgb("+ r%255 + "," + (r*7)%255+","+(r*3)%255+")";
    r++;
}, 100);

</script>

</head>
<body>
 
<div class="css-rotor"></div>

</body>
</html>
