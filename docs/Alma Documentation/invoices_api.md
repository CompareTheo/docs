---
layout: default
title: The Invoices API
parent: Alma Documentation
nav_order: 6
---

### The Invoices API

- Invoices are stored in Alma using a unique identifier. This identifier seems to only be discoverable via Analytics and is used as the ID entry when making an API call. In essence, this unique identifier is the invoice's primary key.

- There are three call types in the invoices API endpoint: GET, PUT, POST. Each corresponding to one or more activities that you might want to complete using the API. 
    - GET: allows for the programmatic reading of invoices. 
    - PUT: allows you to update an invoice. This is made more complicated by the fact that "what" can be updated is dependent on the "status" of the invoice at the time of the update.
    - POST allows for a service (payment) to be run on the invoice. It is via this endpoint that you can properly "pay" an invoice such that it's status is changed from "waiting to payment" to closed.

#### POSTing Invoices

- When an invoice is in "Waiting for payment", only the following fields can be updated:
    - report_tax
    - explicit_ratios
    - notes
    - payment_status
    - voucher_number
    - voucher_date
    - voucher_amount
    - voucher_currency

#### Working Notes

- Using test record ID 4346732450008066.

<invoice>
<payment>
<payment_status>PAID</payment_status>
<voucher_date>2024-03-11</voucher_date>
<voucher_number>JM-1234</voucher_number>
<voucher_amount>150</voucher_amount>
<voucher_currency>USD</voucher_currency>
</payment>
</invoice>