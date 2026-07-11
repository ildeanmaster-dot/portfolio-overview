# Data Engineering Portfolio — Jornada de Promoção a Sênior

> Repositório mestre de acompanhamento. Programa de 12 semanas, estruturado em 4 fases com critérios de saída (Go/No-Go), com o objetivo de consolidar as competências exigidas para Engenheiro de Dados Sênior/Specialist — baseado em pesquisa real de mercado (vagas Compass UOL, jul/2026).

**Autor:** Freitas · Founder Yottaflow · Base: Marabá/PA, Brasil
**Início do programa:** `[DATA A PREENCHER]`
**Status atual:** 🟡 Fase 0 — Preparação

---

## Por que este portfólio existe

Cada projeto aqui não é um exercício isolado — é a resposta pública a uma das **6 perguntas de aceite** que definem se alguém está pronto para o nível Sênior:

| # | Pergunta de aceite | Projeto(s) que respondem |
|---|---|---|
| 1 | Você desenha arquitetura Medallion, não só executa notebooks? | Semanas 4, 5 |
| 2 | Você testa dados antes de confiar neles? | Semanas 1, 4 |
| 3 | Você rastreia o impacto de uma mudança num pipeline? | Semana 9 |
| 4 | Você trabalha em mais de uma cloud? | Semana 7 |
| 5 | Você aplica governança formal (catálogo, acesso, qualidade)? | Semana 8 |
| 6 | Você está à frente da curva em IA aplicada a dados? | Semanas 10, 11 |

O Gate 4 (semana 12) só libera "aplicar/pedir promoção" se as 6 perguntas tiverem resposta pública demonstrável.

---

## Painel de Progresso

### Fase 1 — Disciplina de Engenharia (Semanas 1-3)
| Semana | Projeto | Status | Repositório | Post LinkedIn |
|---|---|---|---|---|
| 1 | Data Quality Framework (Great Expectations) | ⬜ Não iniciado | — | — |
| 2 | Framework de ETL Reutilizável | ⬜ Não iniciado | — | — |
| 3 | SQL Performance Deep Dive | ⬜ Não iniciado | — | — |

**🚦 Gate 1:** ⬜ Não avaliado
Critério: 3 repositórios públicos com README completo · pelo menos 1 com testes automatizados rodando · 1 interação real no LinkedIn.

### Fase 2 — Arquitetura em Escala (Semanas 4-6)
| Semana | Projeto | Status | Repositório | Post LinkedIn |
|---|---|---|---|---|
| 4 | Bronze → Silver (Databricks + Delta Lake) | ⬜ Não iniciado | — | — |
| 5 | Silver → Gold (Star Schema + Power BI) | ⬜ Não iniciado | — | — |
| 6 | Orquestração (Databricks Workflows) | ⬜ Não iniciado | — | — |

**🚦 Gate 2:** ⬜ Não avaliado
Critério: pipeline Bronze→Silver→Gold funcional e documentado · Power BI consumindo dados reais · orquestração com tratamento de erro demonstrável.

### Fase 3 — Multi-Cloud + Governança (Semanas 7-9)
| Semana | Projeto | Status | Repositório | Post LinkedIn |
|---|---|---|---|---|
| 7 | AWS Serverless Data Lake | ⬜ Não iniciado | — | — |
| 8 | Unity Catalog + Auto Loader | ⬜ Não iniciado | — | — |
| 9 | Data Lineage + Observabilidade | ⬜ Não iniciado | — | — |

**🚦 Gate 3:** ⬜ Não avaliado
Critério: projeto funcional em 2+ clouds · governança demonstrável · lineage com 1 caso de análise de impacto real.

### Fase 4 — IA Aplicada + Consolidação (Semanas 10-12)
| Semana | Projeto | Status | Repositório | Post LinkedIn |
|---|---|---|---|---|
| 10 | Agentic RAG para Dados | ⬜ Não iniciado | — | — |
| 11 | Governança + IA (recomendações automáticas) | ⬜ Não iniciado | — | — |
| 12 | Capstone (Consolidação Total) | ⬜ Não iniciado | — | — |

**🚦 Gate 4 (Go/No-Go final):** ⬜ Não avaliado
Critério: 6 perguntas de aceite respondidas publicamente · capstone sobe em máquina limpa · 3+ posts com engajamento real · você explica cada projeto em <2min de cor.

**Legenda de status:** ⬜ Não iniciado · 🟡 Em andamento · ✅ Concluído · ⚠️ Atrasado

---

## Matriz de Competências (Diagnóstico)

Baseado em pesquisa de vagas reais (Compass UOL, Data Engineer Junior→Specialist, jul/2026).

| Competência | Nível atual | Nível exigido (Sênior) | Gap | Onde é fechado |
|---|---|---|---|---|
| Databricks + PySpark | Alto | Alto | Nenhum | Consolidado nas Semanas 4-8 |
| SQL avançado | Alto | Alto | Pequeno | Semana 3 |
| Python (engenharia) | Médio | Alto | Médio | Semana 2 |
| Medallion Architecture | Alto | Alto | Pequeno | Semanas 4-5 |
| Data Quality (testes formais) | Baixo | Alto | **Grande** | Semana 1 |
| Data Lineage / Observabilidade | Muito baixo | Alto | **Grande** | Semana 9 |
| AWS | Muito baixo | Médio-Alto | **Grande** | Semana 7 |
| Azure | Médio | Alto | Médio | Reforçado ao longo do programa |
| Unity Catalog / Governança | Muito baixo | Alto | **Grande** | Semana 8 |
| RAG / GenAI aplicado a dados | Alto | Médio | Nenhum (diferencial) | Semanas 10-11 |
| CI/CD para pipelines | Baixo | Alto | Grande | Semanas 2, 6 |

---

## Stack Tecnológico do Programa

```
Linguagens:        Python, SQL, PySpark
Processamento:      Apache Spark, Databricks
Armazenamento:      Delta Lake, PostgreSQL, AWS S3
Cloud:              Databricks (core), AWS (gap), Azure (reforço)
Qualidade:          Great Expectations
Governança:         Unity Catalog, lineage graph (Neo4j)
Orquestração:       Databricks Workflows
Visualização:       Power BI
IA/RAG:             Claude API, Chroma, LangChain, FastAPI
Infra como código:  Terraform
```

---

## Estrutura de Repositórios

Cada projeto semanal vive em seu próprio repositório público, seguindo o template padrão (`templates/README-projeto.md`). Nomenclatura:

```
01-data-quality-framework
02-python-etl-framework
03-sql-performance-tuning
04-medallion-bronze-to-silver
05-medallion-silver-to-gold
06-databricks-orchestration
07-aws-serverless-datalake
08-databricks-unity-catalog
09-data-lineage-observability
10-agentic-rag-data-assistant
11-ai-governance-recommendations
12-modern-data-stack-capstone
```

---

## Cadência de Publicação

| Dia | Atividade |
|---|---|
| Terça | Post de anúncio do projeto da semana |
| Quinta | Post de deep dive técnico |
| Sábado | Carrossel / artigo de fechamento |

Ver `templates/calendario-editorial.md` para o detalhamento e `templates/post-linkedin.md` para os textos-modelo.

---

## Log de Decisões e Aprendizados

> Atualizar semanalmente. Este log é, em si, uma prova de maturidade de engenharia — mostra que você documenta trade-offs, não só resultados.

| Semana | Decisão tomada | Alternativa descartada | Motivo |
|---|---|---|---|
| — | — | — | — |

---

## Links de Referência da Pesquisa

- Vagas analisadas: Compass UOL — Data Engineer (Junior, Pleno, Sênior, Specialist), Azure Data Engineer, AWS Data Engineer, Databricks Data Engineer, Data Engineer + GenAI
- Pesquisa realizada: julho de 2026
- Fontes: LinkedIn, Glassdoor, Indeed, Jobgether
