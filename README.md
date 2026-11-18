# Mohit Bhatnagar: AI and Operations Portfolio

Director, Operations | AI-native operations leader | P&L and budget owner. 16+ years running service businesses; most recently built and ran a 300+ person distributed delivery organisation serving US clients, taking delivery quality from 76% to 95%+ while raising productivity by more than 200%. Lean Six Sigma Black Belt.

This portfolio shows how I think about **running an organisation where AI agents do the repeatable work and people handle judgement and exceptions**: the operating model and governance around it, and the agentic AI, RAG and MCP engineering underneath. It is original work on synthetic data and contains no employer code or confidential information.

LinkedIn: https://www.linkedin.com/in/mohitbhatnagar-ai/

## 21 projects, ordered by size and technical complexity (largest first)

| # | Repo | What it shows | Tests |
|---|---|---|---|
| 1 | [ai-prospecting-outreach](https://github.com/MohitBhatnnagar/ai-prospecting-outreach) | Agentic lead-to-send pipeline: search, assessment, email verification, RAG-grounded drafting, human approval gate, throttled sending, signed reply webhooks, MCP approval tools, funnel export for dashboards | 70 |
| 2 | [ai-quality-and-evals](https://github.com/MohitBhatnnagar/ai-quality-and-evals) | SPC control charts, reviewer calibration (Cohen's kappa), retrieval evaluation with bootstrap confidence intervals | 34 |
| 3 | [agentflow-hitl](https://github.com/MohitBhatnnagar/agentflow-hitl) | Workflow engine for AI agents: autonomy policy, durable approval gates, held outputs, hash-chained audit log | 20 |
| 4 | [mohit-app-builder](https://github.com/MohitBhatnnagar/mohit-app-builder) | MCP app builder: Claude or Cursor creates, runs, screenshots and versions full-stack apps with database, sign-in, storage, email, Claude AI and demo data built in; a local take on Floot | 48 |
| 5 | [ops-mcp-server](https://github.com/MohitBhatnnagar/ops-mcp-server) | A Model Context Protocol server over stdio with strict validation and approval-only writes | 23 |
| 6 | [automation-platform-toolkit](https://github.com/MohitBhatnnagar/automation-platform-toolkit) | Lint n8n workflows for open webhooks, secrets and missing approvals before send; score automation platforms with sensitivity analysis | 38 |
| 7 | [agentic-ai-patterns](https://github.com/MohitBhatnnagar/agentic-ai-patterns) | ReAct, plan-and-execute and reflection with budgets, allow-listed tools and prompt-injection handling | 26 |
| 8 | [mcp-gateway](https://github.com/MohitBhatnnagar/mcp-gateway) | Gateway fronting several MCP servers: namespacing, per-client policy, default deny, rate limits, audit, real stdio upstream | 31 |
| 9 | [voice-agent-flow](https://github.com/MohitBhatnnagar/voice-agent-flow) | Voice agent call-flow engine: verification before disclosure, barge-in, escalation, latency budgets, transcript QA | 37 |
| 10 | [llm-gateway](https://github.com/MohitBhatnnagar/llm-gateway) | OpenAI, Anthropic and Gemini adapters with routing, failover, circuit breaker, cache, budget and cost tracking | 32 |
| 11 | [app-builder-spec-compiler](https://github.com/MohitBhatnnagar/app-builder-spec-compiler) | Lint a product spec for ambiguity and gaps, compile staged prompts for AI app builders, generate a QA checklist | 36 |
| 12 | [rag-service](https://github.com/MohitBhatnnagar/rag-service) | Hybrid retrieval, access control before scoring, citations, abstention and groundedness checks | 31 |
| 13 | [automation-business-case](https://github.com/MohitBhatnnagar/automation-business-case) | ROI and NPV with scenarios, Holt-Winters demand forecasting with backtests, capacity and hiring plans | 29 |
| 14 | [coding-agent-config](https://github.com/MohitBhatnnagar/coding-agent-config) | One spec generates AGENTS.md, CLAUDE.md, Cursor rules and Replit notes; drift check and permission linter | 32 |
| 15 | [persona-studio](https://github.com/MohitBhatnnagar/persona-studio) | A shipped full-stack AI product (React and Node, async jobs, consent gate, rate limits). Live at www.mohitstudio.dev | 21 |
| 16 | [agent-evals-harness](https://github.com/MohitBhatnnagar/agent-evals-harness) | Trajectory scoring, forbidden-tool vetoes, pass@k and pass^k reliability, regression gate | 31 |
| 17 | [multi-agent-orchestrator](https://github.com/MohitBhatnnagar/multi-agent-orchestrator) | Supervisor and specialist agents with a permissioned blackboard, loop detection and escalation | 21 |
| 18 | [ai-governance-framework](https://github.com/MohitBhatnnagar/ai-governance-framework) | Risk tiering, approval matrix and incident response, mapped to NIST AI RMF | 18 |
| 19 | [ai-workforce-design-playbook](https://github.com/MohitBhatnnagar/ai-workforce-design-playbook) | Method and scoring tool for deciding what agents do alone, with approval, or not at all | 22 |
| 20 | [ai-operating-model](https://github.com/MohitBhatnnagar/ai-operating-model) | The operating model and case study: work design, organisation, quality system, rhythm, onboarding | docs |
| 21 | [horaskope](https://github.com/MohitBhatnnagar/horaskope) | A complete consumer AI product with a two-stage pipeline, live at www.horaskope.com, about 11,000 readings in beta | 8 |

**608 automated tests in total.** Python repos use only the standard library; Persona Studio is React and Node; Mohit is TypeScript on Node. All suites run in CI.

## Notes

- All data in these repositories is synthetic. Nothing from a real employer, client or customer is included.
- The model layer in each repo is an injected interface, replaced by test doubles in the tests, so the tests verify control logic rather than model quality.
- Tool names that appear (for example n8n, Zapier, Lyzr, Bolt, Rocket, Hercules, Smallest AI, Cursor, Replit, Claude Code, Codex, ChatGPT, Gemini) are targets and examples. Each repo's README says what it was tested against.
