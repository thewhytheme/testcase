# testcase 
Test cases for moneyfy application
1) Add expense
Prerequisites:
USER should have an account (Any currency)
Steps:
1. Click on a "-" icon on a Main Screen.
2. Enter value 15.
3. Click on "Choose category" button.
4. Pick any.
Expected result:
1. New expense screen with available value field is present.
2. Value is entered.
3. Default categories if expences are present.
4. Expence should be added on main screen successfully.

2) Add income
Prerequisites:
USER should have an account (Any currency)
Steps:
1. Click on a "+" icon on a Main Screen.
2. Enter value 666.
3. Click on "Choose category" button.
4. Pick any.
Expected result:
1. New income screen with available value field is present.
2. Value is entered.
3. Default categories if expences are present.
4. Income should be added on main screen successfully.

3) Add account
Prerequisites:
USER has an existing default account (Any currency)
Steps:
1. Click on right top action menu.
2. Click accounts.
3. Click Add.
4. Fill name field, starting balance and pick an icon.
5. Click Add. 
Expected result:
1. Side menu is opened.
2. Accounts tab is displayed.
3. New account screen is present.
4. Parameters are set.
5. Pop up on a main screen is present and new account present in accounts tab.

4) Delete expense
Prerequisites:
USER should have an account and expence (dating today) (Any currency)
Steps:
1. Click o balance button on a main screen.
2. Click on existing category o expenceq.
3. Click on expense amount.
4. Click on garbage can icon (top right).
Expected result:
1. Current date balance tab is opened.
2. Amount is present.
3. Editing expense screen is opened.
4. Pop up is present (Transaction deleted) and expense in not present on a balance tab. 

5) Add expense with empty amount
Prerequisites:
USER has an existing default account (Any currency)
Steps:
1. Click on a "-" icon on a Main Screen.
2. Click on "Choose category" button.
Expected result:
1. New expense screen with available value field is present.
2. Amount field is highlighted red and new expense screen is present.

6) Find an transaction with note by search
Prerequisites:
USER has an existing default account with expense/income record with note "test" (Any currency)
Steps:
1. Click on magnifiing glass icon.
2. Enter "test" in a searchbar and click on it.
Expected result:
1. Search bar is active and keyboard is present.
2. Transaction is present in search results tab.

7) Transfer money on same account
Prerequisites:
USER has an existing default account (Any currency)
Steps:
1. Click on transfer icon.
2. Click on amount field.
Expected result:
1. New transfer tab is opened.
2. Field is animated and pop up "accounts should be different is present". New transfer screen is opened.

8) Show expenses of a given date
Prerequisites:
USER has an existing default account (Any currency) and any expense (two weeeks old from date of test)
Steps:
1. Click on action menu on a main screen (top left).
2. Click "Pick date" button.
3. Set a date two weeks ago from today and click OK.
Expected result:
1. Side menu is opened.
2. Date pecker is opened.
3. Main screen is opened on a choosen date and transaction is present.

9) Check transfer of the balance
Prerequisities:
USER has an existing default account (Any currency)
Steps:
1. Create new account with Name "Test", value "9", date of starting balance: yesterday.
2. Click on action menu on a main screen (top left).
3. Click on All Accounts button and pick Test account.
Expected result:
1. Account is creted.
2. Side menu is opened.
3. On a main screen transfered balnce should be present and at day before screen should be income line with amount 9 (days before are not containing transactions).

10) Add an expense by icon
Prerequisities:
USER has an existing default account (Any currency)
Steps:
1. On a main screen click on any icon.
2. Fill amount field and create expense.
Expected results:
1. New expense window is opened.
2. New expense is added on main screeen current date.
