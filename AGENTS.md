# AGENTS.md — jonathanmccallum-my (Burmese mirror of jonathanmccallum.com)

Burmese mirror site. Same theme and design as the main site (Paper Light),
content translated into Burmese, meaning-first. Repo: streamjonathan/jonathanmccallum-my.
Live: jonathanmccallum-my.pages.dev (Jonathan approved all 50 mirrors live, 22 Nov 2026).
Custom subdomain my.jonathanmccallum.com comes later, via the dashboard.

## Mission

Mirror jonathanmccallum.com in Burmese — every article translated for meaning,
not word for word, in Jonathan's voice: plain short sentences, friendly, positive,
never preachy. An average person interested in Jesus, not an expert or theologian.

## Roles

- **Bobby (Muse) is the lead builder.** He coordinates, builds, pushes to GitHub
  and deploys to Cloudflare. He is the ONLY one who pushes or deploys.
- **Claude advises and reviews** translation quality. He does not push or deploy.
- **Helper Muses translate** one article at a time, drafts only.

## Publishing

Jonathan approved all 50 language mirrors live (22 Nov 2026), so this mirror
goes live on jonathanmccallum-my.pages.dev with its 5 proof articles.
The custom subdomain my.jonathanmccallum.com is a later dashboard step. New articles stay drafts
until he approves them.

## Translation rules

- English repo (streamjonathan.github.io) is the source of truth. Articles are
  translated from the English Markdown, keeping the same date, slug, source_video
  and shareImage. Only the title and body are translated.
- Script: Myanmar (Burmese) Unicode, left-to-right.
- Register: plain, warm, honest; short sentences; no preaching. Reader addressed
  as သင် (polite "you") with plain verb endings (တယ် / ပါ). FLAG for Jonathan:
  if a warmer casual မင်း is preferred, pronouns and some verb forms change.
- Names (never vary): God ဘုရားသခင်, Jesus ယေရှု (Judson Bible forms), Aslan
  အက်စလန်, Narnia နာနီးယား, Lewis လူးဝစ်, Lucy လူစီ, Digory ဒီဂိုရီ, Tirian
  တီရီယန်, Adam and Eve အာဒံနှင့်ဧဝ, Peter ပေတရု. Book titles are kept in
  English — no published Burmese translations found, flagged.
- "Surfer" is the loanword ဆားဖာ — alternative descriptive rendering
  "လှိုင်းစီးတဲ့ သာမန်လူတစ်ယောက်" flagged for Jonathan. "Free will" =
  လွတ်လပ်သောဆန္ဒ, flagged (alternative လွတ်လပ်စွာ ရွေးချယ်ခွင့်).
- Bible verses: the bread/water of life lines are Jonathan's paraphrase, never
  quoted as Scripture. No direct Lewis quotations appear.
- No emojis, no newsletter form, no links the English article does not have.
- Never invent facts, dates, links or details.

## Site facts

- Eleventy 3, Cloudflare Pages, Paper Light theme (Fraunces + Newsreader).
- No Ask chat and no note Worker on this site yet — search (Pagefind) works,
  Ask and notes come later. The Ask floating button and ask.js are removed.
- CSS is preloaded, not inlined (CSP blocks inline style). Bump the `?v=` query
  on any CSS/JS file you change.
