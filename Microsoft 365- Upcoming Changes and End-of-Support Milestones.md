# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.  
  
Discover the **key changes, deprecations**, and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

  
Here is a list of changes categorized by month and year.  

*   July (Retirements: 7, New Features: 11; Enhancements: 8, Existing Functionality Changes: 5, Action Needed: 6)
*   August 2025 (Retirements: 4, New Features: 7, Enhancements: 3, Existing Functionality Changes: 1, Action Needed: 3)
*   September 2025 (Attention Needed: 11)
*   Q4 2025 (Attention Needed: 13)
*   2026 (Attention needed: 20)

  

## July 2025

## Retirements

### July 1, 2025 - Microsoft 365 Business Premium and Office 365 E1 Grant Discontinuation for Non-profits

Microsoft is retiring the Microsoft 365 Business Premium and Office 365 E1 grant offers for non-profits. Going forward, nonprofits can receive up to 300 licenses of Microsoft 365 Business Basic and up to 75% discounts on other Microsoft 365 plans, including Business Premium and Office 365 E1.

**Solution**: Move to the Microsoft 365 Business Basic grant or another Microsoft 365 offer for nonprofits.

**_Ref_**: [https://partner.microsoft.com/en-ca/asset/collection/microsoft-365-business-premium-and-office-365-e1-grant-discontinuation#/](https://partner.microsoft.com/en-ca/asset/collection/microsoft-365-business-premium-and-office-365-e1-grant-discontinuation#/)

  

### July 1, 2025 - End of Support for Viva Engage Private Content Mode

Microsoft Viva Engage's private content mode will retire on _June 30, 2025_. So, after June 30, private content mode will automatically be disabled for all tenants. This change applies to Viva Engage on the web, in Microsoft Teams, and in Outlook. The setting will also be removed from the classic Yammer admin center as part of the ongoing transition to Viva Engage.

**Solution:** To manage access without private content mode, organizations can use roles for viewing private communities, group management, compliance access, and supervisor mode for API access.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1045211](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1045211)

### Early-July 2025 - Deprecation of Monitor Action in Microsoft Defender Safe Attachments Policies

The Monitor action in Safe Attachments policies allows emails with malicious attachments to be delivered without blocking them, while still logging the detection for review and tracking. Microsoft will retire this Monitor action in early-July 2025, and it will be removed from both the Defender portal and PowerShell. Policies currently using _Monitor_ will be automatically switched to _Block_, with no changes to recipients, status, or priority.

**Solution:** Switch Safe Attachments policies from Monitor to Block to maintain protection. Alternatively, if you need to run the policy in audit mode, consider using [Evaluation mode](https://security.microsoft.com/atpEvaluation) as a replacement.

**_Ref:_** [https://admin.microsoft.com/?#/MessageCenter/:/messages/MC918563](https://admin.microsoft.com/?#/MessageCenter/:/messages/MC918563)

### July 2025 – SharePoint Alerts Retirement

Starting July 2025, Microsoft will no longer allow users to create new SharePoint alerts for newly onboarded tenants. This change is part of Microsoft's effort to modernize notification experiences across SharePoint Online. After a gradual phase-out, SharePoint alerts will be completely retired and no longer available.

**Solution:** Microsoft recommends moving SharePoint Alerts to either Power Automate for advanced workflows or SharePoint Rules for basic notifications. Admins can use the Microsoft 365 Assessment tool to review alerts and plan the transition smoothly.

**_Ref_**: [https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f](https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f)

### July 28, 2025 - Microsoft OneNote to Retire Legacy .DOC Export Option for Windows

Starting July 28, 2025, Microsoft OneNote for Windows will no longer support exporting pages or sections as Word 97-2003 (.doc) documents.

**Solution:** This change may impact workflows that rely on the legacy format, so users are advised to switch to modern formats like .docx.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1104312](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1104312)

### July 31, 2025 – Retirement of Organization Data Type in Microsoft Excel

Microsoft Excel’s _Organization_ data type feature, which enabled admins to access and integrate data from their Power BI datasets directly within Excel, will be retired on July 31, 2025.

**Solution:** Use Get Data > From Power BI on the Data ribbon in Excel to import data from Power BI. Alternatively, you can use an add-in to create custom data types for your organization.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1072405](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1072405)

### July 31, 2025 – TLS Deprecation for Fabric Platform

As part of ongoing efforts to strengthen security, the Fabric Platform will require all outbound connections to customer data sources to use TLS version 1.2 or higher. Support for TLS 1.1 and older versions will end on July 31, 2025.

**Solution:** If systems are still running TLS 1.1 or earlier, update them to TLS 1.2 or higher promptly to avoid service disruptions.

**_Ref:_** [https://blog.fabric.microsoft.com/en-US/blog/tls-deprecation-for-fabric/](https://blog.fabric.microsoft.com/en-US/blog/tls-deprecation-for-fabric/)

## New Features

### July 2025 - Native Forms within SharePoint Document Libraries

Microsoft will introduce native forms in SharePoint document libraries to boost productivity. After this rollout, admins will be able to create custom forms directly within libraries for seamless file uploads and metadata submission.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?id=489834](https://www.microsoft.com/en-US/microsoft-365/roadmap?id=489834)

### July 2025 - Microsoft Purview Compliance Portal: Scan Cold Files in SharePoint and OneDrive for Sensitive Information

A new capability in the Microsoft Purview compliance portal will allow admins to scan existing files at rest in SharePoint and OneDrive for Business to detect sensitive information. This feature supports the classification and labeling of files that have never been scanned or that haven’t been scanned in a while.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?id=475062](https://www.microsoft.com/en-US/microsoft-365/roadmap?id=475062)

### July 2025 - Microsoft 365 Backup Adds Protection Unit-Level Deletion

A protection unit refers to a OneDrive account, SharePoint site, or Exchange Online mailbox that is protected in the Backup tool. Microsoft 365 Backup now introduces deletion of backups at the protection unit level, available in _public preview_ from July 2025.

This update helps organizations manage storage, cut costs, and meet GDPR deletion requests. As deletions are permanent, admins are advised to proceed with caution.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=464994](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=464994)

### Early-July 2025 - New File Attachments in External 1:1 and Group Chats in Teams

Currently, users can’t attach files directly to the compose box in 1:1 or group chats with external users. As a workaround, they had to manually copy and paste a file link into the chat.

Starting early-July, Microsoft Teams is rolling out support for file attachments in external 1:1 and group chats, making cross-organization collaboration more seamless. The feature is **off by default**, and admins can enable it via PowerShell using the **_FileSharingInChatsWithExternalUsers_** policy to maintain control and ensure secure sharing.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1102790](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1102790)

### Early-July 2025 - New Audit Logs for Give Control, Take Control, and Screensharing in Microsoft Teams

Microsoft will roll out detailed audit logs for _Give Control, Take Control, and Screen Sharing_ activities in Microsoft Teams this July. The logs record who performed each action with timestamps and usernames. This update is available for Teams on Windows, Mac, and the web.

**_Ref_**: [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1090698](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1090698)

### Early-July 2025 - Facilitator Agent in Microsoft Teams

Microsoft Teams will introduce a Facilitator Agent to enhance collaboration by automating notetaking and summarizing key discussions during meetings and chats. This feature also enables real-time co-authoring, allowing participants to edit and collaborate on notes seamlessly.

**Note:** It applies to Teams for Windows desktop, Teams for Mac desktop, Teams for the web, and Teams for iOS/Android. Also, a Microsoft Copilot license is required to use this feature.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1017117](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1017117)

### Early-July 2025 - New Multi-Admin Notifications for Microsoft 365 Backup

Starting early July 2025, Microsoft 365 Backup introduces multi-admin notifications to improve visibility and admin awareness. Organizations can configure a centralized notification list for backup events in one of the following ways:

*   Notify both global admins and Microsoft 365 Backup admins
*   Notify only global admins
*   Notify only Microsoft 365 Backup admins
*   Specify a custom set of recipients, such as users, mail-enabled security groups, or distribution lists

Notifications will be triggered for key events such as backup disablement, offboarding, restore initiation, and policy updates.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=464993](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=464993)

### Mid-July 2025 - Data Security Posture Management for AI in Microsoft Purview

Microsoft is bringing a dedicated AI page to its Data Security Posture Management solution in Microsoft Purview. This addition helps organizations discover and secure AI activity across Microsoft Copilot, agents, and other AI apps.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1066341](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1066341)

### Mid-July 2025 - Drag and Drop Between Accounts Coming to New Outlook for Windows

The new Microsoft Outlook for Windows adds drag and drop support to attach emails and files between personal or enterprise accounts, improving cross-account productivity. This update also allows attaching content from shared mailboxes or shared folders into another mailbox. Admins can control this capability using the **_ItemsToOtherAccountsEnabled_** parameter in _OWAMailboxPolicy_.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1104315](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1104315)

### Mid-July 2025 - Network-Level Detection for Cloud and AI Activity in Microsoft Purview Insider Risk Management

Starting mid-July, Microsoft Purview Insider Risk Management introduces network-level detection to identify sensitive files and text shared to any cloud application or website, including generative AI platforms.

This enhances the detection of insider risks such as intellectual property theft, data leakage, and policy violations.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1102773](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1102773)

### Late-July 2025 Microsoft Defender XDR: Scoped AD Domain Access for Defender for Identity

Microsoft Defender for Identity will support Active Directory domain-based scoping. This enables more granular role-based access control (RBAC) and enhances security in complex environments through domain-specific access control.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1091443](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1091443)

## Enhancements

### July 2025 - Microsoft Purview Adds Email Attachment Preview in Content Explorer

From July 2025, Microsoft Purview Content Explorer will support previewing email attachments flagged for sensitive data in Exchange Online. Previously limited to message body view, this enhancement allows admins to inspect flagged attachments without downloading.

**_Ref:_** [https://admin.microsoft.com/?#/MessageCenter/:/messages/MC1090691](https://admin.microsoft.com/?#/MessageCenter/:/messages/MC1090691)

### July 2025 - Allow Recording and Transcription by Default in Teams Calling Global Policy

Starting July 2025, Microsoft Teams’ global calling policy will have recording and transcription enabled by default for new tenants and those using the default global policy. This update aligns calling policies with Teams meetings policies and expands access to AI-powered features like Calls Recap and Calling Copilot.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1084030](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1084030)

### Early-July 2025 - New Outlook to Support Admin Setting for S/MIME Signature Inheritance in Replies

New Microsoft Outlook for Windows desktop will support a new admin setting, **_NoSignOnReply_**, to control whether S/MIME signatures are inherited in replies. Rolling out from early-July 2025, this setting is not applicable to Outlook for web.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1072404](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1072404)

### Early-July 2025 - Microsoft Purview Compliance Portal: Timeline View of User Activity

A new timeline of user activity is being introduced to help you better understand potential data security or compliance incidents. This comprehensive view displays all flagged interactions for a user in a single, easy-to-follow timeline, providing insights into potentially risky behavior.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1079735](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1079735)

### Mid-July 2025 - Microsoft Purview Integrates Insider Risk Management with Data Security Investigation

Beginning mid-July 2025, Microsoft Purview will integrate Insider Risk Management (IRM) with Data Security Investigation (DSI). This allows admins to launch pre-scoped investigations directly from IRM cases for faster incident response.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1091445](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1091445)

### Mid-July 2025 - Microsoft 365 Default Setting Changes to Strengthen Security

As part of the _Microsoft Secure Future Initiative (SFI)_ and the _“Secure by Default”_ principle, Microsoft 365 is updating default settings to block legacy authentication and enforce admin consent for third-party app access.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1097272](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1097272)

### Mid-July 2025 - Microsoft Expands Best Practice Configurations Dashboard in Teams Admin Center

Starting mid-July 2025, the Microsoft Teams admin center will enhance the Best Practice Configurations dashboard by adding new monitoring scenarios focused on meeting experiences. These include checks for bypassing local proxy, bypassing cloud proxy, and DNS resolution failures.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1103605](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1103605)

### Mid-July 2025 – Information Protection: On-demand Classification of Files in SharePoint and OneDrive for Business

Microsoft Purview is introducing on-demand classification for files in SharePoint Online and OneDrive, enabling the discovery and classification of sensitive content in historical data—including files that were never scanned or haven't been scanned in a while. On-demand classification of files is a pay-as-you-go feature (not part of the E5 license).  
  
**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1013459](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1013459)

## Existing Functionality Changes

### July 1, 2025 - Microsoft Teams Live Event Assistance Program (LEAP) Moves to Paid Model

Microsoft 365 Live Event Assistance Program (LEAP), previously a free support service, will become a paid offering under Microsoft Unified, now called _Teams Events Hosting Assistance_. Starting July 1, 2025, new event support requests will require a Unified contract and VBD.

Microsoft is also introducing _Teams Events Advanced Production Services_ for enhanced support with town halls, webinars, and large events.

**_Ref:_** [https://adoption.microsoft.com/en-us/virtual-event-guidance/assistance/](https://adoption.microsoft.com/en-us/virtual-event-guidance/assistance/)

### July 2025 - Insider Risk Management: Increasing Policy Template Limits

Currently, Insider Risk Management allows up to 20 policies per template. However, Microsoft is increasing the limit to 100 active policies in total, removing template-specific restrictions. This means you can now create up to 100 policies across all templates instead of being limited per template.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=477364](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=477364)

### Early-July 2025 - Outlook to Block Additional File Types for Enhanced Security

Microsoft is updating the default list of blocked file types in _OwaMailboxPolicy_ by adding **_.library-ms_** and **_.search-ms_** extensions. With this change, Outlook for web and the new Outlook for Windows will start blocking these file types by default beginning early July 2025.

If users need to access these file types, admins can use the **_Set-OwaMailboxPolicy_** cmdlet to add them to the **_AllowedFileTypes_** property before the rollout.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1090702](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1090702)

### Early-July 2025 - Microsoft Entra ID: Updated Guest Sign-In Experience for B2B Users

Starting early-July 2025, guest users will be redirected to their home organization’s sign-in page after entering their email, improving clarity and reducing confusion during B2B sign-ins. This is to ensure that users clearly see their own tenant’s branding and URL, helping them identify which credentials to use.

**_Ref:_** [https://admin.microsoft.com/?#/MessageCenter/:/messages/MC1103608](https://admin.microsoft.com/?#/MessageCenter/:/messages/MC1103608)

### Late-July 2025 - Microsoft Pauses Unified Teams App Management Rollout

The rollout of unified management for Teams apps across Teams, Outlook, and the Microsoft 365 app is currently on hold, with an update expected by late July 2025. Once released, the feature will unify app settings into a single platform for consistent availability across clients.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC796790](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC796790)

## Action Needed

### After July 1, 2025 – Azure AD PowerShell Retirement

The Azure AD PowerShell module will be retired after July 1, 2025.  

**Solution**: Migrate to Microsoft Graph PowerShell SDK or Microsoft Entra PowerShell module.  

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991)

### July 1, 2025 – DNS Provision Change

Starting July 1, 2025, A records for new Accepted Domains will move from mail.protection.outlook.com to subdomains under mx.microsoft to support DNSSEC.

**Action Required:** If you have automation that configures MX records, you must update it to use the **List serviceConfigurationRecords Graph API** to retrieve the correct MX values. After July 1, this API will be the only reliable source for MX records. Failing to update may result in mail flow issues for new domains.

**_Ref_**: [https://admin.microsoft.com/#/MessageCenter/:/messages/MC1048624](https://admin.microsoft.com/#/MessageCenter/:/messages/MC1048624)

### July 1, 2025- Classic Teams Desktop App End of Availability

Starting July 1, 2025, classic Teams desktop app will reach end of availability for all users irrespective of OS.

**Solution:** Users need to switch to new Teams, or they can use Teams web app (on supported browser) as an alternative.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783985](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783985)

### July 1, 2025 - Reshare SharePoint Content After Entra B2B Integration

Effective July 1, 2025, external users will lose access to content shared via SharePoint One Time Passcode (OTP) prior to enabling Microsoft SharePoint and OneDrive integration with Entra B2B. To restore access, the content must be reshared.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1089315](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1089315)

### July 30, 2025 - Microsoft Teams Android Devices Moving to Modern Authentication

On July 31, 2025, Microsoft is transitioning certified Microsoft Teams Android devices to modern authentication using Entra ID-based tokens. This update enables advanced security capabilities, including Continuous Access Evaluation and enforcement of IP-based Conditional Access policies.

Devices with supported app versions will automatically switch to modern authentication, while those on unsupported versions will continue using legacy authentication. Kindly note, Teams Displays are excluded from this milestone.

**Solution:** Organizations must update devices to the required app versions by **_December 31, 2025_**, to avoid service disruption.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1088732](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1088732)

### July 31, 2025 - Updates to Required Permissions for Microsoft Graph Beta API Device Management

Starting July 31, 2025, the Microsoft Graph Beta API /deviceManagement endpoints will require _DeviceManagementScripts.Read.All or DeviceManagementScripts.ReadWrite.All_ permissions to operate.

**Solution:** Any existing apps, scripts, or tools using _DeviceManagementConfiguration.ReadWrite.All or DeviceManagementConfiguration.Read.All_ permissions must be updated to use the new permissions.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1066336](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1066336)

## August 2025

## Retirements

### August 1, 2025 - Retirement of Classic e-Discovery in Microsoft Purview

Starting August 1, 2025, Microsoft will retire Classic eDiscovery, including Content Search, eDiscovery (Standard), and eDiscovery (Premium), from the Microsoft 365 Purview portal.

**Solution:** Transition to the new unified eDiscovery for faster and improved search and investigation capabilities.  

**_Ref:_** [https://learn.microsoft.com/en-us/purview/ediscovery-legacy-retirement](https://learn.microsoft.com/en-us/purview/ediscovery-legacy-retirement)

### Early-August 2025 - Retirement of Microsoft Project for the Web and Project in Teams

Microsoft Project for the web and Project in Teams will be retired in August 2025. Users will be redirected to Planner for the web and Planner in Teams, where existing Project features will be integrated to ensure a seamless transition.

**Solution:** Users should migrate Roadmap data to Portfolios and re-pin Projects in Teams tabs using Planner.  

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1068905](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1068905)

### Mid-August 2025 - Outlook for Mac to Retire Admin Option for Legacy Switch

Starting mid-August 2025, the New Outlook for Mac will become the default for Current Channel users (version 16.100+), and the admin setting _EnableNewOutlook_ will be retired. By mid-October 2025 (version 16.102), switching back to Legacy Outlook will no longer be possible.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1098932](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1098932)

### Mid-August 2025 - Deprecation of Speaker Coach in Microsoft Teams

Speaker Coach in Microsoft Teams offers private, personalized feedback on speaking performance during meetings and provides a summary afterward. The feature (Preview) will be retired starting mid-August 2025 across Teams for Windows, Mac, and the web.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1101903](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1101903)

## New Features

### August 2025 - Mail Merge (Advanced) on Outlook on the Web and New Outlook for Windows

Enhanced mail merge features are coming to Outlook on the Web and the new Outlook for Windows in August 2025. Users will be able to insert dynamic fields into email templates for personalized emails and advanced customizations.  

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047)

### August 2025 - Microsoft Purview Launches AI-Powered Data Security Investigations Solution

Microsoft Purview Data Security Investigations (DSI) is an AI-driven solution designed to help security teams identify, analyze, and mitigate data risks. It enables deep content analysis, visualizes correlations, and supports policy refinement within a unified experience.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1047912](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1047912)

### August 2025 – Decoupling of Policy Tips and Email Notifications for SharePoint and OneDrive

Currently, enabling email notifications for a DLP policy also requires enabling the policy tips, and vice versa. However, Microsoft will soon allow admins to configure email notifications and policy tips independently for SharePoint and OneDrive DLP policies.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=394279](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=394279)

### August 2025 – Microsoft Purview DLP to Restrict Copilot from Processing Labeled Emails

Starting August 2025, Microsoft Purview Data Loss Prevention (DLP) will prevent Microsoft 365 Copilot from processing emails that contain sensitivity labels. The feature enhances data protection by using DLP policies to detect sensitivity labels and block access within Copilot chat experiences.

**_Ref_**: [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1088731](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1088731)

### Early-August 2025 - Insider Risk Management- Risky AI Usage

New detections in Insider Risk Management will be generally available, enabling admins to identify risky AI activity, such as sensitive prompts, risky intents, and AI-generated sensitive content. This applies to M365 Copilot, Copilot Studio, and ChatGPT Enterprise, contributing to Adaptive Protection risk levels.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC947048](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC947048)

### Early-August 2025 - Microsoft Teams to Support Silent Test Calls for Network Readiness

Microsoft Teams will allow IT admins to run silent call simulations to proactively test network readiness and detect issues early. Available for Windows and Mac desktops, this feature requires a Teams Premium license.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1089323](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1089323)

### Mid-August 2025 - Microsoft Teams Adds Rule-Based Management for Microsoft 365 Certified Apps

Microsoft Teams now allows admins to manage Microsoft 365 certified apps based on custom rules in the Teams admin center. App availability can be controlled by permissions accessed and publisher names, with trusted apps enabled automatically based on defined conditions.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=485712](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=485712)

## Enhancements

### August 2025: Microsoft Purview: Audit Log Message Update for Role Group Changes

Microsoft Purview enhances audit log messages for role group membership changes, specifically for _GrantPermission_ and _DeletePermission_ operations under the SecurityComplianceRBAC workload. The _PreExecutionMessage_ and _PostExecutionMessage_ fields will provide clearer insights. Organizations using these logs programmatically should update their parsing logic accordingly.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1090695](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1090695)

### August 1, 2025 - Microsoft Fabric to Enforce 1,000 User/Group Limit on Workspace Roles

Microsoft Fabric will limit each workspace to a maximum of 1,000 users or groups in workspace roles _(Admin, Member, Contributor, Viewer)_. Overlimit workspaces can’t add more users or groups until they are under the threshold.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1098946](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1098946)

### Mid-August 2025 - Microsoft Teams Web Adds Apple and Google Sign-In for Consumers

Microsoft Teams on the web is introducing _Continue with Apple_ and _Continue with Google_ sign-in options for a limited set of consumer users as part of a **private preview**. These options may also appear for enterprise users based on authentication settings. Existing sign-in methods remain unchanged.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1102784](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1102784)

## Existing Functionality Changes

### August 20, 2025 – Sender Email Address Update for Microsoft Teams DLP Generate Incident Report Emails

Microsoft is changing the sender address for Teams DLP Generate Incident Report (GIR) emails. After August 20, 2025, only the new address ([no-reply@teams.mail.microsoft.com](mailto:no-reply@teams.mail.microsoft.com)) will be used. If your inbox rules are set to act on the old sender address, update them to match the new address.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1064354](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1064354)

## Action Needed

### August 14, 2025 - Microsoft Entra ID to Limit Access Review Data Retention to 12 Months

Starting August 15, 2025, Microsoft Entra ID will retain only the past 12 months of access review data in the UI and APIs. Older data will no longer be accessible, and the Review history report will reflect this limit. This change does not impact audit logs and is enabled by default.

**Solution:** To avoid data loss when the 12-month access review data retention policy takes effect on August 15, 2025:

*   Export all historical review data using Microsoft Graph APIs before the cutoff date.
*   Use queries to [create customized reports in Azure Data Explorer](https://learn.microsoft.com/en-us/entra/id-governance/custom-entitlement-report-with-adx-and-entra-id#example-various-queries-that-use-access-reviews) and transfer historical data for audit or compliance purposes.
*   Set up an annual process to generate and securely store review reports to maintain long-term data access.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1101895](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1101895)

### August 31, 2025 - Legacy Message Trace Experience Retires in Exchange Online

With the introduction of the new Message Trace in Microsoft Exchange Online, the legacy experience will retire on September 1, 2025. The updated version offers improved performance and a modern interface, replacing:

1.  Legacy Message Trace UI in the EAC
2.  Legacy cmdlets: **Get-MessageTrace, Get-MessageTraceDetail**
3.  Reporting Web Service support for Message Trace data

**Solution:** As the new Message Trace becomes the default, admins should update scripts to use **_Get-MessageTraceV2_** and **_Get-MessageTraceDetailV2_**, and complete the transition by **August 31, 2025**. The new UI remains enabled in the Exchange admin center.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1092458](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1092458)

### August 31, 2025 - Retirement of Azure AD Graph API

Azure AD Graph APIs will retire in early September 2025. Applications using them will stop working, and temporary outage tests will occur between late July and early September.

**Solution:** Use the _Recommendations_ tab in the Microsoft Entra admin center to identify affected apps and migrate to Microsoft Graph APIs by August 31, 2025.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1101901](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1101901)

## September 2025 (Attention Needed: 11)

### Early-Sep 2025 - General Availability of Progressive Alert Scoring in IRM

Microsoft will roll out a new feature -" Progressive alert scoring" in Microsoft Purview Insider Risk Management. Currently, user activities that could potentially result in data security incidents will be assessed once every 24 hours. After this rollout, the assessment of user activities will be done more frequently within a 24- hour period, along with alert insights. This feature will be generally available for GCC, GCC-High, DoD environments by early-Sep 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC707653](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC707653)

### Early-Sep 2025 - Microsoft Teams Expands Peripheral Health Reporting for BYOD Spaces

From mid-September 2025, admins can proactively monitor device issues in BYOD rooms and desks using enhanced peripheral health reports in the Pro Management portal. Reports detect faulty, missing, or undetectable devices before users are impacted.

**_Ref:_** [https://admin.microsoft.com/?#/MessageCenter/:/messages/MC1090689](https://admin.microsoft.com/?#/MessageCenter/:/messages/MC1090689)

### Early-Sep 2025 - Microsoft Rolls Out ‘Reject Direct Send’ Parameter in Exchange Online

Microsoft Exchange Online will roll out the _‘Reject Direct Send’_ parameter for the _Set-OrganizationConfig_ cmdlet in September 2025 to help block unwanted Direct Send traffic. This setting allows admins to prevent spoofed emails from on-premises or third-party sources using accepted domains.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/introducing-more-control-over-direct-send-in-exchange-online/4408790](https://techcommunity.microsoft.com/blog/exchange/introducing-more-control-over-direct-send-in-exchange-online/4408790)

### Mid-Sep 2025 - Data Lifecycle Management: Retention Based on “last accessed” for OneDrive and SharePoint Files

Starting mid-Sep2025, Microsoft will introduce a "When items were last accessed" option in Purview retention policies. This will allow admins to configure retention policies based on file access history in OneDrive and SharePoint, enabling the removal of outdated data.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442)

### Mid-Sep 2025 - Microsoft Lists Mobile Apps to Be Removed from App Stores

Microsoft will retire the Microsoft Lists mobile apps for iOS and Android. Starting mid-September 2025, new users will no longer be able to install the apps. Users should switch to the mobile browser experience, which remains supported and regularly updated.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1087635](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1087635)

### Mid-Sep 2025 - Microsoft Loop Usage Reports Coming to Microsoft 365 Admin Center

Microsoft Loop usage data will be available in the Microsoft 365 admin usage dashboards. This enables administrators to monitor adoption and activity without additional configuration.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC929020](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC929020)

### Mid-Sep 2025 - Data Lifecycle Management: Separate Retention Policies for Copilot and AI Apps

Admins can configure distinct retention policies for Microsoft 365 Copilot, Copilot Studio, ChatGPT Enterprise, and other AI apps starting mid-September 2025. This allows faster deletion of Copilot and generative AI interactions for better data governance.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC973511](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC973511)

### Mid-Sep 2025 - Microsoft Purview: Separate Retention Policies for Copilot and Teams Chats

Starting mid-September 2025, admins can configure separate retention policies for Microsoft 365 Copilot interactions and Microsoft Teams chats using PowerShell or the compliance center UI. This feature requires a Microsoft 365 Copilot license and enhances flexibility in managing lifecycle policies for different communication types.

**_Ref:_** [https://admin.microsoft.com/?#/MessageCenter/:/messages/MC926899](https://admin.microsoft.com/?#/MessageCenter/:/messages/MC926899)

### Sep 26, 2025 - Unlicensed OneDrive Accounts to Enter Read-Only Mode

Microsoft will begin transitioning OneDrive accounts that remain unlicensed before July 28, 2025, to read-only mode by **_September 26, 2025_**. Admins should monitor the Unlicensed OneDrive Accounts report and take appropriate actions such as renewing, archiving, or deleting accounts to ensure compliance and uninterrupted access.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC836942](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC836942)

### Sep 30, 2025 – Retirement of Managing Authentication Methods in Legacy MFA &SSPR Policy

Starting Oct 2025, Microsoft no longer allow authentication methods to be managed in the legacy MFA and SSPR policies.

**Solution:** Organizations should use the converged authentication methods policy where methods can be managed centrally for all authentication scenarios including passwordless, MFA and SSPR.

**_Ref:_** [https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-methods-manage#legacy-mfa-and-sspr-policies](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-methods-manage#legacy-mfa-and-sspr-policies)

### Late-Sep 2025 - New Secure Workflow to Bypass Legal Holds and Retention Policies in Microsoft Purview

Admins will have the ability to permanently delete sensitive Exchange mailbox content; bypassing retention policies and eDiscovery holds. This will be possible through the “Priority Cleanup Administrator” role, which grants authorized users’ permission to initiate Priority Cleanup for Exchange, allowing exceptions to standard retention and legal hold policies.

Since this process is irreversible and overrides existing policies, Microsoft has built-in approvals and special auditing for security.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC971035](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC971035)

## Q4 2025 (Attention Needed: 13)

### Oct 2025 – Adding Support for SMTP DANE with DNSSEC for Exchange Online

Microsoft is adding inbound support for SMTP DANE with DNSSEC to Exchange Online GCC High and DoD. This enhancement will be available in preview starting October 2025, further strengthening email security for these environments.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?featureid=361914&searchterms=361914](https://www.microsoft.com/en-in/microsoft-365/roadmap?featureid=361914&searchterms=361914)

### October 2025 - Just in Time Protection on SharePoint in DLP

Microsoft is introducing Just-in-Time protection for SharePoint in Microsoft Purview Data Loss Prevention in preview.

With this feature, organizations can automatically apply DLP restrictions to unclassified files when they are accessed or shared externally. Instead of restricting files in advance, JIT protection enforces security measures only when there is a risk of data leaving the organization.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457)

### October 2025 – New Personalization Settings in Microsoft Purview

Microsoft will introduce a new personalization page in Microsoft Purview, allowing admins to customize their experience. New features will include the ability to pin/unpin solutions, toggle solution bar visibility, access solution walk-throughs, export personalization data, and delete preferences. This update will help streamline the management of individual admin experiences within Microsoft Purview.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=483884](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=483884)

### Oct 14, 2025 - End of Office 2016 and Office 2019 Support

Support for Office 2016 and Office 2019 will end on October 15, 2026. After this date, these versions will no longer receive updates or support.  

**Solution:** Upgrade to Microsoft 365 E3 or Office LTSC 2024 for continued updates and support

**_Ref:_** [https://techcommunity.microsoft.com/blog/officeeos/get-ready-now-one-year-until-office-20162019-end-of-support/4267801](https://techcommunity.microsoft.com/blog/officeeos/get-ready-now-one-year-until-office-20162019-end-of-support/4267801)

### Oct 14, 2025 - Microsoft OneNote for Windows 10 retirement

To offer a unified and modern OneNote experience, Microsoft will retire the OneNote for Windows 10 app on October 14, 2025. After this date, the app will become read-only and will no longer receive support.

**Solution:** Switch users to the Microsoft OneNote for Windows app, which features a sleek, modernized interface and enhanced security.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC899174](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC899174)

### Oct 31, 2025 - Retirement of the SharePoint SendEmail API

The _SP.Utilities.Utility.SendEmail_ API in SharePoint will be retired on October 31, 2025. Any components, custom code, or Power Automate flows relying on this API should be updated before its retirement.

Consider transitioning to modern solutions such as the Microsoft Graph API or Power Automate’s Outlook connector for email functionality.

**_Ref_**:[https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC921752](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC921752)

### After Oct 2025 – End of Support for Legacy Microsoft Outlook for Mac

As part of Microsoft's commitment to a more secure and robust email experience, Microsoft 365 subscriptions linked to a personal, work, or school account will no longer support the legacy version of Microsoft Outlook for Mac.

**Solution:** Upgrade to the latest version of Outlook for Mac, which is built on modern technology for improved performance, security, and reliability.

**_Ref:_** [https://support.microsoft.com/en-us/office/end-of-support-for-legacy-outlook-for-mac-7b9cf644-7035-4345-a151-8c1c7a65ac25](https://support.microsoft.com/en-us/office/end-of-support-for-legacy-outlook-for-mac-7b9cf644-7035-4345-a151-8c1c7a65ac25)

### Nov 2025 - Microsoft Entra ID to Support Passkey Profiles in Authentication Methods Policy

In November 2025, Microsoft Entra ID will introduce support for passkey profiles in the passkey (FIDO2) authentication methods policy. This update allows admins to apply different passkey configurations to specific user groups, offering more granular control. New schema changes will apply if configurations are made through the Azure or Entra portal during the preview.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1097225](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1097225)

### Nov 2025 - Introducing Data Lifecycle Management for Microsoft Planner

Compliance admins can now create retention policies to manage content in Microsoft Planner, including tasks from plans associated with Microsoft 365 groups.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=486828](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=486828)

### Dec 2025 - Integration of New ChatGPT Enterprise Connector with Microsoft Purview Compliance Portal

The ChatGPT Enterprise connector will be integrated into the Microsoft Purview Compliance portal, allowing admins to discover, collect, and store prompts and responses from users' interactions with ChatGPT.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=401125](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=401125)

### Dec 2025 – Microsoft Teams App Usage Report Renamed and Redesigned as Integrated Apps Usage Report

The Teams app usage report is being renamed and redesigned as the Integrated Apps usage report, featuring new charts and metrics. It provides insights into app usage across Teams, Outlook, Microsoft 365 apps, and Copilot extensions. The data is organized by Publishing Type, Host Product, and Platform, with detailed views on app and user activity.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=410248](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=410248)

### Dec 2025 – Microsoft Purview DLP Adds Actionable Email Notifications for End Users

Microsoft Purview Data Loss Prevention now supports actionable email notifications, enabling end users to remediate policy violations directly from their mailbox. For OneDrive and SharePoint files that trigger DLP policies, users can now stop sharing, delete files, apply labels, override policies, report false positives, or indicate they’re unable to act—streamlining the remediation process.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=464996](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=464996)

### Dec 2025 – Inline Detection of Sensitive Data Shared Over Network via Microsoft Purview

Microsoft Purview now integrates with your existing Secure Access Service Edge (SASE) solution, extending Data Loss Prevention (DLP) capabilities to the network layer. This enables admins to intercept, inspect, and enforce DLP policies on network traffic carrying sensitive data.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=488807](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=488807)

## 2026 (Attention Needed: 20)

### Jan 13, 2026 – End of Extended Support for Microsoft Advanced Threat Analytics 1.x

Microsoft Advanced Threat Analytics (ATA) extended support will be ended on January 13, 2026.

**Solution**: Updates for Microsoft ATA are available from Microsoft Update or by manual download.

**_Ref_**: [https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c](https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c)

### Jan 2026 - Microsoft Purview Insider Risk Management Adds OCR Support for Image-Based Risk Detection

Starting January 2026, Insider Risk Management in Microsoft Purview will support Optical Character Recognition (OCR) to detect sensitive content in images shared via SharePoint, Teams messages, and endpoints. This enhancement helps identify potential insider threats such as data leaks or intellectual property theft, while preserving user privacy through pseudonymization and audit controls.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=171185](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=171185)

### Jan 2026 - SharePoint File-Level Archiving Coming to Microsoft 365 Archive

Microsoft 365 Archive will support file-level archiving in SharePoint, enabling more granular retention and storage control. This feature enters public preview in January 2026.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=477371](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=477371)

### March 2026 - Long-term Retention Period for Microsoft 365 Backup

Admins will be able to configure longer-term retention for Microsoft 365 backups, allowing data storage beyond one year. This feature will be available in preview by March 2026.  

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=481834](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=481834)

### Mar 2026 - Retirement of "Require Approved Client App" Grant Control" in Entra ID Conditional Access

The Conditional Access "Require approved client app" grant control is being retired from Microsoft Entra ID & Microsoft Intune by March 2026.

**Solution:** Use the "Require application protection policy" grant control, which offers the same data loss prevention while providing enhanced security benefits.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1029989](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1029989)

### Mar 2026 - Microsoft Purview Information Barriers v2 Now Available for New Customers

Information Barriers v2 (IB v2) will be available by default for all new onboarding tenants. It supports up to 5,000 segments, allows users to be in up to 10 segments, and offers flexible user discoverability while enforcing IB policies.

Existing IB v1 tenants must opt in to upgrade to IB v2 to use these new capabilities. This update applies only to IB v1 customers.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=402516](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=402516)

### Mar 2026 - New DLP Rule Action: Trigger Power Automate Workflows in Microsoft Purview

Starting March 2026, Microsoft Purview will support a new Data Loss Prevention (DLP) rule action that triggers custom Power Automate workflows when a policy match occurs.

Ref: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=380721](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=380721)

### Mar 31, 2026- Deprecation of ‘Require Approved Client App’ Conditional Access Grant

The Require approved client app control in Azure Active Directory (Azure AD) Conditional Access will be retired and no longer enforced.

**Solution:** You can make use of the “Require app protection policy” control, which has all the same capabilities

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448)

### April 2026 – External Recipient Rate Limit in Exchange Online

Exchange Online will begin enforcing an External Recipient Rate (ERR) limit of 2,000 recipients within 24 hours. This restriction will apply to the cloud-hosted mailboxes of all newly created tenants.

**Note:** Exchange Online currently enforces a Recipient Rate limit of 10,000 recipients for cloud-hosted mailboxes. The 2,000 ERR limit will be a sublimit within this 10,000 Recipient Rate limit.

**_Ref:_** [https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733](https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733)

### April 1, 2026 - Automatic Migration to New Outlook for Windows

Microsoft 365 Enterprise users will automatically switch to the new Outlook for Windows, gaining access to modern features like Copilot, theming, and time-saving options such as Pinning and Snoozing emails. A toggle will be available for users to revert to the classic Outlook. Admins can prevent this automatic migration via cloud policy.

**_Ref:_** [https://admin.microsoft.com/#/MessageCenter/:/messages/MC949965](https://admin.microsoft.com/#/MessageCenter/:/messages/MC949965)

### Apr 02, 2026 – SharePoint 2013 Workflow Retirement

SharePoint 2013 workflows will no longer be supported.

**Solution:** You can move to Power Automate or other supported solutions.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC542767](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC542767)

### Apr 02, 2026- SharePoint Add-in Retirement  
  

SharePoint Add-Ins will stop working for existing tenants from April 2nd, 2026.

**Solution:** Admins can run the [Microsoft 365 Assessment tool](https://aka.ms/assessment/addinsacs) to scan their tenants for SharePoint Add-In usage.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865)

### Apr 02, 2026 – Azure ACS Retirement in Microsoft 365

After April 2, 2026, existing tenants using Azure ACS for custom or third-party app access in SharePoint Online will no longer function due to its retirement.

**Solution:** Admins can utilize the Microsoft 365 Assessment tool to scan the tenants for any usage of Azure Access Control Service (ACS) and [migrating from Azure ACS to Microsoft Entra ID](https://aka.ms/retirement/acs/guidance).

**_Ref:_** [https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/retirement-announcement-for-azure-acs](https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/retirement-announcement-for-azure-acs)

### Apr 02, 2026 - Retirement of Domain Isolated Web Part in SharePoint Framework

  
From Apr 02, 2026, the domain isolated web part feature will be fully retired. Organizations using this feature will receive an error message.

**Solution:** Update your domain isolated web parts to regular web parts and redeploy them to ensure continued functionality.

**_Ref:_** [https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/](https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/)

### April 30, 2026 - Basic Auth for Client Submission (SMTP AUTH) Retirement in Exchange Online

Exchange Online will permanently remove support for Basic authentication with Client Submission (SMTP AUTH), reaching 100% rejection of such requests by April 30, 2026.

**Solution:** You can start to use OAuth with Client Submission (SMTP AUTH).

**_Ref_**: [https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-retire-basic-auth-for-client-submission-smtp/ba-p/4114750](https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-retire-basic-auth-for-client-submission-smtp/ba-p/4114750)

### July 14, 2026- InfoPath 2013 Client and InfoPath Forms Services in SharePoint Online Will be Retired

  
  
InfoPath Client 2013 will reach the end of its extended support period on July 14, 2026, and to keep an aligned experience across Microsoft products, InfoPath Forms Service will be retired from SharePoint Online.

**Solution:** To understand the usage of InfoPath within your organization, you can utilize the [Microsoft 365 Assessment tool](https://aka.ms/assessment/infopath) to scan your tenant and analyze InfoPath usage. If you are currently using InfoPath, you can initiate the migration process to modern alternatives such as Power Apps, Power Automate, or Forms.

**_Ref_**: [https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190](https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190)

### July 2026 - SharePoint Alerts Will be Fully Retired

Microsoft will discontinue support for SharePoint Alerts. Existing alerts can no longer be modified and will eventually stop functioning.

**Solution:** Microsoft recommends migrating SharePoint Alerts to Power Automate or SharePoint Rules. Use the Microsoft 365 Assessment tool to review alerts and plan the move.

**_Ref_**: [https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f](https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f)

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