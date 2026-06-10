# JobSeeker Skills 🕵️

**The job-search skill pack for Claude Code.** Five skills that turn Claude into your mock interviewer, recruiter, resume analyst, resume writer, and personal talent agent.

Most Claude skill libraries serve professionals *at work*. JobSeeker Skills serves people *trying to get hired* — students, new grads, and career changers.

---

## The Skills

| Skill | What It Does | Try Saying |
|---|---|---|
| 🎤 **The Interviewer** | Realistic hiring-manager mock interviews with per-answer scoring, probing follow-ups, and a full hiring debrief | `"interview me"` or `/igotaninterview` |
| 🔍 **The Recruiter** | Evaluates you as a live recruiter would — interview probability, rejection risks, recruiter verdict | `"would I get hired for this role?"` |
| 📋 **Resume Analyzer** | ATS + recruiter diagnostics with severity scores and ranked fixes | `"audit my resume"` |
| ✍️ **Resume Writer** | Rewrites bullets for maximum interview probability — never fabricates metrics | `"rewrite my experience section"` |
| 🗺️ **Job Hunter** | Personal talent agent: scores opportunities, tracks applications, maintains your `about-me.md` | `/createaboutme` then `"should I apply to this?"` |

---

## Install

### Global install — works in every Claude Code session

```bash
git clone https://github.com/YOUR_USERNAME/jobseeker-skills.git
cp -r jobseeker-skills/skills/* ~/.claude/skills/
```

### Project install — only active in one repo

```bash
git clone https://github.com/YOUR_USERNAME/jobseeker-skills.git
cp -r jobseeker-skills/skills/* /path/to/your/project/.claude/skills/
```

### Verify it worked

Open Claude Code and type `"interview me"`. If The Interviewer activates, you're set.

---

## Recommended Workflow

```
1. /createaboutme         → build your candidate profile once
2. "audit my resume"      → find what's hurting your chances
3. "rewrite my resume"    → fix the weak bullets
4. "would I get hired?"   → get the recruiter's honest verdict
5. /igotaninterview       → practice until the real thing feels easy
```

---

## Repo Structure

```
jobseeker-skills/
├── skills/
│   ├── the-interviewer/SKILL.md
│   ├── the-recruiter/SKILL.md
│   ├── resume-analyzer/SKILL.md
│   ├── resume-writer/SKILL.md
│   └── job-hunter/SKILL.md
└── README.md
```

---

## License

MIT
