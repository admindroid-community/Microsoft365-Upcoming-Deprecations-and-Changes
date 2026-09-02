# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. 🌟 We’ll shed light on the features and products that are undergoing transformations or bidding farewell. Whether you’re a system administrator 🧑‍💻 managing the Microsoft 365 environment or an avid user 🙋‍♂️ staying ahead of the curve, this blog will provide invaluable insights and actionable recommendations.

🚀Discover the **key changes, deprecations,** and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we’ve got you covered! Make informed decisions and ensure a smooth transition. ⚡️


## Microsoft 365 Upcoming Changes and Deprecations List:

Here is a list of changes categorized by month and year:

*   September 2026 (Retirements: 7, New Features: 11, Enhancements: 7, Existing Functionality Changes: 7, Action Needed: 4, Live: 3)
*   October 2026 (Retirements: 9, New Features: 10, Enhancements: 6, Existing Functionality Changes: 2, Action Needed: 3)
*   November 2026 (Attention Needed: 5)
*   December 2026 (Attention Needed: 5)
*   2027 (Attention Needed: 16)

## September 2026

Retirements: 7 | New Features: 11 | Enhancements: 7| Existing Functionality Changes: 7 | Action Needed: 4 | Live Now: 3

### Retirements

### September 2, 2026 – Power Automate Retires the Legacy Chatbot

Microsoft will retire the legacy chatbot experience in the Power Automate portal starting September 2, 2026. After the retirement, users will no longer be able to access the legacy chatbot.

Help, documentation, and support resources will remain available through the Help (?) menu in the Power Automate portal. Existing flows and other Power Automate functionality will not be affected.

**Solution:** Inform affected users about the retirement and direct them to the available Help (?) resources for assistance.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1448890](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1448890)

### Early-September 2026 – Microsoft Teams Retires Android Device Management in Teams Admin Center

Microsoft is transitioning Teams Android device management from the Teams admin center (TAC) to the Teams Rooms Pro Management portal (PMP). While the public-cloud migration to PMP is already complete, Microsoft will begin retiring overlapping Android device-management capabilities in TAC in early September 2026.

**Solution:** Move Android device-management operations to the Teams Rooms Pro Management portal (PMP) and update administrator processes accordingly.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1227622](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1227622)

### Early-September 2026 – Exchange Admin Center Retires the “Other Features” Page

Microsoft will retire the _Other Features page_ in the Exchange admin center beginning in early September 2026. The page mainly provides links to administrative experiences hosted in other Microsoft portals. No Exchange Online workloads, settings, policies, or management capabilities are being removed.

**Solution:** Update documentation, bookmarks, and administrative procedures that reference the retired page. Replace those references with direct links to the relevant Microsoft admin portals.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1452374](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1452374)

### September 17, 2026 – Retirement of Legacy Education LTI Tools

On September 17, 2026, Microsoft will retire legacy Education LTI tools such as Teams Assignments, OneDrive, OneNote Class Notebook, and Reflect. These tools will be replaced by a single Microsoft 365 LTI unified tool.

**Solution:** Migrate to and configure the Microsoft 365 LTI unified tool, and ensure users and admins are prepared for the transition.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1160188](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1160188)

### September 24, 2026 – Microsoft Edge Retires Windows Information Protection and Defender Application Guard

Microsoft Edge will retire support for Windows Information Protection (WIP) and Microsoft Defender Application Guard (MDAG) by September 24, 2026. These capabilities have already been removed from Windows 11 version 24H2.

**Solution:** Organizations still using WIP or MDAG on Windows 10 should migrate to supported alternatives, such as Microsoft Purview Information Protection, Purview DLP, or Microsoft Edge's built-in security capabilities.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1459132](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1459132)

### September 26, 2026 – Defender for Cloud Apps Retires Cloud Application Administrator Support

Microsoft Defender for Cloud Apps is retiring Cloud Application Administrator support for App Governance. This change aligns App Governance with the standard Microsoft Entra roles used across Microsoft Defender and supports future RBAC enhancements. Starting September 26, 2026, administrators assigned only this role will no longer be able to access App Governance.

**Solution:** Review affected administrator assignments and assign a supported role, such as Security Administrator, Compliance Administrator, Application Administrator, or Global Reader, before the enforcement date.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1462464](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1462464)

### September 30, 2026 – Deprecation of Custom Controls in Microsoft Entra Conditional Access

Microsoft is officially retiring Conditional Access Custom Controls on September 30, 2026. This legacy preview feature is being deprecated as Microsoft moves away from the older custom-control approach for integrating third-party authentication providers.

**Solution:** Admins should migrate to External MFA before the retirement date to avoid disruption.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/external-mfa-in-microsoft-entra-id-is-now-generally-available/4488926](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/external-mfa-in-microsoft-entra-id-is-now-generally-available/4488926#:~:text=Migration%20from%20Custom%20Controls)

### New Features

### September 2026 – Microsoft Purview Enhances DLP Alert Aggregation

Microsoft Purview will enhance Data Loss Prevention (DLP) alerting by aggregating alerts based on common user entities, even when multiple DLP rules are triggered. This consolidates related alert events into a single alert, helping reduce alert noise, simplify investigations, and provide better context for policy violations.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=567010](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=567010)

### September 2026 – Mail Merge (Advanced) in Outlook on the Web & New Outlook for Windows

Outlook on the web and the new Outlook for Windows will receive enhanced Mail Merge (Advanced) capabilities. With this update, users will be able to insert dynamic fields into email templates, enabling more personalized and customized communication at scale.

This enhancement simplifies the process of tailoring messages, making it more efficient to send targeted and professional emails.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047)

### September 2026 – New Secure Workflow to Bypass Legal Holds and Retention Policies in Microsoft Purview

Admins will have the ability to permanently delete sensitive Exchange mailbox content, bypassing retention policies and eDiscovery holds. This will be possible through the “Priority Cleanup Administrator” role, which grants authorized users’ permission to initiate Priority Cleanup for Exchange, allowing exceptions to standard retention and legal hold policies.

Since this process is irreversible and overrides existing policies, Microsoft has built-in approvals and special auditing for security.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=392838](https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=392838)

### September 2026: Pay-As-You-Go Billing for Extra Microsoft SharePoint Storage

Currently, organizations must purchase the Office 365 Extra File Storage add-on for additional SharePoint storage, which is billed in per-GB increments and can result in paying for unused capacity.

With this update, Microsoft is making [pay-as-you-go billing for extra SharePoint storage](https://blog.admindroid.com/pay-as-you-go-billing-for-extra-sharepoint-storage/) generally available worldwide. Storage is measured via a consumption-based meter, allowing organizations to pay only for what they use and improving overall cost efficiency.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1330893](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1330893)

### Early-September 2026 – Microsoft Defender for Office 365 Adds Prompt Injection Protection for Email

Microsoft Defender for Office 365 introduces prompt injection protection to detect and block malicious email content designed to manipulate AI assistants and agents. Emails identified as prompt injection attacks are classified as _High Confidence Phish_ and automatically quarantined. The feature is enabled by default for organizations with Microsoft Defender for Office 365 Plan 2 or Microsoft 365 E5.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1422060](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1422060)

### Early-September 2026 – eSignature for Microsoft 365 Recipient Groups

When a specific signer is unavailable, workflows may be interrupted, causing delays in the signing process. To improve reliability, eSignature for Microsoft 365 recipient groups is being introduced, allowing a single recipient slot to be assigned to up to 10 people. The first available signer can complete the signing requirement. The feature is enabled by default and doesn’t require any admin configuration.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1290821](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1290821)

### Mid-September 2026 – Full Workload Backup for SharePoint, OneDrive, and Exchange Enters Public Preview

A [Full Workload Backup](https://blog.admindroid.com/microsoft-365-backup-for-onedrive-sharepoint-and-exchange/#%F0%9F%91%89June-2026-Update%3A-Microsoft-Introduces-Full-Workload-Backup-for-SharePoint-Online%2C-Exchange-Online%2C-and-OneDrive) capability is being introduced for Microsoft 365 Backup, enabling organizations to create a single backup policy for an entire workload, including SharePoint, OneDrive, and Exchange Online. This policy will automatically protect all eligible artifacts within the selected workload.

The GA rollout will begin in mid-September 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1387526](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1387526)

### Mid-September 2026 – Microsoft 365 Introduces a New File and Folder Sharing Experience

Microsoft 365 is introducing a new file and folder sharing experience centered around a single **hero link** for each file or folder. The new experience allows users to update the existing sharing link when access requirements change instead of creating and distributing a new link.

By default, the hero link is limited to people explicitly added to the file or folder, while administrators can configure the default audience at the SharePoint site collection or OneDrive level.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1454378](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1454378)

### Mid-September 2026 – Microsoft Purview Adds Lifecycle Status Controls to Adaptive Scopes

Microsoft Purview is adding lifecycle status controls for adaptive scopes, letting admins control which active, inactive, or soft-deleted users and site owners are included.

Newly created adaptive scopes will evaluate only active recipients and site owners by default. Administrators can configure scopes to include inactive or soft-deleted users when required. The update also adds support for ISO 8601 duration values for selected date attributes in the advanced query builder.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1450128](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1450128)

### Late-September 2026 – Microsoft Purview Extends DLP Protection to the Network Layer

Microsoft Purview is extending Data Loss Prevention (DLP) to the network layer through integration with Microsoft Entra Internet Access, a component of Entra Global Secure Access (GSA). This enables organizations to inspect and protect sensitive data in network traffic, including AI prompts, files, and cloud service interactions, using existing Purview DLP policies.

The integration also enables administrators to audit or block sensitive data transfers and investigate alerts and incidents through Microsoft Purview and Microsoft Defender.  

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1419797](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1419797)

### September 30, 2026 – New Outlook for Windows Becomes Available for GCC High and DoD Environments

Microsoft is introducing the new Outlook for Windows experience for all GCC High and DoD environments, providing users with access to modern Outlook features. The experience will be available as an opt-in feature and is off by default.

Existing organizational settings remain unchanged, and users are not automatically switched to the new Outlook. Users can switch between the new and classic Outlook experiences at any time using the built-in toggle.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1338816](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1338816)

### Enhancements  

### September 2026 – Microsoft Purview Extends DLP and Auto-Labeling to Non-Microsoft Connected Apps

Microsoft Purview plans to expand DLP and Information Protection auto-labeling to non-Microsoft connected apps, including Google Workspace, Box, Dropbox, and Salesforce.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=568075](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=568075)

### Mid-September 2026 – Microsoft Purview Extends Endpoint DLP Protection to Excluded Windows Folders

Microsoft Purview Endpoint Data Loss Prevention (DLP) will extend protection to sensitive files stored in previously excluded Windows folders, such as AppData and temporary directories. Policy enforcement will apply during egress activities, including copying, printing, saving to network shares, and uploading to cloud services.

*   Audit mode: User actions continue and are logged for review.
*   Block mode: Restricted actions, such as copying, printing, or uploading sensitive files, are blocked.
*   If both policies apply: Block mode takes precedence over Audit mode.

Before enabling this feature, deploy Microsoft Defender anti-malware _client version 4.18.26051_ or later. Review excluded folder paths, update Endpoint DLP policies, and validate the changes in _Audit_ mode before enabling _Block_ mode.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1384420](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1384420)

### Mid-September 2026 – Updates to Tenant External Recipient Rate Limit Quotas for New, Trial, and Education Tenants

Microsoft is updating Tenant External Recipient Rate Limit (TERRL) quotas for new, trial, and education tenants in Exchange Online. The changes adjust how external recipient limits are calculated based on tenant age and licensing conditions.

The update is intended to provide more appropriate limits for different tenant types while helping protect Exchange Online from abuse.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1454397](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1454397)

### Late-September 2026 – Microsoft Defender Automatically Enables Unified RBAC for Tenants

Starting in late September, Microsoft will begin automatically enabling unified RBAC for eligible tenants. Administrators will receive advance notification before their tenant is enabled, and existing roles will be imported into the unified RBAC model.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1457836](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1457836)

### Late-September 2026 – Microsoft Teams Introduces a Refreshed In-Meeting Experience with Simpler Controls

Microsoft Teams is refreshing the in-meeting experience with redesigned meeting controls and a smarter sharing panel. Meeting controls will be simplified and reorganized, while the updated share panel will provide easier access to content-sharing options and improved previews.

The refreshed experience is designed to make common meeting actions easier to find and reduce accidental actions when presenting or leaving meetings.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1317197](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1317197)

### Late-September 2026: Hard Delete SharePoint and OneDrive Files in Microsoft Purview

Microsoft Purview Data Lifecycle Management is introducing a new hard delete option in Priority Cleanup policies. The update adds a “Delete data permanently” action for supported SharePoint and OneDrive file types, allowing organizations to permanently remove files from storage. Deleted files will no longer be discoverable through Microsoft 365 services. The capability also applies to files governed by retention policies and retention labels.

The GA rollout will begin in late September 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1261587](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1261587)

### September 30, 2026 – Microsoft Teams Introduces New PowerShell Controls for Federated Group Chats

Microsoft Teams is introducing [PowerShell controls for federated group chats](https://blog.admindroid.com/manage-federated-group-chats-with-teams-powershell-controls/) to enforce stricter external access and mutual federation policies. Disabled by default, these controls are managed using the _Set-CsTenantFederationConfiguration_ cmdlet.

Starting September 30, 2026, the _EnableMutualFederationForChatParticipants_ parameter will be available. When enabled, it requires all participating organizations in a federated group chat to have mutual federation configured.

Review your external access policies and Allowed Domains configuration before enabling these controls. Evaluate how they may affect existing federated group chats and users with restricted federation access.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1423114](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1423114)

### Existing Functionality Changes

### September 2026 – Microsoft Expands Archive Mailbox Capacity Beyond 1.5 TB

Currently, auto-expanding archive mailboxes are limited to 1.5 TB, after which they stop working. This limit has now been removed, allowing archive mailboxes to grow beyond 1.5 TB automatically to support ongoing retention needs.

This feature follows a consumption-based pricing model for storage beyond 1.5 TB, costing $0.25 per GB per month (or $0.0082 per GB per day).

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=560820#Roadmap](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=560820#Roadmap)

### September 2026 – Prepare for the New Intune Device Page Becoming the Default

Microsoft Intune is making the new device management experience the default device page in the Intune admin center. The refreshed experience provides an updated interface for viewing and managing device information and replaces the existing device page as the default experience.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1456780](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1456780)

### September 1, 2026 – Microsoft Entra Makes Passkeys the Default Authentication Method

Microsoft Entra will make passkeys the default authentication experience starting September 1, 2026, as Microsoft moves away from SMS and voice-based authentication toward phishing-resistant MFA. Users will be prompted to register a passkey during sign-in.

Organizations should prepare users for the new passkey registration experience and review their authentication policies to ensure they are ready for the transition.  
  
**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1426371](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1426371)

### Mid-September 2026 – Microsoft Purview Changes Just-in-Time Audit Behavior for Endpoint DLP

Microsoft Purview Endpoint Data Loss Prevention (DLP) is changing how Just-in-Time protection collects audit events. Previously, user activities were automatically audited when Just-in-Time protection was enabled. Going forward, admins must explicitly configure which users or groups are included in the audit scope, giving organizations greater control over audit data collection and reducing unnecessary audit noise.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1387575](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1387575)

### September 24, 2026 – Copilot Chat Edge Endpoint Change

Microsoft is updating the endpoint used by Copilot Chat in Microsoft Edge. Organizations may need to review network, firewall, proxy, or allowlist configurations to ensure continued access to Copilot Chat after the endpoint change.

Admins should verify that the required Microsoft domains and endpoints are permitted in their organization's network environment to prevent connectivity issues.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1456610](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1456610)

### Late-September 2026 – Update Office Apps to Keep Read Aloud, Transcription, and Dictation Features

Read Aloud, Transcription, and Dictation features in Microsoft 365 Office apps will stop working on versions earlier than 16.0.18827.20202 because of backend upgrades. This change takes effect late September 2026 for Worldwide tenants and November 2026 for GCC, GCC High, and DoD environments.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1127222](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1127222)

### Late-September 2026 – Teams Channel Whiteboard Storage Moves to SharePoint

Microsoft is updating the default storage location for whiteboards created in Teams Channel tabs. Starting in late Sep 2026, these files will be stored in the channel’s associated SharePoint site instead of the creator’s OneDrive. Enabled by default, this change prevents access issues caused by sharing settings, Information Barriers, and Conditional Access policies.

With this update, Whiteboards inherit SharePoint-based Microsoft Purview controls such as DLP, sensitivity labels, retention, eDiscovery, and audit logging, while also improving centralized compliance monitoring and reporting.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1253753](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1253753)

### Action Required  

### September 1, 2026 – Microsoft Defender Retires Standalone Automated Investigation and Response (AIR)

Microsoft Defender will retire the standalone Automated Investigation and Response (AIR) experience on September 1, 2026. AIR will no longer support manual triggering, as its detection and response capabilities are already integrated into always-on antivirus protection and run automatically. For on-demand investigations, administrators can use full antivirus scans.

**Solution:** Organizations that trigger AIR through playbooks, scripts, or integrations must update those workflows before the retirement. Replace AIR-based workflows with full antivirus scan workflows for on-demand investigations before September 1, 2026.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1411577](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1411577)

### September 1, 2026 – Update Power Platform Flows Using SharePoint Thumbnail URLs

Microsoft is changing how SharePoint thumbnail URLs are generated and accessed. Power Platform flows that directly reference or construct SharePoint thumbnail URLs may stop working as expected after the change.

**Solution:** Review Power Automate flows and other Power Platform solutions that use SharePoint thumbnail URLs. Update affected flows to use supported methods for retrieving thumbnail information to prevent broken images or flow failures.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1454816](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1454816)

### Mid-September 2026 – External Messaging Limits for onmicrosoft.com-Only Organizations in Microsoft Teams

Microsoft Teams is introducing external messaging limits for organizations that use only an **onmicrosoft.com** domain. These limits are intended to help protect the Teams messaging environment and reduce unwanted external communication.

**Solution:** Review your organization's external messaging requirements and ensure users who need to communicate externally are configured with the appropriate supported domain.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1463510](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1463510)

### September 30, 2026 – Upgrade to Microsoft Entra Connect v2.5.79.0 or Later

As part of Microsoft’s ongoing security hardening, Microsoft Entra Connect now uses the Microsoft Entra AD Synchronization Service, a dedicated first-party application, to synchronize Active Directory with Microsoft Entra ID.

**Solution:** Organizations must upgrade to Microsoft Entra Connect version 2.5.79.0 or later by September 30, 2026, to ensure uninterrupted synchronization.

**_Ref:_** [https://learn.microsoft.com/en-us/entra/identity/hybrid/connect/how-to-upgrade-previous-version?WT.mc\_id=Portal-Microsoft\_AAD\_IAM](https://learn.microsoft.com/en-us/entra/identity/hybrid/connect/how-to-upgrade-previous-version?WT.mc_id=Portal-Microsoft_AAD_IAM)

### Live in September

### Microsoft Teams Adds Security Detection Report

Microsoft Teams now includes a Security Detection Report in the Teams admin center, giving administrators a centralized view of messaging security detections. The report helps identify potential threats such as impersonation attempts, malicious URLs, and weaponizable file types.

Administrators can review detection activity in one place and export detailed report data to support security investigations and response workflows.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1311977](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1311977)

### New Report for “Everyone” and “Everyone except external users” in SharePoint

Microsoft SharePoint now includes a new report in the SharePoint admin center that provides item-level visibility into permissions granted through the Everyone and Everyone except external users special groups.

The report helps administrators identify broadly shared content across SharePoint and OneDrive, supporting governance, oversharing reviews, and permission remediation without changing existing permissions.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1450131](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1450131)

### September 2026 – New SharePoint Experience

Microsoft rolled out the redesigned SharePoint experience with a refreshed app bar and new Discover, Publish, and Build hubs. The update also introduced AI-assisted capabilities for users with a Microsoft 365 Copilot license and renamed Followed Sites and Saved for Later to Favorites.

The new experience was made available automatically, with existing SharePoint content transitioning to the redesigned experience.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher#/MessageCenter/:/messages/MC1240699](https://admin.cloud.microsoft/?source=applauncher#/MessageCenter/:/messages/MC1240699)

## October 2026

### Retirements

### October 01, 2026- Retirement of Exchange Web Services in Exchange Online

Starting October 1, 2026, Microsoft will start blocking EWS requests from non-Microsoft apps to Exchange Online. The changes in Exchange Online do not affect Outlook for Windows or Mac, Teams, or any other Microsoft product.

**Solution**: Upgrade your applications to Microsoft Graph to access Exchange Online data and take advantage of the latest capabilities.

**_Ref_**_:_ [https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-exchange-web-services-in-exchange-online/ba-p/3924440](https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-exchange-web-services-in-exchange-online/ba-p/3924440)

### October 1, 2026 – Microsoft Teams and Google Calendar Sync Retirement

Microsoft Teams will retire calendar synchronization with Google Workspace on October 1, 2026. Calendars previously configured for synchronization will stop syncing, and administrators will no longer be able to manage calendar synchronization through the Teams Admin app.

**Solution:** Use the Microsoft Teams Meeting add-on for Google Workspace to schedule Teams meetings directly from Google Calendar.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1462469](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1462469)

### October 01, 2026- Sign-in Risk Policy and User Risk Policy Retirement from Entra ID Protection

User risk policy or Sign-in risk policy UX in Entra ID Protection (formerly Identity Protection) will be retired on October 1, 2026.

**Solution:** Migrate Sign-in risk and User risk policies to Conditional Access.

**_Ref_**_:_ [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/what-s-new-in-microsoft-entra/ba-p/3796395](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/what-s-new-in-microsoft-entra/ba-p/3796395)

### October 01, 2026 – Retirement of SharePoint One-Time Passcode for External Sharing

Microsoft will retire SharePoint One-Time Passcode authentication for external sharing beginning in October 2026. As part of this change, external sharing authentication in OneDrive and SharePoint will transition to Microsoft Entra B2B. External users who previously accessed content using OTP will receive access denied unless a corresponding guest account exists.

*   All external access shifts to Microsoft Entra B2B, enforcing Conditional Access, Identity Protection, and centralized guest governance.
*   Authentication, invitations, and audit tracking move from SharePoint OTP to Entra B2B and its audit logs.
*   Existing “specific people” links may fail for users without a corresponding guest account.

**Solution:** Create a guest account in Entra B2B or have an internal user re-share content to automatically provision the guest account and restore access.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1243549](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1243549)

### October 5, 2026 – Microsoft Teams Live Chat Retirement

Microsoft Teams Live Chat will no longer be supported starting October 5, 2026. The Live Chat widget will stop relaying incoming customer messages from websites to Teams. New customers have already been unable to set up the feature since August 6, 2026, while existing integrations will stop functioning in October. Historical chat content stored in Teams will remain available.

**Solution:** Remove the Microsoft Teams live chat widget from all websites, notify affected users, and implement an alternative customer engagement solution.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1449174](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1449174)

### October 13, 2026- Retirement of Microsoft Publisher

On October 13, 2026, Microsoft will discontinue Publisher in Microsoft 365, with on-premises suite support ending.

**Solution:** Identify Publisher-dependent workflows and transition them to suitable alternatives such as Word, PowerPoint, or Designer.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC716267](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC716267)

### October 13, 2026 – End of Support for Office LTSC 2021 And Additional Apps

Microsoft will retire Office LTSC 2021, Visio LTSC 2021, Microsoft Project LTSC 2021, and a few other products on October 13, 2026.

**Solution:** Upgrade to a Microsoft 365 or Office 365 plan that includes Microsoft 365 Apps. For fully offline deployments, upgrade to Office LTSC 2024.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1278920](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1278920)

### October 2026 – Microsoft Teams Retires Calendar Functionality for Older Mobile App Versions

Microsoft Teams users on iOS and Android must update to the latest mobile app by October 2026 to continue using Calendar. Calendar functionality will no longer be available in older Teams mobile app versions. Desktop and web clients are not affected.

**Solution:** Ensure users update to the latest Teams mobile app and configure managed devices to deploy app updates automatically. If your organization still relies on Exchange Web Services (EWS) for Teams Calendar functionality, you can extend EWS support until April 2027, but plan to transition before it is retired.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=567313](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=567313)

### October 26, 2026 – Microsoft Entra ID Retires Custom CSS Positioning Properties in Company Branding

As part of Microsoft’s Secure Future Initiative (SFI), Microsoft Entra ID will retire support for custom CSS positioning properties used in company branding starting October 26, 2026. Properties such as position, margin, transform, opacity, overflow, filter, and other layout-related CSS properties will no longer be supported to improve sign-in security and phishing resistance. Branding elements that rely on these retiring properties will remain visible but may revert to their default placement.

**Solution:** Review company branding configurations and remove unsupported CSS positioning properties. Update branding elements that depend on these properties to ensure they display as expected.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1435782](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1435782)

### New Features

### Early-October 2026 – Microsoft Entra ID Adds Passkey Support for B2B Users

Microsoft Entra ID is expanding passkey support to business-to-business (B2B) collaboration users, enabling eligible external users to authenticate with passkeys when accessing resources in a partner organization. This strengthens phishing-resistant authentication for guest and external users while providing a more secure and convenient sign-in experience.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1459133](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1459133)

### Early-October 2026 – Microsoft Teams Enables Users to Report Security Concerns in Group Calls

Microsoft Teams will allow users to report security concerns directly during group calls. This provides participants with a way to flag potentially suspicious or problematic activity during a call, helping organizations improve their security response and protect users.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1447673](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1447673)

### Early-October 2026 – Credential scanning in Microsoft Purview Data Security Posture Agent

A new Credential Scanning capability will be introduced in Microsoft Purview Data Security Posture Agent to identify exposed credentials and related security risks across configured data sources. The AI-powered scanning engine uses large language models (LLMs) to detect sensitive credentials, including Microsoft Entra ID credentials, private keys, and API keys.

Scan results are presented through a dashboard with risk scores, AI-generated insights, and confidence ratings, enabling administrators to prioritize and remediate credential exposure more effectively.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1259828](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1259828)

### Early-October 2026 – Microsoft Teams Introduces AI Meeting Archive Files

Microsoft Teams introduces AI meeting archive files that capture AI-generated meeting insights to improve responses from Microsoft 365 Copilot and Facilitator. The archive contains structured AI-generated meeting information instead of raw meeting content and is stored in a tenant-owned SharePoint Embedded container.

The feature is enabled by default, with administrator controls to manage archive generation and retention. Only meeting participants can access AI responses based on the meeting archive.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1429018](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1429018)

### October 2026 – Microsoft Teams Introduces Separate Attendance Report Policy for Events

Microsoft Teams is introducing a dedicated attendance and engagement report policy for Teams events, such as webinars and town halls, separating their controls from Teams meetings. This allows administrators to grant event organizers access to event attendance and engagement reports while separately controlling access to Teams meeting reports.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=567466](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=567466)

### October 2026 – Microsoft Purview Adds Inline DLP Controls for Prompts in Microsoft Foundry Apps and Agents

Microsoft Purview Data Loss Prevention (DLP) will support inline DLP policies for built-in apps and agents in Microsoft Foundry. Organizations will be able to enable Microsoft Purview within Foundry to apply these policies. The integration helps prevent sensitive data from being shared through prompts and AI interactions, strengthening data protection controls.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1304291](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1304291)

### October 2026 – Microsoft Teams Adds the Ability to Pop Out Calls into a New Browser Window

Microsoft Teams browser app users will be able to pop out calls into a simplified call window that remains available while they navigate away from, hide, or minimize the browser tab or progressive web app (PWA) hosting the call. This makes it easier for users to multitask and continue collaborating while staying on a call.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=569206](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=569206)

### October 2026 – Microsoft Teams Automatically Blocks External AI Bots in Meetings

Microsoft Teams is introducing automatic blocking of external AI bots in meetings to help organizations prevent unauthorized AI assistants from joining and capturing meeting content. This provides administrators with greater control over the use of external AI services during Teams meetings.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1459141](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1459141)

### Oct 2026 – Just in Time Protection on SharePoint in DLP

Microsoft is introducing Just-in-Time protection for SharePoint in Microsoft Purview Data Loss Prevention in preview.

With this feature, organizations can automatically apply DLP restrictions to unclassified files when they are accessed or shared externally. Instead of restricting files in advance, JIT protection enforces security measures only when there is a risk of data leaving the organization.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457)

### Late-October 2026 – Microsoft Entra Enables Passwordless Password Changes from My Sign-Ins

Microsoft Entra will allow passwordless users to change their passwords directly from _My Sign-Ins_ page using a strong credential, such as a passkey, FIDO2 security key, or Windows Hello for Business.

Users can complete the password change without knowing their current password or using Self-Service Password Reset (SSPR). The feature is disabled by default and can only be enabled as a tenant-wide setting.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1437671](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1437671)

### Enhancements

### Early-October 2026 – Microsoft Teams Brings More Granular Controls for Channel Notifications

Microsoft Teams is introducing more granular channel notification options, including presets such as All new messages, Mentions and replies, and Mute. Within each option, users can further customize notifications for thread follows, tag mentions, channel mentions, and Teams mentions.

The feature is enabled by default for all users, providing greater control over how channel activity is surfaced.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1388719](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1388719)

### Early-October 2026 – Microsoft Entra Makes Windows Hello for Business and macOS Platform SSO Standalone MFA Factors

Microsoft Entra will recognize Windows Hello for Business (WHfB) and macOS Platform Single Sign-On (PSSO) as standalone multifactor authentication factors in supported authentication scenarios. Users will be able to satisfy supported MFA requirements without registering an additional passkey.

The credentials will also appear in My Security Info as auto-registered passkeys, helping organizations expand the use of phishing-resistant authentication methods.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1450134](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1450134)

### Mid-October 2026 – Microsoft Purview Adds Lifecycle Controls to Adaptive Scopes

Microsoft Purview is introducing lifecycle status evaluation controls for adaptive scopes, allowing administrators to configure whether recipients and site owners should be evaluated based on their lifecycle status. This provides greater control over how adaptive scopes dynamically identify users and sites for compliance and data governance policies.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1450128](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1450128)

### October 2026 – Microsoft Purview Introduces a Guided Diagnostics Experience for DLP

Microsoft Purview is introducing a guided diagnostics experience for Data Loss Prevention (DLP), helping administrators troubleshoot DLP policy and enforcement issues more efficiently. The guided experience provides targeted diagnostic information to help identify configuration or policy-related problems and determine appropriate remediation steps.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1293479](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1293479)

### October 2026 – Microsoft Purview Increases Auto-Labeling Scale for SharePoint and OneDrive

Microsoft Purview is increasing the daily auto-labeling limit for SharePoint and OneDrive from 100,000 to 500,000 files per tenant. This enables organizations to automatically apply sensitivity labels to larger volumes of content and improves coverage for large Microsoft 365 environments.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1461154](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1461154)

### Late-October 2026 – Purview Integrates Adaptive Protection with Data Lifecycle Management

Microsoft Purview is making its Adaptive Protection integration with Data Lifecycle Management (DLM) generally available in late October 2026. The integration automatically retains content deleted by elevated-risk users for 120 days across SharePoint, OneDrive, and Exchange, helping protect against potential data sabotage.

Admins can enable the integration from the Microsoft Purview compliance portal, while Microsoft automatically creates and manages the required retention label and policy.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC791110](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC791110)

### Existing Functionality Changes

### October 5, 2026 – OneDrive Adds Default Exclusion for .db-wal Files

Microsoft OneDrive will add the .db-wal file type to its default exclusion list starting October 5, 2026. Newly created .db-wal files will no longer sync to OneDrive by default, reducing unnecessary synchronization of temporary database files that frequently change and are generally useful only with their associated database. Existing .db-wal files that are already syncing will not be affected.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1457838](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1457838)

### Mid-October 2026 – Entra ID Sign-in Experience to Enforce Stricter Content Security Policy

Microsoft Entra ID will enforce a stricter Content Security Policy (CSP) for browser-based sign-ins starting mid-October 2026. The updated policy will allow only trusted Microsoft scripts, helping prevent injected code and reduce cross-site scripting (XSS) risks.

The change applies to sign-ins through _login.microsoftonline.com_ and does not affect Entra External ID tenants.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1191924](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1191924)

### Action Needed

### Early-October 2026 – Microsoft 365 Copilot App Requires Access to copilot.cloud.microsoft

Microsoft is moving the Microsoft 365 Copilot web app from m365.cloud.microsoft to copilot.cloud.microsoft. Organizations that block copilot.cloud.microsoft may experience disruption when users are automatically redirected to the new Copilot URL.

**Solution:** Allow the \*.cloud.microsoft domain in network configurations and validate connectivity to copilot.cloud.microsoft before the redirect.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1462915](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1462915)

### October 1, 2026 – Exchange Web Services Will Be Blocked for Kiosk and Frontline Licenses

Microsoft will block Exchange Web Services access for mailboxes that do not include EWS usage rights starting October 1, 2026. After enforcement, requests made without a supported license will return an HTTP 403 error. Impacted licenses include Exchange Online Kiosk, Microsoft 365/Office 365 F1, and F3.

**Solution:** To continue using EWS, assign a license that includes EWS access, such as Exchange Online Plan 1 or 2 or Microsoft 365 E3/E5.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/update-to-ews-access-for-kiosk–frontline-worker-licensed-users/4474299](https://techcommunity.microsoft.com/blog/exchange/update-to-ews-access-for-kiosk%E2%80%93frontline-worker-licensed-users/4474299)

### October 31, 2026 – Retirement of Microsoft Defender for Endpoint on Amazon Linux 2 (ARM64)

From October 31, 2026, Microsoft will retire support for Microsoft Defender for Endpoint on Amazon Linux (ARM64). Linux versions beyond 101.25122.0004 will no longer install on AL2 environments, and affected devices will miss security enhancements and feature updates.

**Solution:** Organizations should migrate to a supported Linux distribution for Microsoft Defender for Endpoint before October 31, 2026, to ensure continued security updates and feature support.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1392568](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1392568)

## November 2026 (Attention Needed: 5)

### November 2, 2026 – Outlook for Windows Report Retirement in the Exchange Admin Center

Microsoft is retiring the Outlook for Windows report in the Exchange admin center. Administrators will no longer be able to access the report through the existing Exchange admin center experience after the retirement.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1230889](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1230889)

### November 3, 2026 – Microsoft Entra ID Retires MemberOf Rule Operator

Microsoft Entra ID will retire the MemberOf rule operator for dynamic groups and dynamic administrative units. Organizations using this operator in dynamic membership rules will need to update those rules to supported alternatives before the retirement date.

**_Ref:_** [https://techcommunity.microsoft.com/discussions/microsoft-365/entra-id-drops-the-memberof-rule-operator-for-dynamic-groups-and-dynamic-admin-u/4544978](https://techcommunity.microsoft.com/discussions/microsoft-365/entra-id-drops-the-memberof-rule-operator-for-dynamic-groups-and-dynamic-admin-u/4544978)

### November 9, 2026 – Microsoft Entra ID SSPR Requires Registered Authentication Methods

Microsoft Entra ID Self-Service Password Reset (SSPR) will require users to verify their identity using authentication methods explicitly registered for authentication. Directory-stored contact information that has not been registered as an authentication method will no longer be accepted for SSPR verification.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1325414](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1325414)

### November 2026 – Pay-as-You-Go Consumption-Based Billing for Extra OneDrive Storage

Microsoft is introducing a pay-as-you-go billing model for OneDrive storage based on consumption. When storage usage exceeds the allocated quota, additional capacity is automatically made available and billed based on actual consumption.

The model enables organizations to scale storage flexibly and pay only for the additional capacity consumed, reducing the need to purchase fixed storage add-ons.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=562352](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=562352)

### November 2026 – Microsoft Purview Reduces DLP Policy Sync Time from 2 Hours to 30 Minutes

Microsoft Purview is reducing the expected synchronization time for Data Loss Prevention (DLP) policy changes from approximately two hours to 30 minutes. This enhancement allows administrators to see newly created or modified DLP policies take effect more quickly across supported workloads.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1317834](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1317834)

## December 2026 (Attention Needed: 5)  

### December 2026 – Credential Parameter Retirement in Exchange Online PowerShell

Exchange Online PowerShell is deprecating the _\-Credential_ parameter as it relies on the legacy ROPC authentication flow that does not support MFA or Conditional Access. This change applies to both the _Connect-ExchangeOnline_ and _Connect-IppsSession_ cmdlets.

**Solution:** Move to secure authentication methods such as _interactive sign-in,_ _app-only authentication_, or _managed identity authentication_ when connecting to Exchange Online PowerShell.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/deprecation-of-the–credential-parameter-in-exchange-online-powershell/4494584](https://techcommunity.microsoft.com/blog/exchange/deprecation-of-the%E2%80%93credential-parameter-in-exchange-online-powershell/4494584)

### December 2026 – Custom Retention for Message Trace Logs in Exchange Online

Starting in December 2026, organizations will be able to select how long Message Trace data is retained by choosing from a set of predefined retention periods. This enhancement gives admins greater flexibility to align log retention with their compliance, audit, and operational requirements.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=542929](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=542929)

### End of December 2026 – Disable SMTP Auth for Basic Authentication

SMTP AUTH Basic Authentication will be disabled by default for existing tenants by Dec end, though admins can enable it if required.

**Solution:**

*   Migrate applications and devices to OAuth-based authentication.
*   Use alternatives such as High-Volume Email for Microsoft 365, Azure Communication Services for Email, or an on-premises Exchange.

**_Ref_**: [https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835](https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835)

### End of December 2026 – Retirement of Power BI Q&A

Microsoft is retiring the Power BI Q&A experience by the end of December 2026. Existing Q&A visuals and experiences will stop working, and Q&A Setup tools will also be retired. Organizations should transition Q&A experiences to Copilot in Power BI and use Prep Data for AI as an alternative to Q&A Setup tools.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1218421](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1218421)

### December 31, 2026 – End of Support for Dynamics 365 Guides and Remote Assist

Dynamics 365 Guides and Dynamics 365 Remote Assist will retire on December 31, 2026. After this date, the products will no longer receive security updates, bug fixes, or technical support.

**Solution:** Customers should plan their transition early by identifying dependent users and scenarios. Explore alternative mixed reality solutions available in the [Microsoft Marketplace](https://marketplace.microsoft.com/marketplace/apps?category=mixed-reality), and consider Microsoft Teams Mobile with [spatial annotation](https://learn.microsoft.com/en-us/dynamics365/mixed-reality/remote-assist/teams-mobile-annotate) for certain remote collaboration use cases.

**_Ref:_** [https://learn.microsoft.com/en-us/lifecycle/announcements/dynamics-365-guides-remote-assist-end-of-support](https://learn.microsoft.com/en-us/lifecycle/announcements/dynamics-365-guides-remote-assist-end-of-support)

## 2027 (Attention Needed: 16)

### January 06, 2027 – Microsoft Purview Retires the Instances Policy Location for DLP

Microsoft Purview will retire the Instances policy location for Data Loss Prevention (DLP) on January 6, 2027. Dedicated application locations are being introduced for supported non-Microsoft applications, replacing the existing instance locations.

**Solution:** Review existing DLP and auto-labeling policies that use the Instances location and recreate them using the corresponding dedicated application locations before January 6, 2027.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1429010](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1429010)

### January 2027 – Retirement of Basic Authentication for Client Submission in Exchange Online

Microsoft will disable Basic Authentication with Client Submission (SMTP AUTH) by default starting January 2027. OAuth will be the supported authentication method.

**Proactive Steps:**

*   Move applications and devices to OAuth-based authentication for SMTP AUTH.
*   If Basic Authentication is still needed, consider alternatives such as High-Volume Email for Microsoft 365, Azure Communication Services for Email, or an on-premises Exchange Server in a hybrid setup.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835](https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835)

### January 2027 – End of Life of Standalone SharePoint Online and OneDrive for Business Plans

Microsoft is ending the lifecycle of standalone SharePoint Online Plan 1 and Plan 2 and OneDrive for Business Plan 1 and Plan 2. New customers are no longer able to purchase these standalone plans. From Jan 2027, renewals will no longer be permitted, although existing subscriptions will continue until their expiration.

**Solution:** Move to Microsoft 365 suite offerings such as Business Basic, Business Standard, Business Premium, E1, E3, or E5 for continued service availability.

**_Ref:_** [https://learn.microsoft.com/en-us/partner-center/announcements/2026-january#retirement-of-standalone-sharepoint-online-and-onedrive-for-business-plans-plan-1-and-plan-2](https://learn.microsoft.com/en-us/partner-center/announcements/2026-january#retirement-of-standalone-sharepoint-online-and-onedrive-for-business-plans-plan-1-and-plan-2)

### Late-January 2027 – Microsoft Extends DLP to Restrict Processing of External Emails in Copilot

Microsoft is extending Data Loss Prevention (DLP) support for Microsoft 365 Copilot and Copilot Chat by introducing a new capability to exclude emails from external or untrusted domains. These emails will not be used for summarization, responses, or grounding data in Copilot experiences.

The feature is available as an opt-in option. Once enabled, emails from trusted internal sources will continue to be used for Copilot responses, while content from external untrusted domains will be restricted.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1301714](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1301714)

### January 31, 2027 – Retirement of MDE and XDR Advanced Hunting APIs

To unify the interface across Microsoft Defender products, Microsoft will retire the Microsoft Defender for Endpoint (MDE) Advanced Hunting API and Microsoft Defender XDR Advanced Hunting API.

**Solution:** Move to Microsoft Graph Security API for broader data coverage, improved consistency, and better scalability for automation and security workflows.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1220762](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1220762)

### January 31,2027 – Full Retirement of Restricted SharePoint Search

Microsoft will fully retire Restricted SharePoint Search (RSS), which limits how SharePoint content appears in Microsoft Search and Microsoft 365 Copilot, by January 31, 2027. Existing Restricted SharePoint Search configurations will not be automatically migrated to Restricted Content Discovery (RCD).

**Solution:** Organizations should migrate from Restricted SharePoint Search to Restricted Content Discovery (RCD) or adopt another appropriate control for managing content discoverability before the retirement date.

**Ref:** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1395311](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1395311)

### February 1, 2027 – Retirement of Built-in SMS and Voice MFA in Microsoft Entra

Microsoft is retiring its built-in SMS and voice authentication service in Microsoft Entra on February 1, 2027. Organizations that continue using SMS or voice MFA must configure a supported telecom provider, as Microsoft will no longer provide these services.

Passkeys become the recommended authentication method, starting September 1, 2026. Tenants that continue relying only on Microsoft’s built-in SMS or voice authentication may experience sign-in disruptions after February 1, 2027.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1426371](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1426371)

### March 01, 2027 – Automatic Migration to New Outlook for Windows

Microsoft 365 Enterprise users will automatically switch to the new Outlook for Windows, gaining access to modern features like Copilot, theming, and time-saving options such as pinning and snoozing emails. A toggle will be available for users to revert to the classic Outlook. Admins can prevent this automatic migration via cloud policy.

The opt-out phase originally scheduled for April 2026 has been postponed to March 1, 2027, providing organizations with additional time to prepare.

**_Ref_**_:_ [https://admin.microsoft.com/#/MessageCenter/:/messages/MC949965](https://admin.microsoft.com/#/MessageCenter/:/messages/MC949965)

### March 2027 – Retirement of Security Questions in Microsoft Entra Self-Service Password Reset

Microsoft will retire security questions as an authentication method for Self-Service Password Reset (SSPR) in Microsoft Entra ID starting March 2027, due to security vulnerabilities and low verification reliability.

After this retirement, users will no longer be able to verify their identity using security questions during password reset. Organizations that continue relying on this method may experience failed password reset attempts, user lockouts, and increased help desk support requests.

**Solution:** Ensure users are registered with [supported authentication methods](https://learn.microsoft.com/en-us/entra/identity/authentication/tutorial-enable-sspr#select-authentication-methods-and-registration-options) before March 2027 to avoid Self-Service Password Reset failures.

**_Ref:_** [https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-security-questions](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-security-questions)

### March 31, 2027 – Microsoft Sentinel Retirement in Azure Portal

Microsoft is migrating Microsoft Sentinel from the Azure portal to the Microsoft Defender portal. After March 31, 2027, Microsoft Sentinel will no longer be supported in the Azure portal, and must be accessed through the Microsoft Defender portal.

The Microsoft Defender portal will become the primary management experience for Microsoft Sentinel and can be used even without Microsoft Defender XDR or a Microsoft 365 E5 license.

**_Ref:_** [https://learn.microsoft.com/en-us/azure/sentinel/overview?tabs=defender-portal#microsoft-sentinel-in-the-azure-portal-retirement-timeline](https://learn.microsoft.com/en-us/azure/sentinel/overview?tabs=defender-portal#microsoft-sentinel-in-the-azure-portal-retirement-timeline)

### April 1, 2027 – Exchange Online EWS Fully Retired

Exchange Web Services (EWS) in Exchange Online will be fully and permanently retired on April 1, 2027. Microsoft will progressively disable EWS beginning October 1, 2026, with the final shutdown removing the ability to use EWS in Exchange Online. Organizations should identify remaining EWS dependencies and migrate supported integrations to Microsoft Graph.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1447678](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1447678)

### April 2027 – Excel Power Query Retires the Microsoft Exchange Connector

Microsoft is retiring the existing Microsoft Exchange connector in Excel Power Query in April 2027. It will be replaced by new Exchange Mail and Exchange Calendar connectors. Existing workbooks will not automatically migrate, so workbook owners using the current connector will need to reconnect their Exchange data using the new connectors. The new connectors require Microsoft 365 Apps or Office 2024.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1461158](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1461158)

### May 2027 – Microsoft Entra Conditional Access Custom Controls Fully Retire

Microsoft Entra ID will fully retire Custom Controls in Conditional Access by May 2027, replacing them with External MFA for third-party MFA integrations. Custom Controls will stop being evaluated by the Conditional Access engine after the final retirement. Microsoft has already planned an earlier September 2026 milestone when administrators will no longer be able to create or modify Custom Controls.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1422061](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1422061)

### July 1, 2027 – Retirement of SharePoint Online Remote Event Receivers

Microsoft is retiring Remote Event Receivers (RERs) in SharePoint Online as part of its platform modernization. Azure ACS-registered RERs stopped working on April 2, 2026, while Microsoft Entra ID-registered RERs will continue to function until July 1, 2027, after which all RERs will stop working.

**Solutions:** Organizations should migrate to SharePoint webhooks or Microsoft Graph change notifications before the retirement date, as no extensions will be provided.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1411726](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1411726)

### October 2027 – Removal of Passcode Option from Create Meeting API

In October 2027, Microsoft will remove the option to create meetings without passcodes. This means all online meetings created through the Microsoft Graph API will automatically require a passcode, and the _isPasscodeRequired_ property on the _joinMeetingIdSettings_ resource will be removed. This change ensures that every meeting is consistently secured with a passcode, simplifying meeting creation, and improving security.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC985483](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC985483)

### October 14, 2027 – Retirement of Duplicative Properties in Passkey (FIDO2) Authentication Methods Policy

To align with the updated passkey policy API schema that supports group-based passkey profiles, Microsoft will retire _isAttestationEnforced_ and _keyRestrictions_ from the fido2AuthenticationMethodConfiguration API. During the transition, these properties will sync with attestationEnforcement and keyRestrictions in the Default passkey profile.

**Solution:** Admins should update configurations, automations, and integrations to use the new schema.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1188230](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1188230)

In conclusion, navigating the ever-evolving landscape of Microsoft 365 requires staying informed about the changes 🔍. By proactively adapting to these changes, you can optimize your Microsoft 365 experience, maximize productivity, and effectively plan for the future. 💪

We’re committed to keeping this blog fresh with the most current information. Stay tuned for the latest updates!

[https://blog.admindroid.com/microsoft-365-end-of-support-milestones/](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/)