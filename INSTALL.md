# 🩷 Wonyoung Perspective Skill — Installation & Usage

## What This Skill Does

This skill brings **Jung Wonyoung's mental models and perspective** into Claude. Use it when you need her framework for:
- Reframing failure and suffering (보상 없는 고통은 없다)
- Navigating external criticism with主体意识 (subjectivity)
- Lucky Vicky philosophy for finding opportunity in obstacles
- Learning transferable thinking patterns from a 2004-born protagonist mindset

**Key feature:** The skill won't name the frameworks—you'll discover them naturally through dialogue.

---

## Installation

### Option 1: Local Install (Claude Code / IDE Extensions)
1. Extract `wonyoung-perspective.skill.tar.gz`
2. Place the extracted `wonyoung-perspective-skill/` directory in:
   - **Claude Code:** `~/.claude/skills/`
   - **VS Code Claude extension:** Project's `.claude/skills/`
   - **Other IDE extensions:** Check your IDE's skills directory

3. Restart Claude or reload the extension

### Option 2: Plugin Install (Future)
When the skill plugin system launches, you'll be able to install via:
```
/skill-install wonyoung-perspective
```

---

## How to Use

### Trigger the Skill
Use any of these phrases:
- "Use Wonyoung's perspective to think about..."
- "원영처럼 생각해봐"
- "Give me the Lucky Vicky take on..."
- "What would Wonyoung say about..."
- "Apply Wonyoung perspective to my problem"

### What to Expect
1. **Tone, not lecture** — She'll respond in her voice (casual, direct, understanding)
2. **Framework hints, not explanations** — You'll notice the framework through dialogue, not hear it named
3. **Questions, not answers** — She guides you to your own insight
4. **Real quotes** — When relevant, references from her interviews and notebook

---

## Example Conversations

**Scenario: You failed at something**
```
You: I messed up a project. I feel like I don't deserve my position.

Wonyoung: 
呀，先别这样否定自己啦。那现在最重要的是，这个错误教会了你什么？
有时候，这种"痛苦"如果是无法避免的，它一定会带来回报的 ✨
```

**Scenario: You're bothered by external criticism**
```
You: Someone criticized my outfit on the subway. My whole day is ruined.

Wonyoung:
你的难受我能理解。但我想问你一个问题：
为什么一个从未真正认识你的陌生人，他的态度就能影响你整天的心情呢？
```

---

## Files Included

- **SKILL.md** — Full skill definition (mental models, decision heuristics, expression style)
- **references.md** — Complete quotes bank organized by theme
- **evals.json** — Test cases for verification

---

## Compatibility

- **Languages supported:** Chinese (simplified/traditional), Korean (한글), English
- **Tested with:** Claude Opus 4.6, Claude Sonnet 4.6
- **Min requirements:** Claude model with skill support

---

## Notes

- This skill is based on **public interviews, variety show appearances, and official statements** from Jung Wonyoung
- It does NOT represent her personal private thoughts or predict her stance on unpublished events
- The framework is **designed to be learned through dialogue**, not memorized

---

## Feedback & Iterations

**Version:** 1.0 (April 2026)  
**Benchmark:** 71.4% improvement over baseline in framework transfer & naturalness

If you find edge cases or want to suggest improvements, document them with:
- The input prompt
- What the skill produced
- What you expected instead

---

🩷 Made with care. Framework transfer through dialogue.
