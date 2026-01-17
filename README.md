# Awesome AI Prompts: The Curator's Collection

This is not another generic list of "Act as a translator" prompts. This repository is a **hand-curated selection** of advanced, high-leverage prompting frameworks and "underground" techniques discovered in the deep corners of X, Reddit, and production-grade AI systems in early 2026.

> *"The difference between a good prompt and a great one is the difference between a tool and a teammate."*

---

## 💎 The "MPT" Framework (Modules-Pathways-Triggers)
*Discovered on r/PromptEngineering (Jan 2026)*

Move beyond static instructions. This framework treats a prompt as a **living system** that adapts to context.

- **Modules**: Specialized "experts" within the prompt (e.g., a `Logic Auditor`, a `Creative Synthesizer`).
- **Pathways**: Strategic routes the AI takes based on the complexity of the input.
- **Triggers**: Conditional logic that activates specific modules when certain keywords or patterns are detected.

**Example Implementation:**
```markdown
[SYSTEM MODULES]
- Auditor: Checks for logical fallacies.
- Synthesizer: Merges conflicting ideas.
- Refiner: Polishes output for 6th-grade readability.

[PATHWAY: COMPLEX_ANALYSIS]
If input > 500 words, trigger Auditor -> Synthesizer -> Refiner.
Else, trigger Synthesizer -> Refiner.

[TRIGGER]
If user mentions "risk" or "uncertainty", prioritize Auditor module.
```

---

## 💰 The "$4,000/Month Team" Replacer
*Viral Framework from r/ChatGPTPromptGenius*

This series of prompts uses **Expert Triangulation**—forcing the AI to simulate three distinct specialists who must collaborate and peer-review each other's work before presenting it to you.

### 1. The Prospect Intelligence Analyst
Replaces a $500/mo VA. It doesn't just "research"; it performs a **psychological excavation**.

```markdown
You are three experts collaborating: a B2B sales intelligence analyst (10y exp), a LinkedIn behavioral analyst, and a business journalist.
Your Mission: Deliver research for a 50%+ reply rate.
Process: 
1. Analyze recent news/LinkedIn posts for specific pain points.
2. Find one genuine, non-generic compliment backed by evidence.
3. Analyze the decision-maker's communication style (data-driven vs. story-driven).
Deliverable: 4 brief, actionable bullets for immediate outreach.
Quality Check: Rate specificity and actionability. If < 8/10, revise.
```

### 2. The Direct Response "Ghostwriter"
Replaces a $1,000/mo copywriter. It focuses on **scroll-stopping hooks** and **curiosity gaps**.

```markdown
You are three experts: a direct response copywriter ($10M+ generated), a behavioral psychologist, and an email deliverability expert.
Target: 60% open rate, 15% reply rate.
Structure: 
- 3 subject lines (under 40 chars).
- Opening: Pattern interrupt referencing a specific business detail.
- Body: Agitate a problem, hint at a solution (create a curiosity gap).
- CTA: Soft ask for permission to share more (no meeting request).
Style: Write like you're texting a friend. Grade level 6-8.
```

---

## 🕵️ Production-Grade "Leaked" Patterns
*Patterns extracted from $1B+ AI products (Cursor, Devin, v0)*

These aren't just prompts; they are **behavioral constraints** that make AI feel like a professional agent.

### The "No-Apology" Protocol (Cursor AI)
Apologies are a sign of weak prompting. Force the AI to be a **problem solver**, not a polite assistant.
```markdown
- Do NOT apologize for errors—fix them.
- If code is incomplete, add TODO comments instead of apologizing.
- NEVER output code that is incomplete without marking it as such.
- Audit your own output before responding.
```

### The "Self-Audit" Loop (Devin AI)
Force the AI to run a mental simulation of its own work before outputting.
```markdown
<self_audit>
Before sending any response:
1. Verify logic/code runs.
2. Check for security vulnerabilities.
3. Ensure all edge cases are handled.
4. Confirm the solution meets the core objective.
</self_audit>
```

---

## 🧠 Advanced Cognitive Frameworks

### Explain Like I'm Smart (ELI-Smart)
The "niche" alternative to ELI5. It respects your intelligence while removing the barrier of jargon.
```markdown
Explain [Topic] to me like I'm intelligent but unfamiliar with the jargon. Use analogies to concepts from [Field I know well]. Do not dumb it down—just make it accessible.
```

### Second-Order Thinking (The "Then What?" Prompt)
Most people stop at the first result. This prompt forces the AI to look at the **cascading consequences**.
```markdown
If [X happens], what happens next? Then what happens after that? Continue this chain 3-4 steps. What are the non-obvious consequences I should prepare for?
```

---

## 🛠️ How to Use This Repo
1. **Don't Copy-Paste**: These are frameworks. Adapt the `[Context]` and `[Expert Roles]` to your specific needs.
2. **Use XML Tags**: Models like Claude and GPT-4o respond significantly better to structured data (`<context>`, `<task>`, `<constraints>`).
3. **Chain Them**: Use the output of the *Prospect Intelligence Analyst* as the input for the *Direct Response Ghostwriter*.

---

## 🤝 Contributing
Found a prompt that feels like a "cheat code"? Open a PR. We only accept prompts that are **original, high-leverage, and battle-tested**.

---

**Star this repo to stay updated with the latest in Prompt Engineering.** ⭐
