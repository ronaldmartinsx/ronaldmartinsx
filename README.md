# Ronald Martins

**Engenharia de dados, de Manaus (AM).** Construo o caminho inteiro: do dado cru à pergunta que o diretor faz na reunião.

Meu trabalho hoje é dado de locadora de frotas B2B — faturamento, inadimplência, telemetria, ciclo de vida do veículo — num lakehouse no **Microsoft Fabric** com consumo em **Power BI**. Fora do expediente, os projetos abaixo são onde eu testo arquitetura nova de ponta a ponta.

Três coisas que eu levo para todo projeto:

- **Regra de negócio tem um lugar só.** Na camada de dados, versionada e testada — nunca espalhada em SQL solto ou em coluna calculada de relatório.
- **Problema de qualidade se marca e se mede, não se apaga.** Um `INNER JOIN` descuidado esconde receita sem avisar ninguém.
- **O painel responde uma pergunta por tela, em português de gente.** Quem lê o número não precisa saber interpretar a fórmula.

---

## Projetos

| Projeto | O que é | Stack |
|---|---|---|
| **[rideshare-marketplace-intelligence](https://github.com/ronaldmartinsx/rideshare-marketplace-intelligence)** | Lakehouse sobre as corridas de aplicativo de Nova York (TLC + clima), com ingestão automatizada, ADRs e contratos de schema. Em construção, fase 2. | AWS (S3, Glue, Athena, Iceberg), dbt, Airflow, Terraform, Power BI |
| **[ecommerce-databricks](https://github.com/ronaldmartinsx/ecommerce-databricks)** | Pipeline de e-commerce da ingestão ao agente em português: medalhão no Unity Catalog, 22 testes que deixam o Job vermelho, um dashboard por diretoria e Genie. Tudo como Asset Bundle, `dev` e `prod`, serverless. | Databricks, Lakeflow, PySpark, Unity Catalog, AI/BI Genie |
| **[dashboard-financeiro-frotas](https://github.com/ronaldmartinsx/dashboard-financeiro-frotas)** | Cinco páginas, uma pergunta de negócio por tela, sobre uma camada semântica com **116 verificações** no CI. A análise achou o que não estava no briefing: a crise é de crédito, não de receita. [Painel no ar.](https://dashboard-financeiro-rdev.streamlit.app) | Streamlit, Parquet, pandas, GitHub Actions |
| **[rag-production](https://github.com/ronaldmartinsx/rag-production)** | RAG em produção: ingestão, avaliação e serviço, do módulo de IA da trilha Jornada de Dados. | Python, LLM, RAG |

## Ferramentas do dia a dia

`Python` · `SQL` · `PySpark` · `dbt` · `Airflow` · `Databricks` · `Microsoft Fabric` · `Power BI (PBIP/TMDL, DAX)` · `AWS` · `Terraform` · `Git` · `Claude Code`

---

Para conversar sobre dados, projeto ou vaga: **ronald.martinss11@gmail.com**
