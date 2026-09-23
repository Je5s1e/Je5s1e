## Hi, I'm Chao Jiang 👋

[![AI Agent](https://img.shields.io/badge/%F0%9F%A4%96_AI_Agent-6366F1?style=flat-square)](#building-reliable-agents)
[![SIGKDD 2026](https://img.shields.io/badge/SIGKDD_2026-1f6feb?style=flat-square)](https://github.com/Je5s1e/KDD26-ADS-StarVerus)
[![ASE 2026](https://img.shields.io/badge/ASE_2026-00897B?style=flat-square)](#selected-work)
[![Formal Verification](https://img.shields.io/badge/Formal_Verification-6A5ACD?style=flat-square)](https://github.com/verus-lang/verus)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)](https://www.rust-lang.org/)

I am an M.S. student in Software Engineering at [Shenzhen University](https://www.szu.edu.cn/) and a research intern at Ant Group's Technology Research Institute. I build **LLM agents for real-world code repositories**, with a focus on **context engineering, tool use, multi-agent orchestration, and reliable execution**. My current work applies these ideas to Rust code generation and verification in the [Asterinas](https://github.com/asterinas) ecosystem.

I am interested in how agents turn a task into a working change: retrieving relevant context, planning edits, calling tools, learning from execution feedback, and checking the result. My work spans both **agent workflow engineering** and **research on repair decisions and output quality**.

### Building reliable agents

- **Context engineering** — Retrieve repository history, cross-file dependencies, and reusable proof patterns; load domain knowledge on demand through shared skills.
- **Tool use & orchestration** — Compose generation, migration, verification, repair, and review into reusable workflows, with explicit tool constraints and retry budgets.
- **Multi-agent collaboration** — Separate planning, specialized repair, patch execution, and structural rewriting so each role handles a distinct decision in the repair loop.
- **Evaluation & auditing** — Examine verification results, specification quality, and executable semantics separately to assess what an agent's output actually guarantees.

| <a href="https://github.com/Je5s1e"><img align="center" src="https://github-readme-stats-omega-eight-15.vercel.app/api?username=Je5s1e&show_icons=true&include_all_commits=true&theme=buefy&hide_border=true" alt="Je5s1e's GitHub statistics" /></a> | <a href="https://github.com/Je5s1e"><img align="center" src="https://github-readme-stats-omega-eight-15.vercel.app/api/top-langs/?username=Je5s1e&layout=compact&theme=buefy&hide_border=true" alt="Je5s1e's top languages" /></a> |
| ------------- | ------------- |

### Selected work

- **[KVerus Skills](https://github.com/asterinas/KVerus/tree/main/skills)** — **Agent workflow engineering at Ant Group.** Contributed reusable skills that connect repository context retrieval, Rust-to-Verus migration, proof generation, and iterative repair through verifier feedback. The workflow also incorporates post-processing review gates and semantic auditing for Asterinas kernel verification.
- **[StarVerus](https://github.com/Je5s1e/KDD26-ADS-StarVerus)** — **Multi-agent generation and repair.** First-author work accepted to **SIGKDD 2026**. Builds repository context from caller/callee relationships, aligns generated contracts, and coordinates Planner, Repairer, Actor, and Rewriter roles within a bounded verification-and-repair loop.
- **Beyond Benchmarks** — **Understanding agent failures in real repositories.** Third-author work accepted to **ASE 2026**. Studies how repository dependencies and semantic modeling affect coding agents, why verifier diagnostics can diverge from root causes, and how iterative repair can stagnate or regress.
- **[Large Language Models for Multilingual Code Intelligence: A Survey](https://arxiv.org/abs/2604.25960)** — First-author survey accepted to **KSEM 2026**, covering multilingual code generation, translation, retrieval-augmented generation, multi-agent methods, and trustworthy evaluation.

### Research interests

`Coding Agents` · `Context Engineering` · `Tool Use` · `Multi-Agent Systems` · `Agent Skills` · `Feedback-Driven Repair` · `Agent Evaluation` · `RAG`

### Tools I work with

`Python` · `Rust` · `LangGraph` · `Claude Code` · `Codex` · `Function Calling` · `Verus` · `Static Analysis`

### Education

- **M.S. in Software Engineering**, Shenzhen University, 2024–2027
- **B.Eng. in Software Engineering**, Changsha University of Science & Technology, 2020–2024

### Contact

- GitHub: [Je5s1e](https://github.com/Je5s1e)
- Email: [chao_cc@outlook.com](mailto:chao_cc@outlook.com)
