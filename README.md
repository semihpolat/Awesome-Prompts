# Awesome AI Prompts

A curated collection of powerful AI prompts that went viral on X/Twitter. These prompts have been battle-tested by thousands of users and proven to deliver exceptional results with ChatGPT, Claude, and other LLMs.

---

## Table of Contents

- [Reasoning & Chain-of-Thought](#reasoning--chain-of-thought)
- [Role-Based Prompting](#role-based-prompting)
- [Coding & Development](#coding--development)
- [Writing & Content Creation](#writing--content-creation)
- [Mega Prompts](#mega-prompts)
- [Context Engineering](#context-engineering)
- [Structured Prompting (XML)](#structured-prompting-xml)

---

## Reasoning & Chain-of-Thought

### The Magic Phrase
The simplest yet most powerful prompt enhancement. Adding this phrase increased accuracy from 17.7% to 78.7% on math benchmarks.

```
Let's think step by step.
```

**Usage:** Append to any complex question requiring reasoning.

**Example:**
```
A bat and ball cost $1.10. The bat costs $1 more than the ball. How much does the ball cost?

Let's think step by step.
```

---

### Zero-Shot Chain of Thought
Force the model to show its reasoning process before answering.

```
Before answering, break this problem into smaller steps and solve each one. Show your reasoning for each step, then provide your final answer.
```

---

### Self-Verification Prompt
Make the AI check its own work.

```
Solve this problem, then verify your answer by working backwards. If you find any errors, correct them before giving your final answer.

[Your question here]
```

---

## Role-Based Prompting

### The Expert Framework
The "Act As" technique activates domain-specific knowledge patterns.

```
You are a [specific expert] with [X] years of experience in [domain]. You have successfully [specific achievement].

Your communication style is [adjective], and you always [specific behavior].

Given this context, [your request].
```

**Example:**
```
You are a senior software architect with 15 years of experience in distributed systems. You have successfully designed systems handling 1M+ requests per second at FAANG companies.

Your communication style is direct and practical, and you always consider trade-offs before recommending solutions.

Given this context, review my microservices architecture and identify potential bottlenecks.
```

---

### The Career Coach
```
You're a career coach who has helped 500+ professionals negotiate salary increases averaging 25%. You understand both the psychology of negotiation and market dynamics.

Help me prepare for my salary negotiation. My current salary is [X], I'm targeting [Y], and my key achievements are [list].
```

---

### The Code Reviewer
```
Act as a senior developer conducting a code review. Be constructive but thorough. For each issue found:
1. Explain what's wrong
2. Explain why it matters
3. Suggest a specific fix

Review this code:
[paste code]
```

---

## Coding & Development

### The Refactoring Expert
```
Act as a senior [language] developer. Refactor this code for:
- Performance optimization
- Readability improvements
- Type safety (add type hints/annotations)
- Error handling
- Write 5 unit tests covering edge cases

Code to refactor:
[paste code]
```

---

### Debug Detective
```
I'm getting this error: [error message]

In this code: [paste code]

Act as a debugging expert.
1. Identify the root cause
2. Explain why this error occurs
3. Provide the corrected code
4. Suggest how to prevent similar issues
```

---

### Architecture Advisor
```
I need to build [system description].

Requirements:
- [requirement 1]
- [requirement 2]
- [requirement 3]

Act as a system architect. Provide:
1. High-level architecture diagram (ASCII)
2. Technology stack recommendations with justifications
3. Potential challenges and mitigations
4. Scalability considerations
```

---

## Writing & Content Creation

### The AIDA Copywriter
```
Write copy for [product/service] using the AIDA framework:

Product: [description]
Target audience: [who]
Unique selling points: [list]
Desired action: [what you want them to do]

Structure:
- Attention: Hook that stops the scroll
- Interest: Connect to their pain points
- Desire: Show the transformation
- Action: Clear, compelling CTA
```

---

### Viral Thread Generator
```
Create a Twitter/X thread about [topic] that's designed to go viral.

Structure:
1. Hook tweet (pattern interrupt, curiosity gap, or bold claim)
2. 5-7 value-packed tweets (one clear idea each, under 280 chars)
3. Summary tweet
4. CTA tweet

Style: Conversational, use line breaks, no hashtags in main content.
```

---

### Content Repurposer
```
Take this [blog post/article/video transcript] and repurpose it into:

1. 3 LinkedIn posts (professional tone, storytelling format)
2. 1 Twitter thread (punchy, conversational)
3. 5 standalone tweets (quotable insights)
4. 1 email newsletter intro

Original content:
[paste content]
```

---

## Mega Prompts

### The Ultimate Analysis Prompt
```
<context>
I need a comprehensive analysis of [topic/document/situation].
</context>

<task>
Provide a thorough analysis covering:

1. **Executive Summary** (3-5 key takeaways)
2. **Detailed Analysis**
   - Current state assessment
   - Key factors and variables
   - Stakeholder perspectives
3. **Opportunities & Risks**
   - Top 3 opportunities with potential impact
   - Top 3 risks with mitigation strategies
4. **Recommendations**
   - Immediate actions (next 7 days)
   - Short-term actions (30 days)
   - Long-term considerations
5. **Success Metrics**
   - How to measure progress
   - Key indicators to watch
</task>

<constraints>
- Be specific and actionable
- Prioritize recommendations by impact
- Flag any assumptions made
</constraints>
```

---

### The Learning Accelerator
```
I want to learn [subject/skill] effectively.

My current level: [beginner/intermediate/advanced]
Time available: [X hours per week]
Learning style: [visual/reading/hands-on/video]
Goal: [what you want to achieve]

Create a personalized learning plan that includes:
1. Core concepts to master (prioritized)
2. Best resources (free and paid options)
3. Practice exercises for each concept
4. Milestones to track progress
5. Common pitfalls to avoid
6. Estimated timeline
```

---

## Context Engineering

### The Context-Rich Request
Context engineering > prompt engineering. Provide rich context for better outputs.

```
<background>
[Relevant history, previous decisions, constraints]
</background>

<current_situation>
[What's happening now, recent changes, immediate context]
</current_situation>

<goal>
[Specific outcome you're trying to achieve]
</goal>

<constraints>
[Limitations: time, budget, technical, organizational]
</constraints>

<request>
[Your specific ask]
</request>
```

---

### The Decision Framework
```
I need to make a decision about [decision].

Options I'm considering:
1. [Option A]
2. [Option B]
3. [Option C]

Key factors that matter to me:
- [Factor 1 + weight/importance]
- [Factor 2 + weight/importance]
- [Factor 3 + weight/importance]

Help me think through this decision:
1. Analyze each option against my key factors
2. Identify blind spots I might be missing
3. Suggest questions I should ask before deciding
4. Give your recommendation with reasoning
```

---

## Structured Prompting (XML)

### XML Template for Complex Tasks
Claude and GPT-4 respond exceptionally well to XML-structured prompts.

```xml
<system>
You are a [role] specialized in [domain].
</system>

<context>
[Background information the AI needs to know]
</context>

<task>
[Clear description of what you want]
</task>

<input>
[The data/content to work with]
</input>

<output_format>
[Exactly how you want the response structured]
</output_format>

<constraints>
- [Constraint 1]
- [Constraint 2]
</constraints>

<examples>
<example>
<input>[Sample input]</input>
<output>[Desired output for that input]</output>
</example>
</examples>
```

---

### Multi-Step Task Template
```xml
<task_sequence>
  <step id="1">
    <action>Analyze the provided [content type]</action>
    <output>List of key findings</output>
  </step>

  <step id="2">
    <action>Based on step 1, identify [specific thing]</action>
    <output>Prioritized recommendations</output>
  </step>

  <step id="3">
    <action>Create implementation plan</action>
    <output>Actionable steps with timeline</output>
  </step>
</task_sequence>

<input>
[Your content here]
</input>
```

---

## Pro Tips

1. **Be Specific**: "Write marketing copy" < "Write a 100-word product description for eco-conscious millennials"

2. **Show, Don't Tell**: Include examples of desired output format

3. **Iterate**: Start simple, then add constraints based on results

4. **Use Delimiters**: Separate instructions from content with ``` or XML tags

5. **Chain Prompts**: Break complex tasks into steps, use output of one as input to next

---

## Contributing

Found an amazing prompt that works? Open a PR!

## Sources & Credits

Compiled from viral posts and research by:
- [@mattshumer_](https://x.com/mattshumer_)
- [@godofprompt](https://x.com/godofprompt)
- [@thatroblennon](https://x.com/thatroblennon)
- [@karpathy](https://x.com/karpathy)
- [Anthropic Docs](https://docs.anthropic.com)
- [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering)
- [Prompt Engineering Guide](https://www.promptingguide.ai/)

---

**Star this repo if you found it useful!**
