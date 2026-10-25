# Hi, I'm Jonathan 👋

Building practical projects and sharing what I learn.

📍 Vancouver, BC

## 👨‍💻 Featured Projects

**[ocisec](https://github.com/jayekwere/ocisec)** - Go static analyzer for OCI runtime
specs that flags container-escape misconfigurations (dangerous capabilities, host
namespace sharing, missing seccomp/AppArmor, unsafe host mounts) by parsing against the
upstream `opencontainers/runtime-spec` types rather than regex. Runs as a CI gate via
severity-based exit codes.

**[CI/CD Security Pipeline](https://github.com/jayekwere/ci-cd-security-pipeline)** -
Hardened GitHub Actions pipeline wiring SAST (Semgrep, CodeQL), SCA (Snyk), secret
scanning (TruffleHog), and DAST (OWASP ZAP) into every push and PR. Built around a gating
policy that blocks on new-code findings and reports on deferred ones, so the gate stays
trusted instead of getting disabled — with SHA-pinned actions for supply-chain hardening.

**[CVE Exploit Prediction](https://github.com/jayekwere/cve-exploit-prediction)** - ML
pipeline predicting which CVEs land in CISA's KEV catalog from public threat intel (EPSS +
KEV), evaluated on precision/recall with limitations documented honestly.

**[AI-Agent Anomaly Detection](https://github.com/jayekwere/agent-anomaly-detection)** -
Unsupervised anomaly detection (Isolation Forest, sequence-level features) for flagging
compromised AI agents. A study in honest evaluation: caught feature leakage behind an
inflated ROC-AUC, rebuilt the dataset, and reported the true result.

## 📑 Certifications
- **Proofpoint Certified AI Agent Security Specialist**
- **CEH** - Certified Ethical Hacker
- **CompTIA CySA+** - Cybersecurity Analyst
- **CompTIA CSAP** - Security Analytics Professional (stackable)
- **CompTIA Security+** 
- **CISM** - Certified Information Security Manager
- **Microsoft Certified: Azure Fundamentals**

## 🤝 Connect
- 📫 jonathan_ekwere@yahoo.com
