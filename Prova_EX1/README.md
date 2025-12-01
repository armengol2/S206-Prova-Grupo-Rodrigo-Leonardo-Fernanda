# Prova – Testes com Cypress

Este projeto contém os testes automatizados desenvolvidos para a prova prática de Qualidade de Software.  
Os testes foram feitos utilizando **Cypress** e o relatório final é gerado automaticamente em **HTML** usando *cypress-mochawesome-reporter*.
---

## Estruturas principais do Projeto

├── cypress/
│ ├── e2e/
│ │ └── teste1.cy.js -> **código do teste 1**
| | └── teste2.cy.js -> **código do teste 2**
| | └── teste3.cy.js -> **código do teste 3**
│ ├── fixture/ -> exemplo de JSON
│ ├── reports/
| | └── assets/ -> Configurações do HTML
| | └── Screenshots/ -> Prints dos testes inválidos
| | └── index.html -> **Relatório HTML**
│ └── support/
| | └── commands.js -> Detalha comandos
| | └── e2e.js -> Importar comandos
| | └── Utils.js -> **Classe da função da URL**
│ └── Node/ -> Pacotes instalados para o node.js
├── cypress.config.js -> configuração principal do Cypress e reporter
├── package-lock.json → definir versões exatas de todos os pacotes
├── package.json → scripts e dependências do projeto
└── README.md -> Documentação do trabalho

## Configurações Principais

### **cypress.config.js**
Contém:
- integração do `cypress-mochawesome-reporter`
- configuração do `after:run` para gerar o relatório automaticamente
- definição do `baseUrl`
- task de exemplo usada nos testes

### **package.json**
Inclui:
- dependências do Cypress e mochawesome
- scripts NPM
- suporte para rodar os testes e gerar relatório automaticamente