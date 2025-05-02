# 💻 Desafio DIO: Configuração de Instância de Banco de Dados no Microsoft Azure

Este repositório foi criado como parte do desafio da DIO para praticar a configuração de uma instância de banco de dados na plataforma Microsoft Azure. O objetivo é documentar o processo, reunir dicas e anotações relevantes, além de criar um material de apoio para estudos e futuras implementações.

---

## 📚 Conteúdo

- [Objetivo](#objetivo)
- [Pré-requisitos](#pré-requisitos)
- [Passo a Passo](#passo-a-passo)
- [Dicas Úteis](#dicas-úteis)
- [Referências](#referências)

---

---

## 📌 Referências

- [Documentação Oficial - Criar Instância Gerenciada SQL](https://learn.microsoft.com/pt-br/azure/azure-sql/database/sql-database-paas-overview)
- [Guia de Markdown GitHub](https://guides.github.com/features/mastering-markdown/)
- [Formação GitHub Certification (GitBook)](https://dio.me/github-certification)

---

## 🎯 Objetivo

Aplicar, na prática, os conhecimentos adquiridos durante as aulas da DIO para:

- Criar uma instância gerenciada de banco de dados SQL no Azure;
- Compreender as principais opções de configuração;
- Documentar o processo técnico de forma clara e estruturada;
- Utilizar o GitHub como ferramenta de compartilhamento técnico.

---

## 🧰 Pré-requisitos

Antes de iniciar, certifique-se de ter:

- Conta ativa no [Microsoft Azure](https://portal.azure.com/)
- Conta no [GitHub](https://github.com/)

---

## 🔧 Passo a Passo

### 1. Acessar o Portal do Azure
- Navegue até [portal.azure.com](https://portal.azure.com)
- Faça login com sua conta Microsoft

### 2. Criar uma Instância Gerenciada de Banco de Dados SQL
- No menu lateral, clique em **"Criar um recurso"**
- Selecione **Banco de Dados > SQL Database**
- Preencha os campos necessários (nome, grupo de recursos, servidor etc.)
- Escolha a camada de desempenho conforme seu caso de uso

### 3. Configurar o Servidor
- Criar novo servidor ou reutilizar um existente
- Definir login e senha de administrador
- Selecionar localização geográfica

### 4. Regras de Firewall
- Liberar o IP local para acessar o banco externamente
- Configurar redes virtuais se necessário

### 5. Testar Conexão
- Utilizar ferramentas como **SQL Server Management Studio (SSMS)** ou **Azure Data Studio**
- Conectar com os dados fornecidos (nome do servidor, login, senha)

---

## 💡 Dicas Úteis

- Utilize a opção **Camada Gratuita** para evitar custos durante os testes
- Ative o **firewall apenas para o seu IP público** para mais segurança
- Crie **scripts de backup e restore** no SQL Server para testar funcionalidades avançadas
- Utilize tags nos recursos do Azure para organização e controle de custos

---
---

## 📌 Referências

- [Documentação Oficial - Criar Instância Gerenciada SQL](https://learn.microsoft.com/pt-br/azure/azure-sql/database/sql-database-paas-overview)
- [Guia de Markdown GitHub](https://guides.github.com/features/mastering-markdown/)
- [Formação GitHub Certification (GitBook)](https://dio.me/github-certification)

---


