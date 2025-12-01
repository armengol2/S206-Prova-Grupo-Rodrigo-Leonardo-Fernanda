# Prova – Testes com Cypress

Este projeto contém os testes Feitos para a prova de Qualidade de Software(CYPRESS).  
Os testes foram feitos utilizando **Cypress** e o relatório final é gerado automaticamente em **HTML** usando *cypress-mochawesome-reporter*.
---
```
## Estruturas principais do Projeto
Prova_EX1/
│
├── 📂 cypress/
│   ├── 📂 e2e/
│   │   ├── 🔹 teste1.cy.js    # Código do teste 1
│   │   ├── 🔹 teste2.cy.js    # Código do teste 2
│   │   └── 🔹 teste3.cy.js    # Código do teste 3
│   │
│   ├── 📂 fixtures/           # Exemplos de JSON para testes
│   │
│   ├── 📂 reports/
│   │   ├── 📂 assets/         # Configurações do HTML
│   │   ├── 📂 screenshots/    # Prints dos testes inválidos
│   │   └── 🌐 index.html      # Relatório HTML gerado
│   │
│   └── 📂 support/
│       ├── 🔧 commands.js     # Comandos customizados do Cypress
│       ├── 🔧 e2e.js          # Importação de comandos
│       └── 🔧 Utils.js        # Classe com funções da URL
│
├── ⚙️ cypress.config.js       # Configuração principal do Cypress e reporter
├── 📦 package.json           # Scripts e dependências do projeto
├── 🔒 package-lock.json      # Define versões exatas de todos os pacotes
└── 📖 README.md             # Documentação do trabalho
## Configurações Principais
```

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


