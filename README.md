<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Linguagens de Programação</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
    <style>
        body {
            background-color: #f5f5f5;
            font-family: 'Open Sans', sans-serif;
        }
        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
            background-color: #fff;
            border: 1px solid #ddd;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        .lang-card {
            margin-bottom: 20px;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .lang-card:hover {
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
        }
        h1, h2 {
            font-weight: bold;
            color: #333;
        }
        p {
            font-size: 16px;
            color: #666;
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">Linguagens de Programação</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Sobre</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Contato</a>
                </li>
            </ul>
        </div>
    </nav>
    <div class="container">
        <h1>Bem-vindo ao meu site de linguagens de programação!</h1>
        <p>Aqui você encontrará informações sobre as principais linguagens de programação.</p>
        <div class="row">
            <div class="col-md-4 lang-card">
                <h2>Java</h2>
                <p>Java é uma linguagem de programação orientada a objetos desenvolvida pela Sun Microsystems.</p>
            </div>
            <div class="col-md-4 lang-card">
                <h2>Python</h2>
                <p>Python é uma linguagem de programação de alto nível, interpretada, de código aberto.</p>
            </div>
            <div class="col-md-4 lang-card">
                <h2>C++</h2>
                <p>C++ é uma linguagem de programação compilada, de alto desempenho, desenvolvida por Bjarne Stroustrup.</p>
            </div>
            <div class="col-md-4 lang-card">
                <h2>JavaScript</h2>
                <p>JavaScript é uma linguagem de programação interpretada, utilizada principalmente para desenvolvimento de aplicações web.</p>
            </div>
            <div class="col-md-4 lang-card">
                <h2>Ruby</h2>
                <p>Ruby é uma linguagem de programação interpretada, de código aberto, desenvolvida por Yukihiro Matsumoto.</p>
            </div>
            <div class="col-md-4 lang-card">
                <h2>Swift</h2>
                <p>Swift é uma linguagem de programação desenvolvida pela Apple, utilizada para desenvolvimento de aplicações iOS e macOS.</p>
            </div>
        </div>
    </div>
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
</body>
</html>
