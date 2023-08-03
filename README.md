# hardhat-base-template

## To create a Hardhat project with this template
1. `git clone https://github.com/consensus-collective/hardhat-base-template`
2. `yarn install`
3. `yarn hardhat init`
4. Hardhat will give a script with a bunch of dependecies, install them, it'll look like:
    ```
    yarn add --dev "hardhat@^2.14.0" "@nomicfoundation/hardhat-toolbox@^3.0.0" "@nomicfoundation/hardhat-network-helpers@^1.0.0" "@nomicfoundation/hardhat-chai-matchers@^2.0.0" "@nomicfoundation/hardhat-ethers@^3.0.0" "@nomicfoundation/hardhat-verify@^1.0.0" "chai@^4.2.0" "ethers@^6.4.0" "hardhat-gas-reporter@^1.0.8" "solidity-coverage@^0.8.0" "@typechain/hardhat@^8.0.0" "typechain@^8.1.0" "@typechain/ethers-v6@^0.4.0" "@types/chai@^4.2.0" "@types/mocha@>=9.1.0" "@types/node@>=16.0.0" "ts-node@>=8.0.0" "typescript@>=4.5.0"
    ```
5. `yarn hardhat compile` : Check if tests compile    