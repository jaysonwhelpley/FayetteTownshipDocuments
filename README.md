# Fayette Township Documents (Juniata County, PA)

A personal archive of Fayette Township's publicly posted ordinances, zoning map, and meeting minutes, converted to searchable/readable text where the source was a scanned or otherwise non-machine-readable file.

Source: [fayettetownship.com](https://fayettetownship.com/) — scraped/collected July 27, 2026.

## Why this exists

The township's own site only offers scanned PDFs and `.odt` files for most documents — no text layer, not searchable, and not diffable. This repo OCRs and transcribes those into plain markdown so the content is searchable, linkable, and easy to reference (e.g., when researching what's permitted on a specific parcel).

**This is not an official or legal source.** For anything you intend to rely on — setbacks, permitted uses, procedures, compliance — cross-check against the original PDF in this repo or with the township directly. OCR and manual transcription both introduce risk of error; see the per-document notes below.

## Contents

| File | Description |
|---|---|
| [`Fayette-Township-Documents-Index.md`](Fayette-Township-Documents-Index.md) | Index of everything on the township site: what's here, what's OCR'd, what's link-only, and notable items surfaced while reading the minutes (zoning/land-use relevant). Start here. |
| [`Fayette-Zoning-Ordinance-2000-FullText.md`](Fayette-Zoning-Ordinance-2000-FullText.md) | Full OCR text of the 2000 Zoning Ordinance (Ordinance No. 2000-1), 125 pages. The eight dimensional/use-table pages that OCR couldn't parse (they're rotated 90° in the scan) have been manually transcribed into markdown tables in place, each with the upright source image embedded alongside for verification. |
| [`Fayette Zoning Ordinance-ocr.pdf`](Fayette%20Zoning%20Ordinance-ocr.pdf) | The original scanned zoning ordinance PDF, with an OCR text layer added (searchable, but the underlying scan quality is what it is). |
| [`Fayette-SALDO-1996-FullText.md`](Fayette-SALDO-1996-FullText.md) | Full OCR text of the 1996 Subdivision & Land Development Ordinance (SALDO). Clean OCR throughout — no rotated tables. |
| [`Fayette-Township-Meeting-Minutes-Archive.md`](Fayette-Township-Meeting-Minutes-Archive.md) | Full text of all 25 available Board of Supervisors meeting minutes, June 2024 – June 2026, in one file. A few were converted from user-uploaded `.odt` files via pandoc where the web version wasn't scrapable. |
| [`meeting-minutes/`](meeting-minutes/) | The same 25 meetings, split into one file per meeting (`YYYY-MM-DD-Minutes.md`), for linking to or reading a single meeting without opening the full archive. |
| [`Zoning-Map-2017-Revision.pdf`](Zoning-Map-2017-Revision.pdf) | The 2017 revision of the township zoning map. Archived as-is (it's a map image, not a text document — no OCR attempted). |
| [`zoning-district-tables/`](zoning-district-tables/) | The eight dimensional/use-table page images from the zoning ordinance, rotated upright and named by district and page number. Referenced inline from the full-text ordinance (see below). |

## The zoning-district-tables

The 2000 Zoning Ordinance includes dimensional and permitted/conditional-use tables for each district (RA, F, R, C, I), printed rotated 90° on the page — a layout OCR can't reliably parse. Each of these eight pages is handled three ways in [`Fayette-Zoning-Ordinance-2000-FullText.md`](Fayette-Zoning-Ordinance-2000-FullText.md), at the point in the document where the table actually appears:

1. **A markdown table** transcribed by hand from the source image — usable, copyable, diffable, searchable.
2. **An embedded image** of the upright (rotated-to-readable) source page, so you can visually verify the transcription against the original layout.
3. **A direct link** to the full-resolution image file in [`zoning-district-tables/`](zoning-district-tables/), in case you want to view or download it independently.

A couple of cells in the RA District table (page 37, Use #6 — Single-Family Detached Dwellings) have handwritten corrections in the original scanned document. Where a correction was clearly legible it's reflected in the transcribed table with a footnote; where it wasn't fully legible, the footnote says so — check the embedded image or the original PDF before relying on that figure.

## Notes on the underlying ordinances

- **Zoning Ordinance (2000)** and **SALDO (1996)** are the two ordinances most directly relevant to permitted uses, dimensional requirements, and the subdivision process.
- The **Solar Ordinance** has not yet been OCR'd (link-only in the index) — solar on agricultural land is currently not permitted without a zoning amendment or variance, per multiple mentions in the meeting minutes.
- A **Floodplain Management Ordinance** was in active drafting as of the last minutes captured here (Oct 2025–Jan 2026) — the township did not have one as of that point.
- The supervisors were actively developing a **data center ordinance** as of the most recent minutes (raised Apr 2026, ongoing through Jun 2026).

See the index file for the full list of what's tracked, what's missing, and land-use-relevant items pulled from the minutes.

## Provenance / disclaimer

- Text files marked "FullText" are OCR output (Tesseract), not proofread line-by-line against the original scans.
- The eight zoning-table pages noted above were manually transcribed by a human/AI pass against the source images, not automated OCR.
- Meeting minutes are transcribed as posted by the township or converted from user-uploaded `.odt` copies where the web version wasn't scrapable.
- Always confirm against the official township records before relying on any figure here for a legal, compliance, or permitting decision.
