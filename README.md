# metacrafters_ETH-AVAX-PROOF_Project_Module_2
This report contains project assessment code for the ETH + AVAX PROOF course under metacrafter.

# Create a Token Using ERC20 on loacal HardHat

This Solidity program is a simple  program that demonstrates the basic syntax and functionality of the Solidity programming language. The purpose of this program is to Create a Token Using ERC20 on loacal HardHat.

## Description

This Solidity contract implements a basic token system with public variables to store essential token details: To

The contract provides a `mint` function that allows for the creation of tokens. It takes an address parameter and a value parameter, increasing the total token supply and adding the minted tokens to the balance of the given address. Conversely, the `burn` function decreases the token supply and deducts tokens from the specified address. To ensure the balance is sufficient for burning tokens, the function includes conditionals.

There is also a `transfer` function that allows to transfer tokens from one use to another.

By utilizing this contract, you can easily manage the creation and destruction of tokens while maintaining the overall token supply and individual token balances associated with Ethereum addresses.

## Getting Started

### Executing program

1. clone this repositry
2. Inside the project directory, in the terminal type: npm i
3. Open two additional terminals in your VS code
4. In the second terminal type: npx hardhat node
5. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js

Now, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., <YourFileNameHere>.sol). Copy and paste the code of this file --> [FileLink](https://github.com/vikasphulariya/Module3_eth_avax/blob/main/contracts/MyToken.sol)


To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" (or another compatible version), and then click on the "Compile <YourFileNameHere>.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar.
Now  select an Injected provider - Metamask from the Enviroment dropdown.
Select the "<YourFileNameHere>" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the  various functions.

## Authors
- Anshuman Roshan

