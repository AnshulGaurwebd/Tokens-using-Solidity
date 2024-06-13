# Token Solidity Smart Contract

This is a simple token smart contract written in Solidity.

**Discription:**
Introducing "BITCOIN" (BIT), a custom token on Ethereum. This contract enables token creation, distribution, and destruction within the blockchain ecosystem. Users can mint new tokens with the "mint" function and burn existing ones with the "burn" function, ensuring balance integrity. With public variables for token details and a mapping for address balances, this contract offers a streamlined approach to decentralized finance on Ethereum.

**Getting Started:**

Installing:

Download: To obtain the program, you'll need to access the source code provided. You can copy the Solidity code into a text editor or directly save it as a ".sol" file.

Modifications: No modifications are needed to the files or folders. However, ensure that you have a compatible Solidity compiler installed to compile the contract.

Executing Program:

Compilation: Use a Solidity compiler to compile the contract. You can either use an online Solidity compiler or install one locally on your machine.

Deployment: After compilation, deploy the compiled contract to an Ethereum-compatible blockchain network. This can be done using tools like Remix, Truffle, or directly through Ethereum development frameworks like Hardhat.

Interaction: Once deployed, you can interact with the deployed contract using Ethereum wallets or through custom applications. Interactions include minting new tokens by calling the mint function and burning tokens by calling the burn function.

Step-by-Step:

Download: Save the provided Solidity code as a ".sol" file on your local machine.

Compilation: Open the Solidity file in a Solidity IDE or text editor that supports syntax highlighting for Solidity code. Compile the contract using a Solidity compiler. Ensure that the compiler version matches or is compatible with the pragma directive specified at the beginning of the file (^0.8.18 in this case).

Deployment: Deploy the compiled contract to an Ethereum network of your choice. This can be done through various development tools like Remix, Truffle, or using Ethereum development frameworks like Hardhat. Ensure that you have the necessary permissions and funds to deploy contracts on the chosen network.

Interaction: Once deployed, interact with the contract using Ethereum wallets or custom applications. Use the mint function to create new tokens and the burn function to destroy existing tokens. Ensure that you provide the required parameters (address and value) when calling these functions, and observe the changes in the total token supply and individual balances accordingly.

**Features:**

* Stores token details: name, abbreviation, and total supply.
* Tracks balances for individual addresses using a mapping.
* Allows minting of new tokens for a specified address.
* Enables burning of existing tokens held by an address with balance checks.

**Requirements:**

* Solidity compiler version ^0.8.18 or higher.

**Deployment:**

1. Compile the contract using your preferred Solidity compiler.
2. Deploy the contract to a blockchain network (e.g., Ethereum ).
3. Interact with the contract functions (mint and burn) using a web3 library or wallet connected to the network.

**Functions:**

* `mint(address recipient, uint amount)`: Mints a specified number of tokens (`amount`) for the provided address (`recipient`).
* `burn(address account, uint amount)`: Burns a specified number of tokens (`amount`) held by the provided address (`account`). This function includes a check to ensure the burning amount doesn't exceed the address's balance.
