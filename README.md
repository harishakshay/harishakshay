### Hi, I'm Harish Akshay

I'm a CS undergrad in Chennai. I like building tools that fix problems I've run into myself, mostly in security and automation.

- I built **VulnLens**, an open-source security scanner you can install from PyPI
- I run **[FlowGenius](https://flowgenius.in)**, where I write about why n8n automations break in production and how to fix them
- I've won 4 hackathons, including 1st place at the SIMATS Engineering Hackathon, and my work has been featured in The Hindu three times

---

### What I've shipped

**[VulnLens](https://github.com/harishakshay/open-source-vulnerability-scanner)**: a security scanner that shows you the bugs attackers are actually exploiting
`pip install vulnlens` · [PyPI](https://pypi.org/project/vulnlens/) · [Live demo](https://harishakshay.github.io/open-source-vulnerability-scanner/) · [GitHub Marketplace](https://github.com/marketplace/actions/vulnlens)

Most scanners hand you hundreds of warnings and leave you to guess which ones matter. VulnLens started as my SIMATS hackathon project, and I kept building it after it won. It checks your code, dependencies and secrets, then puts anything that's being exploited in the wild (using CISA's KEV list and EPSS scores) at the top.

- I ran it on 50 popular open-source AI projects. Out of about 10,000 findings, only 34 needed action, and among them were known, actively exploited CVEs still shipping in 7 of the projects.
- I reported those to the maintainers through each project's security channel ([one report is public](https://github.com/ruc-datalab/DeepAnalyze/issues/130)).
- I added an optional Claude-based review step that clears out false alarms. On a small labelled test set it removed 61% of them without dismissing a single real issue.

**[n8n Preflight](https://github.com/harishakshay/flowgenius-n8n-tool)**: catches the mistakes that break n8n workflows in production

While writing for FlowGenius I kept seeing the same failures: no error handling, no retries, missing timeouts, API keys pasted straight into workflows. Preflight checks for these automatically and fixes the safe ones for you.

- 25 checks, usable from the command line, as a GitHub Action on pull requests, or in the browser (your workflow never leaves the page)
- Before trusting it, I ran it on all 12,074 public n8n templates and checked a sample of 200 findings: 96.5% were correct
- It isn't released yet; that's what I'm finishing now

### Also built
- **[Hybrid RAG reasoning agent](https://github.com/harishakshay/hybrid-rag-reasoning-agent)**: a document Q&A assistant built for a hackathon. It searches by meaning (ChromaDB) and by how documents relate to each other (Neo4j), and every answer cites the passage it came from.
- **[RL content discovery](https://github.com/harishakshay/rl-content-discovery)**: a recommender that uses reinforcement learning to keep a feed interesting without trapping you in a filter bubble, and shows why it picked each item.
- **[Meme coin signal engine](https://github.com/harishakshay/Coin-Meme-Hackathon)**: reads Reddit, Twitter and Discord posts to spot meme coin hype early, from sentiment, engagement and sudden spikes in mentions.

### Tools I use
Python, TypeScript, React, Flask, PyTorch, Neo4j, ChromaDB, GitHub Actions, n8n, and LLM APIs (Claude, OpenAI, Groq)

### Find me
[LinkedIn](https://www.linkedin.com/in/harishakshay21/) · [flowgenius.in](https://flowgenius.in) · Always happy to talk about security tooling or automation.
