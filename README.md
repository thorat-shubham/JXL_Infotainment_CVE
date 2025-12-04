# CVE-2025-63896

## ⚔️ Attack Name
### <span style="color:#2ECC71; font-weight:bold;">
Wireless Keystroke Injection on JXL Infotainment
</span>

---

## 📘 Description
A vulnerability was identified in **<Component / System / Version>** where **<brief technical explanation of flaw>** occurs.  
The issue originates from **<root cause / weakness>**, enabling an attacker to **<high-level effect or capability>** under specific conditions.  
This vulnerability affects **<affected devices/versions>** when **<scenario or trigger>**.

---

## 📂 Additional Details (Optional Sections)

### Afftected product
- < JXL 9 Inch Car Android Double Din Player - Android version 12.0 >

### 🔎 Affected Components
- Bluetooth Low Energy stack 
-  Infotainment system input handler  
- Executable or service responsible for Bluetooth HID device connections

### 🎯 Attack Vector
- <Remote>  
- Short An attacker within Bluetooth range can emulate a malicious HID device. Due to minimal pairing security (simple    Yes/No    confirmation), the device is accepted as a keyboard. Once connected, the attacker can inject arbitrary keystrokes to open browsers, visit    malicious sites, or trigger infotainment functions without user consent


### 👨‍💻 Credits
- Researcher: `Shubham S. Thorat`


## 📜 References
- <Link 1>  



