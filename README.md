<link rel="stylesheet" href="assets/style.css ">
    <title>Flashcard</title>
</head>
<body>
    <main>
        <section id="container">
            <article class="cartao">
                <div class="cartao__conteudo">
                    <h3>PROGRAMAÇÃO</h3>
                    <div class="cartao__conteudo__pergunta">
                        <p>O que é javascript?</p>
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
                        <p>quem foi a primeira pessoa a programar ?</p>
                    </div>
                    <div class="cartao__conteudo__resposta">
                    <p>A primeira programadora da história foi Ada Lovelace.</p>
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


body {
    background-color: bisque;
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
    background-color: aquamarine;
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
