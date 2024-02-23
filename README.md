# Vault Contract

## Description

This Solidity smart contract implements a Vault, allowing users to deposit Ether as grants for specific beneficiaries. The contract facilitates the donation process, tracks grant details such as amounts and deadlines, and enables beneficiaries to claim their grants once the specified deadline is reached.

## Getting Started

### Prerequisites

Before deploying the contract, ensure you have the following dependencies installed:

- Node.js
- Hardhat

### Installing

1. Clone this repository to your local machine:

```
git clone https://github.com/your-username/vault-contract.git
```

2. Navigate to the project directory:

```
cd vault-contract
```

3. Install the required npm packages:

```
npm install
```

### Deploying the Contract

1. Configure your Ethereum wallet provider in the `hardhat.config.js` file.

2. Write your Vault contract in the `contracts` directory or use the provided contract.

3. Compile the contracts:

```
npx hardhat compile
```

4. Deploy the contract to the desired Ethereum network:

```
npx hardhat run scripts/deploy.js --network <network-name>
```

Replace `<network-name>` with the desired network (e.g., `rinkeby`, `mainnet`).

## Usage

Once the contract is deployed, users can interact with it through the following actions:

- **Donate:** Users can donate Ether to the vault, specifying the beneficiary and the duration of the grant.
- **Claim Grant:** Beneficiaries can claim their grants once the specified deadline is reached, and the grant becomes available for withdrawal.

## Help

If you encounter any issues or have questions about using the Vault contract, you can refer to the Solidity documentation, Hardhat documentation, or seek assistance from the Ethereum development community.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.