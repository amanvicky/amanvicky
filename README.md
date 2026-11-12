# Hi, I'm Aman Elugam

Software engineer in Hyderabad, India. I spent two years teaching cybersecurity to engineering students at RapidSkill, and these days I build AI agents and computer-vision tools. Everything I make is open on GitHub, and everything I claim on this page links to code, tests or screenshots.

Most demos stop at "it should work". Mine end with test output or a source link.

## Try something right now, no install

**[Cleanroom](https://amanvicky.github.io/cleanroom/)** — paste a GitHub repo link and **run it live in your browser**: a disposable Python VM boots inside the tab, the repo's files load into memory, and you use the repo against it — real-time, free, no install, no account, no server. GUI apps run on an app screen: tkinter apps open a real window of HTML widgets right in the page. When you close the tab, nothing remains; there was never anything on your disk to begin with.

**[OpenBroadcast Web](https://amanvicky.github.io/openbroadcast-web/)** — real-time eye gaze correction in your browser. Allow the camera, look away from the screen like you're reading notes, then turn the correction on and watch your eyes get pulled back to the lens. The face model downloads once (~3 MB), every frame is processed on your device, nothing is uploaded.

**[Tokenizer Playground](https://amanvicky.github.io/tokenizer-playground/)** — type anything and watch a byte-level BPE tokenizer chop it into colored pieces, live. 400 merges trained on the repo's own corpus; the JS encoder is proven token-identical to the Python trainer. Nothing is uploaded.

**[Spamcheck](https://amanvicky.github.io/spamcheck/)** — a spam classifier actually *trained* on 5,574 real SMS messages (98.47% held-out accuracy), running live in your browser. The chips show which words push the verdict and by how much. The same model runs in the repo's terminal CLI — a CI gate proves both agree to nine decimal places.

## Projects

### [Genesis](https://github.com/amanvicky/Genesis-Business-Decoding-Engine) — venture due diligence by a team of agents

Give it a company or just an idea and it returns an 18-tab report: business model, compliance per country, revenue from SEC filings, pricing, plus a red team that argues back. Every claim links a source. Runs on your machine, no API keys. Python, FastAPI, Next.js, MIT.

<p align="center">
  <img src="https://raw.githubusercontent.com/amanvicky/Genesis-Business-Decoding-Engine/main/docs/genesis-demo.gif" alt="Genesis decoding a company" width="85%">
</p>

### [cleanroom](https://github.com/amanvicky/cleanroom) — run any repo in a disposable sandbox, leave zero trace

The AI-agent era means code from random repos gets executed all day — exactly the flow supply-chain attacks target. Cleanroom guards that loop: the [browser runner](https://amanvicky.github.io/cleanroom/) boots CPython (WebAssembly) inside the tab with no disk access and no network sockets; the CLI adds a static triage report (install hooks, secrets, typosquats, shell-profile persistence), a whitelist environment that hides every secret-shaped variable, an outbound-network guard, and a teardown that re-verifies it left zero residue. GUI repos run on an app screen — tkinter apps render as real HTML widgets in the page, static web apps open in a no-origin sandboxed frame, and in this-PC mode a full-stack server runs as a real process with its own UI embedded at 127.0.0.1. The scan engine exists twice — Python and JavaScript — and CI proves every finding identical. 37 real-process tests on Ubuntu and Windows.

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
| [csv-clinic](https://github.com/amanvicky/csv-clinic) | Diagnose and clean messy CSVs from the terminal — inspect types/blanks/duplicates, then fix with a full change report |

### Getting into AI? Start here

| Repo | What's in it |
|---|---|
| [attention-from-scratch](https://github.com/amanvicky/attention-from-scratch) | Self-attention in ~90 lines of NumPy, every matrix explained — no torch, no API keys, 11 property tests |
| [fine-tune-prep](https://github.com/amanvicky/fine-tune-prep) | Validate, split and convert chat datasets before you pay for a fine-tune — zero dependencies, ships with a sample |
| [tokenizer-playground](https://github.com/amanvicky/tokenizer-playground) | Watch BPE chop text into tokens, live — trainer + browser encoder proven identical, token by token |
| [spamcheck](https://github.com/amanvicky/spamcheck) | A trained classifier (98.47% on real data) shipped as one JSON file — Python CLI + browser demo, parity-gated |

### Security — real-time, defensive

| Repo | What's in it |
|---|---|
| [cleanroom](https://github.com/amanvicky/cleanroom) | Paste a repo link → risk report → run it in a disposable sandbox → wipe it clean. Browser VM + CLI, live at [amanvicky.github.io/cleanroom](https://amanvicky.github.io/cleanroom/) |
| [honeypot-lite](https://github.com/amanvicky/honeypot-lite) | Real SSH/Telnet/HTTP traps that log attacker behavior to a live feed — spin one up in minutes, 7 socket-level tests |
| [file-sentinel](https://github.com/amanvicky/file-sentinel) | Watches a folder for the mass-encryption pattern (ransomware's first move) and can webhook you — 9 tests incl. a live canary run |

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
- Building small tools most weeks — the newest: [cleanroom](https://github.com/amanvicky/cleanroom) (paste a repo link, run it live in your browser, wipe it clean) and [spamcheck](https://github.com/amanvicky/spamcheck) (a trained spam classifier)
