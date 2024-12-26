
# NFTMarketplace

NFTMarketplace is a blockchain-based platform designed for minting, buying, and selling NFTs (Non-Fungible Tokens). Built on the Aptos blockchain, it leverages the power of decentralized systems for secure and efficient trading of digital assets.

---

## Package Information

**Name:** NFTMarketplace  
**Version:** 0.1.0

---

## Blockchain Addresses

The project defines the following addresses:

- **NFTMarketplace:** `0x6a7a7ce8593e4e127a11110a17e0e3b478dd5eb10a6b6b0b4581c29d6516e107`
- **Aptos Framework:** `0x1`
- **Primitives:** `0xCAFE`

---

## Dependencies

The project uses the following dependencies:

1. **AptosFramework**  
   Repository: [Aptos Core](https://github.com/aptos-labs/aptos-core)  
   Path: `aptos-move/framework/aptos-framework`  
   Revision: `main`

2. **AptosStdlib**  
   Repository: [Aptos Core](https://github.com/aptos-labs/aptos-core)  
   Path: `aptos-move/framework/aptos-stdlib`  
   Revision: `main`

3. **MoveStdlib**  
   Repository: [Aptos Core](https://github.com/aptos-labs/aptos-core)  
   Path: `aptos-move/framework/move-stdlib`  
   Revision: `main`

---

## Setup

Follow these steps to set up the NFTMarketplace project:

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-repository/nftmarketplace.git
   ```

2. **Navigate to the Project Directory**  
   ```bash
   cd nftmarketplace
   ```

3. **Ensure Move and Aptos CLI Tools Are Installed**  
   Install Move CLI and Aptos CLI to manage dependencies and deploy modules.

4. **Build the Project**  
   ```bash
   move build
   ```

5. **Run Tests**  
   ```bash
   move test
   ```

6. **Deploy**  
   Deploy the modules to your Aptos testnet or mainnet account using the Aptos CLI:
   ```bash
   aptos move publish --package-dir . --profile testnet
   ```

---

## Features

- **Mint NFTs**: Create new NFTs with unique attributes and metadata.
- **Buy/Sell NFTs**: Trade NFTs in a decentralized and secure manner.
- **Integration with Aptos Wallets**: Supports Aptos wallet connections for seamless transactions.

---

## Contribution

We welcome contributions from the community! To contribute:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add feature'`.
4. Push the branch: `git push origin feature-name`.
5. Open a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments

Special thanks to the Aptos community for providing an open-source framework for blockchain development.
