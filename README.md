# Sauce Demo - Testes Automatizados com Playwright e POM

Este repositório contém testes automatizados desenvolvidos com [Playwright](https://playwright.dev/) para o site [Sauce Demo](https://www.saucedemo.com/). Os testes seguem o padrão **Page Object Model (POM)** para facilitar a manutenção e a reutilização de código.

---

## **Pré-requisitos**

Antes de iniciar, garanta que você possui os seguintes itens instalados no seu ambiente:

- [Node.js](https://nodejs.org/) (versão 16 ou superior).
- Um editor de código, como o [Visual Studio Code](https://code.visualstudio.com/).

---

## **Passo 1: Clonar o Repositório**

1. Abra o terminal no seu computador.
2. Navegue até o diretório onde deseja salvar o projeto.
3. Execute o comando abaixo para clonar o repositório:
   ```bash
   git clone https://github.com/Trovisck/playwright-pom-sauce-demo.git
   
4. Após o download, entre na pasta do projeto:
   ```bash
   cd playwright-pom-sauce-demo
   ```
   Ou acesse a pasta do projeto pelo Visual Studio Code e abra o terminal
---

## **Passo 2: Instalar as Dependências**

1. Certifique-se de estar na raiz do projeto.
2. Execute o comando abaixo para instalar todas as dependências do projeto:
   ```bash
   npm install

---

## **🧪 Execução dos Testes**

- Para rodar todos os testes:
   ```bash
   npx playwright test

- Para abrir o relatório:
   ```bash
   npx playwright show-report

- Para rodar testes com interface gráfica:
   ```bash
   npx playwright test --headed

---

## 📂 Estrutura do Projeto

- **`pages/`**: Contém classes que representam as páginas da aplicação.
- **`tests/`**: Contém os arquivos de testes.
- **`playwright.config.js`**: Configuração do Playwright.

---

## 📋 Fluxo Testado

- Login com credenciais válidas.
- Navegação e validação de detalhes do produto.
- Adição ao carrinho.
- Finalização do checkout.

---

## 🚀 Tecnologias

- [Node.js](https://nodejs.org/)
- [Playwright](https://playwright.dev/)

---

## 📌 Notas

Este projeto foi desenvolvido como parte de um teste para avaliação de automação de QA.

