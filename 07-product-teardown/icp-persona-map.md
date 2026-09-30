# ICP & Persona Map

> **PORTFOLIO SIMULATION**

---

## Ideal Customer Profile

Potential high-fit characteristics:

- Cloud-first organization
- Significant cloud infrastructure
- Kubernetes / containers
- Large engineering organization
- Dedicated security team
- Cloud Security function
- DevSecOps practices
- Multiple security tools
- Large volume of security findings
- Security-to-engineering workflow
- Complex cloud environments

These are **signals**, not automatic qualification criteria.

---

# Persona Map

## 1. CISO / Security Leadership

### Cares about

- Security risk
- Organizational exposure
- Security operations efficiency
- Risk reduction
- Compliance
- Engineering capacity
- Strategic security initiatives

### SDR lens

Don't lead with:

> "Here are our technical features."

Lead toward:

> "How does your organization currently prioritize cloud security risk across the environment?"

---

## 2. Cloud Security Engineer

### Cares about

- Cloud configuration
- Identity
- Vulnerabilities
- Workloads
- Attack paths
- Security posture
- Investigation
- Remediation

### SDR lens

Technical discovery is appropriate.

Example:

> "When a cloud finding comes in, how much context do engineers have before they decide whether it actually needs remediation?"

---

## 3. Security Engineer

### Cares about

- Investigation
- Detection
- Context
- Correlation
- Automation
- Incident response
- Security tooling

### SDR lens

Focus on workflow.

Example:

> "Where do your security engineers still have to manually correlate information across cloud, identity, and workload systems?"

---

## 4. DevSecOps

### Cares about

- Developer workflow
- Security integration
- CI/CD
- Infrastructure
- Kubernetes
- Vulnerabilities
- Remediation

### SDR lens

Focus on security becoming actionable without creating unnecessary developer friction.

---

## 5. Platform Engineering

### Cares about

- Infrastructure
- Kubernetes
- Developer platforms
- Reliability
- Access
- Operational workload
- Remediation ownership

### SDR lens

Focus on what security findings create downstream engineering work.

Example:

> "When security identifies an infrastructure issue, how does it get routed to the team responsible for fixing it?"

---

# Persona → Message

| Persona | Primary Lens |
|---|---|
| Security Leadership | Risk / efficiency |
| Cloud Security | Visibility / risk / prioritization |
| Security Engineering | Investigation / context / automation |
| DevSecOps | Security + engineering workflow |
| Platform Engineering | Infrastructure / remediation |

---

# Key Lesson

The product stays the same.

The **conversation changes**.

```text
                    SAME PRODUCT
                         │
        ┌────────────────┼────────────────┐
        ↓                ↓                ↓
     CISO          Security Engineer   Platform
        ↓                ↓                ↓
      Risk         Investigation      Remediation