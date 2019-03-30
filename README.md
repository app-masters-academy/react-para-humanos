# React para Humanos
Este repositório serve de suporte ao treinamento [React para Humanos](https://academy.appmasters.io/) da **App Masters Academy**. Apresentamos informaçòes iniciais para configuração do ambiente e inicio do projeto com React, bem como receberá todos links e conteúdos adicionais necessários ao longo do treinamento.

## Apresentação e projeto do treinamento
Cada turma terá um repositório com os códigos do projeto realizado em sala, para consulta quando necessário. O código apresentado pelo professor é atualizado em tempo real no repositório online.

- Quarta turma - Projeto: [Just Coders Network](https://github.com/app-masters-academy/just-coders-network) - Apresentação: [Google Presentation](https://docs.google.com/presentation/d/1SxDLvpLew6bQ_nmtRAqEdIvFlkp-clfXBUIqcW4EFAc/edit?usp=sharing)

# Preparação o ambiente

## Instalação do node
O primeiro passo é instalar o [node](https://www.taniarascia.com/how-to-install-and-use-node-js-and-npm-mac-and-windows/) em sua máquina, a versão LTS. Escolha entre [Windows](https://medium.com/@adsonrocha/como-instalar-o-node-js-no-windows-10-cf2bd460b8a8), [Linux](https://medium.com/collabcode/como-instalar-node-js-no-linux-corretamente-ubuntu-debian-elementary-os-729fb4c92f2d) e [Mac](https://receitasdecodigo.com.br/nodejs/instalacao-nodejs-no-mac). Ao final da instalação, ao executar `node -v` em seu terminal deverá ser apresentada a versão instalada.

## Criação de um projeto React

Uma vez que o node esteja instalado, você poderá criar seu primeiro projeto usando o [Create React App](https://github.com/facebook/create-react-app). Resumidamente você irá executar um comando para criar o projeto, algo como `npx create-react-app meu-projeto`, que fará download de tudo que o react precisa pra funcionar. Em seguida entrará na pasta do projeto `cd meu-projeto` e então inicializar o projeto `npm start`.

Neste moemento ele inicializará seu projeto e através do browser você poderá acessar-lo, normalmente por [http://localhost:3000/](http://localhost:3000/).  

Se isso acontecer, seu ambiente está pronto!

## Instalando a IDE

Será necessário uma IDE para se programar... sugerimos [VSCode](https://code.visualstudio.com/) ou [Web Storm](https://www.jetbrains.com/webstorm/).

Para nossos alunos oferecemos uma licença de três meses para uso do Web Storm. Nos diga se quiser experimentar, para lhe enviarmos a licença.

# Conteitos do React

Recentemente toda a [documentação do React](https://pt-br.reactjs.org/) foi traduzida para o português. É uma excelente fonte de informação e leitura recomendada. Existe inclusive um [tutorial](https://pt-br.reactjs.org/tutorial/tutorial.html) que passa pelas mesmas etapas que passaremos durante o treinamento.

## JSX e Renderização de elementos
- Documentação: [Introduzindo JSX](https://pt-br.reactjs.org/docs/introducing-jsx.html)
- Post: [JSX](https://braziljs.org/blog/jsx/)
- Post: [JSX, a resposta do React pra resolver definitivamente um problema](JSX, a resposta do React pra resolver definitivamente um problema)
- Documentação: [Renderizando Elementos](https://pt-br.reactjs.org/docs/rendering-elements.html)
- Post: [Renderização condicional em React](https://medium.com/reactbrasil/renderiza%C3%A7%C3%A3o-condicional-em-react-bb8c16dddd6f)

## Style
- Documentação: [Estilização e CSS](https://pt-br.reactjs.org/docs/faq-styling.html)
- Post: [Four ways to style react components](https://codeburst.io/4-four-ways-to-style-react-components-ac6f323da822)

## Lidando com props
Props podem ser entendidas como properties, propriedades, atributos ou parâmetros, que são passados de um elemento para o outro afim de mudar sua apresentação ou comportamento.

- Documentação: [Componentes e Props](https://pt-br.reactjs.org/docs/components-and-props.html) – Conteúdo essencial
- Post: [How to pass props to components in React](https://www.robinwieruch.de/react-pass-props-to-component/) – Explicação mais detalhadas e casos de uso

## States e ciclo de vida
É hora da aplicação interagir, reagir, mudar a interface, e isso acontece alterando o estado. Cada alteração no estado irá forçar o componente a renderizar novamente, apresentando assim a mudança esperada.

- Documentação: [State e Ciclo de Vida](https://pt-br.reactjs.org/docs/state-and-lifecycle.html) – Conteúdo essencial
- [Perguntas Frequentes](https://pt-br.reactjs.org/docs/faq-state.html)
- [Requisições ajax e o estado](https://pt-br.reactjs.org/docs/faq-ajax.html)

# É bom você saber
Ao programar para React você precisará, ao longo do tempo, lidar com várias metodologias, tecnologias e ferramentas. Por isso é bom você saber um pouco ao menos sobre coisas que estão ao redor do seu projeto e que farão ele ser ainda mais incrível!

## ES6
- Post: [O Guia do ES6: TUDO que você precisa saber](https://medium.com/@matheusml/o-guia-do-es6-tudo-que-voc%C3%AA-precisa-saber-8c287876325f)

## Arrow Function
- Post: [Arrow Functions — Declaração, funcionamento, escopos e o valor de this](https://medium.com/@raphalima8/arrow-functions-declara%C3%A7%C3%A3o-funcionamento-escopos-e-o-valor-de-this-9cb6449bca31)

## Flexbox
- Post: [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- Post: [Guia completo do Flexbox](https://origamid.com/projetos/flexbox-guia-completo/)
- Tutorial/Game: [Flexbox Froggy](https://flexboxfroggy.com/) - jogo para aprender a usar o flexbox

## Babel e Webpack
- Post: [Entendendo webpack e criando uma aplicação em React com ele](http://felipegalvao.com.br/blog/2017/03/29/entendendo-webpack-e-criando-uma-aplicacao-em-react-com-ele/)
- Ferramenta: [Experimente o Babel em tempo real](https://babeljs.io/repl/#?presets=react)
