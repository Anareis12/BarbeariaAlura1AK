<div class="principal">
    <h1>Sobre a Barbearia Alura</h1>

    <p>Localizada no coração da cidade a <strong>Barbearia Alura</strong> traz para o mercado o que há de melhor para o seu cabelo e barba. 
    Fundada em 2019, a Barbearia Alura já é destaque na cidade e conquista novos clientes a cada dia.</p>

    <p id="missao"><em>Nossa missão é: <strong>"Proporcionar auto-estima e qualidade de vida aos clientes"</strong>.</em></p>

    <p>Oferecemos profissionais experientes e antenados às mudanças no mundo da moda. 
    O atendimento possui padrão de excelência e agilidade, garantindo qualidade e satisfação dos nossos clientes.</p>
</div><div class="beneficios">
    <h2>Benefícios</h2>

    <ul>
        <li class="itens">Atendimento aos Clientes</li>
        <li class="itens">Espaço diferenciado</li>
        <li class="itens">Localização</li>
        <li class="itens">Profissionais Qualificados</li>
    </ul>

    <img src="beneficios.jpg" class="imagembeneficios">
</div>body {

}

.principal{
    background: #CCCCCC;
    padding: 30px;
}.itens {
    font-style: italic;
}

.beneficios {
    background: #FFFFFF;
    padding: 20px;
}

h2 {
    text-align: center;
}ul {
    display: inline-block;
    vertical-align: top;
    width: 20%;
    margin-right: 15%;
}.imagembeneficios {
    width: 50%;
}<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>Produtos - Barbearia Alura</title>
        <link rel="stylesheet" href="produtos.css">
    </head>
    <body>
        <header>
            <h1><img src="logo.png"></h1>

            <ul>
                <li>Home</li>
                <li>Produtos</li>
                <li>Contato</li>
            </ul>
        </header>
    </body>
</html>
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>Produtos - Barbearia Alura</title>
        <link rel="stylesheet" href="produtos.css">
    </head>
    <body>
        <header>
            <h1><img src="logo.png"></h1>

            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="produtos.html">Produtos</a></li>
                    <li><a href="contato.html">Contato</a></li>
                </ul>
            </nav>
        </header>
    </body>
</html>
header {
    background: #BBBBBB;
}

nav li {
    display: inline;
    margin: 0 0 0 15px;
}

nav a {
    text-transform: uppercase;
    color: #000000;
    font-weight: bold;
    font-size: 22px;
    text-decoration: none;
}
<link rel="stylesheet" href="reset.css">
<link rel="stylesheet" href="produtos.css">
<div class="caixa">
    <h1><img src="logo.png"></h1>

    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="produtos.html">Produtos</a></li>
            <li><a href="contato.html">Contato</a></li>
        </ul>
    </nav>
</div>
header {
    background: #BBBBBB;
    padding: 20px 0;.caixa {
    position: relative;
    width: 940px;
    margin: 0 auto;
}

nav {
    position: absolute;
    top: 110px;
    right: 0;
}
header {
    background: #BBBBBB;
    padding: 20px 0;
}

.caixa {
    position: relative;
    width: 940px;
    margin: 0 auto;
}

nav {
    position: absolute;
    top: 110px;
    right: 0;
}

nav li {
    display: inline;
    margin: 0 0 0 15px;
}

nav a {
    text-transform: uppercase;
    color: #000000;
    font-weight: bold;
    font-size: 22px;
    text-decoration: none;
}
<main>
    <ul class="produtos">
        <li>
            <h2>Cabelo</h2>
            <img src="cabelo.jpg">
            <p class="produto-descricao">Na tesoura ou máquina, como o cliente preferir</p>
            <p class="produto-preco">R$ 25,00</p>
        </li>
        <li>
            <h2>Barba</h2>
            <img src="barba.jpg">
            <p class="produto-descricao">Corte e desenho profissional de barba</p>
            <p class="produto-preco">R$ 18,00</p>
        </li>
        <li>
            <h2>Cabelo + Barba</h2>
            <img src="cabelo+barba.jpg">
            <p class="produto-descricao">Pacote completo de cabelo e barba</p>
            <p class="produto-preco">R$ 35,00</p>
        </li>
    </ul>
</main>
.produtos {
    width: 940px;
    margin: 0 auto;
    padding: 50px 0;
}

.produtos li {
    display: inline-block;
    text-align: center;
    width: 30%;
    vertical-align: top;
    margin: 0 1.5%;
    padding: 30px 20px;
    box-sizing: border-box;
}

.produtos h2 {
    font-size: 30px;
    font-weight: bold;
}

.produto-descricao {
    font-size: 18px;
}

.produto-preco {
    font-size: 22px;
    font-weight: bold;
    margin-top: 10px;
}
border: 2px solid #000000;
border-radius: 10px;.produtos li {
    display: inline-block;
    text-align: center;
    width: 30%;
    vertical-align: top;
    margin: 0 1.5%;
    padding: 30px 20px;
    box-sizing: border-box;
    border: 2px solid #000000;
    border-radius: 10px;
}
nav a:hover {
    color: #C78C19;
    text-decoration: underline;
}
.produtos li:hover {
    border-color: #C78C19;
}
.produtos li:active {
    border-color: #088C19;	
}
.produtos li:hover h2 {
    font-size: 34px;
}
<footer>
    <img src="logo-branco.png">
    <p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
</footer>
footer {
    text-align: center;
    background: url("bg.jpg");
    padding: 40px 0;
}

.copyright {
    color: #FFFFFF;
    font-size: 13px;
    margin: 20px 0 0;
}
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>Contato - Barbearia Alura</title>

        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <header>
            <div class="caixa">
                <h1><img src="logo.png"></h1>

                <nav>
                    <ul>
                        <li><a href="index.html">Home</a></li>
                        <li><a href="produtos.html">Produtos</a></li>
                        <li><a href="contato.html">Contato</a></li>
                    </ul>
                </nav>
            </div>
        </header>

        <footer>
            <img src="logo-branco.png">
            <p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
        </footer>
    </body>
</html>
<main>
    <form>
        <label for="nomesobrenome">Nome e sobrenome</label>
        <input type="text" id="nomesobrenome">

        <label for="email">Email</label>
        <input type="text" id="email">

        <label for="telefone">Telefone</label>
        <input type="text" id="telefone">

        <input type="submit" value="Enviar formulário">
    </form>
</main>
main {
    width: 940px;
    margin: 0 auto;
}

form {
    margin: 40px 0;
}

form label {
    display:block;
    font-size: 20px;
    margin: 0 0 10px;
}

form input {
    display: block;
    margin: 0 0 20px;
    padding: 10px 25px;
    width: 50%;
}
<label for="mensagem">Mensagem</label>
<textarea cols="70" rows="10" id="mensagem" class="input-padrao"></textarea>
<div>
    <p>Como prefere o nosso contato?</p>
    <label for="radio-email">
        <input type="radio" name="contato" value="email" id="radio-email">
        Email
    </label>
    
    <label for="radio-telefone">
        <input type="radio" name="contato" value="telefone" id="radio-telefone"> 
        Telefone
    </label>
    
    <label for="radio-whatsapp">
        <input type="radio" name="contato" value="whatsapp" id="radio-whatsapp">
        WhatsApp
    </label>
</div>
<div>
    <p>Qual horário prefere ser atendido?</p>
    <select>
        <option>Manhã</option>
        <option>Tarde</option>
        <option>Noite</option>
    </select>
</div>
<label class="checkbox">
    <input type="checkbox">
    Gostaria de receber nossas novidades por email?
</label>
form label {
    display:block;
    font-size: 20px;
    margin: 0 0 10px;
}
form input {
    display: block;
    margin: 0 0 20px;
    padding: 10px 25px;
    width: 50%;
}
.checkbox {
    margin: 20px 0;
}
<img src="logo.png" alt="Logo da Barbearia Alura">

<img src="logo-branco.png" alt="Logo da Barbearia Alura">
<label for="email">Email</label>
<input type="email" id="email" class="input-padrao" required placeholder="seuemail@dominio.com">

<label for="telefone">Telefone</label>
<input type="tel" id="telefone" class="input-padrao" required placeholder="(XX) XXXXX-XXXX">
<label for="radio-whatsapp">
    <input type="radio" name="contato" value="whatsapp" id="radio-whatsapp" checked>
    WhatsApp
</label>
<label class="checkbox">
    <input type="checkbox" checked>
    Gostaria de receber nossas novidades por email?
</label>
form label, form legend {
    display:block;
    font-size: 20px;
    margin: 0 0 10px;
}
<input type="submit" value="Enviar formulário" class="enviar">
.enviar {
    width:40%;
    padding: 15px 0;
    background: orange;
    color: white;
    font-weight: bold;
    font-size: 18px;
    border: none;
    border-radius: 5px;
    transition: 1s all;
    cursor: pointer;
}
.enviar:hover {
    background: darkorange;
    transform: scale(1.2);
}
<table>
    <thead>
        <tr>
            <th>Dia</th>
            <th>Horário</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Segunda</td>
            <td>8h ~ 20h</td>
        </tr>
        <tr>
            <td>Quarta</td>
            <td>8h ~ 20h</td>
        </tr>
        <tr>
            <td>Sexta</td>
            <td>8h ~ 20h</td>
        </tr>
    </tbody>
</table>
table {
    margin: 20px 0 40px;
}

thead {
    background: #555555;
    color: white;
    font-weight: bold;
}

td, th {
    border: 1px solid #000000;
    padding: 8px 15px;
}

}

