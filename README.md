## Estrutura do Repositório

### Pré-requisitos de instalação
- Git, Docker, AWS CLI, Azure CLI, Terraform, Ansible, kubectl, etc.

### 00. Fundamentos Essenciais
**Objetivo:** Dominar as ferramentas básicas necessárias para DevOps

#### Linux Essencial
- Navegação e manipulação de arquivos
- Permissões e usuários
- Processos e gerenciamento de recursos
  
#### Git Essencial
- Comandos fundamentais: clone, add, commit, push, pull
- Branches, merge e pull requests
- Tags e versionamento
- Automação com funções personalizadas

#### Vi Essencial
- Modos de edição
- Comandos básicos de navegação
- Busca e substituição

---

### 01. Containers com Docker
**Objetivo:** Containerizar aplicações e criar ambientes reproduzíveis

- Conceitos de imagens e containers
- Docker CLI completo (build, run, exec, logs, ps, stop, rm)
- Dockerfile multi-stage para otimização
- Docker Compose para orquestração local
- Push de imagens para Docker Hub
- **Labs práticos:**
  - Containerização de aplicação Node.js
  - Containerização de API FastAPI (Python)
  - Docker Compose com PostgreSQL
  - .gitignore para projetos Docker

---

### 02. Cloud Computing (AWS e Azure)
**Objetivo:** Provisionar recursos cloud via console e CLI

#### AWS
- Criação de instâncias EC2 (Ubuntu)
- Configuração de segurança (Security Groups)
- Elastic IP para IP fixo
- User data para automação de inicialização
- Buckets S3 com versionamento e políticas de segurança
- AWS CLI para automação

#### Azure
- Criação de VMs no Azure
- Configuração de NSG (Network Security Groups)
- Gerenciamento via Azure CLI

---

### 03. Automação CLI (AWS e Azure)
**Objetivo:** Automatizar tarefas com scripts e comandos CLI

- AWS CLI avançado
- Azure CLI avançado
- Scripts de automação para provisionamento
- Integração com pipelines

---

### 04. Terraform Essencial
**Objetivo:** Infraestrutura como Código (IaC) em AWS e Azure

- Conceitos de IaC e benefícios
- Estrutura de projeto Terraform (main.tf, variables.tf, outputs.tf, versions.tf)
- Providers AWS e Azure
- State remoto com Azure Storage
- Módulos reutilizáveis
- **Labs práticos:**
  - Provisionamento de VM no Azure
  - Criação de buckets S3 com políticas
  - Estrutura profissional de projetos Terraform

---
