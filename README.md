### Hi, I'm Harish Akshay 👋

CS undergrad in Chennai. I build developer tools for security and automation, and I ship them.

- 🛡️ Creator of **VulnLens**, an open-source security scanner on PyPI
- ⚙️ Founder of **[FlowGenius](https://flowgenius.in)**, a technical resource for engineers running n8n in production
- 🏆 4× hackathon winner (including 1st place, SIMATS Engineering Hackathon) · 📰 3× featured in The Hindu

---

### What I've shipped

**[VulnLens](https://github.com/harishakshay/open-source-vulnerability-scanner)**: a security scanner that tells you which findings actually matter
`pip install vulnlens` · [PyPI](https://pypi.org/project/vulnlens/) · [Live demo](https://harishakshay.github.io/open-source-vulnerability-scanner/) · [GitHub Marketplace](https://github.com/marketplace/actions/vulnlens)

- Scans code (Semgrep), dependencies (OSV.dev) and secrets (TruffleHog), then ranks every finding by real-world exploitation (CISA KEV, EPSS) instead of severity alone
- On 50 popular open-source AI apps it cut **10,114 findings to 34** that needed action, and caught actively exploited CVEs still shipping in 7 projects, which I reported to maintainers through coordinated disclosure
- Claude-based triage removes **61% of false alarms with zero real issues missed** on a labeled benchmark
- 129 tests on Linux, Windows and macOS, with a tokenless release pipeline

**[n8n Preflight](https://github.com/harishakshay/flowgenius-n8n-tool)**: production-readiness checks and safe auto-fix for n8n workflows
- 25 rules (error handling, retries, timeouts, leaked secrets, open webhooks), with a 0-100 score
- Checked against all **12,074 public n8n templates**: 96.5% precision on a held-out sample
- Ships as a CLI, a GitHub Action (inline PR comments, SARIF) and a browser app where workflows never leave the page

### Also built
- **[Hybrid RAG reasoning agent](https://github.com/harishakshay/hybrid-rag-reasoning-agent)**: document Q&A that searches ChromaDB (semantic) and Neo4j (structural) together, with section-aware chunking, reranking and cited answers
- **[RL content discovery](https://github.com/harishakshay/rl-content-discovery)**: a reinforcement-learning recommender that fights filter bubbles, with graph-based explanations of each recommendation
- **[Meme coin signal engine](https://github.com/harishakshay/Coin-Meme-Hackathon)**: sentiment, engagement and spike detection across Reddit, Twitter and Discord posts

### Tools I use
Python · TypeScript · React · Flask · PyTorch · LLM APIs (Claude, OpenAI, Groq) · Neo4j · ChromaDB · GitHub Actions · n8n

### Find me
[LinkedIn](https://www.linkedin.com/in/harishakshay21/) · [flowgenius.in](https://flowgenius.in)
