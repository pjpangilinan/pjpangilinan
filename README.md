<div align="center">

# Hi, I'm Patrick James Pangilinan 👋
### Cloud, DevOps & Agentic Engineer · Computer Engineering

**AWS Certified Solutions Architect · Cisco Network Automation · Go & Python Systems Builder**

[![Portfolio](https://img.shields.io/badge/Live%20Portfolio-Kanbalio-00D4FF?style=flat-square&logo=safari&logoColor=white)](https://pjpangilinan.github.io/kanbalio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/patrick-james-pangilinan-490a41329)
[![Email](https://img.shields.io/badge/ProtonMail-Contact%20Me-6D4AFF?style=flat-square&logo=protonmail&logoColor=white)](mailto:patrickjpangilinan@protonmail.com)
[![Open to Remote](https://img.shields.io/badge/Open%20to%20Work-Remote%20%2F%20Global-22c55e?style=flat-square&logo=target)](#-contact)

<br/>

```text
AWS Serverless Architecture  ·  Go Microservices  ·  Agentic LLMs & Guardrails  ·  IaC (CDK)  ·  CI/CD
```

</div>

---

### ⚡ Technical Summary

Computer Engineering builder specializing in production serverless architectures, Go distributed tools, and responsible agentic AI pipelines. I focus on high-velocity deployment, strict security boundaries (socket-level SSRF defense, prompt-injection guardrails), and hyper-optimized cloud operational costs (running full production systems between **$0.00 and $0.80/month**).

---

### 🏆 Flagship Production Systems

<table>
  <thead>
    <tr>
      <th width="35%">Project</th>
      <th width="45%">Architecture & Technical Highlights</th>
      <th width="20%">Demos & Source</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <strong>AreWeUpYet</strong><br/>
        <em>Multi-Tenant Synthetic Uptime SaaS</em>
      </td>
      <td>
        • <strong>Go 1.22+</strong> probing engine running on AWS Lambda with EventBridge 1-minute cron.<br/>
        • <strong>Custom Socket-Dial SSRF Defense</strong> blocking DNS rebinding, internal subnets, and AWS IMDS (<code>169.254.0.0/16</code>).<br/>
        • <strong>HMAC-SHA256</strong> signed webhook dispatching and public status pages with 30s live polling.<br/>
        • AWS Amplify Gen 2 + AWS CDK, Cognito JWT tenant isolation, DynamoDB TTL.
      </td>
      <td>
        <a href="https://main.d3pikhz9umtg2m.amplifyapp.com/"><strong>🚀 Live Production</strong></a><br/>
        <a href="https://github.com/pjpangilinan/areweupyet">📂 GitHub Repo</a>
      </td>
    </tr>
    <tr>
      <td>
        <strong>Deony</strong><br/>
        <em>Generative AI Media Archive & Critic Agent</em>
      </td>
      <td>
        • <strong>Amazon Bedrock Runtime</strong> (Claude 3 Haiku / Nova) powering "Deonysus" AI critic agent.<br/>
        • <strong>AWS Bedrock Guardrails:</strong> Pre-inference prompt injection/jailbreak defense and real-time PII redaction (<code>[REDACTED_PII]</code>).<br/>
        • <strong>Serverless Stack:</strong> React 19, AWS Lambda (ARM64), API Gateway v2, Cognito, and 4 on-demand DynamoDB tables with GSIs.
      </td>
      <td>
        <a href="https://d1cdomhzh1pe4j.cloudfront.net"><strong>🚀 Live Production</strong></a><br/>
        <a href="https://github.com/pjpangilinan/deony">📂 GitHub Repo</a>
      </td>
    </tr>
    <tr>
      <td>
        <strong>DGOS</strong><br/>
        <em>Digital Guest Ordering System (~$0.80/mo)</em>
      </td>
      <td>
        • <strong>3 Independent SPAs</strong> (Customer, Kitchen, Admin) deployed via CloudFront.<br/>
        • <strong>Real-Time WebSockets</strong> via API Gateway with heartbeat reconnects and exponential backoff.<br/>
        • <strong>Enterprise CDK IaC:</strong> 7 DynamoDB tables with PITR, presigned S3 uploads, CloudWatch metrics, DLQs, and 255+ automated tests.
      </td>
      <td>
        <a href="https://dyk5iqkiyeb4c.cloudfront.net"><strong>🚀 Customer App</strong></a><br/>
        <a href="https://d2n6ostm7w9jzu.cloudfront.net"><strong>🚀 Admin App</strong></a><br/>
        <a href="https://github.com/pjpangilinan/dgos">📂 GitHub Repo</a>
      </td>
    </tr>
    <tr>
      <td>
        <strong>maylupa 🇵🇭</strong><br/>
        <em>Philippine Geospatial Infra & Cited AI ($0.00/mo)</em>
      </td>
      <td>
        • <strong>60 FPS WebGL:</strong> Deck.gl + MapLibre GL mapping 1,613 Philippine LGUs.<br/>
        • <strong>PSGC Data Pipeline:</strong> Unified CMCI, PSA poverty, DOH health, and Project NOAH climate flood risk data.<br/>
        • <strong>Grounded Bedrock AI:</strong> Direct citations from official government methodology docs with $0.00 vector-DB footprint.
      </td>
      <td>
        <a href="https://d251rdq8bbiuc2.cloudfront.net"><strong>🚀 Live Production</strong></a><br/>
        <a href="https://github.com/pjpangilinan/maylupa">📂 GitHub Repo</a>
      </td>
    </tr>
    <tr>
      <td>
        <strong>VOTECHAIN</strong><br/>
        <em>IoT Biometric Blockchain Voting System</em>
      </td>
      <td>
        • <strong>Hardware MFA:</strong> Raspberry Pi 5 + AS608 optical fingerprint sensor + RFID reader.<br/>
        • <strong>Immutable Ledger:</strong> Custom Python SHA-256 chained-block architecture.<br/>
        • <strong>Real-Time Transparency:</strong> Django Channels WebSockets streaming tallies to a public React dashboard.
      </td>
      <td>
        <a href="https://github.com/pjpangilinan/votechain">📂 GitHub Repo</a>
      </td>
    </tr>
  </tbody>
</table>

---

### 🛠️ Core Stack & Tooling

```
Languages:        Go  ·  Python  ·  TypeScript  ·  JavaScript  ·  C++  ·  SQL  ·  Bash
Cloud & DevOps:   AWS (Lambda ARM64, DynamoDB, Bedrock, CloudFront, S3, Cognito, API Gateway, CDK)
                  Docker  ·  GitHub Actions (CI/CD)  ·  Linux  ·  Amplify Gen 2
Web & Real-Time:  React 19  ·  Vite  ·  Tailwind CSS  ·  WebSockets  ·  FastAPI  ·  Deck.gl  ·  MapLibre
Security & AI:    Bedrock Guardrails  ·  Prompt Injection Defense  ·  Socket SSRF Defense  ·  HMAC
```

---

### 📜 Professional Certifications

- 🏅 **AWS Cloud Solutions Architect Professional** — Amazon Web Services *(June 2026)*
- 🏅 **Go (GoLang) Specialization** — Packt *(June 2026)*
- 🏅 **Cisco Network Automation Engineering Fundamentals** — Cisco *(May 2026)*
- 🏅 **IBM DevOps, Cloud, and Agile Foundations** — IBM *(May 2026)*
- 🏅 **Google AI Professional Certificate** — Google *(April 2026)*
- 🏅 **Google Cloud Advanced Machine Learning** — Google Cloud *(October 2025)*
- 🏅 **Google Advanced Data Analytics Professional** — Google *(May 2025)*
- 🏅 **IBM Systems Analyst Professional** — IBM *(May 2026)*

---

### 📬 Connect With Me

- **Portfolio:** [pjpangilinan.github.io/kanbalio](https://pjpangilinan.github.io/kanbalio/)
- **LinkedIn:** [linkedin.com/in/patrick-james-pangilinan-490a41329](https://linkedin.com/in/patrick-james-pangilinan-490a41329)
- **Email:** [patrickjpangilinan@protonmail.com](mailto:patrickjpangilinan@protonmail.com)
- **Location:** Cavite, Philippines (Open to remote worldwide & hybrid)
