---
layout: default
title: E-Resource Portfolio Loader
parent: Alma Documentation
nav_order: 3
---
### The E-Resource Portfolio Loader

#### Usage
Alma's Portfolio Loader is used in four primary ways: 
1. Activate or deactivate collections linked to your Institution Zone from the Community Zone. (These are titles that are actively managed in the community zone).
2. Create a new electronic collection in the Institution Zone from a list of existing titles.
3. Import and export portfolio information.
4. Update existing electronic collections and individual portfolios within that collection (including: proxy settings, URL, parser parameters, inventory management groups, etc.).

This tool conducts **bulk** edits on an e-resource collection. For individual portfolio additions, use the "part of electronic collection" option when loading portfolios. Best practice has been to extract a MARC file of the portfolios that need to be moved and create the portfolio loader file from that set of MARC records. This will allow one to extract the Portfolio_PID from the MARC records to ensure a direct match against only intended titles. 

<div markdown="block">
{: .note }
An excel template is available for bulk loading titles through the Portfolio Loader. The template can be retrieved [here](https://knowledge.exlibrisgroup.com/Alma/Product_Documentation/010Alma_Online_Help_(English)/Electronic_Resource_Management/030_Working_with_Local_Electronic_Resources/015Managing_Electronic_Resources#Portfolio_Loader). This template is periodically updated by ExLibris and might require downloading again.
</div>

| Field                 | MARC Mapping/Description                                                     |
|:----------------------|:-----------------------------------------------------------------------------|
| TITLE                 | 245$a                                                                        | 
| ACCESS_TYPE           | Current or Perpetual                                                         | 
| AVAILABILITY          | ACTIVE or INACTIVE                                                           |
| PLACE_OF_PUBLICATION  | 260$a                                                                        |
| DATE_OF_PUBLICATION   | 260$c                                                                        |
| URL                   | overriding URLs of global portfolios or for setting URL on local portfolios  |
| PROXY_ENABLE          | True or False                                                                |
| PROXY_SELECTED        | Main                                                                         |
| PROXY_LEVEL           | PORTFOLIO or SERVICE                                                         |
| OWNERSHIP             | Hannon                                                                       |
| PUBLIC_NOTES          | Free Text Field (Kanopy Expiration Dates)                                    |

<div markdown="block">
{: .warning }
At least one of the following fields must be available in the Excel file: PORTFOLIO_PID, ISSN, ISBN, or OTHER_SYSTEM_NUMBER.
</div>