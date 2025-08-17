# 🛡️ Xcapit Offline Wallet for Cardano

## Overview  
**Xcapit Offline Wallet for Cardano** is an **open-source, SMS-enabled blockchain wallet** designed for users without internet or smartphones.  
The project enables **NGOs, governments, and humanitarian partners** to deliver **secure, transparent, and low-cost aid** at scale, using only basic feature phones.  

Unlike traditional wallets, this solution runs **fully offline**, bridging the digital divide and onboarding underserved communities into the Cardano ecosystem.  

---

## ✨ Key Features  
- **SMS-Based Account Creation & Management** → Programmatic setup of user addresses on Cardano via SMS, with sponsored initialization by NGOs.  
- **Fund Distribution via Smart Contracts (Aiken)** → Automated, transparent, and traceable distribution of funds.  
- **Sponsored Onboarding** → NGOs can pre-fund and activate wallets for beneficiaries.  
- **Offline Payments** → Merchants and users confirm transactions using SMS, without apps or internet.  
- **Partner Portal** → NGOs and partners can onboard beneficiaries, manage accounts, and monitor fund traceability.  
- **Open Source & DPG-Oriented** → Built as a **Digital Public Good** on Cardano.  

---

## 🚀 Roadmap / Milestones  
1. **Prototype (Month 2)**  
   - Core SMS wallet (account setup, transfers, sponsored onboarding).  
   - Transactions verifiable on Cardano testnet.  

2. **MVP (Month 4)**  
   - Partner portal + smart contracts in **Aiken**.  
   - Dashboard with real-time on-chain data.  

3. **Pilot (Month 6)**  
   - NGO pilot with 1–5K users.  
   - Target: **1,000+ successful transactions on Cardano mainnet**.  

4. **Technical Improvements & GTM (Month 7)**  
   - Release of **SDK/API open source** for Cardano developers.  
   - Go-to-market materials + partner integrations.  

---

## 🧩 Why Cardano?  
- **Low and predictable fees** → Scalable for millions of micro-transactions.  
- **Formal verification & security** → Safe fund management in high-stakes humanitarian contexts.  
- **Ecosystem alignment** → Integration with **Atala PRISM** for decentralized identity.  
- **Community-first approach** → Built with **Aiken smart contracts** to ensure developer accessibility and long-term sustainability.  

---

## 📂 Repository Structure  
```bash
offline-wallet-cardano/
│── contracts/        # Aiken smart contracts
│── wallet-core/      # Core offline wallet logic
│── sms-gateway/      # SMS integration module
│── partner-portal/   # NGO partner management tools
│── docs/             # Documentation & guides
│── examples/         # Example scripts & demos
