# Units Network Testnet Bot

This repository contains a Node.js application that automates transactions on the Units Network Testnet using multiple private keys.

## Requirements

- Node.js
- npm (Node Package Manager)

## Installation

1. **Nhập vào gitpot:**

   ```bash
   https://github.com/vinhben12/units-network-bot.git
  
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Chuẩn bị private keys:**

   - Tạo hoặc edit `privateKeys.json` to chứa private key. Có thể dùng nhiều acc

   **Example `privateKeys.json` (correct format):**
   ```json
   [
       "private_key_1_here",
       "private_key_2_here"
   ]
   ```

   Ensure each private key string is correctly formatted as shown above.

## Usage

- **Run the application:**

  ```bash
  npm start
  ```

- Follow the prompts to enter the number of transactions to send per private key.
