# cyber-lab4
# 🔍 Vulnerability Scanning using Nessus and OpenVAS (Lab 4)
### 1. 🔎 Basic Vulnerability Scan using Nessus
A basic vulnerability scan was performed on the target system `192.168.63.134` using Tenable Nessus Essentials.

📸 **Scan Overview**  
<img width="1440" alt="Screenshot 1" src="https://github.com/user-attachments/assets/eb8fe5fa-d91b-4fad-bd36-8bd89f920834" />

### 2. 📊 Analyzing Scan Results

The scan returned several vulnerabilities classified by severity:

- **Critical**: 10
- **High**: 7
- **Medium**: 9

  <img width="1440" alt="Screenshot  2" src="https://github.com/user-attachments/assets/c9a15200-bd7e-4515-9e68-08e89bdc92df" />

  <img width="1440" alt="Screenshot " src="https://github.com/user-attachments/assets/7495f440-9e7d-4e3e-8464-6c7554864dc9" />


  - **rlogin Service Detection**  
  - **Plugin ID**: 10205  
  - **Description**: rlogin service is detected which allows unauthenticated remote access.  
  - **Risk**: High  
  - **CVE**: CVE-2008-0166
    
<img width="1440" alt="Screenshot 3" src="https://github.com/user-attachments/assets/9bbdeb40-c990-4711-988c-fac161ca002c" />


- **Debian OpenSSH/OpenSSL Random Number Generator Weakness**  
  - **Plugin ID**: 32314  
  - **CVE**: CVE-2008-0166  
  - **Description**: Weak key generation due to a flaw in Debian’s OpenSSL package.  
  - **Risk**: Critical
    <img width="1440" alt="Screenshot4" src="https://github.com/user-attachments/assets/67484dfd-b300-479c-8816-a4daf81650cb" />


- **SSL Medium Strength Cipher Suites Supported (SWEET32)**  
  - **Plugin ID**: 42873  
  - **CVE**: CVE-2016-2183  
  - **Description**: The system supports 64-bit block ciphers (like 3DES) which are vulnerable to the SWEET32 attack.  
  - **Risk**: High  
<img width="1440" alt="Screenshot 2025-05-11 at 18 44 36" src="https://github.com/user-attachments/assets/3e67a039-7bd9-4114-b33d-43841b7f2fe4" />

<img width="1440" alt="Screenshot 2025-05-11 at 18 44 44" src="https://github.com/user-attachments/assets/c7270ed1-5349-4281-8057-97bd62d56667" />


