# ðŸ”¥ PyrovaCoin (PYR)

**Decentralized Cryptocurrency | SHA-256 | 21M Supply | Open Source**

---

## About PyrovaCoin

PyrovaCoin (PYR) is a decentralized, open-source cryptocurrency built on a modified Bitcoin Core codebase. It features SHA-256 Proof-of-Work mining, a capped supply of 21,000,000 PYR, and 5-minute block times.

## âš¡ Key Features

| Feature | Details |
|---------|---------|
| **Algorithm** | SHA-256 (Proof of Work) |
| **Block Time** | 5 Minutes |
| **Total Supply** | 21,000,000 PYR |
| **Block Reward** | 50 PYR |
| **Halving Interval** | Every 210,000 blocks |
| **Default P2P Port** | 8533 |
| **Default RPC Port** | 8532 |

## ðŸ“¦ Downloads

Download the latest release from the [Releases](https://github.com/jay534/pyrovacoin/releases) page.

### Windows 64-bit Binaries

| Binary | Description |
|--------|-------------|
| `pyrovacoind.exe` | PyrovaCoin Core Daemon (full node) |
| `pyrovacoin-cli.exe` | Command-line interface for RPC |
| `pyrovacoin-wallet.exe` | Wallet management tool |
| `pyrovacoin-tx.exe` | Transaction creation utility |
| `pyrovacoin-util.exe` | Miscellaneous utilities |

## ðŸš€ Quick Start

### 1. Start the Node
```bash
pyrovacoind.exe -daemon
```

### 2. Create a Wallet
```bash
pyrovacoin-cli.exe createwallet "MyWallet"
```

### 3. Get a New Address
```bash
pyrovacoin-cli.exe getnewaddress
```

### 4. Start Mining
```bash
pyrovacoin-cli.exe generatetoaddress 1 <your_address>
```

## ðŸ› ï¸ Configuration

Create a `pyrovacoin.conf` file in your data directory:

```ini
server=1
rpcuser=yourusername
rpcpassword=yourpassword
rpcallowip=127.0.0.1
rpcport=8532
port=8533
```

**Default Data Directory:** `%APPDATA%\PyrovaCoin\`

## ðŸ“‹ Specifications

- **Consensus:** Proof of Work (SHA-256d)
- **Network:** Mainnet
- **Address Prefix:** `P` (starts with P)
- **Genesis Block:** Custom genesis with PyrovaCoin parameters
- **Difficulty Adjustment:** Every 2016 blocks

## ðŸ“„ License

PyrovaCoin Core is released under the terms of the MIT License.

## ðŸŒ Links

- **GitHub:** [https://github.com/jay534/pyrovacoin](https://github.com/jay534/pyrovacoin)

---

*PyrovaCoin - Powering the future of decentralized finance* ðŸ”¥
