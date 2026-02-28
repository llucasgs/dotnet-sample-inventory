# 🚀 AppProject – .NET Enterprise Template

<p align="center">
  <img src="https://img.shields.io/badge/.NET-9.0-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/C%23-Language-239120?style=for-the-badge&logo=csharp&logoColor=white" />
  <img src="https://img.shields.io/badge/ASP.NET_Core-API-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/Blazor-Frontend-512BD4?style=for-the-badge&logo=blazor&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL_Server-Database-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
</p>

# 🇧🇷 Português

## 📌 Sobre o Projeto

Este projeto é um template corporativo moderno em **.NET**, estruturado com separação clara entre camadas e foco em escalabilidade, organização e testabilidade.

Foi projetado como base reutilizável para aplicações empresariais robustas.

## 🏗 Visão Geral da Arquitetura

```
Cliente (Browser/Mobile)
        ↓
Frontend (Blazor)
        ↓
Refit (DTOs)
        ↓
Controllers (API)
        ↓
Services (Regras de Negócio)
        ↓
Infrastructure (Banco, Email, Jobs, IA)
        ↓
Resposta
```

## 🔹 Frontend

- Blazor
- Auth0
- Radzen
- Refit
- Internacionalização (.resx)
- Estrutura modular

## 🔹 Backend

- ASP.NET Core Web API
- Controllers REST
- Camada de Services
- Validações centralizadas
- Tratamento global de exceções
- Cache híbrido
- Swagger

# 🧱 Estrutura da Solução

## 🌍 Projetos Globais

- `AppProject.Exceptions`
- `AppProject.Models`
- `AppProject.Resources`
- `AppProject.Utils`

## 🟢 Backend

- `AppProject.Core.API`
- `AppProject.Core.Services.<Module>`
- `AppProject.Core.Contracts`
- `AppProject.Core.Controllers.<Module>`
- `AppProject.Core.Infrastructure.Database`
- `AppProject.Core.Infrastructure.Email`
- `AppProject.Core.Infrastructure.Jobs`
- `AppProject.Core.Infrastructure.AI`
- `AppProject.Core.Models.<Module>`

## 🟣 Frontend

- `AppProject.Web`
- `AppProject.Web.Framework`
- `AppProject.Web.ApiClient.<Module>`
- `AppProject.Web.Models.<Module>`
- `AppProject.Web.Shared`
- `AppProject.Web.<Module>`

## 🧪 Testes

- `AppProject.Core.Tests.<Module>`
- `AppProject.Web.Tests.<Module>`

# 🛠 Tecnologias

## 🔷 Core

<p>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white"/>
  <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/Blazor-512BD4?style=flat-square&logo=blazor&logoColor=white"/>
</p>

## 🗄 Banco de Dados

<p>
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white"/>
  <img src="https://img.shields.io/badge/Entity_Framework_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
</p>

## 🔐 Autenticação

<p>
  <img src="https://img.shields.io/badge/Auth0-EB5424?style=flat-square&logo=auth0&logoColor=white"/>
</p>

## 🔄 Comunicação com a API

<p>
  <img src="https://img.shields.io/badge/Refit-00ADD8?style=flat-square"/>
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black"/>
</p>

## 📊 Logs e Qualidade de Código

<p>
  <img src="https://img.shields.io/badge/Serilog-0E9BA4?style=flat-square"/>
  <img src="https://img.shields.io/badge/StyleCop-000000?style=flat-square"/>
</p>

## 📬 Serviços Externos

<p>
  <img src="https://img.shields.io/badge/SendGrid-00B3E3?style=flat-square&logo=sendgrid&logoColor=white"/>
  <img src="https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hangfire-FF6C37?style=flat-square"/>
  <img src="https://img.shields.io/badge/GitHub_Models-181717?style=flat-square&logo=github&logoColor=white"/>
</p>

## 🧪 Testes Automatizados

<p>
  <img src="https://img.shields.io/badge/NUnit-25A162?style=flat-square"/>
  <img src="https://img.shields.io/badge/Moq-000000?style=flat-square"/>
  <img src="https://img.shields.io/badge/Bogus-FF6F00?style=flat-square"/>
  <img src="https://img.shields.io/badge/Shouldly-512BD4?style=flat-square"/>
</p>

## 🧠 Princípios Arquiteturais

- Separação de responsabilidades
- Inversão de dependência
- Modularização por domínio
- Abstração de infraestrutura
- DTOs isolados por camada
- Estratégia de cache híbrido
- Internacionalização
- Alta testabilidade

## 🚧 Status

🟡 Em desenvolvimento  
✔ Estrutura base concluída  
🔄 Implementação de módulos em andamento

---

# 🇺🇸 English

## 📌 About

This project is a modern enterprise **.NET template**, designed with clear layer separation, scalability and maintainability in mind.

It serves as a reusable foundation for robust business applications.

## 🏗 Architecture Overview

```
Client (Browser/Mobile)
        ↓
Frontend (Blazor)
        ↓
Refit (DTO Contracts)
        ↓
Controllers (API Layer)
        ↓
Services (Business Rules)
        ↓
Infrastructure (Database, Email, Jobs, AI)
        ↓
Response
```

## 🔹 Frontend

- Blazor
- Auth0
- Radzen UI Components
- Refit
- Internationalization (.resx)
- Modular structure

## 🔹 Backend

- ASP.NET Core Web API
- REST Controllers
- Service Layer
- Centralized validations
- Global exception handling
- Hybrid cache strategy
- Swagger documentation

# 🧱 Solution Structure

## 🌍 Global Projects

- `AppProject.Exceptions`
- `AppProject.Models`
- `AppProject.Resources`
- `AppProject.Utils`

## 🟢 Backend

- `AppProject.Core.API`
- `AppProject.Core.Services.<Module>`
- `AppProject.Core.Contracts`
- `AppProject.Core.Controllers.<Module>`
- `AppProject.Core.Infrastructure.Database`
- `AppProject.Core.Infrastructure.Email`
- `AppProject.Core.Infrastructure.Jobs`
- `AppProject.Core.Infrastructure.AI`
- `AppProject.Core.Models.<Module>`

## 🟣 Frontend

- `AppProject.Web`
- `AppProject.Web.Framework`
- `AppProject.Web.ApiClient.<Module>`
- `AppProject.Web.Models.<Module>`
- `AppProject.Web.Shared`
- `AppProject.Web.<Module>`

## 🧪 Tests

- `AppProject.Core.Tests.<Module>`
- `AppProject.Web.Tests.<Module>`

# 🛠 Technologies

## 🔷 Core

<p>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white"/>
  <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/Blazor-512BD4?style=flat-square&logo=blazor&logoColor=white"/>
</p>

## 🗄 Database

<p>
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white"/>
  <img src="https://img.shields.io/badge/Entity_Framework-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
</p>

## 🔐 Authentication

<p>
  <img src="https://img.shields.io/badge/Auth0-EB5424?style=flat-square&logo=auth0&logoColor=white"/>
</p>

## 🔄 API Communication

<p>
  <img src="https://img.shields.io/badge/Refit-00ADD8?style=flat-square"/>
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black"/>
</p>

## 📊 Logging & Code Quality

<p>
  <img src="https://img.shields.io/badge/Serilog-0E9BA4?style=flat-square"/>
  <img src="https://img.shields.io/badge/StyleCop-000000?style=flat-square"/>
</p>

## 📬 External Services

<p>
  <img src="https://img.shields.io/badge/SendGrid-00B3E3?style=flat-square&logo=sendgrid&logoColor=white"/>
  <img src="https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hangfire-FF6C37?style=flat-square"/>
  <img src="https://img.shields.io/badge/GitHub_Models-181717?style=flat-square&logo=github&logoColor=white"/>
</p>

## 🧪 Testing Stack

<p>
  <img src="https://img.shields.io/badge/NUnit-25A162?style=flat-square"/>
  <img src="https://img.shields.io/badge/Moq-000000?style=flat-square"/>
  <img src="https://img.shields.io/badge/Bogus-FF6F00?style=flat-square"/>
  <img src="https://img.shields.io/badge/Shouldly-512BD4?style=flat-square"/>
</p>

## 🧠 Architectural Principles

- Separation of concerns
- Dependency inversion
- Modular domain organization
- Infrastructure abstraction
- Layer-isolated DTOs
- Hybrid caching
- Internationalization
- High testability

---

## 🚧 Status

🟡 In development  
✔ Base architecture completed  
🔄 Domain modules under construction

---

# 👨‍💻 Author

Lucas Silva  
FullStack Developer  
.NET • Blazor • ASP.NET Core • SQL Server
