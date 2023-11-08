# O que é CSS?

CSS é chamado de linguagem Cascading Style Sheet e é usado para estilizar elementos escritos em uma linguagem de marcação como HTML. O CSS separa o conteúdo da representação visual do site. Pense  na decoração da sua página. Utilizando o CSS é possível alterar a cor do texto e do fundo, fonte e espaçamento entre parágrafos. Também pode criar tabelas, usar variações de layouts, ajustar imagens para suas respectivas telas e assim por diante.

# CSS Básico

Ao adicionar a tag style comandos de CSS podem ser escritos em seu arquivo HTML.

```
<style>
p {
color: blue;
text-weight: bold;
}
<style>
```

Por exemplo, o comando abaixo alinha os conteúdos da tag p para o centro da tag body, atribui o tamanho da fonte para 16 px e muda a cor da fonte para rosa.

```
<style>
p {
 text-align: center;
 font-size: 16px;
 color: pink;
}
</style>

```

## A tag ```<div>``` 

O elemento de divisão ```<div>``` é um container genérico para conteúdo de fluxo, que de certa forma não representa nada.

```
<div>
  Eu estou dentro de uma div
</div>
```

## Classes no CSS

As classes são uma forma de identificar um grupo de elementos. Através delas, pode-se atribuir formatação a vários elementos de uma vez. O código a seguir cria uma classe que é atribuída a uma div.

```CSS
 .caixa_vermelha {
     width: 250px;
     height: 250px;
     background-color: red;
     border: 2px solid blueviolet; 
 }
```

```HTML
<div class="caixa_vermelha">
 Eu estou dentro da caixa vermelha
</div>
```


