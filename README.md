### Hi, I'm Ed 👋

I'm a Senior Technical Staff Member (principal-level IC) at IBM Research in Austin, TX, working on AI for chip design. My career has one through-line: imposing structure on large, messy scientific data, from semiconductors to genomics to AI agents. Today I build agentic AI systems: agent harnesses, MCP-connected platforms, and knowledge graphs that models can learn from.

**What I'm working on**

*Personal*
- **Agent guardrails:** [turnstile](https://github.com/edseabolt/turnstile) (TypeScript) enforces a planner → plan-reviewer → executor → test-runner → reviewer pipeline in [OpenCode](https://github.com/sst/opencode) through runtime hooks instead of prompt instructions. Plan-approval gates, evidence-verified test gates, and a tamper-evident JSONL audit journal. Policy steers; turnstile blocks.
- **Local inference:** [local-agent-stack](https://github.com/edseabolt/local-agent-stack) is my config and tooling for a local agentic coding stack. I run open-weight LLMs on a Mac Studio M3 Ultra (512 GB) with oMLX, an MLX-based serving stack: GLM-5.3-Flash, Qwen3.8-Flash-Next, Qwen3.8-27B, and Ornith-1.5-35B-A3B, quantized, with MTP speculative decoding. I publish my quantizations on [Hugging Face](https://huggingface.co/rwtd5150), including 400B-class MoE models, and in the [mlx-community](https://huggingface.co/mlx-community) org.
- **Agent orchestration:** I use OpenCode as my primary harness for open-source development, and [Orca](https://orca.dev) to orchestrate many agents across parallel worktrees.

*IBM*
- **AI for chip design:** building agentic data pipelines and knowledge graphs over chip-design artifacts (RTL, formal-verification testbenches, physical-design outputs) across three processor families. Shipped an MCP server that exposes these graphs to coding agents, used by 20+ engineers and researchers, and used it to curate a knowledge base of 1,100+ design cards (~7.6M words) that agents reason over directly.
- **Cloud EDA (EDAaaS):** architected IBM Research's hybrid-cloud platform for chip design on IBM Cloud and AWS, adopted by Cadence, Synopsys, and Rapidus engagements. Built an agent system that generates validated Terraform for large HPC/EDA environments, and an MCP server with OAuth 2.0 device flow so coding agents author and submit EDA workflows, with root-cause and Q&A agents on top.

**Before this**
- Architected the [IBM Functional Genomics Platform](https://github.com/IBM/omxware-getting-started): a continuously self-updating knowledge base of ~400K genomes, 70M+ genes, 60M+ proteins, and ~300M protein domains. Published in *IEEE/ACM TCBB*; extended to SARS-CoV-2 within weeks of COVID-19 hitting.
- Built Watson solutions including Chef Watson (4 patents, SXSW 2016) and the Watson Advisor for Leukemia with MD Anderson.
- 16 granted patents and 20 peer-reviewed publications ([Google Scholar](https://scholar.google.com/citations?user=0v1sRZYAAAAJ)).

[LinkedIn](https://www.linkedin.com/in/eseabolt/) · [Hugging Face](https://huggingface.co/rwtd5150) · [ORCID](https://orcid.org/0000-0002-2286-0226) · [Google Scholar](https://scholar.google.com/citations?user=0v1sRZYAAAAJ) · [Email](mailto:edseabolt@gmail.com)