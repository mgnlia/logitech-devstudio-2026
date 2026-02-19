# DialMind — Adaptive AI Context Interface for MX Creative Console
## Logitech DevStudio 2026 | Track 1: Actions SDK | Phase 1 Submission Draft (Corrected)

> This file is retained for compatibility with earlier references. Canonical submission copy lives in `concept-doc-v2.md`.

---

## Problem
Developers using AI coding assistants (Cursor, Copilot, Claude Code) still perform frequent context switches to inspect and apply suggestions. These interruptions break flow during high-focus development work.

## Concept
DialMind maps MX Creative Console dials, buttons, and LED feedback to editor-visible coding context so developers can interact with AI workflows without leaving keyboard flow.

### Core controls
- **Left dial:** cycle active suggestions
- **Right dial:** suggestion creativity preference (conservative → exploratory)
- **Center button:** accept top suggestion (long-press dismiss/snooze)
- **Top-left button:** jump to next error/diagnostic
- **Top-right button:** toggle AI-assist session mode
- **LED ring:** ambient state signal (suggestion-ready, paused, debug urgency)

## Adaptive behavior (novelty)
DialMind reconfigures mappings based on context:
- **Writing mode:** baseline productivity mappings
- **Review mode:** suggestion navigation + acceptance
- **Debug mode:** diagnostics navigation + quick-fix flow

## Technical accuracy constraints
- **No dial resistance/haptic-force claim:** Actions SDK supports input events and LED output, not force-feedback control.
- **No raw model temperature API claim:** creativity preference is a plugin UX setting, not direct model-parameter control.
- **Cursor scope constrained:** implementation relies on VS Code-compatible public APIs and editor-visible/polling heuristics, not private Cursor suggestion-stream APIs.

## Impact & viability
- Addresses high-frequency AI-coding interaction friction
- Strong device-market fit for Logitech ecosystem users
- Freemium path: Free core, Pro advanced mappings/profiles, Enterprise managed deployment

## Implementation plan
- Logitech Actions SDK (C#) for hardware I/O and LED signaling
- VS Code extension APIs for diagnostics/context signals
- Local companion process for state orchestration (privacy-first)
- Phase 1: concept + architecture + pitch assets
- Phase 2: working prototype (if selected)

---

For final submission text, use `concept-doc-v2.md` and `devpost-criteria-mapped-copy-v3.md`.
