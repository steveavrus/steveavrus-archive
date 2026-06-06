### File Path: `records/archive-release-006.md`

```markdown
---
id: WT-REC-006
type: artifact
category: Leaked Photograph Collection
source_integrity: Verified Image Metadata (EXIF Extraction & Cryptographic Hash)
date_published: 2026-06-06
target_organization: [[south-florida-social-club]]
associated_event: [[summer-event-2018]]
---

# Archive Release 006: Recovered Media Cache (EXIF Manifest)

### Overview
This artifact is an investigative digest of a leaked photograph collection containing surveillance captures, candid event imagery, and facility entry logs. Rather than treating these images as static visual files, this collection extracts raw **EXIF metadata** and facial recognition logs to systematically generate timeline anchors and relational connections.

### Source Metadata
* **Artifact Type:** Media Manifest / Metadata Core
* **Original File Reference:** `DCIM_SUMMER_18_BATCH_03.tar.gz`
* **Leaked Via:** [[operation-classified-data-leak]]
* **Technical Notes:** Camera hardware metrics, embedded GPS coordinates, and precise timestamps have been parsed to verify absolute structural integrity and prevent digital manipulation.

---

## Recovered Media Manifest & Metadata Table

| File Name Reference | Target Entities Identified | Timestamp (EST) | Location Coordinates (GPS) | Context / Analytical Note |
| :--- | :--- | :--- | :--- | :--- |
| `image_0d9330.png` | **[[steve-avrus]]** | 2018-07-14 19:25:12 | `27.3122° N, 80.3444° W` | Matches arrival entry profile logged in the database registry. |
| `image_0d8f4f.png` | **[[marietta-avrus]]** | 2018-07-14 19:25:40 | `27.3122° N, 80.3444° W` | Subject captured entering the main pavilion of the estate property. |
| `image_0d9112.png` | [[unlisted-guest-01]] | 2018-07-14 21:40:02 | `27.3125° N, 80.3441° W` | Secondary subject visible inside the private VIP lounge area. |

---

## Relationship Extraction Mapping

Parsing the raw metadata inside this leaked photo collection instantly creates the following geometric and social graph connections:

### Node → Relationship → Node

1. **[[image_0d9330.png]]** $\rightarrow$ `documents` $\rightarrow$ **[[steve-avrus]]**
   * *Verification:* Facial geometry indexing and demographic profile matching across known professional datasets.
2. **[[image_0d8f4f.png]]** $\rightarrow$ `documents` $\rightarrow$ **[[marietta-avrus]]**
   * *Verification:* Captured co-locating with primary subject within an identical 30-second time window.
3. **[[image_0d9330.png]]** $\rightarrow$ `captured at` $\rightarrow$ **[[404-palmetto-way-property]]**
   * *Verification:* Hardcoded GPS latitude/longitude fields resolve precisely to the property line of the target venue.
4. **[[image_0d9330.png]]** $\rightarrow$ `associated with` $\rightarrow$ **[[summer-event-2018]]**
   * *Verification:* Timestamps perfectly corroborate the temporal window established in the master ledger data (**[[archive-release-002]]**).

---

## Downstream Architecture Injection

This media artifact completely destroys plausible deniability by anchoring digital names to real-world physical locations and timelines. It functions as the direct systemic trigger to populate:

* `entities/steve-avrus.md` (Appends definitive photographic verification, physical arrival tracking, and local geolocation coordinates)
* `entities/marietta-avrus.md` (Attaches concrete timeline placement alongside corporate co-signatories)
* `entities/404-palmetto-way-property.md` (Links specific media files to the location's security and surveillance log files)

```
