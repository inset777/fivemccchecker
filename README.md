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
```

### 4. Run the Script
```powershell
.\insetchecker.ps1
```

### 5. View the Automated Reports
- The script automatically creates an output folder in the same location, for example:  
  `INSETCHECKER_bd4b49c0-9de4-49cc-bafa-bc4b051503e6`
- Inside this folder, you will find all generated reports:
  - `forensic_log.txt`
  - `forensic_findings.txt`
  - `drivercheck.txt`
  - `datchecker.txt`
  - `reviewer_notes.txt`
  - `confidence_explanation.txt`
  - `evidence_heatmap.txt`
  - `LICENSE.txt`

---

## License

This product is proprietary and fully licensed to INSET.  
All rights reserved.

**Restrictions:**
- Do not copy, distribute, sell, or create derivative works from this script.  
- Use is limited to legal auditing and forensic review only.

---

## Important Notes
- Always run as administrator for full functionality.  
- The tool is non-invasive and does not modify system files or memory.  
- Do not move or modify the output folder while the script is running.  

---

## Tips
- Keep your PowerShell execution policy set to bypass temporarily only for running this tool.  
- Review the generated reports carefully—this tool provides insights, not verdicts.  
- The evidence heatmap helps visualize suspicious activity over time.  

---

## Quick Copy Commands
- Copy and paste the following directly into PowerShell:
