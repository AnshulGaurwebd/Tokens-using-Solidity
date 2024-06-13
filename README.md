# Token Solidity Smart Contract

This is a simple token smart contract written in Solidity.

**Discription:**
Introducing "BITCOIN" (BIT), a custom token on Ethereum. This contract enables token creation, distribution, and destruction within the blockchain ecosystem. Users can mint new tokens with the "mint" function and burn existing ones with the "burn" function, ensuring balance integrity. With public variables for token details and a mapping for address balances, this contract offers a streamlined approach to decentralized finance on Ethereum.

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
