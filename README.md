# CVE-2025-63896

##  Attack Name
![Attack](https://img.shields.io/badge/Attack-Wireless_Keystroke_Injection_on_JXL_Infotainment-blue?style=for-the-badge)


---

## 📂 Additional Details (Optional Sections)

### Afftected product
- < JXL 9 Inch Car Android Double Din Player - Android version 12.0 >

###  Affected Components
- Bluetooth Low Energy stack 
-  Infotainment system input handler  
- Executable or service responsible for Bluetooth HID device connections

###  Attack Vector
 
- Short An attacker within Bluetooth range can emulate a malicious HID device. Due to minimal pairing security (simple    Yes/No    confirmation), the device is accepted as a keyboard. Once connected, the attacker can inject arbitrary keystrokes to open browsers, visit    malicious sites, or trigger infotainment functions without user consent


### Credits
- Researcher: `Shubham S. Thorat`


## 📜 References
- CVE-2025-63896 [Report](https://github.com/thorat-shubham/JXL_Infotainment_CVE/blob/main/JXL_Infotainment_CVE-2025-63896.pdf)

## POC
![Demo GIF](https://github.com/thorat-shubham/JXL_Infotainment_CVE/blob/main/Attack_POC.gif)




