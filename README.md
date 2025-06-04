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




body {
    background-color: bisque;
    font-family: Bai Jamjuree;

   }
   #container{
display: flex;
   }

.cartão{
    margin: 1rem  1rem;
    background-color: blue;
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
