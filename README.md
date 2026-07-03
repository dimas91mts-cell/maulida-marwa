<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Untuk Maulida Marwa 🤍</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    background:linear-gradient(135deg,#7dd3fc,#60a5fa,#2563eb);
    overflow:hidden;
}

.card{
    width:90%;
    max-width:420px;
    background:#fff;
    padding:30px;
    border-radius:25px;
    text-align:center;
    box-shadow:0 15px 35px rgba(0,0,0,.2);
}

h1{
    color:#2563eb;
    margin-bottom:15px;
}

p{
    color:#555;
    margin-bottom:20px;
}

button{
    padding:15px 35px;
    border:none;
    border-radius:50px;
    background:#2563eb;
    color:white;
    font-size:17px;
    cursor:pointer;
    transition:.3s;
}

button:hover{
    transform:scale(1.05);
}

#pesan{
    display:none;
    margin-top:20px;
    background:#eef6ff;
    padding:20px;
    border-radius:18px;
    line-height:1.8;
    color:#333;
    animation:fade .6s;
}

@keyframes fade{
    from{
        opacity:0;
        transform:translateY(20px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

#akhir{
    margin-top:15px;
    font-weight:bold;
    color:#2563eb;
}
</style>

</head>
<body>

<div class="card">

<h1>Hai Maulida Marwa 🌙</h1>

<p>Ada sesuatu yang mau aku sampaikan...</p>

<button onclick="buka()">Klik di Sini 🤍</button>

<div id="pesan">

<b>Eh, Maulida Marwa...</b><br><br>

Tadi aku sempat kepikiran, kok chat kamu sepi ya? Aku kira kamu lagi sakit atau kenapa-kenapa.

Eh ternyata...

Jangan-jangan kamu <b>begadang lagi.</b> 😑

Serius deh, jangan sering begadang. Tidur itu penting buat kesehatan. Badan juga butuh istirahat supaya besok bangunnya tetap semangat, nggak gampang capek, dan tetap ceria.

Aku cuma ngingetin karena pengen kamu tetap sehat.

<hr style="margin:15px 0;">

🤣 EHHH...

Masih tidur lu?

Begadang mulu.

Sleep call aja enggak.

Sok sibuk amat.

Udah sana...

<b>Mending tidur.</b>

Biar besok nggak jadi zombie. 🧟

<div id="akhir">
#DimasForever 🤍
</div>

</div>

</div>

<script>
function buka(){
document.getElementById("pesan").style.display="block";
}
</script>

</body>
</html>
