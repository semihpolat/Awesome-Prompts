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

## 🎨 Visual Synthesis & Nano Banana
*Advanced Image Generation Techniques (Jan 2026)*

These prompts leverage the **Nano Banana Pro** (Gemini 3.0 Image AI) model for high-aesthetic, photorealistic visual synthesis.

### 🖼️ The 2026 Vision Board Framework
A comprehensive prompt for creating high-aesthetic vision boards that maintain character consistency and integrate typography seamlessly.

**Prompt:**
```markdown
Create a high-aesthetic 2026 vision board collage combining beautiful lifestyle photos with visible inspirational text and affirmations. Use the uploaded face image as the main character in several frames, preserving facial identity accurately. 

The vision board represents an ideal 2026 life: success, peace, love, confidence, freedom, abundance, and self-alignment. Editorial yet dreamy visuals, soft luxury lifestyle, intentional living. 

IMPORTANT: Text is a key element. Short phrases, affirmations, and words must be visibly integrated into the collage. Typography should feel aesthetic, handwritten, serif, or clean minimal fonts. 

Scenes & visuals to include:
- Portrait of the woman in soft natural light, calm confident expression.
- Cozy morning scene: sunlight through curtains, coffee, notebook.
- Career / purpose scene: working in a beautiful cafe, laptop open.
- Travel or freedom scene: window, balcony, city view.
- Luxury details: coffee cups, jewelry, flowers, neutral tones.

Visual style: Soft editorial lighting, neutral and warm color palette (beige, cream, taupe), film look, subtle grain.
Aspect ratio: vertical 16:9
```

![Nano Banana Vision Board 2026](https://private-us-east-1.manuscdn.com/sessionFile/7kdJwDbuC51Rejff6HEhGb/sandbox/aonFj6nQDOuPrrNNpCfJ4i-images_1768672015919_na1fn_L2hvbWUvdWJ1bnR1L0F3ZXNvbWUtUHJvbXB0cy9hc3NldHMvaW1hZ2VzL25hbm9fYmFuYW5hX3Zpc2lvbl9ib2FyZF8yMDI2.webp?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvN2tkSndEYnVDNTFSZWpmZjZIRWhHYi9zYW5kYm94L2FvbkZqNm5RRE91UHJyTk5wQ2ZKNGktaW1hZ2VzXzE3Njg2NzIwMTU5MTlfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwwRjNaWE52YldVdFVISnZiWEIwY3k5aGMzTmxkSE12YVcxaFoyVnpMMjVoYm05ZlltRnVZVzVoWDNacGMybHZibDlpYjJGeVpGOHlNREkyLndlYnAiLCJDb25kaXRpb24iOnsiRGF0ZUxlc3NUaGFuIjp7IkFXUzpFcG9jaFRpbWUiOjE3OTg3NjE2MDB9fX1dfQ__&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=mAphTAlvuSIAeXgLaO6QZ-4v-ZvQO8BMH7IqBesgltI2znUhMhv8Q9HTRaxh~r-5YVFW~IRNGLwsqC~0yROhDms1KHSbAj9DWUAsjAHPQGL7uhPd2WMiHw9HsebRorhTJPXumH4GI-I7ld1VqUrsYKVtG5LeiObKspPTwnvY4zXNdbcP0J9gFL2funFk83to1pzIWzoQKiZ6ePlq5LZbiKvJFW29x-f6RoLmL~NNsYVw-BXA2OYTGt2f9npm5uzFYJRVrWpkuhSoYOe1phiwTj3wEymRntayLRi9XHqnUY0z6NrvfPfjs31V5nucoBXfKFZntoUHDSpy9551wPck2g__)

---

### 📸 Realistic Lifestyle Portrait (JSON Structured)
Nano Banana Pro responds exceptionally well to JSON-structured visual descriptions, allowing for granular control over lighting, composition, and technical specs.

**Prompt:**
```json
{
  "metadata": { "image_type": "photograph", "primary_purpose": "lifestyle/portrait" },
  "composition": {
    "rule_applied": "rule of thirds",
    "focal_points": [ "Subject's face and eyes", "Environmental depth" ]
  },
  "lighting": {
    "type": "mixed artificial",
    "mood": "casual/inviting/warm",
    "quality": "soft light (flattering on face)"
  },
  "technical_specs": {
    "medium": "digital photography",
    "style": "realistic/lifestyle",
    "depth_of_field": "medium - subject sharp, background slightly out of focus"
  },
  "generation_parameters": {
    "prompts": [
      "POV photo of a beautiful young woman sitting at a sushi bar counter, looking back over shoulder at camera with a soft smile, photorealistic, high quality, soft focus background"
    ]
  }
}
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
