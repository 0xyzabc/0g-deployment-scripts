# OG Deployment Scripts

Skrip dan konfigurasi untuk deployment smart contract menggunakan [Hardhat](https://hardhat.org/).

## 📁 Struktur Proyek
    ├── artifacts/ # Output build Hardhat (ignored)
    ├── cache/ # Cache build Hardhat (ignored)
    ├── contracts/ # Folder smart contracts (Solidity)
    ├── scripts/ # Deployment dan skrip testing
    ├── test/ # File test (Mocha/Chai)
    ├── .env # Variabel lingkungan (ignored)
    ├── .gitignore # File untuk mengecualikan file dari Git
    ├── hardhat.config.js # Konfigurasi utama Hardhat
    ├── package.json # Konfigurasi npm & dependencies
    └── README.md # Dokumentasi proyek


## ⚙️ Setup

### 1. Clone repositori ini

```bash
git clone https://github.com/username/og-deployment-scripts.git
cd og-deployment-scripts

## Install dependencies

    npm install

## Compile kontrak

    npx hardhat compile

## Deploy kontrak

    Deploy kontrak

npx hardhat run scripts/deploy.js --network testnet
