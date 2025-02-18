<img width="1448" alt="BeyondLife" src="https://github.com/user-attachments/assets/c3562110-05b5-4c85-9a19-03bf19a1b185">


# 💡 BeyondLife: Third-Party Digital Will Application 💻

[![Expo](https://img.shields.io/badge/Expo-Demo-green)](https://expo.dev/accounts/xinzhang9091/projects/digitalWill/builds/ab94c5f5-80aa-4059-ad8f-279980712374)
[![React Native](https://img.shields.io/badge/React%20Native-Framework-purple)](https://reactnative.dev)
![License: MIT](https://img.shields.io/badge/license-MIT-lemo)



✨ Welcome to **BeyondLife**, an innovative prototype app that transforms the concept of a digital legacy into a simplified interactive experience. The project aims to explore the future of posthumous data management, making it simple and easy to set up, manage, and securely share a digital will. 🔒

This repository provides an open-access implementation related to our research paper submitted to [WWW25](https://www2025.thewebconf.org) (International World Wide Web Conference 2025). It contains a lightweight prototype that demonstrates key functionalities discussed in the paper below.

> **"BeyondLife: Third-Party Digital Will Application"**\
> *Xinzhang Chen, Arash Shaghaghi, Jesse Laeuchli and Salil S. Kanhere*\
> *Published at WWW Companion '25*\
> [Read it on ACM DL](https://doi.org/10.1145/3701716.3715168)


For a quick overview, please refer to the [📸 screenshots](#screenshots) and [🎥demo video](#demo-video) below.

---

## 🌟 Key Features

- 🧭 **Interactive Will Setup**  
  Embark on a guided and fun journey to add heirs, assign permissions, and craft your digital legacy in just a few clicks.

- 🔗 **Cross-Platform Integration**  
  Easily connect to platforms like Google Drive and Twitter to manage and secure your digital treasures.

- 🎨 **Visually Intuitive Design**  
  Built with simplicity in mind—whether you're a tech whiz or not, BeyondLife has you covered!

- 🔒 **Privacy-Focused Security**  
  No leaks, no risks! Your data stays encrypted and accessible only to your trusted recipients.
  In BeyondLife, we implemented and integrated a customized Attribute-Based Encryption (ABE) scheme, called PD-CP-ABE (Partially Decryptable Ciphertext Policy Attribute-Based Encryption).


✨ **Explore the PD-CP-ABE Implementation:** [Visit the PD-CP-ABE Repo](https://github.com/Xinzhang-Chen/BeyondLife_PD-CP-ABE)

#### Encryption Performance Comparison of PD-CP-ABE and bsw07

| **File Size (Files)** | **PD-CP-ABE (s)** Avg Time | **PD-CP-ABE (s)** Std Dev | **bsw07 (s)** Avg Time | **bsw07 (s)** Std Dev |
|-----------------------|---------------------------|---------------------------|------------------------|-----------------------|
| **5**                 | 0.1652                   | 0.0532                    | 0.1513                | 0.0047                |
| **160**               | 0.8574                   | 0.0057                    | 3.6726                | 0.0239                |
| **1500**              | 0.8719                   | 0.0169                    | 31.5530               | 0.1992                |


---

## Demo Video

🎬 Watch a quick **BeyondLife** demonstration:  

https://github.com/user-attachments/assets/f86febd1-15be-4c5a-bfeb-838b4e7e32ac

---

## Try in Practice

📱 Want to see it in action? Access the live demo now via Expo:

👉 **[🚀 Launch the Demo](https://expo.dev/accounts/xinzhang9091/projects/digitalWill/builds/ab94c5f5-80aa-4059-ad8f-279980712374)** 👈

> **Note**: As this is a prototype, performance may vary based on your device and network speed.  
> Additionally, the backend server is deployed on a personal desktop and may not be available 24/7.

Via **local installation**:  

- 📲 **Android** → [Download Here]()  
- 🍏 **iOS** → [Download Here]()  
---


## 🔮 Future Potential

While BeyondLife is already paving the way for digital legacy management, there's always room to grow! Here’s what could be next:

1. 🤖 **AI-Assisted Guidance**  
   Let AI simplify complex setups and guide you through estate planning like a pro.

2. 🌐 **Expanded Platform Support**  
   Add integrations for services like Dropbox, Instagram, and more.

3. 📜 **Legal Compliance**  
   Align the app with international legal standards to make your digital will enforceable across borders.

4. 🌈 **Personalized Experiences**  
   Offer customizable themes and tailored recommendations for a more personal touch.

---

## ⚠️ Disclaimer

This repository contains **no source code**—it serves solely as a demonstration resource for the **BeyondLife** prototype hosted via Expo, and pre-built Android and iOS bundles are also available for local installation.

🔍 **BeyondLife** is designed for research and concept exploration. It is **not intended for production use** or the management of sensitive personal data. Evaluate and enjoy this app as a prototype, not as a finalized product. 

---

❗️ **Demo Version Details**:

The current demo version is a **simplified version** of the full application. It currently supports setting up a digital will for **X (formerly Twitter)**, while support for **Gmail** and **Google Drive** will be included in the full version.  

To ensure **data security for demo users** (e.g., avoiding accidental deletion of personal tweets), the demo allows users to link their private Twitter accounts but does **not use the authorized token** to retrieve or modify any data. Instead, predefined **sample tweets** are provided for testing purposes.

However, the **cloud storage link is fully functional** in this demo version. During interactions, **BeyondLife** will upload encrypted data to the demo user’s cloud storage.


---


## Screenshots

Take a look at some screenshots of BeyondLife in action!

<div align="center">


### User Login and Registration
<img src="https://github.com/user-attachments/assets/00a3256a-28f1-4454-a099-5e3e68caf6d8" alt="Heir Config 1" width="250">
<img src="https://github.com/user-attachments/assets/715ad89c-8afb-490f-83ca-77225fde0a10" alt="Heir Config 2" width="250">
<img src="https://github.com/user-attachments/assets/ba76aac4-d65b-47d9-97ed-4b65224af8a4" alt="Heir Config 3" width="250">

### Connect to Cloud Platforms
<img src="https://github.com/user-attachments/assets/c62d82d0-941d-4152-8fa8-4301aa2effc2" alt="Heir Config 3" width="250">
<img src="https://github.com/user-attachments/assets/d641e9a0-8d6a-4cbd-9c5f-9fae41c80ebb" alt="Heir Config 2" width="250">
<img src="https://github.com/user-attachments/assets/337efa98-302a-45f4-bac3-fe30e7224ec9" alt="Heir Config 1" width="250">


### Heir Configuration  
<img src="https://github.com/user-attachments/assets/f7840060-7d73-4da6-9684-e62f8649d59a" alt="Heir Config 1" width="250">
<img src="https://github.com/user-attachments/assets/f726caef-1f82-47ab-b8c8-ffb392eeedf8" alt="Heir Config 2" width="250">
<img src="https://github.com/user-attachments/assets/75918d5f-22a5-4766-8c73-e68b2d199e62" alt="Heir Config 3" width="250">

<img src="https://github.com/user-attachments/assets/431c1dbc-fea0-4c6f-b75c-cd27f79821cf" alt="Heir Config 2" width="250">
<img src="https://github.com/user-attachments/assets/ad73c491-d318-4d61-9e61-0123d33c7f94" alt="Heir Config 3" width="250">
<img src="https://github.com/user-attachments/assets/44231f9e-0b8e-4110-82f1-c1bae541e0af" alt="Heir Config 3" width="250">


### Interactive Will Setup  
<img src="https://github.com/user-attachments/assets/b7f53b02-b8f6-42f5-a8e3-40068ac69bb6" alt="Will Setup 1" width="250">
<img src="https://github.com/user-attachments/assets/c7fc557d-e260-4ada-9237-c215902bfa3e" alt="Will Setup 2" width="250">
<img src="https://github.com/user-attachments/assets/bc01738d-cda4-4f40-8606-b024c66c60ba" alt="Will Setup 3" width="250">

<img src="https://github.com/user-attachments/assets/a9f992c4-144c-401c-8d5b-5ec256c8390c" alt="Will Setup 1" width="250">
<img src="https://github.com/user-attachments/assets/2bdfbe6e-56cf-4db3-aab6-72689e491663" alt="Will Setup 2" width="250">
<img src="https://github.com/user-attachments/assets/f842d61e-467a-4d98-8482-3d5d54ce1f86" alt="Will Setup 3" width="250">

<img src="https://github.com/user-attachments/assets/62de8a8e-23de-4631-b92a-a3d0e914bee1" alt="Will Setup 1" width="250">
<img src="https://github.com/user-attachments/assets/8e4d0284-7dfd-4950-b7a8-b13de47c4a8d" alt="Will Setup 2" width="250">
<img src="https://github.com/user-attachments/assets/c846992b-3f8d-42b0-a33c-37c4a3e9ff44" alt="Will Setup 3" width="250">



### Will Activation and Accessing inherited data
<img src="https://github.com/user-attachments/assets/a046553d-4c6a-4bcb-94ed-541bdc1f4076" alt="Data Upload 1" width="250">
<img src="https://github.com/user-attachments/assets/bc1259a5-04dd-40bd-a414-747cb71e68e7" alt="Data Upload 2" width="250">
<img src="https://github.com/user-attachments/assets/d6499574-1c95-463b-9993-5b2494a6db4b" alt="Data Upload 3" width="250">
<img src="https://github.com/user-attachments/assets/456a65f7-a542-48d2-8f71-f2ef339f8534" alt="Data Upload 3" width="250">
<img src="https://github.com/user-attachments/assets/8860c4fe-3634-47ba-8c4a-b1959b222f64" alt="Data Upload 3" width="250">

</div>


---

## 🚀 Ready to Secure Your Digital Legacy?

Click below to take the first step toward simplifying your posthumous data management:

👉 **[Try the Demo Now!](#try-in-practice)** 👈
