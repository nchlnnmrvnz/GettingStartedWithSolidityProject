# Project Title

Getting Started with Solidity - A Metacrafters Project

## Description

The project is a solidity-based Ethereum smart contract designed to facilitate the creation, management, and transfer of a custom token.

## Getting Started
### Installing
To execute this program, Remix, an online Solidity IDE, can be utilized. Commence by visiting the Remix website accessible at https://remix.ethereum.org/.

While on the Remix website, initiate the process by generating a new file via the "+" symbol found on the left-hand sidebar. Ensure that the file is saved with a .sol extension (e.g., HelloWorld.sol). Proceed by copying and pasting the subsequent code into the newly created file:

```solidity
pragma solidity ^0.8.4;

contract HelloWorld {
    function sayHello() public pure returns (string memory) {
        return "Hello World!";
    }
}
```

For code compilation, navigate to the "Solidity Compiler" tab on the left-hand sidebar. Confirm that the "Compiler" option is configured to "0.8.4" (or a compatible version), and subsequently, execute the compilation process by clicking on the "Compile HelloWorld.sol" button.

After successful compilation, the contract can be deployed by visiting the "Deploy & Run Transactions" tab on the left-hand sidebar. Choose the "HelloWorld" contract from the dropdown menu and proceed by clicking on the "Deploy" button.

With the contract now deployed, interaction is possible by invoking the sayHello function. Select the "HelloWorld" contract within the left-hand sidebar, access the "sayHello" function, and execute it by clicking the "transact" button to retrieve the "Hello World!" message.

## Authors

Contributors names and contact info

Nichole Anne Marie J. Avañez 
[@nchlnnmrvnz](https://github.com/nchlnnmrvnz)

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
