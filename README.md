# Resume Optimizer — OpenClaw Skill

An OpenClaw skill that rewrites and optimizes resumes for overseas job markets (US, UK, Singapore, Australia).

## What It Does

- Rewrites weak bullet points using the STAR framework with quantified achievements
- Checks ATS (Applicant Tracking System) compatibility
- Tailors resume to a specific job description
- Adapts tone and format for different markets (US/UK/SG/AU)
- Handles fresh graduates, experienced professionals, and career changers

## Files

| File | Purpose |
|---|---|
| `SKILL.md` | Main skill instructions loaded by OpenClaw |
| `examples.md` | Before/after rewrite examples for 4 common scenarios |
| `templates.md` | 6 industry-specific resume templates + quantification cheat sheet |

## Install via ClawHub

```bash
clawhub install resume-optimizer
```

## Manual Install

Copy this folder into your OpenClaw skills directory:

```bash
# macOS/Linux
cp -r resume-optimizer ~/.openclaw/skills/

# Windows (PowerShell)
Copy-Item -Recurse resume-optimizer "$env:USERPROFILE\.openclaw\skills\"
```

Restart your OpenClaw session to activate.

## Usage

Simply send your resume content to OpenClaw and ask:

- "帮我优化一下这份简历"
- "Help me rewrite my resume for a software engineer role in Singapore"
- "Make my resume ATS-friendly for this job description: [paste JD]"
- "I'm a fresh graduate, help me write my first resume"

## Publish to ClawHub

```bash
npm i -g clawhub
clawhub login
clawhub publish . --slug resume-optimizer --name "Resume Optimizer" --version 1.0.0 --tags latest
```

## Supported Markets

- 🇺🇸 United States
- 🇬🇧 United Kingdom
- 🇸🇬 Singapore
- 🇦🇺 Australia

## Supported Industries

- Software Engineering / Tech
- Marketing / Growth
- Product Management
- Finance / Banking
- Operations / Business Analysis
- Design (UI/UX)
