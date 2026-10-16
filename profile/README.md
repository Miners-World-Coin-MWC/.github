# Miners World Coin (MWC)

**CPU-Mineable • Fair Launch • Community & Charity Driven**

Miners World Coin (MWC) is an open-source Proof-of-Work cryptocurrency built around accessible CPU mining, community participation and a commitment to making cryptocurrency mining more accessible.

MWC uses its own YesPower-based proof-of-work algorithm, `yespowerMWC`, and aims to enable participation across a range of supported devices, including desktop computers and compatible mobile and ARM-based systems.

Whether you're a miner, developer, node operator or community member, you're welcome to explore the project and contribute to its development.

## 🌐 Official Links

| Resource | Link |
|---|---|
| Official Website | [minersworld.org](https://minersworld.org/) |
| Core Repository | [MinersWorldCoin](https://github.com/Miners-World-Coin-MWC/MinersWorldCoin) |
| GitHub Organisation | [Miners-World-Coin-MWC](https://github.com/Miners-World-Coin-MWC) |
| Block Explorer | [MWC Explorer](https://miners-world-coin-mwc.github.io/explorer/) |
| Public API | [api.minersworld.org](https://api.minersworld.org) |
| CPU Miner | [Sugarmaker](https://github.com/Miners-World-Coin-MWC/sugarmaker) |
| Web Miner | [WebMiner](https://github.com/Miners-World-Coin-MWC/WebMiner) |
| API Server / Web Wallet | [Api-Server](https://github.com/Miners-World-Coin-MWC/Api-Server) |
| Mobile Wallets | [MinersWorldCoin-Mobile-Wallets](https://github.com/CryptoLover705/MinersWorldCoin-Mobile-Wallets) |
| Community Discord | [Join the MWC Discord](https://discord.gg/5HZGx5bbKK) |

Check each repository for the latest releases, supported platforms, documentation and installation instructions.

## 🚀 Project Highlights

- **CPU-Mineable:** designed around accessible proof-of-work mining rather than requiring specialised ASIC hardware.
- **YesPower-based mining:** uses the MWC-specific `yespowerMWC` algorithm.
- **Fair launch:** no premine, presale or ICO.
- **Open-source development:** core software and ecosystem tools are available through GitHub.
- **Cross-platform ambitions:** development targets multiple desktop, ARM and mobile environments.
- **Community and charity driven:** built around community participation and a commitment to supporting positive initiatives.
- **Open participation:** users can explore mining, run supported software, contribute code and help grow the ecosystem.

## ⚙️ Network Specifications

| Parameter | Specification |
|---|---|
| Name | Miners World Coin |
| Ticker | MWC |
| Consensus | Proof of Work (PoW) |
| Mining algorithm | `yespowerMWC` |
| Algorithm basis | Modified YesPowerSugar |
| YesPower N parameter | 2048 |
| YesPower r parameter | 32 |
| Target block time | 120 seconds |
| Maximum supply | 300,000,000 MWC |
| Initial block reward | 300 MWC |
| Mining reward | 270 MWC |
| Development and operations allocation | 30 MWC |
| Halving interval | 300,000 blocks |
| Mainnet P2P port | 4408 |
| Testnet P2P port | 14408 |
| Pool RPC port | 4403 |
| Pool P2P / Stratum port | 5579 |
| Mainnet address prefixes | 20 / 10 / 123 |
| Testnet address prefixes | 83 / 197 / 240 |
| Mainnet Bech32 HRP | `mwc` |
| Testnet Bech32 HRP | `tmwc` |

**Note:** These parameters describe the project's intended configuration. Confirm consensus-critical values against the source code and the network configuration of the release you're using.

## 💰 Block Rewards and Supply

The initial block reward is distributed as follows:

| Allocation | Amount | Share |
|---|---:|---:|
| Miner reward | 270 MWC | 90% |
| Development and operations | 30 MWC | 10% |
| **Total** | **300 MWC** | **100%** |

The block reward reduces according to the network's halving schedule, with a published halving interval of 300,000 blocks.

The maximum supply is 300 million MWC.

Mining rewards, balances and network activity should always be verified against the blockchain and current consensus implementation.

## ⛏️ Mining Miners World Coin

MWC is designed to support CPU mining using compatible hardware and mining software.

### Sugarmaker CPU Miner

Sugarmaker is the project's CPU mining software.

**Repository:** https://github.com/Miners-World-Coin-MWC/sugarmaker

Example command structure:

```bash
sugarmaker --a YespowerMwc --url <pool> --threads <threads> --user <wallet.worker> --pass <password>
```

Replace the placeholders with your chosen pool address, thread count, wallet address and the pool's required password or worker configuration.

Always check the miner's README and the pool operator's current instructions before connecting.

### Mobile and Alternative Mining

MWC development also includes mining and software initiatives for alternative platforms.

- [Sugarmaker](https://github.com/Miners-World-Coin-MWC/sugarmaker)
- [WebMiner](https://github.com/Miners-World-Coin-MWC/WebMiner)

Device compatibility and mining performance vary. Mobile mining can increase battery usage, device temperature and hardware wear.

## 👛 Wallets and Accessing MWC

Use the official project repositories to explore available wallet software and interfaces.

- **Core software:** [MinersWorldCoin](https://github.com/Miners-World-Coin-MWC/MinersWorldCoin)
- **Mobile wallets:** [MinersWorldCoin-Mobile-Wallets](https://github.com/CryptoLover705/MinersWorldCoin-Mobile-Wallets)
- **Web wallet and API server:** [Api-Server](https://github.com/Miners-World-Coin-MWC/Api-Server)
- **Block explorer:** [MWC Explorer](https://miners-world-coin-mwc.github.io/explorer/)
- **Public API:** [api.minersworld.org](https://api.minersworld.org)

Check the release documentation for supported operating systems, installation steps and compatibility requirements.

### Wallet Security

- Back up your recovery phrase and private keys securely.
- Never share wallet recovery information with anyone.
- Verify recipient addresses before sending transactions.
- Download wallet software only from sources you trust.
- Keep backups offline and protected.
- Test new software and unfamiliar features with small amounts or a suitable test environment first.

## 🔧 Development and Building

MWC is an open-source project, and contributions from developers and testers are welcome.

### Clone the Core Repository

```bash
git clone https://github.com/Miners-World-Coin-MWC/MinersWorldCoin.git
cd MinersWorldCoin
```

Follow the build documentation and dependency instructions provided by the repository for your operating system and target architecture.

Build requirements can differ between Windows, Linux, macOS, ARM and mobile environments.

### Contributing

If you want to help improve MWC:

1. Explore the existing source code and documentation.
2. Review open issues before starting substantial changes.
3. Test changes in an appropriate development environment.
4. Submit bug reports with clear reproduction steps.
5. Contribute fixes, documentation, tests and improvements through the project's GitHub repositories.

For consensus-critical changes, including mining algorithms, block rewards, difficulty adjustment, transaction validation and supply rules, thorough testing and review are essential.

Never commit wallet secrets, private keys, recovery phrases or API credentials.

## 🌍 Community

The MWC community is an important part of the project's development and growth.

Join the community to discuss mining, wallets, development, releases and ways to contribute.

- [Official Website](https://minersworld.org/)
- [Discord Community](https://discord.gg/5HZGx5bbKK)
- [GitHub Organisation](https://github.com/Miners-World-Coin-MWC)
- [Block Explorer](https://miners-world-coin-mwc.github.io/explorer/)

Community members can contribute by running compatible mining software, testing releases, helping newcomers, improving documentation and developing new ecosystem tools.

Be cautious of impersonators, fake giveaways, unofficial downloads and anyone requesting your recovery phrase or private keys.

## 📜 Licence

Please refer to the `LICENSE` file in the relevant repository for the applicable licence and conditions.

Licensing may differ between the core node, mining software, wallets, web interfaces and third-party dependencies.

## ⚠️ Disclaimer

Miners World Coin is open-source cryptocurrency software provided subject to the applicable project licences and terms. No guarantee is made regarding market value, mining profitability, network availability, future development or suitability for any particular purpose.

Cryptocurrency mining involves electricity costs, hardware wear and operational risks. Software may contain defects or vulnerabilities, and cryptocurrency transactions may be irreversible.

Users are responsible for evaluating the risks, securing their wallets, verifying software sources and complying with applicable laws and regulations.

---

**Miners World Coin (MWC)**

*CPU-Mineable • Fair Launch • Community & Charity Driven*

Website: https://minersworld.org/  
GitHub: https://github.com/Miners-World-Coin-MWC
