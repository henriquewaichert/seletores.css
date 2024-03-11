# seletores.css

/* Exercícios
1. Implemente um código CSS para mudar as cores dos links de uma página. A
cor padrão do link deverá ser vermelha ( red ) e deverá mudar para limão (lemon)
quando sobreposta pelo mouse.
*/

    a {
        color: red;
    }

    a:hover {
        color: lime;
    }

/*
2. Implemente um código CSS que irá customizar os parágrafos da seguinte
forma.
•Parágrafos em geral terão a fonte Arial
•Parágrafos declarados logo após h1 ficarão em negrito
*/

    p {
        font-family: Arial, Helvetica, sans-serif;
    }
    h1 + p {
        font-weight: bold;
    }

/*
3. Implemente um código CSS para estilizar a classe .destaque da seguinte forma.
•Por padrão, utilizará a fonte Arial
•Se atribuída a um parágrafo, ficará em negrito
•Se atribuída a um <strong> , ficará em vermelho
*/

    .destaque {
        font-family: Arial, Helvetica, sans-serif;
    }

    p.destaque {
        font-weight: bold;
    }

    strong.destaque {
        color: red;
    }
