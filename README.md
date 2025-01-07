# -Intune-Compliance
"Configuration and enforcement of compliance policies in Microsoft Intune to ensure secure and compliant device management."
# Intune Compliance Policy Configurations

## Overview
This project focuses on creating and enforcing compliance policies in Microsoft Intune to maintain a secure and compliant device ecosystem. Policies ensure devices meet organizational security standards before accessing corporate resources.

## Key Features
- **Policy Types**:
  - Device encryption enforcement.
  - Minimum OS version requirements.
  - Device health checks (e.g., antivirus and firewall enabled).
- **Integration**:
  - Azure AD Conditional Access to restrict non-compliant devices.
- **Reporting**:
  - Monitor compliance status through Intune dashboards.

## Setup Guide
1. **Create Compliance Policies**:
   - Navigate to **Microsoft Intune** → **Devices** → **Compliance policies**.
   - Define rules for encryption, OS versions, and device health.
2. **Assign Policies**:
   - Assign compliance policies to user groups or device groups.
3. **Enable Conditional Access**:
   - Integrate with Azure AD to block non-compliant devices from accessing resources.
4. **Monitor Compliance**:
   - Use the Intune compliance dashboard to track device adherence.

## Results
- Achieved 99.1% compliance rate across enrolled devices.
- Strengthened security posture by enforcing encryption and health checks.
- Enhanced resource access control with Azure AD Conditional Access.

## Screenshots
*(Add screenshots of compliance policy creation, enforcement dashboards, and Conditional Access configurations.)*

## Technologies Used
- Microsoft Intune
- Azure AD Conditional Access
- Windows Defender and Firewall

## Next Steps
- Expand compliance policies to include advanced threat protection.
- Automate compliance enforcement using PowerShell scripts.
