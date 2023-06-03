# Accounting General Ledger

> ACCOUNTING_GENERAL_LEDGER

|  Field Name  | type | d|
| :------------ | :------------ |:------------ |
|  REF_CODE |  string | The Primary key of the table. [↓](#ref_code) |
|  NAME | string  |   |
|  GL_CODE |  string  |   |
|  CLASSIFICATION | string(enumeration)  |   |
|  SHORT_NAME | string  |   |
|  DESCRIPTION | string  |   |
|  EXTERNAL_CODE | string  |   |
|  HIERARCHY | string  |   |
|  MANUAL_JOURNAL_ENTRIES_ALLOWED | boolean  |   |
|  DISABLED  | boolean  |   |

>REF_CODE:
 <a name="ref_code"></a> For the tables whose goal is configuration, the primary key field has been named the "REF_CODE"
Two strategy can be chosen in coding the ref-code
  * Numerical values 1:first record. 2: second record and ...
  * Set value similar to GL_CODE column 
>
