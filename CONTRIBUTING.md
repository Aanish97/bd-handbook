# Contributing to the BD Handbook

This handbook is a living document. Anyone on the GrowthCode team is encouraged to
improve it.

## Two ways to edit

1. **In GitBook** (easiest) — edit the page in GitBook's editor; it commits back
   to this repo automatically via Git Sync.
2. **On GitHub** — edit the Markdown file directly, or open a pull request.

## Ground rules

* **This repo is public.** Never commit anything confidential: no customer names
  or lists, no unpublished pricing, no pipeline/revenue figures, no credentials.
  Use placeholders (`> **Fill in:** ...`) and link to the private source instead.
* **Keep the structure in sync.** If you add or move a page, update
  [`SUMMARY.md`](SUMMARY.md) — that file is the navigation tree GitBook renders.
* **One idea per change.** Small, focused edits are easier to review.
* **Write for a new hire.** Plain language, concrete examples, no unexplained
  jargon (add terms to the [Glossary](resources/glossary.md)).

## File layout

```
README.md                 Landing page
SUMMARY.md                Navigation tree (edit when adding/moving pages)
.gitbook.yaml             GitBook Git Sync config
getting-started/          Onboarding, tools
foundations/              What we sell, ICP, messaging
process/                  Sales stages, qualification, CRM
playbooks/                Outreach, discovery, objections
resources/                Templates, glossary, FAQ
```

## Review

An owner reviews changes for accuracy and for the "nothing confidential" rule
before they're merged / published.

> **Fill in:** Name the handbook owner(s) and where edits get discussed.
