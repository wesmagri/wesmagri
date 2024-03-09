<html lang="pt-br"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário de Reserva de Viagem</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
  </head>
  <body>
    <header class="container-fluid p-2 bg-warning text-center">
      <nav class="navbar navbar-expand-lg bg-warning">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Alugue seu carro dos sonhos</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse justify-content-end bg-warning" id="navbarSupportedContent">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Carros disponíveis</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Fale conosco
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Whatsapp</a></li>
                  <li><a class="dropdown-item" href="#">Instagram</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">E-mail</a></li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#"><i class="bi bi-cart3"></i></a>
                
              </li>
            </ul>
          </div>
        </div>
      </nav>
      <div id="carouselExampleCaptions" class="carousel slide">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="./assets/bmw-branco.jpg" class="d-block w-100" width="250px">
            <div class="carousel-caption d-none d-md-block">
              <h5>Encontre sua BMW</h5>
              
            </div>
          </div>
          <div class="carousel-item">
            <img src="./assets/carousel2.jpg" class="d-block w-100" width="250px">
            <div class="carousel-caption d-none d-md-block">
              <h5>Encontre sua melhor versão </h5>
              
            </div>
          </div>
          <div class="carousel-item">
            <img src="./assets/onix-vermelho.jpeg" class="d-block w-100" width="250px">
            <div class="carousel-caption d-none d-md-block">
              <h5>Encontre seu Onix</h5>
              
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </header>

    <section class="container-fluid bg-light">
      <h1>Formulário de Reserva de Viagem</h1>
      <p>
        Preencha o formulário para que possamos entrar em contato com você.
      </p>
      <form action="#" method="post">
        <fieldset>
          <legend><b>Dados do Cliente</b></legend>
          <div>
            <label class="form-label" for="nome"> Nome:</label>
          </div>
          <input type="text" class="form-control" id="nome" name="nome" required=""><br><br>

          <div>
            <label class="form-label" for="email"> Email:</label>
          </div>
          <input type="email" class="form-control" id="email" name="email" required=""><br><br>
        </fieldset>
        <fieldset>
          <legend><b>Serviços Desejados</b></legend>
          <div class="form-check">
            <input class="form-check-input" type="checkbox" id="passagens" name="servico" value="passagens">
          <label class="form-check-label" for="CompraPassagens">Compra de Passagens</label><br>
          </div>
          
          <div class="form-check">
            <input class="form-check-input" type="checkbox" id="hospedagem" name="servico" value="hospedagem">
          <label class="form-check-label" for="ReservadeHospedagem">Reserva de Hospedagem</label><br>
          </div>
          <div class="form-check">
            <input class="form-check-input" type="checkbox" id="veiculos" name="servico" value="veiculos">
          <label for="AluguelDeveiculos">Aluguel de Veículos</label><br><br>
          </div>
          
        </fieldset>
        <fieldset>
          <legend><b>Prazo de Pagamento</b></legend>
          <select id="prazo" name="prazo">
            <option value="avista">À Vista</option>
            <option value="cincovezes">Cinco Vezes Sem Juros</option>
            <option value="dezvezes">Dez Vezes Com Juros</option></select><br><br>
        </fieldset>
        
        
        <button class="btn btn-secondary">Salvar</button>
        <br><br>
      </form>
    </section>

    <section class="container-fluid bg-warning text-xl-center">
      <h2>Taxa de serviço</h2>
      <table class="table table-warning table-striped table-hover table-bordered border-warning">
        <caption>
          Descrição dos serviços e respectivos valores
        </caption>
        <thead class="table-secondary">
          <tr>
            <th>Serviço</th>
            <th>Valor</th>
          </tr>
        </thead>
        <tbody class="table-group-divider">
          <tr>
            <td>BMW Branca</td>
            <td>R$ 3.000,00</td>
          </tr>
          <tr>
            <td>Cobalt cinza</td>
            <td>R$ 2.500,00</td>
          </tr>
          <tr>
            <td>Onix Vermelho</td>
            <td>R$ 2.000,00</td>
          </tr>
        </tbody>
      </table>
    </section>
    <section class="container-fluid bg-warning-subtle text-xl-center">
      <h2>Conheça nossos carros</h2>
      <p>
        As melhores condições para você reservar e aproveitar

      </p>
    </section>

    <div class="row">
      <div class="row row-cols-1 row-cols-md-3 g-4">
        <div class="col">
          <div class="card h-100 ">
            <img src="./assets/onix-vermelho.jpeg" class="card-img-top" alt="...">
            <div class="card-body bg-warning-subtle">
              <h5 class="card-title">Onix</h5>
              <h1 class="card-subtitle text-muted"> R$2.000,00</h1>
              <p class="card-text">Corra atrás da sua aventura</p>
            </div>
            <a href="#" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">Reservar</a>
            <div class="card-footer">
              <small class="text-body-secondary">Em até 5x</small>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100 ">
            <img src="./assets/bmw-branco.jpg" class="card-img-top" alt="...">
            <div class="card-body bg-warning-subtle">
              <h5 class="card-title">BMW</h5>
              <h1 class="card-subtitle text-muted">R$3.000,00</h1>
              <p class="card-text">Corra atrás da sua aventura</p>
            </div>
            <a href="#" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">Reservar</a>
            <div class="card-footer">
              <small class="text-body-secondary">Em até 5x</small>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100">
            <img src="./assets/cobalt-cinza.jpeg" class="card-img-top" alt="...">
            <div class="card-body bg-warning-subtle">
              <h5 class="card-title">Cobalt</h5>
              <h1 class="card-subtitle text-muted">R$2.500,00</h1>
              <p class="card-text">Corra atrás da sua aventura</p>
            </div>
            <a href="#" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">Reservar</a>
            <div class="card-footer">
              <small class="text-body-secondary">Em até 5x</small>
            </div>
          </div>
        </div>
      </div>
    </div>
    <footer class="container-fluid bg-warning text-center">
      <p>Desenvolvido por Andressa Madureira - 2024</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
  
  

<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5" id="exampleModalLabel">Suas compras</h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
       Produto adicionado ao carrinho!
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-primary" data-bs-dismiss="modal">Continuar compra</button>
        <a href="checkout.html" type="button" class="btn btn-success">Finalizar compra</a>
      </div>
    </div>
  </div>
</div>

</body></html>
