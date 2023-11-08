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

## Vamos praticar um pouco

```
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .container {
            font-family: arial;
            position: relative;
            font-size: 24px;
            width: 300px;
            height: 300px;
            outline: dashed 1px black;
            /* Center vertically and horizontally */
            /* justify-content: center;
            align-items: center; */
        }

        .caixa_vermelha1 {
            width: 50px;
            height: 50px;
            background-color: red;
            border: 2px solid blueviolet; 
            position: absolute;
            top: 0px;
            right: 0px;  
            display: flex; 
            justify-content: center;
            align-items: center;           
        }
        .caixa_vermelha2 {
            width: 48px;
            height: 48px;
            background-color: red;
            border: 1px solid blueviolet; 
            position: absolute;
            top:  26px;
            right: 220px; 
            display: flex;    
            justify-content: center;
            align-items: center;          
        }
        .caixa_vermelha3 {
            width: 50px;
            height: 50px;
            background-color: red;
            border: 2px solid blueviolet; 
            position: absolute;
            top:  125px;
            right: 125px;     
            display: flex;
            justify-content: center;
            align-items: center;   
                   
        }                
    </style>
    <title>Document</title>
</head>

<body>
    <div class="container">
        <div class="caixa_vermelha1"> Ok </div>
        <div class="caixa_vermelha2"> Ok </div>
        <div class="caixa_vermelha3"> Ok </div>
    </div>
</body>
</html>
```

## Exercício 



