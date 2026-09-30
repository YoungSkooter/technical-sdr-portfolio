# Technical Capabilities

> **PORTFOLIO SIMULATION**
>
> Independent technical product analysis based on publicly available information.

---

## Capability Map

| Capability Area | Technical Concept | SDR Interpretation |
|---|---|---|
| Cloud Security | Cloud infrastructure visibility | Understand the customer's cloud footprint |
| Security Posture | Misconfigurations / security risks | Identify potential exposure |
| Vulnerability Management | Vulnerable workloads/resources | Connect vulnerabilities to real context |
| Identity Security | Identities and permissions | Understand access-related risk |
| Kubernetes Security | Containers / clusters / workloads | Relevant to cloud-native organizations |
| Risk Context | Relationships between resources/signals | Reduce isolated-finding problem |
| Prioritization | Risk-based decision making | Help teams decide what matters |
| Remediation | Security-to-engineering workflow | Connect findings to action |

---

# Technical Mental Model

A useful way for an SDR to understand a cloud-security platform is:


                    CLOUD ENVIRONMENT
                           │
          ┌────────────────┼────────────────┐
          ↓                ↓                ↓
       Identity         Workloads        Resources
          │                │                │
          └────────────────┼────────────────┘
                           ↓
                    Security Signals
                           ↓
                      Correlation
                           ↓
                    Risk Context
                           ↓
                     Prioritization
                           ↓
                       Action
                           ↓
                     Remediation