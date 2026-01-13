# System Architecture Overview

The system follows a simple client-centric architecture designed to study transaction behavior under constrained conditions.

## High-Level Components

- Client Application
- Local Persistence Layer
- Background Synchronization Worker
- Backend Simulator

## Architecture Flow

User Action
→ Local Persistence
→ Background Sync
→ Backend Simulator
→ Confirmation / Reconciliation
→ UI Update

## Rationale
Separating local persistence from network synchronization allows the system to remain usable even when external dependencies fail.

## Limitations
This architecture prioritizes clarity and reasoning over production-level completeness.
