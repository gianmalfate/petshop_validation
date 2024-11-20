# Doguito Petshop - Validação de Formulários

Bem-vindo ao repositório do **Doguito Petshop**! Este projeto foi desenvolvido durante um curso sobre validação de formulários. Ele simula um sistema de cadastro de clientes e produtos para um petshop, com validação dinâmica de campos e interação com o usuário.

---

## 📋 Funcionalidades

- **Cadastro de clientes** com validação de:
  - Nome, email e senha.
  - CPF e data de nascimento (somente maiores de 18 anos).
  - Endereço (CEP, logradouro, cidade e estado com preenchimento automático via API).

- **Cadastro de produtos**, incluindo:
  - Nome do produto.
  - Preço com máscara monetária.
  - Descrição opcional.

- Mensagens de erro dinâmicas exibidas diretamente nos campos.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**:
  - Validação customizada.
  - Máscara para campos de preço com [Simple Mask Money](https://github.com/codermarcos/simple-mask-money).

---

## 🚀 Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/doguito-petshop.git
2. Abra o arquivo `cadastro.html` ou `cadastro_produto.html` no navegador para acessar as telas de cadastro.

## 🧑‍💻 Estrutura do Projeto

-   `cadastro.html`: Formulário de cadastro de clientes.
-   `cadastro_concluido.html`: Tela de sucesso do cadastro de clientes.
-   `cadastro_produto.html`: Formulário de cadastro de produtos.
-   `cadastro_produto_concluido.html`: Tela de sucesso do cadastro de produtos.
-   `app.js`: Script principal para interações.
-   `validacao.js`: Validações customizadas para os formulários.

----------

## 👩‍💻 Autor

Desenvolvido por [Giancarlo Malfate](https://github.com/gianmalfate). Feedbacks são bem-vindos!
