# Logitech DevStudio 2026 — Track 1 Phase-1 Concept Brief (1 page)

## Project Title
**FlowPilot: Context-Aware IDE Control for MX Creative Console + MX Master 4 & Actions Ring**

## One-Liner
FlowPilot turns Logitech input devices into an adaptive command surface for coding, review, and debugging workflows in VS Code—reducing context switching and speeding up high-focus work.

## Problem
Developers lose time and cognitive flow by constantly switching between keyboard shortcuts, IDE panels, terminal commands, code assistant prompts, and PR checklists. Existing macro tools are static and do not adapt to coding context (e.g., lint errors, failing tests, or active refactor/review phases).

## Solution
FlowPilot is an Actions SDK plugin concept that maps context-aware dev actions to Logitech controls:

- **MX Creative Console** for glanceable state + quick scene switching.
- **MX Master 4 + Actions Ring** for mode changes and single-action execution.

The plugin adapts commands based on IDE context and a user-selected behavior profile.

## Core Features (Phase-1 Concept Scope)
1. **Adaptive Review Mode (VS Code-first):**
   - Uses public VS Code extension signals (diagnostics/problems, test status, git diff size) to infer work mode:
     - Build/Fix
     - Refactor
     - Review/PR prep
   - **Important scope note:** no claim of direct Cursor suggestion-stream integration.

2. **Creativity Preference (Not raw model temperature):**
   - User setting with three levels: **Conservative / Balanced / Exploratory**.
   - Changes template style and suggestion breadth for generated prompts/actions.
   - **Important scope note:** framed as plugin-level behavior preference, not direct model-temperature control.

3. **One-Press Workflow Actions:**
   - Summarize current git diff
   - Generate tests for changed files
   - Create PR checklist draft
   - Trigger “explain failing diagnostics” prompt scaffold
   - Run project-defined command presets (lint/test/build)

4. **Device Feedback (supported channels only):**
   - On-screen notifications and control-label updates through the plugin workflow.
   - **Important scope note:** no claim of dial resistance/haptic-force control.

## Why it is Novel
Most dev macro setups are fixed. FlowPilot is context-aware: one physical control surface behaves differently based on detected coding phase and user preference profile, while staying within currently supportable SDK/API constraints.

## Target Users
- Professional software developers
- Technical leads and reviewers
- DevRel engineers/demo builders
- Power users of Logitech productivity hardware

## Impact
- Reduce micro-friction from repetitive IDE actions
- Improve code-review consistency with repeatable checklists
- Lower context-switch overhead in debugging/refactor loops
- Enable accessible, ergonomic control paths for repetitive workflows

## Viability & Go-to-Market
- Fits Logitech marketplace narrative (workflow productivity plugin)
- Clear user segment with existing hardware willingness-to-pay
- Expansion path: templates for languages/frameworks, team-shared action packs, enterprise distribution

## Implementation Path
- **Stack:** Logitech Actions SDK plugin + VS Code extension + local companion service
- **Phase-1 (this submission):** validated concept, UX flow, action taxonomy
- **Phase-2:** working prototype, telemetry-informed iteration, demo of end-to-end workflow

## Judging Alignment
- **Novelty:** adaptive control by coding context + preference profile
- **Impact:** faster and less fragmented developer workflows
- **Viability:** practical plugin distribution and expansion model
- **Implementation Quality:** focused, ergonomic UX designed around real IDE states
