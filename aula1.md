## AULA 01 - Revisão: HTML, CSS, JS na Prática

Primeiro passo para mergulhar na Imersão Front-End.

### Nessa aula foi visto...

Nesta aula, foi iniciado o projeto da recriação da página inicial do Spotify por meio do HTML e do CSS, aprendendo atalhos, recursos e as diferenças entre os códigos.

### Conceitos

- No HTML 5 a tag <nav></nave> trouxe mais semântica para as outras tags html. Ex: Ao inves de usar tag div com class nav, usar direto a tag nav que ja tem peso semântico. 
    - O que é peso semântico: É aquela tag dizer extamento qual é a função dela. Ex: Não precisar forçar que um <link> vire um <botao> se ja existe essa tag para botão.

### Ferramenta

- Font Awesome: Oferece itens como icone, fontes... entre outros estilos CSS de forma gratuita.
    ##### Como adicionar ícones ao site via CDN?
    Os links para CDN são: solid.css e fontawesome.css
    ```html
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Spotify Imersão</title>

        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="styles.css">

        <!-- Links para trazer os ícones via CDN -->
        <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/solid.css"/>
        <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/fontawesome.css"/>
    </head>
    ```
    ##### Por que usar o CDN?

    O CDN é como se fosse uma "biblioteca online" que permite adicionar recursos ao código. Na aula, precisávamos usar ícones no HTML, e por padrão, o HTML não possui esse recurso. Então, para que possamos adicionar os ícones, foi necessário carregar uma biblioteca externa que forneça esses ícones. É aí que entra o link do CDN, como pecinhas de lego para dar mais poder ao código.

### Códigos

- Criar pasta | Entrar na pasta | Abrir VS Code
```bash
mkdir spotify-imersao-alura
cd spotify-imersao-alura
code .
```
- O código pode ser iniciado incluindo atributos ao escrever os elementos HTML. Ex: div(elemento) class(atributo) = div.nomeDaClasse + Enter
```html
<div class="sidebar"></div>
```
- Quandor fizer uma lista no VS Code pode ser usado essa linha para 2 <li> o comando ul>li*2 + Enter
```html
<ul>
    <li></li>
     <li></li>
</ul>
```

### Extensão | Snippet

- Snippet do VS Code chamado "Live Server" irá criar um servidor para página. Após instalar nas extensões clicar em "Go live" no rodape para abrir.


### Tag

- Tag <nav></nave> responsável por criar menu
- Tag <link/> chama/carrega o CSS no html via href que é o relacionamento com o styles

## Dicas

- Estrautura de pasta não deve ser a preocupação no inicio do projeto, deve deixar que ao longo do desenvolvimento o aumento de código e da complexidade a necessidade de organizar será sentida.
- Criar estratura básica do HTML com "! + Enter".
- Usar comando "Ctrl + B" para fechar/abrir menu esquerdo.