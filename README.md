<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Buscadores Web</title>

<style>
    body{
        margin:0;
        font-family: Arial, sans-serif;
        background: linear-gradient(135deg, #0f172a, #1e293b);
        color:white;
        text-align:center;
    }

    h1{
        margin-top:40px;
        font-size:50px;
    }

    p{
        color:#cbd5e1;
        margin-bottom:40px;
    }

    .contenedor{
        display:flex;
        flex-wrap:wrap;
        justify-content:center;
        gap:25px;
        padding:20px;
    }

    .card{
        background:white;
        color:black;
        width:250px;
        padding:25px;
        border-radius:20px;
        box-shadow:0 10px 25px rgba(0,0,0,0.3);
        transition:0.3s;
    }

    .card:hover{
        transform:scale(1.07);
    }

    .card h2{
        margin-bottom:10px;
    }

    .card p{
        color:#444;
    }

    .btn{
        display:inline-block;
        margin-top:15px;
        padding:12px 25px;
        background:#2563eb;
        color:white;
        text-decoration:none;
        border-radius:12px;
        font-weight:bold;
        transition:0.3s;
    }

    .btn:hover{
        background:#1d4ed8;
    }

    footer{
        margin-top:50px;
        padding:20px;
        color:#94a3b8;
    }
</style>
</head>

<body>

<h1>🌐 Buscadores Web</h1>
<p>Haz clic en cualquier buscador para abrirlo 🚀</p>

<div class="contenedor">

    <div class="card">
        <h2>Google</h2>
        <p>El buscador más usado del mundo.</p>
        <a href="https://www.google.com" target="_blank" class="btn">Entrar</a>
    </div>

    <div class="card">
        <h2>Bing</h2>
        <p>Buscador creado por Microsoft.</p>
        <a href="https://www.bing.com" target="_blank" class="btn">Entrar</a>
    </div>

    <div class="card">
        <h2>Yahoo</h2>
        <p>Noticias, correo y buscador clásico.</p>
        <a href="https://www.yahoo.com" target="_blank" class="btn">Entrar</a>
    </div>

    <div class="card">
        <h2>DuckDuckGo</h2>
        <p>Privacidad y búsquedas seguras.</p>
        <a href="https://duckduckgo.com" target="_blank" class="btn">Entrar</a>
    </div>

    <div class="card">
        <h2>Yandex</h2>
        <p>Buscador popular con muchas herramientas.</p>
        <a href="https://yandex.com" target="_blank" class="btn">Entrar</a>
    </div>

</div>

<footer>
✨ Página creada por Kevin Web Studios 3000 ✨
</footer>

</body>
</html>