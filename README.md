<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">

    <title>VJR Home Care</title>
</head>

<body>
    <!--NAVBAR   -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">VJR HOME CARE</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"
                            data-bs-toggle="dropdown" aria-expanded="false">
                            Nossos Serviços
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <li><a class="dropdown-item" href="#">Action</a></li>
                            <li><a class="dropdown-item" href="#">Another action</a></li>
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
                        </ul>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"
                            data-bs-toggle="dropdown" aria-expanded="false">
                            Sobre
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <li><a class="dropdown-item" href="#">Action</a></li>
                            <li><a class="dropdown-item" href="#">Another action</a></li>
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>

                        </ul>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Idéias</a>
                    </li>
                    <button type="button" class="btn btn-outline-info">Solicite seu Orçamento</button>
                </ul>
                <form class="d-flex">
                    <input class="form-control me-2" type="search" placeholder="Oque procura hoje ?"
                        aria-label="Buscar">
                    <button class="btn btn-info" type="submit">Procurar</button>
                </form>
            </div>
        </div>
    </nav>
    <!--CARROSSEL  -->
    <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
                aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
                aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"
                aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="https://i.imgur.com/uITIwLw.png" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>First slide label</h5>
                    <p>Some representative placeholder content for the first slide.</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="https://i.imgur.com/BEiLOtE.png" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Second slide label</h5>
                    <p>Some representative placeholder content for the second slide.</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="https://i.imgur.com/q9jByaH.png" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Third slide label</h5>
                    <p>Some representative placeholder content for the third slide.</p>
                </div>
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions"
            data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions"
            data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>
    <!-- Quem Somos  -->
    <div id="quemSomos">
        <div class="card mb-8">
            <img class="card-img-top" src="https://i.imgur.com/cvhe85P.png/10px18/" alt="Imagem de capa do card">
            <div class="card-body">
                <h2 class="card-title">Veja porque a VJR é uma empresa de limpeza diferente.</h2><br />
                <br />
                <h3>Especialista em Limpeza</h3>
                <p class="card-text">Somos uma empresa especializada em limpeza pois só fazemos isso há décadas. Como
                    especialistas, garantimos uma qualidade superior em serviços de limpeza.</p>
            </div>
        </div>
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">Especialista em Manutenção</h3>
                <p class="card-text">Seja para a sua Casa, Apartamento, Condomínio ou Empresa temos o profissional certo
                    para atender com Total Eficiência, Segurança e Rapidez todos os reparos que o seu imóvel precisa.
                    Serviços de Eletricista, Instalador téc em informática,téc em infraestrutura de redes Montador,
                    Pintor e
                    muito mais...</p>
            </div>
        </div>
    </div>

    <!-- Valores Centrais -->
    <div id="valores">
        <div id="valoresCentrais"><h5>VALORES CENTRAIS</h5></div>
        <div class="card-group">
            <div class="card">
                <img class="card-img-top" src=".../100px180/" alt="Imagem de capa do card">
                <div class="card-body">
                    <h5 class="card-title">Integridade</h5>
                    <p class="card-text">Inspiramos
                        confiança e conquistamos credibilidade ao cumprir o prometido, atuando de
                        maneira ética e encorajando o uso de práticas sustentáveis.</p>
                </div>
                <div class="card-footer">
                </div>
            </div>
            <div class="card">
                <img class="card-img-top" src=".../100px180/" alt="Imagem de capa do card">
                <div class="card-body">
                    <h5 class="card-title">Melhores Pessoas</h5>
                    <p class="card-text">Buscamos atrair e desenvolver os melhores talentos para o nosso negócio,
                        incentivando atitudes positivas e profissionais.</p>
                </div>
                <div class="card-footer">

                </div>
            </div>
            <div class="card">
                <img class="card-img-top" src=".../100px180/" alt="Imagem de capa do card">
                <div class="card-body">
                    <h5 class="card-title">Alta Performance</h5>
                    <p class="card-text">Contribuimos para o sucesso de nossos clientes, através de serviços de padrão
                        superior, baseados na excelência da execução.</p>
                </div>
                <div class="card-footer">
                   </div>
            </div>
        </div>
        <div class="card-group">
            <div class="card">
                <img class="card-img-top" src=".../100px180/" alt="Imagem de capa do card">
                <div class="card-body">
                    <h5 class="card-title">Atendimento Incomparável</h5>
                    <p class="card-text"> Valorizamos e incentivamos a presença do dono, a VJR frente dos negócios no dia a dia, garantindo melhor comunicação com clientes, máxima atenção aos detalhes, flexibilidade e agilidade..</p>
                </div>
                <div class="card-footer">

                </div>
            </div>
            <div class="card">
                <img class="card-img-top" src=".../100px180/" alt="Imagem de capa do card">
                <div class="card-body">
                    <h5 class="card-title">Visão de longo prazo </h5>
                    <p class="card-text">Como empresa , buscamos resultados e relacionamentos duradouros e ganhos mútuos, sem imediatismos.</p>
                </div>
                <div class="card-footer">

                </div>
            </div>
            <div class="card">
                <img class="card-img-top" src=".../100px180/" alt="Imagem de capa do card">
                <div class="card-body">
                    <h5 class="card-title">Atenção com os clientes</h5>
                    <p class="card-text">Essa atenção especial aos detalhes é o que nos diferencia, pois o básico qualquer empresa faz.</p>
                </div>
                <div class="card-footer">

                </div>
            </div>
        </div>
    </div>

    <!-- Segmentos atendidos -->
    <div class="card-deck">
        <div class="card">
          <img class="card-img-top" src=".../100px180/" alt="Imagem de capa do card">
          <div class="card-body">
            <h5 class="card-title">Título do card</h5>
            <p class="card-text">Este é um card maior com suporte a texto embaixo, que funciona como uma introdução a um conteúdo adicional. Este conteúdo é um pouco maior, para demonstração.</p>
          </div>
          <div class="card-footer">
            <a href="#" class="btn btn-primary">Visitar</a>
          </div>
        </div>
        <div class="card">
          <img class="card-img-top" src=".../100px180/" alt="Imagem de capa do card">
          <div class="card-body">
            <h5 class="card-title">Título do card</h5>
            <p class="card-text">Este é um card com suporte a texto embaixo, que funciona como uma introdução a um conteúdo adicional.</p>
          </div>
          <div class="card-footer">
            <a href="#" class="btn btn-primary">Visitar</a>
          </div>
        </div>
        <div class="card">
          <img class="card-img-top" src=".../100px180/" alt="Imagem de capa do card">
          <div class="card-body">
            <h5 class="card-title">Título do card</h5>
            <p class="card-text">Este é um card maior com suporte a texto embaixo, que funciona como uma introdução a um conteúdo adicional. Este card tem o conteúdo ainda maior que o primeiro, para mostrar a altura igual, em ação.</p>
          </div>
          <div class="card-footer">
            <a href="#" class="btn btn-primary">Visitar</a>
          </div>
        </div>
      </div>

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4"
        crossorigin="anonymous"></script>


</body>

</html>
