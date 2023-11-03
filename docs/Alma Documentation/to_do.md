---
layout: default
title: To Do List
parent: Alma Documentation
nav_order: 1
---

### To Do List

#### Active
- [ ] Define how "EOY" stats will be collected using "Advanced" searching methods. (@Ron)
- [ ] "Ordering" Workflow Documentation (@Ron)
- [ ] "CVG Load to Portfolio Loader" Conversion Procedure - Marie says that split coverage will be an issue. (@Marie)
- [ ] Create "Vendor Interfaces" in Alma - We should think about how those interfaces will best help us query the system.
- [ ] Liaison Automatic Fund Reporting Setup
- [ ] ALMA CATs Procedure Documentation (@Cristina)
- [ ] Investigate Alma "Task" Structure (@Ron)
- [ ] Alma "Workday" Integration
- [ ] Write "License API" Documentation
- [ ] Write "Vendor API" Documentation 
- [ ] Acquisitions Reporting Code Definitions (@Glenn) [delay one year]
- [ ] Create "Ordering Templates" - Create only where necessary. (@Ron)
- [ ] Create "Baby Bib" Templates - This will be defined by the .EDI structure. - Create only where necessary. (@Ron)
- [ ] Align Activated E-Resources with Vendors - This information will need to be populated (updated) once we go-live.
- [ ] Define Annual Reporting Statistics Needed - Align these with information creation and gathering in Alma.
- [ ] Remove P2E Stragglers - These records *should not* have migrated and will need to be cleaned up.
- [ ] Procedure and Documentation for E-Journal "Perpetual Access" stanzas update in Alma.
- [ ] Define which collections will need to exist so that we can also group the non-CZ managed and non-P2Ed once they are loaded.
- [ ] Discuss and design procedure for utilizing "Community Zone Update Tasks List" for keeping an eye on our owned titles managed in the community zone.
- [ ] Discuss and design a "tasking" workflow that might supplement or supplant the "NON-GOBI" E-Resource Tracker
- [ ] Paper Idea: How does a mid-size university use the Alma APIs? How do you implement that learning process? How do you make those decisions as a group? What does that group look like?
- [ ] How are "Rush" titles marked when a request is received after ordering and before receiving?
- [ ] Faculty Select Setup (@Steph, @Jamie)
- [ ] We are going to need to go back and look at all portfolios loaded and uncover all of the titles in each portfolio that are "inactive" due to lack of link. The link is in the 856 of the bib in most cases, but did not make it in the migration to the portfolio itself.
- [ ] How does EZProxy interact in Alma? How are URL vs. QURL determined? Can we solve the ASP issues?
- [ ] Make a dashboard for where we are in testing the metadata and edi load automation.
- [ ] ACRL, IPEDS, and All-Star(Law) are the reporting associations we report our data too each year. 
- [ ] Find examples of "Correct order record types for all P2E master bib records" (@Marie)
- [ ] Schedule time to flesh out the ["E-resourcePriorityTasks"](https://lmu.box.com/s/3q9lqvm23yh6fancjqncvbirauqxcvjs) sheet with those procedures that you and Ron have already highlighted and discussed on the ["ERA Procedures"](https://lmu.box.com/s/tsanew1xi4gdvlu9g3wfopwi20jmgz2k) sheet.
- [ ] Investigate "Correct order record types for all P2E master bib records" and write up something for Marie to review.
- [ ] Identify migrated ebooks without portfolios attached. Create a logical set so that Marie can see the query and review the total record count.
- [ ] Identify migrated ebooks with two portfolio from the same provider.
- [ ] Write documentation about the GOBI import profiles.
- [ ] Create import profiles for EOD records from subaccounts -08, -16, -47, -48, -49.
- [ ] Make sure all of the GOBI subaccounts are mapped in the vendor accounts area of the main_gobi vendor record.
- [ ] Investigate using analytics to create a scheduled list of ISBNs of new non-GOBI print purchases.
- [ ] Add additional procedures needed to the ["ERA Procedures"](https://lmu.box.com/s/tsanew1xi4gdvlu9g3wfopwi20jmgz2k) sheet.
- [ ] Document Normalization Rules needed for MARC record loads of locally managed continually updated record ingest.
- [ ] MMS ID 991022637483008066 had its visibility turned off in Ebook Central. We are waiting to see what will happen with that title; mainly, we want to know if it will be removed from the ProQuest Ebooks collection in Alma automatically.
- [ ] Document rules for LibEres email account management. Where do things go? What is the process?
- [ ] Create documentation for retrieving records from OCLC WMS and loading them into Alma. (This might need to be re-written once we have the normalization rules in pace. Also... once all of that is in place, write a proposal for how Alma could process these in the overnight period and the ERA could QC the work at the scheduled time instead of having to take the time to do the physical loads themselves.)
- [ ] Need full description of the issue with ECHO360 so that we can have a discussion with Jamie and with IT about possible solutions. 
- [ ] Write up the messy CZ Swank MARC Record issue for Glenn so that he can talk with Swank while at Charleston. 
- [ ] Write up changes to the "Request a Book Form" and get those to Astra ASAP for changes so that we can begin piloting the form before Thanksgiving for a launch in January.
- [ ] Is it possible to do an integration between libguides and records in Alma? How would that work? So that we can keep the two database lists in sync.
- [ ] Add reporting codes to Alma configuration so that they appear as options in the PO lines.

#### Complete
- [x] Look at QC queries in Sierra to see if they need to be saved before Sierra goes away.
- [x] Continuations will need a vendor change from main_gobi_dep to main_gobi
- [x] Jobs to automate the STC process from the ACD side?
- [x] Ask Ron about setting an invoice amount Threshold.
- [x] Kanopy "Import Profile" might need to create the PO & an inventory record in the import process. Work with this again. Do Kanopy imports overlay existing imports? - Perhaps we default this to NO and then manually process the "renewed" lease.
- [x] Setup Printers
- [x] Define "API Restriction Profiles" and Strategy (@Steph)
- [x] GOBI API Integration
- [x] MARCEdit API Integration
- [x] Configure "Shipping, Insurance, et al." to not auto insert during invoice creation. (Completed: 6/1/2023 @ 1742)
- [x] "Receiving" Transit time  - Get this behavior nailed down and clearly define it. (@Glenn)
- [x] Ugly Primo from "Display in Discovery" click (@Steph)
- [x] Create "Receiving" Workflow Documentation (@Cristina)
- [X] Create "Send To Cataloging" Workflow Documentation (@Kim)
- [x] Update "Access Models" List
- [x] Create "Import Profiles"
- [x] "Over-encumbered" Funds - Do we let care?
- [x] Configure "Invoice Review" Rules (@Ron) - These can be **very** granular.
- [x] Configure "Invoice Approval" Rules (@Ron) - These can be **very** granular.
- [x] Configure "Purchase Review" Rules (@Ron) - These can be **very** granular.
- [x] Configure "Acquisitions Alerts."
- [x] Create STO list and send to Suzanne/Copy - Jenny, Glenn, Ron, LibSto
- [x] Vlookup MAP Standing Order back to spreadsheet from Glenn to send to GOBI.
- [x] Write procedure for creating local electronic collections. (@Marie) [notes](https://lmu.app.box.com/notes/1261058251941)[Completed Procedure](https://lmu.box.com/s/s0wg1io6l98fqxt7kgpdx1gjwy9ft34q)
- [x] DDA & EBA Pool Management Strategy - what does it look like to manage these in the PDA area - what do the records look like - how is a purchased title processed out of that pool. - Write this up for Marie. 
- [x] Update P2E with Access Models
- [x] Send to Cataloging "Set" Query and Report (@Kim - Items needing cataloging can not be shelved "accidentally" - 9780824501778)
- [x] Rename E-Resource Collections - Thinking specifically about the way we want these to read to our patrons.
- [x] "Access Model" Display Configuration - What does this look like? License Display + Access, Access Only, License Only.
- [x] Group all of our P2E titles into collections for easy internal searching - Think about a strategy for this, we might mirror the Sierra strategy, or we might think about combining things and having fewer "Collection 1, Collection 2, Collection 3" sets.
- [x] Define all owned collections activated in the "Community Zone" and work to get vendor defined (purchase information verified) title lists for these collections where possible.