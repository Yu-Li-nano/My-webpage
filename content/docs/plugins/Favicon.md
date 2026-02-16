---
publish: true
permalink: /docs/plugins/Favicon.md
title: Favicon
created: 2026-02-15T23:02:38.427+08:00
modified: 2026-02-15T23:02:38.427+08:00
tags:
  - plugin/emitter
cssclasses: ""
---


This plugin emits a `favicon.ico` into the `public` folder. It creates the favicon from `icon.png` located in the `quartz/static` folder.
The plugin resizes `icon.png` to 48x48px to make it as small as possible.

> [!note]
> For information on how to add, remove or configure plugins, see the [[docs/configuration#Plugins\|Configuration]] page.

This plugin has no configuration options.

## API

- Category: Emitter
- Function name: `Plugin.Favicon()`.
- Source: [`quartz/plugins/emitters/favicon.ts`](https://github.com/jackyzha0/quartz/blob/v4/quartz/plugins/emitters/favicon.ts).
