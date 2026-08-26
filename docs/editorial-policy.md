# Editorial policy

The rules this repository is built and maintained by. The README's
"How tools are selected" section is the short version; this is the full one.

## Scope

Tools a developer uses while building software. The test applied to every candidate was whether it plugs into a real development workflow: an editor, a terminal, a pull request, a CI pipeline, or a running system.

That is a narrower question than "could a developer find this useful", and the narrowness is the point. A general chat assistant can write a regular expression, and so it turns up on every developer list ever written, which is precisely why those lists stop being useful. It is not here unless it ships something development-specific.

This is the build-time slice of the TiorAI portfolio. `awesome-ai-tools` covers the general landscape, `awesome-ai-agents` covers agent frameworks and infrastructure including the developer-facing ones, and this repository covers the working day of someone writing code.

## What qualifies

- A developer uses it while building, testing, shipping, or operating software.
- It fits into an existing workflow: an editor, a terminal, a pull request, or a pipeline.
- Its value comes from a model doing something a rule-based tool could not.
- There is enough public information to describe it accurately.
- It covers something the entries already in that category do not.

## What does not

- General-purpose assistants with no development-specific integration.
- Writing, design, and marketing tools that happen to be usable by developers.
- Model providers and hosted inference, unless the product is aimed at development work.
- No-code app builders aimed at people who are not writing software.
- Broken, parked, or login-walled sites with no public information.
- Products that have shut down or been folded into something else.
- Affiliate landing pages, coupon sites, and lead-capture funnels.
- Near-identical clones with no meaningful difference from something already listed.
- Anything whose main activity is clearly illegal, and NSFW-focused products.
- Anything submitted purely as a promotional exercise.

## Descriptions

One sentence, 8 to 25 words, 35 at the absolute maximum, ending in a full stop. Written for
this repository rather than adapted from a vendor's homepage, and rewritten if a neighbouring
entry could swap places with it unnoticed.

Banned outright: superlatives (*best*, *leading*, *revolutionary*, *cutting-edge*,
*game-changing*, *world-class*, *ultimate*, *powerful*, *seamless*, *unleash*), `AI-powered`
as an opening, unverifiable claims about users, funding, or awards, and the em dash inside a
description, which is reserved as the entry separator so the format stays machine-parseable.

## Metadata vocabularies

Closed sets. A term outside them is a defect, not a judgement call.

**Pricing** — at least one, at most two, in this order:
`Free` · `Freemium` · `Paid` · `Open Source` · `Free Trial`

`Open Source` means an OSI-approved licence. Source-available products do not get the label;
the description says "source-available" instead. `Free Trial` never appears alone.

**Platform** — zero to six, in this order:
`Web` · `Windows` · `macOS` · `Linux` · `iOS` · `Android` · `API` · `CLI` ·
`Browser Extension` · `VS Code` · `JetBrains` · `Discord`

Applied only where verified. A wrong label is worse than a missing one.



## Ordering

Alphabetical within a category, ignoring punctuation and a leading "The". Position carries no
meaning and there is no paid placement.

Between categories, the order is editorial, by expected reader interest. That ranks topics,
never products.

## Categories

Minimum 4 entries, 8 is the working target, roughly 15 is the ceiling. A category that cannot
reach 8 strong entries is merged or dropped rather than padded. No subcategories.

The taxonomy is revisited when a category drops below 6 entries, passes 15, or starts
receiving the same submissions as its neighbour.

## Links

The primary link is the resource's own official site: canonical, HTTPS, no tracking
parameters, no affiliate parameters, no shortener, no directory listing, no review page.

TiorAI links are capped: at most 25% of entries carry one, all distinct, at most three per
category, maintainer-placed only. Contributors are asked not to add them.

## Removal

An entry is removed when the product shuts down, the domain is taken over or starts serving
something harmful, the listing turns out to be misleading, or the entry no longer meets the
scope above. Removals are recorded in [CHANGELOG.md](../CHANGELOG.md). An entry removed for
a safety reason goes through review again rather than being quietly restored.
