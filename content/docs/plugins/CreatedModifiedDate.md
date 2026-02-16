---
publish: true
permalink: /docs/plugins/CreatedModifiedDate.md
title: CreatedModifiedDate
created: 2026-02-15T23:02:38.427+08:00
modified: 2026-02-15T23:02:38.427+08:00
tags:
  - plugin/transformer
cssclasses: ""
---


This plugin determines the created, modified, and published dates for a document using three potential data sources: frontmatter metadata, Git history, and the filesystem. See [[docs/authoring content#Syntax]] for more information.

> [!note]
> For information on how to add, remove or configure plugins, see the [[docs/configuration#Plugins\|Configuration]] page.

This plugin accepts the following configuration options:

- `priority`: The data sources to consult for date information. Highest priority first. Possible values are `"frontmatter"`, `"git"`, and `"filesystem"`. Defaults to `["frontmatter", "git", "filesystem"]`.

When loading the frontmatter, the value of [[docs/plugins/Frontmatter#List]] is used.

> [!warning]
> If you rely on `git` for dates, make sure `defaultDateType` is set to `modified` in `quartz.config.ts`.
>
> Depending on how you [[docs/hosting\|host]] your Quartz, the `filesystem` dates of your local files may not match the final dates. In these cases, it may be better to use `git` or `frontmatter` to guarantee correct dates.

## API

- Category: Transformer
- Function name: `Plugin.CreatedModifiedDate()`.
- Source: [`quartz/plugins/transformers/lastmod.ts`](https://github.com/jackyzha0/quartz/blob/v4/quartz/plugins/transformers/lastmod.ts).
