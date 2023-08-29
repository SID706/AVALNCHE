This Solidity smart contract implements a basic token with minting and burning functions. The contract allows you to mint new tokens and burn existing tokens based on specified conditions.

Features
Mint new tokens and assign them to an address.
Burn existing tokens from an address, updating both total supply and individual balances.
Contract Details
Token Name: TYU
Token Abbreviation (Symbol): TU
Total Supply: Initialized to 0 and updated when minting tokens.
Functions
mint(address _address, uint _value)
This function mints new tokens and assigns them to the specified address.

Parameters:
_address: Ethereum address to which the tokens will be assigned.
_value: Number of tokens to mint and assign.
burn(address _address, uint _value)
This function burns (destroys) existing tokens from the specified address.

Parameters:
_address: Ethereum address from which tokens will be burned.
_value: Number of tokens to burn.
Usage
Deploy the MyToken contract on the Ethereum blockchain using a compatible development environment or tools like Remix.
Interact with the contract using transactions to mint and burn tokens.
Ensure that the balance of the sender (caller) address is sufficient for burning tokens.
