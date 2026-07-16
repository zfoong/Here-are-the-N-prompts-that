# Collection format

One social post becomes one small Markdown file:

```text
collections/<domain>/<id>-<descriptive-slug>.md
```

The file contains only what someone needs to find and use the prompts.

## Template

````markdown
---
title: "Here are the 5 prompts that did something improbable"
domain: business
source_url: "https://www.threads.com/@example/post/example"
platform: threads
author: "@example"
---

# 💼 Here are the 5 prompts that did something improbable

[← All prompt packs](../../CATALOG.md) · **Business** · [Original post ↗](https://www.threads.com/@example/post/example)

## Prompts

Copy a prompt and replace every `[BRACKETED_VARIABLE]` with your own context.

### 1. A clear prompt title

```text
Perform [TASK] for [AUDIENCE] using [CONTEXT]. Return [OUTPUT_FORMAT].
```

## Source

Distilled from [@example on Threads](https://www.threads.com/@example/post/example).
````

That is the complete format: five short metadata fields, numbered prompt blocks, and a source link. The ID comes from the filename, and the prompt count comes from the blocks, so neither needs another field.

## Add or edit a pack

1. Copy a nearby file from the appropriate domain.
2. Assign the next unused `hnp-NNN` filename and replace all five metadata values.
3. Add each prompt as a numbered `###` heading followed by a `text` code block.
4. Submit the new collection file; maintainers will refresh the indexes.

`README.md` and `CATALOG.md` are maintained from the collection files, so contributors only need to work on the prompt-pack page itself.
