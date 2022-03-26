main page with the fund list
Add/Edit/Delete fund

go into 1 fund to get transaction details 
Add/Edit/Delete transaction

Operations
funds
    - List of funds
        - TODO: view to get list of funds
    - add new fund
        - TODO: view to add new fund
    - edit / delete fund
        - TODO: view to update/delete fund
    - search fund
        - search fund with filter (criteria - name, type, investment, profile, loss)
    - sort fund
        - could be handled with js (profit/loss)

fund detail
    - get the overall fund performance
        - get the fund details - name, purchase type, inveted amount, current amount, latest NAV, date of NAV, 
    - list of transaction
        - TODO: view to get list of transactions
        - TODO: sorted funds with latest transactions
    - add new transaction
        - TODO: view to add transaction
    - edit / delete transaction
        - TODO: view to delete transaction / Update can be delayed

scheduled updates for nav
    - TODO: authentication with JWT or OAuth
    - TODO: DRF API - for updating nav of funds

authentication
    - TODO: username, password
    - TODO: will try authenticating with google
    - TODO: jwt/oauth for api call

models

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
