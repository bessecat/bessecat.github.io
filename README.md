<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portifólio</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/css/bootstrap.min.css"
        integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/js/bootstrap.min.js"
        integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"
        crossorigin="anonymous"></script>
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
        integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.14.7/dist/umd/popper.min.js"
        integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1"
        crossorigin="anonymous"></script>
    <script src="https://kit.fontawesome.com/6c8549fd66.js" crossorigin="anonymous"></script>
    <style>
        .foto-perfil {
            height: 100%;
            width: auto;
            max-width: 100%;
            border-radius: 5%;
        }

        .corPrimaria {
            background-color: #94DDDE;
        }

        .corSecundaria {
            background-color: #494389;
        }

        p {
            font-family: Arial, Helvetica, sans-serif;
            color: #494389
        }

        .icones {
            iconespadding-left: 5px;
        }

        .titulosBrancos {
            color: white;
        }

        .textoClaro {
            color: #7E74F1 !important;
        }

        .titulosEscuros {
            color: #494389;
        }

        .textoFooter {
            margin: 0px;
            padding-top: 15px;
            padding-bottom: 15px;
        }

        html {
            scroll-behavior: smooth;
        }
    </style>
</head>

<body>
    <nav class="navbar navbar-expand-lg navbar-light corSecundaria">
        <a class="navbar-brand textoClaro" href="#">Dani Bessegatto</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">

            </ul>
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link textoClaro" href="#conhecimentos">Conhecimentos</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link textoClaro" href="#projetos">Projetos</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link textoClaro" href="#sobre-mim">Sobre mim</a>
                </li>
            </ul>
        </div>
    </nav>
    <section class="jumbotron text-center corPrimaria">
        <div class="container">
            <img class="foto-perfil" src="https://i.ibb.co/6Dv3ppR/dani.png" alt="dani">
            <h1 class="jumbotron-heading titulosBrancos">Dani Bessegatto</h1>
            <p class="lead titulosEscuros"><i>Criativa, estudante de programação, recentemente apaixonada pelo front-end
                    e
                    design nas mais variadas artes possíveis.</i></p>
            <p>
                <a href="mailto:danibessegatto@gmail.com" class="btn btn-dark my-2 corSecundaria">Contato</a>
            </p>
            <a href="https://www.linkedin.com/in/daniella-ventorim-bessegatto-7ba49512a/"><i
                    class="textoClaro fab fa-linkedin icones"></i></a>
            <a href="github.com/bessecat"><i class="textoClaro fab fa-github icones"></i></a>
        </div>
    </section>
    <section class="text-center" id="conhecimentos">
        <div class="container">
            <h2 class="jumbotron-heading titulosEscuros" align="center ">Conhecimentos:</h2>
            <br>
            <br>
            <div class="row" align="center">
                <div class="col-lg-2">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c"
                        width="100" height="100">
                    <h6>Linguagem C</h6>
                </div>
                <div class="col-lg-2">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg"
                        alt="html5" width="100" height="100">
                    <h6>HTML</h6>
                </div>
                <div class="col-lg-2">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg"
                        alt="css3" width="100" height="100">
                    <h6>CSS</h6>
                </div>
                <div class="col-lg-2">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg"
                        alt="js" width="100" height="100">
                    <h6>JavaScript</h6>
                </div>
                <div class="col-lg-2">
                    <img src="https://camo.githubusercontent.com/accac71d5d4e61a129dc89eaac39d1c4c5437c44e18e085c2834a4297613ef50/68747470733a2f2f63646e2e776f726c64766563746f726c6f676f2e636f6d2f6c6f676f732f72656163742d322e737667"
                        alt="react" width="100" height="100">
                    <h6>React</h6>
                </div>
                <div class="col-lg-2">
                    <img src="https://camo.githubusercontent.com/ed93c2b000a76ceaad1503e7eb9356591b885227e82a36a005b9d3498b303ba5/68747470733a2f2f7777772e766563746f726c6f676f2e7a6f6e652f6c6f676f732f6669676d612f6669676d612d69636f6e2e737667"
                        alt="figma" width="100" height="100">
                    <h6>Figma</h6>
                </div>
            </div>
        </div>
        <br>
        <br>
    </section>
    <div class="album py-5 bg-light">
        <div class="container">
            <h2 class="jumbotron-heading titulosEscuros" align="center " id="projetos">Projetos:</h2>
            <br>
            <br>
            <div class="row">
                <div class="col-md-4">
                    <div class="card mb-4 box-shadow">
                        <img class="card-img-top"
                            data-src="holder.js/100px225?theme=thumb&amp;bg=55595c&amp;fg=eceeef&amp;text=Thumbnail"
                            alt="Thumbnail [100%x225]" style="height: 225px; width: 100%; display: block;"
                            src="https://i.ibb.co/93nbPkh/Em-breve.png" data-holder-rendered="true">
                        <div class="card-body">
                            <h4 class="titulosEscuros">Em Breve</h4>
                            <p class="card-text">Aguarde, estou desenvolvendo o projeto.</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="btn-group">
                                    <a href="..."><button type="button" class="btn btn-sm btn-outline-success">Ver
                                            projeto</button></a>
                                    <a href="..."><button type="button"
                                            class="btn btn-sm btn-outline-primary">Código</button></a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <section class="jumbotron text-center corPrimaria" id="sobre-mim">
                    <div class="container">
                        <h2 class="jumbotron-heading titulosBrancos">Sobre mim</h2>
                        <p class="lead titulosEscuros">Estudante do curso Biopark Connect, muito interessada em me
                            desenvolver na
                            programação, especificamente na area de front end. Me considero uma pessoa muito criativa, e
                            sempre busco manter essas inspirações em qualquer projeto. Desde sempre apaixonada por
                            tecnologia e buscando fazer a diferença em qualquer atuação possível.
                        </p>
                    </div>
                </section>
            </div>
        </div>
    </div>
</body>
<footer class="text-center textoFooter">
    <p align="center">© 2022 Daniella Ventorim Bessegatto, Inc
    </p>
</footer>

</html>
