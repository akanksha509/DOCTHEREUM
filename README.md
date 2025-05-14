# Docthereum 🩺
A decentralized application (dApp) designed to maintain anonymous medical reports and enhance healthcare accessibility globally 🌎.

## How Docthereum Enhances Healthcare

### 1. **Efficient Storage 📂**
Hospitals and healthcare institutions traditionally rely on paper-based records, which require significant storage space and are prone to errors, loss, or tampering. Searching for specific records can be slow and inefficient.  
**Solution:** Docthereum leverages decentralized storage, ensuring that medical records are securely stored in a digital format. This system is tamper‑proof, easy to retrieve, and removes the need for physical storage, improving accessibility and reducing the risk of manipulation.

### 2. **Patient Privacy 🎭**
Maintaining the confidentiality of patient records is crucial in healthcare. Breaches of privacy can have severe legal and reputational consequences for both hospitals and patients.  
**Solution:** By linking medical records to a patient’s Ethereum public address, Docthereum keeps identities anonymous. Only the patient controls their data, guaranteeing confidentiality and reducing the risk of unauthorized access.

### 3. **Enabling Medical Research 👩‍🔬**
Medical research often relies on large data sets from patient records, but obtaining consent can be cumbersome and time‑consuming.  
**Solution:** Because Docthereum anonymizes data at the source, aggregated medical information can be shared with researchers without violating patient privacy, accelerating progress in public health and clinical studies.

## Key Challenges & Solutions

### 1. **Verification 🕵️‍♂️**
Verifying doctors and labs without a centralized third party.  
**Solution:** Doctors and labs submit their registration IDs, which are verified via an external API. Chainlink oracles feed the result directly into the smart contract, keeping the process decentralized and tamper‑resistant.

### 2. **Testnet Compatibility**
Chainlink’s Rinkeby oracle network was under maintenance, while The Graph didn’t yet support Kovan.  
**Solution:** Smart contracts were deployed on both Rinkeby (for indexing) and Kovan (for testing oracle verification), allowing uninterrupted development.  
*Note: the live dApp currently interacts with the Rinkeby contract.*

## Technologies Used
- **Solidity** – Ethereum smart contracts  
- **IPFS** – decentralized file storage  
- **The Graph** – blockchain indexing & querying  
- **Chainlink** – decentralized oracles for external data  
- **React** – front‑end framework  
- **Web3.js** – JavaScript library for Ethereum interaction

## Demo
https://docthereum.web.app/

