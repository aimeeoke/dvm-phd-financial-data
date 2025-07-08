# dvm-phd-financial-data
This repository contains data files for financial projections and analysis of the DVM/PhD combined degree program.

## Data Files

### `historical-costs.json`
Contains historical cost rates by fiscal year including:
- Stipend amounts
- GRA fringe rates  
- PhD tuition and fees
- DVM tuition and fees by program year

### `trainees.json`
Contains trainee enrollment records including:
- Entry year
- Graduation year (actual or projected)
- Program status
- Trainee identifiers

### `program-rules.json`
Contains business logic and funding model rules including:
- Default funding allocation by program year
- T32 grant parameters
- Projection assumptions

## Data Structure

All files follow consistent JSON formatting with:
- Metadata sections for data provenance
- Standardized field naming (camelCase)
- Consistent data types

## Usage

These files are designed to be consumed by financial analysis tools via direct URLs:
https://raw.githubusercontent.com/aimeeoke/dvm-phd-financial-data/main/[filename].json

## Last Updated
July 8 2025

## Data Sources
- University Financial Records (KFS)
- Oracle distributions (Oracle)
- Accounts Receivable Operations (ARO Portal)
- Graduate School Database (Ariesweb)

