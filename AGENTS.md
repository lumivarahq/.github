# lumivara-github-meta

The Lumivara GitHub **org profile** repo — pushed to `lumivarahq/.github` (the
local dir is named `lumivara-github-meta` so the auto-sync cron and shell globs
see it). `profile/README.md` renders on https://github.com/lumivarahq.

- Lumivara product line: **Sites** (org-facing marketing surface).
- Package manager: none (markdown only, no build).
- Public by GitHub requirement (org profile repos must be public) — this is the
  deliberate exception to the "new public repos go to palimkarakshay" rule,
  since a `.github` profile repo can only live in the org itself.

## Commands
- Develop: edit `profile/README.md`; preview with any markdown renderer.
- Verify: `git push` then check https://github.com/lumivarahq renders it.

## Layout
- `profile/README.md` — the org profile: og.png banner (hotlinked from
  lumivara.tech/og.png), studio positioning, SAP×AI flagship blurb, live
  products table, OSS pointer to `palimkarakshay`, building-with strip, contact.

## Gotchas / invariants
- Keep copy in lockstep with https://lumivara.tech (lumivara-home repo) — same
  positioning: "AI-native software studio", solo operation implicit, never
  "one-operator" explicitly.
- The banner is hotlinked to lumivara.tech/og.png — regenerating og.png in
  lumivara-home updates this page automatically; deleting/renaming it breaks
  the banner here.
- Product links must stay in sync with the live fleet (same list as the site).
