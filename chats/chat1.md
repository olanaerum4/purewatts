# Pure Watts Affiliate UI

_Started 2026-06-10 09:20 UTC_

---

## User

Make a UI for an affilate marketing website for an endurance tiktok page called Pure Watts, with articles like "save 5w for under $5" for example. here is the list, just use english and usd,

## Assistant

_[tool: questions_v2]_

## User

Questions answered:
- pages: Homepage / feed of articles, Single article page (like 'Save 5W for under $5'), Product card / single product review
- layout_vibe: Decide for me
- device: Both side by side
- goal: Affiliate link clicks (buy on Temu)
- tone: Decide for me
- variations: Decide for me

## Assistant

_[tool: update_todos]_

_[tool: copy_starter_component]_

_[tool: write_file]_

Now I'll build the full wireframe file — 3 homepage directions × mobile/desktop, plus article page and product card variants.

_[tool: done]_

_[tool: fork_verifier_agent]_

Here's what I built — **5 sections** of wireframes for Pure Watts:

---

**3 Homepage directions** (each shown mobile + desktop):
- **A – Editorial Feed** — Wirecutter-style article list with a savings sidebar. Best for SEO + long-form trust-building.
- **B – Card Grid** — TikTok-native product grid with savings badges as the hero. Best for click-through rate from social.
- **C – Comparison Table** — All 9 picks in one data table (branded price vs yours vs savings). Best for comparison-shoppers.

**Article page** — personal testing badge, branded vs this pick comparison box, pull quote, sticky affiliate CTA sidebar.

**3 Product card variants** — A (savings-first), B (trust/quote-first), C (compact row).

---

**Next steps — which direction resonates?** Once you pick one (or say "mix of A + B" etc.) I can move into a hi-fi build with real styling, your referral links, and all 9 products.

## User

Make it look more proffetsjonal

## Assistant

_[tool: update_todos]_

_[tool: write_file]_

_[tool: write_file]_

Now the article page:

_[tool: done]_

_[tool: fork_verifier_agent]_

Here's what's ready — two hi-fi pages:

**[Pure Watts.html](Pure Watts.html) — Homepage**
- Sticky nav with category filter pills (Cycling, Running, Tools, Safety, Under $5, Save $30+)
- Bold dark hero with live stats ($272 total savings, 10 picks, etc.)
- Responsive 3→2→1 column product grid, all 10 products with real prices, star ratings, taglines and affiliate links
- Referral code banner + footer

**[Pure Watts Article.html](Pure Watts Article.html) — Single product review**
- Full Aero Socks review with branded vs. this pick comparison box
- Pull quote, specs grid, verdict callout
- Sticky sidebar with savings callout + affiliate CTA
- Related picks at the bottom

Cards on the homepage link through to the article page (Aero Socks) or directly to Temu for the other products.

**Next steps — what to work on:**
- Drop in real product photos to replace the stripe placeholders
- Build out article pages for the remaining 9 products
- Add an email capture / TikTok follow prompt
- Any copy, color, or layout tweaks

## User

No issues found

## Assistant

All clean. The site is ready to use as-is — just swap in real product photos and you're live.

A few quick wins if you want to keep going:
- **Real photos** — drag product images into the placeholder areas
- **More articles** — I can build out the remaining 9 product pages in the same format
- **Email capture** — a simple "get new picks" signup strip in the hero or footer
- **TikTok embed** — pull your latest video into the homepage

What would you like to tackle next?

