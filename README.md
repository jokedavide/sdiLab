# sdiLab
Question 3

Event flow
Start of use case
1. When Sarah approaches the ATM, she inserts her card into the machine and it begin the transaction

2. When the user insert the card, the ATM system activates and displays PIN entry. 

3. when the user enters their PIN number, ATM system will verify the PIN with bank database

4. When the user selects "withdraw cash" the ATM will display options for withdrawal amount. 

5. When the user enter the desired amount, the ATM will verify the account balance. 

6. When the balance is sufficient, the ATM dispenses the requested cash. 

7. When the cash is dispensed, the ATM prints receipt showing transaction details.

8. When the transaction completes, ATM will ejects the card and return to idle state. 

ALT :

INValid / wrong
When the user enters an incorrect Pin, ATM will display error message

Insufficient balance
When the requested amount exceeds the available balance, ATM will display " Insufficient Funds" and display new amount or cancellation

Transaction cancelled
When the User cancels the transaction, ATM will ejects the card and end the session. 

End of case
User(Sarah) retrieves her card and cash and ATM return to idle state. 
