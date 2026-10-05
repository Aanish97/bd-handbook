# CRM Conventions

The CRM is our single source of truth. Consistent data in means reliable
forecasts and clean handoffs out. These conventions are not optional.

> **Fill in:** Replace generic names with our actual CRM and its field/stage
> names.

## The golden rules

1. **Log it the day it happens.** Calls, emails, meetings, next steps.
2. **One record per company and per person.** Check for duplicates before
   creating.
3. **Every open deal has a future-dated next step.** No next step = stalled deal.
4. **Stage reflects reality,** not hope. See [Sales Process](sales-process.md).

## Required fields by stage

A deal can't advance until the fields for its stage are complete.

| Stage | Required fields |
| ----- | --------------- |
| Engaged | Source, persona, next step |
| Discovery | Pain, metric, champion |
| Qualified | Full [MEDDICC](qualification.md), close date, amount |
| Proposal | Proposal link, success criteria, decision process |
| Negotiation | Procurement status, redlines, signature date |

## Naming & hygiene

> **Fill in:** Our conventions for deal names, amounts (ARR vs TCV), close-date
> discipline, and how we log lost reasons (use a fixed picklist so we can learn
> from losses).

* **Deal name format:** _e.g._ `[Company] – [Product] – [Term]`
* **Amount:** _ARR or TCV? — TBD_
* **Close date:** the realistic date, updated as it changes — never left in the
  past.
* **Lost reason:** always pick from the list; never leave blank.

## What never goes in a public doc

This handbook is public. The CRM is private and stays that way. Never copy
customer names, contact details, pricing, or pipeline numbers into this repo.
