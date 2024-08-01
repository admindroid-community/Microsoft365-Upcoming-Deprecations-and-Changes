# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.

Discover the **key changes, deprecations**, and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

Here is a list of changes categorized by month and year.

- Aug 2024 (New Features: 6, Retirements: 7, Enhancements: 8, Existing Functionality Changes: 2, Action Required: 1)
- Sep 2024 (Attention needed: 11)
- Oct 2024 (Attention needed: 4)
- Nov 2024 (Attention needed: 5)
- Dec 2024 (Attention needed: 5)
- 2025 (Attention needed: 15)
- 2026 (Attention needed: 9)





## August 2024

New Features: 6 | Retirements: 7 | Enhancements: 8 | Existing Functionality Changes: 2 | Action Needed: 1
## New Features

### Early-Aug 2024 - Public Preview of Progressive Alert Scoring

Microsoft is rolling out a new feature -" Progressive alert scoring" in public review, starting in early August 2024. Currently, user activities that could potentially result in data security incidents will be assessed once every 24 hours. After this rollout, the assessment of user activities will be done more frequently within a 24- hour period, along with alert insights.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC707653>

### Early-Aug 2024 - New Administrative Units for Microsoft Teams Administration


Microsoft will start rolling out new Administrative Units in the Teams admin center by early August 2024. After the rollout, admins can facilitate delegation administration by assigning the following roles to the AUs.

- Teams Administrator
- Teams Device Administrator
- Teams Communication Administrator
- Teams Communication Support Engineer
- Teams Communication Support Specialist
- Teams Telephony Administrator

***Ref:*** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC810173>



### Mid-Aug 2024 - New Recommendations for Microsoft Secure Score


Microsoft Defender XDR is enhancing its security capabilities by introducing four new recommendations focused on Azure Single Sign-On (SSO) account configurations and Microsoft Entra Connect accounts.

These new recommendations will be visible in Microsoft Defender XDR from mid-August 2024.

- Azure SSO account configuration: Password last set more than 90 days ago
- Azure SSO account configuration: Resource-Based Constrained Delegation configured
- Remove unnecessary replication permissions for Microsoft Entra Connect accounts
- Rotate password for Entra Connect connector users



**Note:** By default, it will be available only to customers who have installed an MDI sensor on the Entra Connect server.



***Ref:*** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC816173>








### Late-Aug 2024 - General Availability of Adaptive Protection for GCC, GCCH, DoD


By late August 2024, the Adaptive Protection integration with Microsoft Purview Data Loss Prevention will be generally available for government clouds (GCC, GCC High, DoD). Following this, admins will be able to manage policies more effectively based on insider risk levels.



***Ref:*** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC803011>

### Aug 2024 - New Authentication Method "QR Code Sign-in"

Microsoft is introducing a new authentication method, "QR code sign-in," in a private preview by August 2024. This feature allows users on mobile devices (Android/iOS/iPadOS) to authenticate using a QR code and PIN.

**Ref:**
<https://techcommunity.microsoft.com/t5/microsoft-entra-blog/what-s-new-in-microsoft-entra-june-2024/>


### Aug 2024 - Conditional Access What If API in Preview


The Conditional Access What If API, which is used to analyze the impact of Configured CA policies, will enter preview by August 2024.



***Ref:*** <https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=In%20development&searchterms=406760>


## Retirements

### Aug 5, 2024 - Microsoft 365 Groups Connectors Retirement

Microsoft 365 group connectors, which deliver notifications from online tools and services to group emails, will no longer be available for New Outlook for Windows & Outlook on the Web users from Aug 5, 2024. Existing group connectors will not receive any updates after this date.

**Solution**: Use the Power Automate app as an alternative to receive notifications and updates on Group email.

**Ref:**
<https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC798683>

### Aug 15, 2024 - Office 365 Connectors Retirement

Users will no longer be able to create new Office 365 Connectors from Aug 15, 2025. However, all the existing connectors will continue to work until December 2025, unless you undergo a URL update.



**Solution:** Migrate to alternate solutions such as Power Automate or Microsoft Graph.



***Ref:*** <https://devblogs.microsoft.com/microsoft365dev/retirement-of-office-365-connectors-within-microsoft-teams/>



### Aug 18, 2024 - Retirement of Four Override Alerts in Microsoft Defender for Office 365


Microsoft Defender for Office 365 plans to remove four legacy override alerts starting August 18, 2024. This decision is due to the 'Secure by default' feature with ZAP (Zero-Hour Auto Purge), which will automatically block high-confidence phishing emails. As a result, these four alerts will no longer be needed.

1. Phish not zapped because ZAP is disabled
1. Malware not zapped because ZAP is disabled
1. Phish delivered due to ETR override
1. Phish delivered due to IP allow



***Ref:*** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC822720
](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC822720)


### Aug 19, 2024 - “Publish to Power BI” Feature Retirement in Microsoft Excel


The "Publish to Power BI' feature in Microsoft Excel will retire by Aug 19, 2024. So, users will no longer be able to publish the data directly from Excel to Power BI.



**Solution:** Move to Power BI service (Power BI on the web), which offers additional capabilities that are not found in Excel publishing including, non-default workspaces, workspace folders, and modern format data models.



***Ref:*** <https://learn.microsoft.com/en-us/power-bi/connect-data/service-publish-from-excel>


### Aug 20, 2024 – All Contents from Stream (Classic) will be Deleted 

With the retirement of Stream Classic on April 15, 2024, all content will be deleted starting August 20, 2024. 

**Solution:** Migrate your Stream (Classic) content to Stream (on SharePoint) to ensure continued access. 

***Ref:*** 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC764452> 

### Aug 26, 2024 – Existing SharePoint News Connectors Retirement

All existing SPO news connectors will be retired by August 26, 2024. Also, users can’t create new SPO news connectors from July 22, 2024.

**Solution:** Move to alternatives like Viva Connections News notifications, Viva Amplify, or Teams Workflow.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC803508>



### Aug 31, 2024 - Azure AD Graph API Retirement

The initial phase of Azure AD Graph API retirement begins on Aug 31, 2024. Entra ID apps created after this date and trying to use the Azure AD Graph API will face errors. Applications that are created *before Aug 31, 2024,* will not be impacted at this stage. 

***Ref:*** 
[https://techcommunity.microsoft.com/t5/microsoft-entra-blog/what-s-new-in-microsoft-entra-june-2024/ba-p/3796387](https://techcommunity.microsoft.com/t5/microsoft-entra-blog/what-s-new-in-microsoft-entra-june-2024/ba-p/3796387#:~:text=Important%20Update%3A%20Azure%20AD%20Graph%20Retirement)

## Enhancements

### Aug 2024- Microsoft SharePoint Document Libraries: Improved Version History Controls

Microsoft is introducing new version controls to assist tenant and site admins, as well as document library owners, in reducing storage consumption caused by low-value file versions. With this update, admins can configure two version history settings.  

- ***Automatic Mode:*** This mode automatically expires both new and existing versions based on their age and the probability of restoration.  
- ***Manual Mode:*** In this mode, admins can set time-based version expiration and count limits for both new and existing versions according to their preferences.  

Admins can opt into the Public Preview by running the SharePoint Online Management PowerShell cmdlet.  

` `Set-SPOTenant -EnableVersionExpirationSetting $true   

Note: Public preview for this feature was released in May 2024, and the General Availability is scheduled for August 2024, 

***Ref:*** 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC789209> 

### Mid-Aug 2024 - Outlook: Folder/Subfolder Recursive Search 

With this feature, when a user searches for content in an Outlook folder, all its subfolders are also searched, and the results are displayed. 

***Ref:***  <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC802699>

### **Mid-Aug 2024 - New Filters in Microsoft Purview Audit Search**

Four new filters will be available in the public preview for unified audit log search by mid-August 2024. The four additional fields in the audit search UI are UserType, UserKey, ClientIP, and Id.



***Ref:*** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC789312>


### Mid-Aug 2024 - New eDiscovery Hold Reports in Microsoft Purview

The new tenant-wide "eDiscovery Hold reports" will be generally available under the *Reports* tab in eDiscovery (Premium). Starting mid-August 2024, admins can access this report to review all hold policies with eDiscovery cases in the Microsoft Purview compliance portal.



***Ref:*** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC776192>

### Mid-August 2024 - Audit: New Cloud Policy Service Audit Logs for Policy Changes



Microsoft will soon integrate cloud policy service into Microsoft Purview Compliance portal. Admins can search and review Microsoft 365 cloud policy changes (Create, update, delete) using unified audit logs from mid-August 2024. These logs will be available to **Purview Audit Standard** users.

***Ref:*** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC789309>

### Mid-August 2024 - SharePoint eSignature Service in Canada, the UK, and Selected European Countries

Microsoft's SharePoint eSignature service, initially launched in the US in late November 2023, is now expanding its availability to include users in the UK, Canada, and selected European countries. Starting mid-August 2024, users from these regions will be able to utilize SharePoint online to request eSignatures on PDF documents.

**Ref:**
<https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC800502>

### **Late-Aug 2024 - Microsoft 365 Groups Scoping in Teams DLP Policy Extend Protection to 1:1/n Chats**


Starting late August 2024, DLP policies for Microsoft 365 Groups in Teams will automatically protect all 1:1/n (non-channel) chats, in addition to standard and shared channel chats. So, manually adding users or groups is no longer required, except for those using OCR in Teams chat.



***Ref:*** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC837079>


### **Aug 2024 - Enhanced Alert and User Investigation with Copilot for Security**


Starting in August, Copilot for Security will assist in investigating alerts within Microsoft Purview Insider Risk Management. It will provide concise summaries of alerts and important details, such as the user's risk profile and other relevant information.



***Ref:*** <https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=In%20development&searchterms=407864>

## Existing Functionality Changes

### Early-Aug 2024 - Changes in Handling of Documents in MS Outlook for iOS and Android.


Currently, Microsoft prioritizes opening documents in the Microsoft 365 app when users have both the Microsoft 365 app and standalone apps for Word, Excel, or PowerPoint. However, starting early-August 2024, users will be prompted to use the standalone apps instead of the Microsoft 365 app.



**Note**: It is advised to review your organization's app management policies to ensure that users are not restricted to using only the Microsoft 365 app for document handling.



***Ref:*** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC788952>




### Aug 30, 2024 - Admins Can No Longer Receive User Passwords in Email


Starting August 30, 2024, the 'Send Password in Email' feature will be retired from the Microsoft 365 admin center. Admins will no longer be able to receive usernames and passwords via email after this date. Instead, it is advised to use the "Print" option in the Microsoft admin center to save the account credentials and share them with respective users.



***Ref***: <https://learn.microsoft.com/en-us/microsoft-365/admin/add-users/reset-passwords?view=o365-worldwide>


## Action Required

### Aug 31, 2024 – PowerBI Retiring Support for Older Browsers by August 31, 2024

Microsoft PowerBI is retiring support for older browsers on September 1, 2024. 

**Solution:** To avoid interruptions in functionality, users should upgrade their browsers by August 31, 2024.

***Ref:*** <https://powerbi.microsoft.com/en-us/blog/power-bi-june-2024-feature-summary/>


## September 2024

## New Features

### Mid-Sep 2024 - New Workflow Builder Feature in Microsoft Teams


Starting mid-September 2024, Microsoft Teams will introduce a new 'Workflow Builder' feature. This feature allows you to describe the automation you need and find matching workflows. Initially, it will be available under the 'Workflows' app in the Teams chat and channel overflow menu, with plans to expand its availability to other entry points in the future.



***Ref:*** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC718250>

### Mid-Sep 2024 - General Availability of New Teams Onboarding Process


The new onboarding process which gives Teams owners the ability to recommend Teams members to join the needed channels will be generally available by mid-September 2024.



***Ref:*** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC790796>

### Sep 2024 – Exchange - High Volume Email for Microsoft 365 (General Availability) 

High Volume Email (HVE) is designed for large-scale internal communications, facilitating mass mailing needs.  

Note: In public preview, you can send emails to up to 100k recipients per 24 hours, with a maximum of 2,000 external users. 

***Ref:***
<https://learn.microsoft.com/en-us/Exchange/mail-flow-best-practices/high-volume-mails-m365>  

### Sep 2024 - New "Resources" Category in Microsoft Entra Conditional Access

Microsoft Entra Conditional Access will streamline the "Target resources" assignment by combining the current options "Cloud apps" and "Global Secure Access" into a single category named "Resources."


***Ref:*** 
<https://techcommunity.microsoft.com/t5/microsoft-entra-blog/what-s-new-in-microsoft-entra-june-2024/>



## Retirements


### Sep 1, 2024 - File Pages in Microsoft Defender for Cloud Apps Retirement


Microsoft will start deprecating the Files page from Microsoft Defender for Cloud Apps from September 1, 2024. Additionally, Microsoft will also be removing the Files and Insights tabs found under Microsoft Defender > Settings > Cloud Apps > App Connectors.



**Solution:** Use the Policy Management Page to create/modify/explore Information Protection policies and malware files.



***Ref:*** <https://learn.microsoft.com/en-us/defender-cloud-apps/file-filters>

### Early - Sep 2024 - Retirement of Dictation Feature in Microsoft Outlook for iOS and Android.


Microsoft will be removing the dedicated Dictation feature from Outlook for iOS and Android due to redundancy with the system microphone. This change will take effect starting in early September 2024.



**Solution**: Use the system microphone itself for dictation in Outlook for iOS and Android.



***Ref:*** <https://support.microsoft.com/en-us/office/dictate-your-emails-in-outlook-mobile-fe39a8bc-ea2b-45b9-83cc-e71b8e8c7d93>

### Sep 30, 2024- Azure Multi-Factor Authentication Server   

Azure MFA Server deployments will no longer service MFA requests, which could cause authentications to fail for your organization.  

**Solution:** Organizations should migrate their users’ authentication data to the cloud-based Azure MFA service    

***Ref:*** 
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-september-2022-train/ba-p/2967454> 

### Sep 30, 2024 – Business Connectivity Services Retirement in Microsoft 365  

Microsoft will retire Business Connectivity Services features in Microsoft 365.   

**Solution**: Microsoft recommends using Power Apps to replace their Business Connectivity Services solutions in SharePoint in Microsoft 365.  

***Ref***: 
<https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-business-connectivity-services-in-microsoft/ba-p/3938773>  

## Enhancements
### Early-Sep 2024 - General Availability of Inbound SMTP DANE with DNSSEC


Exchange Online has begun supporting DNS-based Authentication of Named Entities (DANE) for SMTP and Domain Name System Security Extensions (DNSSEC) for securing inbound mail. This feature is currently in public preview and will be generally available by early September 2024.



***Ref:*** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC711018>




### Late-Sep 2024 - Default Sensitivity Labels and Policy Enhancement


Default sensitivity labels and policies, which currently cover only files and emails, will also include meetings. This update will not change any existing sensitivity labels used in your organization. It will only affect organizations that choose to activate the default labels.



***Ref:*** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC841050>




## Existing Functionality Changes

### Sep 2024 - Changes to Phone Call Settings in Entra ID

Entra will relocate phone call settings (custom greetings and caller ID) from the multifactor authentication blade to the voice authentication method within the authentication method policy.

***Ref:*** 
<https://techcommunity.microsoft.com/t5/microsoft-entra-blog/what-s-new-in-microsoft-entra-june-2024/>


## October 2024 

### Oct 01, 2024- Classic Teams in VDI End of Support 

The end of support for the classic Teams client in VDI starts October 1, 2024, and the end of availability for the classic Teams client in VDI starts July 1, 2025. 

***Ref:*** 
<https://learn.microsoft.com/en-us/MicrosoftTeams/new-teams-vdi-requirements-deploy>   

### Oct 1, 2024 - IPv6 Enablement for Accepted Domains in Exchange Online

To improve security and performance, Microsoft will begin enabling IPv6 for accepted domains using Exchange Online for inbound mail. To benefit from IPv6, admins must ensure that their network allow-list includes Exchange Online IPv6 endpoints.



***Ref:*** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC835648>

### Mid-Oct 2024- New cmdlet for Content Explorer 

Currently, the Content Explorer export feature has a limitation of exporting data only after drilling down to a specific location. With this update, admins can use a new cmdlet, ***Export-ContentExplorerData***, to export all rows of data for the content on the Content Explorer. 

Note: The new cmdlet is available in Security & Compliance PowerShell. 



***Ref:*** <https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC698421>  

### Oct 23, 2024- Classic Teams Desktop App End of Availability 

Beginning on October 23, 2024, the classic Teams desktop app will no longer be available for Windows 7, 8, 8.1, and Mac OS Sierra (10.12). 

Starting July 1, 2025, classic Teams desktop app will reach end of availability for all users. Also, the “New” label will be removed from the new Teams app by mid-July 2024. 

**Solution:** Users need to update their OS, or they can use the new Teams web app (on supported browser) as an alternative. 

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783985> 

## November 2024

### Nov 01, 2024- Azure ACS Retirement in Microsoft 365

Microsoft is retiring the use of Azure ACS as auth platform for SharePoint Online. Starting November 1st, 2024, new tenants will not be able use Azure ACS. For existing tenants that currently rely on Azure ACS to provide custom-developed or third-party applications access to SharePoint Online, this functionality will cease to work after April 2, 2026.  

**Solution**: Admins can utilize the Microsoft 365 Assessment tool to scan the tenants for any usage of Azure Access Control Service (ACS) and [migrating from Azure ACS to Microsoft Entra ID](https://aka.ms/retirement/acs/guidance).  

***Ref***:
<https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/retirement-announcement-for-azure-acs>  

### Nov 01, 2024- SharePoint Add-in Retirement  
SharePoint Add-Ins will stop working for new tenants as of November 1, 2024, and they will be fully retired as of April 2nd, 2026.  

**Solution**: Admins can run the [Microsoft 365 Assessment tool](https://aka.ms/assessment/addinsacs) to scan their tenants for SharePoint Add-In usage.  

***Ref***: 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865> 

### Early-Nov 2024 - Microsoft Teams: Shorter Meeting URLs


Microsoft plans to shorten the meeting URLs for easy sharing across all Teams platforms. Starting early-November, the URL will contain only the meeting ID and other parameters such as tenant ID, Organizer ID, Conversation ID, and message ID will not be there. This will be the new URL format: https://teams.microsoft.com/meet/<meeting\_id>?p=<HashedPasscode>



***Ref:*** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC772556>

### Early Nov 2024 - Enhanced Content Extraction and File Type Coverage for DLP on Windows Devices


The Microsoft Purview Data Loss Prevention has planned to introduce the following enhancements by early-November 2024.

- The number of supported file types will increase from 40 to 100.
- Identifies sensitive content in metadata and protected files (pfiles)
- DLP will detect sensitive information in PDF form fields and files embedded within Office files (e.g., a .txt file inside a .pptx file)

***Ref:*** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791881>

### Mid- Nov 2024 - General Availability of Dynamic Watermarking for Current Channel

Dynamic watermarking, a new sensitivity label setting is used to add watermarks onto content in files created in Microsoft Word, Excel, and PowerPoint. This feature will be generally available to the current channel by mid-November 2024.



***Ref:*** <https://techcommunity.microsoft.com/t5/security-compliance-and-identity/preview-dynamic-watermarking-for-sensitivity-labels-in-word/ba-p/4185842>



## December 2024

### Dec 16, 2024 - Delve Web Retirement 

Microsoft retiring Delve on December 16th, 2024. Many Delve features are now available and improved in other Microsoft 365 experiences.  

**Solution:** Key alternatives include: 

- Discover documents: Use Office.com, Office apps, and Profile Cards. 
- View profile data: Utilize Profile Cards, people search on Office.com, and SharePoint search. 
- Edit profile: A new edit profile experience will be released in H2 2024 and can also be edited in SharePoint. 
- Organizational view: Available in the Profile Card and Org Explorer. 
- Favorites: Use favorites on Office.com and OneDrive for similar functionality. 
- Boards: Will not be replaced. 

***Ref:*** <https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC698136>

### Mid-Dec 2024 - Data Lifecycle Management: New integration with Adaptive Protection
### 
Microsoft Purview's Data Lifecycle Management integrates with Adaptive Protection to automatically retain items deleted by users identified as having an elevated risk level. This integration capability will be generally available by mid-December 2024

***Ref:*** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110>


## Dec 31, 2024 - Intune Ending Support for Android Device Administrators on Devices with GMS Access
Google has decided to phase out Android device administrator management. In response, Microsoft Intune will stop supporting this management type on devices using Google Mobile Services (GMS) starting December 31, 2024.

**Solution:** Stop enrolling devices into Android device administrator and migrate impacted devices to other management methods. 

***Ref:***
<https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC674247>

### December 31, 2024 - Update the URL of Existing Office 365 Connectors to Continue Functioning.


Connector owners must update their URLs by this date to continue using connectors beyond December 31, 2024, or the connectors will stop working.



***Ref:***
<https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC808160>


### End of 2024- Retirement of Mail and Calendar Apps in Windows  

At the end of 2024, Microsoft replacing the Mail and Calendar apps in Windows with the new Outlook for Windows.    

**Solution:** Start trying and testing the new Outlook for Windows.  

***Ref***: 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC590123> 

## 2025 (Attention Needed: 13)

### Jan 01, 2025- External Recipient Rate Limit in Exchange Online 

Exchange Online will begin enforcing an external recipient rate (ERR) limit of 2000 recipients in 24 hours. This restriction will be applicable to the cloud-hosted mailboxes of all newly created tenants. 

For existing tenants, this limit will be enforced in the second half of 2025. 

**Note:** Exchange Online enforces a Recipient Rate limit of 10000 recipients for cloud-hosted mailboxes. The 2000 ERR limit will become a sublimit within this 10000 Recipient Rate limit. 

***Ref:*** 
<https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733> 

### Early 2025 - MFA Enforcement for CLI, Azure PowerShell, IaC Tools

As part of enforcing MFA for all Azure users, MFA enforcement for Azure Command Line Interface (CLI), Azure PowerShell, and Infrastructure as Code (IaC) tools will gradually be introduced to all tenants starting in early 2025.

***Ref:*** 
<https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/update-on-mfa-requirements-for-azure-sign-in/>

### Late-Jan 2025 - Microsoft Auto-Archives Unlicensed OneDrive Accounts

Starting in **late January 2025**, any OneDrive accounts left unlicensed for more than 90 days will be automatically archived, hitting you with extra costs to regain access in Microsoft Archive.  Yes! You will be charged $0.05 per GB per month to store unlicensed OneDrive content and $0.60 per GB to reactivate the account in the Microsoft 365 archive.



***Ref:*** <https://learn.microsoft.com/en-us/sharepoint/unlicensed-onedrive-accounts>




### Feb 2025- Removal of the ApplicationImpersonation Role Based Access Control (RBAC) in Exchange Online  

Microsoft is going to remove ApplicationImpersonation Role Based Access Control (RBAC) role and its feature set from Exchange Online. 

***Ref:*** 
<https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-rbac-application-impersonation-in-exchange-online/ba-p/4062671> 
### Feb 01, 2025 - Azure Key Vault: Soft-delete Will be Enabled in All Key Vaults
Soft Delete preserves deleted key vaults and secrets for up to 90 days, enabling customers to restore them through a self-serve process.   

***Ref:*** <https://learn.microsoft.com/en-us/azure/key-vault/general/soft-delete-change> 

### Feb 22, 2025- Viva Topics Retirement 
Viva Topics will be discontinued on February 22, 2025, and Microsoft will no longer pursue new feature enhancements for the platform. 

Existing Topic pages will transition to standard SharePoint pages. Users can edit and publish updates as other SharePoint pages. AI-generated Topic pages will no longer be accessible. 

***Ref:*** 
<https://learn.microsoft.com/en-us/microsoft-365/topics/changes-coming-to-topics> 

### Mar 30, 2025- Azure AD and MSOnline PowerShell Modules may Stop Working
Microsoft has officially deprecated the Azure AD and MSOnline PowerShell modules Mar’24. However, they will remain functional until March 30, 2025, with support limited to critical security fixes.  

**Note:** Only MSOnline versions 1.1.166.0 (2017) and later are guaranteed to function as expected.  

***Ref:*** 
<https://techcommunity.microsoft.com/t5/microsoft-entra-blog/important-update-deprecation-of-azure-ad-powershell-and-msonline/ba-p/4094536>   

### April 2025 - Insider Risk Management- Risk AI Usage

Microsoft plans to introduce a new feature in Insider Risk Management, which will be widely available from April 2025. This feature aims to detect potentially risky use of AI. It includes monitoring activities involving sensitive information in prompts generated by AI assistants, covering both copilots and third-party AI applications.


**Ref:** 
<https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=In%20development&searchterms=394281>

### Apr 02, 2025 – Retirement of Domain Isolated Web Part in SharePoint Framework 

As part of the SharePoint Framework domain isolated web parts retirement, this feature will be turned off for newly created tenants starting from Apr 02, 2025. 

**Note:** From Apr 02, 2026, existing tenants will no longer be able to use this feature. 

***Ref:***
<https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/>  

### H2 2025- External Recipient Rate Limit in Exchange Online 

In the second half of 2025, Exchange Online will start enforcing an external recipient rate (ERR) limit of 2000 recipients within a 24-hour period for all existing tenants. This restriction was already implemented for all newly created tenants in January 2025. 

**Note**: Exchange Online enforces a Recipient Rate limit of 10000 recipients for cloud-hosted mailboxes. The 2000 ERR limit will become a sublimit within this 10000 Recipient Rate limit. 

***Ref:*** 
<https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733> 

### July 1, 2025- Classic Teams Desktop App End of Availability 
Starting July 1, 2025, classic Teams desktop app will reach end of availability for all users irrespective of OS. 

**Note**: From Oct 23, 2024, classic Teams desktop app on Windows 7,8,8.1 and Mac OS Sierra (10.12) will reach end of availability. 

**Solution:** Users need to switch to new Teams, or they can use Teams web app (on supported browser) as an alternative. 

***Ref:*** 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783985> 

### Sep 2025- Basic Auth for Client Submission (SMTP AUTH) Retirement in Exchange Online 

Exchange Online will permanently remove support for Basic authentication with Client Submission (SMTP AUTH) in September 2025. 

**Solution:** You can start to use OAuth with Client Submission (SMTP AUTH). 

***Ref:*** 
<https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-retire-basic-auth-for-client-submission-smtp/ba-p/4114750> 

### Sep 30, 2025 – Retirement of Managing Authentication Methods in Legacy MFA &SSPR Policy

Starting Oct 2025, Microsoft no longer allow authentication methods to be managed in the legacy MFA and SSPR policies.   

**Solution:** Organizations should use the converged authentication methods policy where methods can be managed centrally for all authentication scenarios including passwordless, MFA and SSPR.   

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448> 

### Oct 14, 2025- End of Extended Support for Office 2016 & Office 2019   

Office 2016 and Office 2019 extended support ends in 2025. 

**Solution:** You can start to use the latest supported versions. 

***Ref:***
<https://learn.microsoft.com/en-us/lifecycle/products/microsoft-office-2016>

### Dec 2025 - Existing Office 365 Connectors will stop Working

Existing Office 365 connectors will continue to work until December 2025, after which they will no longer work.



***Ref:*** <https://learn.microsoft.com/en-us/power-bi/connect-data/service-publish-from-excel>



## 2026 (Attention Needed: 9)

### Jan 13, 2026 – End of Extended Support for Microsoft Advanced Threat Analytics 1.x

Microsoft Advanced Threat Analytics (ATA) extended support will be ended on January 13, 2026.   

**Solution**: Updates for Microsoft ATA are available from Microsoft Update or by manual download.   

***Ref:*** 
<https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c> 

### Mar 31, 2026- Deprecation of ‘Require Approved Client App’ Conditional Access Grant    

The Require approved client app control in Azure Active Directory (Azure AD) Conditional Access will be retired and no longer enforced.   

**Solution:** You can make use of the “Require app protection policy” control, which has all the same capabilities   

***Ref:*** 
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448> 
### 
### Apr 02, 2026 – SharePoint 2013 Workflow Retirement

SharePoint 2013 workflows will no longer be supported. 

**Solution:** You can move to Power Automate or other supported solutions. 

***Ref:*** 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC542767> 

### Apr 02, 2026- SharePoint Add-in Retirement
SharePoint Add-Ins will stop working for existing tenants from April 2nd, 2026.   

**Solution:** Admins can run the [Microsoft 365 Assessment tool](https://aka.ms/assessment/addinsacs) to scan their tenants for SharePoint Add-In usage.   

***Ref:*** 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865> 

### Apr 02, 2026 – Azure ACS Retirement in Microsoft 365

After April 2, 2026, existing tenants using Azure ACS for custom or third-party app access in SharePoint Online will no longer function due to its retirement.  

**Solution:** Admins can utilize the Microsoft 365 Assessment tool to scan the tenants for any usage of Azure Access Control Service (ACS) and [migrating from Azure ACS to Microsoft Entra ID](https://aka.ms/retirement/acs/guidance).   

***Ref:*** 
<https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/retirement-announcement-for-azure-acs>  


### Apr 02, 2026 - Retirement of Domain Isolated Web Part in SharePoint Framework 

From Apr 02, 2026, the domain isolated web part feature will be fully retired. Organizations using this feature will receive an error message. 

**Solution:** Update your domain isolated web parts to regular web parts and redeploy them to ensure continued functionality. 

***Ref:*** 
<https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/>  

### July 14, 2026- InfoPath 2013 Client and InfoPath Forms Services in SharePoint Online will be Retired


InfoPath Client 2013 will reach the end of its extended support period on July 14, 2026, and to keep an aligned experience across Microsoft products, InfoPath Forms Service will be retired from SharePoint Online. 

**Solution:** To understand the usage of InfoPath within your organization, you can utilize the [Microsoft 365 Assessment tool](https://aka.ms/assessment/infopath) to scan your tenant and analyze InfoPath usage. If you are currently using InfoPath, you can initiate the migration process to modern alternatives such as Power Apps, Power Automate, or Forms. 

***Ref:*** 
<https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190> 

### Oct 01, 2026- Retirement of Exchange Web Services in Exchange Online 

October 1, 2026, Microsoft will start blocking EWS requests from non-Microsoft apps to Exchange Online. The changes in Exchange Online do not affect Outlook for Windows or Mac, Teams, or any other Microsoft product. 

**Solution**: Migrate your applications to Microsoft Graph to access Exchange Online data and gain access to the latest features and functionality. 

***Ref***: 
<https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-exchange-web-services-in-exchange-online/ba-p/3924440> 

### Oct 01, 2026 – Sign-in Risk Policy and User Risk Policy Retirement from Entra ID Protection

User risk policy or Sign-in risk policy UX in Entra ID Protection (formerly Identity Protection) will be retired on October 1, 2026. 

**Solution:** Migrate Sign-in risk and User risk policies to Conditional Access. 

***Ref***:
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/what-s-new-in-microsoft-entra/ba-p/3796395> 

### Oct 13, 2026- Retirement of Microsoft Publisher 

In October 2026, Microsoft will discontinue Publisher in Microsoft 365, with on-premises suite support ending. While support lasts, they're exploring modern alternatives across Word, PowerPoint, and Designer for common Publisher tasks, with updates forthcoming. 

***Ref:*** 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC716267> 

In conclusion, navigating the ever-evolving landscape of Microsoft 365 requires staying informed about the changes. By proactively adapting to these changes, you can optimize your Microsoft 365 experience, maximize productivity, and effectively plan for the future.

We are committed to keeping this blog updated with the latest information, so stay tuned for upcoming updates.
### <https://blog.admindroid.com/microsoft-365-end-of-support-milestones/>





