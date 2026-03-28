# E aí! 👋 Sou o Quintanilha

<div align="center">
  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-quintanilha-997360185/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/gabriel_quintanilha09/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gabriel.hemendinger@gmail.com)

</div>

## 👨‍💻 Um pouco sobre mim

Fala pessoal! Sou desenvolvedor Java e adoro construir soluções com **Spring Boot** e **Microserviços**. Quando não estou debugando código, estou estudando alguma tecnologia nova ou pensando em como melhorar algum sistema.

Gosto muito de trabalhar com **APIs RESTful**, **banco de dados** (PostgreSQL é vida ❤️) e colocar tudo para rodar na **AWS**. Também domino **Docker**, **Redis** e estou sempre atento às boas práticas como **Clean Code** e **SOLID**.

Ah, e sim... **estou de olho em oportunidades** para trabalhar em projetos desafiadores! 🚀

---

## 🛠️ Tecnologias que eu curto usar

**Backend (meu forte):**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)

**Banco de Dados:**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

**Cloud & DevOps:**

![AWS](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

**Frontend (quando precisa):**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

**Ferramentas do dia a dia:**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=for-the-badge&logo=github&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Argo](https://img.shields.io/badge/Argo-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![VS Code](https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)

---

## 🏡 Projeto do qual tenho orgulho

### ArremateAI - Plataforma de Leilões de Imóveis

É uma plataforma completa de leilões de imóveis que construí do zero usando **arquitetura de microserviços**. O sistema tem autenticação com 2FA, gestão de vendedores PJ (com validação automática de CNPJ usando API da Receita Federal), processamento de imagem e vídeo, notificações por email... enfim, é bem completa!

Dá uma olhada nos microserviços:

<details>
<summary><b>📦 Os 7 Microserviços</b></summary>

<br>

| Serviço | Tecnologia Principal | O que faz | Repositório |
|---------|---------------------|-----------|-------------|
| **Gateway** | Spring Cloud Gateway | Porta de entrada - controla rate limiting, circuit breaker e roteamento | [Ver código](https://github.com/Quintanilha09/arremateai-gateway) |
| **Identity** | Spring Security + OAuth2 | Gerencia autenticação, 2FA, JWT e dispositivos confiáveis | [Ver código](https://github.com/Quintanilha09/arremateai-identity) |
| **Property Catalog** | Spring Data JPA | Catálogo de imóveis com busca avançada e filtros | [Ver código](https://github.com/Quintanilha09/arremateai-property-catalog) |
| **Vendor** | WebFlux + OpenFeign | Registro de vendedores PJ com validação de CNPJ | [Ver código](https://github.com/Quintanilha09/arremateai-vendor) |
| **UserProfile** | Spring Cache | Gerencia perfis, favoritos e configurações | [Ver código](https://github.com/Quintanilha09/arremateai-userprofile) |
| **Media** | AWS S3 + CloudFront | Realiza upload e processa imagens/vídeos | [Ver código](https://github.com/Quintanilha09/arremateai-media) |
| **Notification** | JavaMail + SQS | Envia notificações por email, push e in-app | [Ver código](https://github.com/Quintanilha09/arremateai-notification) |

</details>

<details>
<summary><b>🔧 Stack completa do projeto</b></summary>

<br>

- **Backend**: Java 17, Spring Boot 3.2.2
- **Segurança**: Spring Security 6, JWT, OAuth2 (Google/Facebook), 2FA
- **Banco**: PostgreSQL 16, Flyway para migrations
- **Cache**: Redis 7 (usado para perfis, favoritos, rate limiting)
- **Cloud**: AWS S3, CloudFront, SQS
- **Gateway**: Spring Cloud Gateway com Resilience4j (Circuit Breaker)
- **APIs Externas**: ReceitaWS (validação de CNPJ), ViaCEP
- **Email**: JavaMail + templates em Thymeleaf
- **DevOps**: Docker, Docker Compose, GitHub Actions
- **Frontend**: Next.js 14, TypeScript, TailwindCSS

</details>

<details>
<summary><b>✨ O que o sistema faz</b></summary>

<br>

- ✅ Sistema completo de autenticação (registro, login, 2FA, login social)
- ✅ Vendedores PJ com validação de CNPJ na API da Receita Federal
- ✅ CRUD de imóveis com busca avançada e filtros dinâmicos
- ✅ Sistema de leilões com lances em tempo real
- ✅ Upload de imagens (gera thumbnails, compressão) e vídeos
- ✅ Notificações por email, push e in-app com templates HTML
- ✅ Sistema de favoritos e configurações personalizadas
- ✅ Dispositivos confiáveis (dispensa 2FA por 30 dias)
- ✅ Rate limiting distribuído com Redis
- ✅ Circuit Breaker para resiliência

</details>

---

## 📊 Linguagens mais utilizadas

<div align="center">

![](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Quintanilha09&theme=tokyonight)
![](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Quintanilha09&theme=tokyonight)

</div>

---

## 💡 No que já trabalhei

**Desenvolvimento Backend:**
- APIs RESTful com Spring Boot
- Arquitetura de microserviços (como o ArremateAI mostrado acima)
- Integração com AWS (S3, SQS, CloudFront)
- Autenticação e autorização (JWT, OAuth2, 2FA)
- Banco de dados relacional e cache (PostgreSQL, Redis)

**DevOps e Cloud:**
- Docker e Docker Compose para containerização
- CI/CD com GitHub Actions
- Deploy na AWS
- Logs e monitoramento de sistemas distribuídos

**Boas Práticas:**
- Clean Code e princípios SOLID (levo isso a sério)
- Design Patterns (Factory, Strategy, Observer, etc.)
- TDD (Test-Driven Development)
- Code Review e Git Flow

---

## 🎓 Estudos e Certificações

🎯 **Java Developer** - Focado em Spring Framework  
📚 **Microservices Architecture** - Design e Implementação  
☁️ **AWS Cloud Practitioner** - Estudando (em andamento)

---

## 💼 Busco oportunidades como

Estou procurando oportunidades como:
- **Desenvolvedor Java Backend** (Pleno/Sênior)
- **Arquiteto de Microserviços**

---

## 📫 Onde me achar

💼 **LinkedIn**: [Gabriel Quintanilha](https://www.linkedin.com/in/gabriel-quintanilha-997360185/)  
📧 **Email**: gabriel.hemendinger@gmail.com  
📷 **Instagram**: [@gabriel_quintanilha09](https://www.instagram.com/gabriel_quintanilha09/)  
🐙 **GitHub**: Você já está aqui! 😄

---

<div align="center">
  
### 💭 *"Clean code always looks like it was written by someone who cares."* - Robert C. Martin

![](https://komarev.com/ghpvc/?username=Quintanilha09&color=blue&style=flat-square&label=Visitas+no+perfil)

</div>
