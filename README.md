# 15-a-os
Invitación 
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mis XV Años · Alexia</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,500;0,600;1,500&family=Montserrat:wght@400;500;600;700&display=swap');

:root{
    --morado:#26052f;
    --morado2:#4a1460;
    --rosado:#e99ab8;
    --dorado:#e8bd67;
    --crema:#fff4df;
}

*{
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    margin:0;
    background:#120318;
    color:white;
    font-family:Montserrat,Arial,sans-serif;
}

main{
    max-width:520px;
    margin:auto;
    overflow:hidden;
    background:#1b0426;
}

section{
    position:relative;
    padding:70px 22px;
    overflow:hidden;
}

.hero{
    min-height:100vh;
    display:flex;
    flex-direction:column;
    justify-content:flex-end;
    text-align:center;
    padding-bottom:45px;

    background:
        linear-gradient(
            to bottom,
            rgba(20,2,29,.15),
            rgba(20,2,29,.92)
        ),
        url("foto1.jpg") center/cover;
}

.hero h1{
    margin:5px 0 20px;
    font-family:"Cormorant Garamond",serif;
    font-size:90px;
    font-style:italic;
    font-weight:500;
    color:var(--dorado);
}

.hero h2{
    font-family:"Cormorant Garamond",serif;
    font-size:28px;
}

.quote{
    font-family:"Cormorant Garamond",serif;
    font-size:21px;
    line-height:1.55;
}

.titulo{
    text-align:center;
}

.titulo h2{
    font-family:"Cormorant Garamond",serif;
    font-size:44px;
    font-style:italic;
    color:var(--dorado);
}

.subtitulo{
    color:var(--dorado);
    text-transform:uppercase;
    letter-spacing:.18em;
    font-size:10px;
}

.detalles{
    text-align:center;
    background:linear-gradient(160deg,#21042f,#4a1460);
}

.tarjeta{
    border:1px solid rgba(232,189,103,.55);
    border-radius:25px;
    padding:30px 20px;
    background:rgba(255,255,255,.05);
}

.fecha{
    font-family:"Cormorant Garamond",serif;
    font-size:38px;
    color:var(--dorado);
}

.hora,
.lugar{
    font-size:18px;
    margin-top:10px;
}

.padres{
   
