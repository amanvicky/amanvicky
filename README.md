# Hi, I'm Aman Elugam

Software engineer in Hyderabad, India. I spent two years teaching cybersecurity to engineering students at RapidSkill, and these days I build AI agents and computer-vision tools. Everything I make is open on GitHub, and everything I claim on this page links to code, tests or screenshots.

Most demos stop at "it should work". Mine end with test output or a source link.

## Try something right now, no install

**[OpenBroadcast Web](https://amanvicky.github.io/openbroadcast-web/)** — real-time eye gaze correction in your browser. Allow the camera, look away from the screen like you're reading notes, then turn the correction on and watch your eyes get pulled back to the lens. The face model downloads once (~3 MB), every frame is processed on your device, nothing is uploaded.

## Projects

### [Genesis](https://github.com/amanvicky/Genesis-Business-Decoding-Engine) — venture due diligence by a team of agents

Give it a company or just an idea and it returns an 18-tab report: business model, compliance per country, revenue from SEC filings, pricing, plus a red team that argues back. Every claim links a source. Runs on your machine, no API keys. Python, FastAPI, Next.js, MIT.

<p align="center">
  <img src="https://raw.githubusercontent.com/amanvicky/Genesis-Business-Decoding-Engine/main/docs/genesis-demo.gif" alt="Genesis decoding a company" width="85%">
</p>

### [leyp](https://github.com/amanvicky/leyp) — a job hunt tool I made for myself

Paste a job posting, it drafts a tailored resume and cover letter, tracks applications, reads my Gmail for replies. Nothing gets sent unless I approve it first. Next.js 16, React 19, Prisma 7, strict TypeScript, Vitest + Playwright.

### [OpenBroadcast](https://github.com/amanvicky/Open-Broadcast) and [Gazester](https://github.com/amanvicky/Gazester) — real-time gaze correction

The desktop versions: trained iris-segmentation models, calibration wizard, virtual camera for Zoom, Teams and OBS. The browser demo above is the light version. Python, OpenCV, MediaPipe.

### [GOD MODE](https://github.com/amanvicky/Skill-God-Mode) — dev squads and red teams in one Claude skill

A PM writes acceptance criteria, rival dev squads build, a red team attacks the result, and it doesn't ship until the tests pass. First run made a working game in about 23 minutes.

### [Human-Typer](https://github.com/amanvicky/Human-Typer) — human-like typing for Windows

AutoHotkey script that types your clipboard with human timing, typos and all. For demos and remote desktop sessions where instant typing looks fake.

## The rest of the shelf

### Apps & data

| Repo | What's in it |
|---|---|
| [openbroadcast-web](https://github.com/amanvicky/openbroadcast-web) | The browser gaze-corrector — MediaPipe face landmarks, WASM-speed math, zero upload |
| [Insta-followers-analyzer](https://github.com/amanvicky/Insta-followers-analyzer) | Checks who doesn't follow back, exports CSV, fully documented run-through in the README |
| [SQL](https://github.com/amanvicky/SQL) | 100 self-contained practice databases — hospital to crypto exchange, one disciplined 5-file format each |

### Small tools, built with tests from day one

| Repo | What's in it |
|---|---|
| [edgar-rev](https://github.com/amanvicky/edgar-rev) | One command, ten years of a company's revenue from SEC EDGAR — zero dependencies, CI on two Python versions |
| [gaze-meter](https://github.com/amanvicky/gaze-meter) | Attention analytics from a webcam — blinks/min, off-center %, focus score; the measurement half of the OpenBroadcast family |

### The DevOps year — one deploy, four levels of automation

The same "get a website running" idea, climbed from typed commands to a cluster. That ladder is the most honest thing I can show about how I learn:

| Repo | Level | What's inside |
|---|---|---|
| [AWS-basic](https://github.com/amanvicky/AWS-basic) | 0 — manual | EC2 by CLI + `stress` against CloudWatch alarms |
| [Bash-scripting](https://github.com/amanvicky/Bash-scripting) | 1 — script | 57 scripts incl. a Tomcat installer that branches per OS and an SSH fleet loop |
| [Python](https://github.com/amanvicky/Python) | 1.5 — scriptable | Fundamentals + idempotent user provisioning + a first Ansible playbook |
| [cloudformation-practice](https://github.com/amanvicky/cloudformation-practice) | 2 — declarative | Ten templates incl. a full `cfn-init` bootstrap |
| [Tf-EC2](https://github.com/amanvicky/Tf-EC2) | 2 — declarative | 211 dated Terraform cards: VPC → subnet → SG → instance |
| [Docker](https://github.com/amanvicky/Docker) | 3 — container | The first container exercise, three shutdown behaviors compared |
| [docker-in-depth](https://github.com/amanvicky/docker-in-depth) | 3 — container | CMD vs ENTRYPOINT lab, multistage builds, an Apache site container |
| [Jenkins-CI-CD](https://github.com/amanvicky/Jenkins-CI-CD) | 4 — pipeline | Full CI/CD: Sonar gate → Nexus → Docker → ECR → ECS |
| [kubernetes](https://github.com/amanvicky/kubernetes) | 5 — cluster | kops cluster on AWS, every object applied and broken on purpose |
| [Git](https://github.com/amanvicky/Git) | foundation | An unedited shell-history transcript of learning Git |

## Stack

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-strict-3178C6?logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-16-black?logo=next.js)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-007FFF?logo=google&logoColor=white)

## Now

- Junior software engineer, Hyderabad
- Open to work — fastest way to reach me is [LinkedIn](https://www.linkedin.com/in/aman-elugam/)
- One-page résumé: [amanvicky.github.io/resume](https://amanvicky.github.io/resume)
- HackerRank SQL (Advanced) certified
- Building small tools most weeks — the newest: [edgar-rev](https://github.com/amanvicky/edgar-rev) (SEC revenue CLI) and gaze-meter (attention analytics)
