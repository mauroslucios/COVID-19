# COVID-19
## Desafio Gama Academy VTEX
https://hiringcoders.gama.academy/
- FlexBox
- Html

[![Covid Gama Acdemy](https://i.imgur.com/KaTghoH.png "Covid Gama Acdemy")](https://nervous-heyrovsky-67d313.netlify.app/ "Covid Gama Acdemy")

### css
```css
*{margin: 0;padding: 0;font-size: 100%;font-family: 'Open Sans', sans-serif; box-sizing: border-box;
    color:#707070;
    scroll-behavior: smooth;
}
html a{text-decoration: none;text-transform: uppercase;}
ul li{text-decoration: none;cursor: pointer; list-style-type: none;}

/*header*/
header{
    background-color: #fafafa;/*#b3e5fc;*/
    width: 100%;
    position: absolute;
    top: 0;
    left: 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding:20px 50px ;
}
header{ vertical-align: middle !important;}
header nav ul{display: flex;}
header nav ul li{margin:0px 15px; }
header li:first-child{margin-left: 0px;}
header li:last-child{margin-right: 0px;}
@media(max-width:700px){
    header{flex-direction: column;}
    header img{margin-bottom: 15px;}
    header ul .in{display: none;}
	header ul li{padding-top:20px}
	header a{padding-bottom:15px}
}

/*carrousel*/
.carrousel{
    background-image: url(../img/coronavirus-4833754_1920.jpg);background-size: cover; min-height: 100vh;display: flex;
    justify-content: center; align-items: center; flex-direction: column;text-align: center;}
.carrousel h1{font-size: 3rem;margin-bottom: 15px; margin-top:150px;text-transform: uppercase;color: #ffffff;}
.carrousel h3{font-size: 2rem;margin-bottom: 15px;text-transform: uppercase;color: #ffffff;}
.btn{color:#ff8f00 ;text-decoration: none; background-color: #fff; border-radius: 5px;padding: 20px 50px; text-transform: uppercase;}
@media(max-width:700px){
    .carrousel h1{font-size:1.5rem;}
    .carrousel h3{font-size:0.5rem;}
}
/*sobre mim*/
.sobre{display: flex; flex-direction: column; align-items: center; padding: 50px;}
.sobre .eu{border-radius: 100px;margin-bottom: 15px;}
.sobre h3{font-size: 2rem; margin-bottom: 35px;color:#616161 ;}
.sobre p{max-width: 800px; margin-bottom: 35px;text-align: center}
.sobre hr{ width:200px ; height: 2px; background-color:#707070;margin-bottom: 70px; border:none}

.sbr{display: flex;justify-content: space-between; flex-direction: row; flex-wrap: nowrap;}
.sbr .small{flex-basis: 40%;padding:10px}
.sbr .large{flex-basis: 60%;}
.small h1{font-size: 2rem; text-transform: uppercase;}
.small p{font-size: 1.5rem;text-align: left;}
@media(max-width:700px){
    .sbr .large{flex-basis: 100%;} 
    .sbr .audio{display: none;}
    .sbr .small{display: none;}
}
/*notícias*/
.noticias{background-color:#e0f2f1;display: flex; flex-direction: column; align-items: center; padding: 50px;}
.noticias h3{font-size: 2rem; margin-bottom: 35px;color:#707070 ;}
.noticias p{max-width: 800px; margin-bottom: 35px;text-align: center}
.noticias hr{ width:200px ; height: 2px; background-color:#707070;margin-bottom: 70px; border:none}

.noticias .destaques{width: 100%; display: flex;}
.noticias .destaques li{padding: 0px 30px; text-align: center;}
.noticias .destaques li h4{ text-transform: uppercase; font-size: 1.5; margin-bottom: 30px;}
.noticias .destaques li img{border-radius: 100%;}
@media(max-width:700px){
    .noticias .destaques{flex-direction: column;} 
}
/*saiba mais*/
.saiba{display: flex; flex-direction: column; align-items: center; padding: 25px;}
.saiba h3{font-size: 2rem; margin-bottom: 35px;color:#707070 ; text-transform: uppercase;}
.saiba hr{ width:200px ; height: 2px; background-color:#707070;margin-bottom: 70px; border:none}
.saiba .btn-saiba{border-radius: 5px; background-color: #76ff03; color: #ffffff; padding: 20px; margin: 10px auto 30px auto;}
/*contato*/
.contato{width:100%;display: flex;justify-content: space-between;padding: 25px;}
.contato .form h3{font-size:1.5rem;}
.contato .mapa{padding: 17px;margin: 10px;}
.contato .form label, .contato .form input, .contato .form textarea{width: 100%; margin: 9px;}
.contato .form input{height: 40px;padding: 3px; border: solid 1px #c3c63b;}
.contato .form textarea{border: solid 1px #c3c63b;}
.contato .form button{width: 150px;border-radius: 5px; color: #ffffff; padding: 15px; margin: 0px  5px; border: none; cursor: pointer;}
.contato .form .enviar{background-color:#4285F4 ;}
.contato .form .limpar{background-color:#ff4444;}
@media(max-width:700px){
    .contato .form{flex-direction: column; width: 100%; align-items: center; }
    .contato .form button{width:45%;flex-direction: row; text-align: center;}
    .contato .mapa{display: none;} 
}
/*footer*/
footer{ display: flex; flex-direction: column;background-color: #2E2E2E;padding: 50px 0px; align-items: center;}
footer ul{display: flex; margin-bottom: 25px;}
footer ul li{margin-right: 10px;}
footer ul li:last-child{margin-right: 0px;}
footer ul li a{font-size: 2rem;}
footer p{color: #fff;}

/*top*/
.top button{position:fixed;right:20px;bottom:40px;border-radius:50%;background:#37474F;border:none;color:white;height:50px;
    width:50px;}
```

### Html

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page Mauros Lucios</title>
    <link rel="stylesheet" href="css/style.css">
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/92d10664c3.js" crossorigin="anonymous"></script>
</head>

<body>
    <header id="top">
        <a href="#" alt="coronovirus"><img src="img/logo.png" alt="coronovirus"></a> Hiring Coders Gama Academy
        <nav>
            <ul>
                <li><a href="#noticias">home</a></li>
                <li><a href="#sobre">sobre</a></li>
                <li><a href="#contato">contato</a></li>
                <li><a href="#saiba">saiba mais</a></li>
                <li class="in"><a href="https://www.linkedin.com/in/mauro-l%C3%BAcio-pereira-84114922/" target="blank">
                    <i class="fab fa-linkedin fa-2x"></i></a></li>
            </ul>

        </nav>
    </header>
    <section class="carrousel">
        <h1>"coronavirus" a praga deste século</h1>
        <h3>vamos refletir, superar, aprender e melhorar</h3>
        <a href="#saiba" class="btn">saiba mais</a>
    </section>
    <section class="sobre" id="sobre">
        <img src="img/eu.jpg" alt="" class="eu">
        <h3>Sobre o Mauro</h3>
        <p>Formado em Redes de Telecomunicações pela UCP - Universidade Católica de
            Petrópolis e buscando novos caminhos como desenvolvedor</p>
        <hr>
        <section class="sbr">
            <div class="small">
                <h1>carta coronovirus ao mundo</h1>
                <p>Um lamento aos maus-tratos da humanidade ao eco-sistema de onde tira todo seu
                    sustento, mas não retribui e tampouco se preocupa com acontecimentos futuros.
                </p>
                <audio controls class="audio">
                    <source src="audio/audio.mp3" type="audio/mp3">
                </audio>
            </div>
            <div class="large">
                <iframe width="100%" height="100%" src="https://www.youtube.com/embed/tJwWfqOhI4g" frameborder="0"
                    allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
                    allowfullscreen></iframe>
            </div>
        </section>
    </section>
    <section class="noticias" id="noticias">
        <h3>notícias do covid-19 pelo mundo</h3>
        <hr>
        <ul class="destaques">
            <li>
                <img src="img/equador.jpg" alt="">
                <h4>Equador</h4>
                <p>
                    Provincia mais atingida pelo coronavirus no equador teve 67 mil mortes em 15 dias. Estado esta em
                    colapso.
                </p>
            </li>
            <li>
                <img src="img/sp.jpg" alt="">
                <h4>Brasil</h4>
                <p>
                    Pessoas usam máscara de proteção como medida de combate a disseminação na região central de São
                    Paulo.
                </p>
            </li>
            <li>
                <img src="img/MarianaPinto.jpg" alt="">
                <h4>Brasil</h4>
                <p>
                    População deve usar máscaras simples, feitas em casa a partir de diversos materiais, dizem
                    especialistas para proteção.
                </p>
            </li>
            <li>
                <img src="img/whuran.jpg" alt="">
                <h4>China</h4>
                <p>EUA investigam possibilidade de o novo coronavírus ter vazado de laboratório chinês; China diz que
                    Trump quer confundir o público</p>
            </li>
            <li>
                <img src="img/mandeta.jpg" alt="">
                <h4>Brasil</h4>
                <p>
                    O ministro da Saúde, Luiz Henrique Mandetta, orientou para o uso das máscaras no Brasil contra a
                    contaminação.
                </p>
            </li>
            <li>
                <img src="img/trump.jpg" alt="">
                <h4>Estados unidos </h4>
                <p>
                    "Nós continuamos a ver um número de sinais positivos de que o pico do vírus já passou", disse o
                    chefe da Casa Branca.
                </p>
            </li>
        </ul>
    </section>
    <section class="saiba" id="saiba">
        <h3>saiba mais</h3>
        <a href="https://g1.globo.com/mundo/" class="btn-saiba">Quer saber mais notícias?</a>
        <hr>
    </section>
    <section class="contato" id="contato">
        <div class="form">
            <h3>Contato:</h3>
            <form action="">
                <label for="nome">Nome:</label>
                <input type="text" name="" placeholder="nome" id="" required>
                <label for="nome">Email:</label>
                <input type="email" name="" placeholder="email" id="" required>
                <label for="nome">Telefone:</label>
                <input type="telefone" name="" placeholder="telefone" id="" required>
                <textarea name="" id="" cols="30" rows="10"></textarea>
                <button class="enviar" type="submit">Enviar</button>
                <button class="limpar" type="reset">Limpar</button>
            </form>
        </div>
        <div class="mapa">
            <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3684.816856840521!2d-43.21782168572944!3d-22.5485323130118!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x99090b1fed3c55%3A0xadd32c4d5e0496c6!2sR.%20Leila%20Diniz%20-%20Independ%C3%AAncia%2C%20Petr%C3%B3polis%20-%20RJ%2C%2025645-410!5e0!3m2!1spt-BR!2sbr!4v1587261930745!5m2!1spt-BR!2sbr"
                width="600" height="480" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false"
                tabindex="0"></iframe>
        </div>
    </section>
    <footer>
        <ul>
            <li><a href="https://www.facebook.com/mauroslucios" target="_blank"><i class="fab fa-facebook" style="color:#fff"></i></a></li>
            <li><a href="https://www.linkedin.com/in/mauro-l%C3%BAcio-pereira-84114922/" target="_blank"><i class="fab fa-linkedin" style="color:#fff"></i></a></li>
        </ul>
        <p>Todos os Direitos Reservados</p>
    </footer>
    <a href="#top" class="top"><button>topo</button></a>
</body>

</html>
```
