link rel="stylesheet" href="assets/style.css ">
    <title>Flashcard</title>
</head>
<body>
    <main>
        <section id="container">
            <article class="cartao">
                <div class="cartao__conteudo">
                    <h3>PROGRAMAÇÃO</h3>
                    <div class="cartao__conteudo__pergunta">
                        <p>    O que é javascript?</p>
                    </div>
                    <div class="cartao__conteudo__resposta">
                    <p>O javascript é uma linguagem de programação.</p>
                    </div>
                </div>
            </article>
            <article class="cartao">
                <div class="cartao__conteudo">
                    <h3>PROGRAMAÇÃO</h3>
                    <div class="cartao__conteudo__pergunta">
                        <p> o que é style.css ?</p>
                    </div>
                    <div class="cartao__conteudo__resposta">
                    <p>Em desenvolvimento web, style.css é um arquivo que contém código CSS (Cascading Style Sheets).</p>
                    </div>
                </div>
            </article>
            <article class="cartao">
                <div class="cartao__conteudo">
                    <h3>PROGRAMAÇÃO</h3>
                    <div class="cartao__conteudo__pergunta">
                        <p>o que é CSS?</p>
                    </div>
                    <div class="cartao__conteudo__resposta">
                        <p>O CSS é uma linguagem estilização.</p>
                    </div>
                </div>
            </article>
        </section>
    </main>
    <footer>
        <p>projeto desenvolvido pelo aluno Henry, sem fins lucrativos</p>
    </footer>
</body>
</html>

style.css


:root {
    --text-color: #DBE4EF;
    --card-front-color: #144480;
    --card-back-color: #00F4BF;
}
 

body {
    background: url(img/bg-desktop.webp);
    font-family: Bai Jamjuree;

   }
   #container{
display: flex;
 }

 .cartao {
    margin: 1rem  1rem;
    background-color:aqua;
    height: 20rem;
    flex-grow: 1;
    flex-basis: calc(33% - 6rem);


}

.cartao__conteudo{
    text-align: center;
   /* background-color: aquamarine;*/
    height: 100%;
}
    
.cartao__conteudo h3 {
     color: var(--text-color);
     border: 1px solid var(--text-color);
     text-align: left;
     padding: 0.5rem;
     position: absolute;
     margin: 0.6rem;
     border-radius: 0.6rem;
     font: 1vw;
}
.cartao__conteudo p {
    margin-top: 1rem;
    padding: 2rem;
    
}

   footer {
       background-color: black;
       color: white;
       position: fixed;
       bottom: 0;
       width: 100%;
       height: 2rem;
   }
   
   footer p{
       text-align: center;
       font-size: 0.6rem;
       margin-top:0.5rem ;
   }

