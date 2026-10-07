# Account Overview — Figma

> **Simulation:** This is a Technical SDR account-research exercise based
> on publicly available information. It does not represent an actual
> interaction with Figma or its employees.

## Account

**Company:** Figma  
**Industry:** Software / SaaS  
**Business Model:** B2B SaaS  
**Sales Motion:** Enterprise + self-serve  
**Research Date:** September 2026  
**Portfolio Category:** Cloud Security / DevSecOps / CNAPP

---

## Why Figma?

Figma is a useful technical-sales research target because its own
engineering publications expose substantial infrastructure and security
complexity.

Public engineering material describes:

- AWS infrastructure
- Kubernetes
- Containerized workloads
- Security engineering
- Cloud infrastructure security
- Security data lakes
- SIEM / security alerting
- Automated security investigation
- Automated remediation
- Infrastructure and developer platforms

Figma has also published a detailed account of its migration of most
core services to Kubernetes. The migration followed an earlier period
where containerized workloads ran on AWS ECS.

Figma's security team has also publicly described security operations
covering cloud infrastructure, endpoints, SaaS applications, and
identity systems.

This makes the account technically relevant to a cloud-security /
DevSecOps sales motion.

---

## ICP Assessment

| Dimension | Evidence / Assessment |
|---|---|
| B2B SaaS | Figma is a software/SaaS company |
| Cloud infrastructure | AWS publicly documented |
| Containers | Publicly documented |
| Kubernetes | Majority of core services migrated to Kubernetes |
| Security engineering | Dedicated Security Engineering roles/publications |
| Cloud security | Publicly documented security work around AWS/cloud |
| Security operations | SIEM and security alerting publicly documented |
| Security automation | Extensive recent work publicly documented |
| Potential CNAPP relevance | Reasonable hypothesis |
| Actual buying need | **Unknown** |

The important distinction is that **technical fit is observable while
commercial opportunity is not yet established**.

---

## Current Technical Signals

### Signal 1 — AWS

Figma has publicly documented AWS as its cloud infrastructure provider,
including AWS-based enterprise data hosting and security architecture. :contentReference[oaicite:2]{index=2}

**SDR relevance:** Cloud-security tooling and AWS security workflows
are technically relevant.

---

### Signal 2 — Kubernetes

Figma published its migration of a majority of core services onto
Kubernetes in 2024. The company described moving from AWS ECS toward
Kubernetes as the next generation of its compute platform. :contentReference[oaicite:3]{index=3}

**SDR relevance:** Kubernetes introduces additional infrastructure,
identity, workload, configuration, and runtime-security considerations.

---

### Signal 3 — Security Engineering

Figma publicly publishes technical work from Security Engineering
Managers and Security Engineers, including cloud security,
sandboxing, vulnerability management, and internal security systems. :contentReference[oaicite:4]{index=4}

**SDR relevance:** Security Engineering is a legitimate technical
persona to investigate.

---

### Signal 4 — Security Operations

In July 2026, Figma described a security workflow using Panther as its
SIEM across cloud infrastructure, endpoints, SaaS applications, and
identity systems.

The workflow historically involved alerts being sent to Slack and
Asana for on-call engineers to investigate. Figma specifically
described gathering context as a major part of the manual work. :contentReference[oaicite:5]{index=5}

**SDR relevance:** This is a particularly strong discovery signal
because Figma itself has publicly identified investigation/context
gathering as an operational concern.

---

### Signal 5 — Security Automation

Figma's 2026 security engineering work describes an agentic system that
can investigate alerts, query audit logs, write code changes, open
pull requests, and learn from previous investigations. Figma reported a
71% reduction in alert time-to-resolution in that particular workflow. :contentReference[oaicite:6]{index=6}

**SDR relevance:** This suggests security automation is an active
engineering priority rather than merely a theoretical concern.

---

## Initial Sales Hypothesis

The evidence does **not** justify saying:

> "Figma has a cloud-security problem."

Instead, it supports a narrower hypothesis:

> **Figma operates a technically complex cloud/security environment
> where investigation, contextualization, ownership, and remediation
> workflows are important enough to receive dedicated engineering and
> automation investment.**

That creates a legitimate reason to investigate whether there are
remaining workflow gaps.

---

## Primary Persona

### Security Engineering

**Why:**

- Owns or contributes to security tooling
- Investigates security alerts
- Works with cloud/infrastructure systems
- Builds security automation
- Understands investigation and remediation workflows

### Secondary Personas

- Cloud Security
- Platform Security
- Platform Engineering
- Security Operations
- Security Leadership

---

## Discovery Hypothesis

The first conversation should investigate:

> **When an important cloud/security finding or alert is generated,
> how much context is automatically available, and where does the
> investigation still require human intervention?**

This is deliberately broader than pitching a specific product.

---

## What We Know vs What We Don't

### VERIFIED

- AWS is part of Figma's cloud infrastructure.
- Figma migrated a majority of core services to Kubernetes.
- Figma has dedicated security engineering functions.
- Figma uses Panther for security monitoring.
- Figma has publicly discussed security data lake usage.
- Figma has invested heavily in security automation.
- Figma has publicly discussed reducing alert investigation toil. :contentReference[oaicite:7]{index=7}

### HYPOTHESIS

- There may be remaining manual security investigation workflows.
- Cloud/Kubernetes security workflows may involve multiple systems.
- Security-to-engineering handoffs may create opportunities for
  automation or workflow improvement.

### UNKNOWN

- Whether Figma is evaluating a new security platform.
- Whether its existing security tooling has meaningful gaps.
- Whether a CNAPP vendor would be relevant to an active project.
- Budget.
- Procurement process.
- Decision authority.
- Current vendor satisfaction.
- Current cloud-security finding volume.

---

## SDR Objective

The objective is **not** to convince the prospect that it has a
problem.

The objective is to test whether the research hypothesis corresponds
to an actual workflow problem worth exploring.
