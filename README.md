# Mohit Bhatnagar: AI and Operations Portfolio

Director, Operations | AI-native operations leader | P&L and budget owner. 16+ years running service businesses; most recently built and ran a 300+ person distributed delivery organisation serving US clients, taking delivery quality from 76% to 95%+ while raising productivity by more than 200%. Lean Six Sigma Black Belt.

This portfolio shows how I think about **running an organisation where AI agents do the repeatable work and people handle judgement and exceptions**. It is original work on synthetic data. It contains no employer code or confidential information.

LinkedIn: linkedin.com/in/mohitbhtgr

## Start here

| | |
|---|---|
| [**ai-operating-model**](https://github.com/MohitBhatnnagar/ai-operating-model) | The operating model and a case study: work design, organisation, quality system, rhythm, onboarding. Read this first. |

## Operating frameworks (with working tools)

| Repo | What it answers | Tests |
|---|---|---|
| [ai-workforce-design-playbook](https://github.com/MohitBhatnnagar/ai-workforce-design-playbook) | Which work should agents do alone, with approval, or not at all? | 22 |
| [ai-governance-framework](https://github.com/MohitBhatnnagar/ai-governance-framework) | How do we tier risk, assign approvers and respond to incidents? Mapped to NIST AI RMF. | 18 |
| [ai-quality-and-evals](https://github.com/MohitBhatnnagar/ai-quality-and-evals) | How do we measure quality and keep it improving? SPC, reviewer calibration, RAG evaluation. | 34 |
| [automation-business-case](https://github.com/MohitBhatnnagar/automation-business-case) | Is it worth it, and how many people will we need? ROI, forecasting, capacity. | 29 |

## Agentic AI engineering

| Repo | What it shows | Tests |
|---|---|---|
| [agentflow-hitl](https://github.com/MohitBhatnnagar/agentflow-hitl) | Workflow engine with autonomy policy, human approval gates and a tamper-evident audit log | 20 |
| [agentic-ai-patterns](https://github.com/MohitBhatnnagar/agentic-ai-patterns) | ReAct, plan-and-execute, reflection, with budgets and prompt-injection handling | 26 |
| [ops-mcp-server](https://github.com/MohitBhatnnagar/ops-mcp-server) | A Model Context Protocol server with strict validation and approval-only writes | 23 |

## Products I shipped

| Repo | What it is |
|---|---|
| [persona-studio](https://github.com/MohitBhatnnagar/persona-studio) | AI portrait studio, live at mohitstudio.dev. React and Node, async jobs, consent gate, rate limits |
| [horaskope](https://github.com/MohitBhatnnagar/horaskope) | AI horoscope platform, live at horaskope.lovable.app. About 11,000 readings in beta. Two-stage AI pipeline |

## How the pieces fit

```
ai-operating-model  (the system I run)
 |- work design ........ ai-workforce-design-playbook -> enforced by agentflow-hitl
 |- quality system ..... ai-quality-and-evals
 |- tools for agents ... ops-mcp-server, agentic-ai-patterns
 |- governance ......... ai-governance-framework
 '- economics .......... automation-business-case
```

All code is standard-library Python with unit tests (172 across the seven code repos).
