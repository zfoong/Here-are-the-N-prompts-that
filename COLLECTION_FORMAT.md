# Collection format

One social post becomes one small Markdown file:

```text
collections/<category>/<id>-<descriptive-slug>.md
```

The file contains only what someone needs to find and use the prompts. Prompt text must match the verified source; a rewritten approximation does not qualify.

## No-rewrite rule

- Copy the prompt exactly as it appeared in the source.
- Only change presentation, such as wrapping the unchanged text in a code block.
- Do not fix, parameterize, translate, improve, or recreate it.
- If exact text or the complete `N`-prompt payload cannot be verified and published, discard the candidate.

## Template

````markdown
---
title: "Here are the 5 prompts that did something improbable"
domain: solopreneur
source_url: "https://www.threads.com/@example/post/example"
platform: threads
author: "@example"
---

# 💼 Here are the 5 prompts that did something improbable

[← All prompt packs](../../CATALOG.md) · **Solopreneur** · [Original post ↗](https://www.threads.com/@example/post/example)

## Prompts

Copy a prompt and replace every `[BRACKETED_VARIABLE]` with your own context.

### 1. A clear prompt title

```text
[PASTE THE VERIFIED PROMPT HERE WITHOUT REWRITING IT]
```
````

That is the complete format: five short metadata fields, an original-post link near the title, and numbered prompt blocks. The ID comes from the filename, and the prompt count comes from the blocks, so neither needs another field.

## Add or edit a pack

1. Copy a nearby file from the appropriate category.
2. Assign the next unused `hnp-NNN` filename and replace all five metadata values.
3. Add each verified prompt verbatim as a numbered `###` heading followed by a `text` code block.
4. Submit the new collection file; maintainers will refresh the indexes.

`README.md` and `CATALOG.md` are maintained from the collection files, so contributors only need to work on the prompt-pack page itself.
