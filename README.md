# Climate Litigation Tracker

A structured, searchable, and collaboratively maintained database of significant climate change litigation cases.

## Purpose

This repository serves as a central hub for tracking legal cases that attempt to hold fossil fuel companies and other corporate entities accountable for their contributions to climate change and related damages. As a journalist, policy analyst, or researcher, you can use this database to:

- Identify trends in legal arguments across jurisdictions
- Track the status of key cases (active, settled, dismissed, on appeal)
- Analyze which defendants are being targeted and under which legal theories
- Quickly reference case details for reporting or policy analysis

## Scope

The tracker focuses on litigation that seeks to assign liability for climate-related harms, including:

- **Tort claims** (public nuisance, negligence, failure to warn)
- **Securities fraud** cases related to climate risk disclosure
- **Constitutional law** cases asserting rights to a stable climate
- **Consumer protection** and **fraud** allegations

Both U.S. and international cases are included.

## How to Contribute

### 1. Adding a New Case

Each case is tracked as a GitHub **Issue**. To add a new case:

1. Go to the [Issues tab](https://github.com/tomaseshithari/climate-litigation-tracker/issues) and click "New Issue."
2. Use the following template in the issue body:

```
**Case Name:**
**Docket Number:**
**Court:**
**Filing Date:**
**Legal Theory:**
**Summary of Claim:** (2-3 sentence summary)
**Key Links:** (Link to court docket, major news coverage, or legal analysis)
```

3. Apply the appropriate **labels** (see below) to categorize the case.

### 2. Updating an Existing Case

If a case's status changes (e.g., dismissed, settled, appealed), edit the issue to reflect the new status and update the labels accordingly.

### 3. Suggesting Improvements

Open a **Pull Request** to propose changes to the repository's structure, documentation, or analysis files.

## Label Taxonomy

Labels are used to filter and analyze cases. They are organized into four groups:

### Status
- `active` – Case is currently being litigated
- `settled` – Case resolved through settlement
- `dismissed` – Case dismissed (with or without prejudice)
- `on-appeal` – Case under appellate review

### Legal Theory
- `public-nuisance` – Claim based on public nuisance doctrine
- `tort` – Traditional tort claims (negligence, strict liability)
- `securities-fraud` – Allegations of misleading investors about climate risks
- `failure-to-warn` – Failure to disclose climate-related risks to consumers or the public
- `constitutional` – Claims based on constitutional or human rights

### Defendant
- `exxonmobil` – ExxonMobil Corporation
- `shell` – Shell plc
- `chevron` – Chevron Corporation
- `bp` – BP p.l.c.
- `other-corporate` – Other corporate defendants (e.g., coal companies, utilities)
- `government-agency` – Government bodies as defendants

### Jurisdiction
- `us-federal` – U.S. federal courts
- `us-state` – U.S. state courts
- `international` – Courts outside the United States

## Analysis Files

Periodic analyses of the litigation landscape are maintained in the `analysis.md` file. Contributors are encouraged to update this file as new cases are added or significant developments occur.

## License

This project is licensed under the [MIT License](LICENSE).