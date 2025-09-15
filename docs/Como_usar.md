## 🛠 Como executar, usar e testar o projeto  

Este guia detalha os passos para **configurar e executar o projeto localmente**.  


### ⚡ Pré-requisitos
Certifique-se de ter instalado em sua máquina:  

- [Git](https://git-scm.com/downloads)  
- [Visual Studio Code](https://code.visualstudio.com/)  
- [MySQL](https://dev.mysql.com/downloads/)  
- [Node.js 16+](https://nodejs.org/)  
- [.NET 6+](https://dotnet.microsoft.com/en-us/download)

 ### 1. Clonar o Repositório
Para começar, clone o repositório para sua máquina local e navegue até o diretório do projeto:
```bash
git clone https://github.com/seu-usuario/seu-projeto.git
cd seu-projeto
```
---

### 2. Instalar Dependências
Dependendo do tipo de projeto, execute os comandos apropriados para instalar as dependências:

#### Projeto Node.js (Frontend)
```bash
npm install
```

#### Projeto C# (Backend)
```bash
dotnet restore
```

---

### 3. Configurar Variáveis de Ambiente
Crie um arquivo `.env` na raiz do projeto e adicione as seguintes variáveis com suas credenciais:
```
DB_HOST=localhost
DB_USER=root
DB_PASS=senha
DB_NAME=meu_banco
API_KEY=xxxxxxxxxxxx
```

---

### 4. Executar o Projeto
Siga as instruções abaixo para iniciar o backend e o frontend:

#### Backend (C#)
```bash
dotnet run --project ./src/Backend
```

#### Frontend (Node.js / React / Outro)
```bash
npm start
```
O projeto estará acessível em: [http://localhost:3000](http://localhost:3000)

---

### 5. Testar Funcionalidades
Você pode testar o sistema seguindo estes exemplos:

- Abrir um chamado → Menu Principal → Novo Chamado
- Consultar NFSe → Digitar número da nota → Consultar

#### Executar Testes Automatizados
##### Node.js
```bash
npm test
```

##### C# (xUnit ou NUnit)
```bash
dotnet test
```

---
