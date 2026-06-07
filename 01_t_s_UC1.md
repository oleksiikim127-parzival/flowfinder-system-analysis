# Enter financial transactions

**Use Case ID:** UC1  

**Brief Description:**  UC1 records new financial transactions, including income and expenses, to keep the user's financial records up to date.  

**Primary Actors:**  User  

**Secondary Actors:** -

**Preconditions:** -

**Main Flow of Events:**  
1. The user selects the option to add a new transaction.  
2. The system displays a form for entering transaction details (amount, date, description, category).
3. INCLUDE(Assign category)
4. The user fills in the required fields.  
5. The user confirms and submits the transaction.  
6. The system validates the input and saves the transaction.  
7. The system updates the displayed list of transactions and any relevant balances.  

**Alternative Flows:**  
6a **Invalid Input:** If required fields are missing or invalid (e.g., negative amount for income), the system shows an error message and prompts the user to correct the input.  
6a.1 Continue to 7.

**Post-conditions:**  
- The new transaction is saved in the system and appears in the transaction list.  
- Relevant balances and statistics reflect the new transaction.  
