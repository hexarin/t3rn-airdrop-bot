# t3rn-airdrop-bot

A bot designed to automate transactions and bridge assets on the t3rn network, making the process seamless and efficient.

## Features

- Automates asset bridging and swapping on the t3rn network.
- Supports multiple wallets through a JSON file containing private keys.
- Robust error handling with retry mechanisms to ensure all transactions are completed.
- User-friendly and easy to set up.

## Requirements

- Node.js (v14 or later)
- NPM (v6 or later)
- Private keys for the wallets you intend to use (stored in `privateKeys.json`).

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/dante4rt/t3rn-airdrop-bot.git
   cd t3rn-airdrop-bot
   ```

2. **Install Dependencies**:

   ```bash
   npm install
   ```

3. **Create `privateKeys.json`**:
   Create a file named `privateKeys.json` in the root directory with the following format:

   ```json
   [
     "your_private_key_1",
     "your_private_key_2"
   ]
   ```

4. **Run the Bot**:
   Start the bot by running:

   ```bash
   node index.js
   ```

## Usage

- When the bot starts, it will prompt you to enter the number of transactions you wish to perform.
- The bot will then automatically execute the transactions, handling any errors and retrying as needed.

## Donations

If you would like to support the development of this project, you can make a donation using the following addresses:

- **Solana**: `GLQMG8j23ookY8Af1uLUg4CQzuQYhXcx56rkpZkyiJvP`
- **EVM**: `0x960EDa0D16f4D70df60629117ad6e5F1E13B8F44`
- **BTC**: `bc1p9za9ctgwwvc7amdng8gvrjpwhnhnwaxzj3nfv07szqwrsrudfh6qvvxrj8`

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
