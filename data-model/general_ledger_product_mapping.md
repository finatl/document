### General Ledger Product Mapping


> Table name: <B>GENERAL_LEDGER_PRODUCT_MAPPING<B>

|  Field Name  | Type | Description|
| :------------ | :------------ |:------------ |
| ID  |   primary key| |
| GL_ACCOUNT_ID  |  General Ledger account table ID | |
| PRODUCT_REF_CODE  |  product table pk. this refer to the product | |
| CHARGE_TYPE_REF_CODE  | charge type   | |
| FINANCIAL_CODE  | Fk to Financial type table.  | |
| DESCRIPTION  | string  | short description about defined financial type |
