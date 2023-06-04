### General Ledger

> Table name: <B>GENERAL_LEDGER<B>

|  Field Name  | Type | Description|
| :------------ | :------------ |:------------ |
|  ID |  number | The Primary key of the table.|
|  NAME | string  | General ledger name  |
|  PARENT_ID | number  | The parent id in the hirarchy of general ledger|
|  GL_CODE |  string  |  General ledger and accounting coding |
|  CLASSIFICATION | string(enumeration)  | Account type  [↓](#account_type)|
|  SHORT_NAME | string  | short name for general ledger . for reporting purpose. most of the time the name is too long and we need to have an abrivation   |
|  DESCRIPTION | string  | not too long explanation about the product   |
|  EXTERNAL_CODE | string  |  For reporting purpose. it is better to use refer to an old system  |
|  HIERARCHY | string  | a string comma seperated ids that indicate a link to the root node  |
|  MANUAL_JOURNAL_ENTRIES_ALLOWED | boolean  | This is a control field to restrict useing a general ledger accountto post manual entry from UI(Panel) |
|  DISABLED  | boolean  | By disabling a general ledger all posting to it will be rejected  |

 ### <a name="account_type">Account type</a> 
 - ASSET : the value in table would be "A"
 - LIABILITY : the value in table would be "L"
 - EQUITY : the value in table would be "E"
 - INCOME : the value in table would be "I"
 - EXPENSE : the value in table would be "X"
 - SUBLINE : the value in table would be "S"


