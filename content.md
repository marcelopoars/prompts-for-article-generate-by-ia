# A Importância do HTML Semântico: Melhores Práticas


## Introdução ao HTML Semântico

HTML Semântico é uma abordagem que dá significado às estruturas de uma página web, tornando-as mais compreensíveis para humanos e máquinas. Em vez de simplesmente usar tags genéricas, como `<div`> e `<span>`, o HTML Semântico usa tags que descrevem o conteúdo que elas contêm. Isso melhora a acessibilidade, SEO e manutenibilidade do código.

## A importância do HTML

Entender a importância do HTML é fundamental para qualquer desenvolvedor front-end. O HTML é a espinha dorsal de qualquer página web, fornecendo a estrutura básica e o conteúdo para os navegadores renderizarem. Utilizar HTML Semântico significa comunicar de forma clara a intenção por trás de cada elemento na página, o que facilita a compreensão do código por outros desenvolvedores, motores de busca e tecnologias assistivas.

## O que mudou com a chegada do HTML5?

Com o HTML5, foram introduzidas muitas novas tags semânticas, como `<header>`, `<nav>`, , `<section>`, `<article>`, `<footer>` entre outras. Essas tags fornecem uma maneira mais clara de estruturar o conteúdo de uma página web, substituindo o uso excessivo de `<div>s` que é tag sem valor semânti algum. Isso torna o código mais legível e compreensível, tanto para humanos quanto para máquinas.

## Principais TAGs HTML5

Vamos ver algumas tags introduzidas no HTML5 e como devemos usá-las para criar páginas web mais semânticas e acessíveis.


### HEADER

A tag `<header>` é usada para definir o cabeçalho de uma seção ou documento HTML. Ela geralmente contém elementos introdutórios ou de navegação, como logotipos, menus e outros conteúdos relevantes para a parte superior da página.

Exemplo:

```html
<header>
  <h1>Meu Site</h1>
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Sobre</a></li>
      <li><a href="#">Contato</a></li>
    </ul>
  </nav>
</header>
```

### NAV

A tag é `<nav>` é usada para definir uma seção de navegação em um documento HTML. Esta tag é ideal para agrupar links de navegação, menus e outros elementos relacionados à navegação dentro do site.

Exemplo:

```html
<nav>
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">Sobre</a></li>
    <li><a href="#">Contato</a></li>
  </ul>
</nav>
```

### SECTION

A tag `<section>` é usada para definir uma seção dentro de um documento HTML. A tag <section> é uma maneira de agrupar conteúdo tematicamente relacionado e pode ser usada para dividir uma página em seções distintas.

Exemplo:

```html
<section>
  <h2>Seção Principal</h2>
  <p>Conteúdo da seção...</p>
</section>
```

### ARTICLE

A tag `<article>` define um conteúdo independente que faz sentido por si só e pode ser reutilizada ou distribuída de forma independente. Você pode usaresta tag para marcar posts de um blog, notícias, comentários de usuários e outros tipos de conteúdo autônomo.

Exemplo:

```html
<article>
  <h2>Meu Primeiro Artigo</h2>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
</article>
```


### FOOTER

A tag `<footer>` define o rodapé de uma seção ou documento HTML. É comumente usada para informações de direitos autorais, links de contato, informações de localização, ou qualquer outro conteúdo que pertença ao final da página.

Exemplo:

```html
<footer>
  <p>&copy; 2024 Meu Site. Todos os direitos reservados.</p>
</footer>
```

### MAIN

 A tag <main> é usada para envolver o conteúdo principal de uma página web. Sua principal finalidade é indicar claramente qual é o conteúdo principal do documento. É importante notar que a tag <main> deve ser usada apenas uma vez em um documento HTML.

 ```html
 <!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Uso da Tag Main</title>
  </head>
  <body>
  <header>
    <h1>Meu Site</h1>
  </header>

  <main>
    <article>
      <h2>Meu Primeiro Artigo</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
    </article>
  </main>

  <footer>
    <p>&copy; 2024 Meu Site. Todos os direitos reservados.</p>
  </footer>

  </body>
</html>
 ```

## Conclusão

Usar HTML Semântico e seguir boas práticas de marcação não apenas torna o código mais legível, mas também melhora a acessibilidade e a indexação pelos motores de busca. Ao utilizar as tags semânticas do HTML5, podemos criar páginas web mais claras e bem estruturadas, o que também facilita o entendimento e manutenção do código.

Este conteúdo foi gerado com ChatGPT e revisado por humano (eu). 

#HTML #HTMLSemântico #DesenvolvimentoWeb