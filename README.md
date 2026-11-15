# QualityDesk – Mini QMS Tracker

A small quality management system (QMS) tracker in the style of ISO 9001. I built it to learn how the main parts of a QMS fit together: non-conformances, corrective actions, internal audits, document control and the management review.

**Live demo:** ADD-YOUR-NETLIFY-LINK-HERE (opens instantly, no login, nothing to install)

## What it does

| Area | What you can do |
|---|---|
| **Dashboard** | See open non-conformances, overdue corrective actions, audit progress, documents due for review and CO2e totals. A management review summary is written from the live numbers. |
| **Non-conformances and CAPA** | Log a non-conformance, do a 5 Whys root cause analysis, record the corrective and preventive action, and verify that it worked. A record cannot be closed without a verification note. |
| **Internal audits** | Plan audits against ISO 9001 clauses, record findings (conformity, observation, minor NC, major NC) and raise a finding into the CAPA register with one click. |
| **Document control** | Keep a register of policies and procedures with version, owner, status and next review date. New revisions stay in draft until approved, and every document has a revision history. |
| **Carbon footprint** | Collect yearly activity data from data owners and group emissions by GHG Protocol scope 1, 2 and 3. |
| **Audit trail** | Every change is logged with its date and time. |
| **Export** | Each register exports to CSV, and the dashboard prints as a report. |

## How it works

- One file: `index.html` with plain HTML, CSS and JavaScript. No framework, no build step, no backend.
- Data is saved in the browser (localStorage). "Reset demo data" restores the sample data.
- Due dates in the sample data are set relative to today, so the demo always shows some overdue and upcoming items.

## Run it

Open `index.html` in a browser. To host it, upload the folder to Netlify or GitHub Pages.

## Honest notes

- This is a learning project, not a certified QMS and not a replacement for a real one.
- The emission factors in the carbon tab are example values. Real reporting needs official factors.
- All records in the demo are made-up sample data.
- Built with AI assistance (Claude). I checked the logic and tested each flow myself.
