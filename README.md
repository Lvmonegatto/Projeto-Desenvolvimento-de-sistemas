# 💻 FastDeliveryInformatic

Sistema desenvolvido em linguagem **C** com o objetivo de simular uma plataforma de gerenciamento de pedidos, produtos e usuários para uma empresa fictícia de tecnologia.

O projeto foi criado com foco em:

- Programação estruturada
- Modularização
- Manipulação de arquivos
- Organização de código
- Persistência de dados

---

## 📌 Sobre o Projeto

O sistema FastDeliveryInformatic funciona como uma simulação simplificada de uma loja virtual de informática, permitindo que usuários realizem login, busquem produtos e gerenciem pedidos.

Os dados são armazenados em arquivos `.txt`, simulando um banco de dados simples e garantindo persistência das informações mesmo após o encerramento do programa.

---

## 🚀 Funcionalidades

### 👤 Usuários
- Cadastro de usuários
- Login
- Controle de autenticação

### 🛒 Produtos
- Listagem de produtos
- Busca por produtos
- Visualização de preços

### 📦 Pedidos
- Criar pedidos
- Editar pedidos
- Excluir pedidos
- Adicionar produtos
- Remover produtos
- Listar pedidos do usuário

### ⭐ Avaliação
- Avaliação de pedidos
- Sistema de notas de 0 a 5 estrelas

---

## 🛠️ Tecnologias Utilizadas

- Linguagem C
- Programação Estruturada
- Manipulação de arquivos `.txt`

---

## 📂 Estrutura do Projeto

```txt
projeto/
│
├── main.c
├── usuarios.c
├── usuarios.h
├── produtos.c
├── produtos.h
├── pedidos.c
├── pedidos.h
│
├── usuarios.txt
├── produtos.txt
├── pedidos.txt
│
├── Relatorio_projeto desenvolvimento.pdf
│
└── README.md
```

---

## ▶️ Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/seuusuario/seuprojeto.git
```

### 2. Acesse a pasta do projeto

```bash
cd seuprojeto
```

### 3. Compile o projeto

```bash
gcc main.c usuarios.c produtos.c pedidos.c -o sistema
```

### 4. Execute o programa

```bash
./sistema
```

---

## 📋 Menu Principal

O sistema possui um menu interativo com opções como:

```txt
1 - Cadastrar usuário
2 - Login
3 - Buscar produto
4 - Listar produtos
5 - Gerenciar pedidos
6 - Avaliar pedido
0 - Sair
```

---

## 🧠 Conceitos Trabalhados

Durante o desenvolvimento foram aplicados conceitos como:

- Programação estruturada
- Modularização em arquivos `.c` e `.h`
- Estruturas (`struct`)
- Manipulação de arquivos
- CRUD
- Persistência de dados
- Menus interativos
- Controle de fluxo
- Funções
- Organização de projetos em C

---

## 📦 Gerenciamento de Pedidos

O módulo de pedidos permite:

- Criar pedidos
- Editar informações
- Excluir pedidos
- Adicionar produtos
- Remover produtos
- Listar histórico de pedidos

Cada pedido fica associado ao usuário logado, garantindo um histórico individual de compras.

---

## ⭐ Sistema de Avaliação

Após finalizar um pedido, o usuário pode atribuir uma nota de:

```txt
0 a 5 estrelas
```

A avaliação é salva no arquivo de pedidos, simulando sistemas de feedback encontrados em plataformas de e-commerce.

---

## 💾 Persistência de Dados

As informações são armazenadas em arquivos `.txt`, como:

- usuarios.txt
- produtos.txt
- pedidos.txt

Isso permite que os dados permaneçam salvos mesmo após o fechamento do programa.

---

## 📚 Aprendizados

Esse projeto permitiu praticar:

- Estruturação de sistemas maiores em C
- Separação de responsabilidades
- Manipulação de dados persistentes
- Simulação de sistemas reais de e-commerce
- Organização de menus e funcionalidades

---

## 🚀 Melhorias Futuras

- Interface gráfica
- Banco de dados real
- Criptografia de senhas
- Sistema de estoque
- Carrinho de compras
- Relatórios administrativos
- Sistema de pagamentos
- Cadastro de categorias
- Controle de entregas

---

## 👨‍💻 Autor

**Luciano Ventura Monegatto**  
Estudante de Ciência da Computação
