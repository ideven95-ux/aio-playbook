# AIO Playbook

AI Optimization: the work that gets a brand cited — not just ranked — by ChatGPT, Perplexity, Google AI Overviews, and other answer engines.

## Why this matters

Search is splitting: classic results plus AI answers that cite a handful of sources. The sites that get cited share traits: clear entity identity, structured facts, quotable definitions, and topical authority. This playbook is how I build that.

## The playbook

### 1. Entity clarity
- One canonical "About" page: who you are, what you do, where you operate.
- Identical NAP (name, address, phone) everywhere: site, Google Business Profile, directories, socials.
- `Organization` + `LocalBusiness` schema with `sameAs` links to every official profile.

### 2. llms.txt
- Publish `/llms.txt` at the domain root: a markdown index of the site written for LLMs (what each section covers, key URLs).
- Template included: `llms.txt`. Adapt the sections to the business.

### 3. Citation-friendly content
- Lead with crisp definitions ("X is...") — answer engines quote these verbatim.
- Use clear H2/H3 structure; one idea per section.
- Include original data, stats, and named sources — AI cites sources, not vibes.
- FAQ sections marked up with `FAQPage` schema (example in `examples/faq-schema.json`).

### 4. Topical authority
- Cover the topic cluster fully: pillar page + supporting articles, interlinked.
- Keep content fresh — stale facts don't get cited.

### 5. Measure
- Track brand mentions in AI answers (ask the tools directly, weekly).
- Watch referral traffic from chatgpt.com, perplexity.ai, etc. in analytics.
- Iterate on pages that get cited; expand what works.

## Files

- `llms.txt` — starter template for the domain root
- `examples/faq-schema.json` — FAQPage JSON-LD example

---
Built by Tyra Redot — WordPress developer, SEO & AIO specialist. 📧 ideven95@gmail.com
