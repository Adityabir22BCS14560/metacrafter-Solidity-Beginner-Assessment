This is my project for metacrafters solidity beginner course where this project is for creating a token.

contract Valorant 

Defines a new contract named Valorant, which will encapsulate all the functionality for this token.
Defines public variables for the token's name, abbreviation (symbol), and total supply, initializing total supply to zero.

// Mapping for token balances
Creates a mapping to store token balances for each address, where keys are addresses and values are uints (token amounts).

 // Mint function 
Defines a public mint function that increases total supply and the balance of the specified address by the given amount.

// Burn function 
Defines a public burn function that decreases total supply and the balance of the specified address by the given amount, with a check.
