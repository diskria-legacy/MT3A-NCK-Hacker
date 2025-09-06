# 🔓 MT3A-NCK-Hacker (2016)

Experimental Android app built in 2016 during my first steps in reverse-engineering and telephony tinkering.  
It was designed for the **Megafon Login 2 MT3A** tablet to calculate NCK unlock codes from IMEI and explore hidden telephony APIs.

## ✨ Features

- Input 15-digit IMEI → app generates an NCK code  
- Simple offline algorithm (digit sums and rearrangements)  
- Planned auto-detection of IMEI/ICCID from SIM card (unfinished `getIccCard` task)  
- Extra screen with a progress bar and attempt to call `PhoneFactory.makeDefaultPhone` for experiments  

## 📦 About this project

This app was created in **AIDE** on a phone, as a learning project around SIM locks and Qualcomm devices.  
It is not functional anymore beyond the calculator, but preserved here as a piece of history and early reverse-engineering practice.

## 📸 Screenshots

<p align="center">
  <img src="https://github.com/user-attachments/assets/2b72a2c9-b05f-4b39-8385-b739c2e4c409" width="200" />
</p>

## 🛑 Disclaimer

This project was an **educational experiment** and is preserved for archival purposes only.  
It is not intended for real-world unlocking or bypassing carrier restrictions.
