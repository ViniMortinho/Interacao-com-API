# LojaGames

Este projeto foi criado para o módulo de interação com APIs do curso Full Stack do SENAI. 

##Foi desenvolvido usando a versão 

Angular 15.0.4 
Node.js v18.18.0.

## Configuração do Ambiente de Desenvolvimento

Primeiro, instale as dependências do projeto executando `npm install` no diretório raiz do projeto. Este projeto foi desenvolvido usando a versão v18.17.1 do Node.js.

Para iniciar o servidor de desenvolvimento, execute `ng serve`. Depois disso, você pode acessar o aplicativo em seu navegador de preferência no endereço `http://localhost:4200/`. Qualquer alteração feita nos arquivos de origem resultará no recarregamento automático do aplicativo.

## Configuração das Dependências

Crie um arquivo com a extensão `.json` (por exemplo, `dbgames.json`). Este arquivo deve conter uma constante com cinco atributos que podem ser replicados dentro do projeto.

## Execução do Projeto

Para simular um banco de dados, instale o json-server globalmente com o comando `npm install -g json-server`. Em seguida, inicie o servidor de teste com `json-server –watch dbgames.json`. Isso criará uma porta para o seu arquivo `dbgames.json` no endereço `http://localhost:3000/produtos`.

## Testes Unitários

Para executar os testes unitários, use o comando `ng test`. Os testes serão executados através do Karma.

## Testes End-to-End

Para executar os testes end-to-end, use o comando `ng e2e`. Para usar este comando, primeiro você precisa adicionar um pacote que implemente recursos de teste end-to-end.

## Ajuda Adicional

Se precisar de mais ajuda com o Angular CLI, use `ng help` ou visite a página Visão geral do Angular CLI e referência de comandos.
