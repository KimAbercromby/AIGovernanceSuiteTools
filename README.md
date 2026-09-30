# AI Governance Suite Tools

Interactive navigation tools for the 52-artefact AI governance suite (v3.9.1, 30 September 2026: Playbook v19.9.11, README/Index v1.26). Draft for Council review.

These tools approve nothing. The AI Governance Lead confirms every route and tier, and every decision sits with the delegated decision-maker named in the suite.

## The tools

| Page | What it does |
|---|---|
| `index.html` | Landing page linking the three tools. |
| `suite-map.html` | All 52 artefacts and the UC-ID current view, arranged by lifecycle stage with the AI Register as the spine. Select an artefact to see what feeds it and what it triggers, trace a route, or **view as a role** to see what that role does, decides and contributes to. |
| `flow-builder.html` | Start from a scenario or any artefact and open the next steps one at a time, with the conditions that decide each one. **Role chips** show who does each step; highlight a role to see where it is involved. |
| `route-finder.html` | Answer the suite's own screening questions and see only your case's route, by role, with a handover checklist for each stage. |
| `docs/` | One PDF per artefact, opened from the tools. Workbooks open as a heading summary; the Excel files hold the formulas and dropdowns. |

Everything is plain HTML with no build step. Open `index.html` in a browser, or serve the folder with GitHub Pages (Settings > Pages > Deploy from a branch > main, / (root)).

## Roles are a pilot design

The role view comes from the draft role table (`AIG_Role_Table_pilot_2026-09-29.xlsx`, kept outside this repo), checked against the v3.9 suite on 30 September 2026. Positions that v3.9 now settles are marked as settled, with their source. It is **not adopted**.

- Where the suite's own text names who does, decides or contributes, the tools show that.
- Where the suite is silent, the tools show a proposed pilot position, marked **?**.
- Where two documents disagree, the tools show a proposed pilot position, marked **!**, and name the conflict to be decided.

These stay pilot positions until the Council confirms its own delegations, owners and operating practice. The role data is embedded in `suite-map.html` and `flow-builder.html` as `ROLEDATA` and is regenerated from the role table when it changes.

## Visibility

This repository is private while the suite and the role design are in draft.
