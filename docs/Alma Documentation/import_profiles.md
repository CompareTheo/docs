---
layout: default
title: Import Profiles
parent: Alma Documentation
nav_order: 4
---

### Types of Import Profiles
<br />

**New Order**: Used for loading bibliographic records with embedded order data (EOD). This profile will create a new bibliographic record, a PO-Line from the embedded order data, and physical/electronic inventory. (e.g., GOBI approvals, Kanopy)

**Update Inventory**: Used for updating inventory or bibliographic records with an associated PO-Line. The only match point in this profile is the PO line reference number. (e.g., FY23 purchases needing payment in Alma)

**Repository**: Used for loading/updating bibliographic records and physical/electronic inventory (e.g., Streaming video collections, E-Resource collections)
<br />

#### Repository Import Profile

| Field | Example Value | Formatting Instructions |
| --- | --- | --- |
| Profile name: | main_nameofprofile | All profile names created for the Westchester campus library should be formatted in all lowercase with no spaces and should be proceeded by  "main_"
| Profile description: | Loads Kanopy provided MARC records. Creates active portfolios from information contained in the MARC. | Please be as descriptive as possible with your descriptions. Use keywords to indicate the type of records being created and any activation or collection creation steps the profile might be creating. |
| Originating system: | Kanopy | Select the provider of the MARC records being loaded. This is where you retrieved these records from and not the provider of the titles within the MARC records. If the MARC provider is not listed, please select "Other". |
|Import Protocol: | Upload File/s | For the vast majority of MARC records ingested into Alma "Upload File/s" is the appropriate selection. Using "Upload File/s" will allow the individual running the profile to select the MARC file from their local computer. |
| Physical source format: | Binary | Where MARC records are being loaded, the only appropriate selection is "Binary". |
| Encoding format: | UTF-8 | Set the encoding format for your MARC file. When in doubt, choose UTF-8 as the default option |
| Source format: | 