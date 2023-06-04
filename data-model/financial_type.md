### Financial Type 

> Table name: <B>FINANCIAL_TYPE<B>

|  Field Name  | Type | Description|
| :------------ | :------------ |:------------ |
| FINANCIAL_CODE | string |  primary key and coding. code and name column could be same | 
| FINANCIAL_NAME | string | Financial type name .  any GL account that need to define in a product has a name here [↓](#FINANCIAL_NAME) |
| FINANCIAL_TYPE | string | this is same as general ledger account type [↓](#FINANCIAL_TYPE)| 
| DESCRIPTION  | string | short description about the financial type |

  
### <a name="FINANCIAL_NAME">Financial Type names</a> 
  The follwing list are default and primary general ledger mappings to the product .
  base on a need the new names and type can be defined
  in order to map the general ledger to a specific product , first we need define financial type in this table , after that in gl product mapping we map to a desired product
  
 * Saving
      - SAVINGS_CONTROL
 * ShortTerm Deposit
      - DEPOSIT_CONTROL  
 * FixedDeposit
      - DEPOSIT_CONTROL
 * Loan 
      - LOAN_CONTROL
      - INTEREST_ON_LOANS
      - INCOME_FROM_FEES 
      - INCOME_FROM_PENALTIES
  
  
  ### <a name="FINANCIAL_TYPE">Financial Type</a> 

* FINANCIAL_TYPE
- ASSET 
- LIABILITY 
- EQUITY 
- INCOME
- EXPENSE
- SUBLINE
  
