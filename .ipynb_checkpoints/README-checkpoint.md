# blockchain-wallets-homework
Module 19 Challenge: Cryptocurrency Wallet

## KryptoJobs2Go
![Application interface](Images/application_interface.png)  
KryptoJobs2Go is an application in which customers can find FinTech professionals from among a list of candidates, hire them, and pay them. Candidates are displayed in a single column on the main page. Candidate information includes:
- Headshot (picture)
- Name
- Ethereum account address
- KryptoJobs2Go rating
- Hourly rate in Ether

Customers can select a candidate and set the number of work hours required in the lefthand sidebar. The application automatically displays the customer's connected wallet address and their balance of Ether, as well as information relating to the candidate selected and the total wage expected based on the work hours required. Customers can hire the candidate by clicking the `Send Transaction` button at the bottom of the sidebar.

### Customer balance
![Customer balance](Images/customer_balance.png)  
Within Ganache, the customer's balance can be found under the `ACCOUNTS` section.

### Block details
![Block details 01](Images/block_details_01.png)  
![Block details 02](Images/block_details_02.png)  
Within Ganache, information relating to the block can be found under the `BLOCKS` section. Clicking on the newest block will open the block's details.

### Transaction details
![Transaction details 01](Images/transaction_details_01.png)  
![Transaction details 02](Images/transaction_details_02.png)  
Within Ganache, information relating to the transaction can be found under the `TRANSACTIONS` section. Clicking on the transaction will open the transaction's details.

## Other information
- All work for the application interface can be found in the [krypto_jobs.py](https://github.com/julianritchey/blockchain-wallets-homework/blob/main/krypto_jobs.py) file.
- All relating to wallet connectivity can be found in the [crypto_wallet.py](https://github.com/julianritchey/blockchain-wallets-homework/blob/main/crypto_wallet.py) file.
- All images used in this assignment can be found in the [Images](https://github.com/julianritchey/blockchain-wallets-homework/blob/main/Images/) folder.