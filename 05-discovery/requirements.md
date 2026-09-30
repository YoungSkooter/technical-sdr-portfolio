# Technical Requirements

> **Simulation:** Requirements below are derived from hypothetical
> discovery responses.

## Functional Requirements

### 1. Context Gathering

The solution should be able to gather relevant context from multiple
technical systems.

Potential sources:

- Cloud
- Identity
- Application telemetry
- Kubernetes
- Security monitoring

---

### 2. Correlation

The system should correlate information across those sources.

---

### 3. Investigation

The system should assist with determining:

- What happened
- Which resources are involved
- What identities are involved
- What systems are affected
- What action may be required

---

### 4. Human Approval

High-risk remediation decisions should remain under human control.

---

### 5. Engineering Integration

The workflow should connect to the existing engineering remediation
process.

---

# Non-Functional Requirements

Potential requirements:

- Security
- Access control
- Auditability
- Reliability
- Scalability
- Data protection
- Integration reliability
- Operational visibility

---

# Technical Questions for SE

The SDR should not attempt to answer these independently.

The Solutions Engineer should validate:

- API availability
- Authentication requirements
- Authorization model
- Data ingestion architecture
- Integration architecture
- Deployment model
- Network requirements
- Data residency
- Security controls
- Performance requirements
- Existing infrastructure compatibility

---

# SDR → SE Boundary

## SDR Owns

- Business context
- Problem
- Impact
- Urgency
- Stakeholders
- High-level environment
- Requirements discovery
- Next-step coordination

## SE Owns

- Architecture
- Integration feasibility
- Technical implementation
- Security architecture
- Product configuration
- Technical validation
- Proof of concept

The SDR should understand enough technical detail to identify the
right questions without pretending to be the technical authority on
product implementation.