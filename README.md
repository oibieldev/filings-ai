# 📊 FilingsAI - Enterprise Financial Analysis Agent

An advanced, enterprise-grade back-end application engineered to automate corporate earnings report analysis utilizing AI-driven RAG architecture. Designed under Value Investing (Benjamin Graham) and Dividend Growth (Luiz Barsi) methodologies.

## 🏛️ Financial Domain Core
- **Intrinsic Value Calculation:** Automated execution of Graham's Fair Price formula with adjustable Margin of Safety.
- **Dividend Projection Engine:** Analytical tracking of historical payouts focusing on a minimum 6% annual yield in resilient economic sectors.

## 🛠️ Tech Stack & Infrastructure
- **Core Language:** Java 21 (Utilizing Virtual Threads for high-performance concurrent processing)
- **Framework:** Spring Boot 3.x (Spring AI, Spring Data JPA, Spring Security)
- **Database & Vectors:** PostgreSQL with `pgvector` extension for semantic embeddings storage
- **Containerization:** Docker & Docker Compose
- **Architecture:** Layered Clean Architecture (Decoupled Domain, Service, and Infrastructure layers)

## 🔏 Engineering Standards Implemented
- **Branching Model:** Simplified GitFlow (`main`, `develop`, `feature/*`) via Pull Requests.
- **Commit Pattern:** Strict adherence to [Conventional Commits](https://conventionalcommits.org).
- **CI/CD Target:** GitHub Actions ready for automated testing.
