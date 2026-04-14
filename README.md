🔐 AuxoLock
Where Deposits Earn Safely

AuxoLock is a real-world asset (RWA) protocol that transforms rental security deposits into secure, programmable, yield-generating assets on blockchain.

🚀 Problem

Rental security deposits today are:

Locked for months or years with zero returns
Prone to delays and unfair deductions
Managed through manual, trust-based systems
Lacking transparency during disputes

Both tenants and landlords deal with friction, inefficiency, and uncertainty.

💡 Solution

AuxoLock replaces traditional deposit handling with a non-custodial smart contract escrow built on Avalanche.

Deposits are locked on-chain with predefined rules
Funds remain fully protected (principal never at risk)
While locked, deposits earn low-risk yield (simulated in MVP)
Settlement is automatic and transparent
Disputes follow a structured, rule-based flow
🧠 How It Works
Lease Creation
Landlord defines lease terms and tenant address.
Deposit Locking
Tenant deposits funds into a smart contract escrow.
Yield Accrual
Deposit earns simulated yield over time (no risk to principal).
Settlement
No dispute → instant refund + yield split
Dispute → contract freezes and resolves via predefined logic
⚙️ Tech Stack
Blockchain: Avalanche Fuji Testnet
Smart Contracts: Solidity + Hardhat
Frontend: React (Vite) + Tailwind CSS
Web3 Integration: Ethers.js
Deployment: Vercel
🔐 Key Features
Non-custodial escrow (no third-party control)
Principal protection (no risk to deposit)
Yield-generating deposits (capital efficiency)
Automated settlement (no delays)
Transparent dispute handling
Fully on-chain record of actions
🏗 Project Structure
contracts/      → Smart contracts & deployment scripts  
frontend/       → React app & UI  
test/           → Contract tests  
docs/           → Architecture & demo docs  
🧪 Running Locally
1. Clone the repo
git clone https://github.com/your-username/auxolock.git
cd auxolock
2. Setup Contracts
cd contracts
npm install

Create .env:

FUJI_RPC_URL=...
PRIVATE_KEY=...
SNOWTRACE_API_KEY=...

Compile:

npx hardhat compile

Deploy:

npx hardhat run scripts/deploy-auxolock.js --network fuji
3. Setup Frontend
cd ../frontend
npm install

Create .env:

VITE_AUXOLOCK_ADDRESS=your_contract_address

Run:

npm run dev
🌐 Deployment
Smart contract → Avalanche Fuji
Frontend → Vercel

Add env variable in Vercel:

VITE_AUXOLOCK_ADDRESS=...
🏆 Why AuxoLock?

AuxoLock doesn’t change how renting works — it upgrades the infrastructure behind it.

It turns:

❌ Dead capital → ✅ Productive assets
❌ Trust-based systems → ✅ Rule-based execution
❌ Manual disputes → ✅ Transparent automation
🔮 Future Scope
Real DeFi integration (Aave / Benqi)
Reputation-based deposit reduction
Insurance-backed deposits
DAO-based dispute resolution
NFT deposit receipts
🤝 Contributing

Pull requests and ideas are welcome.
This project is built as part of Build Games on Avalanche.

📜 License

MIT License
