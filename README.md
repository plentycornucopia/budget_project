# Project: Inquiry
Project: Inquiry

We need to store all inquiry records on our personal budget from month to month. We want to store them in a Postgres DB with the following column structure:

|Reference|Report Date|Creditor Name|Type of Business|Date of Inquiry|Credit Bureau|
| :---------------- | :------: | ----: | ----: | ----: | ----: |
|*VARCHAR(9)|*MM/DD/YYYY|VARCHAR(255)|**VACHAR(255)|MM/DD/YYYY|VARCHAR|

* From month to month we will not know how many inquiry records we'll have. Could be 1. Could 30. Could be 0.
* If 0, no record should be created. If ≤1, then create the corresponding record(s) in the DB.

*must always be present

**may sometimes be blank

***postgres db available upon request

## Table Selector
`#Inquiries > table.rpt_content_table.rpt_content_header.rpt_content_contacts.ng-scope`
