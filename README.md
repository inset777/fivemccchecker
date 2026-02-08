# FiveMCCChecker – INSETCHECKER

**INSETCHECKER** is a safe, evidence-based forensic correlation tool for Windows systems.  
It reconstructs execution history, inventories files, and identifies suspicious patterns in a transparent, non-invasive, and legal manner.  
This tool is intended for administrative auditing and forensic analysis only.

---

## How to Use

### 1. Place the Script
- Navigate to your main Windows drive (usually `C:\`).  
- Go to `C:\Users\<Administrator>` (replace `<Administrator>` with your admin account folder).  
- Place the `insetchecker.ps1` script in this folder.

### 2. Run PowerShell as Administrator
- Right-click **PowerShell** → **Run as Administrator**.

### 3. Set Execution Policy
- This allows the script to run temporarily.
```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
# Press "Yes to All" when prompted
