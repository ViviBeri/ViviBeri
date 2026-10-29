# Bernard Vivian
### Turning Everyday Needs, Ideas & Imagination into Working Software

I turn day-to-day needs, ideas, and imagination into live, working projects. I build practical web apps, Android tools, AI-assisted workflows, and business solutions—and keep improving them through testing, feedback, and real-world use.

**Current build status:** GradeCalc is improving continuously · LeadFlow is under testing · Nexora AI and OneClick AI Cover are still in development.

**Based in Puducherry, India** · [GitHub](https://github.com/ViviBeri) · [LinkedIn](https://www.linkedin.com/in/berivivi)

---

## Project showcase

<p align="center">
  <a href="https://gradecalc-sgc.netlify.app/"><img src="https://raw.githubusercontent.com/ViviBeri/ViviBeri/main/assets/projects/gradecalc.svg" alt="GradeCalc project cover — live SGPA and CGPA calculator" width="48%" /></a>
  <a href="https://github.com/ViviBeri/LeadFlow"><img src="https://raw.githubusercontent.com/ViviBeri/ViviBeri/main/assets/projects/leadflow.svg" alt="LeadFlow project cover — Android lead management, under testing" width="48%" /></a>
</p>
<p align="center">
  <a href="https://github.com/ViviBeri/nexora-ai"><img src="https://raw.githubusercontent.com/ViviBeri/ViviBeri/main/assets/projects/nexora.svg" alt="Nexora AI project cover — human-reviewed AI workspace, in development" width="48%" /></a>
  <a href="https://github.com/ViviBeri/OneClick-AI-Cover"><img src="https://raw.githubusercontent.com/ViviBeri/ViviBeri/main/assets/projects/oneclick-ai-cover.svg" alt="OneClick AI Cover project cover — local audio workflow, in development" width="48%" /></a>
</p>
<p align="center">
  <a href="https://viviberi.github.io/tax-business/"><img src="https://raw.githubusercontent.com/ViviBeri/ViviBeri/main/assets/projects/kvb-enterprises.svg" alt="KVB ENTERPRISES — live business services website" width="48%" /></a>
</p>

*Project covers are visual summaries, not screenshots of running interfaces. Open each project to explore the app or source code.*

---

## Selected work

### GradeCalc — SGPA & CGPA Calculator
A continuously improving calculator for SGC Pondicherry students. It supports credit-weighted SGPA, semester-based CGPA, grade conversion, and an installable PWA experience with offline support. I refine it day by day as I find better ways to solve students’ real needs.

- **[Open the live app](https://gradecalc-sgc.netlify.app/)**
- [Source code](https://github.com/ViviBeri/gradecalc-app)
- [Calculation tests](https://github.com/ViviBeri/gradecalc-app/blob/main/tests.js)
- **Engineering focus:** grade boundaries, credit-weighted calculations, absent/failed subjects, input validation, installability, and offline behavior.
- **Stack:** HTML, CSS, JavaScript, PWA manifest, service worker, Node.js test runner.
- **Status:** Live and actively improving.

### OneClick AI Cover — Local AI audio workflow

A free, open-source, Windows-first desktop project designed to separate vocals from a track, convert vocals with an authorized RVC voice model, remix them with the instrumental, and export audio locally—without paid APIs or cloud inference.

- [Source code](https://github.com/ViviBeri/OneClick-AI-Cover)
- [Verification plan](https://github.com/ViviBeri/OneClick-AI-Cover/blob/main/docs/verification.md)
- [Latest Windows CI run](https://github.com/ViviBeri/OneClick-AI-Cover/actions/workflows/windows-checks.yml)
- **Engineering focus:** local audio-processing workflow, Demucs vocal separation, RVC CLI integration, audio mixing/export, managed setup, and automated smoke checks.
- **Stack:** Python, Gradio, Demucs, RVC integration, FFmpeg, GitHub Actions.
- **Status:** Still in development. CI smoke checks pass, but clean-machine installer validation and complete end-to-end conversion are not yet verified. This is a local desktop application, not a hosted browser demo.

### LeadFlow — Android lead management

An Android app for managing business leads and following up through WhatsApp. It is designed around manual, user-controlled outreach, with local lead storage and export options.

- [Source code](https://github.com/ViviBeri/LeadFlow)
- **Engineering focus:** Kotlin and Jetpack Compose UI, Room database, lead search and management, CSV/XLSX/PDF export, and WhatsApp link handoff without scraping or automatic message sending.
- **Stack:** Kotlin, Jetpack Compose, Room, Android.
- **Status:** Under testing — still being validated before it is presented as a finished release.

### KVB ENTERPRISES — Business services website
A live website for a local business offering tax and registration assistance. The site includes service information, English/Tamil content, location pages, and enquiry-focused flows.

- **[Visit the live website](https://viviberi.github.io/tax-business/)**
- [Source code](https://github.com/ViviBeri/tax-business)
- **Engineering focus:** responsive static pages, service-oriented navigation, bilingual content, SEO basics, and lead-generation interactions.
- **Stack:** HTML, CSS, JavaScript, Python build tooling, GitHub Pages.

### Nexora AI — AI-assisted workspace
An AI-assisted workspace for coordinating tasks with human review, version history, and explicit approval before finalization. The current milestone includes a React/TypeScript dashboard and a FastAPI prototype with SQLite persistence.

- [Repository](https://github.com/ViviBeri/nexora-ai) *(private repository; access may be required)*
- **Engineering focus:** separating the UI and API, persistence, and keeping human approval in the workflow.
- **Stack:** React, TypeScript, FastAPI, SQLite.
- **Status:** Still in development. Full local workflow validation, authentication/authorization, and deployment hardening remain before production use.

---

## Engineering in practice

I prefer evidence in the code over long lists of technology badges. Examples from the projects above:

- **Frontend delivery:** build and maintain responsive web interfaces with HTML, CSS, and JavaScript.
- **Offline-first behavior:** use a PWA manifest and service worker to support installation and offline use in GradeCalc.
- **Calculation correctness:** maintain automated tests for grade boundaries, absent/failed subjects, credit-weighted SGPA, and CGPA behavior in GradeCalc.
- **Deployment:** publish working static sites through Netlify and GitHub Pages.
- **Workflow automation:** maintain GitHub Actions workflows for repository automation.
- **Backend engineering:** develop Nexora AI with a React/TypeScript frontend and a FastAPI/SQLite backend.
- **Android app development:** build LeadFlow with Kotlin, Jetpack Compose, and Room while testing the lead-management and export workflows.
- **Local AI/audio tooling:** integrate audio-processing components in OneClick AI Cover and clearly separate CI smoke checks from full product verification.

### Tools and technologies used

**Web:** HTML · CSS · JavaScript  
**PWA & mobile:** Progressive Web Apps · Service Workers · Android app packaging  
**Backend & data:** Python · FastAPI · SQLite · TypeScript · React  
**Engineering workflow:** Git · GitHub · GitHub Actions · Node.js testing · Netlify · GitHub Pages

*These are technologies used in the projects above, not a claim of equal depth or professional certification in every tool.*

---

## How I approach projects

1. **Start with a real need** — define the user and the job the software should do.
2. **Build the smallest useful version** — prioritize the core workflow over decorative features.
3. **Validate behavior** — test important calculations and edge cases, then fix what fails.
4. **Ship and improve** — deploy the result, document limitations, and iterate based on actual use.

---

## Interactive Cursor Cat

<p align="center">
  <a href="https://viviberi.github.io/ViviBeri/cat-banner/" title="Open the interactive cursor-following cat">
    <img src="https://raw.githubusercontent.com/ViviBeri/ViviBeri/main/assets/cursor-cat-banner.svg" alt="Interactive Cursor Cat banner — click to open the live cursor-following demo" width="100%" />
  </a>
</p>

**Click the banner to try it.** The cat's eyes follow your pointer on the interactive webpage. GitHub README images are static, so the interaction runs on the linked page.

- [Open the interactive cat demo](https://viviberi.github.io/ViviBeri/cat-banner/)
- [View the HTML, CSS and JavaScript](https://github.com/ViviBeri/ViviBeri/blob/main/cat-banner/index.html)
- [View the banner artwork](https://github.com/ViviBeri/ViviBeri/blob/main/assets/cursor-cat-banner.svg)

---

## GitHub activity

My contribution graph is retained below. Automated activity visualizations are supplementary; the projects and their source code above are the primary evidence of my work.

<!-- Contribution Snake: keep the existing green contribution animation -->
<p align="center">
  <img
    src="https://raw.githubusercontent.com/ViviBeri/ViviBeri/output/github-contribution-grid-snake-dark.svg?v=2"
    alt="Green GitHub contribution graph animation"
    width="100%"
  />
</p>

---

## Contact

I'm interested in practical web and mobile projects, useful developer tools, and collaborations where clear implementation and reliability matter.

- [Connect on LinkedIn](https://www.linkedin.com/in/berivivi)
- [Browse all repositories](https://github.com/ViviBeri?tab=repositories)
