### General Ledger Journal Entry  

> Table name: <B>GL_JOURNAL_ENTRY<B>

|  Field Name  | Type | Description|
| :------------ | :------------ |:------------ |
| ID  | number  | auto generated id as a unique primary key|
| GL_ACCOUNT_ID  | number  | General Ledger table id|
| ENTRY_TYPE  | string  | entry type (credit or debit) enumeration(DR,CR) |
| AMOUNT | number(19,6) | Entry amount  |
| CURRENCY_CODE | string | currency code . the currency comes from product definition |
| OFFICE_CODE | string |office can be a bank branch , head branch or in general or a cost center|
| TRANSACTION_ID | number | fk to the transaction table. it is not mandatory |
| REFERENCE_NUMBER | string | a unique reference number to grouping the multiple entreis together|
| request_id | string | a unique id that links this entry a input (API) request. |
| EXTERNAL_REFERENCE_NUMBER | string| any external keys. for example when we need to link entries to Loan, Savings or also any external accounting system |
| DESCRIPTION | string| short description about the entry |
| ENTRY_DATE | time stamp | the date and time of the entry |
| MANUAL_ENTRY | boolean | if the entry posted by back office and manually enterd to the database (1 manual, systematically 0 )|
| USER_ID | number| entry added user  |
| CREATED_DATE | The date that entry created| |

