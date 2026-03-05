# Hmmm
Something
<!DOCTYPE html>
<html>
<head>
<title>UfEAcbae</title>

<style>
body{
background:black;
display:flex;
justify-content:center;
align-items:center;
height:100vh;
font-family:Arial;
color:white;
}

.box{
text-align:center;
}

input{
padding:10px;
font-size:18px;
border-radius:5px;
border:none;
outline:none;
}

button{
padding:10px 20px;
font-size:18px;
margin-left:10px;
cursor:pointer;
}
</style>

<script>
function cekKode(){
var kode = document.getElementById("kode").value;

if(kode === "NyXTvutx"){
window.location.href="https://drive.google.com/drive/folders/1PsfetoNrBnnZKJfXmgSYzsTsaep_RXC3";
}

else if(kode === "Conceal"){
window.location.href="https://drive.google.com/drive/folders/1RG-tTTqOjUfVC-Icwf88DYH6BULvgGFF";
}

else{
alert("Kode salah");
}
}
</script>
</head>

<body>

<div class="box">
<h2>UfEAcbae</h2>

<input type="text" id="kode" placeholder="Masukkan kode">
<button onclick="cekKode()">Enter</button>

</div>

</body>
</html>
