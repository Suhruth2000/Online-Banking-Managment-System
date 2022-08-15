Functionalites:
- You can either sign up as a joint account or single account. Duplicate usernames are not allowed. Initial balance is set to 0
- You can sign in by username, password and specifying what kind of account
- User-> Deposit, Withdraw, checkBalance, Change Password, View Details.
- Admin-> Add user, Delete user, Modify user, Get User Details.

How to Run:
First Run the account.c file. This will create a database.bin with 11 accounts in it. 5 of them are single accounts while other 5 are joint accounts.
The last account is the admin's  account. 
All the initial accounts have their ID's printed. 
Initially, passwords for single accounts are same as IDs. For joint accounts, passwords are the min(joint IDs).
Now run the server file with "cc -pthread -o server.out server.c". After executing server.out, in a different terminal you can now run client.c.
In order to shut the server down, login as admin with ID = 1 and password = admin. 
