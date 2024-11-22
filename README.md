# Sistema de Distribuidora de Bebidas  

Este projeto é um sistema web desenvolvido para gerenciar os produtos de uma distribuidora de bebidas. Ele inclui um **frontend** hospedado remotamente, um **backend** para APIs RESTful e um **banco de dados SQLite**.

## 🖥️ Acesso ao Sistema  

- **Frontend**:  
  O frontend pode ser acessado no link abaixo:  
  [Sistema de Distribuidora - Frontend](https://trabalho-ads-frontend.onrender.com/)  

- **Backend e Banco de Dados**:  
  O backend está configurado no Render e funciona integrado ao banco de dados SQLite. Por estar hospedado no plano gratuito, pode haver um **delay de inicialização** ao acessá-lo pela primeira vez, pois o container precisa ser iniciado.  

---

## 🛠️ Funcionalidades  

### **Frontend**
- **Página de Login**: Autenticação de usuário.
- **CRUD de Produtos**:
  - Listar, adicionar, editar e excluir produtos.
- **Relatório**:
  - Exibe uma visão consolidada dos produtos cadastrados.

### **Backend**
- Desenvolvido com **FastAPI** e configurado para gerenciamento de usuários e produtos.
- Banco de dados: **SQLite**.
- API interativa disponível em [`/docs`](https://trabalho-ads-backend.onrender.com/docs) no servidor backend.

---

## 🚀 Como Acessar  

### **Credenciais de Acesso Padrão**
- **Login**: `admin`  
- **Senha**: `admin`  

### **Observações**
1. O backend pode demorar alguns segundos para responder devido ao delay de inicialização no **Render Free Plan**.
2. O frontend está conectado remotamente ao backend para consumir as APIs e manipular os dados.

---

## 📚 Tecnologias Utilizadas  

### **Frontend**
- HTML, CSS, JavaScript
- Bootstrap

### **Backend**
- FastAPI
- SQLite (Banco de Dados)

### **Hospedagem**
- Frontend e Backend: [Render](https://render.com/)

---

## 📂 Estrutura do Projeto  

### **Frontend**
- Contém as páginas HTML e scripts JavaScript para interação com o backend.

### **Backend**
- API RESTful criada com FastAPI para manipulação de dados e autenticação de usuários.
- Configuração do banco de dados SQLite.

---
