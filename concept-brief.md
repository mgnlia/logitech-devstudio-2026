# DialMind — 1-Page Concept Brief
**Logitech DevStudio 2026 | Track 1 (Actions SDK) | Phase 1**

## Problem
AI coding tools (Cursor, Copilot, Claude Code) improve output, but interaction still breaks flow. Developers repeatedly leave keyboard focus to inspect, accept, reject, or tune suggestions. These micro-interruptions happen dozens of times per session and create real cognitive overhead.

At the same time, Logitech MX Creative Console hardware (dials, buttons, LED feedback) is underused in software engineering workflows.

## Concept
**DialMind** is an Actions SDK plugin that turns MX Creative Console into an adaptive physical interface for AI-assisted coding.

Instead of static shortcuts, DialMind changes mappings based on live editor context:
- **Writing mode:** normal editing controls and productivity shortcuts.
- **Review mode:** suggestion browsing/accept/reject controls become primary.
- **Debug mode:** diagnostics navigation and quick-fix workflows are prioritized.

The LED ring provides peripheral awareness (ready, paused, error urgency) so users stay focused on code.

## Core Interaction Model
- **Left dial:** cycle through active AI suggestions.
- **Right dial:** adjust suggestion preference (conservative → exploratory).
- **Center button:** accept top suggestion (long-press = dismiss/snooze).
- **Top-left button:** jump to next file/error.
- **Top-right button:** toggle AI-assist mode for current session.
- **LED ring:** contextual status feedback.

## Why This Is Novel
Most hardware workflows for creators are static macro mappings. DialMind introduces **context-aware remapping for AI coding state** (writing/review/debug), making the hardware surface adaptive to the developer’s cognitive mode.

This is not another shortcut pack; it is a continuously stateful interaction layer between IDE and physical controls.

## Impact
- Large and growing AI-assisted coding user base.
- Clear Logitech-device fit (MX control surface + premium desktop users).
- Immediate productivity value: fewer context switches, lower interaction friction, faster review/accept cycles.

## Viability
- **Distribution:** Logitech ecosystem + marketplace listing model.
- **Business model:** Free core mappings, Pro tier for profiles/sync/custom mappings, Enterprise deployment options.
- **Technical feasibility:** Actions SDK for hardware layer + IDE extension bridge for context state.

## Implementation Plan
### Phase 1 (this submission)
- Concept + architecture + UX definition.
- Criteria-mapped narrative and 60s pitch video script.

### Phase 2 (build stage)
- Actions SDK plugin for dial/button/LED control.
- IDE bridge (VS Code/Cursor) for suggestion and diagnostics context.
- Mode engine for adaptive remapping.
- Usability test loop and polish.

## Judging Criteria Alignment (Summary)
- **Novelty:** Adaptive physical interface for AI coding workflows.
- **Impact:** Reduces repeated interaction friction for active AI-coding users.
- **Viability:** Clear route to distribution, monetization, and expansion.
- **Implementation quality:** Scoped architecture with practical Phase-2 execution path.
