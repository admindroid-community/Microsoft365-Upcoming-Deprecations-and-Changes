# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. 🌟 We’ll shed light on the features and products that are undergoing transformations or bidding farewell. Whether you’re a system administrator 🧑‍💻 managing the Microsoft 365 environment or an avid user 🙋‍♂️ staying ahead of the curve, this blog will provide invaluable insights and actionable recommendations.

🚀Discover the **key changes, deprecations,** and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we’ve got you covered! Make informed decisions and ensure a smooth transition.⚡️

## Microsoft 365 Upcoming Changes and Deprecations List:

Here is a list of changes categorized by month and year.

*   August 2026 (Retirements: 6, New Features: 10, Enhancements: 4, Existing Functionality Changes: 5, Action Needed: 5, Live: 1)
*   September 2026 (Retirements: 3, New Features: 14, Enhancements: 5, Existing Functionality Changes: 5, Action Needed: 2)
*   October 2026 (Attention Needed: 18)
*   Q4 2026 (Attention Needed: 5)
*   2027 (Attention Needed: 13)

## August 2026

Retirements: 6 | New Features: 10 | Enhancements: 4 | Existing Functionality Changes: 5 | Action Needed: 5 | Live Now: 1

### Retirements

### August 3, 2026 – Microsoft Entra Blocks New Assignments to Legacy Partner Tier Support Roles

Partner Tier 1 and Tier 2 Support are legacy Entra ID roles used by CSP partners for customer tenant administration under Delegated Admin Privileges (DAP). Microsoft Entra is retiring these support roles by blocking new assignments starting August 3, 2026. Existing assignments will continue to function, but new assignment requests via portals, APIs, or scripts will return an HTTP 400 error.

**Solution:** Audit admin scripts, CSP/GDAP workflows, and internal automation to replace these legacy roles with alternatives like User Administrator, Helpdesk Administrator, or custom least-privilege roles.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1409305](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1409305)

### Mid-August – Microsoft Outlook Deprecates Meeting Insights

Microsoft is retiring Meeting Insights from Outlook. As a result, users will no longer see relevant emails and files surfaced in meeting details.

**Solution:** Microsoft 365 Copilot users can instead use the “Prepare for this meeting” experience to access AI-generated meeting context, tasks, and relevant content.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1430531](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1430531)

### Mid-August – Outlook for Windows Report Retirement in the Exchange Admin Center

Microsoft will retire the Outlook for Windows reports from the Exchange admin center. To streamline and improve the reporting experience, this report will be removed automatically, with no option to opt out.

**Solution:** Admins can continue accessing Outlook for Windows usage insights through the Microsoft 365 admin center under Reports → Usage → Microsoft 365 Apps → Usage → Outlook for Windows.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230889](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230889)

### August 15, 2026 – OneDrive Sync App Ends Support for Windows 10 21H2 and Earlier

Microsoft is ending support for OneDrive sync app updates on devices running Windows 10 version 21H2 and earlier. Starting August 15, 2026, these devices will no longer receive feature updates, bug fixes, or security updates. Devices running Windows 10 version 22H2 will continue receiving OneDrive sync app updates through October 10, 2028.

**Solution:** Upgrade devices running Windows 10 21H2 and earlier to Windows 10 22H2 or Windows 11 to continue receiving OneDrive sync app updates.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1426708](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1426708)

### August 22, 2026 – End of Support for Legacy Microsoft Whiteboards and Standalone App

Microsoft Whiteboard is retiring legacy whiteboards and the standalone Whiteboard app as it completes the transition to OneDrive-backed whiteboards. Unmigrated legacy whiteboards will be permanently deleted and cannot be recovered. Enterprise users can continue using Microsoft Whiteboard through Microsoft Teams.

**Solution:** Migrate any remaining legacy whiteboards before August 22, 2026, verify the migration, and inform users about the transition to Microsoft Whiteboard in Microsoft Teams.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1441775](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1441775)

### Late-August 2026 – Microsoft Teams Removes CAPTCHA Policy for Meeting Join

Microsoft Teams will remove the “Require verification by participants (CAPTCHA)” policy from Teams admin center starting late August 2026, preventing admins from enabling it.

**Solution:** Microsoft will transition to a default-on bot detection capability that requires organizer approval for external bots.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1262588](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1262588)

### New Features

### August 2026 – OneDrive Adds Folder Exclusion for Sync

OneDrive for Windows and Mac will allow users to exclude selected folders from syncing, preventing local-only folders from being uploaded to the cloud. Administrators can also define organization-wide folder exclusion rules to ensure specified folders remain on users' devices.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=567470](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=567470)

### Early-August 2026 – Microsoft Entra ID Governance Account Discovery

Application accounts are accounts that exist directly within applications and are often created outside of Microsoft Entra ID. These may include local or orphaned accounts that are not centrally managed, making it difficult to track access and enforce governance.

Microsoft Entra ID Governance introduces Account Discovery to help administrators identify these accounts across connected applications. It can detect local and orphaned accounts and match them with Microsoft Entra ID users, improving visibility and access control.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1287372](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1287372)

### Mid-August 2026 – Archive Unused OneDrive and SharePoint Files in Microsoft Purview

An Archive option will be introduced in Microsoft Purview Data Lifecycle Management to move inactive OneDrive and SharePoint files to Microsoft 365 Archive. This helps reduce storage costs and improve Microsoft 365 Copilot responses.

The feature will be available in public preview, is disabled by default, and must be enabled by an administrator.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1325441](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1325441)

### Late-August 2026 - Microsoft Teams Extends Support for Teams Rooms Devices to Attend Webinars on Android

Microsoft is extending support for Teams Rooms devices with Teams Rooms Pro licenses to attend webinars and structured meetings as attendees on Android. The update enables Teams Rooms devices to use chat, reactions, raise hand, captions, participant roster, and visibility controls during meetings.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1317839](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1317839)

### Late-August 2026 – New Security Detection Report in Teams Admin Center

Microsoft will introduce a new report in the Teams admin center called the “Security Detection Report.” This report enables admins to review detection activities such as impersonation attempts, malicious URL detection, and identification of weaponizable file types.

Admins can also export detailed data from this centralized view for further investigation and analysis.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1311977](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1311977)

### Late-August 2026 – Microsoft Purview Adds View-Only Access for Role Management

Microsoft Purview now introduces view-only visibility for Global Reader and Security Reader roles. Users with these roles can now directly inspect role assignments and administrative scopes within the Microsoft Purview and Microsoft Defender portals without requiring elevated role management permissions.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1403403](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1403403)

### Late-August 2026 – Teams Expands Cross-Tenant Meeting Audit Visibility

Microsoft Teams extends Meeting Participant Detail audit records to participating tenants in cross-tenant meetings. Organizations can access audit records for their own users, including meeting organizer information, improving auditing and investigation while maintaining tenant data boundaries. Audit records for users from other participating organizations are not shared.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1441774](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1441774)

### Late-August 2026 – Microsoft Teams Adds Support for Existing Planner Plans in Meetings

Microsoft Teams now lets users link meetings to existing Microsoft Planner plans, allowing meeting tasks to be tracked alongside ongoing work instead of in separate plans. Facilitator can automatically add tasks to the linked plan, while users can also create tasks manually. If no plan is selected, Teams continues to create a new Planner plan by default. Targeted Release rollout begins in late August 2026.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1392571](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1392571)

### Late-August 2026 – Microsoft Entra ID Optimizes Passkey Registration Experience

Microsoft Entra ID is enhancing the passkey registration experience across Registration Campaign, Authentication Strengths, and My Sign-Ins. The passkey registration process remains unchanged for end users. Behind the scenes, updated logic automatically enforces admin passkey policies and prioritizes device-local passkeys when permitted.

This helps improve registration success without requiring any administrator action.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1440968](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1440968)

### Late-August 2026 – Microsoft Purview Adds Time-Limited Role Assignments

Microsoft Purview introduces time-limited role group assignments, allowing administrators to set expiration dates from 1 day to 2 years for users and security groups. The feature helps enforce temporary administrative access and least-privilege practices, with rollout to GCC, GCC High, and DoD starting in late August.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1411431](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1411431)

### Enhancements

### Early-August 2026 – Microsoft Teams Extends Custom Recording and Transcription Notifications to 1:1 Calls

Microsoft Teams is introducing custom recording and transcription notifications for 1:1 calls in targeted release, bringing the same consent messaging already available in meetings to one-on-one conversations. Existing meeting policy configurations will automatically apply to 1:1 calls, providing a consistent user experience. Mobile clients are not supported at this time.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1426709](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1426709)

### August 2026 – Microsoft Entra Supports Sensitivity Labels for Cloud Security Groups

Microsoft Entra now supports Microsoft Purview sensitivity labels for cloud security groups. This extends existing classification and governance policies to cloud security groups without requiring separate label configurations.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=568217](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=568217)

### Late-August 2026 – Microsoft Purview DLP Policy Sync Time Reduced from 2 Hours to 30 Minutes

Microsoft has reduced the synchronization interval for Microsoft Purview Data Loss Prevention (DLP) policies from 2 hours to 30 minutes. This change enables faster policy synchronization and enforcement across Microsoft 365 services. This helps organizations apply DLP protections more quickly.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1317834](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1317834)

### Late-August 2026 – Microsoft Planner Tab Support for Shared and Private Channels

Microsoft is expanding Planner integration within Teams by enabling Planner tabs in both Shared and Private channels. Starting late-August 2026, users can add new or existing plans directly to these environments, allowing for seamless task management within the channel. The feature is enabled by default.

Users can add Planner via the “+” tab experience, with plans inheriting channel permissions and Microsoft 365 compliance controls. Existing Planner behavior remains unchanged, and all data continues to follow current storage and retention policies.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1262590](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1262590)

### Existing Functionality Changes

### Early-August 2026 – Microsoft Defender Adds Quarantine Protection for Unscannable Encrypted Attachments

Microsoft Defender for Office 365 is introducing a new opt-in Safe Attachments policy to automatically quarantine emails containing password-protected attachments that cannot be scanned or detonated. This helps protect organizations from potentially malicious content that cannot be fully inspected.

Administrators can configure the policy and manage quarantined messages. They can also allow users to self-release eligible emails by providing the attachment password. The feature supports common password-protected file types, including ZIP, RAR, PDF, and Microsoft Office documents.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1440701](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1440701)

### August 2026 – Exchange Online Message Recall Expands to Cross-Tenant Emails

Exchange Online has expanded its message recall experience to support [cross-tenant email recall](https://blog.admindroid.com/configure-cross-tenant-message-recall-exchange-online/). Beginning in August 2026, users will also be able to recall emails sent to external organizations that have added their tenant to a recall allow list.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=561330](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=561330)

### August 2026 – Microsoft Entra Changes Default Federated Token Validation for Cross-Domain Sign-Ins

Microsoft Entra ID will change the default federated token validation behavior for cross-domain sign-ins. Going forward, sign-ins will be blocked by default when the internal domain federation does not match the user's User Principal Name (UPN) domain, strengthening security for federated authentication.

Previously, administrators had to manually configure this validation rule. With this update, the protection is enabled by default, reducing the risk of unauthorized cross-domain sign-ins.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=566869](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=566869)

### Mid-August 2026 – Microsoft Forms Changes Automated Email Sender Address

Microsoft Forms will change the sender address for its automated emails from _maccount@microsoft.com_ to _no-reply@forms.mail.microsoft_. This change applies to emails such as response receipts, new response notifications, and response monitoring updates. Organizations using a custom domain for Forms notifications are not affected.

Admins should review and update any mail flow rules, mailbox rules, or email filtering policies that reference the previous sender address. To ensure uninterrupted email delivery, consider adding the new sender address to your organization's safe sender or allow lists before the rollout.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1427970](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1427970)

### August 17, 2026 – SharePoint Embedded Updates driveItem.webUrl API Behavior

Microsoft is updating driveItem.webUrl in SharePoint Embedded to return a browser launch URL instead of a stable file URL, starting in mid-August 2026. Organizations requiring more time to migrate must opt out by August 17, 2026, which extends the current behavior until February 22, 2027. Update applications to use driveItemId for stable file identification before the extension expires.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1442608](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1442608)

### Action Required

### August 2026 – Deprecation of Teams Android Device Management in Teams Admin Center

Microsoft is transitioning Teams Android device management from the Teams admin center (TAC) to the Teams Rooms Pro Management (PMP) portal. As part of this transition, Microsoft will begin deprecating Teams Android device management capabilities in TAC in August 2026, with the process completing by September 2026.

**Solution:** Move Teams Android device management to the Teams Rooms Pro Management (PMP) portal and update administrator documentation before TAC capabilities are fully removed.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1227622](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1227622)

### August 1, 2026 – Exchange Online Retires Legacy TLS Support for POP3 and IMAP4

Exchange Online will retire support for TLS 1.0 and TLS 1.1 for POP3 and IMAP4 connections, requiring TLS 1.2 or later. Most modern email clients are already compatible, but legacy applications, devices, and custom systems using older TLS versions may no longer connect.

**Solution:** Administrators should verify that all POP3 and IMAP4 clients, applications, and devices support TLS 1.2 or later, and update or replace any legacy systems that still rely on older TLS versions.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1293480](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1293480)

### August 1, 2026 – Microsoft Defender Threat Intelligence to Merge with Defender and Sentinel

Microsoft Defender Threat Intelligence will merge with Microsoft Defender and Microsoft Sentinel by August 1, 2026, bringing threat intelligence directly into the SecOps workflow. After the transition, threat insights will be available through the Microsoft Defender portal, with enhanced Threat Analytics that include:

*   Indicators of Compromise (IoCs) integrated into reports
*   MITRE ATT&CK mappings for tactics and techniques
*   Insights into threat actors and targeted industries
*   IoCs linked to cases for Microsoft Sentinel customers

After August 1, 2026, accessing MDTI capabilities will require an active Microsoft Defender or Microsoft Sentinel license.

**Solution:** Plan your transition to Microsoft Defender or Microsoft Sentinel before the deadline and review licensing to ensure uninterrupted access to MDTI capabilities.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1192257](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1192257)

### August 4, 2026 – Microsoft Retires EWS-Based Controls for Personal Bookings

Microsoft will retire Exchange Web Services (EWS)-based controls for managing Personal Bookings in Microsoft Bookings. After August 5, 2026, access to Personal Bookings will be managed only through OWA Mailbox Policy settings, and existing EWS-based configurations will no longer be honored.

**Solution:** To maintain the intended Personal Bookings access, administrators must migrate existing EWS-based configurations to OWA Mailbox Policy by August 4, 2026.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1418559](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1418559)

### August 20, 2026 – Microsoft 365 Cleans Up Aged Pending Requests in All Agents

Microsoft 365 is performing a one-time cleanup of aged pending requests in All Agents. Pending requests created before June 1, 2026, that remain unresolved by August 20, 2026, will be permanently deleted. Approved and rejected requests will be retained.

**Solution:** Review pending requests created before June 1, 2026, and approve or reject any requests you want to retain before August 20, 2026.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1443510](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1443510)

### Live In August

Released in August, this feature is now ready for you to use.

### Microsoft Entra Cloud Sync Introduces Device Synchronization in Preview

Microsoft Entra Cloud Sync now includes [device sync](https://blog.admindroid.com/configure-device-sync-in-microsoft-entra-cloud-sync/) to synchronize Active Directory computer objects with Microsoft Entra ID, enabling Microsoft Entra hybrid join. The feature is currently available in preview and is disabled by default.

**_Ref:_** [https://learn.microsoft.com/en-us/entra/identity/hybrid/cloud-sync/device-sync](https://learn.microsoft.com/en-us/entra/identity/hybrid/cloud-sync/device-sync)

## September 2026

### Retirements

### September 1, 2026 – Microsoft Entra Retires Built-in SMS & Voice MFA and Moves to Passkeys by Default

Microsoft is [phasing out SMS and voice authentication](https://blog.admindroid.com/passkeys-default-sms-voice-authentication-retirement/), with complete retirement set for February 1, 2027. To guide organizations toward phishing-resistant MFA ahead of the deadline, Microsoft Entra will make passkeys the default authentication experience starting September 1, 2026, automatically prompting users to register passkeys during sign-in.

Organizations that still require telephony-based MFA after February 2027 must connect a custom provider through the Microsoft Security Store.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1426371](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1426371)

### September 17, 2026 – Retirement of Legacy Education LTI Tools

On September 17, 2026, Microsoft will retire legacy Education LTI tools such as Teams Assignments, OneDrive, OneNote Class Notebook, and Reflect, transitioning to a single Microsoft 365 LTI unified tool that users and admins must adopt.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1160188](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1160188)

### September 30, 2026 – Deprecation of Custom Controls in Microsoft Entra Conditional Access

Microsoft is officially retiring Conditional Access Custom Controls on September 30, 2026. This legacy preview feature is being replaced by External MFA, a more robust and integrated framework for third-party MFA providers.

**Solution:** Admins should migrate to External MFA before the retirement date to avoid disruption.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/external-mfa-in-microsoft-entra-id-is-now-generally-available/4488926#:~:text=Migration%20from%20Custom%20Controls](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/external-mfa-in-microsoft-entra-id-is-now-generally-available/4488926#:~:text=Migration%20from%20Custom%20Controls)

### New Features

### Early-September 2026 - Microsoft Teams Adds Recap Content Deletion for GCC High Environments

Microsoft Teams will allow organizers in GCC High environments to manage meeting-generated recap content using a new “Delete recap content” option available from the _More_ menu on the meeting recap page. The feature is expected to be generally available starting September 2026.

This capability enables deletion of selected recap content; however, shared content, custom summaries, and audio recaps cannot be deleted using this option. Deleted content cannot be restored.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1289725](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1289725)

### Early-September 2026 – Microsoft Defender for Office 365 Adds Prompt Injection Protection for Email

Microsoft Defender for Office 365 introduces prompt injection protection to detect and block malicious email content designed to manipulate AI assistants and agents. Emails identified as prompt injection attacks are classified as High Confidence Phish and automatically quarantined. The feature is enabled by default for organizations with Microsoft Defender for Office 365 Plan 2 or Microsoft 365 E5.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1422060](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1422060)

### Early-September 2026 – Microsoft Teams Introduces AI Meeting Archive Files

Microsoft Teams introduces AI meeting archive files that capture AI-generated meeting insights to improve responses from Microsoft 365 Copilot and Facilitator. The archive contains structured AI-generated meeting information instead of raw meeting content and is stored in a tenant-owned SharePoint Embedded container.

The feature is enabled by default, with administrator controls to manage archive generation and retention. Only meeting participants can access AI responses based on the meeting archive.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1429018](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1429018)

### Early-September 2026 - eSignature for Microsoft 365 Recipient Groups

When a specific signer is unavailable, workflows may be interrupted, causing delays in the signing process. To improve reliability, eSignature for Microsoft 365 recipient groups is being introduced, allowing a single recipient slot to be assigned to up to 10 people. The first available signer can complete the signing requirement. The feature is enabled by default and doesn’t require any admin configuration.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1290821](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1290821)

### September 2026 – Microsoft Teams Introduces Separate Attendance Report Policy for Events

Microsoft Teams is introducing a dedicated attendance and engagement report policy for Teams events, such as webinars and town halls, separating their controls from Teams meetings. This allows administrators to grant event organizers access to event attendance and engagement reports while separately controlling access to Teams meeting reports.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=567466](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=567466)

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

With this update, Microsoft introduces a [pay-as-you-go billing for extra SharePoint storage](https://blog.admindroid.com/pay-as-you-go-billing-for-extra-sharepoint-storage/) based on actual consumption. Storage is measured via a consumption-based meter, allowing organizations to pay only for what they use and improving overall cost efficiency.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1330893](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1330893)

### Mid-September 2026 - Full Workload Backup for SharePoint, OneDrive, and Exchange Enters Public Preview

A [Full Workload Backup](https://blog.admindroid.com/microsoft-365-backup-for-onedrive-sharepoint-and-exchange/#%F0%9F%91%89June-2026-Update%3A-Microsoft-Introduces-Full-Workload-Backup-for-SharePoint-Online%2C-Exchange-Online%2C-and-OneDrive) capability is being introduced for Microsoft 365 Backup, enabling organizations to create a single backup policy for an entire workload, including SharePoint, OneDrive, and Exchange Online. This policy will automatically protect all eligible artifacts within the selected workload.

This simplifies backup management and ensures coverage keeps pace with growing Microsoft 365 environments without requiring frequent policy updates.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1387526](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1387526)

### Late-September 2026 - Microsoft Teams Brings More Granular Controls for Channel Notifications

Microsoft Teams is introducing more granular channel notification options, including presets such as All new messages, Mentions and replies, and Mute. Within each option, users can further customize notifications for thread follows, tag mentions, channel mentions, and Teams mentions.

The feature is enabled by default for all users, providing greater control over how channel activity is surfaced.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1388719](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1388719)

### Late-September 2026 – Microsoft Purview Extends DLP Protection to the Network Layer

Microsoft Purview is extending Data Loss Prevention (DLP) to the network layer through integration with Microsoft Entra Internet Access, a component of Entra Global Secure Access (GSA). This enables organizations to inspect and protect sensitive data in network traffic, including AI prompts, files, and cloud service interactions, using existing Purview DLP policies.

The integration also enables administrators to audit or block sensitive data transfers and investigate alerts and incidents through Microsoft Purview and Microsoft Defender.  

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1419797](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1419797)

### Late-September 2026 – Microsoft Teams Adds Evaluation Scores for Apps and Agents

Microsoft Teams is introducing a centralized evaluation experience that automatically scores apps and agents against administrator-defined trust requirements, such as compliance and data residency. Detailed evaluation reports help administrators make faster, more consistent app approval decisions. The feature is enabled by default and becomes generally available in late September 2026.

*   Admins can define trust requirements, such as GDPR compliance, SOC 2 certification, and data residency, in _Teams admin center → Teams apps → Evaluation score settings_.
*   Then, admins can review evaluation scores in _Teams admin center → Teams apps → Manage apps_ and access detailed evaluation reports from the App details page.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1218713](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1218713)

### September 30, 2026 - New Outlook for Windows Becomes Available for GCC High and DoD Environments

Microsoft is introducing the new Outlook for Windows experience for all GCC High and DoD environments, providing users with access to modern Outlook features. The experience will be available as an opt-in feature and is off by default.

Existing organizational settings remain unchanged, and users are not automatically switched to the new Outlook. Users can switch between the new and classic Outlook experiences at any time using the built-in toggle.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1338816](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1338816)

### Enhancements

### Early-September 2026: Hard Delete SharePoint and OneDrive Files in Microsoft Purview

Microsoft Purview Data Lifecycle Management is introducing a new hard delete option in Priority Cleanup policies. The update adds a "Delete data permanently" action for supported SharePoint and OneDrive file types, allowing organizations to permanently remove files from storage. Deleted files will no longer be discoverable through Microsoft 365 services. The capability also applies to files governed by retention policies and retention labels.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1261587](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1261587)

### September 2026 – Microsoft Purview Extends DLP and Auto-Labeling to Non-Microsoft Connected Apps

Microsoft Purview plans to expand DLP and Information Protection Auto-labeling to supported non-Microsoft connected apps, including Google Workspace, Box, Dropbox, and Salesforce.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=568075](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=568075)

### Mid-September 2026 – Microsoft Purview Extends Endpoint DLP Protection to Excluded Windows Folders

Microsoft Purview Endpoint Data Loss Prevention (DLP) will extend protection to sensitive files stored in previously excluded Windows folders, such as AppData and temporary directories. Policy enforcement will apply during egress activities, including copying, printing, saving to network shares, and uploading to cloud services.

*   Audit mode: User actions continue and are logged for review.
*   Block mode: Restricted actions, such as copying, printing, or uploading sensitive files, are blocked.
*   If both policies apply: Block mode takes precedence over Audit mode.

Before enabling this feature, deploy Microsoft Defender anti-malware _client version 4.18.26051_ or later. Review excluded folder paths, update Endpoint DLP policies, and validate the changes in _Audit_ mode before enabling _Block_ mode.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1384420](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1384420)

### Mid-September 2026 – Microsoft Purview Changes Just-in-Time Audit Behavior for Endpoint DLP

Microsoft Purview Endpoint Data Loss Prevention (DLP) is changing how Just-in-Time protection collects audit events. Previously, user activities were automatically audited when Just-in-Time protection was enabled. Going forward, admins must explicitly configure which users or groups are included in the audit scope, giving organizations greater control over audit data collection and reducing unnecessary audit noise.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1387575](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1387575)

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

### September 30, 2026 – Upgrade to Microsoft Entra Connect v2.5.79.0 or Later

As part of Microsoft's ongoing security hardening, Microsoft Entra Connect now uses the Microsoft Entra AD Synchronization Service, a dedicated first-party application, to synchronize Active Directory with Microsoft Entra ID. Organizations must upgrade to Microsoft Entra Connect version 2.5.79.0 or later by September 30, 2026, to ensure uninterrupted synchronization.

**_Ref:_** [https://learn.microsoft.com/en-us/entra/identity/hybrid/connect/how-to-upgrade-previous-version?WT.mc\_id=Portal-Microsoft\_AAD\_IAM](https://learn.microsoft.com/en-us/entra/identity/hybrid/connect/how-to-upgrade-previous-version?WT.mc_id=Portal-Microsoft_AAD_IAM)

### Late-September 2026 – Update PowerPoint Client Versions to Access Captions & Subtitles

Microsoft is upgrading the backend service that supports Captions & Subtitles in PowerPoint. As a result, users running Microsoft 365 PowerPoint app versions earlier than 16.0.19426.20218 (Windows) or 16.103.1207.4 (macOS) will lose access to caption and subtitle features after the update.

**Solution:** Update PowerPoint clients to Windows (Win32) 16.0.19426.20218 or macOS 16.103.1207.4 or later.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1231437](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1231437)

### Late-September 2026 – Update Office Apps to Keep Read Aloud, Transcription, and Dictation Features

Read Aloud, Transcription, and Dictation features in Microsoft 365 Office apps will stop working on versions earlier than 16.0.18827.20202 because of backend upgrades. This change takes effect after September 2026 for Worldwide tenants and November 2026 for GCC, GCC High, and DoD environments.

**Solution:** Update all Office apps to 16.0.18827.20202 or later before the deadline.

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

### September 7, 2026 – Microsoft Entra ID SSPR Requires Registered Authentication Methods

Microsoft Entra ID Self-Service Password Reset (SSPR) currently allows password reset verification using certain directory-stored contact details, even if they were never registered as authentication methods. Starting September 7, 2026, only explicitly registered authentication methods will be accepted for SSPR verification. Users without registered methods will be unable to complete password resets.

**Solution:** Ensure users have at least one registered authentication method that satisfies your SSPR policy via Microsoft Entra admin center → Authentication methods → User registration details.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1325414](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1325414)

## October 2026 (Attention Needed: 18)

### October 1, 2026 - Exchange Web Services Will Be Blocked for Kiosk and Frontline Licenses

Microsoft will block Exchange Web Services access for mailboxes that do not include EWS usage rights starting June 30, 2026. After enforcement, requests made without a supported license will return an HTTP 403 error. Impacted licenses include Exchange Online Kiosk, Microsoft 365/Office 365 F1, and F3.

**Solution:** To continue using EWS, assign a license that includes EWS access, such as Exchange Online Plan 1 or 2 or Microsoft 365 E3/E5.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/update-to-ews-access-for-kiosk–frontline-worker-licensed-users/4474299](https://techcommunity.microsoft.com/blog/exchange/update-to-ews-access-for-kiosk%E2%80%93frontline-worker-licensed-users/4474299)

### October 01, 2026- Retirement of Exchange Web Services in Exchange Online

October 1, 2026, Microsoft will start blocking EWS requests from non-Microsoft apps to Exchange Online. The changes in Exchange Online do not affect Outlook for Windows or Mac, Teams, or any other Microsoft product.

**Solution:** Migrate your applications to Microsoft Graph to access Exchange Online data and gain access to the latest features and functionality.

**_Ref:_** [https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-exchange-web-services-in-exchange-online/ba-p/3924440](https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-exchange-web-services-in-exchange-online/ba-p/3924440)

### October 01, 2026- Sign-in Risk Policy and User Risk Policy Retirement from Entra ID Protection

User risk policy or Sign-in risk policy UX in Entra ID Protection (formerly Identity Protection) will be retired on October 1, 2026.

**Solution:** Migrate Sign-in risk and User risk policies to Conditional Access.

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/what-s-new-in-microsoft-entra/ba-p/3796395](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/what-s-new-in-microsoft-entra/ba-p/3796395)

### October 01, 2026 – Retirement of SharePoint One-Time Passcode for External Sharing

Microsoft will retire SharePoint One-Time Passcode authentication for external sharing beginning in October 2026. As part of this change, external sharing authentication in OneDrive and SharePoint will transition to Microsoft Entra B2B. External users who previously accessed content using OTP will receive access denied unless a corresponding guest account exists.

*   All external access shifts to Microsoft Entra B2B, enforcing Conditional Access, Identity Protection, and centralized guest governance.
*   Authentication, invitations, and audit tracking move from SharePoint OTP to Entra B2B and its audit logs.
*   Existing “specific people” links may fail for users without a corresponding guest account.

**Solution:** Create a guest account in Entra B2B or have an internal user re-share content to automatically provision the guest account and restore access.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1243549](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1243549)

### October 2026 - Microsoft Purview Adds Inline DLP Controls for Prompts in Microsoft Foundry Apps and Agents

Microsoft Purview Data Loss Prevention (DLP) will support inline DLP policies for built-in apps and agents in Microsoft Foundry. Organizations will be able to enable Microsoft Purview within Foundry to apply these policies. The integration helps prevent sensitive data from being shared through prompts and AI interactions, strengthening data protection controls.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1304291](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1304291)

### October 2026 – Just in Time Protection on SharePoint in DLP

Microsoft is introducing Just-in-Time protection for SharePoint in Microsoft Purview Data Loss Prevention in preview.

With this feature, organizations can automatically apply DLP restrictions to unclassified files when they are accessed or shared externally. Instead of restricting files in advance, JIT protection enforces security measures only when there is a risk of data leaving the organization.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457)

### October 2026 - Microsoft Teams Retires Calendar Functionality for Older Mobile App Versions

Microsoft Teams users on iOS and Android must update to the latest mobile app by early October 2026 to continue using Calendar. Calendar functionality will no longer be available in older Teams mobile app versions. Desktop and web clients are not affected.

**Solution:** Ensure users update to the latest Teams mobile app and configure managed devices to deploy app updates automatically. If your organization still relies on Exchange Web Services (EWS) for Teams Calendar functionality, you can extend EWS support until **April 2027**, but plan to transition before it is retired.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=567313](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=567313)

### October 2026 - Pay-as-You-Go Consumption-Based Billing for Extra OneDrive Storage

Microsoft is introducing a pay-as-you-go billing model for OneDrive storage based on consumption. When storage usage exceeds the allocated quota, additional capacity is automatically made available and billed based on actual consumption.

The model enables organizations to scale storage flexibly and pay only for the additional capacity consumed, reducing the need to purchase fixed storage add-ons.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=562352](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=562352)

### Early-October 2026 – AI-Powered Meeting Recap Without Recording or Transcript in Microsoft Teams

Microsoft Teams will introduce an AI-powered meeting recap feature that generates summaries without saving meeting transcripts or recordings. The feature will be available as an opt-in capability, and organizations with a Microsoft 365 Copilot (premium) license will be able to enable or disable it before or during meetings.

The AI-generated meeting summary will be saved as a document in the user’s OneDrive by default for 120 days, with options to customize the retention period. Deletion of post-meeting AI summaries is also supported.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1275312](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1275312)

### Early-October 2026 - Credential scanning in Microsoft Purview Data Security Posture Agent

A new Credential Scanning capability is introduced in Microsoft Purview Data Security Posture Agent to identify exposed credentials and related security risks across configured data sources. The AI-powered scanning engine uses large language models (LLMs) to detect sensitive credentials, including Microsoft Entra ID credentials, private keys, and API keys.

Scan results are presented through a dashboard with risk scores, AI-generated insights, and confidence ratings, enabling administrators to prioritize and remediate credential exposure more effectively.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1259828](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1259828)

### October 13, 2026- Retirement of Microsoft Publisher

In October 2026, Microsoft will discontinue Publisher in Microsoft 365, with on-premises suite support ending. While support lasts, they’re exploring modern alternatives across Word, PowerPoint, and Designer for common Publisher tasks, with updates forthcoming.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC716267](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC716267)

### October 13, 2026 – End of Support for Office LTSC 2021 And Additional Apps

Microsoft will retire Office LTSC 2021, Visio LTSC 2021, Microsoft Project LTSC 2021, and a few other products on October 13, 2026.

To continue receiving support and updates, Microsoft recommends upgrading to a Microsoft 365 or Office 365 plan that includes Microsoft 365 Apps. If a fully offline solution is required, upgrading to Office LTSC 2024 is recommended, which will be supported until October 2029.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1278920](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1278920)

### Mid-October 2026 – Content Security Policy for Entra ID Sign-in Experience

Microsoft Entra ID is enforcing a stricter Content Security Policy (CSP) for sign-ins starting mid-October 2026. Only trusted Microsoft scripts will be allowed, blocking injected code to reduce XSS risks. This applies to browser-based sign-ins on login.microsoftonline.com and does not affect Entra External ID tenants.

**Solution:** If you use tools or extensions that inject code, switch to non-injecting alternatives and test sign-in flows before CSP enforcement begins.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1191924](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1191924)

### Late-October 2026 – Microsoft Entra Enables Passwordless Password Changes from My Sign-Ins

Microsoft Entra will allow passwordless users to change their passwords directly from _My Sign-Ins_ page using a strong credential, such as a passkey, FIDO2 security key, or Windows Hello for Business.

Users can complete the password change without knowing their current password or using Self-Service Password Reset (SSPR). The feature is disabled by default and can only be enabled as a tenant-wide setting.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1437671](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1437671)

### Late-October 2026 – Purview Integrates Adaptive Protection with Data Lifecycle Management

Microsoft Purview is integrating Adaptive Protection with Data Lifecycle Management (DLM) to automatically retain content deleted by elevated-risk users for 120 days. Administrators can enable the integration from the Microsoft Purview compliance portal, after which Microsoft automatically creates and manages the required retention label and policy.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC791110](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC791110)

### October 26, 2026 – Microsoft Entra ID Retires Custom CSS Positioning Properties in Company Branding

As part of Microsoft's Secure Future Initiative (SFI), Microsoft Entra ID will retire support for custom CSS positioning properties used in company branding starting October 26, 2026. Properties such as position, margin, transform, opacity, overflow, filter, and other layout-related CSS properties will no longer be supported to improve sign-in security and phishing resistance.

Branding elements that rely on these retiring properties will remain visible but may revert to their default placement. Additionally, custom CSS is already unavailable for company branding in Microsoft Entra ID tenants created after January 5, 2026.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1435782](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1435782)

### October 28, 2026 – Retirement of Microsoft Entra PIM Iteration 2 (Beta) APIs

Microsoft will retire Microsoft Entra Privileged Identity Management Iteration 2 (beta) APIs on October 28, 2026. After this date, applications and scripts using these APIs will fail because the endpoints will no longer return data.

**Solution:** Migrate to the Iteration 3 (GA) APIs, which are fully supported and more reliable. Stop new development on Iteration 2 APIs and begin migration planning.

Ref: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1181281](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1181281)

### October 31, 2026 – Retirement of Microsoft Defender for Endpoint on Amazon Linux 2 (ARM64)

From October 31, 2026, Microsoft will retire support for Microsoft Defender for Endpoint on Amazon Linux (ARM64). Linux versions beyond 101.25122.0004 will no longer install on AL2 environments, and affected devices will miss security enhancements and feature updates.

**Solution:** Organizations should migrate to a supported Linux distribution for Microsoft Defender for Endpoint before October 31, 2026, to ensure continued security updates and feature support.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1392568](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1392568)

## Q4 2026 (Attention Needed: 5)

### Late-November 2026 – Microsoft Purview Insider Risk Management Adds Policy Recommendations Panel

Microsoft Purview Insider Risk Management will introduce a Policy Recommendation panel to help administrators identify gaps in insider risk coverage and prioritize new policy creation. The feature uses analytics to recommend policies for scenarios such as data leakage, data theft, risky AI usage, IP theft, and security violations.

Existing policies remain unchanged and the feature is enabled by default.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher#/MessageCenter/:/messages/MC1387681](https://admin.cloud.microsoft/?source=applauncher#/MessageCenter/:/messages/MC1387681)

### December 2026 – Credential Parameter Retirement in Exchange Online PowerShell

Exchange Online PowerShell is deprecating the _\-Credential_ parameter as it relies on the legacy ROPC authentication flow that does not support MFA or Conditional Access. This change applies to both the _Connect-ExchangeOnline_ and _Connect-IppsSession_ cmdlets.

**Solution:** Move to secure authentication methods such as _interactive sign-in,_ _app-only authentication_, or _managed identity authentication_ when connecting to Exchange Online PowerShell.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/deprecation-of-the–credential-parameter-in-exchange-online-powershell/4494584](https://techcommunity.microsoft.com/blog/exchange/deprecation-of-the%E2%80%93credential-parameter-in-exchange-online-powershell/4494584)

### December 2026 – Custom Retention for Message Trace Logs in Exchange Online

Starting in December 2026, organizations will be able to select how long Message Trace data is retained by choosing from a set of predefined retention periods. This enhancement gives admins greater flexibility to align log retention with their compliance, audit, and operational requirements.

Ref: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=542929](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=542929)

### End of December 2026 – Disable SMTP Auth for Basic Authentication

SMTP AUTH Basic Authentication will be disabled by default for existing tenants by Dec end, though admins can enable it if required.

**Solution:**

*   Migrate applications and devices to OAuth-based authentication.
*   Use alternatives such as High-Volume Email for Microsoft 365, Azure Communication Services for Email, or an on-premises Exchange.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835](https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835)

### December 31, 2026 – End of Support for Dynamics 365 Guides and Remote Assist

Dynamics 365 Guides and Dynamics 365 Remote Assist will retire on December 31, 2026. After this date, the products will no longer receive security updates, bug fixes, or technical support.

**Solution:** Customers should plan their transition early by identifying dependent users and scenarios. Explore alternative mixed reality solutions available in the Microsoft Marketplace, and consider Microsoft Teams Mobile with spatial annotation for certain remote collaboration use cases.

**_Ref:_** [https://learn.microsoft.com/en-us/lifecycle/announcements/dynamics-365-guides-remote-assist-end-of-support](https://learn.microsoft.com/en-us/lifecycle/announcements/dynamics-365-guides-remote-assist-end-of-support)

## 2027 (Attention Needed: 13)

### January 2027 – Retirement of Basic Authentication for Client Submission in Exchange Online

Microsoft will disable Basic Authentication with Client Submission (SMTP AUTH) by default starting January 2027. OAuth will be the supported authentication method.

**Proactive Steps:**

*   Move applications and devices to OAuth-based authentication for SMTP AUTH.
*   If Basic Authentication is still needed, consider alternatives such as High-Volume Email for Microsoft 365, Azure Communication Services for Email, or an on-premises Exchange Server in a hybrid setup.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835](https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835)

### January 2027 - End of Life of Standalone SharePoint Online and OneDrive for Business Plans

Microsoft is ending the lifecycle of standalone SharePoint Online Plan 1 and Plan 2 and OneDrive for Business Plan 1 and Plan 2. In June 2026, new customers are no longer able to purchase these standalone plans. From June 2027, renewals will no longer be permitted, although existing subscriptions will continue until their expiration.

**Solution:** Move to Microsoft 365 suite offerings such as Business Basic, Business Standard, Business Premium, E1, E3, or E5 for continued service availability.

**_Ref:_** [https://learn.microsoft.com/en-us/partner-center/announcements/2026-january#retirement-of-standalone-sharepoint-online-and-onedrive-for-business-plans-plan-1-and-plan-2](https://learn.microsoft.com/en-us/partner-center/announcements/2026-january#retirement-of-standalone-sharepoint-online-and-onedrive-for-business-plans-plan-1-and-plan-2)

### Late-January 2027 - Microsoft Extends DLP to Restrict Processing of External Emails in Copilot

Microsoft is extending Data Loss Prevention (DLP) support for Microsoft 365 Copilot and Copilot Chat by introducing a new capability to exclude emails from external or untrusted domains. These emails will not be used for summarization, responses, or grounding data in Copilot experiences.

The feature is available as an opt-in option. Once enabled, emails from trusted internal sources will continue to be used for Copilot responses, while content from external untrusted domains will be restricted.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1301714](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1301714)

### January 06, 2027 – Microsoft Purview Retires the Instances Policy Location for DLP

Microsoft Purview will retire the Instances policy location for Data Loss Prevention (DLP) on January 6, 2027. Dedicated application locations are being introduced for supported non-Microsoft applications, replacing the existing Instances locations.

**Solution:** Review existing DLP and auto-labeling policies that use the Instances location and recreate them using the corresponding dedicated application locations before January 6, 2027.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1429010](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1429010)

### January 31, 2027 – Retirement of MDE and XDR Advanced Hunting APIs

To unify the interface across Microsoft Defender products, Microsoft will retire the Microsoft Defender for Endpoint (MDE) Advanced Hunting API and Microsoft Defender XDR Advanced Hunting API.

**Solution:** Move to Microsoft Graph Security API for broader data coverage, improved consistency, and better scalability for automation and security workflows.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1220762](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1220762)

### January 31,2027 – Full Retirement of Restricted SharePoint Search

Microsoft will fully retire Restricted SharePoint Search (RSS), which limits how SharePoint content appears in Microsoft Search and Microsoft 365 Copilot, by January 31, 2027. Existing Restricted SharePoint Search configurations will not be automatically migrated to Restricted Content Discovery (RCD).

**Solution:** Organizations should migrate from Restricted SharePoint Search to Restricted Content Discovery (RCD) or adopt another appropriate control for managing content discoverability before the retirement date.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1395311](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC13953114)

### February 1, 2027 – Retirement of Built-in SMS and Voice MFA in Microsoft Entra

Microsoft is retiring its built-in SMS and voice authentication service in Microsoft Entra on February 1, 2027. Organizations that continue using SMS or voice MFA must configure a supported telecom provider, as Microsoft will no longer provide these services.

Passkeys become the recommended authentication method going forward. Tenants that continue relying only on Microsoft's built-in SMS or voice authentication may experience sign-in disruptions after February 1, 2027.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1426371](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1426371)

### March 01, 2027 – Automatic Migration to New Outlook for Windows

Microsoft 365 Enterprise users will automatically switch to the new Outlook for Windows, gaining access to modern features like Copilot, theming, and time-saving options such as Pinning and Snoozing emails. A toggle will be available for users to revert to the classic Outlook. Admins can prevent this automatic migration via cloud policy.

The opt-out phase originally scheduled for April 2026 has been postponed to March 1, 2027, providing organizations with additional time to prepare.

**_Ref:_** [https://admin.microsoft.com/#/MessageCenter/:/messages/MC949965](https://admin.microsoft.com/#/MessageCenter/:/messages/MC949965)

### March 2027 – Retirement of Security Questions in Microsoft Entra Self-Service Password Reset

Microsoft will retire security questions as an authentication method for Self-Service Password Reset (SSPR) in Microsoft Entra ID starting March 2027, due to security vulnerabilities and low verification reliability.

After this retirement, users will no longer be able to verify their identity using security questions during password reset. Organizations that continue relying on this method may experience failed password reset attempts, user lockouts, and increased help desk support requests.

**Solution:** Ensure users are registered with supported authentication methods before March 2027 to avoid Self-Service Password Reset failures.

**_Ref:_** [https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-security-questions](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-security-questions)

### March 31, 2027 – Microsoft Sentinel Retirement in Azure Portal

Microsoft is migrating Microsoft Sentinel from the Azure portal to the Microsoft Defender portal. After March 31, 2027, Microsoft Sentinel will no longer be supported in the Azure portal, and must be accessed through the Microsoft Defender portal.

The Microsoft Defender portal will become the primary management experience for Microsoft Sentinel and can be used even without Microsoft Defender XDR or a Microsoft 365 E5 license.

**_Ref:_** [https://learn.microsoft.com/en-us/azure/sentinel/overview?tabs=defender-portal#microsoft-sentinel-in-the-azure-portal-retirement-timeline](https://learn.microsoft.com/en-us/azure/sentinel/overview?tabs=defender-portal#microsoft-sentinel-in-the-azure-portal-retirement-timeline)

### July 1, 2027 – Retirement of SharePoint Online Remote Event Receivers

Microsoft is retiring Remote Event Receivers (RERs) in SharePoint Online as part of its platform modernization. Azure ACS-registered RERs stopped working on April 2, 2026, while Microsoft Entra ID-registered RERs will continue to function until July 1, 2027, after which all RERs will stop working.

**Solutions:** Organizations should migrate to SharePoint webhooks or Microsoft Graph change notifications before the retirement date, as no extensions will be provided.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1411726](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1411726)

### October 2027 – Removal of Passcode Option from Create Meeting API

In October 2027, Microsoft will remove the option to create meetings without passcodes. This means all online meetings created through the Microsoft Graph API will automatically require a passcode, and the isPasscodeRequired property on the joinMeetingIdSettings resource will be removed. This change ensures that every meeting is consistently secured with a passcode, simplifying meeting creation, and improving security.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC985483](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC985483)

### October 14, 2027 – Retirement of Duplicative Properties in passkeys (FIDO2) Authentication Methods Policy

To align with the updated passkey policy API schema that supports group-based passkey profiles, Microsoft will retire isAttestationEnforced and keyRestrictions from the fido2AuthenticationMethodConfiguration API. During the transition, these properties will sync with attestationEnforcement and keyRestrictions in the Default passkey profile.

**Solution:** Admins should update configurations, automations, and integrations to use the new schema.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1188230](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1188230)

In conclusion, navigating the ever-evolving landscape of Microsoft 365 requires staying informed about the changes 🔍. By proactively adapting to these changes, you can optimize your Microsoft 365 experience, maximize productivity, and effectively plan for the future. 💪

We are committed to keeping this blog updated with the latest information, so stay tuned for upcoming updates.

[https://blog.admindroid.com/microsoft-365-end-of-support-milestones/](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/)