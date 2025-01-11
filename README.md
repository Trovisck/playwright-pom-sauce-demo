# playwright-pom-sauce-demo
Testes automatizados para o site Sauce Demo usando Playwright e o padrão Page Object Model (POM). Este repositório contém testes de ponta a ponta, incluindo login, navegação, validação de produtos e checkout.

# Sauce Demo - Testes Automatizados com Playwright e POM

Este repositório contém testes automatizados desenvolvidos com [Playwright](https://playwright.dev/) para o site [Sauce Demo](https://www.saucedemo.com/). Os testes seguem o padrão **Page Object Model (POM)** para facilitar a manutenção e a reutilização de código.

## ⚙️ Configuração

1. Clone o repositório:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
## 🧪 Execução dos Testes

- Para rodar todos os testes:
  ```bash
  npx playwright test
  ```
- Para abrir o relatório:
  ```bash
  npx playwright show-report
  ```
- Para rodar testes com interface gráfica:
  ```bash
  npx playwright test --headed
  ```

## 📂 Estrutura do Projeto

- **`pages/`**: Contém classes que representam as páginas da aplicação.
- **`tests/`**: Contém os arquivos de testes.
- **`playwright.config.js`**: Configuração do Playwright.

## 📋 Fluxo Testado
- Login com credenciais válidas.
- Navegação e validação de detalhes do produto.
- Adição ao carrinho.
- Finalização do checkout.

## 🚀 Tecnologias
- [Node.js](https://nodejs.org/)
- [Playwright](https://playwright.dev/)

## 📌 Notas
Este projeto foi desenvolvido como parte de um teste para avaliação de automação de QA.
