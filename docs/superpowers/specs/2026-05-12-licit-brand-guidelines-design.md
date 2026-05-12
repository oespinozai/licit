# Licit — Brand Guidelines Design Spec

**Date:** 2026-05-12
**Product:** Licit — SEACE procurement intelligence for Peruvian suppliers
**Reference:** Linear.app design language

---

## 1. Logo & Wordmark

- **Isologo:** 3 vertical bars of decreasing height (parallel, like a signal/radar strength indicator). Color `#0A2FFF`.
- **Wordmark:** "licit" in Satoshi Bold, all lowercase, no dots or stylizations.
- **Variants:** Horizontal (symbol + wordmark side by side), symbol-only (favicon/avatar), wordmark-only.
- **Exclusions:** No outline versions, no shadows, no gradients, no tagline inside the logo.

## 2. Color Palette

| Role | Hex | Usage |
|---|---|---|
| Primary | `#0A2FFF` | Buttons, links, accents, symbol |
| Text | `#0A0A0A` | Headings, body |
| Text-secondary | `#5C6170` | Metadata, descriptions |
| Text-tertiary | `#8A90A0` | Tiny text, placeholders |
| Border | `#E7E9F0` | Cards, inputs, dividers |
| Surface | `#FFFFFF` | Card backgrounds, panels |
| Bg | `#FAFAFA` | Page background |
| Success | `#0F9F6E` | Live pills, alert indicators |

Rules: No secondary color. No UI element gradients. Hover = primary at 90% opacity.

## 3. Typography

- **Primary:** Satoshi (Fontshare), variable weight. 400, 500, 700, 900 used. Never Light (300) or Thin (100).
- **Monospace:** JetBrains Mono or Space Mono (Google Fonts) for codes, IDs, tender numbers.
- **Scale:** H1 900 / clamp(2.8rem–4.7rem) / `-0.055em` tracking. H2 700 / clamp(1.75rem–2.45rem) / `-0.04em`. H3 700 / 1.1rem / `-0.03em`. Body 400 / 1rem / 1.6 line-height.

## 4. Spacing & Layout

- Max width: 1180px
- Border radius: 10px (sm), 14px (md), 18px (lg)
- Shadows: `--shadow-sm` (cards), `--shadow-md` (CTAs/modals) — very subtle
- Card padding: 20px consistent
- Gaps: 12-16px elements, 24px section columns
- Breakpoints: 1080px → 1 column, 720px → hidden nav

## 5. Voice & Tone

- Direct, professional, no legal jargon
- "Usted" register but not overly formal
- Short sentences, max 3 lines per paragraph
- Translate anglicisms: feedback → retroalimentación, onboarding → registro, deadline → fecha límite
- No marketing fluff. No superlatives. Show, don't claim.

## 6. Application Examples (to include in brand guide HTML)

- WhatsApp alert card simulation
- Pricing card (refined existing)
- High-priority signal feed card
- Navigation bar with logo
- Button system (primary, secondary, sizes)
- Pill/tag component (live, category, priority)
