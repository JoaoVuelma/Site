HTML:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VMInvestimentos</title>
    <link rel="stylesheet" href="css/styles.css"/>
</head>
<body>
<!-- Cabeçalho -->
    <header>
        <nav>
            <div class="elemento-fixo">
        <ul>
            <p>VMInvestimentos</p><img></img>
            <li><a href="#">Nossos Serviços</a></li>
            <li><a href="#">Sobre Nós</a></li>
            <li><a href="#">Contato</a></li>
        </div>
        </ul>
        </nav>
    </header>
<!-- Grid do Site -->
    <main class="container1">
        <section class="products-container1">
            <div class="card1">
                <img src="https://weinvest.com.br/wp-content/uploads/2020/11/original-0e860fa2c08b571d0c9f7641e2b0ae4a.jpg" alt=""></div>
            <div class="card1">
                <h1>Invista Hoje, Garanta o Seu Amanhã</h1>
                <p>A grande semelhança que existe entre pessoas de grande sucesso e as que estão iniciando é que as grandes pessoas um dia foram pequenas, e as pequenas vivem sonhando em ser grandes... porém, as que estão acima certamente fizeram por merecer... </p>
                <p>Entre a teoria e a prática existe um abismo, precisamos dar o primeiro passo, pensar que todos somos da mesma EQUIPE, o individualismo não faz mais parte da atualidade, empresas que têm funcionários individualistas se perdem no caminho e todos perdem com isso, inclusive VOCÊ.</p>
                <a href="#" class="btn1"> Mais</a>
            </div>
        </section>
    </main>
    <h2>Conheça Nossos planos de Investimentos</h2>
    <!-- Divisão de Cards -->
    <main class="container">
        <section class="products-container">
       
         <div class="card">
                <h3>Plano Begginer</h3>
                <p1>Investimentos até R$ 5 mil </p1>
                <p>Esse plano contempla:
                    <li>Chat da Plataforma</li>
                    <li>Operações Renda Variável</li>
                </p>
            <a href="#" class="btn">Conheça mais</a>
            </div>
        <div class="card">
            <h3>Plano Basic </h3>
            <p1>Investimentos de R$ 5 mil até R$ 20 mil</p1>
            <p>Esse plano contempla as seguintes vantagens:
                <li>Chat da Plataforma</li>
                <li>Atendimento via WhatsApp</li>
                <li>Email</li>
                <li>Assessoria</li>
                <li>Operações Renda Variável</li>
            </p>
            <a href="#" class="btn">Conheça mais</a>
        </div>
        <div class="card">
            <h3>Plano Average</h3>
            <p1>Investimentos entre R$ 20 mil e R$ 100 mil</p1>
            <p>Esse plano contempla as seguintes vantagens:
                <li>Beneficios do Plano Basic</li>
                <li>Atendimento pelo Telefone</li>
                <li>Conta Investidor</li>
                <li>Time de especialistas disponiveis para assessoria</li>
            </p>
            <a href="#" class="btn">Conheça mais</a>
        </div>
        <div class="card">
            <h3>Plano Exclusive </h3>
            <p1>Investimentos entre R$ 100 mil e R$ 3 milhões</p1>
            <p>Esse plano contempla as seguintes vantagens:
                <li>Beneficios do Plano Averange</li>
                <li>Telefone 24H</li>
                <li>Assessor dedicado a acompanhamento ativo e personalizado da carteira</li>
                <li>Mesa de operações Renda Variável Premium</li>
            </p>
            <a href="#" class="btn">Conheça mais</a>
        </div>
        </section>
    </main>
<!-- Rodapé -->
   <footer>
    <main class="container3">
        <section class="products-container3">
        <div class="card3">
            <h4>Nossos Seviços</h4>
            <li><a href="#">Assessoria Individual</a></li>
            <li><a href="#">Assessoria Empresarial</a></li>
            <li><a href="#">Opções de Renda variável</a></li>
            <li><a href="#">Abra uma conta </a></li>
        </div>
        <div class="card3">
            <h4>Sobre nós</h4>
            <li><a href="#">Quem somos</a></li>
            <li><a href="#">Acionistas Responsáveis</a></li>
            <li><a href="#">Localização</a></li>
        </div>
        <div class="card3">
            <h4>Contato</h4>
            <li><a href="#">WhatsApp</a></li>
            <li><a href="#">Email</a></li>
            <li><a href="#">Instagram</a></li>
            <li><a href="#">Telefone</a></li>
            <h5>
                <span class="bold">VMInvestimentos</span>
                &copy;2023
            </h5>
        </div>
        </section>
    </main>
   </footer>
</body>
</html>

CSS:

body {
    padding: 20px 0px 0px;
    background-color: #ececec;
    margin: 0;
}

.elemento-fixo {
    position: fixed;
    left: 0;
    top: 0px;
    width: 100%;
    background-color: #242424;
    color: #ffffff;
    font-family: helvetica;
    font-size: 15px;
    font-style: unset;
}

ul p {
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 20px;
}


nav{
    display: inline-block;
    justify-content: space-between;
    padding: 35px;
    font-size: 30px;
    font-family: "Avenir Next", serif;
}

nav ul{
    display: flex;
    list-style: none;
    align-items: center;
}

ul li{
    margin-right: 15px;
    font-size: 15px;
    background-position: right;
    text-align: center;
}

ul li a{
    color:  #eee;
    text-decoration: underline;
    background-position: end;
}

/*Grid do site*/

img{
    display: block;
    text-align: center;
    background-color: #141f3f;
    min-height: none;
    padding: 0;
    width: 370px;
    display: inline-block;
    margin: 0;
}

.container1 {
    background-color: #0a0a0a;
    min-height: 40vh;
    padding-top: 0px;
}

.products-container1 {
    max-width: 900px 400px;
    margin: auto;
}

.card1 {
    width: 41%;
    display: inline-block;
    margin: 1% 1%;
    padding: 10px 20px 20px;
    text-align: right;
    color: #ffffffb6;
}

.card1 h1 {
    text-align: center;
    align-items: center;
    color: #ffbb00dc;
    font-family: Arial;
}
.card1 p {
    text-align: left;
    color: #f0f0f0;
    font-family: helvetica;
}

.product-image1{
    height: 150px;
    width: 100%;
    margin-bottom: 150px;
    background-position: center;
    background-size: cover;
}

.btn1 {
    display: block;
    width: 100%;
    text-align: center;
    text-decoration: none;
    font-family: helvetica;
    background-color: #ffbb00dc;
    color: #000000;
    padding: 10px 10px;
    border-radius: 6px;
    transition: 0.5s;
}
.btn1:hover {
    background-color: #fad778;
}

h2 {
    background-color: #ececec;
    text-transform:none;
    font-family: arial;
    font-size: 50px;
    text-align: center;
    border-radius: 5px;
    padding: 18px 18px;
    margin: 15px 20px;
}

/*Segunda Grid do site*/

.container {
    background-color: #ececec;
    min-height: 60vh;
    padding-left: 70px;
}

.products-container {
    max-width: 500px 500px;
    margin: auto;
}

.card {
    width: 70%;
    display: inline-block;
    margin: 1% 1%;
    padding: 10px;
    background-color: #ffffff;
    border-radius: 6px;
    align-items: center;
    text-align: center;
    box-shadow: 3px 3px 8px  #000000;
}

h3 {
    font-size: 30px;
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif ;
}

p1 {
    color: #474747;
}

.btn {
    display: block;
    text-align: center;
    text-decoration: none;
    font-family: helvetica;
    background-color: #000000;
    color: #ffbb00dc;
    margin: 10px 10px;
    padding: 10px 5px;
    border-radius: 6px;
    transition: 0.5s;
}
.btn:hover {
    background-color: #5a5959;
}

/* Footer */
footer{
    color: #ffffff;
    padding-top: 20px;
}
.container3 {
    background-color: #ececec;
    min-height: 0;
    padding-left: 0;
}

.products-container3 {
    max-width: 500px 500px;
    margin: 0;
}

.card3 {
    width: 100%;
    display: inline-block;
    margin: 0;
    background-color: #242424;
    text-align: center;
}

h4 {
    font-size: 15px;
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif ;
    color: #eee;
}

.card3 li a {
    color: #eee;
}

h5 {
    color: #ffffff;
    padding-left: 30px;
    font-size: 20px;
}