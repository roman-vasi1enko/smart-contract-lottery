# Provably Random Lottery Raffle Contracts

## Table of Contents

1. [About](https://chat.openai.com/c/915f2107-372f-4183-b166-445b2c50cbd6#about)
2. [Features](https://chat.openai.com/c/915f2107-372f-4183-b166-445b2c50cbd6#features)
3. [Technologies](https://chat.openai.com/c/915f2107-372f-4183-b166-445b2c50cbd6#technologies)
4. [Tests](https://chat.openai.com/c/915f2107-372f-4183-b166-445b2c50cbd6#tests)
5. [Contributing](https://chat.openai.com/c/915f2107-372f-4183-b166-445b2c50cbd6#contributing)
6. [License](https://chat.openai.com/c/915f2107-372f-4183-b166-445b2c50cbd6#license)

## About

This repository contains the code for a blockchain-based lottery system that is both transparent and provably random. Utilizing Solidity for smart contracts and Chainlink technologies for randomness and automation, this lottery platform aims to be fair, automated, and fully decentralized.

## Features

### User Interaction

1. **Enter the Lottery**: Users can enter the lottery by purchasing a ticket. The fees for the tickets are stored in a smart contract and are distributed to the winner after the draw.

### Automation and Randomness

2. **Automatic Drawing**: After a predefined period (`X`), the lottery will automatically select a winner programmatically.
3. **Provably Random**: Utilizes Chainlink VRF (Verifiable Random Function) to ensure that the lottery draw is random and verifiable.
4. **Time-Based Trigger**: Uses Chainlink Automation for time-based triggering of the lottery draw.

## Technologies

- Foundry: IDE.
- Solidity: For writing Ethereum-based smart contracts.
- Chainlink VRF: For generating a provably random number for the lottery draw.
- Chainlink Automation: For time-based triggering of the lottery draw.

## Tests

### Included Test Scripts

1. **Deploy Scripts**: Automated scripts for deploying the contracts.
2. **Unit Tests**: Tests that cover individual components of the contracts.
3. **Integration Tests**: Tests that cover the interaction between the contracts.
4. **Forked Tests**: Ability to run tests on:
    - Local chain
    - Forked Testnet
    - Forked Mainnet

Run the tests using Foundry:
`$ foundry test`

## Contributing

Feel free to dive in! Open an issue or submit PRs.

## License

This project is licensed under the MIT License.