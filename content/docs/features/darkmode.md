---
publish: true
permalink: /docs/features/darkmode.md
title: Darkmode
created: 2026-02-15T23:02:38.416+08:00
modified: 2026-02-15T23:02:38.416+08:00
tags:
  - component
cssclasses: ""
---


Quartz supports darkmode out of the box that respects the user's theme preference. Any future manual toggles of the darkmode switch will be saved in the browser's local storage so it can be persisted across future page loads.

## Customization

- Removing darkmode: delete all usages of `Component.Darkmode()` from `quartz.layout.ts`.
- Component: `quartz/components/Darkmode.tsx`
- Style: `quartz/components/styles/darkmode.scss`
- Script: `quartz/components/scripts/darkmode.inline.ts`

You can also listen to the `themechange` event to perform any custom logic when the theme changes.

```js
document.addEventListener("themechange", (e) => {
  console.log("Theme changed to " + e.detail.theme) // either "light" or "dark"
  // your logic here
})
```
