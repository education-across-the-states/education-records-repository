# The Education Records Repository

**The go to place for any issue having to do with education across the nation.**

The **Education Records Project** is a reporting project of **Education Across the States**, a national news organization. The project is produced by **Charles Mayfield, Producer, Education Across the States**.

We asked every state education agency in the United States — plus the District of Columbia and the five U.S. territories, **56 agencies in all** — for the same core records, under each jurisdiction's own public-records law: check registers and purchase orders, agency credit-card records, payroll listings, adopted budgets and budget-versus-actual reports, federal grant files (IDEA Part B allocations, U.S. Department of Education monitoring reports and corrective action plans, determination letters), state complaint and due-process hearing decisions, major vendor contracts, board minutes, and organizational charts. Everything produced is published here, in full, free — filed exactly as the agency produced it.

The same request to every agency, so the answers can be compared. That comparison — and the record of how each agency responded — is the collection.

## Start with the register

[**register.md**](register.md) is the index of the collection, in two parts:

1. **The Document Register** — every document held, the request that produced it, and the date it arrived. This is the citable index.
2. **The Request Register** — every request we have filed, agency by agency: what was asked, when, by what route, and where it stands — sent, awaiting a custodian's reply, portal filing pending, or held because no lawful route to file could be verified. Refusals, delays, and fee demands are logged here as part of the record.

A machine-readable copy of the Document Register is at [`register.csv`](register.csv); the Request Register is at [`requests.csv`](requests.csv).

**Cite as:** Education Records Project, Register ID ERP-[XX]-[seq], [document title], [agency] production of [date], Education Across the States. https://github.com/education-across-the-states/education-records-repository

## How the repository is organized

- One folder per jurisdiction (lowercase postal code: `nh/`, `tx/`, `dc/`, `pr/`, …). Inside, one subfolder per production, holding the documents **exactly as produced** — no edits, no re-typing, no "cleaned" versions — plus a `production-note.md` (date received, format, page count, any agency notes).
- [`requests/`](requests/) — the correspondence: request letters as sent and agency acknowledgments, denials, and fee demands. A refusal is part of the collection, and of the coverage.
- [`finding-aids/`](finding-aids/) — our own work product: indexes, cross-state tables, and analyses built from the productions. Analysis lives only here and is labeled as ours; it never alters a filed document.
- If an agency supplements or corrects a production, the corrected document is added as a new register entry linked to the original. The original is never silently replaced.
- Files larger than GitHub's 100 MB per-file limit are listed in the register with a "held — available on request" note until a compliant host is chosen. Nothing is silently absent.

## The fee protocol

Our standing rule on fees, applied in every jurisdiction:

- **Default position on any fee: NO.** No fee is paid or agreed on first demand. Every formal request asks up front for a public-interest / news-organization fee waiver, or a cost estimate before any charge is incurred.
- **A fee demand is challenged first, in writing.** Before any fee is decided, the agency must document it: the statutory basis for the charge, an itemized breakdown (per-page or per-hour; search time separated from duplication time; the rate and who performed the work), its written decision on the waiver request, and a showing that the amount is the actual, allowable cost of production — not a deterrent to access.
- **Only a documented fee is ever decided.** If, after that documentation, a fee is declined, the correspondence is filed in this repository and the refusal is part of the public record of the project.
- **Fee events are public.** Every fee demand, challenge, justification, and outcome is logged in the register alongside the productions — an agency's fee behavior is itself a documented fact about access in that jurisdiction.

As of October 25, 2026, no agency has demanded a fee on any request in this project.

## Access and licensing

- The records are **public records**. As records of government agencies they are not subject to our copyright, and we claim none. Anyone may use them for any purpose, with or without citing us — that is what public records are for.
- Our work product — the register, indexes, finding aids, cross-state tables, and project page text — is published for free use **with attribution** ("Education Records Project, Education Across the States"). Attribution is requested, and it is what makes the collection grow: citations are how researchers find the register.
- **For researchers and newsrooms:** a standing invitation to verified journalists and academics to use and cite this collection. No registration, no fee, no embargo, no exclusive access. If you publish from a production, citing the Register ID and linking the entry helps the next researcher find the document. Newsrooms planning work from a production are invited (not required) to tell us, so the project page can link the published work — a citation exchange, not a gate.

## The scoreboard

Requests, acknowledgments, productions, and refusals are tracked per jurisdiction on the project page: https://education-across-the-states.github.io/records-project.html — including the jurisdictions that are overdue.

**Status as of October 25, 2026:** requests sent to 33 of 56 agencies (25 formal requests + 8 custodian-first letters, all October 25, 2026); 15 agencies accept requests only through their own portals (filings in preparation); 8 held because no verified filing route exists yet — the gap for each is named in the Request Register.

## Contact

Charles Mayfield, Producer, Education Across the States
educationacrossthestates@gmail.com · (978) 291-8525
