# Desafio de Filmes com Framework

## Índice

- [1. Preâmbulo](#1-preambulo)
- [2. Resumo do projeto](#2-resumo-do-projeto)
- [3. Considerações gerais](#3-considerações-gerais)
- [4. Objetivos de aprendizagem](#4-objetivos-de-aprendizagem)
- [5. Critérios mínimos de aceitação do projeto](#5-criterios-de-aceitacao-minimos-do-projeto)
- [6. Considerações técnicas](#6-consideracoes-tecnicas)

---

## 1. Preâmbulo

A forma como assistimos filmes mudou radicalmente nos últimos anos, em parte
devido ao surgimento dos serviços de
[_streaming_](https://pt.wikipedia.org/wiki/Streaming), que nos permitem
fazê-lo de onde quer que estejamos e a qualquer momento. O melhor reflexo desse
fenômeno é o sucesso da Netflix, HBO, Disney+ e outros.

Acreditamos que há uma grande oportunidade de propor produtos/experiências
inovadoras de todos os tipos usando dados de filmes (diretorxs, atorxs, sagas,
sequências, datas, etc.). Poderíamos pensar em jogos, comunidades, catálogos,
recomendações baseadas em gostos pessoais, etc.
(apenas para mencionar algumas ideias óbvias).

![Filmes](https://live.staticflickr.com/117/257368762_38bf6fcf9f_h.jpg)

## 2. Resumo do projeto

A ideia deste projeto é que, usando uma API com informações de filmes, você
possa planejar, organizar e desenvolver uma aplicação web que utilize esses
dados e tenha uma proposta de valor atraente para lxs usuárixs.

Embora a decisão do que fazer seja totalmente sua, há algumas considerações
gerais apresentadas a seguir. Você pode atender a esses requisitos em projetos
muito diferentes, dependendo da sua criatividade e entendimento de seus
potenciais usuárixs!

Para implementar este projeto, você deverá escolher um framework entre
[React](https://pt-br.reactjs.org/) e [Angular](https://angular.io/).
Ao escolher um _framework_ ou _biblioteca_ para nossa interface, apoiamo-nos
em uma série de convenções e implementações _testadas_ e _documentadas_ para
resolver um problema comum a todas as interfaces da web:
[_manter a interface sincronizada com o estado_](https://medium.com/dailyjs/the-deepest-reason-why-modern-javascript-frameworks-exist-933b86ebc445).
Isso nos permite concentrar-nos melhor (dedicar mais tempo) nas características
_específicas_ de nossa aplicação.

Quando escolhemos uma dessas tecnologias, não só importamos um pedacinho de
código para reutilizá-lo (o que é um grande valor por si só), mas adotamos uma
**arquitetura**, uma série de **princípios de design**, um **paradigma**, umas
**abstrações**, um **vocabulário**, uma **comunidade**, etc.

Como desenvolvedora Front-end, esses kits de desenvolvimento podem ser de grande
ajuda para implementar rapidamente recursos dos projetos em que você trabalha.

## 3. Considerações gerais

- Este projeto deve ser resolvido em equipes de no máximo 3 pessoas.
- Você deve escolher e justificar qual problema ou necessidade está resolvendo
  com o produto que está projetando e desenvolvendo.
- Você deve utilizar os dados da API do
  [The Movie Database API V3](https://developers.themoviedb.org/3/getting-started/introduction)
  ou
  [OMDB](http://www.omdbapi.com/) (The Open Movie Database) ou qualquer
  outra API que encontrar.
- Para implementar este projeto, você deve escolher um framework entre
  React ou Angular.
- Tente pensar em um escopo que, considerando sua complexidade e a quantidade de
  pessoas na equipe, permita concluir o projeto em 3 ou 4 semanas.

## 4. Objetivos de aprendizagem

Reflita e depois enumere os objetivos que quer alcançar e aplique no seu projeto. Pense nisso para decidir sua estratégia de trabalho.

### HTML

- [ ] **Uso de HTML semântico**

  <details><summary>Links</summary><p>

  * [HTML semântico](https://curriculum.laboratoria.la/pt/topics/html/02-html5/02-semantic-html)
  * [Semantics in HTML - MDN](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#Semantics_in_HTML)
</p></details>

### CSS

- [ ] **Uso de seletores de CSS**

  <details><summary>Links</summary><p>

  * [Intro a CSS](https://curriculum.laboratoria.la/pt/topics/css/01-css/01-intro-css)
  * [CSS Selectors - MDN](https://developer.mozilla.org/pt_BR/docs/Web/CSS/CSS_Selectors)
</p></details>

- [ ] **Modelo de caixa (box model): borda, margem, preenchimento**

  <details><summary>Links</summary><p>

  * [Modelo de Caixa e Display](https://curriculum.laboratoria.la/pt/topics/css/01-css/02-boxmodel-and-display)
  * [The box model - MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
  * [Introduction to the CSS box model - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)
  * [CSS display - MDN](https://developer.mozilla.org/pt-BR/docs/Web/CSS/display)
  * [display - CSS Tricks](https://css-tricks.com/almanac/properties/d/display/)
</p></details>

- [ ] **Uso de flexbox em CSS**

  <details><summary>Links</summary><p>

  * [A Complete Guide to Flexbox - CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  * [Flexbox Froggy](https://flexboxfroggy.com/#pt-br)
  * [Flexbox - MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
</p></details>

- [ ] **Uso de CSS Grid Layout**

  <details><summary>Links</summary><p>

  * [A Complete Guide to Grid - CSS Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)
  * [Grids - MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Grids)
</p></details>

- [ ] **Uso de media queries**

  <details><summary>Links</summary><p>

  * [CSS media queries - MDN](https://developer.mozilla.org/pt-BR/docs/Web/CSS/Media_Queries/Using_media_queries)
</p></details>

### JavaScript

- [ ] **Testes unitários (unit tests)**

  <details><summary>Links</summary><p>

  * [Introdução ao Jest - Documentação oficial](https://jestjs.io/docs/pt-BR/getting-started)
</p></details>

- [ ] **Testes assíncronos**

  <details><summary>Links</summary><p>

  * [Testando Código Assíncrono - Documentação oficial](https://jestjs.io/docs/pt-BR/asynchronous)
</p></details>

- [ ] **Uso de mocks e espiões**

  <details><summary>Links</summary><p>

  * [Simulações Manuais - Documentação oficial](https://jestjs.io/docs/pt-BR/manual-mocks)
</p></details>

- [ ] **Módulos de ECMAScript (ES modules)**

  <details><summary>Links</summary><p>

  * [import - MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/import)
  * [export - MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/export)
</p></details>

- [ ] **Uso de linter (ESLINT)**

- [ ] **Uso de identificadores descritivos (Nomenclatura e Semântica)**

### Controle de Versões (Git e GitHub)

- [ ] **Git: Instalação e configuração**

- [ ] **Git: Controle de versão com git (init, clone, add, commit, status, push, pull, remote)**

- [ ] **Git: Integração de mudanças entre ramos (branch, checkout, fetch, merge, reset, rebase, tag)**

- [ ] **GitHub: Criação de contas e repositórios, configuração de chave SSH**

- [ ] **GitHub: Implantação com GitHub Pages**

  <details><summary>Links</summary><p>

  * [Site oficial do GitHub Pages](https://pages.github.com/)
</p></details>

- [ ] **GitHub: Colaboração pelo Github (branches | forks | pull requests | code review | tags)**

- [ ] **GitHub: Organização pelo Github (projects | issues | labels | milestones | releases)**

### HTTP

- [ ] **Consulta ou solicitação (request) e resposta (response).**

  <details><summary>Links</summary><p>

  * [Visão geral do protocolo HTTP - MDN](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Overview)
  * [Mensagens HTTP - MDN](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Messages)
</p></details>

- [ ] **Cabeçalhos (headers)**

  <details><summary>Links</summary><p>

  * [Cabeçalhos HTTP - MDN](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Headers)
</p></details>

- [ ] **Corpo (body)**

  <details><summary>Links</summary><p>

  * [Mensagens HTTP / Corpo - MDN](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Messages#corpo)
</p></details>

- [ ] **Verbos HTTP**

  <details><summary>Links</summary><p>

  * [Métodos de requisição HTTP - MDN](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods)
</p></details>

- [ ] **Códigos de status de HTTP**

  <details><summary>Links</summary><p>

  * [Códigos de status de respostas HTTP - MDN](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Status)
  * [The Complete Guide to Status Codes for Meaningful ReST APIs - dev.to](https://dev.to/khaosdoctor/the-complete-guide-to-status-codes-for-meaningful-rest-apis-1-5c5)
</p></details>

- [ ] **Encodings e JSON**

  <details><summary>Links</summary><p>

  * [Introdução ao JSON - Documentação oficial](https://www.json.org/json-pt.html)
</p></details>

- [ ] **CORS (Cross-Origin Resource Sharing)**

  <details><summary>Links</summary><p>

  * [Cross-Origin Resource Sharing (CORS) - MDN](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/CORS)
</p></details>

### Angular

- [ ] **Components & templates**

  <details><summary>Links</summary><p>

  * [Angular Components Overview - Documentação oficial (em inglês)](https://angular.io/guide/component-overview)
  * [Introduction to components and templates - Documentação oficial (em inglês)](https://angular.io/guide/architecture-components#introduction-to-components)
</p></details>

- [ ] **Diretivas estruturais (ngIf / ngFor)**

  <details><summary>Links</summary><p>

  * [Writing structural directives - Documentação oficial (em inglês)](https://angular.io/guide/structural-directives)
</p></details>

- [ ] **@Input | @Output**

  <details><summary>Links</summary><p>

  * [Component interaction - Documentação oficial (em inglês)](https://angular.io/guide/component-interaction#component-interaction)
</p></details>

- [ ] **Criação e uso de serviços**

  <details><summary>Links</summary><p>

  * [Providing services - Documentação oficial (em inglês)](https://angular.io/guide/architecture-services#providing-services)
</p></details>

- [ ] **Gerenciamento de rotas**

  <details><summary>Links</summary><p>

  * [In-app navigation: routing to views - Documentação oficial (em inglês)](https://angular.io/guide/router)
</p></details>

- [ ] **Criação e uso de Observables**

  <details><summary>Links</summary><p>

  * [Observables in Angular - Documentação oficial (em inglês)](https://angular.io/guide/observables-in-angular)
</p></details>

- [ ] **Uso de HttpClient**

  <details><summary>Links</summary><p>

  * [Communicating with backend services using HTTP - Documentação oficial (em inglês)](https://angular.io/guide/http)
</p></details>

- [ ] **Estilos de componentes (ngStyle / ngClass)**

  <details><summary>Links</summary><p>

  * [Template syntax - Documentação oficial (em inglês)](https://angular.io/guide/template-syntax#built-in-directives)
</p></details>

### React

- [ ] **JSX**

  <details><summary>Links</summary><p>

  * [Introduzindo JSX - Documentação oficial](https://pt-br.react.dev/learn/writing-markup-with-jsx)
</p></details>

- [ ] **Componentes e propriedades (props)**

  <details><summary>Links</summary><p>

  * [Componentes e propriedades - Documentação oficial](https://pt-br.react.dev/learn/passing-props-to-a-component)
</p></details>

- [ ] **Manipulação de eventos**

  <details><summary>Links</summary><p>

  * [Manipulando eventos - Documentação oficial](https://pt-br.react.dev/learn/responding-to-events)
</p></details>

- [ ] **Listas e keys**

  <details><summary>Links</summary><p>

  * [Listas e chaves - Documentação oficial](https://pt-br.react.dev/learn/rendering-lists)
</p></details>

- [ ] **Renderização condicional**

  <details><summary>Links</summary><p>

  * [Renderização condicional - Documentação oficial](https://pt-br.react.dev/learn/conditional-rendering)
</p></details>

- [ ] **Elevação de estado**

  <details><summary>Links</summary><p>

  * [Elevação de estado - Documentação oficial](https://pt-br.react.dev/learn/sharing-state-between-components)
</p></details>

- [ ] **Hooks**

  <details><summary>Links</summary><p>

  * [Introduzindo Hooks - Documentação oficial](https://pt-br.react.dev/reference/react)
</p></details>

- [ ] **CSS modules**

  <details><summary>Links</summary><p>

  * [Adding a CSS Modules Stylesheet - Documentação de Create React App (em inglês)](https://vitejs.dev/guide/features.html#css-modules)
</p></details>

- [ ] **React Router**

  <details><summary>Links</summary><p>

  * [Quick Start - Documentação oficial (em inglês)](https://reactrouter.com/en/main/start/tutorial)
</p></details>

### Vue

- [ ] **Instância de Vue.js**

  <details><summary>Links</summary><p>

  * [A Instância Vue - Documentação oficial](https://br.vuejs.org/v2/guide/instance.html)
</p></details>

- [ ] **Dados e métodos**

  <details><summary>Links</summary><p>

  * [Dados e métodos - Documentação oficial](https://br.vuejs.org/v2/guide/instance.html#Dados-e-Metodos)
</p></details>

- [ ] **Uso e criação de componentes**

  <details><summary>Links</summary><p>

  * [Conceitos Básicos de Componentes - Documentação oficial](https://br.vuejs.org/v2/guide/components.html)
</p></details>

- [ ] **Props**

  <details><summary>Links</summary><p>

  * [Passando dados aos componentes filhos com Props - Documentação oficial](https://br.vuejs.org/v2/guide/components.html#Passando-Dados-aos-Filhos-com-Props)
</p></details>

- [ ] **Diretivas (v-bind | v-model)**

  <details><summary>Links</summary><p>

  * [v-bind - Documentação oficial](https://br.vuejs.org/v2/api/#v-bind)
  * [Binding/Interligações em Formulários - Documentação oficial](https://br.vuejs.org/v2/guide/forms.html)
</p></details>

- [ ] **Iteração (v-for)**

  <details><summary>Links</summary><p>

  * [Array em elementos com v-for - Documentação oficial](https://br.vuejs.org/v2/guide/list.html#Array-em-Elementos-com-v-for)
</p></details>

- [ ] **Eventos (v-on)**

  <details><summary>Links</summary><p>

  * [Manipulação de eventos - Documentação oficial](https://br.vuejs.org/v2/guide/events.html)
</p></details>

- [ ] **Dados Computados e Observadores**

  <details><summary>Links</summary><p>

  * [Dados Computados e Observadores](https://br.vuejs.org/v2/guide/computed.html)
</p></details>

- [ ] **Routing**

  <details><summary>Links</summary><p>

  * [Getting Started - Documentação oficial de Vue Router](https://router.vuejs.org/guide/#html)
</p></details>

- [ ] **Classes e Estilos**

  <details><summary>Links</summary><p>

  * [Interligações de Classe e Estilo - Documentação oficial](https://br.vuejs.org/v2/guide/class-and-style.html)
</p></details>

### typescript

- [ ] **Verificação estática de tipos**

  <details><summary>Links</summary><p>

  * [Documentação oficial do Typescript](https://www.typescriptlang.org/docs/handbook/2/basic-types.html#static-type-checking)
</p></details>

- [ ] **Rigor**

  <details><summary>Links</summary><p>

  * [Documentação oficial do Typescript 1](https://www.typescriptlang.org/docs/handbook/2/basic-types.html#strictness)
  * [Documentação oficial do Typescript 2](https://www.typescriptlang.org/tsconfig#Type_Checking_6248)
</p></details>

- [ ] **Tipos primitivos**

  <details><summary>Links</summary><p>

  * [Documentação oficial do Typescript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)
</p></details>

- [ ] **Arrays**

  <details><summary>Links</summary><p>

  * [Documentação oficial do Typescript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#arrays)
</p></details>

- [ ] **Tipo `any`**

  <details><summary>Links</summary><p>

  * [Documentação oficial do Typescript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#any)
</p></details>

- [ ] **Funções**

  <details><summary>Links</summary><p>

  * [Documentação oficial do Typescript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#functions)
  * [Documentação oficial do Typescript](https://www.typescriptlang.org/docs/handbook/2/functions.html)
</p></details>

- [ ] **Propriedades opcionais**

  <details><summary>Links</summary><p>

  * [Documentação oficial do Typescript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#optional-properties)
</p></details>

- [ ] **Tipos de união**

  <details><summary>Links</summary><p>

  * [Documentação oficial do Typescript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#union-types)
</p></details>

- [ ] **Alias de tipos**

  <details><summary>Links</summary><p>

  * [Documentação oficial do Typescript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#type-aliases)
</p></details>

- [ ] **Interfaces**

  <details><summary>Links</summary><p>

  * [Documentação oficial do Typescript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#interfaces)
</p></details>

- [ ] **Type assertions**

  <details><summary>Links</summary><p>

  * [Documentação oficial do Typescript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#type-assertions)
</p></details>

- [ ] **Tipos literais**

  <details><summary>Links</summary><p>

  * [Documentação oficial do Typescript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#literal-types)
</p></details>

- [ ] **basic-types/null-and-undefined**

- [ ] **Enums**

  <details><summary>Links</summary><p>

  * [Documentação oficial do Typescript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#enums)
</p></details>

- [ ] **Narrowing**

  <details><summary>Links</summary><p>

  * [Documentação oficial do Typescript](https://www.typescriptlang.org/docs/handbook/2/narrowing.html)
</p></details>

- [ ] **classes/members/fields**

- [ ] **classes/members/constructor**

- [ ] **classes/members/methods**

- [ ] **classes/members/getter-setters**

- [ ] **classes/class-heritage/implements**

- [ ] **classes/class-heritage/extends**

- [ ] **classes/member-visibility/public**

- [ ] **classes/member-visibility/protected**

- [ ] **classes/member-visibility/private**

- [ ] **Membros estáticos da classe**

  <details><summary>Links</summary><p>

  * [Documentação oficial do Typescript](https://www.typescriptlang.org/docs/handbook/2/classes.html#static-members)
</p></details>

- [ ] **this**

  <details><summary>Links</summary><p>

  * [Documentação oficial do Typescript](https://www.typescriptlang.org/docs/handbook/2/classes.html#this-at-runtime-in-classes)
</p></details>

- [ ] **Classes abstratas**

  <details><summary>Links</summary><p>

  * [Documentação oficial do Typescript](https://www.typescriptlang.org/docs/handbook/2/classes.html#abstract-classes-and-members)
</p></details>

- [ ] **Decoradores**

  <details><summary>Links</summary><p>

  * [Documentação oficial do Typescript](https://www.typescriptlang.org/docs/handbook/decorators.html)
</p></details>

### Centrado no usuário

- [ ] **Desenhar e desenvolver um produto ou serviço colocando as usuárias no centro**

### Design de produto

- [ ] **Criar protótipos para obter feedback e iterar**

- [ ] **Aplicar os princípios de desenho visual (contraste, alinhamento, hierarquia)**

### Pesquisa

- [ ] **Planejar e executar testes de usabilidade**

## 5. Critérios mínimos de aceitação do projeto

- Utilizar a _The Movie Database API V3_ ou _OMDB_ ou qualquer outra API
  através de _fetch_ para obter e mostrar uma interface baseada nos dados
  de cada resposta.
- Sua solução deve ser _responsiva_. Deve se adaptar a telas de desktop,
  tablets e celulares.
- Você deve implantar sua aplicação em qualquer serviço na nuvem.
  Algumas opções são [GitHub Pages](https://pages.github.com/)
  ou [Vercel](https://vercel.com/)
  ou [Netlify](https://www.netlify.com/)

## 6. Considerações técnicas

- Para poder usar a API do _The Movie Database API V3_ ou _OMDB_ você deverá criar
  uma chave (_key_) de acesso e adicioná-la em cada solicitação que fizer ao servidor.
  + Para _The Movie Database API V3_ você deverá criar uma conta e depois uma
    chave neste [link](https://www.themoviedb.org/settings/api).
  + Para _OMDB_ a chave é gerada neste
  [link](http://www.omdbapi.com/apikey.aspx) preenchendo o formulário com a
  versão gratuita (_free_) selecionada e depois verificando seu _e-mail_ para
  ativá-la e poder usá-la.
- Lembre-se que o GitHub Pages serve suas páginas com um certificado
  [SSL](https://pt.wikipedia.org/wiki/SSL) então as solicitações às APIs
  devem incluir `https` na URL.
- Lembre-se que você tem um máximo de 1.000 solicitações diárias às APIs por cada
  [IP](https://pt.wikipedia.org/wiki/Endere%C3%A7o_IP), acreditamos que seja
  suficiente, mas recomendamos que você faça um uso responsável deste recurso gratuito.

## Conteúdo de referência

- [Fetch API](https://developer.mozilla.org/pt-BR/docs/Web/API/Fetch_API)

Tente se divertir. Vamos começar esta aventura 🎬!
