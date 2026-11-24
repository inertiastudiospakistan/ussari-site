# Ussari Labs — ussari.dev site

Static site for **Ussari Labs**, a Pakistani software engineering and AI studio
founded by three friends. Built to the Brand Guidelines Vol. 01
("Structural Precision") — strict grids, sharp 90° angles, no gradients, no
rounding, no shadows.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole site: hero, pillars, about, services, sectors, work/proof, founder, contact |
| `styles.css` | All styling. Tokens are the five guideline colours; nothing else |
| `mark.svg` | The three-block "U" mark (favicon). Also inlined in the header/footer |

## Brand tokens (definitive — do not change without the founders)

- Kinetic Crimson `#DC2626` — active / interactive states only
- Alabaster Tint `#F8F4F4`
- Muted Slate `#A39E9E` — tertiary text
- Absolute White `#FFFFFF`
- Asphalt Charcoal `#1A1515`
- Deep Oxide Red `#4A0E17` — structure / borders
- 60 / 30 / 10 distribution: domain space / framework / spark
- Type: Space Grotesk 700 uppercase headers, Inter body, JetBrains Mono technical
- Zero border-radius. 1px structural borders. Crimson reserved for active states.

The mark is a "U" of three interlocking blocks, one per founder. Never recolour
the blocks outside the palette, add shadows or gradients, round the corners,
rotate the mark, or separate the blocks. Minimum size 34px in digital use.
On light surfaces the blocks are Asphalt Charcoal; on dark surfaces, white
(the primary / reversed variants from the guidelines).

## Content rules enforced in this build

- **No email address anywhere on the site.** Neither `adil@ussari.dev` nor
  `hello@ussari.dev` is active (confirmed by the user, 23 Nov 2026). The only
  contact route is the request form: https://forms.gle/pKDLBtsbxF8gc8SB7
  (verified live, HTTP 200, 23 Nov 2026).
- **No phone number.** The number on the visiting card (+92 300 0000000) is a
  placeholder. Leave phone off until the user confirms a real number.
- **Adil Warraich is ONE of three founders** — founder/developer and AI
  engineering lead. Never presented as sole founder. The other two founders'
  names and roles are unknown; the site says "three friends, one structure"
  and adds their profiles only when confirmed.
- **No invented claims.** Every number on the site is verified: vibe-audit
  (1,063 lines, stdlib-only, 9 areas, $49 after 5 free), Android builds
  (ClearLedger build-22, Saudi EOS Calculator build-8, targetSdk 36),
  harness (199 endpoints, 32 enabled). HIMS is described, never linked —
  its repos are private. Nodefield is shelved and omitted entirely.
- Copy in en-GB. No clients, revenue or testimonials claimed — none exist yet.

## Domain status (23 Nov 2026 — verify again before buying)

- **ussari.dev is AVAILABLE** (WHOIS lookup, who.is, 23 Nov 2026: "Available —
  no WHOIS data found"). No website, no indexed presence, no social presence
  found. The user does **not** own it.
- **Price, Cloudflare Registrar: $8.20 first year, $12.20/yr renewal**
  (confirmed by TLDMath, TLDSpy, cheapest.domains, hostlist.io — all read
  23 Nov 2026). 2-year total $20.40; 5-year $57.00. Porkbun is $8.75 / $12.87.
  Cloudflare is cheapest and the user already uses Cloudflare DNS.
- **Do NOT buy without the user's explicit approval** — it is a morning decision.
- Owning ussari.dev is the prerequisite for ever activating hello@ussari.dev
  (e.g. via free Cloudflare Email Routing forwarding to an existing mailbox).
  Until then, the form is the only contact route.

## Deploy (when the user approves)

Static files only — no build step, no backend.

- **Cloudflare Pages (recommended):** connect the repo, build command empty,
  output directory the repo root. Custom domain ussari.dev once owned.
- **GitHub Pages:** same files, any static host works.

Do not deploy, create a repo, or register the domain until the user approves.

## Open questions (need the user / founders)

1. The other two founders' names and roles.
2. Who registers ussari.dev — approval to buy at Cloudflare ($8.20 first year).
3. Whether the studio is formally registered (company registration, tax status).
4. Any existing site or social accounts under the Ussari name.
5. A real phone number, if the studio wants one published.
6. Whether hello@ussari.dev should be activated (via Cloudflare Email Routing)
   once the domain is owned.
