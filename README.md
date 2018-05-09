# Procondutor: Analista de Qualidade de Software - Automação
Este é teste técnico para o cargo de QA Automatizador. O objetivo é avaliar a sua capacidade de solucionar problemas, portanto é importante que você faça esse teste sozinho. Não tenha medo de errar, não existem soluções iguais e perfeitas. Caso você tenha caído aqui por acaso sinta-se à vontade para resolver esse execício, ela é uma boa oportunidade de aprendizado!

# Instruções
O foco do teste é a automação e também um pouco de conhecimentos em teste de performance. Para iniciar crie um fork desse projeto e desenvolva sua solução. 

## Teste 1 - Automação WEB
Criar um framework de teste que:
1. Acessa uma página que gera dados fictícios de pessoas, como o https://www.fakenamegenerator.com/ e armazena suas informações pessoais
2. Com os dados armazenados, o cadastra no facebook ou gmail ou twitter (ou todos se quiser)
3. Validar o e-mail de confirmação de conta (pode ser utilizado um gerador de e-mail)
4. Acessar a conta, entrar no menu de configurações/segurança
5. Alterar a senha
6. Encerrar sessão
7. Logar com a nova senha
8. Utilizar Cucumber com java
9. Gerar um relatório de execução com evidências
10. Utilizar design pattern Page Object

## Teste 2 - Automação Mobile
Utilizar o teste anterior para rodar no navegador de um dispositivo móvel
1. Utilizar o http://appium.io/
2. Utilizar solução para android
3. Utilizar o Chrome

## Teste 3 - Script performance
Elaborar um script utilizando o Jmeter
1. Escolha uma das APIs de https://github.com/toddmotto/public-apis ou quaquer outra API pública
2. Criar um script no Jmeter "chamando" essa API
3. Validar o retorno da API
4. Realizar a leitura de parâmetros em um arquivo CSV

## O que será avaliado:
* Lógica de programação
* Capacidade de entendimento
* Organização do projeto
* BDD (Cucumber ) - Utilização, criação de features e sintaxe utilizando Gherkin
* Criação de scripts de performance pelo Jmeter (principais elementos, controladores, consumo de dados)
