# Chamber SWLA Business Directory: Enriched Spreadsheet Edition

This repository contains an enriched spreadsheet version of the **Chamber Southwest Louisiana A-Z Business Directory Summary**.

The original PDF summary was created by **Brandon LaVan** and is included as the source reference for this project. The PDF is original/source material that was not created by this repository owner.

This version builds from that original PDF and converts the information into a more usable spreadsheet format for research, review, enrichment, and collaboration.

## Project Purpose

The goal of this project is to make the Chamber Southwest Louisiana business directory data easier to:

* Search
* Sort
* Review
* Enrich
* Validate
* Use for business research
* Improve through collaboration

The original PDF is useful as a static reference document. The spreadsheet version is intended to make the same general information more workable for practical use.

## Source Material

The original PDF was derived from the public Chamber Southwest Louisiana business directory and A-Z member pages.

Primary source base:

* Chamber Southwest Louisiana Business Directory
* A-Z member pages from the public Chamber directory

The original PDF notes that the Chamber public directory showed **1,131 total A-Z results** and that the PDF included **1,074 extracted member names** with short business summaries from accessible public page text and conservative category inference.

Some directory pages did not expose every result cleanly in the available text, so this project should be treated as a working lead and research file, not as an official or certified export.

## Credit

Original PDF summary prepared for:

**Brandon LaVan**

This repository is an enrichment and spreadsheet-conversion project derived from that original PDF.

All credit for the original PDF compilation belongs to Brandon LaVan. Any added spreadsheet formatting, enrichment, cleanup, categorization, validation notes, or additional research should be treated as later project work layered on top of the original source document.

See [NOTICE.md](NOTICE.md) for source and attribution notes.

## Repository Structure

```text
chamber-swla-business-directory-enriched/
|
|-- README.md
|-- NOTICE.md
|-- original/
|   |-- README.md
|   `-- Chamber_SWLA_a_z_business_directory_summary (1).pdf
|
|-- working-files/
|   |-- README.md
|   `-- chamber_swla_pdf_base_plus_enrichment.xlsx
|
|-- export/
|   |-- README.md
|   `-- chamber_swla_pdf_base_plus_enrichment.csv
|
`-- notes/
    `-- changelog.md
```

## Files

### `/original`

Contains the original PDF reference document. The PDF is source/reference material and was not created by this repository owner.

### `/working-files`

Contains the enriched spreadsheet version of the directory.

### `/export`

Contains CSV or text-based exports. These are useful because GitHub can compare CSV changes more easily than Excel files.

### `/notes`

Contains project notes, changelogs, verification notes, and future cleanup plans.

## Current Dataset Snapshot

The initial CSV/XLSX working dataset contains 1,074 business rows, with 88 rows marked as enriched and 986 rows retained from the original PDF without appended enrichment data.

## Important Verification Note

This project should not be treated as a fully verified business database.

Some records may be incomplete, outdated, inferred, duplicated, miscategorized, or missing details from the public Chamber profile. High-value records should be verified directly through:

* The Chamber member profile
* The business website
* Official public records
* Direct business contact
* Current Chamber directory listings

In plain English: this is a useful working dataset, not a court-certified export.

## Suggested Verification Searches

The original PDF recommended using targeted searches to verify thin or incomplete summaries. Examples include:

```text
site:events.allianceswla.org/list/member "BUSINESS NAME"
"BUSINESS NAME" "Chamber Southwest Louisiana"
"BUSINESS NAME" "Lake Charles" "LA"
"BUSINESS NAME" (services OR about OR contact)
site:BUSINESSDOMAIN.com (about OR services OR contact)
```

## How to Contribute

Contributions are welcome if they improve accuracy, completeness, formatting, or usefulness.

Good contributions include:

* Correcting business names
* Adding missing websites
* Adding verified phone numbers
* Adding verified emails
* Improving business categories
* Correcting inaccurate summaries
* Flagging duplicates
* Adding source links
* Adding notes for records that need manual review

## Contribution Rules

Please do not guess.

If you add or change information, include a source whenever possible.

Preferred source types:

* Official business website
* Chamber profile page
* Government or public record source
* Verified business directory profile
* Directly confirmed business information

## Recommended Workflow

For simple corrections, open an Issue.

For direct file changes, submit a Pull Request and explain:

* What changed
* Why it changed
* What source was used
* Whether the change affects only one record or multiple records

## Disclaimer

This is an independent enrichment and collaboration project based on a publicly derived directory summary.

This repository is not presented as an official Chamber Southwest Louisiana publication, official Chamber database, or certified export.

Always verify important business information before using it for outreach, research, marketing, reporting, or decision-making.

## Licensing And Reuse

The derived spreadsheet cleanup, formatting, enrichment notes, and repository documentation may be reused under CC BY 4.0 where legally permitted.

The original PDF source reference was not created by this repository owner and retains its own source/creator attribution. Do not treat this repository as granting new rights to third-party source material.

## Project Status

Working project.

Future improvements may include:

* Cleaner category structure
* Better deduplication
* Website verification
* Email discovery
* Phone number validation
* Source URL column
* Confidence scoring
* Manual review flags
* CSV export for easier GitHub diffs
* Separate tabs by business category or parish
