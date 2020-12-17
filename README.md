# Finance_App_in_C
A console based application to manage accounts and finance in C language.

The application is developed in C language to manage finances and various accounts. It is built using struct and arrays in C. The application has an admin portal and a user portal. The application focuses on authentication. The following operations are performed by the application:

1. It takes input whether you are user or admin.

2. If you are user, you can either create an account or login to an existing account.
3. It automatically generates an Id for new account to ensure unique IDs.
4. If a user wants to login to an existing account, he/she must enter valid credentials.
5. If the credentials entered are correct, the user can then check balance, transfer funds or deposit funds in the account.
6. In case of 3 incorrect attempts to log into an account the user's account gets locked and he/she can no longer access it.

7. If you are an admin, then the admin needs to enter correct credentials to access the admin portal. 
8. Upon accessing the admin portal, a list of accounts are displayed which are locked due to incorrect attempts.
