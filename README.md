# AgentAudit & DataShield 🛡️

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)

AgentAudit & DataShield is an open-source, developer-first observability engine for AI and data pipelines. It tackles silent pipeline failures by automatically detecting statistical distribution drift, schema anomalies, and null spikes across datasets. It also provides automated, context-aware PII scrubbing to prevent sensitive data leakage into LLMs.

## 🚀 Features
* **Statistical Drift Detection:** Catch distribution shifts using Population Stability Index (PSI) and Kolmogorov-Smirnov (KS) tests.
* **PII & Sensitive Data Scrubbing:** Automatically mask or redact personal identifiers before data reaches your models.
* **CI/CD Integration:** Block bad data at the pull request level with automated GitHub Actions.
* **Observability Dashboard:** Visualize data health scores and anomaly timelines.

## 🛠️ Quick Start

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/agentaudit-datashield.git](https://github.com/your-username/agentaudit-datashield.git)
   cd agentaudit-datashield
