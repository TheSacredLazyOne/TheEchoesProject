# Contributing Guide

Thanks for caring about the Relational Information Framework (RIF). This is a **living** project designed to be explored with a Silicon Intelligence (SI) co-pilot and improved through transparent contributions.

## Principles (Code of Conduct)
We hold the **Five Disciplines** as requirements, not aspirations:
**Humility • Invitation • Forkability • Examinability • Open Infrastructure**.  
If a proposal appears to conflict with these, explain why and how the conflict is resolved.

## How to Propose Changes
- **Small edits** (typos, broken links, minor clarifications): open a **Pull Request** directly.
- **Substantive changes** (new sections, philosophical or architectural shifts):
  1. Copy `patches/patch-template.md` to `patches/patch-<short-topic>-v1.0.md`
  2. Fill in motivation, exact diff text, and a review plan
  3. Open a PR including both the patch file and the proposed edits

> **Version history:** We do not maintain a manual changelog or tag walkthroughs. Use Git history (`git log`, `git blame`) and tags for lineage and diffs.

## Interaction Model (SI-first & Living Document)
While you can read the docs directly, the **Living Document interface** (SI co-pilot) will provide guided exploration, citations, and feedback routing.  
**Coming soon:** a public GPT-based co-pilot that mirrors this repository and exports feedback into patch templates.

## Review Process
- PRs remain open for **~2 weeks** for examination unless clearly trivial.
- The **human steward** is accountable for final merges; all reasoning must be documented in the PR.
- Disagree with a decision? **Fork** and continue exploration (federated alternatives are welcome).

## Critique → Contribution
Have a critique or deep review? Please open a **GitHub Discussion** (label: `critique`) for examination.  
If your critique implies a concrete change, convert it into a **patch** using `patches/patch-template.md` and open a PR that includes both the patch and the edits.

## Cultural Impact & Sovereignty Checks
Use this checklist for any change that might affect identifiable communities:
- Affected communities identified; liaisons/bridge agents engaged
- Consent pathways and data stewardship clarified; right to revoke respected
- Cultural continuity preserved; contexts/examination histories maintained
- Non-assimilation and exit/sovereignty preserved by design
- Co-design performed for impactful changes; remediation plan defined if harms are discovered

## Style & Structure
- **Paths:** flat under `docs/rif/` (Git handles releases via tags)
- **Links:** always **relative** (e.g., `[rif-introduction.md](rif-introduction.md)`)
- **Filenames:** prefer **hyphens** (`axioms-to-architecture.md`)
- **Licenses:** Docs → `CC BY-SA 4.0` (`LICENSE-DOCS.txt`); Code → `AGPL v3` (`LICENSE-CODE.txt`)
- **Tolkien note:** The full note lives in `rif-introduction.md`; use a one-line callout elsewhere:
  > The One Ring is *applicable* as a caution: any tool or creed that concentrates power to bend many wills into one—however noble its stated aim—corrupts by **replacing consent with control**. RIF’s answer is plural, federated, and forkable rather than single, central, and coercive.

## File Map (canonical entry points)
- **Start here:** [rif-introduction.md](rif-introduction.md)  
- **Formal derivation:** [axioms-to-architecture.md](axioms-to-architecture.md)  
- **Technical spec:** [rif-spec.md](rif-spec.md)  
- **Patches:** `patches/` (use `patch-template.md`)  
- **Reflections:** `reflections/` (submit sparingly; focus on transformation/Δψ)

## Submitting Reflections vs Critiques vs Patches
- **Reflections**: how understanding changed (process/topology), not just conclusions  
- **Critiques**: examination with reasons/evidence; start as a Discussion  
- **Patches**: concrete text changes to the canon (with exact insert/replace blocks)

---

*Thank you for helping RIF remain federated, examinable, and consent-based.*
