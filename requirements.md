main page with the fund list
Add/Edit/Delete fund

go into 1 fund to get transaction details 
Add/Edit/Delete transaction

Operations
funds
    - List of funds
    - add new fund
    - edit / delete fund

fund detail
    - list of transaction
    - add new transaction
    - edit / delete transaction

Attributes
Fund
    - ID - auto
    - Name - string
    - Option - Growth/IWDC/
    - Purchase type - Direct/Regular
    - invested amount - double
    - current amount - double
    - Latest NAV - double
    - Latest NAV Date - Date
    - test invested amount - double
    - test current amount - double

transaction
    - FundID
    - investment Date - Date
    - NAV - double
    - invested amount  - double
    - current amount - double
    - delta amount - double

fund IDs
    - FundID - foreign
    - ID - auto
    - ID1 - str
    - ID2 - str
