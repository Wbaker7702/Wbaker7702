# Hi, I’m Wes 👋

[![Wes’s GitHub stats](https://github-readme-stats.vercel.app/api?username=Wbaker7702&show_icons=true&theme=radical&rank_icon=github&hide_border=true)](https://github.com/anuraghazra/github-readme-stats)
[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com?user=Wbaker7702&theme=radical&hide_border=true)](https://github.com/denvercoder1/github-readme-streak-stats)
[![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Wbaker7702&layout=compact&theme=radical&hide_border=true)](https://github.com/anuraghazra/github-readme-stats)

---

🚀 Prompt Engineer • Student • Founder

Welcome — I’m Wes. I build with ML/AI, ship products fast, and learn in public. I’ve been “provisioned by Google” since age 13.

> “Provisioned by Google since 13. Green comes in many shades — so does innovation.”

---

## Table of contents
- [About](#about)
- [What I work on](#what-i-work-on)
- [Highlights & Projects](#highlights--projects)
- [Getting started / Local setup](#getting-started--local-setup)
- [Development & Build](#development--build)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

---

## About

- Machine Learning & applied LLMs
- Always learning, always shipping
- Founder / CEO with a builder mindset
- Focused on pragmatic, product-first engineering

### Fun fact
I’m green‑deficient, but I can still tell light green from dark green.  
_(If you know, you know.)_

---

## What I work on

I split time between:
- Building ML/LLM-backed products and prototypes
- Tooling and developer experiences (VS Code extensions, CLI tools)
- OSS contributions and learning-in-public projects

Check my pinned repositories and recent activity for current work.

---

## Highlights & Projects

A few project callouts (link to repos or demos as appropriate):

- declarative-vscode-extension — a VS Code extension for declarative workflows and productivity tooling.
- bootstrap (personal fork/experiments) — UI utilities, theme experiments, and component prototypes.
- sora (collaboration/ML infra experiments) — notebook and model orchestration explorations.

(Replace these with repo links or demo URLs you want to highlight.)

---

General recommendations for most projects:

Install Node.js 18+ (if JS/TS project)

Use npm or yarn to install dependencies:

npm install

# or

yarn

For VS Code extensions:

bash
# install deps
npm install
# compile if TypeScript
npm run compile
# run extension host (in VS Code: press

Development & Build (example workflows)

Use GitHub Actions to automate builds and tests. Example workflow files live under.github/workflows/(e.g. build.yml) to run Cl on pushes and PRs.

To create a local build/package (VSIX for extensions):

bash
npm install -g
vsce
vsce package

For security checks (Snyk) and linting, add Cl steps:

snyk test or snyk monitor in your Cl
npm run lint
npm test

Contributing

Thanks for wanting to contribute! A

suggested workflow:

1. Fork the repo

2. Create a branch: git checkout -b feat/your-feature

3. Make changes, add tests where appropriate

4. Run linters and tests locally

5. Push and open a pull request

Be sure to check CONTRIBUTING.md and any project-specific guidelines.

Contact
