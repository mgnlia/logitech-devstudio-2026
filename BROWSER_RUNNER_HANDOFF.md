# Browser Runner Handoff Pack (Zero-Friction)
## Task: F9isJ8lX_ta5Ei5vAZZEV — Logitech DevStudio 2026 (Track 1)

Use this as an exact runbook for a browser-capable operator.

---

## 1) Deploy to Vercel (public `*.vercel.app` URL)

### Required env var
- `VERCEL_TOKEN` (**required**)

### Optional env vars (only if your account needs explicit scoping)
- `VERCEL_ORG_ID`
- `VERCEL_PROJECT_ID`

### Commands (copy/paste)
```bash
git clone https://github.com/mgnlia/logitech-devstudio-2026.git
cd logitech-devstudio-2026

# Optional: ensure CLI available
npm i -g vercel

# Production deploy (non-interactive)
vercel --prod --yes --token "$VERCEL_TOKEN"
```

### Expected output
- A production URL like: `https://<project>.vercel.app`

### Capture proof
- Save the deployed URL
- Screenshot terminal tail showing successful deploy + URL

---

## 2) Devpost submission (exact fields to fill)

Open: `https://devstudiologitech2026.devpost.com/`

### Track / category
- **Actions SDK (Track 1 / MX Creative Console)**

### Required fields and exact values

#### Project Name
```text
DialMind — Adaptive AI Context Interface for MX Creative Console
```

#### Description (paste full concept text)
Source:
- `concept-doc-v2.md` (repo root)

If a short field is shown, use:
```text
DialMind turns the MX Creative Console into a live, adaptive AI coding interface. Using the Actions SDK, it reads real-time context from VS Code-compatible editor signals (diagnostics, cursor position, and suggestion-state polling) and maps AI suggestion cycling, creativity preference, and error navigation to the Console's dials and buttons with LED ring feedback. The hardware reconfigures itself across writing, review, and debug modes. First physical-digital feedback loop for AI-assisted coding. Target: 40M+ developers reachable via Logitech Marketplace. Free + $5/mo Pro + Enterprise tiers.
```

#### Video URL
- Paste the public video URL (YouTube/Vimeo/Facebook Video/Youku)
- Script source for recording: `video-script-v2.md`

#### Team members
- Add all contributors exactly as required by Devpost UI

#### Rule acknowledgements
- Accept eligibility/rules checkboxes as prompted

### Submit
- Click **Submit project**
- Keep confirmation page open for proof capture

---

## 3) Evidence checklist (must-have artifacts)

All five artifacts are required to close F9.

1. **Registration proof**
   - Screenshot: Devpost registration/join confirmation
   - Must include visible timestamp (system clock or page timestamp)

2. **Deadline proof**
   - Screenshot: Devpost live countdown/timer showing deadline context
   - Must include visible timezone/date context

3. **Video proof**
   - Public URL to the uploaded ~1 min pitch video
   - Optional screenshot of video page with timestamp

4. **Submission proof**
   - Screenshot: Devpost submission receipt/confirmation page
   - Must include visible timestamp

5. **Deployment proof**
   - Public `https://*.vercel.app` URL
   - Screenshot of live site in browser

---

## 4) Post-back template (paste into task update)

```markdown
## F9 Human Ops Completion — Evidence Drop

### Links
- Vercel URL: <https://...vercel.app>
- Video URL: <https://...>

### Screenshots
- Registration proof: <link or attachment>
- Deadline timer proof: <link or attachment>
- Submission receipt proof: <link or attachment>
- Live site proof: <link or attachment>

### Timestamps (local + timezone)
- Registration: <YYYY-MM-DD HH:MM TZ>
- Submission: <YYYY-MM-DD HH:MM TZ>
- Vercel deploy: <YYYY-MM-DD HH:MM TZ>

### Validation
- [ ] All links public and accessible
- [ ] All screenshots readable
- [ ] Project status on Devpost shows submitted
```

---

## 5) Escalation rules

Escalate immediately if any of the below occurs:
- Devpost submission form fields differ from expected flow
- Track selection cannot be set to Actions SDK / Track 1
- Vercel deploy fails due to auth/scope
- Countdown/deadline conflicts with prior assumptions

When escalating, include screenshot + exact error text.
