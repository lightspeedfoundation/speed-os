# Privacy Policy — Speed OS (Chrome Extension)

**Version 1.0 | Last updated: 4/11/2026

---

## 1. Overview

Speed OS is a Chrome extension that replaces your new tab page with a Speed wallet and command interface. This policy explains clearly and concisely what data is processed when you use it, where that data goes, and what control you have over it.

**Operator:** Lightspeed Foundation  
**Contact:** t.me/lightspeed_coin

---
 
## 2. Scope
 
This policy covers the **Speed OS Chrome extension** (and Chromium-based equivalents). It does not apply to:
 
- The Speed CLI when run outside the extension
- Third-party websites or services you access through your browser
- External service providers referenced in §5 (each governed by their own policies)
 
---
 
## 3. What Speed OS Does
 
Speed OS enables you to:
 
- Store an encrypted trading wallet locally in your browser
- Execute Speed commands from a new tab interface (natural language or terminal)
- Access optional features including token swaps, cross-chain bridges, on-chain reads, Hyperliquid integration, and token discovery
 
---
 
## 4. Data We Process
 
### 4.1 Stored Locally on Your Device
 
All of the following lives in Chrome extension storage (`chrome.storage.local` / `chrome.storage.session`) and **never leaves your device** as part of normal extension operation:
 
| Data | Purpose |
|---|---|
| **Encrypted wallet vault** | Stores cryptographic material in encrypted form. Your private key is not transmitted to our servers. |
| **Public wallet address** | Displayed in the UI after you unlock your wallet. |
| **Session state** | Keeps you unlocked across new tabs until you lock or close the browser. |
| **Settings & UI preferences** | Theme, font, background, panel layout, and similar. |
| **Saved token aliases** | Tickers and contract addresses you've saved for use in commands. |
| **Suggestion/ranking data** | Locally computed frequency and recency models for personalizing command suggestions. |
 
> **Your private key is never transmitted outside your device.**
 
---
 
### 4.2 Data Sent Over the Network
 
When you run commands or load data, the extension contacts third-party services on your behalf. These requests are necessary for the features to function — they are not used for advertising or tracking.
 
| Service Category | What's Sent | Why |
|---|---|---|
| **MCP host** (your configured server) | Configuration requests | Fetches encrypted environment material for the CLI merge flow |
| **DEX / routing providers** | Quote and route parameters | Powers swap and bridge features |
| **Blockchain RPC / indexer providers** | Read requests, transaction data | On-chain reads and transaction flows |
| **Token discovery providers** | Token identifiers | Resolves and suggests tokens in the UI |
| **Perpetuals / derivatives providers** | Command parameters | Powers supported trading panels and commands |
 
Each of these providers is subject to **their own privacy policy**, not this one. We recommend reviewing their policies for any services you use frequently.
 
---
 
### 4.3 Notifications
 
Extension notifications are used solely for local feedback about extension events (e.g. a transaction completing). They are not used to deliver third-party advertisements.
 
---
 
## 5. MCP & API Environment
 
When you enable MCP, the extension retrieves encrypted environment payloads from your configured MCP server and merges non-wallet API variables into the in-browser runtime. This process is designed so that your wallet's private key is **never overwritten or exposed** during the merge.
 
The security and data practices of your MCP server are governed by that server's own terms.
 
---
 
## 6. Network Request Modification
 
Speed OS may modify certain HTTP request headers to ensure compatibility with services you have configured. This is scoped strictly to declared rules and **does not affect** other websites you visit.
 
---
 
## 7. Legal Basis for Processing
 
Where GDPR or equivalent regulations apply, we process data on the basis of:
 
- **Contract / service performance** — operating the extension you have installed
- **Legitimate interests** — securing and improving the extension, balanced against your rights
 
---
 
## 8. Data Retention
 
| Location | Retention |
|---|---|
| **Your device** | Persists in extension storage until you uninstall the extension, clear browser data, or use in-app controls (e.g. lock wallet, delete saved items). |
| **Our servers** | If you use the extension without creating an account with us, we do not receive personal data directly from the extension. |
| **Third-party APIs** | Retained per each provider's own policy. |
 
---
 
## 9. Security
 
We use encryption for vault storage and restrict sensitive operations to the extension's isolated context. No storage or transmission method is 100% secure. You are responsible for your own device security and for guarding against phishing attacks.
 
---
 
## 10. Children
 
Speed OS is not intended for anyone under the minimum age required by their jurisdiction to use financial or cryptocurrency-related software. We do not knowingly collect personal information from minors.
 
---
 
## 11. International Users
 
Speed OS is available globally. Any data processed by third-party service providers may transit or be stored in other jurisdictions.
 
---
 
## 12. Your Choices & Rights
 
You have meaningful control over your data:
 
- **Uninstall** the extension to remove all locally stored extension data (subject to your browser's data clearing behavior)
- **Lock or clear** your wallet and saved data using in-app controls
- **Limit exposure** by not configuring optional third-party services you don't trust or need
- **Contact us** at t.me/lightspeed_coin to exercise any rights you may have under applicable law (e.g. access, deletion, correction)
 
---
 
## 13. Changes to This Policy
 
We may update this policy from time to time. Material changes will be communicated via github and, where required, a notice in the Chrome Web Store listing or within the extension itself.
 
---

## 14. Contact

For privacy questions or requests:
t.me/lightspeed_coin
