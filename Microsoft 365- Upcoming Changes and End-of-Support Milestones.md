# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.  
  
Discover the **key changes, deprecations**, and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

  
Here is a list of changes categorized by month and year.  

*   June 2025 (Retirements: 4, New Features: 11; Enhancements: 10, Existing Functionality Changes: 5, Action Needed: 2)
*   July (Retirements: 4, New Features: 5; Enhancements: 4, Existing Functionality Changes: 2, Action Needed: 1)
*   August 2025 (Attention Needed: 3)
*   September 2025 (Attention Needed: 4)
*   Q4 2025 (Attention Needed: 11)
*   2026 (Attention needed: 14)

  

## June 2025

### Retirements:

### June 2025 - Meeting Details Experience for Windows 10 will be Removed in OneNote

  
Microsoft plans to end support for OneNote for Windows 10. As part of this change, Meeting Details will be removed from OneNote for Windows 10, starting June 2025.

**Solution:** Switch to the OneNote for Windows app. iPad and Mac users should upgrade to version 16.95 or later to continue accessing Meeting Details.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1085564](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1085564)

### June 30, 2025 - Retirement of Private Content Mode in Via Engage

Microsoft Viva Engage will retire the "Private Content Mode" by June 30, 2025. After this date, verified admins will no longer be able to enable or disable this feature.

**Solution:** The following alternatives will be available:

*   Admins can join private communities without approval: Global or Groups Administrators can now access private communities directly, with no approval needed.
*   Group members and owners visible in Entra ID: All users can see group members and owners in Entra ID, even without being part of the community.
*   eDiscovery admins can access private content: Compliance and eDiscovery admins can search and export private content for legal or audit purposes.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1045211](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1045211)

### June 30, 2025 – Retirement of Recording Initiator Policy in Microsoft Teams

The _Set-CsTeamsRecordingRollOutPolicy_ cmdlet, currently used by admins to assign recording ownership, will retire the _MeetingInitiator_ value in the _MeetingRecordingOwnership_ setting. Instead, recordings will default to the meeting organizer’s OneDrive, even if the organizer did not attend the meeting. If the organizer doesn’t have OneDrive (e.g., shared mailbox), fallback logic will apply in the following order: Organizer → Co-organizer(s) → Initiator → Async Media Storage (AMS).

**Solution:** Make sure to set MeetingRecordingOwnership to MeetingOrganizer before June 30, 2025, to benefit from the smoother fallback logic sooner.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1085569](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1085569)

### Early-June 2025 – Retirement of Sports Calendar Feature in Outlook

Starting early June 2025, Microsoft will retire the Sports Calendar feature (also known as Interesting Calendars) in Outlook. After this date, users will no longer be able to add or update sports calendars in Outlook. Existing subscriptions will also be phased out over time.

**Solution:** Use the _Subscribe from web_ feature in Outlook to manually subscribe to sports calendars from third-party sources that provide iCal links.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1066162](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1066162)

### New Features

  

### June 1, 2025- Identify and Fix Errors with Troubleshoot Copilot in Power Automate

Troubleshoot Copilot can be used inside the cloud flows designer in Power Automate. It helps you identify and fix errors that occur while building or debugging flows by providing corrections. You can then review the changes and choose to accept or discard them.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1066694](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1066694)

### Early-June 2025 - Insider Risk Management: Enhanced Alert and User Investigation with Microsoft Copilot for Security

Admins will gain enhanced alert and user investigation capabilities with Insider Risk Management using Microsoft Copilot for Security. Along with concise alert summaries, admins can delve into specific user activities with Copilot for Security. These enhancements will help admins make informed decisions on whether to investigate users further or dismiss the alerts appropriately.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC851630](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC851630)

### June 2025 - Microsoft Purview Compliance Portal: Scan Cold Files in SharePoint and OneDrive for Sensitive Information

A new capability in the Microsoft Purview compliance portal will allow admins to scan existing files at rest in SharePoint and OneDrive for Business to detect sensitive information. This feature supports the classification and labeling of files that have never been scanned or that haven’t been scanned in a while.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?id=475062](https://www.microsoft.com/en-US/microsoft-365/roadmap?id=475062)

### June –2025 Full-Workload Backup Policies for Microsoft 365 Backup

Admins can create full-workload backup policies to automatically back up all Exchange or OneDrive users and SharePoint sites within the tenant. These policies also ensure that any new users or sites are automatically included in the backup.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?id=464990](https://www.microsoft.com/en-US/microsoft-365/roadmap?id=464990)

### June 2025 - OneDrive: Transfer Ownership of Departing Employees’ Files with Ease

OneDrive introduces new features to help admins manage files when an employee leaves the company.

*   Account cleanup emails are now more prominent to ensure timely action.
*   New filters enable managers to quickly find important files.
*   The improved “Move and keep sharing” feature allows bulk file transfers while preserving existing sharing permissions, making transitions smoother without disrupting collaboration.
*   This transfer process helps safeguard sensitive data, ensures access is correctly passed on, and supports a smooth offboarding experience.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?id=493946](https://www.microsoft.com/en-US/microsoft-365/roadmap?id=493946)

### June 2025 - Date Lifecycle Management and Power Automate Integration in U.S Government Clouds

Starting June 2025, admins can automate actions on items when they reach the end of their retention period using Power Automate. For example, admins can trigger a workflow to execute a complex disposition approval process or move files to an archive automatically.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=117523](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=117523)

### Mid-June 2025 - New Template Gallery in Modern SharePoint

Microsoft will soon roll out 50+ out-of-the-box modern SharePoint page templates to help admins create high-quality, on-brand pages effortlessly. This update includes a centralized template gallery that allows users to easily discover, preview, and apply both Microsoft-provided and custom site-specific templates.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?id=490565](https://www.microsoft.com/en-US/microsoft-365/roadmap?id=490565)

### Mid-June 2025 - New Email Indicators in Insider Risk Management

Microsoft Purview Insider Risk Management will introduce two new email indicators:

1.  **Email with Attachments to Free Public Domains**: Alerts when sensitive data is sent to free public domain emails.
2.  **Email with Attachments to Self**: Alerts when sensitive data is sent to a personal email or self.  
    

Admins can use these two email indicators within the Data Leaks or Data Theft policy templates to enhance monitoring and protection.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1051101](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1051101)

### Mid-June 2025 - Insider Risk Management- Risky AI Usage

New detections in Insider Risk Management will be generally available, enabling admins to identify risky AI activity, such as sensitive prompts, risky intents, and AI-generated sensitive content. This applies to M365 Copilot, Copilot Studio, and ChatGPT Enterprise, contributing to Adaptive Protection risk levels.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC947048](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC947048)

### Late-June 2025 – IRM Alerts in Microsoft Defender XDR

Microsoft Purview’s Insider Risk Management (IRM) data will integrate with Microsoft Defender XDR, enabling comprehensive investigation and correlation. IRM data will be accessible through the unified alert and incident queue, advanced hunting with KQL queries, Graph API, and Microsoft Sentinel. This feature will roll out to general availability by mid-June 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC961761](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC961761)

### Late-June 2025 - Workspace Inbound/Outbound Access Protection in Microsoft Fabric

Microsoft Fabric is introducing Preview features: Workspace-level private links and Outbound access protection to enhance network security by blocking inbound and outbound public access. These tenant-level settings will be enabled by default, allowing workspace admins to configure the new features at the workspace level.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1070180](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1070180)

### Enhancements

**June 30, 2025 – New Improved PowerShell Script for HR Connector in Microsoft Purview**

Insider Risk Management detects potential insider threats by using the HR Connector, which runs an existing PowerShell script to upload HR data on a regular basis. To enhance security, Microsoft has released an improved version of this script. Admins currently using the HR Connector must update their policies with the new script before June 30, 2025, to ensure continued protection.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1042929](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1042929)

### June 2025 - Add Shared Mailbox as Accounts in New Outlook for Windows

Starting June 2025, you’ll be able to add shared mailboxes as accounts in the New Outlook for Windows. With the necessary permissions, you can access these shared mailboxes by providing the user’s credentials.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=375635](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=375635)

### June 2025 – Configure Group Policy to Block Specific Folders form OneDrive Sync

Currently, admins can configure group policies to exclude specific files or file extensions from syncing with OneDrive. With this update, admins will also be able to exclude entire folders to prevent users from syncing them with OneDrive.

**_Ref_**_:_ [https://www.microsoft.com/en-US/microsoft-365/roadmap?id=178292](https://www.microsoft.com/en-US/microsoft-365/roadmap?id=178292)

### June 2025 - Exclude Spam and Bulk Emails in Communication Compliance

Communication compliance policies in the Microsoft Purview compliance portal are getting a new filter to help reduce noise from bulk emails like newsletters and spam. This filter will help admins focus on more important policy matches by automatically excluding these types of messages.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?id=402194](https://www.microsoft.com/en-US/microsoft-365/roadmap?id=402194)

### June 2025 – Information Protection: On-demand Classification of Files in SharePoint and OneDrive for Business

Microsoft Purview is introducing on-demand classification for files in SharePoint Online and OneDrive, enabling the discovery and classification of sensitive content in historical data—including files that were never scanned or haven't been scanned in a while. On-demand classification of files is a pay-as-you-go feature (not part of the E5 license).  
  
**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1013459](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1013459)

### June –2025 - New "View and upload" Permission for Anyone links to Folders in Microsoft OneDrive

Admins will have a new permission option “View and upload” for Anyone links to folders in OneDrive. Previously, anyone links to folders were limited to “View, edit, and upload.” When set to “View” only, the Request files feature was unavailable.

With this update, admins can assign the “View and upload” permission, enabling users to view files while still using the Request files feature.

**_Ref_**_:_ [https://learn.microsoft.com/en-us/sharepoint/turn-external-sharing-on-or-off#advanced-settings-for-anyone-links](https://learn.microsoft.com/en-us/sharepoint/turn-external-sharing-on-or-off#advanced-settings-for-anyone-links)

### Early June 2025 – New Built-in Teams Reader Role in Teams Admin Center

  
Microsoft will roll out a new built-in role-based access control role called **“Teams Reader.”** Admins assigned to this role will have read-only access to all pages in the Teams admin center. However, there are some limitations. They will not be able to view Teams management, meetings and calls details, the collaboration activity dashboard, and a few other areas.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1085581](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1085581)

### Early-June 2025 - Enhancements to IRM Exclusions to Reduce Alert Noise

To reduce alert noise, Microsoft has enhanced global exclusions in IRM settings. These improvements include updated keyword logic, file path exclusions, and domain exclusions for browsing indicators.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1058262](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1058262)

### Mid-June 2025 – Admin Units Support for Microsoft SharePoint Online

Microsoft Purview Data Loss Prevention will soon support adding SharePoint sites to administrative units. This means that when a DLP policy is assigned to SharePoint locations within an administrative unit, it will automatically apply to all sites contained in that unit.

**_Ref_**: [https://learn.microsoft.com/en-us/purview/purview-admin-units#administrative-units-support-for-sharepoint-sites-preview](https://learn.microsoft.com/en-us/purview/purview-admin-units#administrative-units-support-for-sharepoint-sites-preview)

### Late-June 2025 – Insider Risk Management: Enhancements to User Scoping Features in Policies

Insider Risk Management admins with appropriate permissions can now select combinations of users, groups, and adaptive scopes to include or exclude from Insider Risk Management policies in the Microsoft Purview portal. Microsoft is also adding support for non-email enabled Security Groups within Insider Risk Management policies.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1047928](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1047928)

  

### Existing Functionality Changes

### Early –June 2025 - Enabling a New Public Content Delivery Network (CDN) Domain for SharePoint

Microsoft is migrating the hosting of SharePoint Online assets to a new CDN, Microsoft Azure Front Door. To keep things working smoothly, admins should allow public-cdn.sharepointonline.com and stop using hardcoded CDN links. Also, the old addresses should remain allowed until the switch is finished.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1066155](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1066155)

### June 2, 2025 – Sender Email Address Update for Microsoft Teams DLP Generate Incident Report Emails

Microsoft is changing the sender address for Teams DLP Generate Incident Report (GIR) emails. From June 2, 2025, emails will come from either the old address ([no-reply-MicrosoftInformationProtectionOnline@microsoft.com](mailto:no-reply-MicrosoftInformationProtectionOnline@microsoft.com)) or the new one ([no-reply@teams.mail.microsoft.com](mailto:no-reply@teams.mail.microsoft.com)). After June 20, 2025, only the new address ([no-reply@teams.mail.microsoft.com](mailto:no-reply@teams.mail.microsoft.com)) will be used. If your inbox rules are set to act on the old sender address, update them to match the new address.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1064354](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1064354)

### Mid-June 2025 – Updates to the Get-FederationInformation Cmdlet in Exchange Online

Currently, the Get-FederationInformation cmdlet retrieves all federated domain information in the DomainNames field. After the update, the cmdlet will return details only for the domain explicitly specified as a parameter.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1081538](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1081538)

### Late - June 2025 - Search-MailboxAuditLog and New-MailboxAuditLogSearch Cmdlets Will Become Static

Microsoft plans to deprecate the Search-MailboxAuditLog and New-MailboxAuditLogSearch cmdlets. However, admins can continue to access the old logs and download data using these cmdlets until late June 2025. After that, the cmdlets will become read-only, and no further changes or downloads will be possible.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310](https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310)

### Late - June 2025 – Decoupling of Policy Tips and Email Notifications for SharePoint and OneDrive

Currently, enabling email notifications for a DLP policy also requires enabling the policy tips, and vice versa. However, Microsoft will soon allow admins to configure email notifications and policy tips independently for SharePoint and OneDrive DLP policies. This update will be rolled out to Public preview by late June 2025.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=394279](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=394279)

### Action Required:  

### June 1, 2025– Microsoft Viva Engage: External Networks are Being Modernized

Microsoft Viva Engage will modernize External Networks. So, legacy external networks will be retired starting June 1, 2025.

**Solution:** Admins must migrate to the new platform before May 31, 2025, to avoid data loss.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1036575](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1036575)

### June 2025 – Retirements of SIEM Agents in Microsoft Defender for Cloud Apps

Microsoft will retire the Security Information and Event Management agents from Microsoft Defender for cloud apps, starting mid-Nov 2025. No new SIEM agents can be configured after June 19, 2025.

**Solution:** Use APIs that support the management of activities and alerts data from multiple records.

**_Ref:_** [https://learn.microsoft.com/en-us/defender-cloud-apps/siem](https://learn.microsoft.com/en-us/defender-cloud-apps/siem)

## July 2025

**Retirements:**

### July 1, 2025 - Microsoft 365 Business Premium and Office 365 E1 Grant Discontinuation for Non-profits

Microsoft is retiring the Microsoft 365 Business Premium and Office 365 E1 grant offers for non-profits. Going forward, nonprofits can receive up to 300 licenses of Microsoft 365 Business Basic and up to 75% discounts on other Microsoft 365 plans, including Business Premium and Office 365 E1.

**Solution**: Move to the Microsoft 365 Business Basic grant or another Microsoft 365 offer for nonprofits.

**_Ref_**: [https://partner.microsoft.com/en-ca/asset/collection/microsoft-365-business-premium-and-office-365-e1-grant-discontinuation#/](https://partner.microsoft.com/en-ca/asset/collection/microsoft-365-business-premium-and-office-365-e1-grant-discontinuation#/)

### July 2025 – SharePoint Alerts Retirement

Starting July 2025, Microsoft will no longer allow users to create new SharePoint alerts for newly onboarded tenants. After a gradual phase-out, SharePoint alerts will be completely retired and no longer available.

**Solution:** Microsoft recommends moving SharePoint Alerts to either Power Automate for advanced workflows or SharePoint Rules for basic notifications. Admins can use the Microsoft 365 Assessment tool to review alerts and plan the transition smoothly.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1072889](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1072889)

### July 31, 2025 – Retirement of Organization Data Type in Microsoft Excel

Microsoft Excel’s Organization data type feature, which enabled admins to access and integrate data from their Power BI datasets directly within Excel, will be retired on July 31, 2025.

**Solution:** Use Get Data > From Power BI on the Data ribbon in Excel to import data from Power BI. Alternatively, you can use an add-in to create custom data types for your organization.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1072405](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1072405)

### July 31, 2025 – TLS Deprecation for Fabric Platform

As part of ongoing efforts to strengthen security, the Fabric Platform will require all outbound connections to customer data sources to use TLS version 1.2 or higher. Support for TLS 1.1 and older versions will end on July 31, 2025.

**Solution:** If systems are still running TLS 1.1 or earlier, update them to TLS 1.2 or higher promptly to avoid service disruptions.

**_Ref:_** [https://blog.fabric.microsoft.com/en-US/blog/tls-deprecation-for-fabric/](https://blog.fabric.microsoft.com/en-US/blog/tls-deprecation-for-fabric/)

**New Features**  

### July 2025 - Native Forms within SharePoint Document Libraries

Microsoft will introduce native forms in SharePoint document libraries to boost productivity. After this rollout, admins will be able to create custom forms directly within libraries for seamless file uploads and metadata submission.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?id=489834](https://www.microsoft.com/en-US/microsoft-365/roadmap?id=489834)

### July 2025 - New Planner App for the Web in DOD

A new Microsoft Planner app will be introduced, combining the simplicity of Microsoft To Do with the collaboration features of Planner into a single solution.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?id=490569](https://www.microsoft.com/en-US/microsoft-365/roadmap?id=490569)

### Early-July 2025 - Facilitator Agent in Microsoft Teams

Microsoft Teams will introduce a Facilitator Agent to enhance collaboration by automating notetaking and summarizing key discussions during meetings and chats. This feature also enables real-time co-authoring, allowing participants to edit and collaborate on notes seamlessly.

**Note:** It applies to Teams for Windows desktop, Teams for Mac desktop, Teams for the web, and Teams for iOS/Android. Also, a Microsoft Copilot license is required to use this feature.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1017117](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1017117)

### Mid-July 2025 - Security and Compliance Information for Apps in Teams Admin Center

Microsoft will add security and compliance information for apps in the Teams admin center. Admins will have access to data such as security assessments, vulnerability scans, and certification statuses, helping them make informed decisions about which apps to trust.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1009926](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1009926)

### Late- July 2025 – New Message Consumption Usage Report for Microsoft 365 Copilot Chat

Microsoft will introduce a new report called the Message Consumption Usage Report for Microsoft 365 Copilot Chat. This report provides detailed breakdowns of billed messages by user, by agent, and by agent-user pairs.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1069563](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1069563)

**Enhancements**

  
July 2025 - Permission Report in SharePoint Admin Center

A new report will be available in the SharePoint admin center. Admins can use this report to view users’ direct and indirect permissions at the site, library, folder, and file levels.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?id=492621](https://www.microsoft.com/en-US/microsoft-365/roadmap?id=492621)

### July 2025 - Allow Recording and Transcription by Default in Teams Calling Global Policy

Starting July 2025, Microsoft Teams’ global calling policy will have recording and transcription enabled by default for new tenants and those using the default global policy. This update aligns calling policies with Teams meetings policies and expands access to AI-powered features like Calls Recap and Calling Copilot.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1084030](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1084030)

### Early-July 2025 - Microsoft Purview Compliance portal: Timeline View of User Activity

A new timeline view of user activity is being introduced to help you better understand potential data security or compliance incidents. This comprehensive view displays all flagged interactions for a user in a single, easy-to-follow timeline, providing insights into potentially risky behavior.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1079735](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1079735)

**Existing Functionality Changes**

### July 2025 - Insider Risk Management: Increasing policy template limits

Currently, Insider Risk Management allows up to 20 policies per template. However, Microsoft is increasing the limit to 100 active policies in total, removing template-specific restrictions. This means you can now create up to 100 policies across all templates instead of being limited per template.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=477364](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=477364)

### Action Needed  
  
July 31, 2025 - Updates to required permissions for Microsoft Graph Beta API Device Management

Starting July 31, 2025, the Microsoft Graph Beta API /deviceManagement endpoints will require DeviceManagementScripts.Read.All or DeviceManagementScripts.ReadWrite.All permissions to operate.

**Solution:** Any existing apps, scripts, or tools using DeviceManagementConfiguration.ReadWrite.All or DeviceManagementConfiguration.Read.All permissions must be updated to use the new permissions.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1066336](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1066336)

  

### July 2025 – New Cmdlet for Content Explorer

A new cmdlet, _Export-ContentExplorerData_, will be rolled out to U.S Government clouds by July 2025. This cmdlet allows admins to export all scanned content data from Content Explorer, providing a streamlined way to manage and analyze content data.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=117531](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=117531)

### After July 1, 2025 – Azure AD PowerShell Retirement

The Azure AD PowerShell module will be retired after July 1, 2025.  

**Solution**: Migrate to Microsoft Graph PowerShell SDK or Microsoft Entra PowerShell module.  

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991)

### July 1, 2025 – Azure AD Graph API Will Be Fully Retired

If you've extended the use of Azure AD Graph API, it will no longer work after June 30, 2025. Azure AD Graph will be fully retired, and all Azure AD Graph API requests will stop functioning from July 1, 2025.

**Solution**: Review the application that uses the Azure AD Graph API and migrate them to Microsoft Graph.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-azure-ad-graph-api-retirement/4090533](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-azure-ad-graph-api-retirement/4090533)

**July 1, 2025 – DNS Provision Change**  
  
Starting July 1, 2025, A records for new Accepted Domains will move from mail.protection.outlook.com to subdomains under mx.microsoft to support DNSSEC.

**Action Required:** If you have automation that configures MX records, you must update it to use the **List serviceConfigurationRecords Graph API** to retrieve the correct MX values. After July 1, this API will be the only reliable source for MX records. Failing to update may result in mail flow issues for new domains.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1064044](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1064044)

### July 1, 2025- Classic Teams Desktop App End of Availability

Starting July 1, 2025, classic Teams desktop app will reach end of availability for all users irrespective of OS.

**Note**: From Oct 23, 2024, classic Teams desktop app on Windows 7,8,8.1 and Mac OS Sierra (10.12) will reach end of availability.

**Solution:** Users need to switch to new Teams, or they can use Teams web app (on supported browser) as an alternative.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783985](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783985)

## August 2025 (Attention Needed: 3)

### August 1, 2025 - Retirement of Classic e-Discovery in Microsoft Purview

Starting August 1, 2025, Microsoft will retire Classic eDiscovery, including Content Search, eDiscovery (Standard), and eDiscovery (Premium), from the Microsoft 365 Purview portal.

**Solution:** Transition to the new unified eDiscovery for faster and improved search and investigation capabilities.  

**_Ref:_** [https://learn.microsoft.com/en-us/purview/ediscovery-legacy-retirement](https://learn.microsoft.com/en-us/purview/ediscovery-legacy-retirement)

### Early-August 2025 - Retirement of Microsoft Project for the Web and Project in Teams

Microsoft Project for the web and Project in Teams will be retired in August 2025. Users will be redirected to Planner for the web and Planner in Teams, where existing Project features will be integrated to ensure a seamless transition.

**Solution:** Users should migrate Roadmap data to Portfolios and re-pin Projects in Teams tabs using Planner.  

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1068905](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1068905)

### August 2025 - Mail Merge (Advanced) on Outlook on the Web and New Outlook for Windows  

Enhanced mail merge features are coming to Outlook on the Web and the new Outlook for Windows in August 2025. Users will be able to insert dynamic fields into email templates for personalized emails and advanced customizations.  

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047)

## September 2025 (Attention Needed: 4)

### Sep 2025- Basic Auth for Client Submission (SMTP AUTH) Retirement in Exchange Online

Exchange Online will permanently remove support for Basic authentication with Client Submission (SMTP AUTH) in September 2025.

**Solution:** You can start to use OAuth with Client Submission (SMTP AUTH).

**_Ref_**: [https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-retire-basic-auth-for-client-submission-smtp/ba-p/4114750](https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-retire-basic-auth-for-client-submission-smtp/ba-p/4114750)

### Early-Sep 2025 - General Availability of Progressive Alert Scoring in IRM

Microsoft will roll out a new feature -" Progressive alert scoring" in Microsoft Purview Insider Risk Management. Currently, user activities that could potentially result in data security incidents will be assessed once every 24 hours. After this rollout, the assessment of user activities will be done more frequently within a 24- hour period, along with alert insights. This feature will be generally available for GCC, GCC-High, DoD environments by early-Sep 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC707653](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC707653)

### Mid-Sep - 2025 - Data Lifecycle Management: Retention Based on “last accessed” for OneDrive and SharePoint Files

Starting mid-Sep2025, Microsoft will introduce a "When items were last accessed" option in Purview retention policies. This will allow admins to configure retention policies based on file access history in OneDrive and SharePoint, enabling the removal of outdated data.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442  
](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442)

### Late-Sep 2025 - New Secure Workflow to Bypass Legal Holds and Retention Policies in Microsoft Purview

Admins will have the ability to permanently delete sensitive Exchange mailbox content; bypassing retention policies and eDiscovery holds. This will be possible through the “Priority Cleanup Administrator” role, which grants authorized users’ permission to initiate Priority Cleanup for Exchange, allowing exceptions to standard retention and legal hold policies.

Since this process is irreversible and overrides existing policies, Microsoft has built-in approvals and special auditing for security.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC971035](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC971035)

### Sep 30, 2025 – Retirement of Managing Authentication Methods in Legacy MFA &SSPR Policy

Starting Oct 2025, Microsoft no longer allow authentication methods to be managed in the legacy MFA and SSPR policies.

**Solution:** Organizations should use the converged authentication methods policy where methods can be managed centrally for all authentication scenarios including passwordless, MFA and SSPR.

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448)

## Q4 2025 (Attention Needed: 10)

### Oct 2025 – External Recipient Rate Limit in Exchange Online

Exchange Online will begin enforcing an External Recipient Rate (ERR) limit of 2,000 recipients within 24 hours. This restriction will apply to the cloud-hosted mailboxes of all newly created tenants.

**Note:** Exchange Online currently enforces a Recipient Rate limit of 10,000 recipients for cloud-hosted mailboxes. The 2,000 ERR limit will be a sublimit within this 10,000 Recipient Rate limit.

Ref: [https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733](https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733)

### Oct 2025 – Adding Support for SMTP DANE with DNSSEC for Exchange Online

Microsoft is adding inbound support for SMTP DANE with DNSSEC to Exchange Online GCC High and DoD.

Ref: [https://www.microsoft.com/en-in/microsoft-365/roadmap?featureid=361914&searchterms=361914](https://www.microsoft.com/en-in/microsoft-365/roadmap?featureid=361914&searchterms=361914)

### October 2025 - Just in Time Protection on SharePoint in DLP

Microsoft is introducing Just-in-Time protection for SharePoint in Microsoft Purview Data Loss Prevention.

With this feature, organizations can automatically apply DLP restrictions to unclassified files when they are accessed or shared externally. Instead of restricting files in advance, JIT protection enforces security measures only when there is a risk of data leaving the organization.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457)

### October 2025 – New Personalization Settings in Microsoft Purview

Microsoft will introduce a new personalization page in Microsoft Purview, allowing admins to customize their experience. New features will include the ability to pin/unpin solutions, toggle solution bar visibility, access solution walk-throughs, export personalization data, and delete preferences. This update will help streamline the management of individual admin experiences within Microsoft Purview.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=483884](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=483884)

### October 2025 – Enhanced Capabilities in Information Barriers V2

Microsoft will upgrade Information Barriers (IB) from version 1 to version 2, introducing new capabilities like:

*   Larger segment scale
*   Multi-segment support
*   Flexible people discoverability

Existing IB v1 users can upgrade to IB v2 to access this enhanced feature.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=115482](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=115482)

  

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

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC921752](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC921752)

### After Oct 2025 – End of Support for Legacy Microsoft Outlook for Mac

As part of Microsoft's commitment to a more secure and robust email experience, Microsoft 365 subscriptions linked to a personal, work, or school account will no longer support the legacy version of Microsoft Outlook for Mac.

**Solution:** Upgrade to the latest version of Outlook for Mac, which is built on modern technology for improved performance, security, and reliability.

**_Ref:_** [https://support.microsoft.com/en-us/office/end-of-support-for-legacy-outlook-for-mac-7b9cf644-7035-4345-a151-8c1c7a65ac25](https://support.microsoft.com/en-us/office/end-of-support-for-legacy-outlook-for-mac-7b9cf644-7035-4345-a151-8c1c7a65ac25)

### Dec 2025 - Existing Office 365 Connectors will stop Working

Existing Office 365 connectors will continue to work until December 2025, after which they will no longer work.

**_Ref:_** [https://learn.microsoft.com/en-us/power-bi/connect-data/service-publish-from-excel](https://learn.microsoft.com/en-us/power-bi/connect-data/service-publish-from-excel)

### Dec 2025 - Integration of New ChatGPT Enterprise Connector with Microsoft Purview Compliance Portal

The ChatGPT Enterprise connector will be integrated into the Microsoft Purview Compliance portal, allowing admins to discover, collect, and store prompts and responses from users' interactions with ChatGPT.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=401125](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=401125)

## 2026 (Attention Needed: 14)

### Jan 13, 2026 – End of Extended Support for Microsoft Advanced Threat Analytics 1.x

Microsoft Advanced Threat Analytics (ATA) extended support will be ended on January 13, 2026.

**Solution**: Updates for Microsoft ATA are available from Microsoft Update or by manual download.

**_Ref_**: [https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c](https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c)

### March 2026 - Long-term Retention Period for Microsoft 365 Backup

Admins will be able to configure longer-term retention for Microsoft 365 backups, allowing data storage beyond one year. This feature will be available in preview by March 2026.  

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=481834](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=481834)

### Mar 31, 2026- Deprecation of ‘Require Approved Client App’ Conditional Access Grant

The Require approved client app control in Azure Active Directory (Azure AD) Conditional Access will be retired and no longer enforced.

**Solution:** You can make use of the “Require app protection policy” control, which has all the same capabilities

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448)

### April 2025 - Retirement of Certain Dynamic Data Exchange features in Microsoft Word

Microsoft Word will retire some Dynamic Data Exchange features that were previously disabled in 2017. These features, controlled by a registry key, will be fully removed in April 2025, and the registry key will no longer be available.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC863140](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC863140)

**Late 2025 - Simplified File Sharing with Hero Link in Microsoft 365**

Microsoft is introducing ‘Hero Link’ in Microsoft 365—a single, smart sharing link that consolidates all file access permissions, simplifying collaboration. Instead of generating multiple links when sharing files through different methods (like email, Teams, or directly from the browser), Hero Link ensures every share points to the same file and permissions.

**_Ref_**: [https://techcommunity.microsoft.com/blog/onedriveblog/simple-smart-and-secure-the-next-step-in-sharing-files-in-microsoft-365/4411655](https://techcommunity.microsoft.com/blog/onedriveblog/simple-smart-and-secure-the-next-step-in-sharing-files-in-microsoft-365/4411655)

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

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865)

### Apr 02, 2026 – Azure ACS Retirement in Microsoft 365

After April 2, 2026, existing tenants using Azure ACS for custom or third-party app access in SharePoint Online will no longer function due to its retirement.

**Solution:** Admins can utilize the Microsoft 365 Assessment tool to scan the tenants for any usage of Azure Access Control Service (ACS) and [migrating from Azure ACS to Microsoft Entra ID](https://aka.ms/retirement/acs/guidance).

**_Ref:_** [https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/retirement-announcement-for-azure-acs](https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/retirement-announcement-for-azure-acs)

### Apr 02, 2026 - Retirement of Domain Isolated Web Part in SharePoint Framework

  
From Apr 02, 2026, the domain isolated web part feature will be fully retired. Organizations using this feature will receive an error message.

**Solution:** Update your domain isolated web parts to regular web parts and redeploy them to ensure continued functionality.

**_Ref:_** [https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/](https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/)

### Mar 2026 - Retirement of "Require Approved Client App" Grant Control" in Entra ID Conditional Access

The Conditional Access "Require approved client app" grant control is being retired from Microsoft Entra ID & Microsoft Intune by March 2026.

**Solution:** Use the "Require application protection policy" grant control, which offers the same data loss prevention while providing enhanced security benefits.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1029989](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1029989)

### July 14, 2026- InfoPath 2013 Client and InfoPath Forms Services in SharePoint Online will be Retired

  
  
InfoPath Client 2013 will reach the end of its extended support period on July 14, 2026, and to keep an aligned experience across Microsoft products, InfoPath Forms Service will be retired from SharePoint Online.

**Solution:** To understand the usage of InfoPath within your organization, you can utilize the [Microsoft 365 Assessment tool](https://aka.ms/assessment/infopath) to scan your tenant and analyze InfoPath usage. If you are currently using InfoPath, you can initiate the migration process to modern alternatives such as Power Apps, Power Automate, or Forms.

**_Ref_**: [https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190](https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190)

### July 2026 - SharePoint Alerts will be Fully Retired

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