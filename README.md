SIMPLE SOLIDITY PROGRAM
(TESTING: MOCHA TESTING, DEPLOYMENT: SEPOLIA ETHEREUM NETWORK)

Wallet Provider : Metamask
Select SepoliaTestNetwork in Metamask.
To get Test Ether :
1.	Visit https://sepoliafaucet.com/
2.	Register for a free Alchemy account        
3.	Select Sepolia network
4.	Copy address from Metamask and send Ether from Sepolia faucet.
Testing and Deployment:
Install following packages using npm command in command line. Here I have used VSCode editor for testing and deploying smart contract.


Command:

>npm install mocha ganache web3

>npm install @truffle/hdwallet-provider

>npm install solc@0.8.9

>npm install solc@0.4.17 (Here I used version 0.4.17 compiler. You can use the latest solidity compiler also)


Deployment:

1.	Goto https://infura.io/register
2.	Create free account.
3.	Find Ethereum in Endpoints.
4.	Click the dropdown to select sepolia network.
5.	Goto Active Endpoints and select the URL link.
6.	Assign this URL into provider variable in deploy.js code.


You can check deployed contract in https://sepolia.etherscan.io/ after running deploy.js script.
Copy contract deployed address from terminal and Paste that address in search bar of this page https://sepolia.etherscan.io/ .

Command to run test script :
npm run test

Command to run deploy.js script:
Node deploy.js

Guided By UDEMY course by Steven Grider ( Ethereum and Solidity: The Complete Developer’s Guide) 

