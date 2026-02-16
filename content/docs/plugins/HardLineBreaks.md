---
publish: true
permalink: /docs/plugins/HardLineBreaks.md
title: HardLineBreaks
created: 2026-02-15T23:02:38.427+08:00
modified: 2026-02-15T23:02:38.427+08:00
tags:
  - plugin/transformer
cssclasses: ""
---


This plugin automatically converts single line breaks in Markdown text into hard line breaks in the HTML output. This plugin is not enabled by default as this doesn't follow the semantics of actual Markdown but you may enable it if you'd like parity with [[docs/features/Obsidian compatibility\|Obsidian]].

> [!note]
> For information on how to add, remove or configure plugins, see the [[docs/configuration#Plugins\|Configuration]] page.

This plugin has no configuration options.

## API

- Category: Transformer
- Function name: `Plugin.HardLineBreaks()`.
- Source: [`quartz/plugins/transformers/linebreaks.ts`](https://github.com/jackyzha0/quartz/blob/v4/quartz/plugins/transformers/linebreaks.ts).
