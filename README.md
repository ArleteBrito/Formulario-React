# 📝 Formulários em React

Este projeto demonstra dois tipos de formulários de cadastro criados com **React**:

- Um formulário com **validações manuais** usando `useState` e `lodash`
- Um formulário com **validações automáticas** usando a biblioteca `react-hook-form` e a biblioteca `validator` para validação de e-mails

---

## 📦 Tecnologias Utilizadas

- [React](https://reactjs.org/)
- [React Hook Form](https://react-hook-form.com/)
- [Validator.js](https://github.com/validatorjs/validator.js)
- [Lodash](https://lodash.com/)
- HTML5 + CSS3

---

## ✨ Funcionalidades

### ✅ `GoodForm` (usando `react-hook-form`)

- Validações automáticas com feedback em tempo real
- Verificação de:
  - Campos obrigatórios
  - E-mail válido
  - Senha mínima de 7 caracteres
  - Confirmação de senha
  - Seleção de profissão
  - Aceite dos termos de privacidade

### ⚠️ `BadForm` (validação manual)

- Validações feitas "na mão" com `useState`
- Demonstra a complexidade e risco de erros ao comparar com o `GoodForm`

---

## 📁 Estrutura do Projeto

src/
├── App.jsx # Componente principal com renderização dos formulários
├── BadForm.jsx # Formulário com validação manual
├── GoodForm.jsx # Formulário com react-hook-form
├── index.js # Ponto de entrada da aplicação
├── reportWebVitals.js # Relatórios de performance (CRA)
└── styles.css # Estilo dos formulários

---

## 🚀 Como Rodar o Projeto

1. Clone o repositório:

git clone https://github.com/seu-usuario/react-forms-examples.git

2. Clone o repositório:

npm install

3. Rode o projeto localmente:
npm start