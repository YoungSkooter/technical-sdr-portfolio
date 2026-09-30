# Simulated Technical Discovery Call

> All prospect responses are hypothetical.

## Opening

**SDR:**

> "Thanks for taking the time. From our earlier conversation, my
> understanding is that you've already automated a significant part of
> security investigation, but there are still cases where engineers
> need to pull context from several systems.
>
> I'd like to understand the workflow in a little more detail — what
> systems are involved, where the manual work happens, and what you're
> trying to improve. Then we can figure out whether there's a technical
> fit worth exploring.
>
> Sound good?"

---

# Discovery 1 — Current Workflow

**SDR:**

> "Can you walk me through what happens from the moment an alert is
> generated?"

### Hypothetical Response

> "The alert originates from our security monitoring system. It gets
> routed to the security team. The engineer investigates it and may
> query cloud audit data, identity information, application logs, and
> other security data depending on the case."

### SDR Notes

```text
Detection
   ↓
Security Monitoring
   ↓
Security Engineer
   ↓
Cloud / Identity / Application Context
   ↓
Investigation