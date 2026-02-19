# Devpost-Ready Copy (Criteria-Mapped, Phase-1)

## Project Name
**FlowPilot**

## Tagline
Context-aware Logitech controls for faster coding, debugging, and code review workflows.

## Elevator Pitch (Short Description)
FlowPilot is a Track 1 concept plugin built around Logitech’s Actions ecosystem. It adapts controls on MX Creative Console + MX Master 4 & Actions Ring to the developer’s current VS Code state (diagnostics, tests, and diff context), so one press can trigger the right workflow action at the right time.

## Full Description
FlowPilot addresses a daily developer pain point: fragmented workflows across IDE panels, terminal commands, and AI-assisted review tasks. Instead of static macros, FlowPilot introduces adaptive action sets that change with coding context.

In Build/Fix mode, controls prioritize diagnostics and test remediation. In Refactor mode, controls prioritize transformation and validation tasks. In Review mode, controls prioritize diff summarization, checklist generation, and release-readiness actions.

Users can choose a **Creativity Preference** (Conservative, Balanced, Exploratory) that adjusts output style and breadth of generated scaffolds. This setting is plugin-level behavior tuning, designed for practical adoption in real teams.

FlowPilot is designed for Logitech’s developer-device ecosystem and can be delivered as a marketplace-ready productivity plugin with extensible action packs.

## What Makes This Project Innovative? (Novelty)
- Dynamic control mapping based on live coding context rather than static key macros.
- Workflow-aware command surfaces designed specifically for software development phases.
- Human-centered behavior presets (Creativity Preference) for different coding/review styles.

## What Problem Does It Solve? (Impact)
- Reduces context switching during coding and debugging.
- Speeds up repetitive review and PR preparation tasks.
- Improves consistency in team workflows through reusable action templates.

## Why Is It Feasible? (Viability)
- Clear platform fit: Logitech Actions plugin + VS Code extension integration path.
- Obvious user segment: developers already using Logitech productivity hardware.
- Expandable monetization path: premium action packs, team templates, enterprise rollout.

## Implementation Quality Plan
- Ergonomic interaction design with minimal cognitive overhead.
- Explicit mode visibility and predictable control behavior.
- Clean fallback behavior when context signals are unavailable.

## Built With / Platform Fit
- Logitech Actions SDK (Track 1)
- VS Code extension APIs (diagnostics/tests/source control context)
- Companion local service for orchestration

## Submission Assets Checklist (Devpost form)
- [x] Text description (this copy)
- [ ] 1-minute video pitch (YouTube/Vimeo public link)
- [x] Clear mapping to judging criteria (Novelty, Impact, Viability, Implementation Quality)
- [ ] Final form completion and submit
