# empresa-test

Este projeto é um sistema de cadastro de funcionários desenvolvido em HTML, CSS e JavaScript. O sistema realiza validações de campos do formulário e executa testes automatizados utilizando um framework de testes próprio.

As principais funcionalidades do sistema incluem:

Validação de nome completo, RG, CPF, data de nascimento, e-mail, telefone, cargo, salário, data de admissão, endereço, CEP e número de dependentes.

Execução de testes automatizados no navegador por meio do arquivo tests.js.

Execução de testes automatizados via terminal com Node.js utilizando o arquivo testCLI.js.

Implementação de funções de validação individuais para cada campo, com uso de expressões regulares e regras de negócios.

Mensagens de erro são exibidas caso o campo esteja inválido.

O framework de testes próprio possui métodos como test, assertTrue, assertFalse, assertMatchesRegex e assertGreaterThan.

Para rodar os testes no navegador, basta abrir o arquivo index.html no navegador. Os resultados aparecerão no console.

Para rodar os testes no terminal usando Node.js, execute o comando:

node testCLI.js

O projeto é modular, e os testes podem ser expandidos conforme novas funcionalidades forem adicionadas.
