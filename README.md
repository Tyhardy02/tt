# tt
dekiCoin Solidity Contract
The dekiCoin Solidity contract is a basic implementation of a cryptocurrency token that allows users to mint (create) and burn (destroy) tokens, manage balances, and track the total supply of the token.

Requirements
Token Details: The contract stores essential details about the token, including its name, abbreviation, and total supply.

Balances Mapping: The contract uses a mapping to keep track of token balances for each address.

Mint Function: The contract has a mint function that increases the total supply and the balance of a specified address by a given amount.

Burn Function: The contract features a burn function that reduces the total supply and the balance of a specified address by a given amount. It includes a check to ensure the sender's balance is sufficient for burning.

Usage
Deployment: Deploy the dekiCoin contract to the Ethereum network using a tool like Remix or Truffle.

Token Creation (Minting): To create tokens, call the mint function with the recipient's address and the desired amount as parameters.

Token Burning: To destroy tokens, call the burn function with the sender's address and the amount to burn as parameters. Ensure your balance is sufficient for burning.

Authors
This contract is created by [TTHadjor]. If you have any clarifications, feel free to contact me at [tthadjoryaw02@email.com].

License
This project is licensed under the MIT License.

References
Solidity Documentation: https://soliditylang.org/docs/
Remix - Solidity IDE: https://remix.ethereum.org/
Ethereum Official Website: https://ethereum.org/
