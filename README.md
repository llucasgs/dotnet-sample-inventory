# 🚀 AppProject – .NET Enterprise Template

<p align="center">
  <img src="https://img.shields.io/badge/.NET-9.0-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/C%23-Language-239120?style=for-the-badge&logo=csharp&logoColor=white" />
  <img src="https://img.shields.io/badge/ASP.NET_Core-API-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/Blazor-Frontend-512BD4?style=for-the-badge&logo=blazor&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL_Server-Database-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
</p>

---

## 📌 About

This project is a modern, modular and scalable **.NET enterprise template**, designed with clean separation between:

- Frontend (Blazor)
- Backend (ASP.NET Core API)
- Infrastructure
- Automated Testing
- External Integrations
- AI-ready architecture

It is built to serve as a reusable foundation for robust business applications.

---

# 🏗 Architecture Overview

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
Infrastructure (DB, Email, Jobs, AI)
        ↓
Response
```

---

## 🔹 Frontend Stack

- Blazor
- Auth0 Authentication
- Radzen UI Components
- Refit (Typed HTTP Client)
- .resx Internationalization
- Modular Web Projects

---

## 🔹 Backend Stack

- ASP.NET Core Web API
- REST Controllers
- Service Layer (Business Rules)
- Centralized Exception Handling
- Hybrid Cache Strategy
- Validation Layer
- Swagger Documentation

---

# 🧱 Solution Structure

## 🌍 Global Projects

- `AppProject.Exceptions`
- `AppProject.Models`
- `AppProject.Resources`
- `AppProject.Utils`

---

## 🟢 Backend Projects

- `AppProject.Core.API`
- `AppProject.Core.Services.<Module>`
- `AppProject.Core.Contracts`
- `AppProject.Core.Controllers.<Module>`
- `AppProject.Core.Infrastructure.Database`
- `AppProject.Core.Infrastructure.Email`
- `AppProject.Core.Infrastructure.Jobs`
- `AppProject.Core.Infrastructure.AI`
- `AppProject.Core.Models.<Module>`

---

## 🟣 Frontend Projects

- `AppProject.Web`
- `AppProject.Web.Framework`
- `AppProject.Web.ApiClient.<Module>`
- `AppProject.Web.Models.<Module>`
- `AppProject.Web.Shared`
- `AppProject.Web.<Module>`

---

## 🧪 Test Projects

- `AppProject.Core.Tests.<Module>`
- `AppProject.Web.Tests.<Module>`

---

# 🛠 Technologies

## 🔷 Core

<p>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white"/>
  <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/Blazor-512BD4?style=flat-square&logo=blazor&logoColor=white"/>
</p>

---

## 🗄 Database

<p>
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white"/>
  <img src="https://img.shields.io/badge/Entity_Framework-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
</p>

---

## 🔐 Authentication

<p>
  <img src="https://img.shields.io/badge/Auth0-EB5424?style=flat-square&logo=auth0&logoColor=white"/>
</p>

---

## 🔄 API Communication

<p>
  <img src="https://img.shields.io/badge/Refit-00ADD8?style=flat-square"/>
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black"/>
</p>

---

## 📊 Logging & Code Quality

<p>
  <img src="https://img.shields.io/badge/Serilog-0E9BA4?style=flat-square"/>
  <img src="https://img.shields.io/badge/StyleCop-000000?style=flat-square"/>
</p>

---

## 📬 External Services

<p>
  <img src="https://img.shields.io/badge/SendGrid-00B3E3?style=flat-square&logo=sendgrid&logoColor=white"/>
  <img src="https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hangfire-FF6C37?style=flat-square"/>
  <img src="https://img.shields.io/badge/GitHub_Models-181717?style=flat-square&logo=github&logoColor=white"/>
</p>

---

## 🧪 Testing Stack

<p>
  <img src="https://img.shields.io/badge/NUnit-25A162?style=flat-square"/>
  <img src="https://img.shields.io/badge/Moq-000000?style=flat-square"/>
  <img src="https://img.shields.io/badge/Bogus-FF6F00?style=flat-square"/>
  <img src="https://img.shields.io/badge/Shouldly-512BD4?style=flat-square"/>
</p>

---

# 🧠 Architectural Principles

- Clean Layered Architecture
- Separation of Concerns
- Dependency Inversion
- DTO Isolation per Layer
- Contract-Based Communication
- Infrastructure Abstraction
- Modular Domain Organization
- Hybrid Cache Strategy
- Internationalization Support
- AI-ready Integration Layer
- High Testability

---

# 🔄 Request Flow

1. Client accesses application (Browser/Mobile)
2. Blazor calls API via Refit
3. Controller receives request
4. Service applies business rules
5. Infrastructure accesses external dependencies
6. Response is returned to client

---

# 🚧 Project Status

🟡 In Development  
✔️ Base architecture completed  
🔄 Domain modules under construction

---

# 🎯 Goals

This template aims to provide:

- Enterprise-ready foundation
- Scalability
- Maintainability
- Strong separation of layers
- Production-grade structure
- AI-ready integration

---

# 👨‍💻 Author

**Lucas Silva**  
FullStack Developer  
.NET • Blazor • ASP.NET Core • SQL Server
