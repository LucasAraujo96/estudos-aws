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
.btn:focus-visible{outline:2px solid #111827; outline-offset:2px}
.badges{margin-top:10px;display:flex;flex-wrap:wrap;gap:8px}
.badges span{font-size:12px;background:#eef2f6;border:1px solid #e5e7eb;border-radius:999px;padding:6px 10px;color:#0f172a}
/* NOTA */
.note{background:#ffffff;border-left:4px solid var(--accent);color:#1f2937;padding:12px 14px;border-radius:8px;margin:12px 0}
/* TABELAS */
table{border-collapse:separate;border-spacing:0;width:100%;margin:12px 0;background:#fff;border:1px solid #e5e7eb;border-radius:10px;overflow:hidden;}
th{background:#0ea5a4;color:#fff;padding:10px;text-align:left;font-weight:700;}
td{padding:10px;border-top:1px solid #eef2f6;color:#0f172a;}
tr:nth-child(even) td{background:#f9fbfc}
a{color:var(--link)}
a:focus-visible{outline:2px solid #111827; outline-offset:2px}
.footer{text-align:center;margin:40px auto 20px;color:#6b7280;font-size:0.9rem;}
@media(max-width:900px){ .hero{grid-template-columns:1fr;} }
</style>



<section class="hero">
  <div>
    <h1>📘 Portfólio — Estudos AWS</h1>
    <p><strong>Lucas Araujo</strong> · Catálogo de laboratórios, cursos e PoCs realizados no <em>AWS Skill Builder</em>.
    Centraliza experiências práticas e aprendizados em arquitetura, observabilidade e FinOps.</p>
    <a href="#labs" class="btn" aria-label="Ir para a lista de Laboratórios AWS">📂 Ver Labs</a>
    <a href="#proximos" class="btn secondary" aria-label="Ir para Próximos Estudos">📈 Próximos Estudos</a>
    <div class="badges" aria-label="Principais temas">
      <span>AWS</span><span>Serverless</span><span>FinOps</span><span>Observability</span><span>Networking</span>
    </div>
  </div>
  <div class="avatar" role="img" aria-label="Avatar estilizado de Lucas Araujo" title="Lucas Araujo">Lucas<br>Araujo</div>
</section>

<div class="note" role="note" aria-label="Nota sobre confidencialidade">
⚠️ <strong>Nota:</strong> Este portfólio contém apenas estudos e laboratórios públicos realizados na AWS Skill Builder.  
Nenhuma informação de clientes, credenciais ou ambientes privados é divulgada aqui.
</div>

---

## 📑 Table of Contents
- [1. Visão Geral](#visao-geral)
- [2. Laboratórios AWS Realizados](#labs)
  - [2.1 Builder Labs (Práticos)](#labs-builder)
  - [2.2 Cursos Digitais (Conceituais)](#labs-cursos)
  - [2.3 Planos de Aprendizado](#labs-planos)
- [3. Projetos e PoCs Realizados](#pocs)
- [4. Conceitos Importantes Estudados](#conceitos)
- [5. Próximos Estudos / Pendências](#proximos)
- [6. Ferramentas e Referências](#refs)

---

## 🧭 1. Visão Geral {#visao-geral}
O projeto **Estudos AWS** reúne laboratórios práticos, PoCs e comparativos entre serviços AWS, com foco em arquitetura, observabilidade e otimização de custos.  
A metodologia aplicada combina experimentação em ambientes de laboratório (Skill Builder) com análise de casos reais e boas práticas de arquitetura em nuvem.

---

## ☁️ 2. Laboratórios AWS Realizados {#labs}
### 🧪 2.1 Builder Labs (Práticos) {#labs-builder}

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

### 🎓 2.2 Cursos Digitais (Conceituais) {#labs-cursos}

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

### 🗂️ 2.3 Planos de Aprendizado {#labs-planos}

| Nome do Plano | Nível | Duração | Foco Técnico |
|----------------|--------|----------|---------------|
| **Cloud to AWS Migrations Learning Plan (includes labs)** | Avançado | 6h50 | Estratégias de migração de workloads on-premises para AWS. |
| **Partner Shared Delivery - Onboarding Learning Plan (Partner)** | Intermediário | 4h30 | Treinamento de parceiros para entregas colaborativas AWS. |

---

## 🧱 3. Projetos e PoCs Realizados {#pocs}
### 3.1 Plataforma EdTech — Aulas ao Vivo (BigBlueButton) em AWS

> **Resumo:** Implantação de BigBlueButton (videoconferência educacional) com balanceamento, camadas de segurança e observabilidade, priorizando estabilidade nas aulas e gravações.

**Objetivos**
- Aulas ao vivo estáveis para turmas simultâneas.
- Gravações acessíveis sob demanda.
- Camada WAF + TLS end-to-end.
- Operação simples (runbook + alarmes).

**Stack principal**
- **Rede:** VPC (subnets públicas/privadas), NAT, SGs.
- **Fronteira:** Route 53 (DNS), ACM (TLS), **AWS WAF**.
- **Tráfego:** **ALB** (HTTP/2 + WebSocket).
- **Compute:** **EC2** (pool BBB).
- **Banco:** **Amazon RDS** (MySQL) – metadados/sessões.
- **Armazenamento:** **S3** (gravações), ciclo de vida/Intelligent-Tiering.
- **Observabilidade:** CloudWatch (métricas/logs), Alarmes, Dashboards.

### 3.2 FinOps — CloudFront (Overview Anônimo)

> **Contexto:** algumas distribuições de CDN consumiam **~30 TB/mês**. O objetivo foi reduzir custo de transferência e requisições ao origin **apenas com ajustes de cache e políticas**, sem alterar a aplicação.

**Diagnóstico inicial**
- Levantamento no **CloudWatch/CloudFront** (Requests, **BytesDownloadedFromOrigin**, CacheHitRate).
- **Ranking por consumo** para priorização: **Top 5 distribuições** somavam **~100 TB/mês** de tráfego.
- Amostragem de **status de cache** (Hit/Miss/Expired) e análise por **behavior** (HTML x estáticos).
- Habilitação/validação de **Standard Logs** em S3 e consultas exploratórias em **Athena**.

**Ações implementadas**
- **Readequação de Policies**
  - Separação por tipo de conteúdo (**behaviors**):
    - **HTML**: cache curto ou desabilitado; respeita `Cache-Control` do origin.
    - **Estáticos versionados** (CSS/JS/IMG, `/assets/*`): **cache longo** (dias/semanas).
  - Remoção de variáveis que quebravam cache em estáticos:
    - **Query strings / Cookies / Headers** → **None/Whitelist mínimo**.
- **TTL de Estáticos**
  - `min=1h`, `default=7d`, `max=30d` (ajustado conforme criticidade).
  - Adoção/validação de **file name hashing** (`app.8f2a.js`) para evitar invalidações amplas.
- **Logs e Observabilidade**
  - **Standard Logs** habilitados em S3 para todas as distribuições.
  - **Athena** configurado para consultas (top paths, user-agents, geo, cache status).
  - Painel de métricas (CloudFront/CloudWatch): `CacheHitRate`, `BytesFromOrigin`, `Requests`, `4xx/5xx`, `OriginLatency`.
  - **Real-Time Logs** ativado **temporariamente** nas distribuições com maior custo para diagnóstico fino (gera alto volume e custo, usar por janelas curtas).

**Resultados (baseline esperado)**
- **Cache Hit Rate (estáticos)**: +**10–25 pp** sobre o valor inicial.
- **BytesDownloadedFromOrigin**: queda **significativa** (correlacionada ao aumento de TTL e eliminação de variações).
- **Invalidations**: redução relevante após versionamento por hash.
- **Tempo de carregamento**: melhora perceptível para usuários (mais hits na borda).

> **Nota:** todos os dados foram analisados de forma agregada e **sem identificação de clientes** ou IDs de distribuição.

---

## 🔍 4. Conceitos Importantes Estudados {#conceitos}

### Amazon Aurora (MySQL/PostgreSQL-compatible)
- **Arquitetura:** storage distribuído (6 cópias em 3 AZs) e compute separado do storage.  
- **Failover:** promoção automática de *reader* para *writer* (tipicamente dezenas de segundos) com **failover tiers**.  
- **Escala de leitura:** até **15 Aurora Replicas**. **Endpoints:** *cluster* (RW), *reader* (R), *custom* (subset).  
- **Backups & Restauração:** **PITR** contínuo + snapshots autom./manuais.  
- **Serverless v2:** escala por **ACUs** em tempo real (carga variável).  
- **Global Database:** replicação *cross-region* de baixa latência (DR/leitura global).  
- **Segurança:** VPC, **KMS**, **IAM DB Auth**, **TLS**, *parameter/option groups*.  
- **Boas práticas:** relatórios pesados no **reader endpoint**; monitorar **CPU**, **FreeableMemory**, **BufferCacheHitRatio**, **Deadlocks**, **ReplicaLag**.

### AWS Lambda (Serverless Compute)
- **Cobrança:** por **invocações + duração (ms)** e memória configurada.  
- **Escala automática:** eventos (S3, API Gateway, SQS, EventBridge…).  
- **Concorrência:** gerenciada; **reserved/provisioned concurrency** para latência estável.  
- **Rede:** execução em **VPC** quando precisa acessar recursos privados (networking atual é baseado em Hyperplane, com criação elástica de ENIs).  
- **Observabilidade:** CloudWatch Logs/Metrics, **X-Ray**; idempotência para reprocessos.  
- **Boas práticas:** funções pequenas e focadas; mitigar *cold start* com **provisioned concurrency**; usar **SQS** para suavizar picos.

### S3 + CloudFront (Site Estático & Distribuição Global)
- **S3:** *static hosting* ou acesso privado via **OAC (Origin Access Control)**.  
- **CloudFront:** CDN com **TTL**, *cache policies*, compressão (Gzip/Brotli), HTTP/2/3, TLS (ACM).  
- **Segurança:** bloquear acesso direto ao bucket (OAC), **AWS WAF** opcional, *signed URLs/cookies*.  
- **Custos:** egress mais barato via CloudFront; invalidações cobram após franquia.  
- **Boas práticas:** versionar assets (*cache-busting*); TTL alto para estáticos e baixo/sem cache para HTML.

**Notas de implementação (OAC + SPA)**
- Se usar **OAC**, configure a origem do CloudFront para o **endpoint REST do S3** (não o *Static Website Hosting*).  
- Para **SPAs/rotas amigáveis**, use **Custom Error Responses** no CloudFront: mapear **403/404 → /index.html** retornando **200** (e ajuste TTL de erros).  
- Caso precise do website endpoint (redireção/index automático), não use OAC; em vez disso, controle acesso por políticas públicas restritas + WAF.

### Data Lake no S3 + Glue + Athena + Lambda
- **Arquitetura-base:** dados brutos em **S3 (bronze)** → transformação com **AWS Glue (ETL)** → dados curados **Parquet/Partitioned (silver/gold)** → **AWS Glue Data Catalog** como metastore → **Athena** para SQL *serverless* → **Lambda** consumindo resultados/eventos.
- **Formato & desempenho:** converter **CSV → Parquet** e **compactar (Snappy/Zstd)** reduz custo de leitura no Athena e acelera consultas.
- **Particionamento:** pastas por **ano=AAAA/mês=MM/dia=DD** (ou por *business key*). Evite **milhares de arquivos pequenos** (*small files problem*); use **coalesce/repartition** no ETL.
- **Catálogo & Crawler:** use **Glue Crawler** para inferir schema rapidamente, mas **congele schema** em produção (evolução controlada, compatibilidade).
- **Athena:** prefira **CTAS/INSERT INTO** para materializar consultas; ative **result reuse** e controle **workgroup** com limites de gasto.
- **Eventos & orquestração:** **EventBridge** para agendar ETLs (ex.: a cada 15 min) e acionar **Lambda** pós‑gravação no S3 (**S3 Event Notifications**). Para **atualizações esporádicas** (apenas para manter dados e painéis atualizados), é possível **executar cargas on‑demand** sem agendamento e, quando necessário, alternar para **coletas periódicas** no data lake.
- **Segurança:** **KMS** (SSE-KMS) nos buckets, **Lake Formation** para permissões coluna/tabela, **IAM least privilege**, **VPC endpoints** (S3/Glue).
- **Observabilidade & qualidade:** **CloudWatch Logs/Metrics** para Glue/Lambda, **Athena Query Metrics**, validação com **Deequ/Great Expectations** (opcional).
- **FinOps:** particione bem (filtrar por partições!), **Parquet + projeção de partições** no Athena, **S3 Lifecycle** para arquivar camadas antigas (IA/Glacier).

**Padrões práticos do seu lab**
- Pipeline **CSV → Parquet** no Glue com **partitioning por data** e catálogo no **Glue Data Catalog**.
- **Athena** consultando a camada curada e **Lambda** consumindo resultados/arquivos para *post‑processing* (ex.: publicação em API, notificações ou carga em banco).
- No lab, as cargas foram **on‑demand (sem agendamento)** para atualizar **dados e painéis** quando necessário; **existe a possibilidade** de adotar **coletas periódicas** (ex.: a cada 15 min com EventBridge) conforme a necessidade de atualização.
- 
### CI/CD para ECS — CodePipeline + CodeBuild + ECR (+ Lambda)
- **Arquitetura do lab:** *Dev push* → **CodeCommit/GitHub** → **CodePipeline** (gatilho) → **CodeBuild** (build/teste, `docker build` + `docker push` p/ **Amazon ECR**) → **Implantação no ECS** (service Fargate/EC2). **Lambda** usado como etapa custom (ex.: pós‑deploy, version tag, invalidação de cache/aviso).
- **Fluxo detalhado:**
1. **Source**: repositório (`main`/`develop`) com *webhook*.
2. **Build (CodeBuild)**: usa `buildspec.yml` para: *lint/test*, *build image*, *login ECR*, *tag (commit SHA/semver)* e *push*.
3. **Image Registry (ECR)**: repositório versionado, **image scanning** ativada, *lifecycle policy* para limpar imagens antigas.
4. **Deploy (ECS)**: atualização do **task definition** com `image: <account>.dkr.ecr...:<tag>` e **service** com *rolling update* ou **Blue/Green** (via **CodeDeploy for ECS**, opcional).
5. **Pós‑deploy (Lambda/Step Functions)**: validações, *smoke tests*, *notify* (SNS/Slack), *feature flags* e ações auxiliares (ex.: migração de schema segura).
- **buildspec.yml (dicas):** use *phases* (`install/build/post_build`), *env vars* do **Parameter Store/Secrets Manager**, e **cache** para dependências. Publique *artifacts* mínimos (manifesto/`imagedefinitions.json` quando usar CodeDeploy ECS).
- **Segurança & IAM:** *least‑privilege* por estágio; **ECR** com política de push/pull restrita; **KMS** p/ segredos; **VPC endpoints** p/ ECS/ECR/Logs em ambientes privados.
- **Confiabilidade:** **health checks** no ALB, *rollback automático* via CodeDeploy (Blue/Green com *test listener* + *alarms* no CloudWatch).
- **Observabilidade:** logs do **CodeBuild** no CloudWatch, **ECS Exec** para diagnóstico, **X-Ray** opcional; métricas de *deployment* no CodeDeploy/CloudWatch.
- **FinOps:** use **Fargate Spot** quando possível, **lifecycle ECR**, *build compute type* adequado no CodeBuild, e *build minutes* otimizados (cache e camadas Docker).
- **Extensões úteis:** *Manual Approval* no CodePipeline entre *stages*, **multi‑account** (assume‑role) para promover `dev → hml → prd`, e *gates* de qualidade (SAST/scan de imagem) antes do deploy.


**Padrões práticos do seu lab**
- Repositório com `Dockerfile` e `buildspec.yml` padronizados.
- **Tagging** por `git commit SHA` e por **semver** (ex.: `v1.3.2`), ambos enviados ao ECR.
- Atualização automática do **task definition** e *rolling update* do **ECS service** com **min/max percent** seguros.
- Etapa **Lambda** para pós‑deploy (ex.: notificação e invalidação controlada), mantendo pipeline idempotente.

### Auto Scaling (EC2/ECS)
- **ASG:** define **min/desired/max** com políticas **target tracking**, **step** e **scheduled**.  
- **Disparo por métricas:** **CPU**, **ALB RequestCount**, **SQS QueueLength**, métricas custom.  
- **Health checks:** EC2/ELB; **termination policies**; **warm pools** para reduzir *cold start*.  
- **Integração com ELB:** ALB/NLB distribuem tráfego para instâncias do ASG.  
- **Boas práticas:** **launch templates** imutáveis; *user data* idempotente; AMI *baked*; **grace period**/**cooldown** adequados; **Mixed Instances + Spot** para reduzir custos.

### Pontos importantes
- **Observabilidade:** CloudWatch (Logs/Metrics/Alarms), **X-Ray**, **CloudTrail**.  
- **Rede:** VPC, subnets públicas/privadas, NAT, **Security Groups**, **NACLs**.  
- **Segurança:** IAM *least-privilege*, **KMS**, **Secrets Manager**/**Parameter Store**.  
- **FinOps:** **Savings Plans/RI** (EC2/RDS), **S3 Lifecycle** (IA/Glacier), **CloudFront TTL** e *cache policies*, **AWS Budgets + alerts**.

---

## 🧩 5. Próximos Estudos / Pendências {#proximos}
- **Aurora Global Database – DR drill:** simular *failover/cutover* e medir RTO/RPO.  
- **Lambda + SQS + DLQ:** padrão antipico e idempotência ponta-a-ponta.  
- **OAC + S3 + SPA routing:** playbook de 403/404 → `/index.html` (200) + TTL de erro.  
- **Budgets + Cost Anomaly Detection:** alertas via SNS/Email e classificação por tag.

---

## 🧰 6. Ferramentas e Referências {#refs}
- AWS Skill Builder  
- AWS Documentation  
- AWS Architecture Center  
- AWS Well-Architected Framework  
- FinOps Foundation Labs  
- Projetos práticos e PoCs reais

---
