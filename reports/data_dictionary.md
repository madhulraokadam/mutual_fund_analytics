# Data Dictionary

## fact_nav
- amfi_code : AMFI Scheme Code
- date : NAV Date
- nav : Net Asset Value

## fact_transactions
- investor_id : Unique Investor ID
- transaction_date : Date of Transaction
- amfi_code : Mutual Fund Scheme Code
- transaction_type : SIP / Lumpsum / Redemption
- amount_inr : Transaction Amount

## fact_performance
- amfi_code : Mutual Fund Scheme Code
- scheme_name : Name of Scheme
- fund_house : Asset Management Company
- category : Fund Category
- return_1yr_pct : 1 Year Return (%)
- expense_ratio_pct : Expense Ratio (%)
- aum_crore : Assets Under Management (Crores)