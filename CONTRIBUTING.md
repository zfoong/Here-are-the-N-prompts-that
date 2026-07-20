# Contributing

Found another suspiciously powerful numbered prompt pack? You can suggest the post or add the complete pack yourself.

By contributing, you agree to follow the [data policy](DATA_POLICY.md), especially the **verbatim or reject** rule. Do not recreate, improve, sanitize, or fill in missing prompts.

## What qualifies

A submission should have all of the following:

1. A public source URL from X, Threads, Facebook, Instagram, Reddit, LinkedIn, or another publicly accessible platform.
2. A concrete number and an explicit prompt reveal, such as “Here are the 7 prompts,” “These 5 prompts,” or “I tested 10; here are the 3 that worked.”
3. The complete promised set of prompts available for verification.
4. Exact prompt wording and enough information to credit the author.
5. A reasonable basis to publish the prompt text, such as submitting your own post, author permission, or compatible licensing.

Do not submit private posts, login-bypassed material, engagement-gated prompts obtained through automated comments or DMs, incomplete packs, or a link that merely advertises prompts hosted elsewhere.

## Option 1: Suggest a post

Open a GitHub issue and include:

- the public post URL;
- the author or account handle;
- the number of prompts promised;
- where the complete prompts appear, such as the post, thread, comments, or carousel; and
- whether it is your post or you have permission to reproduce it.

Maintainers will verify the source, check for duplicates, and create the collection page if it qualifies.

## Option 2: Add a complete prompt pack

1. Fork the repository and create a branch.
2. Check the [catalog](CATALOG.md) and search existing `source_url` values to avoid duplicates.
3. Choose the most specific category from the list below.
4. Copy a nearby collection file from that category.
5. Name the new file `hnp-NNN-descriptive-slug.md`, using the next unused number. A maintainer may renumber it if another contribution claims the same ID.
6. Add the metadata, source link, and every verified prompt.
7. Open a pull request and include the original post URL and your publication basis.

Contributors do not need to edit `README.md` or `CATALOG.md`; maintainers regenerate those indexes from the collection files.

## Categories

Use exactly one category and its matching folder name:

| Category | Folder | Use it for |
| --- | --- | --- |
| Money Making | `money-making` | Side hustles, monetization, passive income, and digital products |
| Solopreneur | `solopreneur` | Freelancing, founders, small businesses, and solo operations |
| Growth | `growth` | Followers, reach, engagement, channels, and personal brands |
| Marketing | `marketing` | Ads, email, SEO, sales, leads, and market research |
| Content Creation | `content-creation` | Writing, editing, scripts, presentations, and publishing |
| Design | `design` | Images, photography, logos, Canva, and visual direction |
| Career | `career` | Resumes, job searches, applications, and interviews |
| Productivity | `productivity` | Planning, automation, meetings, schedules, and assistants |
| Learning | `learning` | Studying, teaching, languages, explanations, and research |
| Money Management | `money-management` | Budgeting, investing, stocks, finance, and retirement |
| Travel | `travel` | Flights, hotels, itineraries, rewards, and travel planning |
| Life Admin | `life-admin` | Shopping, gifts, holidays, and everyday decisions |
| Personal Growth | `personal-growth` | Reflection, relationships, journaling, wellness, and habits |
| Prompting | `prompting` | Meta-prompts, prompt generators, and model behavior |

If two categories seem plausible, choose the one that best describes the main outcome of the complete pack.

## Collection file format

Create the file under `collections/<category>/` using this structure:

````markdown
---
title: "The source post title"
domain: solopreneur
source_url: "https://www.threads.com/@example/post/example"
platform: threads
author: "@example"
---

# The source post title

[← All prompt packs](../../CATALOG.md) · **Solopreneur** · [Original post ↗](https://www.threads.com/@example/post/example)

## Prompts

Copy a prompt and replace the bracketed text with your own context.

### 1. Descriptive prompt name

```text
[PASTE THE VERIFIED PROMPT HERE WITHOUT REWRITING IT]
```
````

Use lowercase platform values such as `facebook`, `linkedin`, `reddit`, `threads`, or `x`. Add each prompt as a numbered `###` heading followed by a `text` code block. The number of prompt blocks must equal the number promised by the source.

Do not add a separate `## Source` section. The `source_url` field and **Original post** link already provide attribution.

See [COLLECTION_FORMAT.md](COLLECTION_FORMAT.md) for the canonical format.

## Pull request checklist

- [ ] The post belongs to the numbered prompt-pack family.
- [ ] The source is public and directly linked.
- [ ] The author or account is credited.
- [ ] Every promised prompt is present and copied verbatim.
- [ ] No missing text was invented or reconstructed.
- [ ] The source is not already represented in the catalog.
- [ ] The category, folder, `domain`, and visible category label agree.
- [ ] The pull request explains why the prompt text may be published.

## Corrections and removals

For incorrect wording, attribution problems, duplicates, or removal requests, open an issue with the collection ID, source URL, requested action, and whether you are the author or rights holder.

