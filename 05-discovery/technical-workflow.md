# Technical Workflow Map

> **Simulation:** This represents a hypothetical environment derived
> from the simulated discovery conversation. It is not Figma's actual
> architecture.

## Current-State Workflow

```text
                 SECURITY MONITORING
                         │
                         ▼
                    ALERT CREATED
                         │
                         ▼
                  SECURITY ENGINEER
                         │
              ┌──────────┼──────────┐
              │          │          │
              ▼          ▼          ▼
            Cloud     Identity   Application
           Context     Context      Logs
              │          │          │
              └──────────┼──────────┘
                         │
                         ▼
                    KUBERNETES
                      CONTEXT
                         │
                         ▼
                  MANUAL CORRELATION
                         │
                         ▼
                    INVESTIGATION
                         │
                         ▼
                  SECURITY DECISION
                         │
                  ┌──────┴──────┐
                  │             │
                No Fix         Fix
                                │
                                ▼
                      PLATFORM ENGINEERING
                                │
                                ▼
                         INFRASTRUCTURE
                          REMEDIATION