# ETH Beginner Assessment

This project involves creating a basic Ethereum token named PikuCoin using a smart contract called MyToken. The token incorporates functionalities for minting and burning tokens, enabling management of the total token supply.

## Description

This project is a simple Ethereum smart contract designed to help beginners understand token creation and management on the blockchain. The contract includes public variables for the token's name (PikuCoin), abbreviation (PC), and total supply, and uses a mapping to track token balances for each address. It features a mint function to create new tokens and add them to a specified address, increasing the total supply, and a burn function to destroy tokens from a specified address, reducing the total supply, provided the address has enough tokens.

## Getting Started

### Executing Program

To run this program, you can use Remix, an online Solidity IDE. Follow these steps:

1. **Open Remix IDE**: Go to [Remix IDE](https://remix.ethereum.org/).

2. **Create a New File**: Click on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., MyToken.sol).

3. **Copy the Code**: Copy and paste the code from the [ETH-Beginner-Assessment.sol](ETH-Beginner-Assessment.sol) file into your new file in Remix.

4. **Compile the Code**: Click on the "Solidity Compiler" tab in the left-hand sidebar. Ensure the "Compiler" version is set to a compatible version (e.g., 0.8.0 or higher). Then click the "Compile MyToken.sol" button.

5. **Deploy the Contract**: Go to the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MYTOKEN" contract from the dropdown menu and click the "Deploy" button.

6. **Interact with the Contract**:
    - To mint tokens, use the mint function by providing the recipient address and the number of tokens.
    - To burn tokens, use the burn function by providing the sender address and the number of tokens to be destroyed.

### Modifications

No modifications are required for basic functionality. If you wish to change the token name, abbreviation, or add new features, you can modify the code as needed.

## Authors

Parteek Batheja  
[@ParteekBatheja](https://github.com/ParteekBatheja)

## License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.
