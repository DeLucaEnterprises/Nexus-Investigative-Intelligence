# Contributing to NEXUS Investigation Intelligence

Thank you for your interest in contributing. NEXUS is a mission-driven tool built to support missing persons investigations and open-source intelligence work. Every improvement helps find people.

---

## Review Process

All contributions go through **Mark DeLuca** for review before being merged. No code reaches the `main` branch without approval. This keeps the platform stable and mission-focused.

---

## How to Contribute

### 1. Fork the repository

Click **Fork** in the top-right corner of the GitHub page. This creates your own copy of the repo.

### 2. Create a branch

In your fork, create a branch for your change:

```bash
git checkout -b feature/your-feature-name
# or
git checkout -b fix/bug-description
```

Branch naming conventions:
- `feature/` — new functionality
- `fix/` — bug fixes
- `docs/` — documentation only
- `refactor/` — code cleanup with no behavior change

### 3. Make your changes

NEXUS is a single HTML file (`nexus-investigation.html`). All HTML, CSS, and JavaScript live in that one file. Keep it self-contained — no external dependencies, no CDN links that could break offline use.

**Guidelines:**
- Test in Chrome and Firefox before submitting
- Keep the dark theme and existing color variables (`--accent`, `--bg`, `--panel`, etc.)
- Do not add tracking, analytics, or any external calls beyond the existing Anthropic API integration
- Do not introduce breaking changes to the `.nxs` file format without a migration path
- Preserve offline functionality — the core tool must work without internet

### 4. Open a Pull Request

Go to your fork on GitHub and click **Compare & pull request**.

Fill out the PR template completely — incomplete PRs may be closed without review.

---

## What We're Looking For

**High priority:**
- Bug fixes
- Performance improvements to the physics graph
- Accessibility improvements
- New node types relevant to investigations
- Import/export format support
- Timeline improvements
- UI polish that fits the existing design language

**Please discuss first (open an Issue before building):**
- Major architectural changes
- New external dependencies
- Changes to data storage format
- New AI/API integrations

**Out of scope:**
- Features that require a server or account
- Anything that phones home without explicit user action
- UI changes that break the existing visual style

---

## Bug Reports

Open a GitHub Issue with:
- What you expected to happen
- What actually happened
- Steps to reproduce
- Browser and OS
- Any console errors (press F12 → Console tab)

---

## Feature Requests

Open a GitHub Issue tagged `enhancement`. Describe the use case — what investigation scenario does this help with? Features tied to real investigative workflows get prioritized.

---

## Code of Conduct

NEXUS is built in service of finding missing people and supporting legitimate investigations. All contributors are expected to engage professionally and in good faith. Contributions intended to enable surveillance, harassment, or illegal activity will be rejected and the contributor banned.

---

## Contact

**Mark DeLuca** — MadigrayFoundation@gmail.com  
DeLuca Industries / The MadiGray Foundation
