# No Leaks Plumbing & Heating

Shared rules for Claude Code and Cursor. `CLAUDE.md` and `AGENTS.md` must stay identical.

This is the concept demo for No Leaks Plumbing & Heating (owner: Jonny), a client of Callum at Clockwork AI. It is one static page, `index.html`, plus `scrollcraft.css`, `scrollcraft.js` and `assets/`. The page is `noindex`, and `robots.txt` disallows crawlers. The banner says it is a concept demo by Clockwork AI, not the official website.

## Workflow

- Fetch the latest `main` from GitHub (`clockwork-ai/no-leaks-plumbing-heating`) and branch from that. Do not edit an old local copy.
- Do the work on a branch and open a pull request. Do not push to `main`, and do not upload files directly.
- Check the Vercel preview on the pull request before you call the work done.
- Never merge without Callum's approval.

## Writing

Plain British English, as a local plumbing and heating firm would say it. The page language is `en-GB`. Short sentences. No AI buzzwords.

No em dashes and no en dashes, in copy, titles, comments or commit messages. Titles use a pipe: `No Leaks Plumbing & Heating | Bathrooms in Worsley`. Ranges use "to" (2023 to 2025, Worsley to Leigh).

Use only facts Jonny or Callum have supplied. Do not invent reviews, testimonials, stats, accreditations or guarantees. Leave the Facebook reviews and the counts already in `index.html` as they are, unless a new fact has been supplied.

## What does not belong on this site

Clockwork's pricing and the six systems belong in Clockwork's customer guide, not on this client's site, and not in this repo.

## Name

The business name is No Leaks Plumbing & Heating. Any "Nolix" spelling is a mistake: correct it to No Leaks Plumbing & Heating. The logo alt text and the demo banner also say "No Leaks Plumbing & Heating Services". That is the logo wording. Do not change it unless Callum asks.

## Brand

Set on `:root` in `index.html`, taken from the logo. These values replace the Scrollcraft defaults in `scrollcraft.css`.

Colours:

- Navy `#0B2F6B` (`--navy`), mid navy `#0F3D87` (`--navy-2`), deep navy `#071F49` (`--navy-deep`). The theme colour is the navy.
- Flame orange `#F04A1C` (`--flame`). Filled buttons use `#C2380B` (`--flame-ink`), hover `#A92F07`. The emphasised word in the hero is `#FF7A4D`.
- Water blue `#0078C0` (`--water`), a logo colour. It is declared and not applied to a block yet.
- Paper `#F5F7FB` (`--paper`), second paper `#E9EEF6` (`--paper-2`), line `#D5DDEA` (`--line`).
- Ink `#0D1B33` (`--ink-dark`), soft ink `#4A5876` (`--ink-dark-soft`). Text on navy is `#F4F7FC`, soft text on navy `#B9C6DE`.

WhatsApp green (`#128C4A`) and Facebook blue (`#1877F2`) are those platforms' buttons, not brand colours.

Fonts, loaded from Google Fonts in `index.html`:

- Display: Bricolage Grotesque, weights 600, 700 and 800. Headings and the phone menu.
- Body: Geist, weights 400, 500 and 600. Prose, buttons and labels.
- `scrollcraft.css` still defaults display to Instrument Sans and mono to Geist Mono. This page does not load those faces.

Light sections use `.ground-light` (paper) or `.ground-white` (white). The hero, phone menu, contact block and footer sit on navy.

## Page

Top to bottom in `index.html`:

1. Demo banner.
2. Sticky bar: logo, nav (Bathrooms, Services, Before and after, Reviews, Contact), Gas Safe mark, call button. At 960px and below, the nav and call button hide. A menu button opens a full-screen navy menu, which also links to Areas.
3. Hero, pinned while you scroll. Navy ground, a round window opens onto one of Jonny's finished bathrooms. Call, WhatsApp and Get a quote. A second line fades in as the window opens.
4. Trust strip on white: Gas Safe registered, Facebook recommendation, based in Worsley, one price for the whole job.
5. Services on paper: bathroom specialist (design to sign-off), boiler replacements, then boiler servicing, central heating, general plumbing and domestic gas work.
6. Bathrooms, pinned while you scroll. Photos from one real job and a job ticket: survey and one price, strip-out, first fix plumbing and electrics, boarding and plastering, tiling and fit-out, tested and signed off.
7. Before and after on paper. A slider, five rooms, a photo row, and a Facebook follow link.
8. Reviews on white. The page says the quotes are word for word from his Facebook page.
9. Areas on paper. Based in Worsley, working across Greater Manchester. Towns are listed on the page. Do not add towns.
10. Contact on navy: 07538 951971, WhatsApp, noleaksplumbingandheating@outlook.com, Facebook, and a quote form. The form is demo only. It does not send.
11. Footer, then a fixed Call and WhatsApp bar at 760px and below.

Photos are in `assets/`. Logos: `assets/logo-noleaks.png` (bar) and `assets/logo-noleaks-reverse.png` (menu and footer). Gas Safe mark: `assets/gas-safe.svg`. Share image: `og.jpg`.

Scroll pinning comes from `scrollcraft.js`. Put new layout in `index.html`. Leave Scrollcraft's device classes in `scrollcraft.css` alone. The comment at the top of that file says the same.

## Facts to keep

Change these only when Jonny or Callum supply a new fact.

- Jonny. Phone and WhatsApp: 07538 951971. Email: noleaksplumbingandheating@outlook.com.
- Gas Safe registered. Based in Worsley, covering Greater Manchester.
- A full bathroom is one price. Jonny books and manages plumbing, electrics, boarding, plastering and tiling. An approved electrician does the electrics and the sign-off.
- Facebook: https://www.facebook.com/p/No-leaks-plumbing-and-heating-services-100034855281160/
