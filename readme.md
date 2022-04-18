# Curso Alura HTML e CSS
## _Aprendizado_

Neste curso aprendi sobre HTML e CSS, mas me surpreendi com ::after e ::before.

Otimizando assim minhas possibilidades no CSS, preenchi diversas lacunas em meu aprendizado saindo do meu conhecimento basico.

- Aprendi sobre transition e transform 
> Onde transition é qual animação sera feita ao mudar o elemento.
> E transform qual mudança sera feita no elemento. 
> Assim utilizando transition fora de um evento para habilitar a todas mudanças
> ou no evento para mudar a transição desejada para somente no evento.

```sh
.Enviar{
    width: 40%;
    padding: 15px 0;
    background-color: whitesmoke;
    color: darkorange;
    font-weight: bold;
    font-size: 18px;
    border: none;
    border-radius: 5px;
    transition: all .3s ease;
        transition-property: all;
        transition-duration: 0.3s;
        transition-timing-function: ease;
        transition-delay: 0s;
    cursor: pointer;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
    border: #CCCCCC .3px solid;
}

.Enviar:hover{
    box-shadow: none;
    transform: translateY(3px);
    text-shadow: #000000;
}
```
- e Aprendi muito sobre After, before, First-child e etc
```sh
.titulo-principal{
    text-align: center;
    font-size: 2em;
    margin: 0 0 1em;
    clear: left;
}

.titulo-principal::first-letter{
    font-weight: bold;
}

.itens::before{
    content: "\272F";
}

.itens:first-child::before{
    content: none;
}

.titulo-principal::before{
    content: "[ ";
}
.titulo-principal::after{
    content: " ]";
}
```
