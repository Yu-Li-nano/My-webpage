---
publish: true
permalink: /docs/index.md
title: Welcome to Quartz 4
created: 2026-02-15T23:02:38.426+08:00
modified: 2026-02-15T23:02:38.426+08:00
cssclasses: ""
---


Quartz is a fast, batteries-included static-site generator that transforms Markdown content into fully functional websites. Thousands of students, developers, and teachers are [[docs/showcase\|already using Quartz]] to publish personal notes, websites, and [digital gardens](https://jzhao.xyz/posts/networked-thought) to the web.

## 🪴 Get Started

Quartz requires **at least [Node](https://nodejs.org/) v22** and `npm` v10.9.2 to function correctly. Ensure you have this installed on your machine before continuing.

Then, in your terminal of choice, enter the following commands line by line:

```shell
git clone https://github.com/jackyzha0/quartz.git
cd quartz
npm i
npx quartz create
```

This will guide you through initializing your Quartz with content. Once you've done so, see how to:

1. [[docs/authoring content\|Writing content]] in Quartz
2. [[docs/configuration\|Configure]] Quartz's behaviour
3. Change Quartz's [[docs/layout]]
4. [[docs/build\|Build and preview]] Quartz
5. Sync your changes with [[docs/setting up your GitHub repository\|GitHub]]
6. [[docs/hosting\|Host]] Quartz online

If you prefer instructions in a video format you can try following Nicole van der Hoeven's
[video guide on how to set up Quartz!](https://www.youtube.com/watch?v=6s6DT1yN4dw&t=227s)

## 🔧 Features

- [[docs/features/Obsidian compatibility]], [[docs/features/full-text search]], [[docs/features/graph view]], [[docs/features/wikilinks\|wikilinks, transclusions]], [[docs/features/backlinks]], [[docs/features/Latex\|Latex]], [[docs/features/syntax highlighting]], [[docs/features/popover previews]], [[docs/features/Docker Support]], [[docs/features/i18n\|internationalization]], [[docs/features/comments]] and [many more](./features/) right out of the box
- Hot-reload on configuration edits and incremental rebuilds for content edits
- Simple JSX layouts and [[docs/advanced/creating components\|page components]]
- [[docs/features/SPA Routing\|Ridiculously fast page loads]] and tiny bundle sizes
- Fully-customizable parsing, filtering, and page generation through [[docs/advanced/making plugins\|plugins]]

For a comprehensive list of features, visit the [features page](./features/). You can read more about the _why_ behind these features on the [[docs/philosophy]] page and a technical overview on the [[docs/advanced/architecture]] page.

### 🚧 Troubleshooting + Updating

Having trouble with Quartz? Try searching for your issue using the search feature. If you haven't already, [[docs/upgrading\|upgrade]] to the newest version of Quartz to see if this fixes your issue.

If you're still having trouble, feel free to [submit an issue](https://github.com/jackyzha0/quartz/issues) if you feel you found a bug or ask for help in our [Discord Community](https://discord.gg/cRFFHYye7t).
