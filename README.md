<div align="center">

<a href="./README.md"><img src="https://img.shields.io/badge/English-0D1117?style=for-the-badge&logo=github&logoColor=white" alt="English"></a>
<a href="./README_TR.md"><img src="https://img.shields.io/badge/Türkçe-E30A17?style=for-the-badge&logo=readme&logoColor=white" alt="Türkçe"></a>

# Alptuğ Harun

### Social Media Specialist · AI Workflow Builder · Digital Content Creator

I like turning vague AI ideas into something you can **run, test, explain and reuse**.

[![Website](https://img.shields.io/badge/alptugharun.com-111827?style=for-the-badge&logo=googlechrome&logoColor=white)](https://alptugharun.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alptugharun/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/alptug.harun/)
[![Behance](https://img.shields.io/badge/Behance-1769FF?style=for-the-badge&logo=behance&logoColor=white)](https://www.behance.net/alptugharun/)

</div>

---

## What I actually build

My open-source work follows a simple path:

**prompt → reusable assistant → Agent Skill → MCP/API → automation → verification**

I work across **ChatGPT/OpenAI, Claude/Anthropic, Gemini and Grok/xAI**, with creator workflows for Canva, Pinterest, Reels, social-media research and digital visibility.

The part I care about most is the boring but important bit: **does it run, what can fail, what permissions does it need, and can another person reproduce the result?**

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
<img src="https://img.shields.io/badge/MCP-111827?style=flat-square" alt="MCP">
<img src="https://img.shields.io/badge/Agent_Skills-6D28D9?style=flat-square" alt="Agent Skills">
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI">
<img src="https://img.shields.io/badge/Anthropic-D97706?style=flat-square" alt="Anthropic">
<img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini">
<img src="https://img.shields.io/badge/Grok-000000?style=flat-square&logo=x&logoColor=white" alt="Grok">
<img src="https://img.shields.io/badge/Canva-00C4CC?style=flat-square&logo=canva&logoColor=white" alt="Canva">
<img src="https://img.shields.io/badge/Pinterest-BD081C?style=flat-square&logo=pinterest&logoColor=white" alt="Pinterest">
</p>

## Featured open-source work

### 🚀 [AI Social Media Toolkit](https://github.com/alptugharun/ai-social-media-toolkit)

A practical AI workbench for people who want more than prompt collections.

It includes:

- reusable prompt systems and assistant blueprints;
- **17 Agent Skills** for creator operations, research and digital visibility;
- a dependency-free, read-only **MCP server**;
- API/bot starter patterns;
- CI, CodeQL, OpenSSF Scorecard and M8ven verification;
- reproducible demos, runtime-evidence rules and explicit failure paths.

[![CI](https://github.com/alptugharun/ai-social-media-toolkit/actions/workflows/validate-skills.yml/badge.svg)](https://github.com/alptugharun/ai-social-media-toolkit/actions/workflows/validate-skills.yml)
[![M8ven Score](https://m8ven.ai/badge/mcp/alptugharun-ai-social-media-toolkit-adv58l?v=03bebb9d62df5457451770e8ba62ec55)](https://m8ven.ai/mcp/alptugharun-ai-social-media-toolkit-adv58l?s=readme)
[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/alptugharun/ai-social-media-toolkit/badge)](https://scorecard.dev/viewer/?uri=github.com/alptugharun/ai-social-media-toolkit)

**Start here:** [2-minute proof](https://github.com/alptugharun/ai-social-media-toolkit/blob/main/START-HERE.md) · [10 Quick Wins](https://github.com/alptugharun/ai-social-media-toolkit/blob/main/QUICK-WINS.md) · [AI Ecosystem Hub](https://github.com/alptugharun/ai-social-media-toolkit/blob/main/AI-ECOSYSTEM-HUB.md) · [Standalone MCP](https://github.com/alptugharun/ai-social-media-toolkit/blob/main/packages/ai-workbench-mcp/README.md)

## Standalone projects

Three parts of the toolkit are now focused public repositories of their own.

### 🔌 [AI Workbench MCP](https://github.com/alptugharun/ai-workbench-mcp)

[![CI](https://github.com/alptugharun/ai-workbench-mcp/actions/workflows/ci.yml/badge.svg)](https://github.com/alptugharun/ai-workbench-mcp/actions/workflows/ci.yml)

A dependency-free, read-only MCP server for reusable prompts and assistant blueprints. The public surface is deliberately small: `list_prompts`, `render_prompt` and `get_assistant`.

### 🛡️ [Agent Skill Safety Auditor](https://github.com/alptugharun/agent-skill-safety-auditor)

[![CI](https://github.com/alptugharun/agent-skill-safety-auditor/actions/workflows/ci.yml/badge.svg)](https://github.com/alptugharun/agent-skill-safety-auditor/actions/workflows/ci.yml)

An offline pre-install review tool for Agent Skills. It looks for permission and execution signals such as remote shell pipes, process access, environment reads and install hooks — then leaves the final judgment to a human.

### 📈 [Creator Signal Lab](https://github.com/alptugharun/creator-signal-lab)

[![CI](https://github.com/alptugharun/creator-signal-lab/actions/workflows/ci.yml/badge.svg)](https://github.com/alptugharun/creator-signal-lab/actions/workflows/ci.yml)

Two transparent creator-research scorers: one for content-opportunity prioritization and one for social-post outliers against your own baseline. No scraping, no hidden AI score, no virality promise.

Still inside the main toolkit: **Creator Research Radars** and **Human-first Content QA**. I will split those only if the independent use case becomes stronger than keeping them integrated.

I would still rather maintain **a few useful repositories** than publish twenty empty ones.

## Try something in two minutes

Clone the main toolkit and run:

```bash
python tools/first_run_check.py
```

No API key, social login or paid model call is required for that check.

A passing run verifies the local catalog, dry-run provider path, Agent Skill installer flow and creator demo from the checked-out repository.

## How I label proof

I keep these states separate:

**Blueprint** → **Offline tested** → **Runtime verified** → **Production evidence**

That distinction matters. A README saying something works is not the same as a real host running it.

If you want to help test the standalone MCP package, the current evidence task is here:

→ [Independent MCP runtime verification](https://github.com/alptugharun/ai-social-media-toolkit/issues/110)

## Creator & brand work

GitHub is the technical/open-source side of my work.

Outside GitHub I work on AI-supported social media, digital visibility and creator systems through **ADYA Creative** and **Yeşil Dijital Akademi**.

---

<div align="center">

### GitHub at a glance

<img src="https://github-readme-stats.vercel.app/api?username=alptugharun&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github" height="165" alt="Alptuğ Harun GitHub stats">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=alptugharun&layout=compact&theme=github_dark&hide_border=true" height="165" alt="Top languages">

**Build less noise. Ship more proof.**

</div>
