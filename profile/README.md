# PayLiao❗️

DeFi QR Payments System, using [Singapore's Standardised E-Payment QR Codes (SGQR)](https://www.mas.gov.sg/development/e-payments/sgqr), powered by Ethereum (Sepolia).

<div align="center">
<img 
  src="/assets/payliao-logo-yellow.png" 
  style="width:40% ; height:40%;"
/>
</div>

## 🎬 Introduction
SGQR is the world’s first unified payment QR code system. It combines multiple payment QR codes from payment providers into a single SGQR label, making QR payments in Singapore simple for both consumers and merchants.

With Singapore giving greenlight to stablecoins such as XSGD by StraitsX, CBDCs (Central Bank Digital Currencies) as a mode of payment in Singapore becomes an inevitable future. That's where **PayLiao** swings in!

PayLiao leverages **SGQR's unified payment QR Code** and **Blockchain** to provide a **DeFi payments alternative**.

Anyone owning a mobile phone with a **camera**, **data connectivity**, and an **EVM Wallet** will be able to make payments via PayLiao so long as the merchant supports their choice of payment.

**Visit <a href="https://payliao.github.io/payliao/">PayLiao</a> at the Deployed Website**

## 🤨 What is a Blockchain?

### Overview
A blockchain is a digital ledger that records transactions across a network of computers. It's known for its security, transparency, and resistance to tampering.

### Key Features
- **Decentralization**: Operates across a distributed network
- **Immutability**: Once recorded, data cannot be altered
- **Transparency**: All transactions are visible on the network

### Relevance to PayLiao
- Enables Secure Transactions: Blockchain's secure nature makes it ideal for financial transactions
- Supports Diverse Currencies: Ideal for handling multiple currencies

## 😩 CeFi Pain Points

1. **Uptime Challenges**
  - Traditional banking systems face uptime issues
  - DBS experiencing downtime twice in 2023.
2. **Accessibility Challenges**
  - Many countries lack services like Revolut and Wise
  - Hawker centres do not have credit card machine
3. **Rollout Challenges**
  - Introducing new payment systems to end users and merchants poses significant challenges.
4. **High International Transaction Fees**
  - To compensate the purchaser’s bank for converting funds into a foreign currency

## 🔮 Future of Payments: PayLiao!

### For Consumers 🛍️
1. **Effortless Transactions, Anytime, Anywhere**
   - Scan and PayLiao with existing SGQR
2. **Swift Onboarding, No Hassle**
   - Minimal KYC/AML
3. **Tourist Friendly**
   - No KYC
   - Change currencies easily
   - No remittance fees

### For Merchants ⛴️
1. **Effortless Transaction Monitoring**
   - No onboarding, elderly friendly
   - Just key in UEN or scan QR code to see
2. **Smart Contract Integration**
   - Your on-chain banking app
   - Monitor and manage your funds directly on the blockchain
3. **Tourist Friendly**
   - No KYC
   - Change currencies easily
   - No remittance fees

### For Banks 🏦
1. **Alternative to Banking Apps**
   - Serves as a backup in case traditional apps like PayNow fail
2. **Enhanced Security for Customers**
   - Blockchain reduces fraud and cyber attacks
3. **Improved Transparency**
   - Transparent nature of blockchain can aid in regulatory requirements
  
## 📑 Smart Contracts 

### Overview
- UEN Management Contract holds the database of all UENs in Singapore
- ERC20 contract holds the balance of merchants identified by their UEN

### Modified ERC20 Contract
- Holds merchant balance information
- Requires merchant to onboard and whitelisted before withdrawal
- Merchants can view balance before onboarding
- Can be forked to replace bank backends

### UEN Management
- Primary contract which contains all UENs.
- Prefilled by grabbing government data.
- Account is by default already up, no need for further onboarding to start accepting payments.
- Can be referred to by other smart contracts.

### 🙋🏻 How it works

1. Connect your wallet to PayLiao.
2. Scan a Merchant SGQR Code.
3. Enter the amount of SGDk.
4. Click on "Send Tokens".
5. Voila! It's done. You have paid a merchant in crypto!

<div align="center">
<img 
  src="https://github.com/payliao/.github/blob/main/payliao-flow.jpg"
/>
</div>
