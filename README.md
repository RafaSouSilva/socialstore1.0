<!DOCTYPE html>
<html>
<head>
  <title>Social Store</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  <style>
    .carousel-item {
      width: 100%;
      height: auto;
    }

    /* default styles for all screen sizes */
   .card {
     width: 20%;
     display: inline-block;
     margin-right: 20px;
     margin-left: 30px;
   }
   .card-img-top {
     width: 100%;
     height: 150px;
   }
   h1{
    text-align: center;
   }
   
   
   /* styles for screens smaller than 768px */
   @media (max-width: 576px) {
  .navbar .form-inline {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
}

   @media (max-width: 768px) {
     .card {
       width: 50%;
     }
   }
   
   /* styles for screens smaller than 576px */
   @media (max-width: 576px) {
     .card {
       width: 100%;
     }
     .card-img-top {
       height: 100px;
     }
     
   }
   
     </style>
</head>
<body>
  <nav class="navbar navbar-dark bg-dark justify-content-between">
    <a class="navbar-brand" href="index.html">Social Store</a>
    <form class="form-inline">
      <input class="form-control mr-sm-2" type="search" placeholder="Buscar Ex: Calça Jeans" aria-label="Search">
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Buscar Produtos</button> 
      <span><button type="button" class="btn btn-primary ml-2">Login</button>
      </span>
    </form>
     </nav>

  
      <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
           <a href="saibamais.html"> <img class="d-block w-100" src="images/img1.png" alt="First slide" ></a>
          </div>
          <div class="carousel-item">
            <a href="saibamais.html"><img class="d-block w-100" src="images/img2.png" alt="Second slide"></a>
          </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
        </div>
        <br>
        <h1>Ofertas do dia: </h1>
  <div class="card-deck">
    <div class="card">
      <img src="images/2.png" class="card-img-top" alt="Hero 1">
      <div class="card-body">
        <h5 class="card-title">Calça Jeans Feminina</h5>
        <p class="card-text">Exemplo de um produto em que o vendedor não tem a loja verificada. Ele será direcionado
          para a página do instagram do vendedor.
        </p>
        <a href="https://www.instagram.com/onlinejeanswear/" class="btn btn-danger" target="_blank">Visitar Instagram da Loja</a>
      </div>
    </div>
    <div class="card">
      <img src="images/1.png" class="card-img-top" alt="Hero 2">
      <div class="card-body">
        <h5 class="card-title">Calça Jeans Feminina</h5>
        <h5>Loja Verificada<span><img src="images/icon.png" alt=""></span></h5> 
                <p class="card-text"> Loja Verificada. Cliente compra diretamente e no final após o checkout ele pode verificar o Instagram da loja fornecedora.</p>
        <a href="checkout.html" class="btn btn-primary">Comprar</a>
      </div>
    </div>
    <div class="card">
      <img src="images/2.png" class="card-img-top" alt="Hero 3">
      <div class="card-body">
      <h5 class="card-title">Calça Jeans Feminina</h5>
      <p class="card-text">Exemplo de um produto em que o vendedor não tem a loja verificada. Ele será direcionado para a página do instagram do vendedor.</p>
        <a href="#" class="btn btn-danger">Visitar Instagram da Loja</a>
      </div>
      </div>
      <div class="card">
      <img src="images/1.png" class="card-img-top" alt="Hero 4">
      <div class="card-body">
      <h5 class="card-title">Calça Jeans feminina</h5>
      <h5>Loja Verificada<span><img src="images/icon.png" alt=""></span></h5> 
      <p class="card-text"> Loja Verificada. Cliente compra diretamente e no final após o checkout ele pode verificar o Instagram da loja fornecedora.</p>
      <a href="#" class="btn btn-primary">Visitar Loja</a>
      </div>
      </div>
      
        </div>
        <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
      </body>
      
      </html>
