# transaction-verifier-distributed-server
This repository is for a 3rd party distributed server that prevents fraud by verifying cryptocurrency transactions before they are added to the blockchain maintained by miners who earns commision by doing requests. The server will be able to verify transactions from any blockchain and protect even bridge applications from fraud. 3-factor verification, each party in the transaction initiate and approve the transaction on the 3rd party server and receive unique transaction id for the server to verify with the 3rd party server.

# This vision is for a 
3rd party server that prevents fraud by verifying cryptocurrency transactions before they are added to the blockchain. This would help to ensure that only legitimate transactions are added to the blockchain, and would help to reduce the amount of fraudulent activity that takes place within the cryptocurrency space. This server would work to verify transactions by looking at various factors, such as the amount being transferred, the addresses involved, and the history of the addresses involved. If a transaction is deemed to be suspicious, it would be flagged and further investigated. This server would also work to provide real-time data on the blockchain, so that users can see which transactions are taking place and can make informed decisions about whether or not to participate in them.

# Goals
1. Verify that the transaction is valid and that the sender has the necessary cryptocurrency to complete the transaction. 
2. Prevent double-spending by ensuring that the same cryptocurrency isn't being used in multiple transactions simultaneously. 
3. Ensure that the transaction is authorized by the correct parties before it is added to the blockchain.

# The high level protocol
The protocol would work as follows: 
1. The 3rd party server would receive a transaction from a user. 
2. The server would then verify that the transaction is valid by checking that the user has the necessary cryptocurrency to cover the transaction. 
3. If the transaction is valid, the server would then add it to the blockchain. 
4. If the transaction is invalid, the server would reject it and notify the user.

# Transaction Verifiers 3rd party server users
1. Cryptocurrency exchanges
2. Cryptocurrency wallets
3. Cryptocurrency investors
4. Cryptocurrency traders
5. Cryptocurrency businesses

# Example use cases
- Smart contract that wish to maximize security and remove fraud.
- Crypto currency exchange wishing to have a layer of fraud protection.
- Regulation applications
- Defi applications and other applications that want to be part of a regulated safe exchange environment which give additional layer of hack proof and fraud protection
- Currency developer adopting the server as part of their block creation validation logic.

# Success factor
- Having currency developers adding the server infrastructure as part of crypto transaction handling including bitcoin.

# Miners - 
Distributed transaction verification servers that are participating in the verification process
The 3rd party server will have a API that the miners can query to verify the transaction before they add it to the blockchain. The API will take in the unique transaction id and return whether the transaction is valid or not.
The 3rd party server can be run by anyone, but it needs to be trusted by the miners for it to be effective
