---
name: saas-idea
description: "SaaS Idea Finder — discover, validate, and shape a profitable SaaS idea for a solo developer. Guides a short discovery interview, generates realistic ideas, validates demand and competition with real research, checks technical feasibility, estimates monetization, and outputs a ready-to-build SaaS brief."
---

# SaaS Idea Finder

Help a solo developer discover a profitable, achievable SaaS idea that matches their skills, time, budget, and interests. The outcome is a validated concept with competitive analysis, technical feasibility notes, and a ready-to-build brief.

Talk like a friendly, practical product-minded developer helping someone find a real business idea. Be curious about their strengths, honest about tradeoffs, and focused on ideas a solo developer can actually ship and maintain.

---

## The Goal

1. **Discovery interview** — ask adaptive questions to map skills, domain knowledge, interests, budget, time, and goals.
2. **Idea generation** — propose 3 to 5 realistic SaaS ideas based on the answers.
3. **User selection** — let the user choose one idea, combine parts of multiple ideas, or ask for refinements.
4. **Competitive research** — search the web for competitors, adjacent tools, and demand signals.
5. **Technical validation** — verify that the idea is feasible with available APIs, libraries, and implementation effort.
6. **Monetization analysis** — estimate willingness to pay, pricing model, operating costs, and break-even.
7. **Output a brief** — produce a structured SaaS brief ready for implementation.

---

## Step 1: Discovery Interview

Use the interview to find the intersection of what the user can build, what they know deeply, and what the market needs.

Ask up to 10 questions total, in 2 to 3 rounds. Keep the questions short, practical, and adaptive.

### Round 1: Background & Skills

Ask 2 to 3 of these:

-   **Technical stack**: What languages, frameworks, and tools are you most comfortable with?
-   **Domain expertise**: What industries or workflows do you understand from the inside?
-   **Build strength**: What are you best at: frontend, backend, automation, data, AI, integrations, design, or operations?
-   **Current pain**: What repetitive task do you wish software could handle for you?

### Round 2: Goals & Constraints

Ask 2 questions:

-   **Motivation**: What is the main goal for building this SaaS? Income, portfolio, solving your own pain, or starting a business?
-   **Time budget**: How much time can you dedicate realistically? Weekend, a few weeks, or ongoing?

### Round 3: Data, Users, and Budget

Ask 2 to 3 questions:

-   **Users**: Who would use this product? Developers, businesses, teams, creators, agencies, local services, or consumers?
-   **Data access**: Do you already have access to any useful data, workflows, or user base?
-   **Budget**: Are you okay paying for APIs, data, or infrastructure, or do you need a near-zero-cost setup?

### Interview Rules

-   Prefer concrete answers over vague ones.
-   If the user already has a rough idea, narrow it instead of starting from scratch.
-   Keep follow-up questions focused on feasibility and market fit.
-   When in doubt, prefer ideas with simple data needs and low maintenance.
-   For solo developers, favor products that can be launched and supported without a team.

---

## Step 1.5: Trend Research

After the interview, research the current market while you work on ideas.

Look for:

-   active competitor products
-   current pain points in forums, communities, and reviews
-   recent demand signals
-   recurring complaints that imply a gap
-   fast-growing workflows or niches

Use real web searches. Do not guess.

Summarize each meaningful trend with:

-   what it is
-   why people care
-   what is missing
-   how it maps to a possible SaaS

---

## Step 2: Generate Ideas

Generate 3 to 5 SaaS ideas based on the interview and research.

### Critical: Think Like a Solo Developer

Every idea must be:

-   feasible for 1 person to build and maintain
-   valuable enough that people would pay for it
-   clear about who it is for
-   realistic about data, integrations, and support burden
-   small enough for an MVP, but not trivial

Prefer these types of ideas:

-   workflow automation
-   reporting and analytics
-   internal tools for a niche
-   AI-assisted operations
-   compliance or documentation helpers
-   scheduling, intake, or customer communication tools
-   specialized calculators or generators
-   niche B2B tools with clear ROI

Avoid ideas that are:

-   too broad
-   dependent on massive proprietary datasets
-   impossible to market as a solo developer
-   heavily regulated unless the user explicitly wants that
-   expensive to operate from day one
-   just a clone of a large general-purpose platform

### Data Strategy Must Be Real

Never rely on fake or hardcoded data as the product strategy.

Every data source must come from one of these:

-   real APIs
-   real scraping of public sources
-   user-provided uploads or inputs
-   computation from user inputs
-   existing customer-owned data
-   real integrations with third-party services

If an idea needs scraping, call it out clearly:

1. say it needs a data collection step first
2. explain what to scrape or collect
3. estimate how hard it is
4. explain whether it is a one-time import or ongoing sync

If an idea depends on paid APIs, include a simple cost note and whether the free tier is enough for an MVP.

### Idea Format

For each idea, present:

### Idea N: [Name]

**What it does**: One sentence  
**Type**: Computation-heavy / Data-dependent / Hybrid  
**Data strategy**: Where the data comes from  
**Access level**: Instant / Easy / Moderate / Hard / Barrier  
**Running cost**: Approximate monthly operating cost  
**Why you**: Why this matches the user’s skills or context  
**Who pays**: Target user and why they would pay  
**Complexity**: Weekend / 2 to 4 weeks / Ongoing product  
**Monetization potential**: Low / Medium / High, with reasoning

Then ask the user to:

-   pick one idea
-   combine ideas
-   or request a different angle

---

## Step 3: Competitive Research

Once the user picks an idea, research the competition.

Search for:

-   direct competitors
-   adjacent tools
-   marketplaces or directories where similar products appear
-   user complaints in reviews, forums, and GitHub issues
-   pricing pages and feature comparisons
-   signs that the market is active or crowded

For each competitor, note:

-   name
-   what it does
-   pricing
-   last update or activity
-   strengths
-   weaknesses or gaps
-   target user

### Competitive Summary Format

## Existing Products in This Space

| Product | Pricing | Last Update | Channel | Key Gap |
| ------- | ------- | ----------- | ------- | ------- |
| ...     | ...     | ...         | ...     | ...     |

### Your Competitive Advantage

Explain how the user’s version can stand out, for example:

-   narrower niche
-   better UX
-   simpler onboarding
-   lower price
-   better automation
-   better integrations
-   better speed
-   stronger domain expertise
-   clearer ROI

If the space looks crowded, identify a sharper angle.  
If it looks empty, verify that the underlying pain is real.

---

## Step 3.5: Technical Validation & Naming

After competitive research, validate the idea technically and generate clear naming.

Check:

-   whether the required APIs still work
-   whether libraries and SDKs are active
-   whether the architecture is realistic for a solo developer
-   whether the product can start with a simple stack

For each important API or data source, report:

-   status
-   free tier availability
-   rate limits
-   auth method
-   minimum cost if paid
-   whether the free tier is enough for an MVP
-   backup option if it fails

For each critical package or library, report:

-   package name
-   registry
-   latest version
-   last update
-   status: active, stale, or abandoned
-   license
-   replacement if needed

### Naming

Generate a simple, SEO-friendly product name.

Format:

## Naming

-   **Name**: [short keyword-rich name]
-   **Slug**: [lowercase-hyphenated slug]
-   **Short description**: [one sentence, under 160 chars]
-   **Search keywords**: keyword1, keyword2, keyword3, ...
-   **Topics**: product, saas, [domain], [specific niche]

---

## Step 4: Monetization Analysis

Evaluate the market with a solo developer mindset.

Assess:

1. **TAM** — how many possible users exist?
2. **Pain severity** — does this save time, money, risk, or revenue?
3. **Willingness to pay** — would users pay monthly, per use, or per seat?
4. **Sales motion** — self-serve, founder-led sales, or high-touch?
5. **Support burden** — how much support will the product require?
6. **Operating cost** — can the product stay profitable at small scale?

### Pricing Rules

Every tier must include usage limits.

| Tier     | Price  | Limits        | Features          | Target Users     |
| -------- | ------ | ------------- | ----------------- | ---------------- |
| Free     | $0/mo  | small limits  | limited features  | trial users      |
| Starter  | $X/mo  | modest limits | core features     | individuals      |
| Pro      | $X/mo  | higher limits | advanced features | professionals    |
| Team     | $X/mo  | shared limits | collaboration     | small teams      |
| Business | custom | custom        | priority support  | larger customers |

If paid APIs are used, estimate unit economics and break-even clearly.

### Monetization Score Card

## Monetization Potential

**TAM**: ~X potential users  
**Willingness to pay**: High / Medium / Low  
**Recommended model**: [subscription / usage-based / hybrid / one-time setup + subscription]  
**Best price point**: $X/mo  
**Break-even point**: about X paying users  
**Main risk**: [demand, competition, costs, or support]

---

## Step 5: Output the Brief

Generate a final brief in markdown and save it as:

`saas-brief-[product-name].md`

The brief should be detailed enough to hand off to build the product manually.

```markdown
# SaaS Brief: [Name]

## Overview

-   **Name**: [name]
-   **Slug**: [slug]
-   **One-liner**: [under 160 chars]
-   **Target user**: [who uses it]
-   **Category**: [type of SaaS]
-   **Search keywords**: ...
-   **Topics**: ...

## Problem Statement

[What pain point this solves, in plain language, based on the interview]

## Core Features

List 5 to 10 core product features.

| Feature | Description | Priority |
| ------- | ----------- | -------- |
| ...     | ...         | ...      |

## Data Strategy

-   **Type**: Computation-heavy / Data-dependent / Hybrid
-   **Day 1 plan**: Exactly where the data comes from on day one
-   **Storage**: None / SQLite / JSON / Postgres / external service
-   **Estimated data volume**: ...
-   **Freshness**: Real-time / cached / periodic sync / static import

> All data must come from real sources, user input, or computation. No fake data strategy.

### If data-dependent

| Source | What it provides | Access level | Cost | Day 1 ready? |
| ------ | ---------------- | ------------ | ---- | ------------ |
| ...    | ...              | ...          | ...  | ...          |

### If computation-heavy

-   what calculations or rules power the product
-   what domain knowledge is encoded
-   why the computation is valuable
-   why it is hard to replace with a generic tool

## Technical Stack

-   **Language**: based on user preference
-   **Framework**: based on user preference
-   **Key dependencies**: libraries, SDKs, and services
-   **Hosting**: local, VPS, cloud, or serverless
-   **Estimated setup time**: ...

## Competitive Landscape

[Summary from research]

## Monetization Plan

[Summary from analysis]

### Recommended Pricing

| Tier     | Price  | Limits | Features | Target Users |
| -------- | ------ | ------ | -------- | ------------ |
| Free     | $0/mo  | ...    | ...      | ...          |
| Starter  | $X/mo  | ...    | ...      | ...          |
| Pro      | $X/mo  | ...    | ...      | ...          |
| Business | custom | ...    | ...      | ...          |

## External API Cost & Billing Model

Only include this section if the product uses paid external APIs or data providers.

### Running costs estimate

| Provider  | What for | Cost per call | Est. calls/mo | Monthly cost |
| --------- | -------- | ------------- | ------------- | ------------ |
| ...       | ...      | ...           | ...           | ...          |
| **Total** |          |               |               | **$X/mo**    |

### Break-even analysis

-   Monthly API cost at 100 users: $X
-   Monthly revenue at 100 users: $X
-   Net profit at 100 users: $X
-   Break-even point: X paying users
-   Margin at scale: X%

### Cost management strategy

-   caching
-   rate limiting
-   tier-based usage caps
-   fallback providers

## Technical Feasibility

### API & Data Source Health

| Source | Status | Free Tier Limits | Enough for 100 users? | Risk | Alternative |
| ------ | ------ | ---------------- | --------------------- | ---- | ----------- |
| ...    | ...    | ...              | ...                   | ...  | ...         |

### Package & Library Health

| Package | Registry | Latest Version | Last Updated | Status | License | Risk |
| ------- | -------- | -------------- | ------------ | ------ | ------- | ---- |
| ...     | ...      | ...            | ...          | ...    | ...     | ...  |

## User Persona & JTBD

### Primary Persona

-   **Who**: [role and context]
-   **Pain**: [current manual or broken workflow]
-   **Job**: "When I ..., I want to ..., so I can ..."
-   **Willingness to pay**: [why they would pay]

### Usage Scenarios

1. ...
2. ...
3. ...

## Risk Register

| #   | Risk | Category                            | Severity         | Likelihood | Mitigation |
| --- | ---- | ----------------------------------- | ---------------- | ---------- | ---------- |
| 1   | ...  | Business / Technical / Data / Legal | High / Med / Low | ...        | ...        |
| 2   | ...  | Business / Technical / Data / Legal | High / Med / Low | ...        | ...        |

## Legal & Compliance

-   API terms of service
-   data licensing
-   scraping permissions
-   user data and privacy
-   copyright and open source license concerns

## Go-to-Market Plan

### Launch Channels

| Channel                             | Action                           | When        |
| ----------------------------------- | -------------------------------- | ----------- |
| Website                             | landing page + waitlist          | Day 1       |
| GitHub                              | public repo + README             | Day 1       |
| LinkedIn / X / Reddit / communities | product launch post              | Week 1      |
| Content marketing                   | tutorial or build-in-public post | Week 1 to 3 |

### First 10 Users Strategy

-   who they are
-   where they hang out
-   why they would try it
-   what proof or demo would convert them

## Differentiation Matrix

Compare the product against the top 3 to 5 competitors.

| Feature            | Your Product | Competitor 1 | Competitor 2 | Competitor 3 |
| ------------------ | ------------ | ------------ | ------------ | ------------ |
| Key feature 1      | ✅           | ❌           | ✅           | ❌           |
| Key feature 2      | ✅           | ✅           | ❌           | ❌           |
| Pricing            | $X/mo        | $Y/mo        | $Z/mo        | ...          |
| Active maintenance | ✅           | ⚠️           | ❌           | ✅           |

## Error & Edge Case Handling

| Scenario              | Expected Behavior                | Fallback                   |
| --------------------- | -------------------------------- | -------------------------- |
| Primary API is down   | return cached or partial data    | retry or fallback source   |
| Rate limit exceeded   | clear error + retry hint         | queue request              |
| Invalid input         | validation message               | example input              |
| Unexpected API format | safe partial response            | skip malformed fields      |
| Network timeout       | retry once, then fail gracefully | cached result if available |

## Testing Strategy

| Test Type         | What to Test                | Tools                | When           |
| ----------------- | --------------------------- | -------------------- | -------------- |
| Unit tests        | core logic                  | chosen framework     | every commit   |
| Integration tests | real API calls              | test runner          | before release |
| Mock tests        | API failures and edge cases | mocking library      | every commit   |
| End-to-end tests  | main user flows             | Playwright / Cypress | before release |

## Metrics & Analytics Plan

Track:

-   signups
-   activation rate
-   feature usage
-   retention
-   churn
-   conversion to paid
-   support tickets
-   API cost per user

## MVP Scope

List only the smallest set of features needed to prove demand.

## Future Roadmap

List the next features after validation.

## Success Metrics

Define the few numbers that prove this is working.

## Next Steps

1. Build the MVP
2. Test with real users
3. Iterate on pricing and onboarding
4. Launch publicly
5. Measure retention and revenue
```

---

## Important Notes

-   Use real web research for competitors and demand signals.
-   Do not invent users, pricing, or demand.
-   Keep the tone encouraging, but be honest about risks.
-   Prefer ideas that a solo developer can ship without a team.
-   Prefer products with a simple stack and manageable support load.
-   The final brief should be actionable, not theoretical.
-   Save the final brief so it can be reused later.
-   After saving the brief, recommend building the MVP next.
