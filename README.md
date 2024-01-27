# Projeto de Automação de Testes com Appium e Saucelabs

Este projeto faz parte do desafio final proposto pela escola Iterasys, turma 139. 
O desafio propõem criar um projeto utilizando o aplicativo MyDemoApp, onde o teste deve escolher o produto "Sauce Labs Backpack",adicionar 2 itens desse produto no carrinho e realizar as validações de Nome, preço e quantidade. 

## Pré-requisitos
-  Appium
- Saucelabs
- Ambiente de desenvolvimento configurado para C# e Appium
- Configuração do Ambiente
- Configuração do Saucelabs:
**OBS.** Certifique-se de ter uma conta no Saucelabs e obtenha suas credenciais de acesso (SAUCE_USERNAME e SAUCE_ACCESS_KEY).

## Configuração do Projeto: 

## Clone este repositório para o seu ambiente de desenvolvimento.

https://github.com/welitaluisa/MyDemoApp.git

## Configuração do Ambiente de Teste:

1. Certifique-se de ter o ambiente de teste configurado para C# e Appium.
2. Atualize as Credenciais do Saucelabs:
3. Substitua os valores de SAUCE_USERNAME e SAUCE_ACCESS_KEY no arquivo 
4. SelectProductMDA.cs com suas credenciais Saucelabs.

## Estrutura do Projeto
- SelectProductMDA.cs: Contém o script de automação de teste usando Appium e C#.
- mobile.tests.txt: Contém passo a passo detalhando para inicializar o projeto
- Pasta Evidencias: Contém as evidências dos testes no terminal e no saucelabs

*Após toda a configuração certinha só rodar o comando no terminal para executar os testes*

Comando:  dotnet test

** Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas ou enviar pull requests para melhorar este projeto.

