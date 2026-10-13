# Hi, I'm Saad Kabir Uddin 👋

**Software Engineer | Backend & Full-Stack Development | Software Engineering & AI**

I am a software engineer working on enterprise and financial software systems, primarily using **C#, ASP.NET Core, Angular, SQL Server, and REST APIs**.

My interests sit at the intersection of **Software Engineering, Artificial Intelligence, and Software Security**, with particular interest in building reliable, secure, and maintainable software systems — including the security of LLM agents that act on users' behalf.

I also have academic research experience in **machine learning and computer vision**, including biometric systems and medical image analysis.

---

## 🔬 Research Interests

- Software Engineering
- Software Security
- AI for Software Engineering (AI4SE)
- AI for Security
- Security of LLM Agents and AI Systems
- Secure and Reliable AI-Assisted Software Systems
- Software Architecture
- Automated Testing and Program Analysis

---

## 💻 What I Work On

My professional work focuses on designing and developing enterprise software systems, including:

- Financial and transactional software
- Backend services and REST APIs
- Authentication and authorization systems
- Data reconciliation and processing systems
- Case management applications
- Database design and optimization
- Integration between enterprise applications
- Role-based access control and secure application workflows

---

## 🛠️ Tech Stack

### Languages

`C#` `Python` `SQL` `TypeScript` `JavaScript` `Java` `Go`

### Backend

`ASP.NET Core` `ASP.NET MVC` `.NET` `Entity Framework Core`  
`REST APIs` `FastAPI` `JWT Authentication`

### Frontend

`Angular` `HTML` `CSS` `JavaScript` `TypeScript`

### Database

`Microsoft SQL Server`

### Software Engineering

`Clean Architecture` `CQRS` `MediatR`  
`Dependency Injection` `Git` `API Integration`  
`Authentication & Authorization` `Role-Based Access Control`

### AI / Machine Learning

`PyTorch` `Deep Learning` `Computer Vision`  
`Transfer Learning` `Image Processing` `Local LLMs` `Ollama`  
`LLM Tool Calling`

---

## 🚀 Selected Projects

### 🔹 [LLM Agent Security Gateway (AgentGuard)](https://github.com/saadkabiruddin/LlmAgentSecurityGateway)

A security gateway that sits between an LLM agent and the tools it can call, and decides — independently of the model — whether each tool call is something the user is allowed to do **and** actually asked for.

Built and evaluated on a local banking agent under prompt-injection attacks:

- A **role-based check alone** blocked only 3 of 8 attacks from a hijacked agent — it could not stop unauthorized transfers, because the user *is* allowed to transfer money.
- Adding **task-scope and argument-provenance checks** blocked **8 of 8**, with **no legitimate requests blocked**.

**Key areas:**
- LLM agent security and indirect prompt injection
- Least privilege and task-scoped authorization
- ASP.NET Core gateway with audit logging
- Python agent on local LLMs (Ollama)
- Experimental security evaluation

---

### 🔹 [.NET Security Analyzer (Roslyn)](https://github.com/saadkabiruddin/RoslynSecurityAnalyzer)

A software security research project in two stages:

1. **Vulnerable target API** — a deliberately insecure ASP.NET Core banking-style API with hand-planted vulnerabilities, built as a realistic test target.
2. **Roslyn security analyzer** — a static analysis tool built on the .NET Compiler Platform (Roslyn) that aims to detect those vulnerability patterns directly in C# source code.

**Key areas:**
- ASP.NET Core Web API
- Secure coding and common web vulnerability classes
- Static program analysis
- Roslyn analyzers (C# syntax trees and semantic models)

The goal is to explore how automated analysis can catch security defects earlier in the development process.

---

### 🔹 RecWiz — Reconciliation Wizard

An enterprise reconciliation platform designed for processing and comparing large financial datasets.

**Key areas:**
- ASP.NET Core Web API
- Angular
- SQL Server
- CQRS and MediatR
- Batch data processing
- JWT authentication
- Modular application architecture

---

### 🔹 Case Management Application

Enterprise case management software designed to support structured workflows, reporting, and integration with external financial systems.

**Key areas:**
- Database schema design
- REST API development
- Role-based access control
- External API integration
- Reporting workflows
- Enterprise data management

---

### 🔹 AI Assistant

An experimental full-stack AI assistant using local large language models.

**Technologies:**
- FastAPI
- Angular
- Ollama
- Local LLMs
- Python

The project explores integrating modern AI capabilities into conventional software applications.

---

### 🔹 DeliveryDash

A small 2D game project developed with Unity and published for the web.

**Technologies:**
- Unity
- C#
- WebGL

---

## 📚 Research Experience

My academic research background includes machine learning, computer vision, and image processing.

### Iris Recognition and Segmentation

Research involving iris image processing, segmentation, biometric recognition, and deep-learning-based approaches for non-ideal iris images.

### Brain Tumor Detection from MRI

Worked on deep-learning-based brain tumor classification using transfer learning and EfficientNet architectures.

My current interests increasingly focus on applying AI techniques to problems in software engineering, security, testing, code analysis, and reliable software development — and on securing AI agents themselves.

---

## 🧠 Areas I'm Exploring

I am particularly interested in questions such as:

**Software Engineering & AI**
- How can AI improve software testing and debugging?
- How can we evaluate the correctness of AI-generated code?
- How can software engineering practices improve AI-enabled systems?

**Software Security**
- How can static analysis tools catch security defects before code reaches production?
- How can vulnerabilities in AI-generated code be detected automatically?
- How can AI and LLMs assist in vulnerability detection without overwhelming developers with false positives?
- How can authentication, authorization, and access-control flaws be identified in real-world web APIs?
- How can AI-assisted development remain secure and maintainable?
- How can LLM agents that call tools be kept within what the user actually asked for, even when the model is manipulated?

---

## 📊 GitHub Activity

![GitHub stats](https://github-readme-stats.vercel.app/api?username=saadkabiruddin&show_icons=true&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=saadkabiruddin&layout=compact&hide_border=true)

---

## 🌐 Links

- 🌐 [Portfolio Website](https://saadkabiruddin.github.io/)
- 🔗 [LinkedIn](https://www.linkedin.com/in/saadkabiruddin)
<!-- - 🎓 [Google Scholar](PASTE_YOUR_SCHOLAR_URL_HERE) -->
<!-- - 📄 [Curriculum Vitae](PASTE_YOUR_CV_URL_HERE) -->

---

### Thanks for visiting 👋

I enjoy building reliable software systems and exploring how software engineering, artificial intelligence, and security can work together to create better software.
