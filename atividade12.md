# Atividade12

# ESTRUTURA DO HTML

## Definição

Hypertext Markup Language (ou HTML, para simplificar), é uma linguagem utilizada para definir como determinado conteúdo será exibido em uma página web.
Possui as extensões **.htm** ou **.html**, e são utilizados editores de texto para a criação desses arquivos.

*se der colocar imagens de editores de texto

---

## Estrutura

A seguir serão mostradas todas as tags e declarações necessárias para construir um arquivo HTML básico do zero.

##

#### DOCTYPE

O DOCTYPE representa a primeira linha de um documento HTML. É uma declaração DTD (Document Type Declaration),para informar ao navegador o tipo de documento que está sendo utilizado.

A declaração é feita utilizando o comando abaixo:

```
<!DOCTYPE html>
```

Feito isso, se inicia a construção do código.

##

#### Head

Localizada no início do código, é a tag responsável por informar as caraterísticas da sua página.

Geralmente as tags ```<meta>``` e ```<title>``` são utilizadas dentro da tag ```<head>```.

 A tag ```<meta>``` é utilizada para descrever o conteúdo do seu arquivo. Geralmente é seguida pelo atributo ```charset = “utf-8”```, que indica o formato dos caracteres utilizados no documento.

 Já a tag ```<title>``` é apenas o título da página que é exibido na aba do navegador.

---

#### Body

O elemento ``` <body> ``` possui todo o conteúdo do documento HTML, como textos, parágrafos, links, imagens, tabelas, entre outros.

Esse conteúdo é apresentado utilizando **tags semânticas** específicas para cada função desejada.

##### Tags Semânticas

As tags semânticas são as estruturas da linguagem que contém instruções detalhadas para que cada parte de uma página HTML possua uma apresentação visual. Sendo assim, cada tag tem seu significado semântico e uma função específica para o código.

As principais são ```<header>```, ```<nav>```, ```<section>```, ```<article>```, ```<aside>``` e ```<footer>```.

Tag         | Função
:---------: | :------:
header      | É o cabeçalho da pagina.
nav         | Define links para navegação no documento.
section     | Define a sessão de um documento.
article     | Representa um artigo de um documento.
aside       | Se refere a um conteúdo a parte do conteúdo principal.
footer      | Define o rodapé de uma página.

##

Feitas essas declarações, o código ficará assim¹:

```
<!DOCTYPE html> 
<html> <!-- Inicio do HTML -->
    <head> <!-- Início do Cabeçalho da Página -->
        <meta charset="utf-8"> <!-- Definição do charset a ser utilizado -->
        <title> Título da Página </title> <!-- Definição do Título da Página -->
    </head>
    <body> <!-- Início do Corpo do Documento -->
        ... inserir seu conteúdo aqui ...
    </body> <!-- Fim do Corpo do Documento -->
</html> <!-- Fim do HTML -->
 ```

 As tags semânticas são inseridas dentro do ```<body>``` conforme a necessidade do desenvolvedor.
#
¹ Código retirado do material de aula - DWEI5_Aula02_HTML-CSS-JS_Introducao

---

 ### REFERÊNCIAS
  Materiais de aula:
  DWEI5_Aula02_HTML-CSS-JS_Introducao
  DWEI5_Aula03_HTML-TagsBasicas_CSS-PropriedadesFontesTextos

  Outros sites:
  https://www.w3schools.com/TAGS/default.ASP
