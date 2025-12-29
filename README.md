<p align="center">
  <img src="assets/zeronorth-logo.png" alt="Zero North Vault Logo" width="200"/>
</p>

<h1 align="center">Zero North Vault</h1>

<p align="center">
  Your personal 1-of-1 cipher engine. An offline cryptographic artifact, inspired by blockchain.
</p>

---

> **TL;DR**:
> If you're a random user: This is a secret encryption environment.
> For judges and cryptographers, Zero North Vault is a 1-of-1 unique cryptographic encryption environment that functions like an actual digital artifact, your own personal encryption language.

> **Vaulst generate a 1-of-1 offline `.exe` encryption UI that can only encrypt/decrypt *your* information.**

> No sync. No cloud. No verifier.  
> Just you, your passphrases, and a proof-sealed cryptographic object.
> Your own vault. Your own encryption. Your own language. Forever. 

### 🧬 What is it?

**For Consumers**:  
Zero North Vault (*ZeroNorthVault*) is your personal secret passcode generator.  
**ONLY you** own the `.exe` and the encryption logic. Store it locally. Use it offline.

- Pick a key word to use as the password for your string of text (infinite combinations), encrypt. Enter the same key word and string and decrypt.
- Each `.exe` is **cryptographically distinct**. It is **unable to be deciphered** using other user's vaults, unless theirs are identical builds.  
- The only way to decrypt what it encrypts is through owning the machine output (.exe seeded program) itself.

**Zero North Vault (zkVault)** is a dark-mode, black-box, air-gapped, artifact-bound symmetric encryption app. 

Each vault:
- Is cryptographically unique  
- Can’t decrypt any other vault’s data  
- Includes a merkle-like `vaultproof.json` (for proof of individuality)

Good for:  
Keeping your own personal encryption language on a USB stick.  
Encrypting data in a country where you're compromised, and decrypting it with a backup on your desktop at home.  
A language only you (or a loved one you shared the program with) can ever speak.  

**Nobody can recover your vault. You don’t own an account. There is no sync. No recovery. You are interacting with a physical cryptographic object.**

---

### Core Innovation

Individualized cryptographic AES UX objects.

> 🔻 You don’t store secrets in the cloud.  
> 🔺 Zero North _generates_ an little universe for your secrets.

Zero North Vault flips the security model a bit and gives you the tools to protect yourself.

### Lose the `.exe`, and no one — not even you — can recover the data.  
### That’s the point.

---

### 🔐 How it works

Every `.exe` is generated with:

- A high-entropy cryptographic seed  
- Custom AES runtime logic
- A static build timestamp embedded at generation time (`vault-genesis.txt`)  
- A SHA-256 logic fingerprint (`vaultproof.json`)  

You receive:
- A .zip that packs up your encryption `.exe`  
- A proof-of-build artifact  
- A unique cipher engine that runs fully offline

---

### Usage

This repo contains the **frontend only, sorry.**.

To use the full system:
1. Check the demo vaults in my deployments
2. Encode or decode strings using your `.exe`  
3. Optionally verify build authenticity using `verifyProof.js`  

---

### Note to the pros: 

The idea was an applied 'genesis block' style framework injected into the actual runtime logic of each cryptographic environment.

To verify:
Move verifyProof.js into your /vaultproof/ directory and run it via
node verifyProof.js

It confirms the artifact's logic fingerprint, timestamp, and seed integrity.

This reminds me of those spy tools from when I was a kid, kind of.

---

### 🔒 Ownership & Status

- Created by [**0north.eth**](https://github.com/0north-eth)  
- Built for the **Bolt Prompt Generation Hackathon**  
- **Patent Pending**  
- **Frontend is source-visible** (Apache 2.0)  
- **Encryption backend is closed-source and proprietary**


---

### 🧾 License

This frontend is licensed under [Apache 2.0](LICENSE.md).  
Backend logic is proprietary and not included in this repository.

---

### 🧬 Credits

Crafted by [**0north.eth**](https://github.com/0north-eth)  
Strategic advisor for zk-gaming systems, $40k to charity, researching cryptography.
---

> _"Blue lightsabers."_ 💙
> — 0north

