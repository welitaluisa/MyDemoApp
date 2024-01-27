* Projeto de Automação de Testes com Appium e Saucelabs

Este projeto faz parte do desafio final proposto pela escola Iterasys, turma 139. 
O desafio propõem criar um projeto utilizando o aplicativo MyDemoApp, e nele crie um teste que adiciona 2 "Sauce Labs Backpack" no carrinho e que faça a validação do nome, preço e quantidade no carrinho.

O teste seleciona um produto na loja, adiciona itens e itens desse produto selecionado no carrinho e validando o preço total e quantidade de itens.

** Pré-requisitos
. Appium
. Saucelabs
. Ambiente de desenvolvimento configurado para C# e Appium
. Configuração do Ambiente
. Configuração do Saucelabs:
OBS. Certifique-se de ter uma conta no Saucelabs e obtenha suas credenciais de acesso (SAUCE_USERNAME e SAUCE_ACCESS_KEY).

** Configuração do Projeto: 

Clone este repositório para o seu ambiente de desenvolvimento.
Configuração do Ambiente de Teste:

Certifique-se de ter o ambiente de teste configurado para C# e Appium.
Atualize as Credenciais do Saucelabs:

Substitua os valores de SAUCE_USERNAME e SAUCE_ACCESS_KEY no arquivo SelectProductMDA.cs com suas credenciais Saucelabs.
Execução do Teste:  dotnet test

** Estrutura do Projeto
SelectProductMDA.cs: Contém o script de automação de teste usando Appium e C#.
mobile.tests.txt: Contém passo a passo detalhando para inicializar o projeto
Pasta Evidencias: Contém as evidências dos testes no terminal e no saucelabs

** Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas ou enviar pull requests para melhorar este projeto.
