# Fayette Township (Juniata County, PA) — Document Index

Source: https://fayettetownship.com/
Scraped: July 27, 2026

This index catalogs everything publicly posted on the township site. Full text of the extractable meeting minutes is in the companion file `Fayette-Township-Meeting-Minutes-Archive.md`. Ordinances and a handful of recent minutes/agenda are scanned or `.odt` files with no machine-readable text — links are provided below for direct access.

---

## Ordinances (page: /ordinance/)

These are all scanned/image PDFs — no text layer via web scraping. Two have since been OCR'd from user-uploaded copies (see below); two remain link-only.

| Document | Link | Status |
|---|---|---|
| Zoning Map (2017 Revision) | https://fayettetownship.com/wp-content/uploads/2024/09/Zoning-Map-2017-Revision.pdf | Archived as-is — `Zoning-Map-2017-Revision.pdf` (it's a map image, not a text document, so no OCR attempted) |
| FATP Zoning Ordinance | https://fayettetownship.com/wp-content/uploads/2024/08/FATP-Zoning-Ordinance.pdf | **OCR'd** — see `Fayette-Zoning-Ordinance-2000-FullText.md`. The 8 dimensional/use-table pages (rotated 90° in the scan, unparseable by OCR) are manually transcribed into markdown tables in place, each with its upright source image embedded from `zoning-district-tables/` for verification |
| Fayette Township SALDO (Subdivision & Land Development Ordinance) | https://fayettetownship.com/wp-content/uploads/2024/09/Fayette-Township-SALDO.pdf | **OCR'd** — see `Fayette-SALDO-1996-FullText.md` (clean OCR throughout, no rotated tables) |
| Fayette Twp Solar Ordinance | https://fayettetownship.com/wp-content/uploads/2024/09/Fayette-Twp-Solar-Ordinance-1.pdf | Link only — scanned/image PDF, not yet uploaded for OCR |

**Note for the land parcel project:** Zoning Ordinance (2000) and SALDO (1996) are now fully digitized and directly relevant to your 6.51-acre parcel's permitted uses, dimensional requirements, and subdivision process. The Solar Ordinance is the one remaining gap — upload it the same way (as a PDF in chat) if you want it OCR'd too.

---

## Forms

| Document | Status |
|---|---|
| Building/Land Use Permit application (`Fayette-Land-Use-Permit-Application.pdf`) | Blank application form — user-uploaded from Fayette Township/Juniata County. Has a text layer (no OCR needed). Covers building/land use permit, driveway permit, sewage/septic, and setback fields. |

---

## Agenda (page: /meetings/meetings/)

| Document | Link |
|---|---|
| 2026 Agenda — July 8, 2026 | https://fayettetownship.com/wp-content/uploads/2026/07/2026-Agenda-July-8-2026-2.odt |

`.odt` format — not extractable through this tool. Link only.

---

## Meeting Minutes — now fully archived

All 25 meetings from June 2024 through June 10, 2026 have full text in `Fayette-Township-Meeting-Minutes-Archive.md`. The April, May (x2, duplicate), and June 2026 minutes were originally `.odt` files that couldn't be scraped from the web; they were converted from user-uploaded copies with pandoc and added to the archive.

Still not captured: the July 8, 2026 Agenda (`.odt`, link in the table above) — text-only agenda, low value to convert unless needed.

**Notable from the newly added minutes:** the supervisors are actively developing a **data center ordinance** (raised April 2026, ongoing discussion through June 2026, with resident concerns aired at the June meeting) — worth watching if this could affect land use policy in the township going forward.

---

## Notable items surfaced while reading the minutes (relevant to zoning/land use)

Flagging these because they bear directly on your parcel and general township land-use posture — pulled from the minutes archive, not the ordinance text itself:

- **Solar on agricultural land is currently not permitted** without a zoning ordinance amendment or a variance through the zoning hearing board. This came up twice (Apr 2025 — supervisors declined to amend the ordinance for a 24-acre ag parcel; Jul 2025 — Fulkroad solar farm inquiry told the same, must go through zoning hearing board).
- **Rezoning ag → commercial** is handled case-by-case, not by "spot zoning" — requires a formal zoning hearing board process, ~$1,000 filing fee, adjoining owner notification, hearing within 60 days. Two 2025 cases (Graybill welding shop, Shirk pallet grocery) both went this route; Shirk's was approved after a contested public hearing (Nov 2025).
- **Floodplain Management Ordinance** was in active development as of Oct 2025–Jan 2026 (township doesn't currently have one; supervisors' solicitor was drafting from a model ordinance). Worth checking current status if floodplain exposure matters for your parcel.
- **Granny Flats Ordinance** (2025-3) was adopted August 2025 — relevant if any accessory dwelling use is ever considered.
- **Sewage/septic**: new construction requires sewage planning module approval and DEP sign-off; several subdivision waivers in the minutes were conditioned on DEP approval. SALDO waivers and plan approvals are handled directly by the Board of Supervisors (not a separate planning commission) based on what's in these minutes.
- **Subdivision practice**: typical process seen repeatedly — surveyor (often Axis Surveying or Wright Surveying) presents plan, board approves waivers, then approves the plan itself, same meeting.

---

## Officer Directory

Fayette Township's supervisors, secretary, tax collector, auditors, roadmaster, zoning/permit officer, zoning hearing board, engineer, solicitor, inspection service, and constable, transcribed from Juniata County's own published directory (not the township site) — see [`Fayette-Township-Officer-Directory.md`](Fayette-Township-Officer-Directory.md), sourced from [`2026-JUNIATA-COUNTY-DIRECTORY-07.21.2026.pdf`](2026-JUNIATA-COUNTY-DIRECTORY-07.21.2026.pdf) (pages 15–16 of that document). See the disclaimer in the [README](README.md) before relying on any contact info here — it's a snapshot as of July 21, 2026.

---

## Site pages with no documents

- About Our Township — text-only, no attachments
- Contact Us — not scraped for documents (contact form/info only)
