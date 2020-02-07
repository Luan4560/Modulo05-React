## Aula 2

#Roteamento

1 - yarn add react-router-dom (pode chamar mais de uma rota ao mesmo tempo)

2 - Criar arquivo par gerenciar as rotas ( routes.ks)

3 - Criar pasta com as paginas da aplicação

4 - Importar no arquivo de rotas
{BrowserRouter, Switch, Route }from'react-router-dom'

5 - Criar componente de rotas

6 - Importar as paginas dentro do arquivo de rotas

7 - passar BrowserRouter por volta do Switch

8 - passar o Switch no componente : Switch é responsável por garantir que cada rota seja chamada por momento

9 - Passar <Route path="/caminhodapagina" component={ComponenteChamado} />
Path = caminho da URL
component = Componente chamado pela URL

10 - Com o passo 9 feito, importe o arquivo de rotas
no App.js e passe a tage <Routes/> para dentro do componente (Não esquecer de passar o exact para a rota principal)
