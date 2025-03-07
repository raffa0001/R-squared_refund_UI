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

![immagine](https://github.com/user-attachments/assets/30295501-8b50-41ec-971e-eeeeff906fe1)
![immagine](https://github.com/user-attachments/assets/3618ff43-8ba1-4af6-accc-197f70f56372)


### 4. Find the Contract ID (bytes32 oraclizeQueryId)
- Open the same transaction on **Etherscan**.
- Go to the **Logs** tab.
- Under **Topics 1**, find the `contractId` (bytes32 value).
- Copy and paste it into the **"Contract ID"** field in the portal.

![immagine](https://github.com/user-attachments/assets/6b26cb50-ea62-484a-9be6-087f043cfd7d)
![immagine](https://github.com/user-attachments/assets/2a790313-5756-46f6-bd4b-4dd2f25a1bd3)


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
