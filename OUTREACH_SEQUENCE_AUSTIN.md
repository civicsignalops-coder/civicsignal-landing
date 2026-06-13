# CivicSignal — Cold Outreach Sequence: Austin ZPC Campaign

---

## Campaign Overview

| Parameter | Value |
|---|---|
| **Target Market** | Austin-based commercial developers, civil engineers, land-use attorneys |
| **Lead Source** | `austin_b2b_leads.csv` (59 verified firms) |
| **Sequence Length** | 3 emails over 7 days |
| **Personalization Tokens** | `{{Company Name}}`, `{{First Name}}`, `{{District}}`, `{{Live Link}}` |
| **Sending Cadence** | Day 1 → Day 4 → Day 7 |
| **Goal** | Drive signups to early-access intelligence feed |

---

## Merge Token Reference

These tokens map directly to the fields in our generated lead CSV and intelligence report:

| Token | Source | Example |
|---|---|---|
| `{{Company Name}}` | `austin_b2b_leads.csv` → `company_name` | Endeavor Real Estate Group |
| `{{First Name}}` | Manual enrichment or LinkedIn | David |
| `{{District}}` | Intelligence report → nearest district to firm's projects | District 5 |
| `{{Live Link}}` | Landing page URL | https://civicsignalops-coder.github.io/civicsignal-landing/ |

---

## Email 1: The Direct Value Drop

**Send:** Day 1
**Word Count Target:** Under 150 words

---

### Subject Line Options

> **Option A:** Austin ZPC: District 5 & 10 variances (June 2026)
>
> **Option B:** Quick question regarding Austin zoning pipeline

---

### Body

Hi {{First Name}},

We isolated something from last week's Zoning & Platting Commission session that may be relevant to {{Company Name}}.

The June 2026 ZPC cycle shows concentrated zoning change activity in **{{District}}** — specifically, multiple C14 variance requests along the IH-35 corridor and a conditional use permit at 4109 Marathon Blvd. These staff reports were published to the city's EDIMS portal but haven't surfaced on any mainstream aggregation platform yet.

We compiled the full case feed — case numbers, district maps, and direct links to every official staff evaluation — into a structured briefing.

Two options:

1. I can send the full report directly.
2. You can grab it here: [{{Live Link}}]({{Live Link}})

Either way, no cost. We're validating whether this type of structured municipal feed is useful for teams like yours.

Best,
CivicSignal Research

---

**Word count:** 143

---

## Email 2: The Logic Follow-Up

**Send:** Day 4 (if no reply)
**Word Count Target:** Under 100 words

---

### Subject Line

> **Re: Austin zoning pipeline**

---

### Body

Hi {{First Name}},

Following up briefly. The reason we built this: most land teams we've spoken with spend 5–10 hours per week manually digging through the city's EDIMS portal — clicking through unstructured PDFs, cross-referencing case numbers, and hoping they haven't missed a filing.

We automate that entire workflow and deliver a verified weekly feed with direct source links to every official document.

If {{Company Name}} tracks Austin zoning activity at all, this will save your team real hours. Happy to send the June dataset over — just say the word.

Best,
CivicSignal Research

---

**Word count:** 96

---

## Email 3: The Scarcity / Closing Call

**Send:** Day 7 (if no reply)
**Word Count Target:** Under 80 words

---

### Subject Line

> **Closing out June Austin ZPC data feed**

---

### Body

Hi {{First Name}},

Last note on this. We're closing out the June 2026 Austin ZPC intelligence cycle and building the July distribution list now.

Quick question: should I keep {{Company Name}} on the early-access list for the next data drop, or is municipal zoning monitoring currently handled fully in-house?

Either way — no hard feelings. Just want to make sure we're sending this to teams that actually use it.

Best,
CivicSignal Research

---

**Word count:** 73

---

## Sending Notes

**Do NOT send from a personal email.** Use a dedicated outreach address (e.g., `research@civicsignal.io` or a domain-matched alias) to maintain the Faceless Rule.

**Recommended tools (all free tier):**

| Tool | Purpose | Free Tier |
|---|---|---|
| Gmail alias | Sending | Free |
| Mailmeteor | Mail merge from Google Sheets | 50 emails/day free |
| Hunter.io | Email verification | 25 verifications/month free |

**Compliance:**

- Include an unsubscribe line in production sends.
- Do not misrepresent the sender identity.
- All data referenced is public domain municipal records.

---

*Document generated: June 2026 | CivicSignal Outreach Operations*
