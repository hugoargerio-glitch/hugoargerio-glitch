<div align="center">

# Hugo Argeri Campos
### Data Engineer & Python Backend Developer | Python, SQL, PySpark, Airflow | Databricks & Snowflake | Comércio Exterior (COMEX), Conciliação Cambial (PTAX) & Regulação Aduaneira

<p align="center">
  Engenharia de dados resiliente, construção de APIs determinísticas em <b>FastAPI</b>, modelagem relacional/dimensional em <b>PostgreSQL</b> e automação em ambiente <b>Linux nativo</b>.<br>
  Foco na convergência entre arquitetura de software, orquestração de <i>Coding Agents</i> e regras de negócio financeiras, fiduciárias e de comércio internacional.
</p>

<!-- Badges de Contato e Certificações -->
<p align="center">
  <a href="https://www.linkedin.com/in/hugo-campos-b2a678273/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:hugoargerio@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <img src="https://img.shields.io/badge/IBM_Certified-Data_Engineer-052FAD?style=for-the-badge&logo=ibm&logoColor=white" alt="IBM Data Engineer" />
  <img src="https://img.shields.io/badge/IBM_Certified-Data_Architect-052FAD?style=for-the-badge&logo=ibm&logoColor=white" alt="IBM Data Architect" />
</p>

</div>

---

### ⚡ Arquitetura & Diferencial de Domínio

- **Data Ingestion & Resiliência:** Desenvolvimento de motores de **ingestão de dados** tolerantes a falhas (tratamento de concorrência, *Exponential Backoff with Full Jitter* via `Tenacity`, *Idempotent Upserts* e *Data Contracts* estritos com `Pydantic V2`).
- **Backend & Persistência Fiduciária:** Construção de REST APIs em `Python 3.12` e `FastAPI` integradas a bancos relacionais (`PostgreSQL 16` com integridade ACID estrita, triggers PL/pgSQL e razão de partidas dobradas) e arquiteturas *Medallion Lakehouse* (`DuckDB`, `PySpark`, `Delta Lake`, `Snowflake`).
- **AI Coding & Agentic AI:** Orquestração de fluxos de desenvolvimento assistidos por agentes autônomos (*Claude Code*, *OpenAI Codex*, *Antigravity CLI*, *Tool Calling/MCP*), governança com contratos executáveis (*ODCS v3.2.0*), testes automatizados determinísticos (`pytest`) e isolamento em containers `Docker`.
- **Domínio Aplicado (Comex & Finanças):** Graduando em **Tecnólogo em Comércio Exterior (PUCRS)**. Capacidade prática de traduzir processos regulatórios aduaneiros, documentos fiscais internacionais (*Commercial Invoices*, NCM/HS Code, Incoterms FOB/CIF) e conciliação cambial multi-moeda (BACEN PTAX / Spot) em modelos de dados auditáveis.

---

### 🛠️ Tech Stack Nuclear

<div align="center">

**Linguagens, Backend & Contratos de Dados**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" />
</p>

**Engenharia de Dados, Bancos & Lakehouse**
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black" />
  <img src="https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=Apache%20Airflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/Delta_Lake-00ADD8?style=for-the-badge&logo=deltalake&logoColor=white" />
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" />
</p>

**Infraestrutura, Linux & DevOps**
<p>
  <img src="https://img.shields.io/badge/Fedora_Linux-51A2DA?style=for-the-badge&logo=fedora&logoColor=white" />
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
</p>

</div>

---

### 🏗️ Arquiteturas em Destaque (Featured Projects)

| Projeto | Arquitetura & Escopo Técnico | Stack Principal |
| :--- | :--- | :--- |
| 🏛️ **[comex-data-engine-v2](https://github.com/hugoargerio-glitch/comex-data-engine-v2)** | **Motor Fiduciário e Ingestão Aduaneira:** Razão contábil *append-only* de partidas dobradas com invariante de soma zero e triggers PL/pgSQL (PostgreSQL 16) bloqueando UPDATE/DELETE. Conector live BACEN Olinda PTAX com precisão `Decimal('0.000001')` e algoritmo LOCF, motor de cálculo tributário em cascata (ICMS "por dentro"), esteira HITL para quarentena de inconsistências e 31 testes unitários determinísticos (Pytest). | `Python 3.12` `FastAPI` `PostgreSQL 16` `Pydantic V2` `Tenacity` `Pytest` `Docker` |
| ⚡ **[b2b-price-monitor](https://github.com/hugoargerio-glitch/b2b-price-monitor)** | **Enterprise Dual-Hash CDC Engine & Transactional Outbox:** Motor de captura de mudanças de preços e estoque governado pelo contrato ODCS v3.2.0. Validação *shift-left* `DECIMAL(18,4)` (Zero FLOAT), motor diff determinístico via SHA-256 (`entity_key` + `state_hash`), persistência ACID em SQLite 3 WAL (`BEGIN IMMEDIATE`), Domain Circuit Breaker estatístico ($N \ge 10$, falhas $> 20\%$) e Transactional Outbox assíncrono com Exponential Backoff e Full Jitter para Discord/Slack webhooks. 65 testes automatizados (0.26s). | `Python 3.12` `SQLite 3 WAL` `Pydantic V2` `ODCS v3.2.0` `Docker` `Pytest` |
| 📊 **[MacroFlow-Lakehouse](https://github.com/hugoargerio-glitch/MacroFlow-Lakehouse)** | **Plataforma de Séries Macroeconômicas e Câmbio:** Ingestão distribuída de dados financeiros de APIs oficiais (BACEN SGS e Yahoo Finance) com validação *shift-left* via contratos de dados em Pydantic V2 para neutralizar *schema drift*, arquitetura Medallion (Delta Lake) e Data Warehouse dimensional em Snowflake com políticas FinOps de suspensão automática. | `Python` `Pydantic` `Databricks` `Delta Lake` `Snowflake` `Airflow` |
---

### 🎓 Formação & Certificações Oficiais

- 🎓 **Tecnólogo em Comércio Exterior** — *Pontifícia Universidade Católica do Rio Grande do Sul (PUCRS)*
- 🏅 **IBM Data Architect Professional Certificate** — *Credly Verified*
- 🏅 **IBM Data Engineering Professional Certificate** — *Credly Verified*
