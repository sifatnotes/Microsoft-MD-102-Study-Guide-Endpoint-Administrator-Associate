# Microsoft-MD-102-Study-Guide-Endpoint-Administrator-Associate
MD-102 study guide covering Microsoft Intune, Entra ID, Windows Autopilot, endpoint security, app management, Defender, Windows 365, automation, monitoring, and exam preparation.
```markdown
# Microsoft MD-102 Managing and Securing Microsoft 365 Endpoints Study Guide

## Introduction

The **Microsoft MD-102: Managing and Securing Microsoft 365 Endpoints by using Intune** exam validates skills for deploying, managing, securing, and optimizing Microsoft 365 endpoints.

The certification associated with MD-102 is **Microsoft 365 Certified: Endpoint Administrator Associate**. The current skills measured were updated on **July 24, 2026** and include Microsoft Intune, Microsoft Entra ID, Windows Autopilot, Microsoft Defender for Endpoint, Windows 365, Intune Suite, PowerShell, Microsoft Graph, automation, monitoring, and reporting.

This guide follows Microsoft's current published objectives. ([Microsoft Learn](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/md-102))

## Exam Overview

| Item | Details |
|---|---|
| Vendor | Microsoft |
| Certification | Microsoft 365 Certified: Endpoint Administrator Associate |
| Exam | MD-102 |
| Level | Intermediate |
| Product | Microsoft 365 |
| Role | Administrator |
| Passing Score | 700 or higher |
| Duration | 100 minutes |
| Exam Type | Proctored; interactive components may be included |
| Languages | English, Chinese (Simplified), German, Spanish, French, Japanese, Portuguese (Brazil) |
| Practice Assessment | Available |

Microsoft describes the target candidate as an endpoint administrator who manages devices and client applications using Microsoft Intune and agentic tools and workflows. ([Microsoft Learn](https://learn.microsoft.com/en-us/credentials/certifications/modern-desktop/))

## Who Should Take It?

MD-102 is suitable for professionals who:

- Manage Microsoft 365 endpoints
- Administer Microsoft Intune
- Deploy and configure Windows devices
- Manage Windows, macOS, iOS/iPadOS, and Android devices
- Implement endpoint security policies
- Manage applications and app protection
- Use Windows Autopilot
- Work with Microsoft Entra ID
- Use Microsoft Defender for Endpoint
- Manage Windows 365 Cloud PCs
- Automate endpoint administration with PowerShell and Microsoft Graph
- Monitor endpoint health and performance

Microsoft recommends experience with Microsoft Entra ID, Intune, Windows client and non-Windows device management, Microsoft Security Copilot, Intune agents, and Microsoft Defender XDR.

## Exam Objectives / Domains

Microsoft's current MD-102 study guide contains five domains. ([Microsoft Learn](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/md-102))

### 1. Prepare Infrastructure for Devices — 20–25%

Study:

- Microsoft Entra device registration and join
- Device join types
- Dynamic device groups
- Intune enrollment settings
- Windows automatic enrollment
- macOS and iOS/iPadOS enrollment
- Android enrollment profiles
- Apple Business Manager
- Samsung Knox Mobile Enrollment
- Google Zero Touch
- Intune and Windows 365 roles
- Scope tags
- Scoped administration
- Multi-admin approval
- Compliance policies
- Conditional Access
- Windows Hello for Business
- Windows LAPS
- Local group membership

### 2. Manage and Maintain Devices — 25–30%

Study:

**Windows deployment**
- Windows Autopilot
- Autopilot deployment profiles
- Device preparation policies
- User-driven deployment
- Pre-provisioning
- Self-deploying mode
- Enrollment Status Page
- Windows 11 upgrades
- Windows 365 provisioning
- Cloud PC network connections
- Image management
- Windows Backup and Restore

**Configuration**
- Windows configuration profiles
- ADMX templates
- Group Policy Analytics
- Android configuration profiles
- iOS/iPadOS configuration profiles
- macOS profiles
- Teams Rooms
- HoloLens 2
- Zebra specialty devices
- Assignment filters

**Intune Suite**
- Endpoint Privilege Management
- Enterprise App Catalog
- Remote Help
- Microsoft Cloud PKI
- Microsoft Tunnel
- Advanced Analytics

**Remote management**
- Sync
- Restart
- Retire
- Wipe
- Bulk device actions
- Defender Antivirus security intelligence
- BitLocker recovery-key rotation
- Local administrator password rotation
- KQL device queries
- Diagnostics and logs

### 3. Protect Devices — 15–20%

Study:

- Antivirus policies
- BitLocker and disk encryption
- Firewall policies
- Attack Surface Reduction
- Zero Trust endpoint protection
- Security baselines
- Microsoft Defender for Endpoint integration
- Endpoint Detection and Response
- Endpoint threat investigation
- Defender onboarding
- App Control for Business

**Device updates**
- Update rings
- Feature updates
- Quality updates
- Windows Autopatch
- Hotpatch
- iOS/iPadOS updates
- macOS updates
- Android updates
- Delivery Optimization
- Update monitoring

### 4. Manage and Secure Applications — 15–20%

Study:

- Application preparation
- Win32 applications
- Line-of-business applications
- Microsoft Store applications
- Android and iOS Quiet Time
- Microsoft 365 Apps deployment
- Office policies
- Office Deployment Tool
- Microsoft 365 Apps admin center
- Apple Volume Purchase Program
- Google Play
- App deployment monitoring
- Application troubleshooting
- App Protection Policies
- BYOD protection
- Conditional Access
- App Configuration Policies

### 5. Optimize Endpoint Operations by Using Automation, Monitoring, and Reporting — 10–15%

Study:

- PowerShell automation
- Microsoft Graph
- Security Copilot agents
- Endpoint management recommendations
- PowerShell compliance extensions
- Intune reporting
- Custom reports and filters
- Workbooks and dashboards
- Endpoint Analytics
- Proactive remediations
- Device health scores
- Application startup performance
- Endpoint reliability
- Tenant health
- Service health
- Message Center
- Operational baselines
- Alerts and notifications
- Compliance drift
- Enrollment failures
- Configuration conflicts

This fifth domain is part of the current July 24, 2026 exam update. ([Microsoft Learn](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/md-102))

## Detailed Study Notes

### Microsoft Intune

Understand Intune as the central platform for endpoint enrollment, configuration, compliance, application management, security, and monitoring.

Practice the relationship between:

**Device → Enrollment → Configuration → Compliance → Security → Applications → Monitoring**

### Microsoft Entra ID

Review:

- Device registration
- Microsoft Entra join
- Dynamic groups
- Conditional Access
- Device identities
- Role assignments
- Windows Hello for Business
- LAPS

### Windows Autopilot

Understand how Autopilot supports modern Windows deployment.

Know the differences between:

- User-driven deployment
- Pre-provisioning
- Self-deploying mode
- Deployment profiles
- Device preparation
- Enrollment Status Page

### Endpoint Security

Practice selecting the correct Intune security control for each scenario.

Important areas include:

- Antivirus
- Firewall
- BitLocker
- Attack Surface Reduction
- Security baselines
- Defender for Endpoint
- EDR
- App Control for Business

### Application Management

Understand how Intune manages applications across platforms.

Focus on:

- Win32 apps
- Microsoft Store apps
- LOB apps
- Microsoft 365 Apps
- App protection
- App configuration
- BYOD scenarios
- Deployment troubleshooting

### Automation and Monitoring

Understand how PowerShell, Microsoft Graph, Endpoint Analytics, proactive remediation, and Security Copilot can improve endpoint administration.

## Practical Examples / Labs

Practice these scenarios:

1. Enroll a Windows device into Intune.
2. Configure Microsoft Entra join.
3. Create a dynamic device group.
4. Configure Windows Autopilot.
5. Create an Enrollment Status Page.
6. Deploy a Windows configuration profile.
7. Configure a compliance policy.
8. Create a Conditional Access policy requiring compliance.
9. Configure Windows Hello for Business.
10. Configure Windows LAPS.
11. Deploy a Win32 application.
12. Configure an App Protection Policy for BYOD.
13. Configure BitLocker and recovery-key management.
14. Create an endpoint security baseline.
15. Integrate Microsoft Defender for Endpoint.
16. Configure Windows update rings.
17. Create an Endpoint Privilege Management policy.
18. Configure proactive remediation.
19. Use PowerShell or Microsoft Graph to automate Intune tasks.
20. Analyze endpoint health with Endpoint Analytics.

Microsoft recommends hands-on experience and provides a free Practice Assessment and exam sandbox. ([Microsoft Learn](https://learn.microsoft.com/en-us/credentials/certifications/modern-desktop/))

## Study Strategy

Use this sequence:

1. Read Microsoft's current MD-102 study guide.
2. Learn Intune and Entra ID fundamentals.
3. Practice device enrollment.
4. Master Windows Autopilot.
5. Study configuration and compliance.
6. Practice endpoint security.
7. Learn application deployment and protection.
8. Study Windows and cross-platform updates.
9. Practice PowerShell and Microsoft Graph.
10. Learn Endpoint Analytics and proactive remediation.
11. Explore Security Copilot and Intune agents.
12. Take the Practice Assessment.
13. Review weak domains.
14. Use the exam sandbox before scheduling the exam.

Spend significant study time on **device management**, the largest current domain at 25–30%.

## 30-Day Study Plan

| Days | Focus |
|---|---|
| 1–3 | MD-102 objectives, Intune, and Entra ID |
| 4–7 | Device registration, enrollment, groups, compliance |
| 8–12 | Windows Autopilot and Windows 365 |
| 13–15 | Configuration profiles and Intune Suite |
| 16–18 | Endpoint security and Defender |
| 19–21 | Windows and mobile device updates |
| 22–24 | Application deployment and app protection |
| 25–26 | PowerShell, Graph, automation |
| 27–28 | Endpoint Analytics, remediation, reporting |
| 29 | Practice Assessment and weak-area review |
| 30 | Final revision and exam sandbox |

## Common Mistakes

- Confusing Microsoft Entra registration with Microsoft Entra join
- Choosing the wrong Intune enrollment method
- Memorizing Autopilot modes without understanding use cases
- Ignoring Conditional Access and compliance relationships
- Confusing configuration policies with compliance policies
- Treating App Protection Policies as device configuration
- Overlooking Defender for Endpoint integration
- Ignoring non-Windows endpoint management
- Skipping PowerShell and Microsoft Graph
- Ignoring Endpoint Analytics and proactive remediation
- Studying outdated MD-102 objectives

## Exam-Day Tips

- Read the complete scenario before selecting an answer.
- Identify the device platform and management state first.
- For enrollment questions, determine ownership and enrollment requirements.
- For security questions, distinguish Intune policies from Defender capabilities.
- For application questions, identify the app type and target platform.
- For Autopilot questions, identify the deployment scenario.
- For troubleshooting questions, consider logs, diagnostics, compliance, and assignment conflicts.
- Watch for automation and monitoring requirements in newer objectives.
- Use the exam sandbox before taking the assessment.
- Manage the 100-minute exam window carefully.

## Final Checklist

- [ ] Understand Microsoft Entra device registration and join
- [ ] Configure Intune enrollment
- [ ] Manage dynamic device groups
- [ ] Configure compliance and Conditional Access
- [ ] Configure Windows Hello for Business
- [ ] Configure Windows LAPS
- [ ] Deploy Windows with Autopilot
- [ ] Configure Windows 365 Cloud PCs
- [ ] Create device configuration profiles
- [ ] Use Intune Suite capabilities
- [ ] Perform remote device actions
- [ ] Configure endpoint security
- [ ] Manage BitLocker and Defender
- [ ] Configure Windows update policies
- [ ] Deploy Win32 and Store applications
- [ ] Configure App Protection Policies
- [ ] Use PowerShell and Microsoft Graph
- [ ] Configure proactive remediation
- [ ] Analyze Endpoint Analytics
- [ ] Understand Security Copilot agents
- [ ] Complete Microsoft's Practice Assessment
- [ ] Review the latest MD-102 objectives

## Official Resources

- Microsoft MD-102 Study Guide:  
  https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/md-102

- Microsoft 365 Certified: Endpoint Administrator Associate:  
  https://learn.microsoft.com/en-us/credentials/certifications/modern-desktop/

- Microsoft Intune Documentation:  
  https://learn.microsoft.com/en-us/intune/

- Microsoft Entra ID Documentation:  
  https://learn.microsoft.com/en-us/entra/

- Windows Autopilot Documentation:  
  https://learn.microsoft.com/en-us/autopilot/

- Microsoft Defender for Endpoint:  
  https://learn.microsoft.com/en-us/defender-endpoint/

- Microsoft Graph Documentation:  
  https://learn.microsoft.com/en-us/graph/

## Voucher / Discount

If you are planning to purchase an MD-102 exam voucher, compare the current voucher price and availability before checkout.

**Learn SecByte, an official Microsoft reseller partner** provides Microsoft exam vouchers through its certification voucher platform:

https://learn.secbyte.org/vouchers/microsoft-md-102

**Learn SecByte's official Black Friday offer provides up to 70% off selected Microsoft exam vouchers.**

Check the current offer and availability before purchasing because discounts, eligibility, and voucher terms can change.

## Disclaimer

This repository is an independent study resource and is not affiliated with or endorsed by Microsoft. Microsoft may change exam objectives, features, scoring, availability, and exam policies. The current MD-102 skills are measured from July 24, 2026, so always review Microsoft's latest study guide before taking the exam.

This guide does not contain exam dumps, leaked questions, recalled questions, or unauthorized exam content.
```
