### General Ledger Product Mapping


> Table name: <B>GENERAL_LEDGER_PRODUCT_MAPPING<B>

|  Field Name  | Type | Description|
| :------------ | :------------ |:------------ |
| ID  |   primary key| |
| GL_ACCOUNT_ID  |  General Ledger account table ID | |
| PRODUCT_REF_CODE  |  product table pk. this refer to the product | |
| CHARGE_TYPE_REF_CODE  | charge type   | |
| FINANCIAL_TYPE_NAME  | Financial type name .  any GL account that need to define in a product has a name here [↓](#FINANCIAL_TYPE_NAME) | |
| FIANCIAL_TYPE_REF_CODE  |   | |
| DESCRIPTION_CODE  |   | |


  
   ### <a name="FINANCIAL_TYPE_NAME">Financial Type names</a> 
    ### Saving
      * SAVINGS_CONTROL
    ### ShortTerm Deposit
      * DEPOSIT_CONTROL  
    ### FixedDeposit
      * DEPOSIT_CONTROL
    ### Loan 
      * LOAN_CONTROL
      * INTEREST_ON_LOANS
      * INCOME_FROM_FEES 
      * INCOME_FROM_PENALTIES
  
  
