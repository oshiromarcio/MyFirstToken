
# MyFirstToken Project

This project creates a new token called OSHIRO coin (symbol OSH) in an Ethereum network.

## Step-by-step to execute the smart contract

- Create a new wallet (Metamask recommended);
- Connect the wallet to a test network;
- Change the address at the constructor function to the address of the wallet created;
- Using the Remix IDE configure the compiler to a compatible version (0.4.26 for example) and EVM (byzantium);
- At the deploy tab select the environment (Injected Provider - Metamask), check it out the account (must be the same configured on Metamask), select the contract (OSHToken) and Deploy.

Doing the steps above will execute the smart contract and will create the tokens at the address provided at contructor function.

## An example of the tokens created

This contract has been run at Sepolia Testnet and created the OSH coins. The implementation and transactions links are below:

Address that received the coins:
`
0xb5EB90d4d52044e6Ed0605a31C5A4e8ea920670F
`


Transaction that created the OSH Coins [here](https://sepolia.etherscan.io/tx/0x548b26ae9be8447a650a2ef39e5597121bd887cc485e2bc43834339a0a8d4ec0).

The new token created [here](https://sepolia.etherscan.io/token/0x3b92e429277ef96f643925cdd5eec75b5dc3974d?a=0xb5EB90d4d52044e6Ed0605a31C5A4e8ea920670F).