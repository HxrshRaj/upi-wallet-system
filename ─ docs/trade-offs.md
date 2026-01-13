# Design Trade-offs

## Offline-First vs Strict Online Validation

**Offline-First**
- Better reliability
- Higher implementation complexity

**Strict Online**
- Simpler logic
- Poor experience under instability

## Consistency vs Latency
- Immediate feedback improves UX
- Strong consistency may delay responses

## Decision
For user-facing payment systems, reliability and clarity are prioritized over strict immediacy.
