Author: Kunaal Gupta

Programming Lanaguage: Solidity

Description: A web-based DApp on Ethereum blockchain for holding & transferring parent's Fund to their children upon maturity using Solidity

Included Files:
 * .deps
 * .learneth/Solidity NFT Course/4. Token Creation/
 * artifacts
 * contracts
 * scripts
 * tests
 * README
 * Trust.sol

Concepts:
 * EThereum Blockchain
 * Soldity Programming Language
 * Smart Contracts
 * DApp
 * transaction
 * assets
 

This workspace contains 3 directories:

1. 'contracts': Holds three contracts with increasing levels of complexity.
2. 'scripts': Contains four typescript files to deploy a contract. It is explained below.
3. 'tests': Contains one Solidity test file for 'Ballot' contract & one JS test file for 'Storage' contract.

SCRIPTS

The 'scripts' folder has four typescript files which help to deploy the 'Storage' contract using 'web3.js' and 'ethers.js' libraries. For the deployment of any other contract, just update the contract's name from 'Storage' to the desired contract and provide constructor arguments accordingly 
in the file `deploy_with_ethers.ts` or  `deploy_with_web3.ts`

In the 'tests' folder there is a script containing Mocha-Chai unit tests for 'Storage' contract.

To run a script, right click on file name in the file explorer and click 'Run'. Remember, Solidity file must already be compiled.
Output from script will appear in remix terminal.

Please note, require/import is supported in a limited manner for Remix supported modules.
For now, modules supported by Remix are ethers, web3, swarmgw, chai, multihashes, remix and hardhat only for hardhat.ethers object/plugin.
For unsupported modules, an error like this will be thrown: '<module_name> module require is not supported by Remix IDE' will be shown.

Software used:
 * REMIX IDE

Acknowledgments:
* Ethereum Documentation
* Soldity Documentation
* REMIX Cheatsheet

Github Profile: https://github.com/kunaal-gupta

Feedback: If you have any feedback or issue(s), please reach out to me at kunaalgupta@hotmail.com
