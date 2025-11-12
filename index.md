<!-- ============================
  CUSTOM STYLES + HERO (paste after front matter)
  Works with GitHub Pages / jekyll-theme-architect
  ================================= -->
<style>
:root{
  --accent:#0ea5a4; /* teal-ish */
  --accent-2:#0f172a;
  --muted:#6b7280;
  --card-bg: #ffffff;
  --glass: rgba(255,255,255,0.06);
  --radius: 12px;
  --maxw: 1100px;
  --shadow: 0 8px 24px rgba(2,6,23,0.12);
  --glass-border: rgba(255,255,255,0.06);
}

body {
  background: linear-gradient(180deg, #fbfdff 0%, #f4fbfb 60%);
  color: #0f172a;
}

/* HERO */
.hero {
  max-width: var(--maxw);
  margin: 28px auto;
  padding: 28px;
  border-radius: var(--radius);
  background: linear-gradient(135deg, rgba(14,165,164,0.06), rgba(14,165,164,0.02));
  box-shadow: var(--shadow);
  display: grid;
  grid-template-columns: 1fr 260px;
  gap: 18px;
  align-items: center;
}
.hero h1 { margin:0; font-size: 1.9rem; letter-spacing: -0.5px; }
.hero p { margin:8px 0 0 0; color:var(--muted); font-size:0.98rem; }

/* avatar */
.hero .avatar {
  width: 220px; height: 220px; border-radius: 14px;
  background: linear-gradient(135deg,#0ea5a4,#0284c7);
  display:flex; align-items:center; justify-content:center;
  color:#fff; font-weight:700; font-size:1.05rem;
  box-shadow: 0 8px 30px rgba(2,6,23,0.12);
}

/* CTA buttons */
.cta-row { margin-top:14px; display:flex; gap:10px; align-items:center; }
.btn {
  display:inline-block; padding:10px 14px; border-radius:8px; font-weight:600;
  text-decoration:none; color:white; background:var(--accent); box-shadow:none;
}
.btn.secondary { background: transparent; color:var(--accent-2); border:1px solid rgba(15,23,42,0.06); }

/* cards grid */
.cards { max-width: var(--maxw); margin: 18px auto; display:grid; grid-template-columns: repeat(3,1fr); gap:14px; }
@media (max-width:1000px){ .hero { grid-template-columns:1fr; } .cards { grid-template-columns: repeat(2,1fr);} }
@media (max-width:700px){ .cards { grid-template-columns: 1fr;} }

/* card */
.card { background: white; border-radius:12px; padding:14px; box-shadow: 0 6px 18px rgba(15,23,42,0.06); border:1px solid rgba(15,23,42,0.03); }
.card h3{margin:0 0 8px 0; font-size:1.05rem}
.card p{margin:0;color:var(--muted);font-size:0.92rem}

/* tables */
table { border-collapse: collapse; width:100%; border-radius:8px; overflow:hidden; }
table th { text-align:left; padding:10px; background:#0ea5a4; color:#fff; font-weight:600; }
table td { padding:10px; border-bottom: 1px solid #f3f4f6; font-size:0.95rem; color: #0f172a; }
table tr:nth-child(even) td { background: #fbfdff; }

/* TOC sticky */
.toc-wrap{ position: sticky; top:18px; align-self:start; }

/* callouts */
.callout { background: #f8fafc; border-left:4px solid var(--accent); padding:12px 14px; border-radius:8px; color:var(--muted); margin:12px 0; }

/* footer */
.site-footer { max-width:var(--maxw); margin:30px auto; padding:18px; color:var(--muted); text-align:center; font-size:0.95rem; }
</style>

<!-- HERO -->
<section class="hero">
  <div>
    <h1>📘 Catálogo Vivo — Estudos AWS</h1>
    <p><strong>Lucas Gabriel Santos Araujo</strong> · Repositório de labs, PoCs e trilhas AWS (Skill Builder). Centralize, consulte e publique seu aprendizado.</p>

    <div class="cta-row">
      <a class="btn" href="#-2-laboratórios-aws-realizados">Ver Labs</a>
      <a class="btn secondary" href="https://github.com/<seu-usuario>/estudos-aws" target="_blank">Abrir repositório</a>
      <a class="btn secondary" href="#-5-próximos-estudos--pendências">Próximos estudos</a>
    </div>

    <div style="margin-top:12px">
      <!-- shields: exemplo (altere as urls) -->
      <img src="https://img.shields.io/badge/Labs-40-blue?style=flat-square" alt="labs" />
      <img src="https://img.shields.io/badge/Lang-English-lightgrey?style=flat-square" alt="lang" />
      <img src="https://img.shields.io/badge/Platform-AWS-orange?style=flat-square" alt="aws" />
    </div>
  </div>

  <div style="display:flex;flex-direction:column;gap:12px;align-items:center;">
    <!-- Coloque um avatar em assets/avatar.png ou substitua texto -->
    <div class="avatar">
      Lucas<br/>Araujo
    </div>
    <div style="width:100%; text-align:center; font-size:0.92rem; color:var(--muted);">
      Publicado com GitHub Pages · Tema: Architect
    </div>
  </div>
</section>

<!-- CARDS -->
<div class="cards">
  <div class="card">
    <h3>📚 Labs & Cursos</h3>
    <p>Lista completa de Builder Labs, cursos e planos de estudo — prontos para consulta rápida.</p>
  </div>
  <div class="card">
    <h3>🔭 Projetos & PoCs</h3>
    <p>Arquiteturas, migrações e integrações (ex: Zabbix, CloudFront, Aurora) com anotações práticas.</p>
  </div>
  <div class="card">
    <h3>🧭 FinOps & Observability</h3>
    <p>Dicas de otimização de custos, caching e monitoramento com CloudWatch, Grafana e Zabbix.</p>
  </div>
</div>

<!-- small callout -->
<div style="max-width:var(--maxw); margin:12px auto;">
  <div class="callout">
    ⚠️ <strong>Nota:</strong> Os links para AWS Skill Builder exigem login AWS. Os conteúdos listados são para fins educacionais.
  </div>
</div>


---
title: "📘 Portifolio — Estudos AWS"
layout: default
---

> ⚠️ *Nota:* Este catálogo contém apenas estudos e laboratórios públicos realizados na AWS Skill Builder.  
> Nenhuma informação de clientes, credenciais ou ambientes privados é divulgada aqui.

# 📘 Portifolio — Estudos AWS

**Autor:** Lucas Araujo  
**Início:** 2025  
**Objetivo:** Centralizar os estudos práticos, laboratórios e projetos realizados na AWS, servindo como repositório de conhecimento pessoal e técnico para futuras consultas e reaproveitamento em projetos reais.

---

## 📑 Table of Contents
- [1. Visão Geral](#-1-visão-geral)
- [2. Laboratórios AWS Realizados](#-2-laboratórios-aws-realizados)
  - [2.1 Builder Labs (Práticos)](#-21-builder-labs-práticos)
  - [2.2 Cursos Digitais (Conceituais)](#-22-cursos-digitais-conceituais)
  - [2.3 Planos de Aprendizado](#-23-planos-de-aprendizado)
- [3. Projetos e PoCs Realizados](#-3-projetos-e-pocs-realizados)
- [4. Conceitos Importantes Estudados](#-4-conceitos-importantes-estudados)
- [5. Próximos Estudos / Pendências](#-5-próximos-estudos--pendências)
- [6. Ferramentas e Referências](#-6-ferramentas-e-referências)

---

## 🧭 1. Visão Geral
O projeto **Estudos AWS** reúne laboratórios práticos, PoCs e comparativos entre serviços AWS, com foco em arquitetura, observabilidade e otimização de custos.  
A metodologia aplicada combina experimentação em ambientes de laboratório (Skill Builder) com análise de casos reais e boas práticas de arquitetura em nuvem.

---

## ☁️ 2. Laboratórios AWS Realizados
### 🧪 2.1 Builder Labs (Práticos)

| Data | Nome do Laboratório | Nível | Duração | Idioma | Foco Técnico |
|------|----------------------|--------|----------|----------|---------------|
| 12/11/2025 | **.NET Workloads on AWS Lambda** | Intermediário | 1h | English | Deploy de aplicações .NET em ambiente serverless via AWS Lambda e API Gateway. |
| 11/11/2025 | **Building with Amazon Aurora Databases** | Intermediário | 1h | English | Criação e gerenciamento de clusters Aurora com réplicas de leitura. |
| 11/11/2025 | **Building with Amazon RDS Databases** | Intermediário | 1h | English | Configuração de instâncias RDS e parâmetros de banco gerenciado. |
| 10/11/2025 | **Building VPC, S3, EC2, and RDS Products with AWS Service Catalog** | Fundamental | 2h | English | Criação de produtos AWS via Service Catalog usando CloudFormation. |
| 10/11/2025 | **Migrating RDS MySQL to Aurora with Read Replica** | Intermediário | 1h30 | English | Migração de instância RDS para cluster Aurora com failover automático. |
| 06/11/2025 | **Maintaining High Availability with Auto Scaling (for Linux)** | Intermediário | 2h | English | Configuração de Auto Scaling Groups com balanceamento e HA. |
| 06/11/2025 | **Introduction to Amazon EC2 Auto Scaling** | Fundamental | 45min | English | Fundamentos do Auto Scaling e políticas de escalabilidade automática. |
| 06/11/2025 | **Walkthrough of the AWS Well-Architected Tool** | Fundamental | 30min | English | Uso do Well-Architected Tool para análise e boas práticas de workloads. |
| 05/11/2025 | **Performing a Basic Audit of your AWS Environment** | Fundamental | 1h | English | Auditoria de segurança com IAM, Config, CloudTrail e CloudWatch. |
| 05/11/2025 | **Role Assumption Challenge** | Avançado | 2h | English | Criação e teste de roles IAM e uso de `sts:assume-role` via CLI. |
| 04/11/2025 | **Comparing Amazon VPC Peering and AWS Transit Gateway** | Intermediário | 3h | English | Comparativo entre VPC Peering e TGW para interconexão de redes. |
| 04/11/2025 | **Working with Elastic Load Balancing** | Fundamental | 1h | English | Configuração de balanceadores de carga e health checks em EC2. |
| 04/11/2025 | **Caching Static Files with Amazon CloudFront** | Intermediário | 2h | English | Configuração de CloudFront para entrega global de conteúdo estático. |
| 03/11/2025 | **Configuring and Deploying Amazon VPC for a 3-tier Web App** | Intermediário | 1h30 | English | Criação de topologia 3-tier (Web/App/DB) com subnets públicas e privadas. |
| 03/11/2025 | **Introduction to AWS Identity and Access Management (IAM)** | Fundamental | 45min | English | Criação de usuários, políticas e permissões IAM. |
| 03/11/2025 | **Introduction to AWS Key Management Service (KMS)** | Fundamental | 1h | English | Uso de chaves gerenciadas (CMK) para criptografia de dados em AWS. |
| 03/11/2025 | **Introduction to Elastic Load Balancing** | Fundamental | 1h | English | Fundamentos de balanceamento e disponibilidade de aplicações. |
| 03/11/2025 | **Introduction to Amazon CloudFront** | Fundamental | 1h | English | Fundamentos de CDN, caching e distribuição segura de conteúdo. |
| 29/10/2025 | **AWS Network Firewall for Ingress/Egress Traffic** | Avançado | 1h30 | English | Implementação de AWS Network Firewall para controle de tráfego. |
| 29/10/2025 | **Collecting and Analyzing Logs with Amazon CloudWatch Logs Insights** | Intermediário | 1h30 | English | Consulta e análise de logs de aplicações via CloudWatch Logs Insights. |
| 21/10/2025 | **Building and Deploying Containers Using Amazon ECS** | Fundamental | 1h30 | English | Deploy de containers ECS com task definitions e services. |
| 21/10/2025 | **Working with Amazon Elastic Container Service (ECS)** | Fundamental | 1h | English | Gerenciamento de tasks e services no ECS. |
| 20/10/2025 | **A Day in the Life of a Data Engineer** | Intermediário | 1h | English | Pipeline de ingestão e transformação de dados usando Glue e Athena. |
| 15/10/2025 | **Building and Deploying a Containerized Application with Amazon EKS** | Intermediário | 1h | English | Deploy de aplicação containerizada em cluster Kubernetes (EKS). |
| 02/10/2025 | **Migrating On-Premises NFS Using AWS DataSync and AWS Storage Gateway** | Avançado | 1h15 | English | Migração de dados on-premises via DataSync e Storage Gateway. |
| 06/10/2025 | **Lab - Configure DNS and Routing Policies with Amazon Route 53** | Fundamental | 1h | English | Configuração de DNS e políticas de roteamento (latência, failover). |
| 03/11/2025 | **Auditing Your Security with AWS Trusted Advisor** | Intermediário | 1h30 | English | Uso do Trusted Advisor para revisão de segurança e custo. |

---

### 🎓 2.2 Cursos Digitais (Conceituais)

| Data | Nome do Curso | Nível | Duração | Idioma | Foco Técnico |
|------|----------------|--------|----------|----------|---------------|
| 29/09/2025 | **Amazon CloudWatch Getting Started** | Fundamental | 1h | English | Introdução à coleta e visualização de métricas de recursos AWS. |
| 20/10/2025 | **Amazon ECS Getting Started** | Fundamental | 1h | English | Fundamentos do ECS, clusters e definição de tasks. |
| 08/10/2025 | **Amazon EKS Anywhere Getting Started** | Fundamental | 1h | English | Instalação e operação de EKS Anywhere em ambientes híbridos. |
| 08/10/2025 | **Amazon EKS Primer** | Intermediário | 1h15 | English | Fundamentos do Kubernetes gerenciado com EKS. |
| 20/10/2025 | **Amazon Elastic Kubernetes Service (EKS) - Troubleshooting** | Avançado | 1h | English | Diagnóstico e solução de problemas em clusters EKS. |
| 25/09/2025 | **Amazon VPC Networking Basics** | Intermediário | 2h | English | Criação de VPCs, subnets, gateways e route tables. |
| 17/09/2025 | **Amazon Web Services ProServe 101** | Fundamental | 45min | English | Introdução à metodologia de entrega profissional AWS ProServe. |
| 07/10/2025 | **AWS Backup Primer** | Intermediário | 1h10 | English | Fundamentos de backup e restauração com AWS Backup. |
| 02/10/2025 | **AWS Database Migration Service (DMS) Getting Started** | Fundamental | 1h | English | Configuração de migrações entre bancos com o DMS. |
| 01/10/2025 | **AWS DataSync Primer** | Intermediário | 1h05 | English | Transferência eficiente de dados on-premises para AWS. |
| 17/09/2025 | **AWS Engagement Security Training for Partners - 2025** | Intermediário | 1h | English | Boas práticas de segurança para parceiros AWS. |
| 27/10/2025 | **AWS Fargate Getting Started** | Fundamental | 1h | English | Execução de containers sem servidor via Fargate. |
| 01/10/2025 | **AWS Network Connectivity Options** | Intermediário | 2h30 | English | Comparativo de Direct Connect, VPN e Transit Gateway. |
| 07/10/2025 | **AWS Network – Monitoring and Troubleshooting** | Intermediário | 1h | English | Monitoramento e diagnóstico de conectividade AWS. |
| 26/09/2025 | **AWS Organizations Getting Started** | Fundamental | 1h | English | Criação e gestão de múltiplas contas com AWS Organizations. |
| 17/09/2025 | **AWS Partner: Well-Architected Best Practices (Technical)** | Intermediário | 2h | English | Boas práticas do framework Well-Architected para parceiros. |
| 30/09/2025 | **Build, Secure, and Monitor Networks on AWS** | Fundamental | 2h | English | Princípios de design seguro e monitoramento de redes AWS. |
| 20/10/2025 | **Building Enterprise Architectures in Amazon ECS** | Avançado | 1h30 | English | Design de arquiteturas corporativas com ECS e Fargate. |
| 23/10/2025 | **Getting Started with Amazon ECR** | Fundamental | 30min | English | Uso do Elastic Container Registry para imagens Docker. |
| 06/10/2025 | **Getting Started with AWS CloudFormation** | Fundamental | 20min | English | Introdução a infraestrutura como código (IaC) na AWS. |
| 29/09/2025 | **Landing Zone Accelerator on AWS (LZA)** | Intermediário | 1h06 | English | Estruturação de landing zones seguras e escaláveis. |
| 29/10/2025 | **Managing Applications at Scale with Amazon ECS** | Avançado | 1h30 | English | Escalabilidade e ciclo de vida de aplicações ECS. |
| 22/10/2025 | **Managing the Application Lifecycle in Amazon ECS** | Avançado | 1h30 | English | Estratégias de CI/CD e gerenciamento contínuo em ECS. |
| 02/10/2025 | **Moving to the Cloud with Amazon FSx** | Intermediário | 1h | English | Introdução à migração e uso de sistemas de arquivos gerenciados. |
| 22/10/2025 | **Observing, Troubleshooting, and Optimizing Workloads Running on Amazon ECS** | Avançado | 1h30 | English | Observabilidade e otimização de workloads ECS. |
| 26/09/2025 | **Understanding the Multi-Account Strategy** | Intermediário | 30min | English | Estratégia de múltiplas contas para isolamento e governança. |
| 17/09/2025 | **Introduction to the AWS Cloud Adoption Framework (CAF)** | Fundamental | 45min | English | Estrutura de adoção de nuvem e pilares CAF. |

---

### 🗂️ 2.3 Planos de Aprendizado

| Nome do Plano | Nível | Duração | Foco Técnico |
|----------------|--------|----------|---------------|
| **Cloud to AWS Migrations Learning Plan (includes labs)** | Avançado | 6h50 | Estratégias de migração de workloads on-premises para AWS. |
| **Partner Shared Delivery - Onboarding Learning Plan (Partner)** | Intermediário | 4h30 | Treinamento de parceiros para entregas colaborativas AWS. |

---

## 🧱 3. Projetos e PoCs Realizados
*(Mantido igual à versão anterior, com adições futuras conforme evolução dos projetos)*

---

## 🔍 4. Conceitos Importantes Estudados
*(Mantido conforme o modelo anterior)*

---

## 🧩 5. Próximos Estudos / Pendências
*(Mantido conforme o modelo anterior, com adição futura de novas metas)*

---

## 🧰 6. Ferramentas e Referências
- AWS Skill Builder  
- AWS Documentation  
- AWS Architecture Center  
- AWS Well-Architected Framework  
- FinOps Foundation Labs  
- Projetos práticos e PoCs reais

---
