# coredao-contract-templates
A collection of CoreDAO contract templates for educational and development purposes.

# ☕ **Voting-Contract-Core** Smart Contract


This contains a secure and transparent voting contract built on blockchain technology. It ensures tamper-proof voting, supports multiple election formats, and maintains participant confidentiality. Ideal for decentralized applications and smart contract implementations. Includes code, deployment instructions, and test cases for seamless integration.
---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/vishunagar0404/Voting-Contract-Core.git
cd Voting-Contract-Core
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the project root:

```env
PRIVATEKEY="your_core_wallet_private_key"
CORE_TEST2_SCAN_KEY="your_testnet2_explorer_api_key"
```

> ⚠️ **Important:** Never share your private key or commit the `.env` file to version control.

---

## 🛠 Hardhat Commands

### Compile Contracts

```bash
npx hardhat compile
```

### Run Tests

```bash
npx hardhat test
```

### Deploy Contract

Use a deployment script:

```bash
npx hardhat run scripts/deploy.js --network core_testnet2
```

---

## 🔍 Contract Verification

You can verify contracts using Core block explorers:

```bash
npx hardhat verify --network core_testnet2 <deployed_contract_address> <constructor_args_if_any>
```

API keys for verification must be included in `.env` as shown above.

---
