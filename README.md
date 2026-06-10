# Lumina-Backend

Backend services and smart contracts for the Lumina Network ecosystem, featuring a NestJS/Express API, database migration system, event worker queues, and on-chain vesting integrations.

## 🚀 Key Features
* **Vesting & Claims Management:** Web APIs for creating and tracking vesting vaults, managing claims, and verifying off-chain/on-chain states.
* **Event Worker & Queues:** Background workers for monitoring Soroban events, database syncing, and message queues via BullMQ/RabbitMQ.
* **Robust Core Contracts:** Soroban-based smart contract integrations supporting secure token vesting.

## 🛠️ Tech Stack
* **Language/Framework:** Node.js (NestJS / Express) / Rust (Soroban)
* **Key Dependencies:** `@stellar/stellar-sdk`, `@nestjs/core`, `knex`, `pg`

## 📦 Getting Started

### Prerequisites
Ensure you have the required toolchains installed:
* Node.js (v20 or higher recommended)
* Rust toolchain (cargo, rustc)
* PostgreSQL database

### Installation & Local Setup
```bash
# Clone the repository (if running manually)
git clone https://github.com/Lumina-etwork/Lumina-Backend

# Install dependencies or build
npm install

# Run database migrations
npm run migrate

# Start the API server
npm run start
```

## 🤝 Contributing
Contributions are highly welcome. Please ensure your commits are cryptographically signed using GPG or SSH keys. For major structural changes, please open an issue first to discuss your proposal.