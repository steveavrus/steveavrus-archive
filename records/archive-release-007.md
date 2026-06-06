---
id: WT-REC-007
type: artifact
category: Leaked Cannabis Club Registration
source_integrity: Verified State Licensing Dump (JSON Back-end Table)
date_published: 2026-06-06
target_organization: [[south-florida-social-club]]
associated_location: [[404-palmetto-way-property]]
---

# Archive Release 007: Private Cannabis Dispensing & Social Club License

### Overview
This leaked artifact consists of a regional municipal business license application and approved compliance filing. Rather than serving as an arbitrary industry record, this registration ties a commercially protected cannabis micro-cultivation and consumption entity back to the central physical property, proving it operates as an integrated commercial extension of the **[[south-florida-social-club]]**.

### Source Metadata
* **Artifact Type:** Municipal Regulatory Registration / Commercial Use Application
* **Original File Reference:** `FL_DOH_OMMU_REG_2018_991.json`
* **Leaked Via:** [[operation-classified-data-leak]]
* **Context:** This regulatory record details the underlying commercial infrastructure behind private event logistics, demonstrating how explicit corporate entities control localized licensing layers.

---

## Recovered Registration Entry (Database Dump)

```json
{
  "registration_id": "FL-CANNABIS-2018-09118",
  "filing_status": "Approved / Exempt Under Private Club Clause",
  "effective_date": "2018-05-19",
  "licensee_details": {
    "commercial_entity": "South Florida Social Club Hospitality Division",
    "dba_alias": "Green Canopy Lounge Node",
    "facility_situs": "404 Palmetto Way Property (Cross-Ref: 9632 SW Lindale Trace Node)"
  },
  "compliance_officers": [
    {
      "name": "Steve Avrus",
      "role": "Regulatory & Financial Underwriter",
      "corporate_representation": "Avrus Financial & Mortgage Services, Inc."
    },
    {
      "name": "Marietta Avrus",
      "role": "Compliance Secretary",
      "corporate_representation": "Avrus Financial & Mortgage Services, Inc."
    }
  ],
  "operational_allowances": {
    "private_consumption": true,
    "on_site_distribution_limit": "Tier-3 Micro-Dispensing",
    "restricted_access_protocol": "Requires Verified Membership Record under ID #0882 Sequence"
  }
}
