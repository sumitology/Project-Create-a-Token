
# Project-Create-a-Token

This is a basic token contract written in Solidity for the Ethereum blockchain. It includes the following features:

Public Variables:  
tokenName: The name of the token.
tokenAbbrev: The abbreviation of the token.   
totalSupply: The total supply of the token.

Mapping:  
balances: A mapping of addresses to their corresponding token balances.

Functions:

mint:  
Increases the total supply of the token by the specified amount.  
Increases the balance of the specified address by the specified amount.

burn:  
Decreases the total supply of the token by the specified amount.  
Decreases the balance of the specified address by the specified amount.  
Ensures that the balance of the specified address is greater than or equal to the amount to be burned.








## Deployment



To use this contract, you can deploy it on the Ethereum blockchain and then use the mint and burn functions to manage the token supply and balances.

## License

[MIT](https://choosealicense.com/licenses/mit/)

