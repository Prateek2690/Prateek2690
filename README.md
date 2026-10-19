### Prateek Bhatnagar

**Quantitative Finance Domain Expert · AI Systems Architect · Researcher · Author**
*Credit risk and regulatory capital · Fixed-income portfolio construction · Explainable and AI-safe financial systems*

I have spent more than eight years building and governing the quantitative systems that large U.S. financial institutions rely on for numbers they are accountable for: regulatory capital and loss-reserve figures at a U.S. global systemically important bank, where I served as Vice President in Quantitative Research, and daily portfolio decisions for more than 1,000 client accounts at an institutional asset manager, where I am the sole architect of the optimization platform.

That work showed me a recurring and costly problem. When an automated financial system gets a number wrong, the error is often silent. It passes every check, reaches a regulatory filing or a client portfolio, and is found late, if at all. AI agents that read, repair, and act on these systems make the problem more urgent.

My research addresses it directly: methods that make regulatory figures, risk metrics, and portfolio trades **explainable, auditable, and safe to correct**. I publish this work as solo-authored papers on SSRN and release the code openly so that banks, asset managers, and regulators can test and adopt it.

**What I bring**
- **Industry leadership:** production ownership of regulatory risk pipelines (CCAR, CECL, FR Y-14) covering about $566 billion in exposure, and of a portfolio-rebalancing platform running across 1,000+ accounts every day
- **Risk governance:** model risk management under SR 11-7, with model review and reporting to senior risk management
- **Research and authorship:** three papers on safe automated correction, change attribution, and faithful explanation in financial systems, with open-source code
- **Training:** mathematics (IISER), quantitative finance (Rutgers), and data science (Saint Peter's)

---

#### Domain expertise

**Credit risk and regulatory capital**
- Stress testing (CCAR / DFAST) and risk-appetite metrics for wholesale credit portfolios
- Loss reserving under CECL: expected credit loss, allowance attribution, and period-over-period change analysis
- Credit risk parameters (PD, LGD, EAD) and Basel II / III risk-weighted assets
- Regulatory reporting data (FR Y-14) and model risk management under SR 11-7: model validation, documentation, and governance

**Fixed-income portfolio management**
- Construction and rebalancing of customized separately managed accounts against a benchmark or model portfolio
- Municipal bond portfolios: tax-aware and single-state mandates, credit-quality and issuer concentration limits
- Risk controls: duration and key-rate duration, sector, state, and issuer exposure, tracking error and contribution to benchmark
- Liability-driven and income strategies: cash-flow matching, buy-and-maintain

#### Technical skills

- **Agentic AI architecture:** multi-agent orchestration (planner–executor, supervisor, and router patterns), stateful agent workflows with LangGraph and LangChain, agent memory and context management, tool calling with structured outputs, Model Context Protocol (MCP) servers and agent-to-agent (A2A) interoperability, OpenAI Agents SDK and Claude Agent SDK
- **LLM platforms and retrieval:** OpenAI, Anthropic, and Amazon Bedrock APIs; retrieval-augmented generation (RAG) with vector databases, hybrid search, and re-ranking; model routing for cost and latency
- **AI safety, evaluation, and LLMOps:** agent guardrails and tool-call verification, human-in-the-loop approval and escalation design, prompt-injection defenses, LLM evaluation and faithfulness testing (offline evals and LLM-as-judge), tracing and observability (LangSmith, OpenTelemetry), NLP with Hugging Face Transformers
- **Machine learning:** gradient boosting (LightGBM), conformal prediction and uncertainty quantification, feature engineering, supervised and unsupervised learning, time-series modeling
- **Optimization:** LP / MILP, goal and lexicographic programming, elastic relaxation, infeasibility diagnosis (IIS), large-scale constrained optimization
- **ML engineering and cloud:** AWS (SageMaker, Lambda, S3, Glue, EMR, Redshift), model deployment and monitoring
- **Data engineering:** PySpark, Kafka, DuckDB, SQL / Oracle, event-driven and batch pipelines, data lineage, reconciliation, and data quality controls
- **Languages:** Python (pandas, NumPy, SciPy, scikit-learn), Java / Spring Boot, MATLAB, SQL
- **Research software:** reproducible benchmarks, synthetic data with known ground truth, open-source releases with DOIs
- **Certification:** AWS Certified Machine Learning – Specialty

#### Education

**Master of Quantitative Finance**, Rutgers Business School, Rutgers, The State University of New Jersey (2017). 45 credits.
- *Stochastic modeling and derivatives:* Stochastic Calculus, Introduction to Probability, Derivatives, Financial Time Series
- *Fixed income, portfolios, and risk:* Analysis of Fixed Income, Optimization Models in Finance, Risk Management, Indexing & ETFs, Quantitative Equity Trading Strategies
- *Computation and statistics:* Numerical Analysis, Financial Modeling I & II, Object-Oriented Programming I & II, Econometrics
- Industry internship as a Quantitative Strategy Analyst in corporate credit research
- Member of the first team to represent Rutgers Business School at the Rotman International Trading Competition (Toronto, 2016), which placed in the top 10 in the algorithmic trading case
- Featured in the "Student & Alumni Voices" section of the [Rutgers MQF program page](https://www.business.rutgers.edu/quantitative-finance) and in Rutgers Business School's 2017 [graduate convocation coverage](https://www.business.rutgers.edu/news/confidence-innovation-ethics-resonate-graduate-convocation-speeches)

**Dual BS-MS, Mathematical Sciences** (major) with a minor in Physical Sciences, Indian Institute of Science Education and Research (IISER) Thiruvananthapuram (2014). Five-year, ten-semester program; 175 credits.
- *Analysis and probability:* Real Analysis, Measure Theory and Integration, Functional Analysis, Probability Theory and Random Processes, Probability and Statistics
- *Optimization and computation:* Linear Programming, Numerical Analysis, Computational Methods for PDEs, Scientific Computing, Programming and Data Structures
- *Applied mathematics and finance:* Financial Engineering, Ordinary and Partial Differential Equations, Advanced Linear Algebra, Combinatorics and Graph Theory, Statistical Mechanics
- Two-semester master's research thesis on time-changed Brownian motion in credit risk modeling and the 2007–2008 financial crisis
- INSPIRE Scholarship for Higher Education, Department of Science and Technology, Government of India (2009–2014)

**Master of Science in Data Science**, Frank J. Guarini School of Business, Saint Peter's University, Jersey City, NJ (2022).
- Machine Learning, Data Mining, Big Data Analytics, Predictive Analytics and Financial Modeling, Data Analysis and Decision Modeling, Python for Data Science, Business Analytics, Data Visualization, Data Law and Ethics, Research Practicum

#### Research

| Paper | Status | Code |
|---|---|---|
| **A Safety Gate for AI-Driven Data Repair in Regulated Financial Reporting**: a verification gate that provably prevents automated repairs from silently misstating a reported figure such as a credit-loss allowance | SSRN preprint, Sept 2026 ([7432699](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7432699)) · not yet peer-reviewed | [matrepair](https://github.com/Prateek2690/matrepair) · [![DOI](https://zenodo.org/badge/1418606691.svg)](https://doi.org/10.5281/zenodo.23362560) |
| **Silent Defaults and Phantom Effects**: owner-aware attribution of expected-loss changes in versioned reporting pipelines, with evidence from public SBA loan data | SSRN preprint, Sept 2026 ([7486440](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7486440)) · not yet peer-reviewed | [silent-defaults-attribution](https://github.com/Prateek2690/silent-defaults-attribution) |
| **Faithful by Construction? An Exact Test of LLM Explanations for Constrained Portfolio Optimization Decisions**: checks every claim in an LLM's explanation of a portfolio-optimization decision against the solver's exact ground truth | SSRN preprint, Oct 2026 ([7625878](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7625878)) · not yet peer-reviewed | [faithful-by-construction](https://github.com/Prateek2690/faithful-by-construction) |

All papers use only public or synthetic data, and all code is released under the MIT License.

#### Research interests

- **Explainable AI for high-stakes decisions:** making automated and AI-driven decisions in finance explainable in terms that are faithful to the underlying computation
- **Safe and trustworthy AI agents:** guardrails, verification, and human oversight for agents that read, correct, or act on consequential data
- **Optimization and decision science:** portfolio construction, multi-objective and constrained optimization, and attribution of optimized decisions
- **Reliability of financial data and models:** detecting, explaining, and correcting silent errors in regulatory, risk, and reporting systems
- **Model risk and AI governance:** evaluation, validation, and accountability for quantitative and machine-learning models in regulated industries

---

[ORCID 0009-0000-0359-3268](https://orcid.org/0009-0000-0359-3268) · [SSRN](https://papers.ssrn.com/sol3/cf_dev/AbsByAuth.cfm?per_id=3464295) · [LinkedIn](https://linkedin.com/in/prateekbhatnagar90/)
