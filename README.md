[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=6337462&assignment_repo_type=AssignmentRepo)
# Exercise 4.1 Your First Account

The exercise template comes with a ready-made class named `Account`. The `Account` object represents a bank account that has balance (i.e. one that has some amount of money in it). The accounts are used as follows:

```python
artos_account = Account("Arto's account", 100)
artos_swiss_account = Account("Arto's account in Switzerland", 1000000)

print("Intial state")
print(artos_account)
print(artos_swiss_account)

artos_account.withdraw(20)
print("The balance of Arto's account is now: " + str(artos_account.balance()))
artos_swiss_account.deposit(200)
print("The balance of Arto's other account is now: " + str(artos_swiss_account.balance()))

print("End state")
print(artos_account)
print(artos_swiss_account)
```

Write a program that creates an account with a balance of 100, deposits 20 in it, and finally prints the balance.

**NB!** Perform all the operations in this exact order.
