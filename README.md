# Atomic Red: T1059-Command and Scripting Interpreter Incident Response
In this lab project, I simulated a basic script execution attack by running an Atomic Red script called "AutoIt Script Execution" in a Azure Windows virtual machine. 
“Script execution attacks” are when a bad actor infects your endpoint with malware that uses a “script interpreter” (in this case, AutoIt.exe) to automatically launch malicious programs within the target machine, silently. This typically happens when you download this malware from a website or click a malicious link. In this lab, the “malicious program” that will be remotely launched by this attack will be Windows Calculator. Once the attack runs successfully, I then conduct an incident response investigation based on NIST 800-61 guidelines.


## 🔧 Tools and Frameworks Used In This Lab
- Azure Virtual Machines
- Microsoft Defender for Endpoint
- Microsoft Sentinel
- Wireshark 
- Powershell
- Atomic Red Scripts
- NIST 800-61 Incident Response

## 📄 Read the Full Documentation of this Lab Here

[![View Doc](https://docs.google.com/document/d/1WH6AjiFv9cjapxvi4Pab3rix_m7jloyh9HodT7M-JD8/edit?tab=t.u7qruuov4l97)
