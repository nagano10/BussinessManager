# 🧾 Sistema de Gestão de Negócio

Projeto pessoal desenvolvido com o objetivo de organizar e controlar um pequeno negócio de forma prática e eficiente, utilizando tecnologias modernas e escaláveis.

---

## 📌 Objetivo

Criar um sistema completo para controle de:

- Compras de insumos
- Vendas de produtos
- Cálculo de lucro (por produto e mensal)
- Acompanhamento de desempenho mensal
- Filtros e relatórios por datas
- Controle de custo por produto com base em ingredientes
- Histórico de preço médio dos insumos
- Autenticação de usuários com segurança
- Estrutura preparada para integração com frontend (futuramente)

---

## 📂 Estrutura Inicial

- **Backend em .NET 9 com ASP.NET Core**
- **Arquitetura limpa (Clean Architecture)**
- **Autenticação com JWT**
- **SQL Server como banco de dados**
- **Entity Framework Core**
- **AutoMapper**
- **Swagger para testes da API**
- **Pronto para deploy futuro**

---

## 📋 Funcionalidades Previstas

### 🧮 Controle Financeiro
- Registrar investimento inicial
- Adicionar compras (com valor, data e itens)
- Adicionar vendas (com valor de venda, data, produto)
- Cálculo automático de lucro
- Cálculo de fechamento mensal

### 🛒 Compras e Ingredientes
- Cadastro de ingredientes
- Registro de compras com preço e data
- Histórico de preço médio de cada ingrediente

### 🧁 Produtos
- Cadastro de produtos
- Informar quais ingredientes são usados e em que quantidade
- Cálculo do custo por produto com base nos ingredientes
- Apuração do lucro bruto por unidade vendida

### 📊 Relatórios
- Filtros por período (mês, semana, dia)
- Visualização de lucros, despesas, investimento, vendas e compras

### 🔐 Autenticação
- Cadastro e login de usuários
- Proteção de rotas sensíveis com JWT

---

## 🧪 Tecnologias

- C# / .NET 9
- ASP.NET Core Web API
- SQL Server
- Entity Framework Core
- AutoMapper
- JWT Authentication
- Swagger
- GitHub

---

## 🚀 Etapas Atuais

- [x] Planejamento e levantamento de requisitos
- [ ] Criação da estrutura do projeto
- [ ] Configuração do banco de dados
- [ ] Implementação das primeiras funcionalidades (Investimento, Compras, Vendas)
- [ ] Autenticação de usuários
- [ ] Testes da API
- [ ] Integração com frontend (futuro)
