# Research Notes

## Evidence Classification

| Classification | Meaning |
|---|---|
| VERIFIED | Directly supported by a public source |
| HYPOTHESIS | Reasonable inference that requires validation |
| UNKNOWN | Cannot be established through public research |

---

## Evidence Log

### E1 — AWS Infrastructure

**Observation:** Figma has publicly documented AWS as its cloud
infrastructure provider.

**Classification:** VERIFIED

**Source:** Figma — EU Hosting for Figma and FigJam Files

**Sales relevance:** Establishes AWS/cloud-security relevance.

---

### E2 — Kubernetes Migration

**Observation:** Figma migrated a majority of its core services to
Kubernetes and described Kubernetes as the next generation of its
compute platform.

**Classification:** VERIFIED

**Source:** Figma Engineering — How We Migrated onto K8s in Less Than
12 Months

**Sales relevance:** Establishes a significant Kubernetes/platform
engineering environment.

---

### E3 — Security Engineering

**Observation:** Figma publishes technical security work authored by
Security Engineers and Security Engineering Managers.

**Classification:** VERIFIED

**Sales relevance:** Confirms Security Engineering as a legitimate
technical persona.

---

### E4 — Security Monitoring

**Observation:** Figma states that Panther is used to run checks across
cloud infrastructure, endpoints, SaaS applications, and identity
systems.

**Classification:** VERIFIED

**Sales relevance:** Demonstrates a security monitoring and alerting
workflow spanning multiple environments.

---

### E5 — Investigation Context

**Observation:** Figma described gathering context as a major part of
historical on-call security work.

**Classification:** VERIFIED

**Sales relevance:** Strong discovery trigger around investigation
workflow and analyst/engineer toil.

**Important:** This does not mean the problem remains unresolved.
Figma subsequently described building an agentic system to reduce this
work.

---

### E6 — Security Automation

**Observation:** Figma built an agentic system capable of investigating
alerts, querying audit logs, writing code changes, opening pull
requests, and learning from prior investigations.

**Classification:** VERIFIED

**Sales relevance:** Strong evidence that security automation is an
active technical priority.

---

### E7 — Alert Time-to-Resolution

**Observation:** Figma reported a 71% reduction in alert
time-to-resolution from its agentic security workflow.

**Classification:** VERIFIED

**Sales relevance:** Demonstrates measurable business/operational
impact from security workflow automation.

**Caution:** This metric relates to Figma's described internal system
and should not be generalized as a benchmark for other companies.

---

# Hypotheses

## H1 — Remaining Investigation Friction

Figma may still have security investigations that require manual
context gathering despite its automation investments.

**Confidence:** Medium

**Validation question:**

> "You've invested heavily in automating alert investigation. Where do
> your engineers still have to manually gather context?"

---

## H2 — Cross-System Context

Security investigations may require information from multiple systems,
including cloud, identity, code, audit logs, and communication/ticketing
systems.

**Confidence:** High as a workflow hypothesis.

**Validation question:**

> "When an alert needs deeper investigation, which systems do engineers
> typically have to pull context from?"

---

## H3 — Security-to-Engineering Handoff

Some security issues may require code or infrastructure changes from
engineering teams.

**Confidence:** Medium

**Validation question:**

> "Once an investigation identifies something that needs a code or
> infrastructure change, how does that move into the engineering
> workflow?"

---

# Unknowns

We cannot establish from public research:

- Current cloud-security platform/vendor evaluation
- Current CNAPP requirements
- Current security-tooling gaps
- Number of alerts requiring manual investigation
- Current investigation SLA
- Number of engineers involved
- Current budget
- Active buying project
- Decision maker
- Procurement timeline
- Competitive vendors

These must be discovered rather than assumed.

---

# Research Conclusion

The account has strong **technical ICP fit**.

The most interesting observable signal is not simply:

> "Figma uses AWS and Kubernetes."

It is:

> **Figma is actively engineering its security investigation and
> remediation workflow.**

That creates a more specific and defensible outbound hypothesis.

The next SDR task is therefore **persona mapping**: identifying who
owns this workflow, who uses it, who influences it, and who could
eventually approve a solution.