# Bernard Vivian
### Developer · Web & Android · Practical Software

I build useful software for real workflows: student tools, business websites, and AI-assisted applications. My focus is on shipping usable products, making the underlying logic understandable, and improving reliability through testing and iteration.

**Based in Puducherry, India** · [GitHub](https://github.com/ViviBeri) · [LinkedIn](https://www.linkedin.com/in/berivivi)

---

## Selected work

### GradeCalc — SGPA & CGPA Calculator
A lightweight calculator built for SGC Pondicherry students. It supports credit-weighted SGPA, semester-based CGPA, grade conversion, and an installable PWA experience with offline support.

- **[Open the live app](https://gradecalc-sgc.netlify.app/)**
- [Source code](https://github.com/ViviBeri/gradecalc-app)
- [Calculation tests](https://github.com/ViviBeri/gradecalc-app/blob/main/tests/gradecalc-core.test.cjs)
- **Engineering focus:** grade boundaries, credit-weighted calculations, absent/failed subjects, input validation, installability, and offline behavior.
- **Stack:** HTML, CSS, JavaScript, PWA manifest, service worker, Node.js test runner.

### OneClick AI Cover — Local AI audio workflow

A free, open-source, Windows-first desktop project designed to separate vocals from a track, convert vocals with an authorized RVC voice model, remix them with the instrumental, and export audio locally—without paid APIs or cloud inference.

- [Source code](https://github.com/ViviBeri/OneClick-AI-Cover)
- [Verification plan](https://github.com/ViviBeri/OneClick-AI-Cover/blob/main/docs/verification.md)
- [Latest Windows CI run](https://github.com/ViviBeri/OneClick-AI-Cover/actions/workflows/windows-checks.yml)
- **Engineering focus:** local audio-processing workflow, Demucs vocal separation, RVC CLI integration, audio mixing/export, managed setup, and automated smoke checks.
- **Stack:** Python, Gradio, Demucs, RVC integration, FFmpeg, GitHub Actions.
- **Status:** Early integration build. CI smoke checks have passed, but clean-machine installer validation and complete end-to-end conversion are still pending. This is a local desktop application, not a hosted browser demo.

### KVB ENTERPRISES — Business services website
A live website for a local business offering tax and registration assistance. The site includes service information, English/Tamil content, location pages, and enquiry-focused flows.

- **[Visit the live website](https://viviberi.github.io/tax-business/)**
- [Source code](https://github.com/ViviBeri/tax-business)
- **Engineering focus:** responsive static pages, service-oriented navigation, bilingual content, SEO basics, and lead-generation interactions.
- **Stack:** HTML, CSS, JavaScript, Python build tooling, GitHub Pages.

### Nexora AI — AI-assisted workspace
An in-progress application exploring an approval-based workflow for AI-assisted tasks. The project is being developed with a web dashboard and backend persistence; end-to-end behavior is still under validation.

- [Repository](https://github.com/ViviBeri/nexora-ai) *(private repository; access may be required)*
- **Engineering focus:** separating the UI and API, persistence, and keeping human approval in the workflow.
- **Stack:** React, TypeScript, FastAPI, SQLite.
- **Status:** In development — not presented as a production-ready demo.

---

## Engineering in practice

I prefer evidence in the code over long lists of technology badges. Examples from the projects above:

- **Frontend delivery:** build and maintain responsive web interfaces with HTML, CSS, and JavaScript.
- **Offline-first behavior:** use a PWA manifest and service worker to support installation and offline use in GradeCalc.
- **Calculation correctness:** maintain automated tests for grade boundaries, absent/failed subjects, credit-weighted SGPA, and CGPA behavior in GradeCalc.
- **Deployment:** publish working static sites through Netlify and GitHub Pages.
- **Workflow automation:** maintain GitHub Actions workflows for repository automation.
- **Backend exploration:** develop Nexora AI with a React/TypeScript frontend and a FastAPI/SQLite backend.

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
