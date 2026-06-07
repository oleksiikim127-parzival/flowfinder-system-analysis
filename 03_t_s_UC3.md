## Assign category
**Use Case ID**: UC3

**Brief description**:
This use case allows user to categorize financial transactions.

**Primary actor**:
User

**Secondary actor**: -

**Preconditions**: -

**Main Flow of Events**:
1. The usecase starts when the user is creating a new financial transaction in UC1.
2. The user chooses some already created category.
3. The user clicks on the button `Save`.
4. The system assigns choosen category to the transaction.

**Alternative flows**:
2a. The user decides to create a new category.

2a.1. INCLUDE (Manage categories).

2a.2. Continue to 2.

**Post-conditions**:
1. The financial transaction, serving as an input for this usecase, is labeled by a new category.