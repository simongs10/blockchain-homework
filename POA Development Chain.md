POA Development Chain walkthrough (with screenshots).

A blockchain is a network of nodes or machines linked in a peer-to-peer fashion that facilitates transactions in a verifiable and permanent way.

There are three types of blockchains:

1. Proof of Authority (POA)
2. Proof of Work (POW)
3. Proof of Stake (POS)

For this blockchain walkthrough we have developed a POA blockchain which is a reputation-consensus algorithim in which the model relieas on a limited number of block validaotrs that act as 
moderators to verify the newest blocks and transactions.

Steps in creating a POA blockchain and running a test transaction are detailed below.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Steps require Git Bash running (for Windows) 

1. Node account creation

![Node account creation screenshot](https://github.com/simongs10/blockchain-homework/blob/main/Screenshots/Screenshot%201.PNG)

2. Running puppeth which is a tool that creates a new Ethereum network and build a blockchain.

![Puppeth](https://github.com/simongs10/blockchain-homework/blob/main/Screenshots/Screenshot%202.PNG)

3. Puppeth continued 

![Puppeth continued](https://github.com/simongs10/blockchain-homework/blob/main/Screenshots/Screenshot%203.PNG)

4. Running geth (Go Ethereum) for node 1 which is a command line interface for running Ethereum node implemented in Go Language.

![Geth node 1](https://github.com/simongs10/blockchain-homework/blob/main/Screenshots/Screenshot%204.PNG)

5. Running geth for node 2 

![Geth node 2](https://github.com/simongs10/blockchain-homework/blob/main/Screenshots/Screenshot%205.PNG)

At this point the genesis block has been created and two nodes are running. We are now able to send transactions.

6. Setting up a custom node in MyCrypto note that chain ID is same as was entered during running puppeth (323) and URL points to the default RPC port onlocal machine.

![Setting up a custom node](https://github.com/simongs10/blockchain-homework/blob/main/Screenshots/Screenshot%206.PNG)

7. Sending a transaction, note that to address is address for node 2 and Eth amount is an arbitrary amount for testing purposes

![Sending a transaction](https://github.com/simongs10/blockchain-homework/blob/main/Screenshots/Screenshot%208.PNG)

8. Confirmation of the transaction and hash provided

![Confirmation](https://github.com/simongs10/blockchain-homework/blob/main/Screenshots/Screenshot%209.PNG)
