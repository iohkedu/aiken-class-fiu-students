# 📘 Aiken Smart Contract Development — Course Curriculum

Welcome to the **Aiken Smart Contract Development Course**, designed to guide students from zero knowledge to building real-world on-chain logic on the **Cardano blockchain**.

This curriculum organizes the video lessons into themed modules with clear progression and learning objectives.

---

## 📌 **Course Overview**

Aiken is a modern, developer-friendly language created to build smart contracts for Cardano.

In this course, students learn:

- The EUTxO model  
- On-chain and off-chain components  
- Aiken syntax, types, and functional patterns  
- Smart contract architecture  
- DApp development with MeshJS  
- Oracles, minting, validators, and transaction design  
- Web2 → Web3 integration  
- CIP-30 wallet interactions  

---

## 🧩 **Prerequisites**

- Basic programming experience (any language)  
- Understanding of functional concepts is helpful but not required  
- Node.js + Aiken installed  
- A Cardano testnet wallet  
- Recommended: familiarity with blockchain fundamentals  

---

## 📘 **Learning Outcomes**

By the end of the course, students will:

✅ Understand Cardano’s extended UTxO model  
✅ Write complete validators in Aiken  
✅ Build minting policies  
✅ Use MeshJS to create frontend-driven transactions  
✅ Read and validate transaction context  
✅ Work with oracles  
✅ Integrate Web3 wallets with CIP-30  
✅ Deploy real DApps on Cardano testnets  

---

## 🗣️ Note About Video's Language

The lectures in this course were recorded in Spanish and automatically dubbed into English using artificial intelligence. Some videos marked with an asterisk (`*`) couldn't be automatically translated, so English subtitles are provided instead.

---

## 📚 **Course Modules**

### **Module 1 — Foundations of Cardano & Smart Contracts**

#### 🎯 *Learning Objectives*

- Understand the Extended UTxO (EUTxO) model  
- Know how Cardano smart contracts differ from other blockchains
- Distinguish on-chain vs off-chain components  

#### 🎥 *Lessons*

1. [EUTxO Model](https://youtu.be/uy5bhqifld4?si=JKxqXFd6YEXWua2q)  
2. [On-chain Code](https://youtu.be/7e0KLuwLVVg?si=mRQR8qUyWjA3YDH8)*  
3. [Off-chain Code](https://youtu.be/EOz7k-KmxFc?si=6N0yRkSGAvriLmtz)  
4. [Native Scripts](https://youtu.be/icl7jCqxZWw?si=U2_elnsD5okIUs37)*  

---

### **Module 2 — Building DApps with MeshJS**

#### 🎯 *Learning Objectives*

- Understand how frontends interact with the blockchain  
- Work with MeshJS transaction builders  
- Execute simple on-chain actions from MeshJS

#### 🎥 *Lessons*

5. [Introduction to MeshJS](https://youtu.be/TVFxwD0zHhA?si=Bl0zDfKtIwjulaUy)  
6. [Simple Transactions with MeshJS](https://youtu.be/5I82AMY-D4c?si=S59uLPYodyqSbIxc)

---

## **Module 3 — Aiken Language Basics**

#### 🎯 *Learning Objectives*

- Set up an Aiken project  
- Learn the basics of the language syntax  
- Work with primitive types, variables, functions  

#### 🎥 *Lessons*

7. [Creating a Project in Aiken](https://youtu.be/ej2iRPDpUSo?si=sVlMrOjdCacrLGsM)  
8. [Introduction to Aiken](https://youtu.be/rcoby9c--N4?si=8qCyBq2UrFMtrUmB)  
9. [Primitive Types](https://youtu.be/XKdfaXU772I?si=0gaEP7f1G1LZEWn0)*  
10. [Variables and Constants](https://youtu.be/jDK7Vy9MLrI?si=aU6DItcsfETJJ2tY)  
11. [Functions](https://youtu.be/GTWt0juaiVI?si=rR7nLqm3vDhalUQ2)  
12. [Custom Types](https://youtu.be/SOxdozBlin8?si=Zq3L_G-3v_LGmSRZ)  
13. [Control Structures](https://youtu.be/pt1zahI1_1w?si=WoCI9DurjFZZbs0v)  
14. [Effects](https://youtu.be/bSuFiX2WY1A?si=6SdKhfJuoNe09HAq)  
15. [Modules](https://youtu.be/EMFo9YK-jkQ?si=tJZ_MzfVIOqmOLD5)  

---

## **Module 4 — Plutus Validators with Aiken**

#### 🎯 *Learning Objectives*

- Understand how validators run in Cardano  
- Build complete validator scripts in Aiken  
- Apply transaction context and determinism principles  

#### 🎥 *Lessons*

16. [Plutus Scripts (Validators)](https://youtu.be/2BA00Qnrvm8?si=4j05ni68EVKjlKIW)  
17. [Purposes of Plutus Scripts](https://youtu.be/eyZd7y5p3CE?si=HWxm91QAhUmmkFMR)*  
18. [Building a Validator](https://youtu.be/ebXEHbjFAHk?si=1EtJk7kc0XmOulge)*  
19. [Transaction Context](https://youtu.be/V98csJU0KFw?si=mzrD6Xd_7beQx8r6)  
20. [Determinism](https://youtu.be/A07xJq-YcrQ?si=sGtT2SaA6M-eQLvp)  

---

## **Module 5 — Real Smart Contracts in Aiken**

#### 🎯 *Learning Objectives*

- Implement common patterns: multisig, time locks, spending policies  
- Build minting policies  
- Understand state transitions  

#### 🎥 *Lessons*

21. [Validator: Sign to Unlock](https://youtu.be/0du0KVWS9qQ?si=Tif5_LsO1hNZh60F)  
22. [Vesting](https://youtu.be/xX-bY7RygLE?si=Aa4DUrreYj7xiKvg)*  
23. [Minting Policy](https://youtu.be/rQQWcUpfr-o?si=RMcYrYsgyWE0eLpl)  
24. [Example of a Minting DApp](https://youtu.be/m5yBy0lYYaQ?si=mDmylIbyMolBUabu)  

---

## **Module 6 — Oracles & Advanced DApps**

#### 🎯 *Learning Objectives*

- Understand oracle patterns  
- Build and consume oracle data on-chain  
- Architect full DApps combining front-end and validator logic  

#### 🎥 *Lessons*

25. [Introduction to Oracles](https://youtu.be/t1hcV82LEHI?si=7mXiTE5MfWkYQEsC)  
26. [Oracle Example in Aiken](https://youtu.be/5MJofyoow5c?si=ZAQe_SrqMK_1VPsp)*  

---

## **Module 7 — Web3 Integrations**

#### 🎯 *Learning Objectives*

- Understand how Web2 apps evolve into Web3  
- Implement wallet interactions using CIP-30  
- Build simple full-stack Cardano applications  

#### 🎥 *Lessons*

27. [From Web2 to Web3](https://youtu.be/r7hNf-Cudwk?si=J4e6yk6D5bGzkOT-)  
28. [CIP-30 and Signing Transactions with Browser Wallets](https://youtu.be/TCYduiBUnok?si=xreybhbtzLctKPNl)  

---

## 🤝 Contributing

Pull requests, suggestions, and improvements are welcome! This curriculum is meant to evolve as Aiken and Cardano mature.
