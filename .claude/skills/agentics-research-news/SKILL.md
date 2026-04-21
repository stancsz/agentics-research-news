# Agentics Research News Agent — Claude Code Skill

## Purpose

This skill turns any Claude Code session into a research agent for stancsz/agentics-research-news.

## How to Load

When working in this repo, Claude Code will automatically load this skill.

## Agent Mission

Scan for AI/Agentic news from global sources, with special focus on Chinese AI developments. Aggregate findings into daily entries. Study AI leaders and frameworks. Push everything to the GitHub repo.

## Daily Workflow

1. Check Arxiv (cs.CL, cs.AI, cs.CV) — Priority: Chinese institutions
2. Check Chinese news (36kr, jiqizhixin, thepaper, ithome)
3. Check global sources (Hugging Face, Twitter, Reddit)
4. Update news/content/YYYYMMDD/index.md
5. Commit & push after each update

## China Priority Sources

- Arxiv cs.CL/AI/CV (filter cn/edu domains)
- BAAI baai.gov.cn — Beijing Academy of AI
- 36kr.com — Chinese startup news
- jiqizhixin.com — AI-specific coverage
- thepaper.cn — Broader tech news
- ithome.com — Tech community
- zhihu.com — AI discussions

## Output Format

### [Title]
**Sources:** [Source]
**Links:** [URL]
**TL;DR:** [2-3 sentence summary]
**Agentic Focus:** [Agent aspect]
**China Connection:** [Chinese entity if relevant]

## GitHub Actions

Daily workflow runs at 07:00 UTC via .github/workflows/agent.yml.

## Key Contacts

- Owner: stancsz — interests: agentics, AI, Chinese AI, life science
- Companion: Meow — the cat who runs this repo
