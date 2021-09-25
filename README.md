# Atividade de Núcleo

## Informações principais

- **Núcleo:** Web
- **Orientador:** [Lávio Vale](@lavio) [Monique Silva](@moniquedsilva)
- **Data da Atividade:** 18/09/2021
- **Data de Entrega:** 25/09/2021

## Descrição da atividade

O projeto Coffee Shop tem por objetivo continuar o aprendizado em HTML e CSS, e inicar o aprendizado em Javascript, completando assim as 3 tecnnologias bases do front-end. O projeto possui o formato landing page¹, em que todas as suas informações estão dispostas em uma única página.

### Tarefa

Com base no [mockup²](https://www.figma.com/file/O6TKo1DWnesp1tuF0rY4OZ/Coffee-Shop?node-id=0%3A1) apresentado, usando HTML, CSS e Javascript, construa a landing page da cafeteria Coffee Shop. Além do desenvolvimento da página, é fundamental que o layout se adapte a diferentes larguras e resoluções de tela, como as de smartphones e tablets, ação conhecida como design responsivo. Implemente as modificações necessárias para que seu layout seja responsivo.

Acesse a [issue](https://gitlab.com/InfoJrUFBA/nucleos/2021/03/web/-/issues/2) da atividade para visualizar todos os requisitos que serão avaliados na hora da correção

## Design Responsivo

- Significa que seu site pode se adaptar a diferentes tipos de telas como desktops, laptops, tablets ou smartphones.

![2952ef0b38fed4b201f6d1337194b204](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fsearchengineland.com%2Ffigz%2Fwp-content%2Fseloads%2F2018%2F04%2Fresponsive-design.gif&f=1&nofb=1)

- Funciona usando várias configurações para atender a diferentes propriedades de estilo, dependendo do tamanho da tela.

## Unidade Absoluta x Unidade Relativa

Unidades absolutas possuem valores fixos e aparecerão exatamente como as dimensões mencionadas.

- Exemplos: px, mm, cm, in, pt, pc

Unidades relativas estão vinculadas a outros valores de comprimento como o tamanho máximo da tela. Escala melhor em mídias de diferentes resoluções.

- Exemplos: em, rem, ex, vw, vh, vmin, max, %

Em um contêiner diretamente dentro da janela de visualização com uma largura de 90% sempre terá 90% da largura disponível - esteja eu em um telefone ou tela de alta resolução.

**Sempre opte pelo uso de unidades relativas e deixe para usar unidades absolutas em casos em que realmente necessite de um valor fixo.**

**Unidades recomendadas:**

- Para fontes, margin e padding: **rem** ou em
- Para definir largura e altura dos elementos: % (funciona tanto para largura e altura), vw (view width - largura), vh (view height - altura).

![Relative-units](https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fmark-anthony.ca%2Fwp-content%2Fuploads%2F2015%2F11%2F3038367-inline-i-2-9-gifs-that-explain-responsive-design-brilliantly-02relative-units-vs-static-units-1-copy.gif&f=1&nofb=1)

## Layout responsivo

- Sempre optar pelo uso do flexbox ou grid
- Evitar o uso do position (só para casos específicos, como header fixa na página)
- Não usar margin para posicionar elementos

## O que são breakpoints?

- Breakpoint são as larguras que almejamos em nossas consultas de mídia (media query), porque esse é nesse ponto em que iremos alterar as regras CSS visando mudar o estilo do layout reorganizando seu conteúdo.

![media-queries-1024x426](https://coder-coder.com/wp-content/uploads/2020/03/media-queries-1024x426.png)

![media](https://www.oficinadanet.com.br/imagens/post/13652/3038367-slide-s-3-9-gifs-that-explain-responsive-design-brilliantly-03with-breakpoints-vs-without-breakpoints-1.gif)

## Mobile first x Desktop first

**Mobile first:** Começa com larguras pequenas como as de celulares móveis e gradualmente vai subindo, escolha o ponto da largura da janela no qual deseja que o design mude. Este será o seu ponto de breakpoint.

Declaração do media query quando se utiliza a abordagem mobile first, usando 768px como breakpoint:
`@media (min-width: 768px)`

**Desktop first:** Começa com larguras grande como as de desktop e gradualmente vai descendo, escolha o ponto da largura da janela no qual deseja que o design mude. Este será o seu ponto de breakpoint.

Declaração do media query quando se utiliza a abordagem desktop first, usando 768px como breakpoint:
`@media (max-width: 768px)`

![08_Desktop-first-vs-Mobile-first-3](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fmarquesfernandes.com%2Fwp-content%2Fuploads%2F2019%2F02%2F3038367-slide-s-8-9-gifs-that-explain-responsive-design-brilliantly-08desktop-first-vs-mobile-first-3.gif&f=1&nofb=1)

**Recomendação de abordagem: Mobile first**
Começar o projeto pela versão mobile ajudará você a se manter consistentes com os seus estilos. É melhor para evitar problemas para redimensionar e assim evitar excessivos pontos de quebra.

**Frameworks de CSS que nativamente usam a abordagem mobile first: TailwindCSS, Bootstrap e Foundation**

---

_¹Landing Pages são páginas de um site com um foco principal: conversão. Assim, essas páginas de conversão possuem menos elementos que uma página tradicional, focando apenas na oferta central oferecida por ela. As landing pages são projetadas com um único foco ou objetivo, conhecido como call to action (ou CTA, para abreviar)._

_²Mockup é uma representação estática de um projeto, bem próximo do design final, o seu uso tem como finalidade representar a estrutura da informação, visualizar o conteúdo de forma estática, demonstrar as principais funcionalidades (de forma estática) e estimular os envolvidos a revisarem a parte visual (design) do projeto._

## Materiais de apoio

### Cursos Completos

- Node Studio Treinamentos
  | **[HTML5](https://youtube.com/playlist?list=PLwXQLZ3FdTVGKl3iPEyEWpFoYkMUxWW5O)**
  | **[CSS3](https://youtube.com/playlist?list=PLwXQLZ3FdTVGf7GUtiOFLc_9AXO25iIzG)**
  | **[Javascript](https://youtube.com/playlist?list=PLwXQLZ3FdTVF9Y0RbsuN54XYP7D0dZIlR)**
  | **[HTML5 & CSS3 na Prática](https://youtube.com/playlist?list=PLwXQLZ3FdTVF_HYP5r1oR7vK1_7ZuTU78)**
  | **[Design Responsivo](https://youtube.com/playlist?list=PLwXQLZ3FdTVFi6oHo_K4IYDcwCU5-f1x5)**

### Figma

- [Convert A Figma Design To A Real Website Part.1 - GTCoding](https://youtu.be/q_YNq0j_QfE)
- [Convert A Figma Design To A Real Website Part.2 - GTCoding](https://youtu.be/2r91B6ZwN_E)

### Vídeos/Textos por assuntos presentes na atividade

#### HTML

Estrutura Básica

- [HTML Basic - w3schools (Texto)](https://www.w3schools.com/html/html_basic.asp)
- [Estrutura básica de um Documento HTML - Bóson Treinamentos](https://youtu.be/hMAvQtQ97eE)

HTML Semântico

- [HTML Semantic Elements - w3schools (Texto)](https://www.w3schools.com/html/html5_semantic_elements.asp)
- [Estrutura Semântica do HTML em 25 minutos - Ferreira Studios](https://youtu.be/jEJUopJv12I)
- [Semântica - Dica do Nerd](https://youtu.be/NdAjp7X2CUI)
- [Estruturação da página utilizando tags Semânticas do HTML5 - Tiago Segato](https://youtu.be/6V3msF_YBQk)

#### CSS

Flexbox

- [A Complete Guide to Flexbox - CSS Tricks (Texto)](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Curso de CSS Flexbox - Node Studio Treinamentos](https://youtube.com/playlist?list=PLwXQLZ3FdTVGjLmjwfRc0Q9TA5U-PCWp4)
- [3 Ways to Create a Navigation Bar with Flexbox - Skillthrive](https://youtu.be/PwWHL3RyQgk)

Formatação geral

- [Usando Google Fonts - Curso em Vídeo](https://youtu.be/FLuQonci9wU)
- [Unidades Relativas Part.1 - Ferreira Studios](https://youtu.be/etM0JBeFbf8)
- [Unidades Relativas Part.2 - Ferreira Studios](https://youtu.be/g__c-7M9Xzk)
- [Espaçamentos e a mágica do CSS Box Model - Rocketseat](https://youtu.be/nhW70H9H4gU)
- [Representando Cores com CSS3 - Curso em Vídeo](https://youtu.be/uKjKnztS3cY)
- [min(), max(), and clamp() - Kevin Powell](https://youtu.be/U9VF-4euyRo)
- [Navbar Responsivo com Menu Dropdown - Dev Reis](https://youtu.be/CFmMNuxZ3YY)

Media Queries

- [Responsividade para sites - Curso em Vídeo](https://youtu.be/WcGPSeuJDJ0)
- [Como utilizar Media Queries para sites Responsivos - Origamid](https://youtu.be/AltqAPZzAqo)

#### Javascript

DOM

- [Introdução ao DOM - Curso em vídeo](https://youtu.be/WWZX8RWLxIk)
- [Eventos DOM - Curso em vídeo](https://youtu.be/wWnBB-mZIvY)

Menu

- [Menu Mobile - HTML, CSS e JavaScript - Origamid](https://youtu.be/DnODupiIAiE)
- [Responsive Navigation Menu - Deltaty Code](https://youtu.be/1iS0r238G4g)

Data dinâmica

- [Change Footer Date Automatically with Javascript - RichardCodes](https://youtu.be/xugiXhHS9Bw)

## Instruções para envio

1. Clone este repositório no seu computador
2. Crie a partir da `main` uma nova branch com o seu nome (ou o nome de alguma pessoa do grupo, caso a atividade seja em grupo). Por exemplo: `thales`
3. Inclua seu nome na ficha de entrega do `README.md`
4. Construa a sua atividade apenas nessa branch, e não hesite em pedir por ajuda caso tenha dificuldades
5. Suba constantemente a sua branch para este repositório para possibilitar o acompanhamento por parte dos orientadores
6. Para saber se finalizou a atividade, verifique cuidadosamente se todos os requisitos foram cumpridos
7. Após finalizar a atividade, faça um merge request com o padrão de título: [número da atividade] - [nome da atividade] (por exemplo: 2 - Coffee Shop)
8. Esteja pronto para apresentar o que você fez na próxima RN (Reunião de Núcleo)

## Ficha de entrega

Atividade entregue por: [...]
