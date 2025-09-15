# PIM 4º SEMESTRE
<br>
<h1 align="center"> <b>SmartDesk: Sistema de Abertura de Chamados</b></h1>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b7a4ce2d-20f7-4a12-8cb4-530f36fb1950" width="200" alt="Logo do Projeto"><br><br>
  <i>Web, Desk e Mobile com Integração de IA</i><br>
  <sub>Status do Projeto: 🚧 Em Desenvolvimento</sub>
</p>

<div align="center">

</div>

<br>

## 📄 Documentação do Projeto

Navegue pelas seções abaixo para conhecer todos os detalhes do projeto.

- 🎯 Descrição do Desafio: [**Clique aqui**](./docs/Desafio_do_Projeto.md) para ver com detalhes.
- 📋 Backlog de Produto: [**Clique aqui**](./docs/Backlog.md) para ver o backlog.
- 🚀 Cronograma de Evolução do Projeto: [**Clique aqui**](./docs/Cronograma.md) para ver o cronograma.
- 📆 Tabela Descritiva das Sprints: [**Clique aqui**](./docs/Sprints.md) para saber mais das nossas sprints.
- 💻 Tecnologias Utilizadas: [**Clique aqui**](./docs/Tecnologias_Utilizadas.md) para cohecer as tecnologias do projeto. 
- 🏗️ Estrutura do Projeto: [**Clique aqui**](./docs/Estrutura_do_projeto.md) para ver a estrutura do projeto.
- 🛠️ Como executar, usar e testar o projeto: [**Clique aqui**](./docs/HOW_TO_USE.md) para saber como usar nosso projeto. 
- 👥 Equipe: [**Clique aqui**](./docs/TEAM.md) para conhecer a nossa equipe.

<br>

<br>

## 🏗️ Estrutura do Projeto

/chamados-app  
│  
├── /backend/       # Servidor, APIs e integração com banco de dados  
├── /frontend/      # Aplicação web  
├── /mobile/        # Aplicação mobile  
├── /docs/          # Documentação detalhada  
├── /tests/         # Testes automatizados  
└── README.md       # Documentação principal  

<br>

## 🛠 Como executar, usar e testar o projeto
Este guia detalha os passos para **configurar e executar o projeto localmente**.

### Pré-requisitos
Antes de iniciar, certifique-se de ter instalado em sua máquina:

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

## 📂 Documentação

Toda a documentação do projeto está disponível na pasta [docs](./docs) do repositório.  

Você pode acessar diretamente clicando aqui: [Pasta de Documentação](./docs)

<br>


## 👥 Equipe

| Membro                       | Função          | GitHub                                                                                     | LinkedIn                                                                                   |
|-----------------------------|-----------------|---------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|
| Maria Luíza Fonseca Amaro   | Product Owner   | [![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MariaFAmaro01) | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0e76a8?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maria-luiza-fonseca-amaro-338305279?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)    |
| Felipe Freitas da Rocha     | Scrum Master    | [![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Felipe-Freitas-Rocha) | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0e76a8?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/felipefreitasrocha) |
| Ana Beatriz Barni Franco    | Dev | [![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Anabarni) | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0e76a8?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/anabeatrizfranco) |
| Gabriel Freitas de Campos   | Dev | [![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GabrielFreitas2025) | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0e76a8?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/gabrielfreitascampos) |
| Maio de Almeida Braga       | Dev | [![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/maioAB) | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0e76a8?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/maiobraga) |
| Nicolas Furtado Rodrigues   | Dev | [![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AkiraNyaprog) | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0e76a8?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/nicolasfurtado) |

