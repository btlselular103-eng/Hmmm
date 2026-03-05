# Hmmm
Something
<!DOCTYPE html>
<html>
<head>
<title>Access</title>

<style>
body{
background:black;
color:white;
font-family:Arial;
display:flex;
justify-content:center;
align-items:center;
height:100vh;
}

.box{
background:#111;
padding:30px;
border-radius:10px;
text-align:center;
}

input{
padding:10px;
margin-top:10px;
width:200px;
}

button{
padding:10px;
margin-top:10px;
cursor:pointer;
}
</style>

</head>

<body>

<div class="box">

<h2>UfEAcbae</h2>

<input type="password" id="codeBox" placeholder="Enter code">
<br>
<button onclick="checkCode()">Submit</button>

<p id="message"></p>

</div>

<script>

function checkCode(){

let code = document.getElementById("codeBox").value;

if(code === "NyXTvutx"){
window.open("https://drive.google.com/drive/folders/1PsfetoNrBnnZKJfXmgSYzsTsaep_RXC3", "_blank");
}

else if(code === "Conceal"){
window.open("https://drive.google.com/drive/folders/1avXZGAJ8vFJAAbkx1YkMAF0mP68ek7u_", "_blank");
}

else{
document.getElementById("message").innerText = "Incorrect code";
}

}

</script>

</body>
</html>
