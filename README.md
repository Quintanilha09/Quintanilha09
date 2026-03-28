# 👋 Olá! Eu sou Gabriel Quintanilha

<div align="center">
  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/seu-perfil)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/seu-perfil)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:seu-email@gmail.com)

</div>

## 🚀 Sobre Mim

🔹 **Desenvolvedor Java** apaixonado por construir soluções escaláveis e robustas  
🔹 Especializado em **Spring Framework**, **Microserviços** e **Cloud Computing**  
🔹 Atualmente **procurando oportunidades** para aplicar minha expertise em projetos desafiadores  
🔹 Focado em **Clean Code**, **SOLID** e **Design Patterns**  
🔹 Entusiasta de **DevOps** e **CI/CD**

---

## 💻 Stack Tecnológico

### Backend & Frameworks
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)

### Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

### Cloud & DevOps
![AWS](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

### Frontend
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Tools & Others
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white)
![VS Code](https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)

---

## 🏆 Projeto em Destaque

### 🏡 ArremateAI - Plataforma de Leilões de Imóveis

> **Arquitetura de Microserviços** completa para leilões online de imóveis com sistema de autenticação, gestão de vendedores PJ e processamento de mídia.

<details>
<summary><b>📦 Microserviços & Repositórios</b></summary>

<br>

| Serviço | Tecnologia | Descrição | Repositório |
|---------|-----------|-----------|-------------|
| **Gateway** | Spring Cloud Gateway | API Gateway com rate limiting e circuit breaker | [📂 Ver Código](https://github.com/Quintanilha09/arremateai-gateway) |
| **Identity** | Spring Security + OAuth2 | Autenticação, 2FA, JWT, Trusted Devices | [📂 Ver Código](https://github.com/Quintanilha09/arremateai-identity) |
| **Property Catalog** | Spring Data JPA | Catálogo de imóveis com busca avançada | [📂 Ver Código](https://github.com/Quintanilha09/arremateai-property-catalog) |
| **Vendor** | WebFlux + OpenFeign | Registro de vendedores PJ com validação CNPJ | [📂 Ver Código](https://github.com/Quintanilha09/arremateai-vendor) |
| **UserProfile** | Spring Cache | Gerenciamento de perfis e favoritos | [📂 Ver Código](https://github.com/Quintanilha09/arremateai-userprofile) |
| **Media** | AWS S3 + CloudFront | Upload e processamento de imagens/vídeos | [📂 Ver Código](https://github.com/Quintanilha09/arremateai-media) |
| **Notification** | JavaMail + SQS | Sistema de notificações multi-canal | [📂 Ver Código](https://github.com/Quintanilha09/arremateai-notification) |

</details>

<details>
<summary><b>🛠️ Tecnologias Utilizadas</b></summary>

<br>

- **Backend**: Java 17, Spring Boot 3.2.2
- **Security**: Spring Security 6, JWT, OAuth2 (Google/Facebook), 2FA
- **Database**: PostgreSQL 16, Flyway Migrations
- **Cache**: Redis 7 (perfis, favoritos, rate limiting)
- **Cloud**: AWS S3, CloudFront CDN, SQS
- **Gateway**: Spring Cloud Gateway, Resilience4j (Circuit Breaker)
- **APIs Externas**: ReceitaWS (validação CNPJ), ViaCEP
- **Email**: JavaMail + Thymeleaf Templates
- **DevOps**: Docker, Docker Compose, GitHub Actions
- **Frontend**: Next.js 14, TypeScript, TailwindCSS

</details>

<details>
<summary><b>✨ Funcionalidades Principais</b></summary>

<br>

- ✅ **Autenticação Completa**: Registro, Login, 2FA, OAuth2 Social Login
- ✅ **Sistema de Vendedores PJ**: Validação CNPJ via API Receita Federal
- ✅ **Gestão de Imóveis**: CRUD completo com busca avançada e filtros dinâmicos
- ✅ **Sistema de Leilões**: Lances em tempo real, histórico de lances
- ✅ **Upload de Mídia**: Processamento de imagens (thumbnails, compressão) e vídeos
- ✅ **Notificações Multi-Canal**: Email, Push, In-App com templates HTML
- ✅ **Favoritos e Perfil**: Sistema de favoritos, configurações personalizadas
- ✅ **Trusted Devices**: Dispositivos confiáveis com 2FA bypass (30 dias)
- ✅ **Rate Limiting**: Controle de requisições distribuído com Redis
- ✅ **Circuit Breaker**: Resiliência com fallbacks automáticos

</details>

---

## 📊 GitHub Stats

<div align="center">
  
![Gabriel's GitHub stats](https://github-readme-stats.vercel.app/api?username=Quintanilha09&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Quintanilha09&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

</div>

---

## 🎯 Áreas de Interesse

```java
public class Desenvolvedor {
    private String nome = "Gabriel Quintanilha";
    private String[] especialidades = {
        "Microserviços",
        "Spring Boot",
        "Clean Architecture",
        "Design Patterns",
        "RESTful APIs",
        "Cloud Computing"
    };
    
    private String[] aprendendo = {
        "Kubernetes",
        "Event-Driven Architecture",
        "Apache Kafka",
        "GraphQL"
    };
    
    private String objetivo = "Construir sistemas escaláveis e resilientes";
}
```

---

## 📈 Experiência

### **Backend Development**
- Desenvolvimento de APIs RESTful com Spring Boot
- Implementação de arquitetura de microserviços
- Integração com serviços AWS (S3, SQS, CloudFront)
- Sistema de autenticação e autorização (JWT, OAuth2)
- Gestão de banco de dados (PostgreSQL, Redis)

### **DevOps & Cloud**
- Containerização com Docker e Docker Compose
- CI/CD com GitHub Actions
- Deploy em ambientes cloud (AWS)
- Monitoramento e logs distribuídos

### **Boas Práticas**
- Clean Code e SOLID principles
- Design Patterns (Factory, Strategy, Observer, etc.)
- TDD (Test-Driven Development)
- Code Review e Git Flow

---

## 🎓 Certificações & Educação

🎯 **Java Developer** - Foco em Spring Framework  
📚 **Microservices Architecture** - Design e Implementação  
☁️ **AWS Cloud Practitioner** - Em andamento  

---

## 💼 Procurando Oportunidades

Estou em busca de oportunidades como:
- **Desenvolvedor Java Backend** (Pleno/Sênior)
- **Arquiteto de Microserviços**
- **Full Stack Developer** (Java + React/Next.js)

---

## 📫 Como me Encontrar

💼 **LinkedIn**: [Gabriel Quintanilha](https://linkedin.com/in/seu-perfil)  
📧 **Email**: seu-email@gmail.com  
📷 **Instagram**: [@seu-perfil](https://instagram.com/seu-perfil)  
🐙 **GitHub**: [@Quintanilha09](https://github.com/Quintanilha09)

---

<div align="center">
  
### 💡 *"Clean code always looks like it was written by someone who cares."* - Robert C. Martin

![Profile Views](https://komarev.com/ghpvc/?username=Quintanilha09&color=brightgreen&style=flat-square)

</div>
