# CVE-2025-63896

## ⚔️ Attack Name
**< Wireless Key Stroke Injection on JXL Infotainment >**

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
- < Bluetooth Low Energy stack >  
- < Infotainment system input handler >  
- <Executable or service responsible for Bluetooth HID device connections>

### 🎯 Attack Vector
- <Remote / Local / Physical>  
- <Short An attacker within Bluetooth range can emulate a malicious HID device. Due to minimal pairing security (simple    Yes/No    confirmation), the device is accepted as a keyboard. Once connected, the attacker can inject arbitrary keystrokes to open browsers, visit malicious sites, or trigger infotainment functions without user consent>

### 🧩 Severity
- **CVSS Score:** <X.X>  
- **Impact:** <Confidentiality / Integrity / Availability>

### 📅 Timeline
- Discovery Date: <DD/MM/YYYY>  
- Vendor Notification: <DD/MM/YYYY>  
- Public Disclosure: <DD/MM/YYYY>

### 👨‍💻 Credits
- Researcher: <Shubham S. Thorat>

---

## 📜 References
- <Link 1>  
- <Link 2>  
- <Advisory / Vendor Patch Info>


