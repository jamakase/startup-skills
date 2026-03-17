---
name: saas-cold-outreach
description: Cold email infrastructure and templates for B2B SaaS outbound sales. ALWAYS use this skill when the user mentions: cold email, cold outreach, outbound sales, sales outreach, email prospects, DM potential customers, LinkedIn outreach, email sequences, follow-up emails, outbound engine, sales emails, prospecting emails, reaching out to customers, contacting leads, email deliverability, spam folder, email warmup, sending cold emails, email infrastructure for sales, B2B outreach, or ANY question about sending unsolicited emails to potential customers. Use even if they just say "email potential customers" or "reach out to prospects" without saying "cold."
---

# SaaS Cold Outreach

A complete cold email system for B2B SaaS, covering infrastructure, deliverability, templates, and scaling. Based on frameworks from Za-zu Cold Email Handbook, Cold Start Blueprint, and MRR Unlocked.

## Critical Rule #1

> **NEVER send cold emails from your main domain.**

Cold emails can attract spam complaints. Protect your primary domain's sender reputation by using secondary domains that redirect to your main domain.

---

## Part 1: Infrastructure Setup

### Domain & Mailbox Structure

```
1 secondary domain → 3 mailboxes → 30 emails/day each

Example:
getproduct.com (redirects to product.com)
  ├── alex@getproduct.com     (30 emails/day)
  ├── sarah@getproduct.com    (30 emails/day)
  └── mike@getproduct.com     (30 emails/day)

1 domain = 90 emails/day = 30 leads/day (3-step sequence)
```

### Mailbox Providers

Split 50/50 for best deliverability:
- **Google Workspace** ($6/mo) - best for Gmail recipients
- **Microsoft Outlook** ($6/mo) - best for Outlook recipients

### Warmup Requirements

- **2 weeks warmup** before sending
- Join warmup pool (1M+ accounts)
- Start at 5 emails/day, gradually increase to 30
- Never skip warmup or you'll hit spam folders

### Deliverability Factors

**Email Content:**
- Personalized (recipient name, company)
- Minimal links, HTML, images
- No attachments
- Avoid spam keywords

**Sender Reputation:**
- IP & domain reputation
- SPF, DKIM, DMARC authentication
- Bounce rates <2%
- Spam complaint rates <0.1%

**Sending Behavior:**
- Consistent daily volume (no spikes)
- Human-like timing (business hours)
- Match recipient email provider

---

## Part 2: Capacity Planning

### Calculate Domains Needed

**Reverse engineer from revenue goal:**

```
Target: 1 new client/week
← 5 meetings needed
← 20 interested replies needed
← 600 leads/week needed
← 4 domains (12 mailboxes) needed
```

### Cost Structure

**Tier 1 - Getting Started (~$109-258/mo):**
- 3 domains, 9 mailboxes: $54/mo
- Scheduling software: $37/mo
- Email verification: $18 (pay as you go)
- List building: $0-149/mo
- **Volume: ~1,667 leads/mo**
- **Cost per lead: ~$0.15**

**Tier 2 - Scaling (~$950/mo):**
- 20 domains, 60 mailboxes: $360/mo
- Scheduling software: $97/mo
- Email verification: $75
- List building: $349/mo
- **Volume: ~10,000 leads/mo**
- **Cost per lead: ~$0.10**

---

## Part 3: Email Sequence Templates

### Email 1: Post Initial Contact

Use after meeting at event, call, or referral.

```
SUBJECT: Great meeting you at [event/context]

Hi [Name],

[Opener: Reference where/how you met]

[Observation: What you learned about their situation]

[Value Proposition: Brief, no feature lists - focus on outcome]

[CTA: Specific next step]

P.S. [Soft CTA: Additional resource, case study, or question]
```

### Email 2: Post Discovery Call

Use after qualifying conversation.

```
SUBJECT: Recap: [Key insight from call]

Hi [Name],

Great chatting earlier. Here's what I heard:

**Current State:**
- [Their status quo]
- [Pain discovered]
- [Desired outcome]

**How We Help:**
[Personalized value prop based on their specific needs]

**Potential Blockers:**
[Proactively address concerns raised or likely]

**Next Steps:**
[Mutually agreed roadmap - demo, stakeholders, timeline]

P.S. [Relevant case study or resource]
```

### Email 3: Post Demo Call

The most critical follow-up.

```
SUBJECT: [Product] for [Company] - recap & next steps

Hi [Name],

Thanks for the demo today. Summary:

**What I Heard:**
- Current state: [their situation]
- Pain: [specific problem + business impact]
- Goal: [desired outcome]

**How [Product] Helps:**
[Personalized capabilities → benefits]
- [Feature A] → [Benefit for them]
- [Feature B] → [Benefit for them]

**What Others Say:**
[Relevant social proof - ideally from similar company]

**Questions Raised:**
[Address each concern proactively]

**Next Steps:**
[Specific timeline and owners]

P.S. [Additional resource or limited-time offer]
```

### Cold Email (First Contact)

```
SUBJECT: [Personalized, curiosity-driven]

Hi [Name],

[Hook: Observation about them/company - recent news, LinkedIn post, etc.]

[Problem: Relevant pain point they likely face]

[Solution: Brief value prop - 1-2 sentences max]

[Social Proof: 1 credibility signal]

[CTA: Low-friction ask - "worth a quick chat?" not "can I demo?"]

[Signature]
```

---

## Part 4: Email Copy Principles

### Structure

1. **Hook** (1 sentence) - Personalized observation
2. **Problem** (1-2 sentences) - Relevant pain
3. **Solution** (1-2 sentences) - Your value prop
4. **Proof** (1 sentence) - Credibility signal
5. **CTA** (1 sentence) - Low-friction ask

### What Works

- Personalized first lines (research them)
- Specific, quantifiable outcomes
- Social proof from similar companies
- Clear, single CTA
- Short emails (under 125 words)

### What Doesn't Work

- Generic "I hope this finds you well"
- Feature lists
- Multiple CTAs
- Attachments
- Long emails
- "Checking in" follow-ups

---

## Part 5: Follow-Up Sequence

### Recommended Structure

```
Day 1: Initial email
Day 3: Follow-up 1 (add context/angle)
Day 7: Follow-up 2 (share resource)
Day 14: Follow-up 3 (different CTA)
Day 21: Break-up email
```

### Follow-Up Templates

**Follow-up 1:**
```
Hi [Name],

Bumping this up. Any thoughts on [value prop]?

[New angle or additional context]

[CTA]
```

**Follow-up 2:**
```
Hi [Name],

Thought you might find this useful: [relevant resource]

[One sentence why it's relevant]

Worth a chat?
```

**Break-up Email:**
```
Hi [Name],

I'll assume [problem] isn't a priority right now.

If that changes, I'm here. Otherwise, I won't keep reaching out.

[Signature]
```

---

## Quick Reference

| Metric | Target |
|--------|--------|
| Open rate | >40% |
| Reply rate | >5% |
| Bounce rate | <2% |
| Spam rate | <0.1% |
| Emails/mailbox/day | 30 max |

**Tech Stack:**
- Mailboxes: Google Workspace + Outlook (50/50)
- Scheduling: Instantly or Smartlead
- Verification: ZeroBounce
- List building: Clay

**Golden Rule:** One personalized email beats 100 generic ones.
