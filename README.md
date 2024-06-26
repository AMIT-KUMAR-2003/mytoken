

# MyToken 

This Solidity program is a simple "MyToken" contract that demonstrates the basic syntax and functionality of the Solidity programming language. The purpose of this program is to serve as a starting point for those who are new to Solidity and want to get a feel for how it works by creating a simple token with minting and burning capabilities.

## Description

This program is a smart contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract defines a custom token with a name, abbreviation, and total supply. It includes functions to mint and burn tokens, allowing the supply of tokens to be adjusted. This program serves as a simple and straightforward introduction to Solidity programming, and can be used as a stepping stone for more complex projects in the future.

## Getting Started

### Executing Program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., MyToken.sol). Copy and paste the following code into the file:

// SPDX-License-Identifier: MIT
pragma solidity ^0.8.18;

contract MyToken {
    // public variables here
    string public tokenName = "Amit Kumar Sahu";
    string public tokenSymbol = "Saami";
    uint public totalSupply = 0;

    // mapping variable here
    mapping(address => uint) public balance;
    
    // mint function
    function mint(address _address, uint _value) public {
        totalSupp += _value;
        balance[_address] += _value;
    }

    // burn function
    function burn(address _address, uint _value) public {
        if(balance[_address] >= _value) {
            totalSupp -= _value;
            balance[_address] -= _value;
        }
    }
}

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" (or another compatible version), and then click on the "Compile MyToken.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the mint and burn functions. Click on the "MyToken" contract in the left-hand sidebar to expand it, and you will see the available functions. You can use the input fields next to the functions to specify the parameters and then click on the appropriate function button to execute it.

## Authors

Contributors:
- Amit Kumar Sahu  
  

## License

This project is licensed under the MIT License 




