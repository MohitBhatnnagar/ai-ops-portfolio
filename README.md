# Mohit Bhatnagar: AI and Operations Portfolio

Director, Operations | AI-native operations leader | P&L and budget owner. 16+ years running service businesses; most recently built and ran a 300+ person distributed delivery organisation serving US clients, taking delivery quality from 76% to 95%+ while raising productivity by more than 200%. Lean Six Sigma Black Belt.

This portfolio shows how I think about **running an organisation where AI agents do the repeatable work and people handle judgement and exceptions**. It is original work on synthetic data. It contains no employer code or confidential information.

LinkedIn: linkedin.com/in/mohitbhtgr

## Projects, most technically complex first

| # | Repo | What it shows | Tests |
|---|---|---|---|
| 1 | [ai-quality-and-evals](https://github.com/MohitBhatnnagar/ai-quality-and-evals) | Statistics for AI and human quality: SPC control charts, reviewer calibration (Cohen's kappa), BM25 / TF-IDF / hybrid retrieval evaluation with bootstrap confidence intervals | 34 |
| 2 | [agentflow-hitl](https://github.com/MohitBhatnnagar/agentflow-hitl) | Workflow engine for AI agents: autonomy policy, durable approval gates, held outputs, hash-chained audit log | 20 |
| 3 | [ops-mcp-server](https://github.com/MohitBhatnnagar/ops-mcp-server) | A Model Context Protocol server (JSON-RPC over stdio) with strict input validation and approval-only writes | 23 |
| 4 | [agentic-ai-patterns](https://github.com/MohitBhatnnagar/agentic-ai-patterns) | ReAct, plan-and-execute and reflection, with budgets, allow-listed tools and prompt-injection handling | 26 |
| 5 | [automation-business-case](https://github.com/MohitBhatnnagar/automation-business-case) | ROI and NPV with scenarios, Holt-Winters demand forecasting with backtests, capacity and hiring plans | 29 |
| 6 | [persona-studio](https://github.com/MohitBhatnnagar/persona-studio) | A shipped full-stack AI product (React and Node, async jobs, consent gate, rate limits). Live at mohitstudio.dev | |
| 7 | [ai-governance-framework](https://github.com/MohitBhatnnagar/ai-governance-framework) | Risk tiering, approval matrix and incident response, mapped to NIST AI RMF | 18 |
| 8 | [ai-workforce-design-playbook](https://github.com/MohitBhatnnagar/ai-workforce-design-playbook) | Method and scoring tool for deciding what agents do alone, with approval, or not at all | 22 |
| 9 | [ai-operating-model](https://github.com/MohitBhatnnagar/ai-operating-model) | The operating model and case study: work design, organisation, quality system, rhythm, onboarding | docs |
| 10 | [horaskope](https://github.com/MohitBhatnnagar/horaskope) | A shipped consumer AI product with a two-stage pipeline, about 11,000 readings in beta. Live at horaskope.lovable.app | 8 |

Order is by technical complexity (code volume, number of moving parts, depth of the underlying method). Rows 1 to 5 are the engineering depth; rows 7 to 9 are the management frameworks that tie the work together; rows 6 and 10 are products I shipped.

All code is standard-library Python except Persona Studio (React and Node), with 180 unit tests across the Python repos.
