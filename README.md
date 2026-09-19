\<div align="center">

\<img src="[https://capsule-render.vercel.app/api?type=waving&color=0:512BD4,100:0EA5E9&height=190&section=header&text=Ahmed%20Mohammed%20Saad&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Backend%20.NET%20Developer%20%7C%20ASP.NET%20Core%20%7C%20SQL%20Server&descAlignY=55&descSize=18](https://capsule-render.vercel.app/api?type=waving\&color=0:512BD4,100:0EA5E9\&height=190\&section=header\&text=Ahmed%20Mohammed%20Saad\&fontSize=40\&fontColor=ffffff\&animation=fadeIn\&fontAlignY=35\&desc=Backend%20.NET%20Developer%20%7C%20ASP.NET%20Core%20%7C%20SQL%20Server\&descAlignY=55\&descSize=18)" width="100%"/>


\


\</div>

## 👋 About Me

I'm a **Backend .NET Developer** focused on building backend systems around real business rules, not just CRUD endpoints.

I work primarily with **ASP.NET Core, C#, Entity Framework Core, and SQL Server**, with particular interest in:

- Clean Architecture and maintainable system boundaries
- REST API design
- Authentication and authorization
- Transactional business workflows
- Optimistic concurrency
- Database design
- Real-time systems with SignalR
- Unit, integration, and architecture testing
- Production-oriented backend practices

I enjoy working on systems where correctness matters: scheduling, payments, permissions, financial workflows, multi-tenant access, and concurrent operations.

---

## 🛠️ Core Backend Stack

\<p align="left">

\<img src="[https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white](https://img.shields.io/badge/C%23-239120?style=for-the-badge\&logo=csharp\&logoColor=white)"/>
\<img src="[https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge\&logo=dotnet\&logoColor=white)"/>
\<img src="[https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge\&logo=dotnet\&logoColor=white)"/>
\<img src="[https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge&logo=nuget&logoColor=white](https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge\&logo=nuget\&logoColor=white)"/>
\<img src="[https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge\&logo=microsoftsqlserver\&logoColor=white)"/>

\</p>

### Backend Engineering

\<p align="left">

\<img src="[https://img.shields.io/badge/REST_APIs-02569B?style=for-the-badge](https://img.shields.io/badge/REST_APIs-02569B?style=for-the-badge)"/>
\<img src="[https://img.shields.io/badge/Clean_Architecture-111827?style=for-the-badge](https://img.shields.io/badge/Clean_Architecture-111827?style=for-the-badge)"/>
\<img src="[https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white](https://img.shields.io/badge/JWT-000000?style=for-the-badge\&logo=jsonwebtokens\&logoColor=white)"/>
\<img src="[https://img.shields.io/badge/SignalR-512BD4?style=for-the-badge&logo=dotnet&logoColor=white](https://img.shields.io/badge/SignalR-512BD4?style=for-the-badge\&logo=dotnet\&logoColor=white)"/>
\<img src="[https://img.shields.io/badge/xUnit-512BD4?style=for-the-badge](https://img.shields.io/badge/xUnit-512BD4?style=for-the-badge)"/>
\<img src="[https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge\&logo=swagger\&logoColor=black)"/>
\<img src="[https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)"/>

\</p>

---

# 🚀 Featured Backend Projects

## 🏥 Clinic Management Backend

A production-oriented **clinic management backend** built as a modular monolith with Clean Architecture.

The system models real clinic workflows including scheduling, patients, clinical records, cashier operations, collections, refunds, treatment packages, prescriptions, and administrative approvals.

### Engineering Highlights

- Clean Architecture with strict project boundaries
- Domain, Application, Infrastructure, and API layers
- Architecture tests enforcing dependency rules
- Domain and Application unit tests
- SQL Server-backed API integration tests
- Doctor, room, and medical-device conflict protection
- Transactional appointment scheduling
- Cash drawers and cashier shifts
- Payment allocation and refund workflows
- Administrative cancellation approvals
- SQL Server `rowversion` optimistic concurrency
- ASP.NET Core Identity
- Secure cookie authentication
- CSRF protection
- RFC-style `ProblemDetails`
- Audit logging
- Health and SQL Server readiness checks

**Tech:** `.NET 10` · `ASP.NET Core` · `EF Core` · `SQL Server` · `Identity` · `xUnit`

\


---

## 🏠 EstateHub

A large **multi-tenant real-estate platform backend** supporting customers, real-estate companies, employees, and platform administrators.

The system covers property discovery, company operations, projects, units, listings, CRM, bookings, subscriptions, promotions, billing, reviews, notifications, and secure file delivery.

### Engineering Highlights

- Clean Architecture-inspired layered backend
- Multi-tenant company access
- Database-backed permission resolution
- Fine-grained company RBAC
- Separate platform administration authorization
- JWT authentication
- Persisted refresh sessions
- Refresh-token rotation and revocation
- Authentication-specific rate limiting
- Optimistic concurrency
- Transactional business operations
- Projection-first EF Core queries
- Pagination and cancellation-token propagation
- Secure file upload and delivery
- Billing and subscription workflows
- Extensive API documentation
- **164 distinct HTTP verb/route pairs across 32 controllers**

**Tech:** `.NET 10` · `ASP.NET Core` · `EF Core` · `SQL Server` · `Identity` · `JWT`


\


---

## 🎣 Saiyad — Real-Time Marketplace & Auctions

A backend for a fishing marketplace and real-time auction platform connecting customers, fishermen, bait sellers, and auctioneers.

Saiyad focuses heavily on real-time communication and production-oriented runtime concerns.

### Engineering Highlights

- Real-time auctions using SignalR
- Group-based auction communication
- Concurrency-safe bidding
- Automatic bid processing
- JWT authentication
- Rotating refresh tokens
- SHA-256 refresh-token storage
- Background services for timed workflows
- Wallet and subscription systems
- Order and payment workflows
- Health checks
- SQL Server monitoring
- Serilog structured logging
- Rate limiting
- Security headers
- Production migration locking with SQL Server application locks
- Automated unit and integration tests

**Tech:** `.NET 10` · `ASP.NET Core` · `SignalR` · `EF Core` · `SQL Server` · `JWT` · `Serilog`


\


---

# 🗄️ Database Engineering

## Khidma

A SQL Server database designed for a multi-role service marketplace.

The project focuses on relational database design and database-side workflows.

### Highlights

- Normalized relational schema
- Entity relationships and integrity constraints
- Foreign keys and cascading rules
- **63 Stored Procedures**
- **26 SQL Views**
- Reporting and operational queries



---

# 🧪 How I Approach Backend Engineering

I try to make architectural and implementation decisions based on the problem rather than adding patterns automatically.

Some principles I follow:

```text
Business rules belong outside controllers.

Domain code should not depend on infrastructure.

Use transactions when partial completion would corrupt business state.

Handle concurrent updates explicitly when correctness matters.

Use Result-style outcomes for expected business failures.

Use exceptions for unexpected failures.

Avoid generic abstractions when the framework already provides the behavior.

Test business rules, HTTP behavior, database behavior, and architecture boundaries.

Protect historical financial and clinical data instead of treating everything as disposable CRUD data.
```

---

# 🔍 Areas I'm Currently Deepening

- Advanced ASP.NET Core
- System Design
- SQL Server performance
- Database concurrency
- Authentication & authorization
- Distributed systems fundamentals
- Application observability
- Automated testing strategy
- CI/CD and deployment automation

---

# 🌐 Additional Web Experience

Backend development is my primary focus, but I also have experience building and integrating frontend applications.

Technologies I've worked with include:

```text
JavaScript
TypeScript
React
Vite
Alpine.js
Bootstrap
HTML
CSS
PWA
REST API Integration
SignalR Clients
```

This helps me understand how frontend applications consume and interact with backend systems without positioning frontend development as my main specialization.

---

# 📊 GitHub Activity

\<div align="center">

\<img src="assets/stats.svg" height="165" alt="Ahmed Saad GitHub Stats"/>
\<img src="assets/top-langs.svg" height="165" alt="Ahmed Saad Top Languages"/>

\<br/>

\<img src="assets/streak.svg" alt="Ahmed Saad GitHub Streak"/>

\</div>

---

# 🎯 What I'm Looking For

I'm currently open to opportunities as a:

### **Backend .NET Developer**

where I can work on real backend systems involving:

```text
ASP.NET Core
REST APIs
SQL Server
Entity Framework Core
Authentication & Authorization
Business Workflows
Concurrency
Testing
Backend Architecture
```

I'm especially interested in teams where I can keep improving through code reviews, production systems, and strong engineering practices.

---

\<div align="center">

## 📫 Let's Connect


\


\<br/>

**Backend .NET Developer · C# · ASP.NET Core · SQL Server**

\</div>
