
#  Markdown



## 1 - React como tecnologia🔍

### 1.1 - Índice de capítulo

- 1.1 - Índice de capítulo
- 1.2 - O que é React?
- 1.3 - Como funciona o React?

### 1.2 - O que é React?

React JS é uma biblioteca JavaScript para a criação de interfaces de usuário — ou UI (user interface).

Criado em 2011 pelo time do Facebook, o React surgiu com o objetivo de otimizar a atualização e a sincronização de atividades simultâneas no feed de notícias da rede social, entre eles chat, status, listagem de contatos e outros.

A princípio, todas essas atividades, chamadas de estados, tinham uma descrição muito complexa. Com o React, esta descrição torna-se mais simples, bem como também é simplificada a conexão entre HTML, CSS e JavaScript e todos os componentes de uma página.

Por ter demonstrado grande eficiência, nos anos que se seguiram o React foi incorporado à interface de outras redes sociais do grupo, como o Instagram e, em 2013, seu código foi aberto à comunidade, dando início a sua popularização.

Hoje, o React é uma das mais prestigiadas bibliotecas de JavaScript do mercado.

### 1.3 - Como funciona o React?

O React é uma biblioteca front-end e tem como um de seus objetivos facilitar a conexão entre diferentes partes de uma página, portanto seu funcionamento acontece através do que chamamos de componentes.

Em outras palavras, podemos imaginar que o React divide uma tela em diversos componentes para, então, trabalhar sobre eles de maneira individual.

Os componentes são utilizados para reaproveitamento de código e padronização de interface.

Isso torna o React uma tecnologia muito flexível para a solução de problemas e para a construção de interfaces reutilizáveis, uma vez que cada um destes componentes pode ser manipulado de maneira distinta.

[Kenzie sobre React](https://kenzie.com.br/blog/react/)

## 2 O que é JSX? 

    Para responder o que é JSX primeiro precisamos olhar para como Javascript puro é escrito e aplicado aos elementos. Por natureza, a organização, estilo e lógica das aplicações feitas em Javascript são feitas de forma separada o que muitas vezes não faz sentido uma vez que, em teoria, uma aplicação juntaria essas peças para interagirem umas com as outras depois de criadas.

    JSX é uma extensão de sintaxe para Javascript, adicionando elementos que são muito similares ao HTML permitindo ao programador facilitar essa intereção entre diferentes elementos.

## 3 - Criando um projeto React

### 3.1 - Índice de capítulo

- 3.1 - Índice de capítulo
- 3.2 - Como funciona o React?

### 3.2 - Maneira fácil de criar um projeto DEMO

Podemos adicionar React a um projeto através de CDNs, duas delas sendo depências React e uma delas sendo o compilador Babel para compilar o código em HTML-CSS-Javascript.


Adicionando react:
````
<script crossorigin src="https://unpkg.com/react@18/umd/react.development.js"></script>
<script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
````

Para que o babel seja utilizado devemos adicionar em nossa tag script o **type="text/babel"**.

```
<script src="meuJavascript.js" type="text/babel"></script>
```

### 3.2 - Aplicativo local (create-react-app)

Para criar um aplicativo local React podemos usar, dentro do diretório que o projeto será criado, o comando **create-react-app** diretamente no **cmd**.

A sintaxe padrão é **create-react-app** **minhaNovaAplicação**.

````
create-react-app novaAplicação
````

## 4 - Renderizando elementos HTML em react

A renderização de elementos HTML em react é feita através de uma função chamada ReactDOM.render. Esta função tem 2 parâmetros, o primeiro sendo o elemento HTML e o segundo sendo onde este elemento será inserido.

````
reactDOM.render(<h1>Hello, world!</h1>, document.getElementById("root"))
````

Esta função cria um elemento HTML H1, com o innerHTML "Hello, world!" e acrescenta ele ao elemento de id "root".

## 5 - Componentes

### 5.1 - Resumo

### 5.2 - O que são?

Componentes são partes modulares e reutilizáveis do código. Cada componente é único dentro do código e executa funções diferentes da UI. Sua grande vantagem é que são reutilizaveis em toda a aplicação.

Dentro de uma aplicação é muito comum que tenhamos um componente para o **Header**, outro para o **Body** e mais um para o **Footer**. Outro fator interessante é que não apenas esses componentes vão estar na aplicação, mas cada componente pode ser **filho** ou **pai** de outro componente.

Normalmente dentro do react, todos os componentes são filhos de **App**, que vai comportar todos os outros.

    &rarr; Header
                &rarr;  InfoBlock1
App &rarr; Body &rarr;  InfoBlock2
                &rarr;  InfoBlock3
    &rarr; Footer


Para fins organizatórios, é indicado criar uma pasta para estes componentes novos que serão criados. Por convenção essa pasta tem o nome de **Components**.

### 5.2 - Como funcionam?

Um componente, dentro do React, é tratado como parte







