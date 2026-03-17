---
name: llm-seo
description: LLM SEO, AEO (Answer Engine Optimization), and GEO (Generative Engine Optimization) — getting your product recommended by ChatGPT, Claude, Perplexity, and Gemini. ALWAYS use this skill when the user mentions: LLM SEO, AEO, GEO, AI SEO, get recommended by ChatGPT, appear in ChatGPT results, show up in Perplexity, rank in AI search, get cited by Claude, AI discovery, llms.txt, generative engine optimization, answer engine optimization, AI-powered search, get mentioned by AI, optimize for LLMs, AI search visibility, ChatGPT recommend my product, Perplexity SEO, or ANY question about appearing in AI-generated answers or recommendations.
---

# LLM SEO / AEO / GEO

A practical framework to get your product recommended by ChatGPT, Claude, Perplexity, and Gemini. Based on strategies from Lenny's Newsletter, GTM Strategist, and Vercel's LLM SEO research.

## Why This Matters

AI search is different from Google. LLMs pull from:
1. Training data (static, cutoff date)
2. Real-time web search (Perplexity, ChatGPT with browsing)
3. Citations and trusted sources

You can influence #2 and #3 starting today — even as an early-stage startup.

---

## The Core Insight

LLMs recommend products that appear in **trusted, authoritative third-party content** — not your own website.

> Think of it as: Google ranks pages → LLMs cite sources → you need to BE the source, or be IN the sources.

---

## Part 1: Foundation — Get Indexed by AI Crawlers

### Create llms.txt

Add `/llms.txt` to your site root — a plain-text file that tells LLMs what your product does.

```
# [Your Product Name]

> [One-line description]

[Your product] is a [category] that helps [target user] [achieve outcome] by [mechanism].

## Key Features
- [Feature 1]: [Brief description]
- [Feature 2]: [Brief description]
- [Feature 3]: [Brief description]

## Use Cases
- [Use case 1]
- [Use case 2]
- [Use case 3]

## Pricing
[Free/Freemium/Paid — starting at $X/mo]

## Links
- Docs: [URL]
- Blog: [URL]
- Changelog: [URL]
```

### Create llms-full.txt

A longer version with your full documentation — link to it from llms.txt.

```
# Full Documentation

[Link to llms.txt]
Docs: /llms-full.txt
```

### Meta Tags for AI Crawlers

Add to your `<head>`:
```html
<meta name="description" content="[Clear, factual description — no fluff]">
<meta property="og:description" content="[Same]">
<!-- Structured data for product -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "SoftwareApplication",
  "name": "[Product Name]",
  "description": "[Description]",
  "applicationCategory": "[Category]",
  "offers": {
    "@type": "Offer",
    "price": "[Price]",
    "priceCurrency": "USD"
  }
}
</script>
```

---

## Part 2: Build Citation Sources

LLMs cite specific types of content. Build each:

### 1. Comparison & Alternative Pages

Create pages like:
- `/alternatives/[competitor]` — "Best [Competitor] Alternatives"
- `/vs/[competitor]` — "[Your Product] vs [Competitor]"
- `/[use-case]-software` — "Best [Use Case] Software"

These get cited when users ask "what's a good alternative to X" or "best tools for Y."

**Format:**
```markdown
# [Your Product] vs [Competitor]: Full Comparison (2025)

## Quick Summary
[3-sentence honest comparison]

## Feature Comparison
| Feature | Your Product | Competitor |
|---------|-------------|------------|
| ...     | ✅          | ✅         |

## When to Choose [Your Product]
- [Scenario 1]
- [Scenario 2]

## When to Choose [Competitor]
- [Scenario 1]
```

### 2. Use Case / Problem-Solution Content

Create dedicated pages for each use case:
- `/[industry]-[use-case]` (e.g., `/marketing-automation-for-agencies`)
- `/how-to-[task]` (e.g., `/how-to-automate-email-followups`)

LLMs answer "how do I X" by citing pages that answer that question directly.

### 3. Glossary / Definition Pages

Create `/glossary/[term]` pages for terms in your domain.

LLMs heavily cite definitional content. If you own the definition, you own the citation.

### 4. Statistics & Research Pages

Publish original data or curated stats:
- "State of [Industry] 2025"
- "[X] Statistics: [Topic]"

LLMs love citing numbers. If you're the source of the stat, you get cited.

---

## Part 3: Get Into Third-Party Sources LLMs Trust

This is the most impactful lever. LLMs train on and cite:

### High-Priority Sources to Target

| Source Type | Examples | How to Get In |
|-------------|----------|---------------|
| Software review sites | G2, Capterra, Trustpilot | Claim listing, get reviews |
| Curated lists | Indie Hackers, Product Hunt | Launch + collect upvotes |
| Industry newsletters | Lenny's, MKT1, Hacker News | Submit / pitch |
| Reddit threads | "Best tools for X" threads | Participate genuinely |
| GitHub awesome lists | awesome-[topic] repos | Submit PR |
| Blog roundups | "Top 10 X tools" | Pitch for inclusion |
| Podcasts / YouTube | Indie Hackers podcast, etc. | Guest appearances |
| Wikipedia (advanced) | Wikipedia category pages | Requires notability |

### Tactics to Get Mentioned

1. **Find existing "best of" lists** — Google "[your category] tools 2024" → email the author asking to be included
2. **Answer Reddit questions** — Find threads where users ask for tool recommendations → give genuinely helpful answer that mentions your product
3. **Guest posts** — Write for high-authority blogs in your niche (DA 50+)
4. **HARO / Qwoted** — Respond to journalist queries → get mentioned in articles

---

## Part 4: Optimize Your Content for Citation

### Write Like an LLM Would Summarize You

LLMs pull short, clear, factual passages. Structure your content:

```
❌ Bad: "Our revolutionary AI-powered platform transforms how teams collaborate..."
✅ Good: "[Product] is a project management tool that helps remote teams track tasks, deadlines, and blockers in one place."
```

**Rules:**
- Lead with what you do, not how great you are
- Use factual, specific language
- Include numbers and specifics where possible
- Answer the question directly in the first sentence

### Headers as Answer Targets

Structure content so headers = questions:
```
## What is [Product]?
## Who is [Product] for?
## How does [Product] compare to [Competitor]?
## How much does [Product] cost?
## How do I get started with [Product]?
```

LLMs extract answers to these questions directly.

---

## Part 5: Monitor & Measure

### Track Your LLM Presence

Manually test weekly:
```
Prompts to test in ChatGPT, Claude, Perplexity:
- "What are the best [category] tools?"
- "What's a good alternative to [competitor]?"
- "How do I [use case your product solves]?"
- "Tell me about [your product name]"
```

### Track Citations in Perplexity

Perplexity shows sources. Search for your use case and see which sites appear → those are your citation targets.

### Tools
- [Profound](https://www.profound.co/) — AI search monitoring
- [Otterly.ai](https://otterly.ai/) — track brand mentions in AI answers
- Manual testing (free, most reliable for early stage)

---

## Part 6: Quick Wins Checklist

Run through these first — highest ROI, lowest effort:

- [ ] Add `llms.txt` to your domain root
- [ ] Add `llms-full.txt` with full docs
- [ ] Add structured data (Schema.org SoftwareApplication)
- [ ] Claim and optimize G2 + Capterra listings
- [ ] Create 1 comparison page (you vs. top competitor)
- [ ] Find 3 Reddit threads asking for tool recommendations → answer genuinely
- [ ] Find 3 "best X tools" blog posts → email to request inclusion
- [ ] Add clear, factual FAQ section to homepage
- [ ] Submit to GitHub awesome lists in your category
- [ ] Publish one piece of original data/research

---

## Quick Reference

| LLM | Main Data Source | How to Influence |
|-----|-----------------|-----------------|
| ChatGPT | Training data + Bing | Get into authoritative sites, Bing-indexed content |
| Perplexity | Real-time web search | Fresh, well-structured content + backlinks |
| Claude | Training data + web | Authoritative third-party mentions |
| Gemini | Google index | Google SEO fundamentals + Google Business |

**Golden Rule:** LLMs don't recommend products — they summarize what the internet says about products. Own the narrative on third-party sites.
