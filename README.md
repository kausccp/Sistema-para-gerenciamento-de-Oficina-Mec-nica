# 🔧 Sistema de Oficina Mecânica

Sistema web desenvolvido para auxiliar no gerenciamento de uma oficina mecânica, facilitando a organização de clientes, veículos e agendamentos de serviços. A aplicação busca centralizar as informações e tornar a administração dos atendimentos mais prática e eficiente.

## 📌 Funcionalidades

- 🔐 Autenticação de usuários.
- 👥 Cadastro e gerenciamento de clientes.
- 🚗 Cadastro e gerenciamento de veículos.
- 📅 Organização e gerenciamento de agendamentos.
- 🗄️ Armazenamento de informações em banco de dados.
- 🖥️ Interface web para acesso às funcionalidades do sistema.

## 🛠️ Tecnologias utilizadas

- Python
- Flask
- MySQL
- HTML5
- CSS3
- JavaScript
- bcrypt
- Git e GitHub

## 🚀 Como acessar o sistema

Para executar o sistema localmente, siga as instruções abaixo.

### 1. Pré-requisitos

Instale as seguintes ferramentas:

- Python 3.10 ou superior.
- MySQL Server.
- MySQL Workbench (opcional, para gerenciar o banco de dados).

### 2. Baixe o projeto

Clone o repositório do GitHub:

```bash
git clone URL_DO_SEU_REPOSITORIO
```

Entre na pasta que contém os arquivos da aplicação:

```bash
cd sistema_oficina/arquivos_oficina
```

Substitua `URL_DO_SEU_REPOSITORIO` pelo endereço real do repositório.

### 3. Instale as dependências

Crie e ative um ambiente virtual:

```bash
python -m venv venv
```

No Windows:

```bash
venv\Scripts\activate
```

Instale as bibliotecas necessárias:

```bash
pip install -r requirements.txt
```

### 4. Configure o banco de dados

No MySQL Workbench, execute o script `saep_db.sql` para criar o banco de dados e as tabelas necessárias.

Verifique também as configurações de conexão no projeto, como host, usuário, senha e nome do banco de dados.

### 5. Inicie o sistema

Execute o arquivo principal da aplicação:

```bash
python app.py
```

### 6. Acesse pelo navegador

Após iniciar o servidor, abra o navegador e acesse:

**http://localhost:5000**

A página de login será exibida, caso essa seja a rota inicial configurada na aplicação. Entre com um usuário previamente cadastrado no banco de dados.

> **Observação:** o endereço `localhost` funciona apenas na máquina em que a aplicação está sendo executada. Para acessar o sistema pela internet, é necessário realizar a implantação em um servidor ou serviço de hospedagem compatível.

## 🎯 Objetivo do projeto

O projeto tem como objetivo aplicar conhecimentos de desenvolvimento web, programação em Python, utilização do framework Flask, integração com banco de dados MySQL e criação de interfaces web. A aplicação busca facilitar o gerenciamento das informações e dos serviços de uma oficina mecânica.

## 👨‍💻 Autor

**Kauan Vilas Boas Barbosa**

Estudante de Desenvolvimento de Sistemas, com interesse em programação, desenvolvimento web e banco de dados.

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais e de aprendizado.

---

⭐ Se você gostou do projeto, considere deixar uma estrela no repositório!
