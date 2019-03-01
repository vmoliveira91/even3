# Teste prático - Dev Backend - 2019

Terceira fase para uma vaga de estágio na empresa Even3.

## Execução

Para execução, clonar meu repositório e abrir o index.html.

````
index.html
````

## Dificuldades

Tiveram requisitos do projeto que eu não domino e não tive de tempo de pesquisar a fundo para conseguir fazer. Mas como foi dito que o mais
importante é não deixar de enviar, eu estou enviando.

### Enviar o plano de fundo

Eu pesquisei por cima e vi que poderia ser feito usando Express.js.

### Edição do plano de fundo

O plano de fundo seria editado na página, como eu não fiz a parte de upar a imagem não me preocupei com essa.

## O que foi feito

Criei o template da página baseado no

````
https://even3.blob.core.windows.net/assets/mock-cracha2.png
````

Coloquei o link com diversos templates para ajudar o organizadoro.

Foi criado uma <textarea>, onde é copiado o conteúdo da planilha de participantes(Ctrl+C + Ctrl+V).

A impressão dos crachás é feita em um único PDF ao clicar no <button> Baixar crachás.

Como eu não enviei o plano de fundo, eu coloquei um dos exemplos de crachá na minha pasta do projeto. E usando pdfmake, eu o coloquei como
plano de fundo dos crachás. E como também não fiz a edição do plano de fundo, eu criei meu próprio template dos textos que vão no crachá.

````
{Nome}
{Instituição}(se houver)
{País}
````

## O que foi utilizado

### HTML, CSS, Bootstrap v4.0

Para lidar com as partes do front-end.

### JS

Para fazer a operação de 'confecção' e download dos crachás.

### pdfmake

A client/server side PDF printing in pure JS.
