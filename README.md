**Bank Management System**:
This is a simple banking management system implemented in C++.

**Features:**
**Login/Logout:** Users can log in with their name and account number. Once logged in, they can perform various banking operations. They can also log out when they are done.
**Transfer Money:** Logged-in users can transfer money between two accounts. They need to provide the account numbers of the sender and receiver along with the amount to transfer.
**Create Account:** New users can create an account by providing their name, account number, and initial balance.
**Check Amount:** Users can check the balance and pending loan amount associated with their account by providing their account number.
**Withdraw Cash:** Users can withdraw cash from their account by providing the account number and the amount to withdraw.
**Take Loan:** Logged-in users can take a loan by selecting a loan scheme (personal, home, or car) and providing the loan amount. The loan amount is added to the account balance.
**Issue Credit Card:** Users can check if they are eligible for a credit card based on a minimum balance of 10000. If eligible, they can choose from different credit card options.
Classes:
Account: Represents a bank account with attributes such as name, account number, balance, loan amount, and credit card eligibility. It provides methods to deposit, withdraw, take a loan, and check credit card eligibility.
Bank: Manages a collection of accounts and provides operations such as transfer money, create account, check balance, take a loan, issue a credit card, etc. It also handles user login/logout functionality.
