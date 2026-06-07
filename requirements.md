## Functional requirements
### Basic version mode
1. FlowFinder allows users to use application **without** need of registration.
2. FlowFinder allows user to manually **enter financial transactions**.
3. FlowFinder allows user to **create**, **edit** and **delete** custom **categories**.
4. FlowFinder allows user to assign categories to transactions.
5. FlowFinder allows user to choose **main currency** in which will be displayed past transactions.
6. FlowFinder allows user to track incomes/outcomes in more currencies.
7. FlowFinder allows user to **filter** transactions based on various parameters.
8. FlowFinder **displays** user **statistics** related to transactions.
9. FlowFinder allows user to create, edit and delete **transaction templates**.
10. FlowFinder allows user to **import** / **export** transactions data.
11. FlowFinder allows user to subscribe to full version

### Full version mode
1. FlowFinder allows premium user to **synchronize** their data between devices.
2. FlowFinder allows premium user to **connect** their bank account from supported banks to the app.
3. FlowFinder allows premium user to enter **payment orders**.
4. FlowFinder downloads automatically **current rates**.
5. FlowFinder allows premium user to set **budget limits** for selected categories.
6. FlowFinder **categorizes transactions** automatically using custom rules and machine learning model.
7. FlowFinder allows premium user to view **advanced statistics** from their account and transactions.
8. FlowFinder allows premium users to create/join/leave/manage a **group**.
9. FlowFinder cancels subscription after it is not renewed
10. FlowFinder reminds user of important payments


## Nonfunctional requirements
1. FlowFinder uses local storage to store user data.
2. FlowFinder encrypts all data in transit using TLS 1.3 and secures stored data with AES-256 encryption.
3. FlowFinder works in offline mode except for synchronization between banks/accounts/devices 
4. FlowFinder will ensure no data loss during network interruptions. 
5. FlowFinder has mobile-first design, intuitive for everyday users. 
6. FlowFinder backend is programmed in Java