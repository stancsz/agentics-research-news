# Agentics & AI Mastery Mission 🏹

> *"Know the leaders, know the frameworks, build the future."*

## Mission Overview

**Goal:** Learn everything about agentics, AI, top leaders, top frameworks — using browser MCP, GitHub repos, code study, reflections, and systematic tracking.

**Duration:** 12 weeks (flexible)
**Status:** 🚧 In Progress

---

## The Roadmap

### Phase 1: Foundations (Weeks 1–3)
- [ ] Set up browser MCP for web research
- [ ] Identify and study top 10 AI/agentics leaders
- [ ] Research top 5 agentics frameworks
- [ ] Read/watching key publications from leaders

### Phase 2: Deep Dive (Weeks 4–7)
- [ ] Clone and study 10+ relevant GitHub repos
- [ ] Run and experiment with frameworks locally
- [ ] Write reflection posts on each major discovery
- [ ] Build small projects to test understanding
- [ ] **Architectural deep-dives** — understand how major systems work
- [ ] **Paper implementation** — read latest papers, implement key ideas

### Phase 3: Build & Ship (Weeks 8–12)
- [ ] Identify gaps in current agentics landscape
- [ ] Build original project using learned frameworks
- [ ] Document findings in public-facing format
- [ ] Teach others (write tutorial/blog post)

---

## Study Subjects

### AI Leaders

| Person | Role | Key Resource |
|--------|------|-------------|
| Andrej Karpathy | Tesla AI / OpenAI / YouTube | karpathy.ai, llm.c repo |
| Ethan Mollick | Wharton professor, agentics expert | One Useful Thing blog |
| Lex Fridman | MIT researcher, podcast host | lexfridman.com |
| Garry Tan | Y Combinator CEO | ycombinator.com |
| Sebastian Raschka | AI researcher / educator | lightning.ai |
| Jeremy Howard | fast.ai founder | fast.ai |
| Jim Fan | NVIDIA AI Scientist | Twitter @DrJimFan |
| Yann LeCun | Meta AI Chief Scientist | Twitter @ylecun |

### Repos to Study

```
karpathy/llm.c          # LLM from scratch in pure C
karpathy/minGPT         # Minimal GPT implementation
karpathy/nanoGPT        # nanoGPT (production-focused)
nostrasponds/hermes-3   # Nous Research Hermes 3 Agent
agentics/Hedgehog       # Agentic research framework
openai/swarm            # OpenAI multi-agent framework
anthropic/anthropic-cookbook  # Anthropic agent patterns
```

---

## How to Use This Repo

### Daily Run
```bash
# Fetch latest Arxiv papers
python scripts/fetch_arxiv.py

# Add findings to today's news
# Edit: news/content/YYYYMMDD/index.md

# Push updates
git add . && git commit -m "Update: $(date +%Y-%m-%d)" && git push
```

### Weekly Review
1. Read through all entries in `news/content/` since last review
2. Move interesting papers to `studies/[person]/`
3. Update MISSION.md with new discoveries

---

*Last updated: 2026-04-21*