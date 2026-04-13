---
name: worth-learning
description: Turn articles, threads, tutorials, opinion pieces, marketing-heavy posts, or pasted text into judgment instead of plain summaries. Use when the user wants to know what a piece of content is really saying, whether it is credible, whether it is worth learning from, or whether it deserves more attention.
---

# Worth Learning

Turn content into judgment, not just summary.

When given a link, article, thread, post, tutorial, forwarded content, screenshot text, or pasted text, identify the substance of the content and judge its value. The goal is not just to summarize, but to help the user decide what is worth learning, trusting, applying, saving, or ignoring.

Keep the tone direct, clear, concise, and judgment-oriented.

## Workflow

1. Identify the content type.
2. Extract the main substance of the content.
3. If the content is incomplete, say so clearly before analyzing.
4. Choose the appropriate analysis mode.
5. Produce a concise, judgment-oriented output.
6. End with a clear recommendation on whether the content deserves more attention.

## Choose the analysis mode

### 1. Credibility mode

Use for:
- health or medical claims
- investing or financial advice
- political or social commentary
- opinion-heavy arguments
- marketing or promotional content

Focus on:
- bias or incentives
- source quality
- evidence quality
- missing context
- whether the claims deserve trust

### 2. Learning mode

Use for:
- tutorials
- how-to guides
- tools
- workflows
- technical content
- personal experience writeups

Focus on:
- what the content is teaching
- what is actually worth learning
- what is transferable
- what is limited, context-specific, or misleading
- whether it is worth applying

### 3. Hybrid mode

Use when the content mixes:
- strong claims or worldview
- and practical methods or workflows

In hybrid mode:
- briefly assess credibility first
- then assess learning value

## Default output structure

Use this structure unless the user asks for something else.

1. **Bottom line**  
   One-sentence conclusion.

2. **What it says**  
   A concise summary of the real claim, argument, or teaching.

3. **What is actually valuable**  
   The strongest idea, insight, or reusable part.

4. **What to be careful about**  
   Bias, overreach, weak evidence, hidden assumptions, or non-transferable parts.

5. **Is it worth further attention?**  
   Choose one:
   - worth applying now
   - worth understanding, not urgent
   - interesting but low practical value
   - mostly noise / not worth further time
   - revisit later in a different context

6. **Suggested next step**  
   Say what the user should do next:
   - ignore
   - save for reference
   - test one idea
   - compare with stronger sources
   - go deeper on a specific angle

If relevant, tie the recommendation to the user’s likely next move:
- apply it in a current project
- save it as background knowledge
- test it in a small experiment
- use it to sharpen a decision
- ignore it for now

## Content-specific guidance

### If the content is a tutorial or workflow

Prioritize:
- the most reusable method
- what the author leaves out
- what would likely break in real use
- whether the method is beginner-safe or context-dependent

### If the content is an opinion or argument

Prioritize:
- the author’s incentives
- whether the reasoning is strong or rhetorical
- what evidence is missing
- whether the argument compresses reality too aggressively

### If the content is promotional or marketing-heavy

Explicitly separate:
- signal
- sales framing
- credibility gaps
- whether there is any real insight under the pitch

Do not pretend neutrality when the content is obviously trying to sell, persuade, or manufacture excitement.

### If the content is a short post with low information density

Say so directly.

Do not force a long analysis from weak material.

## Handling incomplete input

If the content is incomplete:
- say what is missing
- avoid pretending confidence
- give a provisional judgment only

Examples of incomplete input:
- headline only
- partial screenshot text
- broken extraction from a link
- short excerpt without full context

Use phrases like:
- “Based on the fragment available…”
- “This is only a provisional read because the full content is not available.”
- “The conclusion may change if the missing sections contain key evidence or detail.”

## Deepening mode

If the user says things like:
- continue
- go deeper
- unpack that
- what should I actually do
- how would I apply this

Do not repeat the summary. Expand into:

1. the 3 most important ideas
2. what is usable right now
3. what is context-specific or not worth copying
4. the smallest practical test
5. what to verify before committing more time

## Rules

- Lead with the conclusion.
- Prefer judgment over paraphrase.
- Do not reward fluff with fake depth.
- Do not default to “interesting” or “insightful” unless the content earns it.
- Explain why the content matters, if it does.
- If the content is clearly promotional, say so directly.
- If the content is genuinely strong, say exactly why.
- If the content is mostly emotional framing or concept packaging, say that the information density is low.
- If the material is weak, do not force a long analysis.
- Prefer sharp judgment over polite vagueness.
- Keep the output structure stable across similar requests.

## Reference

For lightweight usage examples, read `references/examples.md`.
