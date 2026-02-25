# 🚀 MultEdu: High-Performance Mental Arithmetic Engine

[![Stack](https://img.shields.io/badge/Stack-Next.js%2015%20|%20Supabase%20|%20TypeScript-blue)](https://github.com/MultEdu-educacao/multedu)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

O **MultEdu** é uma plataforma robusta de EdTech projetada para democratizar o aprendizado de aritmética avançada através da implementação digital do **Método Trachtenberg**. O foco do projeto é entregar uma experiência de alta performance, segura e escalável para dispositivos de baixo custo.

---

## 🏗️ System Architecture & Infrastructure

O projeto foi construído utilizando os pilares da engenharia de software moderna para garantir baixa latência e integridade de dados:

* **Backend-as-a-Service (BaaS):** Implementação completa via **Supabase**, utilizando PostgreSQL para persistência de dados e autenticação JWT.
* **Cloud Computing & Edge:** Deployment e CI/CD automatizados via **Vercel**, aproveitando Edge Functions para otimização de rotas.
* **Security & OpSec:** Aplicação de **Row Level Security (RLS)** em todas as tabelas, garantindo isolamento total entre usuários no nível de banco de dados.
* **Mobile-First Core:** UI desenvolvida com **React/Next.js**, otimizada para performance em conexões instáveis e hardware limitado.

---

## 🛠️ Key Technical Implementations

### 🔐 Authentication & Identity Management
Sistema de identidade resiliente integrado ao Supabase Auth, com fluxos de cadastro customizados e tratamento de estados de erro via Server Actions do Next.js.

### 📊 Data Modeling
Arquitetura de dados focada em escalabilidade:
* **Profiles:** Extensão do `auth.users` para gestão de XP, níveis e progresso gamificado.
* **Activity Tracking (Roadmap):** Registro detalhado de métricas de performance e tempo de resposta para análise pedagógica.

### ⚡ Infrastructure as Code (Flow)
O desenvolvimento segue um fluxo rigoroso de controle de versão:
1. Sincronização de base (`develop`).
2. Isolamento de funcionalidades em `feature branches`.
3. Revisão técnica via **Pull Requests**.
4. Deploy automático em ambiente de staging/produção.

---

## 👨‍💻 Engineering Team
O desenvolvimento deste core técnico é liderado por uma equipe de engenharia multidisciplinar da UNIVESP focada em performance e usabilidade:

* **Infra & Database:** Elizeu Figueiredo / Carlos Eduardo Januario / Paulo Moreira 
* **Frontend & UX:** Carlos Eduardo Vernizzi / Carlos Eduardo Januario / Rodrigo Rizzo
* **Management & Documentation:** Matheus Marques / Clint Walker / Paulo Roberto / Rodrigo Rizzo.

---
*Este é um projeto Open Source focado em impacto social através da tecnologia.*
