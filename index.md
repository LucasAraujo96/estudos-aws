---
title: "📘 Portfólio — Estudos AWS"
layout: default
---

<!-- ================================================
 🔹 HERO + VISUAL STYLING (compatível com GitHub Pages Architect)
 ================================================= -->
<style>
:root{
  --bg:#f6fafb;
  --grid:#eaf3f5;
  --panel:#ffffff;
  --text:#0f172a;
  --muted:#6b7280;
  --accent:#0ea5a4;
  --link:#0ea5a4;
  --radius:12px; --maxw:1100px;
}
body{
  background:
    linear-gradient(0deg, transparent 24%, rgba(0,0,0,0.03) 25%, rgba(0,0,0,0.03) 26%, transparent 27%, transparent 74%, rgba(0,0,0,0.03) 75%, rgba(0,0,0,0.03) 76%, transparent 77%),
    linear-gradient(90deg, transparent 24%, rgba(0,0,0,0.03) 25%, rgba(0,0,0,0.03) 26%, transparent 27%, transparent 74%, rgba(0,0,0,0.03) 75%, rgba(0,0,0,0.03) 76%, transparent 77%),
    var(--bg);
  background-size: 48px 48px, 48px 48px, auto;
  color: var(--text);
  font-family: "Segoe UI", system-ui, -apple-system, Roboto, sans-serif;
}
/* HERO */
.hero{
  max-width:var(--maxw); margin:28px auto; padding:28px; border-radius:var(--radius);
  background: linear-gradient(135deg, #ffffff, #f9ffff);
  border:1px solid #e5e7eb; box-shadow: 0 10px 24px rgba(2,6,23,0.06);
  display:grid; grid-template-columns:1fr 220px; gap:20px; align-items:center;
}
.hero h1{margin:0; font-size:2rem;}
.hero p{margin-top:8px; color:var(--muted)}
.avatar{
  width:220px;height:220px;border-radius:14px;
  background: radial-gradient(circle at 30% 30%, #0ea5a4, #22d3ee);
  display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700;font-size:1.1rem;
  box-shadow: 0 10px 26px rgba(2,6,23,0.12);
}
.btn{display:inline-block;padding:10px 14px;margin-top:12px;border-radius:8px;font-weight:600;text-decoration:none;color:#fff;background:#0ea5a4;}
.btn.secondary{background:transparent;color:#0f172a;border:1px solid #0ea5a4}
/* NOTA */
.note{background:#ffffff;border-left:4px solid var(--accent);color:#334155;padding:12px 14px;border-radius:8px;margin:12px 0}
/* TABELAS */
table{border-collapse:separate;border-spacing:0;width:100%;margin:12px 0;background:#fff;border:1px solid #e5e7eb;border-radius:10px;overflow:hidden;}
th{background:#0ea5a4;color:#fff;padding:10px;text-align:left;font-weight:700;}
td{padding:10px;border-top:1px solid #eef2f6;color:#0f172a;}
tr:nth-child(even) td{background:#f9fbfc}
a{color:var(--link)}
.footer{text-align:center;margin:40px auto 20px;color:#6b7280;font-size:0.9rem;}
@media(max-width:900px){ .hero{grid-template-columns:1fr;} }
</style>



<section class="hero">
  <div>
    <h1>📘 Portfólio — Estudos AWS</h1>
    <p><strong>Lucas Araujo</strong> · Catálogo de laboratórios, cursos e PoCs realizados no <em>AWS Skill Builder</em>.  
    Centraliza experiências práticas e aprendizados em arquitetura, observabilidade e FinOps.</p>
    <a href="#-2-laboratórios-aws-realizados" class="btn">📂 Ver Labs</a>
    <a href="#-5-próximos-estudos--pendências" class="btn secondary">📈 Próximos Estudos</a>
  </div>
  <div class="avatar">Lucas<br>Araujo</div>
</section>

<div class="note">
⚠️ <strong>Nota:</strong> Este portfólio contém apenas estudos e laboratórios públicos realizados na AWS Skill Builder.  
Nenhuma informação de clientes, credenciais ou ambientes privados é divulgada aqui.
</div>

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
