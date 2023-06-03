# Accounting General Ledger

> ACCOUNTING_GENERAL_LEDGER

|  Field Name  | Type | Description|
| :------------ | :------------ |:------------ |
|  REF_CODE |  string | The Primary key of the table. [↓](#ref_code)|
|  NAME | string  | General ledger name  |
|  GL_CODE |  string  |  General ledger coding |
|  CLASSIFICATION | string(enumeration)  | Account type  [↓](#account_type)|
|  SHORT_NAME | string  |   |
|  DESCRIPTION | string  |   |
|  EXTERNAL_CODE | string  |   |
|  HIERARCHY | string  |   |
|  MANUAL_JOURNAL_ENTRIES_ALLOWED | boolean  |   |
|  DISABLED  | boolean  |   |


 ### <a name="ref_code">REF_CODE</a> 
For the tables whose goal is configuration, the primary key field has been named the "REF_CODE"
* Two strategy can be chosen in coding the ref-code:
  - Numerical values 1:first record. 2: second record and ...
  - Set value similar to GL_CODE column 

 ### <a name="account_type">Account type</a> 
 - ASSET : the value in table would be "A"
 - LIABILITY : the value in table would be "L"
 - EQUITY : the value in table would be "E"
 - INCOME : the value in table would be "I"
 - EXPENSE : the value in table would be "X"
 - SUBLINE : the value in table would be "S"


