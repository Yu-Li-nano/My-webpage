---
publish: true
permalink: /docs/plugins/ExplicitPublish.md
title: ExplicitPublish
created: 2026-02-15T23:02:38.427+08:00
modified: 2026-02-15T23:02:38.427+08:00
tags:
  - plugin/filter
cssclasses: ""
---


This plugin filters content based on an explicit `publish` flag in the frontmatter, allowing only content that is explicitly marked for publication to pass through. It's the opt-in version of [[docs/plugins/RemoveDrafts]]. See [[docs/features/private pages]] for more information.

> [!note]
> For information on how to add, remove or configure plugins, see the [[docs/configuration#Plugins\|Configuration]] page.

This plugin has no configuration options.

## API

- Category: Filter
- Function name: `Plugin.ExplicitPublish()`.
- Source: [`quartz/plugins/filters/explicit.ts`](https://github.com/jackyzha0/quartz/blob/v4/quartz/plugins/filters/explicit.ts).
