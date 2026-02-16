---
publish: true
permalink: /docs/features/Obsidian compatibility.md
title: Obsidian Compatibility
created: 2026-02-15T23:02:38.415+08:00
modified: 2026-02-15T23:02:38.415+08:00
tags:
  - feature/transformer
cssclasses: ""
---


Quartz was originally designed as a tool to publish Obsidian vaults as websites. Even as the scope of Quartz has widened over time, it hasn't lost the ability to seamlessly interoperate with Obsidian.

By default, Quartz ships with the [[docs/plugins/ObsidianFlavoredMarkdown]] plugin, which is a transformer plugin that adds support for [Obsidian Flavored Markdown](https://help.obsidian.md/Editing+and+formatting/Obsidian+Flavored+Markdown). This includes support for features like [[docs/features/wikilinks]] and [[docs/features/Mermaid diagrams]].

It also ships with support for [frontmatter parsing](https://help.obsidian.md/Editing+and+formatting/Properties) with the same fields that Obsidian uses through the [[docs/plugins/Frontmatter]] transformer plugin.

Finally, Quartz also provides [[docs/plugins/CrawlLinks]] plugin, which allows you to customize Quartz's link resolution behaviour to match Obsidian.

## Configuration

This functionality is provided by the [[docs/plugins/ObsidianFlavoredMarkdown]], [[docs/plugins/Frontmatter]] and [[docs/plugins/CrawlLinks]] plugins. See the plugin pages for customization options.
