# Antoine Moineaux

**I design and deploy internal systems that reduce manual work and improve operational reliability.**

Open to **subcontracting for automation agencies**. Remote, immediate availability.

Three and a half years in operations at a mobility operator (300+ vehicles and drivers), a year working in Australia, and since March 2026 independent: five systems delivered and deployed to production for three clients.

## What I actually do

Requests, documents and payments arrive by email and form. Someone reads them, judges them, looks them up in the CRM, types them in again. I build the chain that removes that step, and I leave the judgment where it belongs: a human approves before anything goes out.

## Two systems you can read, not just take my word for

### [opspilot-ai-lead-intake](https://github.com/AntoineMoineaux/opspilot-ai-lead-intake)

Inbound request to qualified CRM record in under two minutes instead of ten. The CRM is queried *before* any write, so duplicates are caught at the door rather than cleaned up for months. Around 70% of AI drafts go out unedited. **In production since June 2026.**

### [ai-financial-admin-automation](https://github.com/AntoineMoineaux/ai-financial-admin-automation)

Every payment linked to the document that proves it: 46 of 46, across 213 centralised documents. Nothing is ever guessed: when an amount cannot be identified, or when the model output is unusable, the record is still written, flagged for human review, with the reason. **In production since June 2026.**

## How I build

- **The CRM is queried before any write.** Cleaning duplicates afterwards is a battle you lose.
- **Nothing runs twice.** Re-running an operation cannot create a second record.
- **Nothing is guessed.** Ambiguous input goes to a review queue, never to the model.
- **Nothing runs by hand.** No human step per item: the chain is autonomous, documented and structured so someone else can pick it up.

## Stack

`n8n` `Claude API` `HubSpot CRM v3` `Airtable` `Google Workspace` `REST APIs` `webhooks` `JSON` `SQL` `Power BI`

## Also here

Earlier work from my data analytics phase: operational performance analysis for a mobility marketplace, recruitment analytics, product retention analysis. SQL and Power BI.

---

Paris · [Full portfolio with the case studies](https://antoine-ai-automation.notion.site/Antoine-Moineaux-AI-Automation-Portfolio-3b42170a9e698100b629c980fef070fc)
