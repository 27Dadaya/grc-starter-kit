# grc-starter-kit
A beginner-friendly starter project for **Governance, Risk, and Compliance (GRC)**: a ready-to-use Excel workbook, blank and example CSV templates, and a plain-language guide that explains every column.

It follows the order a real GRC review happens in:

```
Risk Register  ──▶  Control Assessment  ──▶  Corrective Action Plan (CAP) Tracker
"What could go      "Does the safeguard       "What is the fix, and how
 wrong, and how      actually work?"           do we know it worked?"
 bad is it?"
```

> Based on the *Cyber Compliance Academy, GRC Practice Templates* guide.

## Who this is for

- Students and career-changers practicing GRC for the first time
- Small teams starting a lightweight risk program
- Instructors who need ready-made practice templates

## Quick start

1. Open [`workbook/GRC-Starter-Workbook.xlsx`](workbook/GRC-Starter-Workbook.xlsx) in Excel, Google Sheets, or LibreOffice.
2. Read the **Start Here** sheet (2 minutes).
3. Work through the [Guided Walkthrough](docs/02-guided-walkthrough.md) to build your first risk row.
4. Move on to the Control Assessment, then the CAP Tracker.

## What is in the workbook

| Sheet | Purpose |
|-------|---------|
| **Start Here** | Instructions, color legend, and documented assumptions |
| **Risk Register** | 50 pre-built rows with dropdowns, 1-5 score validation, and auto-calculated inherent and residual scores and levels |
| **Control Assessment** | Dropdowns for method, implementation status, and effectiveness; flags rows that need remediation actions |
| **CAP Tracker** | Severity and status dropdowns, color coding, and an automatic overdue flag |
| **Dashboard** | 5x5 risk heat map plus counts of risks, controls, and corrective actions |
| **Reference** | Dropdown lists, scoring scales, and editable risk-level thresholds |

Row 2 of each sheet holds the guide's worked example. Overwrite it with your own data.

## Documentation

| # | Document | What it covers |
|---|----------|----------------|
| 1 | [Key Terms](docs/01-key-terms.md) | GRC vocabulary: risk, threat, residual risk, root cause, and more |
| 2 | [Guided Walkthrough](docs/02-guided-walkthrough.md) | Build your first risk register row, with a knowledge check |
| 3 | [Risk Register](docs/03-risk-register.md) | Column-by-column guide and worked example |
| 4 | [Control Assessment](docs/04-control-assessment.md) | Column-by-column guide and worked example |
| 5 | [CAP Tracker](docs/05-cap-tracker.md) | Column-by-column guide and worked example |
| 6 | [Cheat Sheet and FAQ](docs/06-cheat-sheet-and-faq.md) | Quick reference and common questions |
| 7 | [Scoring Methodology](docs/07-scoring-methodology.md) | Scales, score matrix, level thresholds, response strategies |
| 8 | [What to Write in Each Column](docs/08-what-to-write.md) | Fill-in guide with sentence starters and examples for all three templates |

## Repository structure

```
.
├── README.md
├── CHANGELOG.md
├── CONTRIBUTING.md
├── workbook/
│   └── GRC-Starter-Workbook.xlsx     # the main deliverable
├── templates/csv/                    # blank CSV templates (headers only)
├── examples/                         # CSVs with the worked examples
├── docs/                             # the guide, one Markdown file per topic
└── .github/                          # issue and pull request templates
```

## Where to go next

Once the basics feel comfortable, these widely used frameworks are good next reads: NIST Risk Management Framework (RMF), NIST SP 800-30 (risk assessments), NIST SP 800-53 (security and privacy controls; the guide's `AC-2` example comes from this catalog), ISO/IEC 27001 and 27005, and SOC 2.

## Contributing

Corrections and improvements are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

No license has been chosen yet. Add a `LICENSE` file before publishing, and confirm you have the right to redistribute the source guide's content.
