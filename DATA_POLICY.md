# Data policy

This repository is intended to record the prompts that actually circulated in public “Here are the N prompts…” posts. It preserves verified prompt wording and keeps a direct source link; it does not silently improve, parameterize, summarize, or reconstruct prompts.

## What is collected

A normal entry must contain:

1. a concrete count;
2. an explicit promise of prompts or prompt templates; and
3. a reveal construction such as “Here are 7 prompts,” “These 10 prompts,” or “I tested 20; here are the 3 that worked.”

The public record stores only the source URL, credited author or handle, short title, primary category, and verified prompt text.

Maintainers check that a candidate has the promised prompt payload before publishing it. A source link does not verify the author’s performance claims.

## What is not collected

- Private, friends-only, deleted, or login-bypassed material.
- Passwords, tokens, account data, or private messages.
- Engagement-gated payloads obtained by automated comments, follows, reposts, or DMs.
- Raw platform responses, full screenshots, or bulk copies of social posts in the public repository.
- Volatile likes, views, and follower counts as timeless facts.
- Personal data that is not needed for attribution.

This project does not use the collection to train a model.

## Verbatim or reject

The default rule is: **do not rewrite the prompt**.

- Preserve the prompt’s words, order, examples, placeholders, and mistakes as they appeared in the verified source.
- Formatting-only changes such as Markdown code fences or line breaks are allowed when they do not change the text.
- Do not parameterize, clarify, shorten, expand, translate, sanitize, or reconstruct a prompt for publication.
- If the exact prompt cannot be verified, is incomplete or engagement-gated, requires substantive redaction, or cannot be published responsibly, reject the prompt or the entire post instead of inventing a replacement.
- If one of the promised `N` prompts is missing, do not fill the gap. Reject the pack until the complete payload can be verified.

An exception requires a real preservation need and must never change meaning. When in doubt, discard rather than rewrite.

The MIT license covers repository-authored code and documentation. It does not relicense third-party posts. Source authors retain their rights. Links and attribution must remain attached to every entry.

Publish a full prompt pack only when there is a reasonable basis to do so, such as author submission, permission, compatible licensing, or a case-specific determination that the functional text may be reproduced. Otherwise reject it; rewriting is not the fallback.

### Existing first batch

The initial 30-pack batch contains transformed templates created before this rule was adopted. Those files are candidates for re-sourcing, not archival transcriptions. Each must be replaced with verified original prompt text or removed.

## Claims and high-risk prompts

Money, growth, replacement, and time-saving statements in source titles are claims made by the source, not verified results or endorsements.

Finance, investment, travel, legal, medical, employment, and other consequential prompts are not rewritten to make them safer. Reject unsafe or unsuitable material instead. Users should verify current facts with authoritative sources and seek qualified help when appropriate.

## Corrections, removal, and recirculation

Open a repository issue and include:

- the collection ID and source URL;
- the requested correction or removal;
- whether you are the author or rights holder; and
- enough information to evaluate the request.

Maintainers should correct attribution and factual metadata promptly. A removed item should keep a non-content tombstone ID so automated discovery does not silently add it again.

Obvious reposts do not count as new collections. One canonical entry may later list multiple public occurrences so the repository can show how prompt packs recirculate without inflating its totals.

## Acquisition rules

Prefer voluntary URL submissions, normal browsing, public search results, and official platform APIs that permit the intended use. Never bypass authentication, privacy settings, rate limits, robots controls, or platform safety mechanisms. Automated discovery may nominate candidates; a human must verify the family match, complete prompt payload, exact wording, attribution, and publication basis before publication.

This policy is a conservative editorial practice, not legal advice.
