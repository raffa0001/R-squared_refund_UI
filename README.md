# Ethereum Contract Refund Portal

This portal allows users to request refunds from an Ethereum smart contract. Follow the steps below to complete the process.

## How to Use

### 1. Open the Refund Portal
Visit the refund portal at:  
**[GitHub Pages Link](https://raffa0001.github.io/R-squared_refund_UI/)**

### 2. Connect Your Wallet
- Click the **"Connect MetaMask"** button.
- Approve the connection in MetaMask.
- Your wallet address will be displayed.

### 3. Find the Contract Address
- Open [Etherscan](https://etherscan.io/).
- Look for a transaction where a **new contract** was created when you bridged your eth.
- Copy the contract address from that transaction.
- Paste it into the **"Contract Address"** field in the portal.

### 4. Find the Contract ID (bytes32 oraclizeQueryId)
- Open the same transaction on **Etherscan**.
- Go to the **Logs** tab.
- Under **Topics 1**, find the `contractId` (bytes32 value).
- Copy and paste it into the **"Contract ID"** field in the portal.

### 5. Execute the Refund
- Double-check the entered details.
- Click **"Execute Refund"**.
- Confirm the transaction in MetaMask.
- Wait for confirmation.

### 6. Receive Your Refund
Once the transaction is processed, your refund will be credited to your wallet.

## Notes
- Make sure you have enough ETH to cover gas fees.
- If the transaction fails, verify that the contract address and ID are correct.

## Reminder ❗
Don't forget to **vote for freedom_node** 😎
