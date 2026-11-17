# Discovery (Pre-Coding Gate)

Discovery validates the recurring evidence-workflow problem before any SaaS build.
Only synthetic examples and templates belong in this repository. Participant
identifiers, recordings, raw interview notes, customer documents, and consent
forms must remain outside git in the excluded `discovery/raw/` and
`discovery/consented-data/` directories.

## Recruitment target

| Group | Target | Purpose |
|---|---:|---|
| Small B2B suppliers | 6–8 | Confirm frequency, cost, rework, and tool gaps |
| CAs/accountants | 3 | Confirm evidence patterns and referral/payer potential |
| Buyer AP/procurement | 3 | Confirm actual requirements and rejection/acknowledgment causes |

## Phase gate

Do not proceed to SaaS implementation unless:

- at least 4 of 6–8 suppliers report repeated recent document/acceptance friction;
- at least 4 provide an anonymized example or reconstruct a concrete rework event;
- at least 3 quantify meaningful monthly time or rework;
- at least 3 demonstrate a material existing-tool gap; and
- at least 2 agree to a supervised paid-pilot commitment.

## Workflow

1. Recruit one participant group at a time.
2. Obtain explicit permission before recording or retaining evidence.
3. Use the relevant interview guide.
4. Create a redacted workflow record in `data-sheet.md`.
5. Walk through existing tools and calculate the affected process cost.
6. Run the concierge workflow on a consented redacted example.
7. Summarize evidence and contradictions in `decision-log.md`.
8. Schedule pilot terms only after the value and gap are demonstrated.

## Required source separation

Record the source of every conclusion:

- **supplier-reported**: stated by a supplier;
- **buyer-confirmed**: confirmed by buyer AP/procurement;
- **observed**: witnessed during walkthrough or concierge work;
- **documented**: supported by a redacted source artifact.
