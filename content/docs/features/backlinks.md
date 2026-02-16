---
publish: true
permalink: /docs/features/backlinks.md
title: Backlinks
created: 2026-02-15T23:02:38.416+08:00
modified: 2026-02-15T23:02:38.416+08:00
tags:
  - component
cssclasses: ""
---


A backlink for a note is a link from another note to that note. Links in the backlink pane also feature rich [[docs/features/popover previews]] if you have that feature enabled.

## Customization

- Removing backlinks: delete all usages of `Component.Backlinks()` from `quartz.layout.ts`.
- Hide when empty: hide `Backlinks` if given page doesn't contain any backlinks (default to `true`). To disable this, use `Component.Backlinks({ hideWhenEmpty: false })`.
- Component: `quartz/components/Backlinks.tsx`
- Style: `quartz/components/styles/backlinks.scss`
- Script: `quartz/components/scripts/search.inline.ts`
