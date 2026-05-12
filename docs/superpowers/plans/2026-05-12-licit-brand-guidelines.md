# Licit Brand Guidelines Implementation Plan

> **For agentic workers:** Single-file HTML implementation. One task, inline execution.

**Goal:** Build a brand guidelines page for Licit following the approved spec (Linear-inspired design language).

**Architecture:** Single HTML file with embedded CSS. Self-contained, no build step, no dependencies. Can be hosted alongside the existing landing page.

**Tech Stack:** Vanilla HTML + CSS, Satoshi font via Fontshare, JetBrains Mono via Google Fonts.

---

### Task 1: Brand Guidelines HTML Page

**Files:**
- Create: `/root/licit/brand.html`

- [ ] **Step 1: Write the brand guidelines page**

Write a single HTML page with embedded CSS containing the following sections:
1. Logo lockups (symbol + wordmark variations)
2. Color palette (swatches with hex codes, usage descriptions)
3. Typography (headings, body, mono with size/weight/letter-spacing)
4. Spacing & layout tokens (radius, shadow, max-width)
5. Voice & tone (examples of what to say and what not to say)
6. UI components (buttons, pills, cards, navigation bar)
7. Application examples (WhatsApp alert, pricing card, signal feed card)

Design follows: `#0A2FFF` primary, Satoshi font, Linear-style minimalism (white bg, thin borders, subtle shadows, generous whitespace).

- [ ] **Step 2: Open brand.html in browser to verify**

Serve locally or open directly and check each section renders correctly.

- [ ] **Step 3: Commit**

```bash
cd /root/licit && git add brand.html && git commit -m "feat: add brand guidelines page"
git push
```
