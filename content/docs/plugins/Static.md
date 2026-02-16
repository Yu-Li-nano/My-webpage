---
publish: true
permalink: /docs/plugins/Static.md
title: Static
created: 2026-02-15T23:02:38.428+08:00
modified: 2026-02-15T23:02:38.428+08:00
tags:
  - plugin/emitter
cssclasses: ""
---


This plugin emits all static resources needed by Quartz. This is used, for example, for fonts and images that need a stable position, such as banners and icons. The plugin respects the `ignorePatterns` in the global [[docs/configuration]].

> [!important]
> This is different from [[docs/plugins/Assets]]. The resources from the [[docs/plugins/Static]] plugin are located under `quartz/static`, whereas [[docs/plugins/Assets]] renders all static resources under `content` and is used for images, videos, audio, etc. that are directly referenced by your markdown content.

> [!note]
> For information on how to add, remove or configure plugins, see the [[docs/configuration#Plugins\|Configuration]] page.

This plugin has no configuration options.

## API

- Category: Emitter
- Function name: `Plugin.Static()`.
- Source: [`quartz/plugins/emitters/static.ts`](https://github.com/jackyzha0/quartz/blob/v4/quartz/plugins/emitters/static.ts).
