# Endpoint Management Project - Greenlight MSP

Learning and implementing device management solutions at Greenlight MSP using Microsoft Intune and Endpoint Central.

## Project Background
- **Company:** Greenlight MSP
- **Role:** IT Support Technician
- **Challenge:** Managing client devices remotely and efficiently  
- **Learning Goal:** Master modern endpoint management tools

## What I'm Working With
- **Microsoft Intune** - Device enrollment and policy management
- **Endpoint Central** - Remote support and troubleshooting
- **Hyper-V** - Testing lab for different configurations
- **PowerShell** - Automation scripts (still learning!)
- **Microsoft 365** - User and device integration

## Daily Tasks at Greenlight MSP
- ✅ Enroll client devices into Intune management
- ✅ Configure compliance policies for different client requirements
- ✅ Use Endpoint Central for remote troubleshooting
- ✅ Create basic PowerShell scripts for routine tasks
- ✅ Document processes for other team members

## PowerShell Scripts I'm Learning
```powershell
# Get device compliance status
Get-IntuneManagedDevice | Select-Object DeviceName, ComplianceState, LastSyncDateTime

# Check Windows Update status
Get-WUList | Where-Object {$_.Size -gt 0}

# Export device inventory
Get-ComputerInfo | Export-Csv -Path "DeviceInventory.csv"
```

## Real-World Experience
- Managing devices for 20+ SMB clients at Greenlight MSP
- Learning to balance security requirements with user productivity
- Troubleshooting connectivity issues and policy conflicts
- Building documentation and training materials

## Files Available
- 📄 **Device_Management_Report.docx** - Monthly client device status
- 📋 **PowerShell_Scripts.docx** - Collection of useful automation scripts
- 📊 **Policy_Templates.docx** - Standard Intune policies we use

---
*Hands-on learning experience at Greenlight MSP managing real client environments and developing practical IT skills.*
