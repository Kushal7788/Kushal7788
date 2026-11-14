# Hi, I'm Kushal 👋

I build zero-knowledge and zkTLS systems: ways to prove facts about your web data (accounts, history, credentials) without handing that data over.

- 🔭 **Now:** building zkTLS solutions at [Burnt Labs](https://github.com/burnt-labs)
- 🧾 **Before:** worked with [Reclaim Protocol](https://www.reclaimprotocol.org/) on zkTLS proofs of web data
- 🎓 **Education:** M.Tech in Computer Science & Information Security, IIIT Hyderabad · B.Tech in Computer Engineering, VIIT Pune
- 🌐 [kushal7788.github.io](https://kushal7788.github.io/) · [LinkedIn](https://www.linkedin.com/in/kushal-s/)

💬 Happy to talk about zero-knowledge, zkTLS and privacy-engineering work. The best way to reach me is [LinkedIn](https://www.linkedin.com/in/kushal-s/).

### 🧑‍💻 Experience

| Where | What I worked on |
|---|---|
| **[Burnt Labs](https://github.com/burnt-labs)** (current) | zkTLS solutions for proving web data |
| **[Reclaim Protocol](https://www.reclaimprotocol.org/)** | zkTLS SDKs (JS, React Native, Flutter, Python), the provider devtool, ClickHouse/Grafana analytics, an A2A verification agent |
| **Indeed**, Data Science Intern (2022) | Resume spell checker with NER that found 25% more errors than existing tools |
| **Snowflake**, Software Engineer Intern (2021) | Automated analytics dashboards with real-time alerts; a bulk PDF-watermarking tool |
| **IDeaS Revenue Solutions**, Software Engineer Intern (2020) | Hotel revenue-management and reservations features, with over 80% test coverage |

### 🛠️ Tech

- **ZK & cryptography:** zkTLS, TLSNotary (MPC-TLS), Circom, snarkjs (Groth16), selective disclosure
- **Languages:** Rust, TypeScript/JavaScript, Python, Dart, C++, Java
- **Backend & infra:** Node.js/Express, axum, MongoDB, Redis, ClickHouse, Grafana, AWS, Cloudflare Workers, Docker
- **Frontend & mobile:** React, React Native, Flutter
- **ML:** PyTorch, Keras, scikit-learn, NLTK, transformers (BERT), LLM serving with Ollama

### 🏆 Highlights

- GATE 2021: 98th percentile
- Two ETHGlobal hackathons
- Deep Learning Specialization (DeepLearning.AI) · Fundamentals of Computer Vision (NVIDIA DLI)

---

## 📌 Featured

| Project | What it is |
|---|---|
| [zk-backpack](https://github.com/Kushal7788/zk-backpack) | Flutter vault for TLSNotary web proofs with selective disclosure and revocable share links |
| [plugin-service](https://github.com/Kushal7788/plugin-service) | TLSNotary MPC-TLS verifier and notary service in Rust (axum) for mobile provers |
| [Vibe-Match](https://github.com/Kushal7788/Vibe-Match-Client) | Prove your Netflix/Prime watch history with zkTLS and match on taste ([service](https://github.com/Kushal7788/Vibe-Match-Service)) |
| [zk-circuits-playground](https://github.com/Kushal7788/zk-circuits-playground) | Circom circuits I write, prove and test, starting with a private email-domain verifier |
| [Wikipedia_Search_Engine](https://github.com/Kushal7788/Wikipedia_Search_Engine) | Field-aware inverted index and TF-IDF ranked search over the full ~90 GB English Wikipedia dump |
| [SQL_Database_Engine](https://github.com/Kushal7788/SQL_Database_Engine) | Disk-backed relational query engine in C++ with a buffer pool and join algorithms |

---

## 🔐 Zero knowledge & zkTLS

- [zk-backpack](https://github.com/Kushal7788/zk-backpack): TLSNotary proof vault with selective disclosure (Flutter)
- [plugin-service](https://github.com/Kushal7788/plugin-service): MPC-TLS verifier and notary for mobile provers (Rust)
- [Vibe-Match-Client](https://github.com/Kushal7788/Vibe-Match-Client) / [Vibe-Match-Service](https://github.com/Kushal7788/Vibe-Match-Service): zkTLS-verified taste matching (React, Express, OpenAI embeddings)
- [zk-circuits-playground](https://github.com/Kushal7788/zk-circuits-playground): Circom circuits I write and test, starting with a private email-domain verifier

### Reclaim Protocol

At Reclaim I worked on the protocol that turns HTTPS website data into zero-knowledge proofs of provenance:

- Built the Reclaim SDKs for JavaScript, React Native, Flutter and Python, with CI/CD for automated publishing. This cut integration time from 4–5 hours to about 15 minutes.
- Built the developer tool for defining custom data providers (request-matching rules and extraction from network responses) without deep protocol knowledge.
- Built centralised logging and analytics on ClickHouse and Grafana.
- Built a verification AI agent and MCP server compatible with Google's A2A protocol, for employment and academic checks.

Public repos from that time:

- [reclaim-sdk-backend-demo](https://github.com/Kushal7788/reclaim-sdk-backend-demo): minimal backend using the Reclaim JS SDK
- [reclaim-demos](https://github.com/Kushal7788/reclaim-demos): eight 2023 demo apps, including proof-gated Discord and Telegram bots, KYC-free loan app, scam check, employment verification and a React Native wallet
- [inji-wallet (reclaim-issuer-integration)](https://github.com/Kushal7788/inji-wallet/tree/reclaim-issuer-integration): Reclaim as a credential issuer in MOSIP's Inji Wallet
- [vc-verifier](https://github.com/Kushal7788/vc-verifier): ISO 8601 date-format support for MOSIP's verifiable-credential verifier

---

## 🤖 Machine learning, NLP & IR

- [CodeMix_Generation](https://github.com/Kushal7788/CodeMix_Generation): Hinglish code-mixed text generation, comparing LSTM/BiLSTM next-word models, a Hinglish sentence-encoder head and a fine-tuned BERT masked LM (ROUGE-L, perplexity)
- [Wikipedia_Search_Engine](https://github.com/Kushal7788/Wikipedia_Search_Engine): inverted index and TF-IDF ranking over the full English Wikipedia
- [Dimensionality_Reduction_Techniques](https://github.com/Kushal7788/Dimensionality_Reduction_Techniques): PCA from scratch (eigenfaces, explained variance) and three PyTorch autoencoder architectures
- [Optimizer-ML-Project](https://github.com/Kushal7788/Optimizer-ML-Project): eight gradient-descent optimizers from scratch, from SGD to Adam
- [llm-deploy](https://github.com/Kushal7788/llm-deploy): self-hosted DeepSeek-R1 chat API (FastAPI + Ollama)

Also: during a data-science internship at Indeed, I built a resume spell checker that used NER to tell names apart from typos. It found 25% more spelling errors than existing tools.

---

## 🧰 Other projects

- [SQL_Database_Engine](https://github.com/Kushal7788/SQL_Database_Engine): relational query engine with paged storage, buffer pool, joins and GROUP BY (C++)
- [P2P_File_Sharing_System](https://github.com/Kushal7788/P2P_File_Sharing_System): tracker-based group file sharing with TCP sockets, pthreads and SHA-1 piece hashing (C++)

---

**Browse by topic:** [zktls](https://github.com/Kushal7788?tab=repositories&q=topic%3Azktls) · [zero-knowledge](https://github.com/Kushal7788?tab=repositories&q=topic%3Azero-knowledge) · [machine-learning](https://github.com/Kushal7788?tab=repositories&q=topic%3Amachine-learning) · [systems](https://github.com/Kushal7788?tab=repositories&q=topic%3Asystems)

<img src="https://github-readme-streak-stats.herokuapp.com/?user=kushal7788" alt="GitHub streak" />
