### Product

> Table name: <B>PRODUCT<B>

|  Field Name  | Type | Description|
| :------------ | :------------ |:------------ |
| CODE  | string  | Table Primary key . it should be manually added. it is better to set equal to product code |
| PRODUCT_CODE  | string  | The Business Product code |
| SHORT_NAME  |  string | breief name of product . it is useful in reporting or show to customer  |
| DESCRIPTION  | string  | not too long descroptioin about the product |
| PRODUCT_TYPE  | string  | type of product. the Eumeration (Loan, Saving) [^]|
| CURRENCY_CODE  | string  | the currency code. the list of currency is provided in global information service|
| EXTERNAL_ID  | string  | any external code. useful when converting data from an old system   |
| START_DATE  | timestamp  |the date and time that this product is available |
| END_DATE  | timestamp  | product expiry date |
| CREATED_BY | number | user who created this record|
| CREATED_DATE | timestamp | |
| UPDATED_BY | number| user who updated this record|
| UPDATED_DATE | timestamp | |
