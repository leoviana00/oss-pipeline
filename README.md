## 🥋 OSS-Pipeline: BJJ Progression & DevOps MasteryO 

OSS-Pipeline é uma aplicação Full Stack desenvolvida com Java Spring Boot projetada para gerenciar a jornada de atletas de Jiu-Jitsu (frequência, graduação de graus e faixas). O diferencial deste projeto não é apenas o CRUD, mas sua infraestrutura de "Faixa Preta", utilizando práticas avançadas de DevOps para garantir entrega contínua, segurança e observabilidade.

## 🎯 Objetivo do Projeto

Demonstrar a aplicação de conceitos de engenharia de software e cultura DevOps em um domínio de alta disciplina, traçando um paralelo entre a evolução de um faixa branca no tatame e a maturação de um código até a produção.

## 🏗️ Arquitetura do Sistem

A solução segue os princípios de Clean Architecture e Twelve-Factor App:

- API Layer: REST Controllers documentados com Swagger (OpenAPI).
- Business Layer: Serviços isolados para regras de graduação (ex: cálculo de carência para próximo grau).
- Infrastructure Layer: Dockerização multi-stage e orquestração via Kubernetes.
- CI/CD Pipeline: Automação completa desde o git push até o deploy.
- Security: Injeção de segredos e sensibilidade a dados (PII).

## 🛠️ Tecnologias Utilizadas

| Categoria | Tecnologia |
| ----- | ------------------------------ |
| Linguagem/Framework | "Java 21, Spring Boot 3.x" |
| Banco de Dados | "PostgreSQL (Relacional), Flyway (Migrations)" |
| Containers | "Docker, Docker Compose" |
| Orquestração | Kubernetes (K8s) |
| CI/CD | GitHub Actions / Azure DevOps |
| Segurança | HashiCorp Vault / Secrets Management |
| Observabilidade | "Micrometer, Prometheus e Grafana" |

🗺️ Roadmap de Implementação

- [ ] Fase 1: O Tatame (Setup)
    - [ ] Configuração do projeto Spring Initializr.
    - [ ] Dockerização da aplicação e banco de dados.
    
- [ ] Fase 2: A Técnica (Desenvolvimento)
    - [ ] Implementação do domínio de Atletas e Graduações.
    - [ ] Testes Unitários e de Integração (JUnit 5/Testcontainers).

- [ ] Fase 3: A Defesa (DevOps & Security)
    - [ ] Criação dos Manifestos Kubernetes (Deployment, Service, ConfigMap).
    - [ ] Configuração de Pipeline de CI (Build, Test, Scan de Vulnerabilidades).
    
- [ ] Fase 4: A Finalização (Observabilidade)
    - [ ] Dashboards de performance da aplicação no Grafana.
    
## 🚀 Como Executar o Projeto

### Pré-requisitos: 

Docker & Docker Compose instalado.JDK 21+.

### Passo a Passo

Clonar o repositório:Bashgit clone https://github.com/seu-usuario/oss-pipeline.git

1. Subir o ambiente via Docker Compose:

```bash
docker-compose up -d
```

2. Acessar a documentação da API:

Abra o navegador em: http://localhost:8080/swagger-ui.html

## 📈 Resultados Esperados

- Uma API resiliente capaz de gerenciar centenas de atletas.
- Pipeline de deploy 100% automatizado, reduzindo o erro humano.
- Ambiente monitorado que permite identificar gargalos de performance em tempo real.

## 🤝 Contribuição

Contribuições são o "sparring" do open source! Sinta-se à vontade para abrir uma Issue ou enviar um Pull Request.

## ⚖️ LicençaDistribuído sob a licença MIT. 

Veja LICENSE para mais informações.