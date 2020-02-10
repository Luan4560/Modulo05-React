# Aula 2

## Roteamento

1 - yarn add react-router-dom (pode chamar mais de uma rota ao mesmo tempo).

2 - Criar arquivo para gerenciar as rotas ( routes.ks).

3 - Criar pasta com as paginas da aplicação.

4 - Importar no arquivo de rotas
{BrowserRouter, Switch, Route }from'react-router-dom'.

5 - Criar componente de rotas.

6 - Importar as paginas dentro do arquivo de rotas.

7 - passar BrowserRouter por volta do Switch.

8 - passar o Switch no componente : Switch é responsável por garantir que cada rota seja chamada. por momento.

9 - Passar <Route path="/caminhodapagina" component={ComponenteChamado} />
Path = caminho da URL
component = Componente chamado pela URL.

10 - Com o passo 9 feito, importe o arquivo de rotas
no App.js e passe a tage <Routes/> para dentro do componente (Não esquecer de passar o exact para a rota principal).

# Aula 4

## styled-component

1 - yarn add styled-components

2 - importar style de 'styled-components' no index de estilização e dar um export default no estilo

3 - importart index de estilo no component

4 - podemos passar funções em elementos do styled-components usando as props.

5 - E usamos o encadeamento no css para estilizar elementos filho do elemento pai.

# Aula 5

## Estilos Globais.

1 - Criar pasta na raiz do projeto com o nome styles.

2 - Criar arquivo de estilização global dentro da pasta, nome sugerido global.js.

3 - Dentro do arquivo global.js importar propriedade do styled-components chamada createGlobalStyle.

4 - export default createGlobalStyle``;

5 - configuração sugerida

- {
  margin: 0;
  padding: 0;
  outline: 0;
  box-sizing: border-box;
  }

html, body, #root {
min-heigth: 100;
}

body {
background: 'cordepreferencia';
-webkit-font-smoothing: antialiased !important;
}

body, input, button {
color: "cordepreferencia"
font-size: 14px;
font-family: "depreferencia"
}

button {
cursor: pointer;
}

6 - Importar GlobalStyle no App e passar para aplicação <GlobalStyle />
