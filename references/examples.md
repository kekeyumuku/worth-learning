# Examples

These examples show the kinds of requests this skill should handle and what good behavior looks like.

---

## Example 1 — Tutorial or workflow

### User
Analyze this tutorial for me. Is it actually worth learning, or is it just a clever demo?

> "I built a RAG pipeline in 30 minutes using LangChain. Here's the exact code. You paste in any PDF, it chunks it, embeds it, and lets you query it with GPT-4. Works perfectly every time."

### Output

**Bottom line:** Useful starting point, but the claim "works perfectly every time" signals this is a demo, not a production method.

**What it says:** A quick LangChain RAG setup — PDF ingestion, chunking, embedding, and querying. The author walks through the code step by step.

**What is actually valuable:** The chunking and embedding pipeline is a solid reference pattern. Worth understanding even if you swap out LangChain later.

**What to be careful about:** "Works perfectly" is a red flag. Real RAG failures happen at retrieval quality, not setup. Chunking strategy, embedding choice, and query formulation all affect output — none of that is covered here.

**Is it worth further attention?** Worth understanding, not urgent.

**Suggested next step:** Use it as a baseline reference. Before applying it, test retrieval quality on a non-trivial document where the answer isn't obvious.

---

### Good behavior
- identify the real workflow being taught
- extract the most reusable idea
- point out what is missing or likely to fail in real use
- judge whether it is worth applying now or only understanding conceptually

---

## Example 2 — Opinionated argument

### User
What is this article really arguing? Is it credible, or just persuasive writing?

### Good behavior
- identify the central argument
- examine incentives, bias, or framing
- separate evidence from rhetoric
- point out weak support or missing context
- judge whether the claims deserve trust

---

## Example 3 — Marketing-heavy content

### User
Break this down for me. Is there real signal here, or is this mostly marketing?

### Good behavior
- separate signal from sales framing
- identify hype, emotional pressure, or manufactured urgency
- extract any real insight under the pitch
- judge whether the content deserves more attention

---

## Example 4 — Low-information short post

### User
This post is getting a lot of attention. Is there actually anything here worth learning?

### Good behavior
- assess whether the information density is genuinely low
- avoid pretending the post is deeper than it is
- explain briefly what the post contributes, if anything
- say clearly whether it is worth more time

---

## Example 5 — Incomplete input

### User
I only have this screenshot. Can you still tell me whether this is worth paying attention to?

### Good behavior
- state clearly that the input is incomplete
- avoid false confidence
- give only a provisional judgment
- explain what missing context could change the conclusion

---

## Example 6 — Follow-up / deepening

### User
Go deeper. If I wanted to apply the best part of this, what should I actually do?

### Good behavior
- do not repeat the summary
- identify the 3 most important ideas
- say what is usable right now
- suggest the smallest practical test
- note what should be verified before investing more effort
