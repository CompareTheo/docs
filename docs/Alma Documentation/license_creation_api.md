---
layout: default
title: The License API
parent: Alma Documentation
nav_order: 1
---
### The License API


#### The License Object
The license API requires the creation of a "license object" that is pushed to Alma via a standard *post* using the API. This license object is detailed in the [Alma documentation](https://developers.exlibrisgroup.com/alma/apis/docs/xsd/rest_license.xsd/?tags=POST). However, this documentation is not clear regarding several key XML structural details that are necessary in the proper formation of the license object.

1. License terms are defined via a pair of definitions including a code (defined in the Alma 'LicenseTerms' code table) and a value (which is determined by the value defined in the pair).
2. The example license object provided by ExLibris lacks clarity around the way term code/value pairs are structured within the object. For each term code/value pair a new XML *term* element needs to be created in order for the term to be reflected properly in Alma. 

<div markdown="block">
{: .warning }
It is imperative that all license creation or modification scripts are tested in the sandbox environment first. Alma does not permit users to delete created license records. Once a license has been created, upon deletion, it will be marked "deleted" but cannot be removed from the database.
</div>