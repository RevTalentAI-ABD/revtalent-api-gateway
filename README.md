# RevTalent API Gateway

The **API Gateway** acts as the single entry point for all client requests entering the **RevTalent** microservices ecosystem. It handles request routing, load balancing, and edge-level CORS policies.

---

##  Dependencies Added

The following dependencies are declared in this service's `pom.xml`:

- **Spring Cloud Gateway** (`spring-cloud-starter-gateway`): Provides API routing, predicate matching, and filter actions.
- **Netflix Eureka Client** (`spring-cloud-starter-netflix-eureka-client`): Registers this gateway with the Eureka Service Registry and handles service discovery.
- **Spring Cloud Config Client** (`spring-cloud-starter-config`): Imports externalized configuration properties from the Central Config Server.
- **Spring Boot Actuator** (`spring-boot-starter-actuator`): Exposes application health checks, metrics, and runtime info.
- **Spring Boot Starter Test** (`spring-boot-starter-test`): Core testing framework dependencies.

---

##  Master Ecosystem Directory (GitHub Repositories)

Here is the master list of all repositories comprising the **RevTalent** microservices ecosystem:

1. **[Frontend](https://github.com/RevTalentAI-ABD/Frontend)**: React & Vite Single Page Client Application.
2. **[revtalent-eureka-server](https://github.com/RevTalentAI-ABD/revtalent-eureka-server)**: Service registry where all instances register for discovery.
3. **[revtalent-config-server](https://github.com/RevTalentAI-ABD/revtalent-config-server)**: Dynamic configuration management cloned from a secure repository.
4. **[revtalent-config](https://github.com/RevTalentAI-ABD/revtalent-config)**: Git repository storing global configuration properties files.
5. **[revtalent-auth-service](https://github.com/RevTalentAI-ABD/revtalent-auth-service)**: Authentication, JWT generation, registration, and OTP verification.
6. **[revtalent-employee-service](https://github.com/RevTalentAI-ABD/revtalent-employee-service)**: Employee directory, hierarchy tree, attendance checks, kudos, and policy documents.
7. **[revtalent-leave-service](https://github.com/RevTalentAI-ABD/revtalent-leave-service)**: Time-off management, requests, approval flows, and leave balances.
8. **[revtalent-payroll-service](https://github.com/RevTalentAI-ABD/revtalent-payroll-service)**: Salary processing, payslip PDF reports, and company-wide notifications/announcements.
9. **[revtalent-performance-service](https://github.com/RevTalentAI-ABD/revtalent-performance-service)**: Employee goal setting, appraisals, feedback, and performance rating evaluations.
10. **[revtalent-recruitment-service](https://github.com/RevTalentAI-ABD/revtalent-recruitment-service)**: Job listings, candidate management, resume parsing, and screening.
11. **[revtalent-ai-service](https://github.com/RevTalentAI-ABD/revtalent-ai-service)**: AI chatbot and Document RAG implementation using local Ollama & ChromaDB vector search.
12. **[revtalent-infrastructure](https://github.com/RevTalentAI-ABD/revtalent-infrastructure)**: Docker Compose orchestration and Kubernetes resource configurations for external database servers and systems.
