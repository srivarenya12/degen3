# DegenToken

This Solidity program is a smart contract for a token called "DegenToken". It includes features such as minting, burning, transferring tokens, and a redeem function for specific items. Below is a brief overview of the contract functionalities:

## Description

The `DegenToken` contract is an ERC20 token with additional functionalities. It includes the ability to mint new tokens, burn existing tokens, transfer tokens, and redeem specific items from a shop using tokens.

The contract has the following main functionalities:

- **Minting**: The `mint` function allows the contract owner to create new tokens and assign them to a specified address.

- **Burning**: The `burn` function enables token holders to destroy a certain amount of their tokens, reducing the total token supply.

- **Transferring**: The `transfer` function allows token holders to transfer tokens to other addresses.

- **Redeeming**: The `redeem` function lets token holders exchange their tokens for specific items listed in the redeem shop.

## Redeem Shop

The redeem shop currently offers three items: toys, places, and curtains. Each item has a corresponding serial number, and token holders can redeem these items by specifying the serial number of the item they wish to acquire.

## Getting Started

### Executing program

To interact with the `DegenToken` contract, you can deploy it on an Ethereum testnet or use Remix, an online Solidity IDE, for testing purposes.

1. **Remix**: 
    - Go to the Remix website at [Remix Ethereum](https://remix.ethereum.org/).
    - Create a new file with a `.sol` extension and paste the contract code into it.
    - Compile the contract by selecting the appropriate compiler version and clicking on the "Compile" button.
    - Deploy the contract by switching to the "Deploy & Run Transactions" tab, selecting the `DegenToken` contract, and clicking on the "Deploy" button.

2. **Ethereum Testnet**:
    - Use tools like Truffle or Hardhat to deploy the contract on an Ethereum testnet such as Ropsten or Rinkeby.
    - Interact with the deployed contract using a wallet like MetaMask.

### Testing Redeem Function

To test the redeem function:
- Ensure you have a sufficient balance of tokens (`DGN`) in your Ethereum wallet.
- Call the `redeem` function with the desired item serial number as an argument.
- Verify that the tokens are deducted from your balance and that you receive the corresponding item.

## Authors
Srivarenya T
onlysrivarenya@gmail.com 

## License

This project is licensed under the MIT License. See the LICENSE file for details.
