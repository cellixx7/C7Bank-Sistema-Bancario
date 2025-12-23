# 🏦 C7Bank - Sistema Bancário

O **C7Bank** é uma aplicação Full Stack de simulação bancária, focada em fornecer uma interface moderna e segura para transações financeiras. O projeto utiliza uma arquitetura robusta dividindo o ecossistema entre um front-end performático em React e um back-end ágil em Python.

---

## 🚀 Tecnologias Utilizadas

### **Front-end**
* **React.js** (com Vite e TypeScript)
* **JavaScript/TypeScript**
* **CSS-in-JS** (Estilização integrada)

### **Back-end**
* **Python**
* **Flask** (Framework web)
* **Node.js** (Ferramentas de automação/scripts)

### **Banco de Dados**
* **PostgreSQL** (Relacional)

---

## 🛠️ Funcionalidades em Desenvolvimento

- [x] Interface Dark Mode Responsiva.
- [x] Estrutura inicial de rotas de usuário.
- [ ] Cadastro e Login de clientes (Autenticação JWT).
- [ ] Consulta de saldo e extrato.
- [ ] Transferências entre contas (PIX/TED).
- [ ] Integração completa Front/Back.

---

## 📦 Como rodar o projeto

### 1. Pré-requisitos
* Node.js instalado
* Python 3.x instalado
* PostgreSQL configurado e rodando

### 2. Configurando o Back-end
```bash
# Entre na pasta do back-end
cd back

# Crie um ambiente virtual
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate

# Instale as dependências (exemplo se houver requirements.txt)
pip install -r requirements.txt

# Execute o servidor
python src/server.py