---
publish: true
permalink: /docs/features/Roam Research compatibility.md
title: Roam Research Compatibility
created: 2026-02-15T23:02:38.416+08:00
modified: 2026-02-15T23:02:38.416+08:00
tags:
  - feature/transformer
cssclasses: ""
---


[Roam Research](https://roamresearch.com) is a note-taking tool that organizes your knowledge graph in a unique and interconnected way.

Quartz supports transforming the special Markdown syntax from Roam Research (like `{{[[components]]}}` and other formatting) into
regular Markdown via the [[docs/plugins/RoamFlavoredMarkdown]] plugin.

```typescript title="quartz.config.ts"
plugins: {
  transformers: [
    // ...
    Plugin.RoamFlavoredMarkdown(),
    Plugin.ObsidianFlavoredMarkdown(),
    // ...
  ],
},
```

> [!warning]
> As seen above placement of `Plugin.RoamFlavoredMarkdown()` within `quartz.config.ts` is very important. It must come before `Plugin.ObsidianFlavoredMarkdown()`.

## Customization

This functionality is provided by the [[docs/plugins/RoamFlavoredMarkdown]] plugin. See the plugin page for customization options.
