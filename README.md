# The GFG Open Source Forge

> *Igniting student projects into collaborative, community‑driven open source.*

[![Status](https://img.shields.io/badge/status-active-success)](#) [![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen)](#) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Code of Conduct](https://img.shields.io/badge/code%20of%20conduct-GFG%20Forge-blue)](CODE_OF_CONDUCT.md)

---

## 🧭 Mission

The **GFG Open Source Forge** identifies promising **student‑led projects** and turns them into **open-source initiatives** maintained under the **GeeksforGeeks Student Chapter**. Students learn real‑world software lifecycles, teamwork, code review, and project governance while building public portfolios.

---

## 📌 Who should read this?

* **Project Creators** — want to submit a project and become a Maintainer.
* **Contributors** — want to pick issues and submit Pull Requests.
* **Club Core Team** — run the cycle, shortlist, and adopt projects.

Use the **Quick Start** below to jump in.

---

## ⚡ Quick Start

### For Contributors (5 steps)

1. **Find an issue:** Browse the current Forge project(s): `Issues → good first issue` / `help wanted`.
2. **Fork & clone:**

   ```bash
   git clone https://github.com/<your-username>/<forge-project>.git
   cd <forge-project>
   ```
3. **Create a branch:**

   ```bash
   git checkout -b feat/<short-topic>
   ```
4. **Commit using Conventional Commits:**

   ```bash
   git add .
   git commit -m "feat(ui): add navbar links"
   git push origin feat/<short-topic>
   ```
5. **Open a PR:** From your fork → *Compare & pull request* → Fill PR template → Submit.

> 🔎 Tip: Prefer issues labeled **good first issue** to start. Join `#forge-<project-name>` on Discord for help.

### For Project Creators (3 steps)

1. **Submit your project** during **Week 1–2** using the monthly form (see **Submission** section).
2. **Pitch & demo** in **Week 3** at the Showcase Event.
3. If selected, **become the Maintainer** (2–3 months) and onboard your repo into the Forge.

---

## 📆 Monthly Cycle (4 Phases)

```
W1–2  ▶  Phase 1: Showcase (Call for Projects, Shortlisting)
W3    ▶  Phase 2: Pitch (Live demos + Community voting + Judges)
W4    ▶  Phase 3: Adoption (Winner onboarded into GFG Org)
∞     ▶  Phase 4: Foundry (Open contributions, active development)
```

### Phase 1 — The Showcase (Week 1–2)

* **Call for Submissions** announced across Discord/Instagram/Class groups.
* **Shortlisting (Top 3–5)** by the Selection Committee.

**Judging rubric (0–10 each, weight shown):**

| Criterion                | Weight | What we look for                            |
| ------------------------ | -----: | ------------------------------------------- |
| Potential Impact         |    30% | Real problem, clear beneficiaries           |
| Collaboration Scope      |    25% | Roadmap, modularity, many contributor paths |
| Technical Foundation     |    25% | Structure, documentation, tests, build      |
| Innovation & Originality |    20% | Creativity, differentiation                 |

> **Score =** 0.30×Impact + 0.25×Collab + 0.25×Tech + 0.20×Innovation

### Phase 2 — The Pitch (Week 3)

* **5–7 min live demo** per shortlisted project.
* **Decision = 50% community vote + 50% committee score.**

### Phase 3 — The Adoption (Week 4)

* Winner announced in a **Forging Ceremony**.
* Repo **transferred/forked** into the **GFG Club GitHub Org**.
* Creator becomes **Project Maintainer** (2–3 months) and completes onboarding checklist (below).

### Phase 4 — The Foundry (Continuous)

* **Call for Contributors** posted.
* Dedicated Discord channel `#forge-<project-name>` opened.
* Issues labeled, milestones set, releases tracked.

---

## 📮 Submission (Project Creators)

> Use the monthly **Call for Projects** form: **[Submit Here](https://forms.gle/YBfjQisxVro1v7pm9)**

**What to prepare:**

* **Title & 1–2 line pitch**
* **Problem statement & users**
* **GitHub repo link** (public; minimal README)
* **Tech stack**
* **Demo link** (screenshots/GIF/video optional)
* **Roadmap** (next 4–8 weeks)
* **Contributor areas** (backend, frontend, docs, testing, UX, data, etc.)

**Eligibility:** student‑led, active or prototype‑ready, open to collaboration, feasible to maintain.

---

## 🧑‍⚖️ Governance & Roles

* **Project Maintainer (PM):** originator/lead; triages issues, reviews PRs, plans releases.
* **Core Reviewers:** senior contributors who co‑review PRs.
* **Contributors:** pick issues, submit PRs, propose features.
* **Selection Committee:** Club Tech Lead, President, (optional) Faculty Advisor.

**Maintainer Rotation:** After 2–3 months, PM can:

* continue as PM, or
* rotate to **Mentor** role and nominate a new PM from active contributors.

---

## 🏗️ Repository Standards (Forge Projects)

Recommended structure (adapt as needed):

```
<project-root>/
├── README.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── LICENSE
├── docs/
│   ├── architecture.md
│   └── roadmap.md
├── src/
├── tests/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md
│   │   ├── feature_request.md
│   │   └── improvement.md
│   └── PULL_REQUEST_TEMPLATE.md
└── ci/ (optional)
```

**Standard issue labels:** `good first issue`, `help wanted`, `bug`, `feature`, `design`, `documentation`, `discussion`, `blocked`, `in progress`.

---

## 🤝 Contribution Workflow

### 1) Pick an issue

* Filter by `good first issue` or `help wanted`.
* Ask clarifying questions in the issue or on Discord.

### 2) Fork & branch

```bash
git fork # or use GitHub UI
git clone https://github.com/<your-username>/<forge-project>.git
cd <forge-project>
git checkout -b feat/<topic>   # or fix/<topic>, docs/<topic>
```

### 3) Set up and run locally

*See the project’s README for stack‑specific steps. Typical example:*

```bash
# Example: Node
npm install
npm run dev

# Example: Python
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
pytest -q
```

### 4) Commit with Conventional Commits

* **Types:** `feat`, `fix`, `docs`, `style`, `refactor`, `perf`, `test`, `build`, `ci`, `chore`.
* **Example:** `feat(auth): add JWT refresh tokens`

### 5) Keep your branch updated

```bash
git remote add upstream https://github.com/<org>/<forge-project>.git
git fetch upstream
git rebase upstream/main
```

### 6) Open a Pull Request

* Fill the PR template & checklist.
* Link the issue: `Closes #123`.
* Pass CI and address review comments.

### 7) Review & Merge

* Reviewer/PM requests changes or approves.
* Squash‑merge preferred for clean history.

---

## ✅ Onboarding Checklist (for Adopted Project Maintainers)

* [ ] Transfer repo to **GFG Club Org** or fork + enable Discussions.
* [ ] Add/refresh **README**, **CONTRIBUTING**, **CODE\_OF\_CONDUCT**, **LICENSE**.
* [ ] Create **docs/roadmap.md** with milestones & release plan.
* [ ] Open **Issues** (label several as `good first issue`).
* [ ] Set up basic **CI** (lint/tests) if applicable.
* [ ] Create Discord channel `#forge-<project-name>`.
* [ ] Post **Call for Contributors** with starter tasks.

---

## 🧩 Templates (copy into your project)

### `.github/ISSUE_TEMPLATE/bug_report.md`

```markdown
---
name: Bug report
about: Report a bug to help us improve
labels: bug
---

**Describe the bug**
A clear and concise description.

**To Reproduce**
Steps to reproduce the behavior.

**Expected behavior**
What you expected to happen.

**Screenshots / logs**
If applicable.

**Environment**
OS, Browser/Runtime, Version.

**Additional context**
Add any other context here.
```

### `.github/ISSUE_TEMPLATE/feature_request.md`

```markdown
---
name: Feature request
about: Suggest an idea for this project
labels: feature
---

**Problem**
What problem does this feature solve?

**Proposed solution**
Describe the solution you'd like.

**Alternatives**
Any alternatives considered?

**Additional context**
Screenshots, references, etc.
```

### `.github/ISSUE_TEMPLATE/improvement.md`

```markdown
---
name: Improvement
about: Quality improvements (refactor, docs, tests, DX)
labels: improvement
---

**Area**
Code quality / Documentation / Testing / DevX / Performance

**Proposal**
What and why?

**Acceptance criteria**
- [ ] Clear, testable outcomes
```

### `.github/PULL_REQUEST_TEMPLATE.md`

```markdown
## Summary
Explain the change and why it’s needed.

## Type of change
- [ ] feat
- [ ] fix
- [ ] docs
- [ ] refactor
- [ ] test
- [ ] chore/ci

## Related issues
Closes #<id>

## How to test
Steps / commands to verify.

## Checklist
- [ ] I read CONTRIBUTING.md
- [ ] I added/updated tests
- [ ] I updated docs (README / docs/*)
- [ ] My changes pass lint/CI
```

---

## 🗂 Example Label Meanings

* **good first issue** — Beginner‑friendly; well‑scoped.
* **help wanted** — Maintainer explicitly requests help.
* **blocked** — Needs another task/decision first.
* **design** — UI/UX tasks (Figma, flows, assets).
* **documentation** — README/docs/site updates.
* **discussion** — Needs community input.

---

## 🗺 Roadmap (Program‑level)

* ✅ Launch Forge program
* 🔜 Adopt first project into GFG Org
* 🔜 Host contributor onboarding sprint
* 🔜 First community release (v0.1.0)
* 🔜 Semester hackathon featuring Forge projects

> Each project maintains its own `docs/roadmap.md` with milestones and releases.

---

## 📣 Communications

* **Discord:** `#forge-<project-name>` (replace with actual link)
* **Announcements:** GFG Club Instagram & Discord
* **Office hours:** Weekly 30–45 min maintainer check‑ins (time announced per project)

---

## 🔐 Code of Conduct & License

Participation is governed by our **[Code of Conduct](CODE_OF_CONDUCT.md)**. By contributing, you agree to follow it.

Unless stated otherwise, projects are licensed under **MIT** (see each repo’s `LICENSE`).

---

## ❓ FAQ

**Q: I’m a beginner. Where do I start?**
A: Look for `good first issue`, read `CONTRIBUTING.md`, and say hello on Discord.

**Q: Can I submit a non‑web project?**
A: Yes. Any tech stack is welcome (web, mobile, data/AI, tooling, etc.).

**Q: What if my project isn’t selected this month?**
A: You can iterate and resubmit next month. We share feedback after shortlisting.

**Q: How long does Maintainer duty last?**
A: Typically **2–3 months**, with an option to extend or rotate to a Mentor role.

**Q: Can alumni contribute?**
A: Yes, contributions are open. Maintainer roles prioritize current students.

---

## 🙌 Acknowledgements

Inspired by open‑source communities everywhere and powered by the **GeeksforGeeks Student Chapter**.

---

### Replace‑Me Links (maintainers)

* Submission form: `https://forms.gle/REPLACE`
* Discord invite: `https://discord.gg/REPLACE`
* GitHub Org: `https://github.com/REPLACE-ORG`
* Banner image: `https://…/banner.png`

---

> Pro‑tip: Pin this repository to your GitHub Org and add the current Forge project(s) as submodules or link them prominently in the README.
