Teste de API Advantage Online Shopping
Visão Geral

Este projeto contém testes automatizados para as APIs do Advantage Online Shopping, que envolvem:

Buscar produtos

Atualizar a imagem de um produto

As implementações são fornecidas tanto em Java (usando Cucumber e REST-assured) quanto em JavaScript (usando Cucumber.js e Axios).

Pré-requisitos
Antes de começar, certifique-se de que você tem as seguintes ferramentas instaladas:

Para Java
Java JDK 8+

Maven

IntelliJ IDEA (ou qualquer IDE de sua preferência)

Para JavaScript
Node.js

NPM

Visual Studio Code (ou qualquer editor de texto de sua preferência)

Configuração do Ambiente
Java
Clone o Repositório:

sh
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
Instale as Dependências: No diretório do projeto, execute:

sh
mvn install
Estrutura do Projeto: Certifique-se de que o pom.xml está configurado com as dependências necessárias para o Cucumber e REST-assured.

Executar os Testes: Para executar os testes, utilize o seguinte comando no terminal:

sh
mvn test
JavaScript
Clone o Repositório:

sh
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
Instale as Dependências: No diretório do projeto, execute:

sh
npm install
Estrutura do Projeto: Certifique-se de que o package.json inclui as dependências do Cucumber.js e Axios.

Executar os Testes: Para executar os testes, utilize o seguinte comando no terminal:

sh
npx cucumber-js
Cenários de Teste
Busca de Produto
gherkin
Feature: Buscar Produto

  Scenario: Procurar por um produto existente
    Given que o usuário deseja buscar um produto chamado "Notebook"
    When o usuário faz uma requisição GET para a API de busca de produtos
    Then a resposta deve conter o produto com o nome "Notebook"
    And o status da resposta deve ser 200
Atualização de Imagem de Produto
gherkin

Autor 
Lucas Rocha Alcici - https://www.linkedin.com/in/lucas-rocha-60a7a119b/
  
