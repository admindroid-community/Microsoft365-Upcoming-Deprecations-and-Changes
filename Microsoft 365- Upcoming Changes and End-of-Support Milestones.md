# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on

the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.  
  
Discover the **key changes, deprecations**, and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

  
Here is a list of changes categorized by month and year.  

*   Dec 2024 (New Features: 8, Retirements: 5, Enhancements: 4, Existing Functionality Changes: 4, Action Needed: 1)
*   Jan 2025 (Attention Needed: 15)
*   Feb 2025 (Attention Needed: 7)
*   Mar 2025 (Attention Needed:3)
*   Apr 2025 (Attention Needed: 5)
*   May 2025 (Attention Needed: 2)
*   June 2025 (Attention Needed: 3)
*   Q3 2025 (Attention Needed: 3)
*   Q4 2025 (Attention Needed: 3)
*   2026 (Attention needed: 9)

  

## December 2024

New Features: 8 | Retirements: 5 | Enhancements: 4 | Existing Functionality Changes: 4 | Action Needed: 1

## New Features

### December 2024 – Integration of Cloud Policy Service with Microsoft Purview Audit

Any changes to policy configurations—whether creating, updating, or deleting—will be captured in Purview Audit, enabling admins to search and review the change history. These logs will be accessible to users with Purview Audit Standard license.

  
**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC789309](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC789309)

### Dec 2024 - Email Response Actions API for Microsoft Defender

Admins will be able to use the Email Response actions API in Microsoft Graph to perform purge actions such as soft delete, hard delete, moving emails to junk, etc., in Microsoft Defender.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=93434](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=93434)

### Dec 2024 - Microsoft Entra: Conditional Access WhatIf API

Microsoft will introduce a Conditional Access policy API by December 2024, enabling admins to test the impact of Conditional Access policies on users and workload sign-ins.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=406760](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=406760)

### Dec 2024 - Integration of New ChatGPT Enterprise Connector with Microsoft Purview Compliance Portal

The ChatGPT Enterprise connector will be integrated into the Microsoft Purview Compliance portal, allowing admins to discover, collect, and store prompts and responses from users' interactions with ChatGPT. This feature will be in preview by December 2024.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=401125](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=401125)

### Early-Dec 2024 - Add Approvals to Any Document Library in SharePoint

With this feature, admins can enable or disable approvals using the "Configure Approvals" option found under the "Automate" dropdown in the SharePoint Online document library. This feature will be enabled by default.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC912181](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC912181)

### Early-Dec 2024 - New License Request Feature for Microsoft 365 Copilot

Starting in early December 2024, a new license requests feature for Microsoft 365 Copilot will be available. Users will be able to request a Copilot license from admins. Global admins or license admins will be able to manage these requests using a new interface in the Microsoft 365 Admin Center.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC940142](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC940142)

### Mid-December 2024 - Insider Risk Management: Adaptive Protection in GCC, GCCH, DoD

Microsoft will finish integrating Adaptive Protection with Microsoft Data Loss Prevention (DLP) in the government clouds (GCC, GCC High, and DoD). This will enable administrators to automatically add users to DLP policies based on their insider risk scores.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC803011](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC803011)

### Mid-Dec 2024 - Data Lifecycle Management: New integration with Adaptive Protection

Microsoft Purview's Data Lifecycle Management integrates with Adaptive Protection to automatically retain items deleted by users identified as having an elevated risk level. This integration capability will be generally available by mid-December 2024

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110)

## Retirements

### Early-Dec 2024 - Retirement of “Turn On All System-level Exploit Protection Settings” Secure Score Recommendation

Microsoft plans to retire the MDE recommendation "Turn on all System-level Exploit protection settings" as part of an improvement action. This gradual rollout will begin in early December 2024.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC941863](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC941863)

### Dec 13, 2024 - Retirement of Classic Microsoft Purview Compliance Portal

The classic Microsoft Purview Compliance Portal will be fully retired by December 13, 2024. All configurations and data will be carried over to the new Microsoft Purview portal.

**Solution:** Transition to the new Purview portal and familiarize yourself with its unified, streamlined experience.

**_Ref:_** [https://learn.microsoft.com/en-us/purview/purview-compliance-portal](https://learn.microsoft.com/en-us/purview/purview-compliance-portal)

  

### Dec 16, 2024 - Delve Web Retirement

Microsoft retiring Delve on December 16th, 2024. Many Delve features are now available and improved in other Microsoft 365 experiences.

**Solution:** Key alternatives include:

*   Discover documents: Use Office.com, Office apps, and Profile Cards.
*   View profile data: Utilize Profile Cards, people search on Office.com, and SharePoint search.
*   Edit profile: A new edit profile experience will be released in H2 2024 and can also be edited in SharePoint.
*   Organizational view: Available in the Profile Card and Org Explorer.
*   Favorites: Use favorites on Office.com and OneDrive for similar functionality.
*   Boards: Will not be replaced.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC698136](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC698136)

### Late-Dec 2024 - Researcher Feature Retirement in Microsoft Word

The Researcher feature in Microsoft Word will be retired starting late December 2024. This applies to Word for Windows desktops and Word for Mac desktops.

Solution: Use Microsoft Copilot as a good alternative to Researcher feature.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC901824](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC901824)

### End of 2024- Retirement of Mail and Calendar Apps in Windows

At the end of 2024, Microsoft replacing the Mail and Calendar apps in Windows with the new Outlook for Windows.

**Solution:** Start trying and testing the new Outlook for Windows.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC590123](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC590123)

## Feature Enhancements

### Early Dec 2024 - Business Chat Usage in Microsoft 365 Copilot Usage Report

The Microsoft 365 Copilot Usage Report will include insights on total Business Chat usage, breaking down data between Business Chat (Work) and Business Chat (Web). This update is available by default.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC942832](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC942832)

### Mid-Dec 2024 - Enrich Triage with Insider Risk Management

Insider Risk Management alerts will be integrated with Communication Compliance (CC) triage flows, providing a more holistic approach to compliance risk assessment.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC878431](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC878431)

### Late-Dec 2024 - Information Protection: Save Filters for Microsoft 365 Activity Explorer

Admins will be able to save and reuse filters in the Microsoft 365 Activity Explorer. This feature, useful for investigations, will be in public preview by late December 2024.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC713369](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC713369)

### Late – Dec 2024 – SharePoint eSignature Service in Selected European Countries

Microsoft’s SharePoint eSignature service, initially launched in the US in late November 2023, is now expanding its availability to include users in selected European countries. Starting late-Dec 2024, users of selected European countries can use SharePoint Online to request eSignatures on PDF documents.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC800502](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC800502)

##   
Existing Functionality Changes

### Dec 2024 - Reintroduction of WhatsApp for MFA OTPs

Microsoft will reintroduce WhatsApp as a channel for MFA OTPs starting December 2024. Initially available for users in India, it will expand to more countries in the future. Users enabled for MFA text messages will be able to receive OTPs on WhatsApp after the rollout.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC926195](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC926195)

### Dec 2024 - Replacement of Forms App by Polls in Teams Meetings

The Forms app in Teams Meetings will be replaced by the Polls app to enhance polling options. After this rollout in December 2024, Forms will only support surveys.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoftformsblog/ultimate-polling-and-quiz-experience-with-polls-app-the-replacement-for-forms-ap/3731630](https://techcommunity.microsoft.com/blog/microsoftformsblog/ultimate-polling-and-quiz-experience-with-polls-app-the-replacement-for-forms-ap/3731630)

### Dec 2024 - Faster Detection to Investigation Time in Microsoft Purview Any Change in Compliance Portal

Microsoft will reduce the detection to investigation time from 24 hours to 1 hour in U.S. Government clouds by December 2024, enabling quicker incident responses.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=93324  
](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=93324)

Dec 2, 2024 - Removal of the 14-day Grace Period from Security Defaults MFA  

Microsoft will remove the 14-day grace period for MFA registration when Security Defaults are enabled. Users will now be required to register for MFA at their first login without any skips or delays. This change applies to newly created tenants from December 2, 2024.

  
**_Ref:_** [https://techcommunity.microsoft.com/blog/identity/update-to-security-defaults/4044868](https://techcommunity.microsoft.com/blog/identity/update-to-security-defaults/4044868)

## Action Required

### Dec 31, 2024 - Intune Ending Support for Android Device Administrators on Devices with GMS Access

Google has decided to phase out Android device administrator management. In response, Microsoft Intune will stop supporting this management type on devices using Google Mobile Services (GMS) starting December 31, 2024.  

**Solution:** Stop enrolling devices into Android device administrator and migrate impacted devices to other management methods.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC674247](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC674247)

## Jan 2025 (Attention Needed: 13)

### Jan 2025 - Add Shared Mailbox as Accounts in New Outlook for Windows

Starting January 2025, you’ll be able to add shared mailboxes as accounts in the New Outlook for Windows. With the necessary permissions, you can access these shared mailboxes by providing the user’s credentials.

  
**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=375635  
](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=375635)

### Jan 2025 - New DLP action to Trigger Custom Power Automate Workflows

Microsoft will introduce a new DLP action that triggers custom Power Automate workflows when a DLP policy is violated.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=380721](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=380721)

### January 2025 - Office 365 Connectors Retirement from Microsoft Teams

Owners of webhook-based Office 365 connectors in Teams must update their URLs to a new structure by January 31, 2025. Immediate updates are crucial to avoid service disruptions, as all webhook-based connectors must be updated to continue posting messages in Teams.

Note that the O365 Connectors service will be retired at the end of 2025, so consider migrating your webhooks to the Workflows app within Teams.

**_Ref:_** [https://devblogs.microsoft.com/microsoft365dev/retirement-of-office-365-connectors-within-microsoft-teams/](https://devblogs.microsoft.com/microsoft365dev/retirement-of-office-365-connectors-within-microsoft-teams/)

### Jan 2025 - Short Meeting URLs for Microsoft Teams

Microsoft plans to shorten the meeting URLs for easy sharing across all Teams platforms. Starting early Jan, the URL will contain only the meeting ID and other parameters such as tenant ID, Organizer ID, Conversation ID, and message ID will not be there. This will be the new

URL format: [https://teams.microsoft.com/meet/<meeting\_id>?p=<HashedPasscode>](https://teams.microsoft.com/meet/%3Cmeeting_id%3E?p=%3CHashedPasscode%3E)

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC772556](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC772556)

### Jan 2025 – New Meeting Chat Control in Teams Admin Center

Microsoft will soon introduce a new setting to allow admins to enable chat before and after meetings. After this roll out, admins can be able to configure any of the five options for the “Meeting Chat” setting: On for everyone, On for everyone but anonymous users, Off, In-meeting only for everyone (new), and In-meeting only except anonymous users (new)

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=422808](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=422808)

### Jan 01, 2025- External Recipient Rate Limit in Exchange Online

Exchange Online will begin enforcing an external recipient rate (ERR) limit of 2000 recipients in 24 hours. This restriction will be applicable to the cloud-hosted mailboxes of all newly created tenants.

For existing tenants, this limit will be enforced in the second half of 2025.

**Note:** Exchange Online enforces a Recipient Rate limit of 10000 recipients for cloud-hosted mailboxes. The 2000 ERR limit will become a sublimit within this 10000 Recipient Rate limit.

**_Ref:_** [https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733](https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733)

### Jan 13, 2025 - Microsoft Viva Engage: Retirement of Private Unlisted Groups in External Networks

Microsoft Viva Engage will retire private unlisted groups in external networks on January 13, 2025. After this date, users will no longer be able to create, export, access, or participate in unlisted groups within external networks. So, admins are advised to convert them to listed ones to secure their data.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC867664](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC867664)

### Jan 14, 2025: The PowerPoint QuickStarter Feature will be Completely Retired  

The PowerPoint QuickStarter feature will be completely retired by Jan 14, 2025, for Office versions 2409 for Windows and 2410 for Mac.

**_Ref_**: [https://support.microsoft.com/en-us/office/research-a-topic-with-powerpoint-quickstarter-4784f273-0b2c-456c-9c89-24e5b977c224](https://support.microsoft.com/en-us/office/research-a-topic-with-powerpoint-quickstarter-4784f273-0b2c-456c-9c89-24e5b977c224)

### Early 2025 - MFA Enforcement for CLI, Azure PowerShell, IaC Tools

As part of enforcing MFA for all Azure users, MFA enforcement for Azure Command Line Interface (CLI), Azure PowerShell, and Infrastructure as Code (IaC) tools will gradually be introduced to all tenants starting in early 2025.

**_Ref:_** [https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/update-on-mfa-requirements-for-azure-sign-in/](https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/update-on-mfa-requirements-for-azure-sign-in/)

### Mid-Jan 2025 - Best Practices Configuration Dashboard in Teams Admin Center

A **Best Practices Configuration** dashboard will be available in the Teams Admin Center starting January 2025. This dashboard will help admins confirm that settings align with Microsoft-recommended best practices in areas like:

*   Updating outdated client versions
*   Enabling appropriate ports and protocols
*   Implementing split tunneling for VPNs

Non-conformance will be highlighted, and the dashboard will be enabled by default.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC929034](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC929034)

### Mid-Jan 2025 - Org Explorer Feature for Enterprise Users

Starting mid-January 2025, the Org Explorer feature will be available to all enterprise users, providing insights into internal structures and connections.

**Note**: Switch to the new Outlook for Windows or Outlook for web to have early access to this new feature.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC939925](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC939925)

### Mid-Jan 2025 - ‘Alert Notifications’ Feature Retirement in Microsoft Defender

The "Alerts notifications" feature in Microsoft Defender for Identity will be retired starting mid-Jan 2025.

**Solution:** As an alternative, you can use the "Incident email notifications" page in Microsoft Defender XDR. Admins are encouraged to transfer all existing notification settings to the Email Notifications page in Microsoft Defender XDR.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC912708](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC912708)

### Mid-Jan 2025 - Manage External Access Policies in Teams Admin Center

External access policies in the Teams admin center are currently manageable only through PowerShell cmdlets. However, starting mid-January 2025, admins will be able to use the new external access policy management page to manage policies for users.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC938541](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC938541)

### Mid-Jan 2025 - Block User Feature in Microsoft Teams

Starting January 2025, Microsoft will introduce a block user feature, allowing admins to create a block list that prevents specific users from participating in 1:1 and group chats with the organization.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC888879](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC888879)

### Late-Jan 2025 - Microsoft Auto-Archives Unlicensed OneDrive Accounts

Starting in **late January 2025**, any OneDrive accounts left unlicensed for more than 90 days will be automatically archived, hitting you with extra costs to regain access in Microsoft Archive. Yes! You will be charged $0.05 per GB per month to store unlicensed OneDrive content and $0.60 per GB to reactivate the account in the Microsoft 365 archive.

**_Ref:_** [https://learn.microsoft.com/en-us/sharepoint/unlicensed-onedrive-accounts](https://learn.microsoft.com/en-us/sharepoint/unlicensed-onedrive-accounts)

## Feb 2025 (Attention Needed: 7)

### Early-Feb 2025 - Microsoft Teams: New policy for voice and face enrollment will default to "On"

In February 2025, Microsoft will update the Teams meeting policy by replacing the current **_csTeamsMeetingPolicy_** with the new **_csTeamsAIPolicy_**, which defaults to ON. The new policy will split the single setting for managing both face and voice profiles, known as EnrollUserOverride, into two separate settings: EnrollFace and EnrollVoice. These new settings will allow for independent management of face and voice profiles for users.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC912707](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC912707).

### Feb 2025: Retirement of Monitor Action in the Safe Attachments

Starting February 2025, Microsoft will remove the "Monitor" action in the Safe Attachments policy. Any existing policies set to "Monitor" will be automatically changed to "Block". The recipients, status, or priority configured in the policy will remain unchanged.

Post-retirement, the only available actions in the Safe Attachments policy will be Off, Block, and Dynamic Delivery. Note that you will also lose the ability to "Redirect messages with detected attachments," as this action applies only to the Monitor.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC918563](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC918563)

### Feb 2025 - Bulk Upload for Priority User Groups in Insider Risk Management

Priority user groups in Insider Risk Management are designed to prioritize examining users who handle sensitive information or have a history of risk. Microsoft will soon enhance these groups by enabling admins to bulk upload users via CSV when creating Priority user groups.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=409540](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=409540)

  

### Feb 2025- Removal of the ApplicationImpersonation Role Based Access Control (RBAC) in Exchange Online

Microsoft is going to remove ApplicationImpersonation Role Based Access Control (RBAC) role and its feature set from Exchange Online.

**_Ref_**: [https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-rbac-application-impersonation-in-exchange-online/ba-p/4062671](https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-rbac-application-impersonation-in-exchange-online/ba-p/4062671)  

### Feb 01, 2025 - Azure Key Vault: Soft-delete Will be Enabled in All Key Vaults

Soft Delete preserves deleted key vaults and secrets for up to 90 days, enabling customers to restore them through a self-serve process.

**_Ref:_** [https://learn.microsoft.com/en-us/azure/key-vault/general/soft-delete-change](https://learn.microsoft.com/en-us/azure/key-vault/general/soft-delete-change)

### Mid –Feb 2025 - New Filters in Microsoft Purview Audit Search  

To help you retrieve relevant logs in the Microsoft Purview audit search, Microsoft will include four additional filters in public preview. They are,  

Id - Unique identifier of an audit record.

UserType - The type of user that performed the operation.

UserKey-Azure Active Directory Object ID in GUID format.

ClientIP - The IP address of the device that was used when the activity was logged.

  
**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC789312](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC789312)

### Feb 22, 2025- Viva Topics Retirement  

Viva Topics will be discontinued on February 22, 2025, and Microsoft will no longer pursue new feature enhancements for the platform.

Existing Topic pages will transition to standard SharePoint pages. Users can edit and publish updates as other SharePoint pages. AI-generated Topic pages will no longer be accessible.

**_Ref:_** [https://learn.microsoft.com/en-us/microsoft-365/topics/changes-coming-to-topics](https://learn.microsoft.com/en-us/microsoft-365/topics/changes-coming-to-topics)

## Mar 2025 (Attention Needed:2)

### Mar 2025 - Optical Character Recognition Support for SharePoint Online and OneDrive for Business

Microsoft is bringing Optical Character Recognition (OCR) support to SharePoint Online and OneDrive for Business. This update will allow automated detection of sensitive content within images and enable the application of DLP policies to safeguard data and prevent exfiltration.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=160010](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=160010)

### Mid-Mar 2025 - File Interactive Previews for GCC Environment

Microsoft Teams will roll out interactive file previews for chats and channels in the GCC environment. Initially, users will be able to preview PDFs, with plans to expand to other formats. This feature allows users to view files directly within Teams, reducing context switches and improving workflow efficiency.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC934727](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC934727)

### Mar 30, 2025- Azure AD and MSOnline PowerShell Modules may Stop Working

Microsoft has officially deprecated the Azure AD and MSOnline PowerShell modules Mar’24. However, they will remain functional until March 30, 2025, with support limited to critical security fixes.

**Note:** Only MSOnline versions 1.1.166.0 (2017) and later are guaranteed to function as expected.

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-blog/important-update-deprecation-of-azure-ad-powershell-and-msonline/ba-p/4094536](https://techcommunity.microsoft.com/t5/microsoft-entra-blog/important-update-deprecation-of-azure-ad-powershell-and-msonline/ba-p/4094536)

## April 2025 (Attention Needed: 5)

### April 2025 - Insider Risk Management- Risk AI Usage

Microsoft plans to introduce a new feature in Insider Risk Management, which will be widely available from April 2025. This feature aims to detect potentially risky use of AI. It includes monitoring activities involving sensitive information in prompts generated by AI assistants, covering both copilots and third-party AI applications.

  
**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=In%20development&searchterms=394281](https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=In%20development&searchterms=394281)

### April 2025 - Mail Merge (Advanced) on Outlook on the Web and New Outlook for Windows  

Enhanced mail merge features are coming to Outlook on the Web and the new Outlook for Windows in April 2025. Users will be able to insert dynamic fields into email templates for personalized emails and advanced customizations.  

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047)

### Apr 2025 -General Availability of Microsoft Copilot for GCC Environments  

Microsoft Copilot will be available for GCC users at no additional cost when signed in with a Microsoft Entra account (no Copilot license required).  

**_Ref_**: [https://techcommunity.microsoft.com/blog/publicsectorblog/microsoft-365-copilot-gcc-ga-update-empowering-public-sector-innovation---update/4222952](https://techcommunity.microsoft.com/blog/publicsectorblog/microsoft-365-copilot-gcc-ga-update-empowering-public-sector-innovation---update/4222952)

### Apr 02, 2025 – Retirement of Domain Isolated Web Part in SharePoint Framework

  
As part of the SharePoint Framework domain isolated web parts retirement, this feature will be turned off for newly created tenants starting from Apr 02, 2025.

**Note:** From Apr 02, 2026, existing tenants will no longer be able to use this feature.

**_Ref_**: [https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/](https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/)

### H2 2025- External Recipient Rate Limit in Exchange Online

In the second half of 2025, Exchange Online will start enforcing an external recipient rate (ERR) limit of 2000 recipients within a 24-hour period for all existing tenants. This restriction was already implemented for all newly created tenants in January 2025.

**Note**: Exchange Online enforces a Recipient Rate limit of 10000 recipients for cloud-hosted mailboxes. The 2000 ERR limit will become a sublimit within this 10000 Recipient Rate limit.

**_Ref:_** [https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733](https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733)

## May 2025 (Attention Needed: 2)

### May 2025: OneDrive Sync Admin Reports for GCC

Microsoft will roll out OneDrive Sync Admin Reports in the Microsoft 365 admin center for GCC users by May 2025. These reports will help admins monitor sync client usage and errors across the organization.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=393333](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=393333)

### Mid-May 2025 - New Cmdlet for Content Explorer

A new cmdlet, _Export-ContentExplorerData_, will be fully rolled out to General Availability by mid-May 2025. This cmdlet allows admins to export all scanned content data from Content Explorer, providing a streamlined way to manage and analyze content data.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC698421](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC698421)

## June 2025 (Attention Needed: 3)

### June 2025 - Message Recall Feature for Outlook for Mac

The Cloud-based Exchange Online Message Recall feature will soon be available for Outlook for Mac users, with a preview rollout scheduled for June 2025.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=189804](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=189804)

### June 2025: Block Specific Folders from OneDrive Sync

Starting June 2025, admins can block not just files or extensions but also specific folders from syncing with OneDrive through Group Policy.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=178292](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=178292)

### June 2025 - Date Lifecycle Management and Power Automate Integration in U.S Government Clouds

U.S. government cloud users can automate actions on items at the end of their retention period using Power Automate by June 2025.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=117523](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=117523)

## Q3 2025 (Attention Needed: 3)

### July 1, 2025- Classic Teams Desktop App End of Availability

Starting July 1, 2025, classic Teams desktop app will reach end of availability for all users irrespective of OS.

**Note**: From Oct 23, 2024, classic Teams desktop app on Windows 7,8,8.1 and Mac OS Sierra (10.12) will reach end of availability.

**Solution:** Users need to switch to new Teams, or they can use Teams web app (on supported browser) as an alternative.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783985](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783985)  

### Sep 2025- Basic Auth for Client Submission (SMTP AUTH) Retirement in Exchange Online

Exchange Online will permanently remove support for Basic authentication with Client Submission (SMTP AUTH) in September 2025.

**Solution:** You can start to use OAuth with Client Submission (SMTP AUTH).

**_Ref_**: [https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-retire-basic-auth-for-client-submission-smtp/ba-p/4114750](https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-retire-basic-auth-for-client-submission-smtp/ba-p/4114750)

### Sep 30, 2025 – Retirement of Managing Authentication Methods in Legacy MFA &SSPR Policy

Starting Oct 2025, Microsoft no longer allow authentication methods to be managed in the legacy MFA and SSPR policies.

**Solution:** Organizations should use the converged authentication methods policy where methods can be managed centrally for all authentication scenarios including passwordless, MFA and SSPR.

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448)

### Oct 2025 - Retirement of the SharePoint SendEmail API

The _SP.Utilities.Utility.SendEmail_ API in SharePoint will be retired on October 31, 2025. Any components, custom code, or Power Automate flows relying on this API should be updated before its retirement.

Consider transitioning to modern solutions such as the Microsoft Graph API or Power Automate’s Outlook connector for email functionality.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC921752](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC921752)

## Q4 2025 (Attention Needed: 2)

### Oct 14, 2025- End of Extended Support for Office 2016 & Office 2019

  
Office 2016 and Office 2019 extended support ends in 2025.

**Solution:** You can start to use the latest supported versions.

**_Ref:_** [https://learn.microsoft.com/en-us/lifecycle/products/microsoft-office-2016](https://learn.microsoft.com/en-us/lifecycle/products/microsoft-office-2016)

### Dec 2025 - Existing Office 365 Connectors will stop Working

Existing Office 365 connectors will continue to work until December 2025, after which they will no longer work.

**_Ref:_** [https://learn.microsoft.com/en-us/power-bi/connect-data/service-publish-from-excel](https://learn.microsoft.com/en-us/power-bi/connect-data/service-publish-from-excel)

## 2026 (Attention Needed: 9)

### Jan 13, 2026 – End of Extended Support for Microsoft Advanced Threat Analytics 1.x

Microsoft Advanced Threat Analytics (ATA) extended support will be ended on January 13, 2026.

**Solution**: Updates for Microsoft ATA are available from Microsoft Update or by manual download.

**_Ref_**: [https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c](https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c)

### Mar 31, 2026- Deprecation of ‘Require Approved Client App’ Conditional Access Grant

The Require approved client app control in Azure Active Directory (Azure AD) Conditional Access will be retired and no longer enforced.

**Solution:** You can make use of the “Require app protection policy” control, which has all the same capabilities

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448)

### Apr 02, 2026 – SharePoint 2013 Workflow Retirement

SharePoint 2013 workflows will no longer be supported.

**Solution:** You can move to Power Automate or other supported solutions.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC542767](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC542767)

### Apr 02, 2026- SharePoint Add-in Retirement  
  

SharePoint Add-Ins will stop working for existing tenants from April 2nd, 2026.

**Solution:** Admins can run the [Microsoft 365 Assessment tool](https://aka.ms/assessment/addinsacs) to scan their tenants for SharePoint Add-In usage.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865)

### Apr 02, 2026 – Azure ACS Retirement in Microsoft 365

After April 2, 2026, existing tenants using Azure ACS for custom or third-party app access in SharePoint Online will no longer function due to its retirement.

**Solution:** Admins can utilize the Microsoft 365 Assessment tool to scan the tenants for any usage of Azure Access Control Service (ACS) and [migrating from Azure ACS to Microsoft Entra ID](https://aka.ms/retirement/acs/guidance).

**_Ref:_** [https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/retirement-announcement-for-azure-acs](https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/retirement-announcement-for-azure-acs)

### Apr 02, 2026 - Retirement of Domain Isolated Web Part in SharePoint Framework

  
From Apr 02, 2026, the domain isolated web part feature will be fully retired. Organizations using this feature will receive an error message.

**Solution:** Update your domain isolated web parts to regular web parts and redeploy them to ensure continued functionality.

**_Ref:_** [https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/](https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/)

### July 14, 2026- InfoPath 2013 Client and InfoPath Forms Services in SharePoint Online will be Retired

  
  
InfoPath Client 2013 will reach the end of its extended support period on July 14, 2026, and to keep an aligned experience across Microsoft products, InfoPath Forms Service will be retired from SharePoint Online.

**Solution:** To understand the usage of InfoPath within your organization, you can utilize the [Microsoft 365 Assessment tool](https://aka.ms/assessment/infopath) to scan your tenant and analyze InfoPath usage. If you are currently using InfoPath, you can initiate the migration process to modern alternatives such as Power Apps, Power Automate, or Forms.

**_Ref_**: [https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190](https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190)

### Oct 01, 2026- Retirement of Exchange Web Services in Exchange Online

  
October 1, 2026, Microsoft will start blocking EWS requests from non-Microsoft apps to Exchange Online. The changes in Exchange Online do not affect Outlook for Windows or Mac, Teams, or any other Microsoft product.

**Solution**: Migrate your applications to Microsoft Graph to access Exchange Online data and gain access to the latest features and functionality.

**_Ref:_** [https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-exchange-web-services-in-exchange-online/ba-p/3924440  
](https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-exchange-web-services-in-exchange-online/ba-p/3924440)

### Oct 01, 2026 – Sign-in Risk Policy and User Risk Policy Retirement from Entra ID Protection

User risk policy or Sign-in risk policy UX in Entra ID Protection (formerly Identity Protection) will be retired on October 1, 2026.

**Solution:** Migrate Sign-in risk and User risk policies to Conditional Access.

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/what-s-new-in-microsoft-entra/ba-p/3796395](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/what-s-new-in-microsoft-entra/ba-p/3796395)

### Oct 13, 2026- Retirement of Microsoft Publisher

  
In October 2026, Microsoft will discontinue Publisher in Microsoft 365, with on-premises suite support ending. While support lasts, they're exploring modern alternatives across Word, PowerPoint, and Designer for common Publisher tasks, with updates forthcoming.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC716267](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC716267)

In conclusion, navigating the ever-evolving landscape of Microsoft 365 requires staying informed about the changes. By proactively adapting to these changes, you can optimize your Microsoft 365 experience, maximize productivity, and effectively plan for the future.  

We are committed to keeping this blog updated with the latest information, so stay tuned for upcoming updates.

### [https://blog.admindroid.com/microsoft-365-end-of-support-milestones/](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/)