# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. 🌟 We’ll shed light on the features and products that are undergoing transformations or bidding farewell. Whether you’re a system administrator 🧑‍💻 managing the Microsoft 365 environment or an avid user 🙋‍♂️ staying ahead of the curve, this blog will provide invaluable insights and actionable recommendations.

🚀Discover the **key changes, deprecations,** and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we’ve got you covered! Make informed decisions and ensure a smooth transition.⚡️

## Microsoft 365 Upcoming Changes and Deprecations List:

Here is a list of changes categorized by month and year.

*   June 2026 (Retirements: 5, New Features: 15, Enhancements: 8, Existing Functionality Changes: 6, Action Needed: 3, Live Now: 1)
*   July 2026 (Retirements: 7, New Features: 11, Enhancements: 3, Existing Functionality Changes: 2, Action Needed: 5)
*   August 2026 (Attention Needed: 4)
*   September 2026 (Attention Needed: 7)
*   Q4 2026 (Attention Needed: 9)
*   2027 (Attention Needed: 6)

## June 2026

Retirements: 5 | New Features: 13 | Enhancements: 8 | Existing Functionality Changes: 6 | Action Needed: 3 | Live Now: 1

### Retirements

### June 1, 2026 – Retirement of the Sway Windows Desktop App

To streamline app management and focus on a fully supported web experience, Microsoft will retire the Sway Windows desktop app.

**Solution:** Users should switch to the web version at _sway.cloud.microsoft_, which provides the same features, preserves all content, and offers improved accessibility and updates.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1213784](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1213784)

### Mid-June 2026 - Outlook for Windows Report Retirement in the Exchange Admin Center

Microsoft will retire the Outlook for Windows reports from the Exchange admin center. To streamline and improve the reporting experience, this report will be removed automatically, with no option to opt out.

**Solution:** Admins can continue accessing Outlook for Windows usage insights through the Microsoft 365 admin center under _Reports > Usage > Microsoft 365 Apps > Usage > Outlook for Windows_

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230889](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230889)

### June 29, 2026 – Deprecation of Teams Live Events

Microsoft is retiring Teams Live Events and related Microsoft Graph APIs on June 30, 2026. Existing live events will continue to function until _February 28, 2027_, but customers will no longer be able to schedule new Teams Live Events, including through Dynamics 365, after the retirement date. The _isBroadcast_ property in the _onlineMeeting_ Graph resource will remain available only until June 30, 2026.

**Solution:** Migrate to Teams town halls, adopt the new Teams meeting Graph APIs, and update workflows or applications that depend on the _isBroadcast_ property by _June 29, 2026_.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1226495](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1226495)

### June 30, 2026 – Retirement of Assignments and Courses ACEs in Viva Connections and SharePoint

To modernize Viva Connections, Microsoft will retire the Assignments and Courses adaptive card extensions (ACEs) and their SharePoint dashboard web parts for Education tenants. These SPFx components currently surface assignment and course information on the dashboard, and their removal aims to reduce redundancy and streamline the user experience. Also, the existing components will reach the end of support on June 30, 2026.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184647](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184647)

### June 30, 2026 - Retirement of Legacy Third-party Teams Meeting and Call Control APIs

Microsoft Teams currently supports certain external apps and hardware, such as meeting control devices and third-party tools to control meetings and calls through an unsupported approach.

Starting June 30, 2026, Microsoft will retire this capability completely. After this change, these external tools will no longer be able to control Teams meetings or calls, and the related privacy setting in the Teams desktop client will also be removed.

This update only affects organizations relying on such integrations. Native Teams functionality will continue to work as expected, and supported integration models will remain available.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1266901](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1266901)

### New Features

### June 01, 2026 - Billing Begins for High Volume Email in Microsoft 365

High Volume Email (HVE) for Microsoft 365 is now generally available, with metered billing starting June 1, 2026. HVE is designed for large-scale internal communications that exceed standard Exchange Online sending limits and is priced at $42 per million recipients. Organizations using HVE should configure billing before the deadline to avoid service interruptions.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1243552](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1243552)

### June 2026 - Governance Reviews Dashboard for SharePoint Site Owners

A Governance Reviews Dashboard (Private Preview) will be introduced to consolidate all site governance tasks into a single unified view. With this dashboard, site owners can track pending reviews, such as inactivity checks, ownership validation, and attestation requirements across all managed sites.

It provides clear visibility into required actions, deadlines, and enforcement status, enabling faster responses without switching between multiple tools. By consolidating policy notifications into one place, it reduces reliance on scattered email alerts and delivers a more streamlined, action-oriented governance experience.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=560541#Roadmap](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=560541#Roadmap)

### June 2026 – Detailed Permissions Report for Everyone Groups in SharePoint Online

SharePoint Online adds a new report to identify permissions granted to the _"Everyone"_ and _"Everyone except external users"_ groups. The report provides item-level visibility into broadly accessible content, helping SharePoint Advanced Management administrators review permissions and strengthen access governance.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=561038](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=561038)

### Early-June 2026 – App Instance Lock Enabled by Default for New Entra Applications

Microsoft Entra will enable App Instance Lock by default for newly created applications. Sensitive service principal properties, such as password credentials, will be protected by default and cannot be modified from outside the application's home tenant.

Organizations should review automation and provisioning workflows that update protected properties. If post-creation updates to protected properties are necessary, app owners and administrators can manually disable App Instance Lock for specific applications.

Without disabling this feature, any attempt to modify the protected properties of a locked application will fail, resulting in a _400 Bad Request error_.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1300584](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1300584)

### Early-June 2026 - Identify External Bots Joining your Teams Meetings

Microsoft Teams is introducing automatic detection of external meeting assistant bots, providing organizations with greater visibility and control over automated participants. When a bot attempts to join a meeting, it will be clearly labeled in the lobby, allowing organizers to approve, block, or remove it.

Additionally, a new admin policy will enable administrators to define how such bots are handled across the organization. This feature will be enabled by default for all tenants, with rollout in general availability by mid-June 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1251206](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1251206)

### Early-June 2026 - File Quarantine Action for SharePoint and OneDrive for DLP

Microsoft will introduce a new option in Microsoft Purview Data Loss Prevention (DLP) for SharePoint and OneDrive called “File Quarantine.” When configured, any file that violates a DLP policy will be automatically moved to an admin-defined quarantine location.  
  
A tombstone file will be placed in the original location to inform users about the quarantine action, along with an admin-defined message. Admins can monitor these activities through Audit logs, DLP alerts, and Activity Explorer.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1288527](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1288527)

### Early-June 2026 – Teams Android Device Management Moves to Pro Management Portal

Teams Rooms on Android, Teams phones, Teams panels, and Teams displays will be managed through the Pro Management Portal (PMP) instead of the Teams Admin Center, unifying device management in one place.

As part of this transition, device inventory and health data will automatically appear in PMP. Admins performing management actions in TAC will be redirected to the new portal experience. The rollout is expected to reach general availability across Worldwide and GCC environments by early June 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1227622](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1227622)

### Mid-June 2026 – New SharePoint Experience Introduced with Registered Navigation and AI Enhancements

  
A [new SharePoint experience](https://blog.admindroid.com/new-sharepoint-experience-in-microsoft-365/) is being introduced with a streamlined design and better navigation to help users discover content, publish information, and build solutions more efficiently. The update also includes AI-assisted capabilities, which require a Microsoft 365 Copilot license.  
  
This experience introduces a redesigned SharePoint app bar with options such as Discover, Publish, Build, OneDrive, and Home. It also brings refreshed pages, news, libraries, and lists to improve content visibility while preserving existing site branding. The general availability is scheduled to begin in mid-June 2026.  
  
**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1240699](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1240699)

### Mid-June 2026 – Purview Insider Risk Management Adds Visibility into AI Interactions

A new capability to view AI interactions associated with insider risk indicators reaches general availability in Microsoft Purview Insider Risk Management. This helps analysts investigate potential risks such as data leakage, policy violations, and inappropriate AI usage.

User identities remain pseudonymized even when AI interactions are visible and can only be revealed through a permitted deanonymization action by an authorized analyst. Existing role-based access controls, audit logging, and privacy safeguards remain unchanged.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1304292](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1304292)

### Mid-June 2026 – Microsoft 365 Copilot Planner Agent Reaches General Availability

The Planner agent will be generally available in Microsoft 365 Copilot for users with an active Copilot license. Users can create, update, and manage personal tasks and shared plans directly within Copilot, reducing the need to switch applications. The agent also provides insights into priorities, deadlines, and at-risk work.

The Planner agent is preinstalled for eligible users. Admins can no longer limit the agent to specific user groups but can disable it for the entire tenant through the Microsoft 365 admin center.

Ref: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1323264](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1323264)

### Mid-June 2026 – Microsoft Teams Adds Support for Reporting Suspicious External Users

Teams will soon allow users to report suspicious external users directly from Teams, adding another layer of protection against phishing, impersonation, and social engineering attacks. Reported users will be surfaced in the Teams admin center, helping administrators investigate suspicious activity more efficiently.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1309744](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1309744)

### Late-June 2026 – Integration of Adaptive Protection with Data Lifecycle Management

Microsoft plans to make the Adaptive Protection and Data Lifecycle Management (DLM) integration generally available by late June 2026. This integration allows administrators to retain or restore items deleted by high-risk users, providing better safeguards against insider threats and accidental data loss.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110)

### Late-June 2026 – SharePoint File-Level Archiving Coming to Microsoft 365 Archive

Microsoft 365 Archive will support file-level archiving in SharePoint, enabling more granular retention and storage control. This feature will reach general availability in June 2026.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1326254](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1326254)

### Enhancements

### June 2026 – Mail Merge (Advanced) in Outlook on the Web & New Outlook for Windows

Outlook on the web and the new Outlook for Windows will receive enhanced Mail Merge (Advanced) capabilities. With this update, users will be able to insert dynamic fields into email templates, enabling more personalized and customized communication at scale.

This enhancement simplifies the process of tailoring messages, making it more efficient to send targeted and professional emails.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047)

### June 2026 – Insider Risk Management for AI Agents

As AI agents become more common in Microsoft 365, associated risks also continue to rise. Microsoft will extend Insider Risk Management to cover AI agents, enabling admins to define policies specifically for agent-driven activities. This enhancement helps detect, flag, or block risky behaviors when AI agents access sensitive data or perform high-risk actions across platforms like Copilot Studio, Azure AI Foundry, and Agent 365.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=516032](https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=516032)

**June 2026 – Microsoft Purview Enhances Role Groups Management Experience**

Microsoft Purview will introduce the enhanced Role Groups management experience in preview starting June 2026. This update enhances the Role Groups page in the compliance portal to simplify permission management and access reviews. Administrators will be able to look up permissions by role and membership, making it easier to understand assigned privileges, review access, and manage compliance roles more efficiently.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=562033](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=562033)

### Early-June 2026 – New Web Parts and Teams App Customization for SharePoint Home Sites

Microsoft is introducing several improvements to SharePoint home sites and the SharePoint app in Teams, including:

*   Simplified home site setup and management from the SharePoint admin center.
*   New Resources web part to highlight important links, tools, and destinations.
*   New Announcements web part for organization-wide communications.
*   The new web parts surface existing SharePoint content while preserving current permissions and access controls.
*   Additional customization options for the SharePoint app in Teams _(formerly Viva Connections_).
*   Site owners can choose whether to add and use the new Resources, Announcements, and News web parts.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1304293](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1304293)

### Early-June 2026 – Microsoft Outlook Adds External Email Tag Support to Inbox Rules

The External email tag made it easier to identify messages from outside the organization, but managing those emails still required manual effort. Microsoft is now adding support for the [External email tag in Outlook Inbox Rules](https://blog.admindroid.com/microsoft-adds-external-email-tag-support-to-outlook-inbox-rules/), allowing users to automatically move, categorize, or prioritize emails from external senders. The feature will be generally available in _early June 2026_, supported across modern Outlook clients, and enabled by default in organizations where the External email tag is active.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1319208](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1319208)

### Early-June 2026 – ZAP Expands Protection to Emails in the Deleted Items Folder

Zero-hour Auto Purge (ZAP) will now scan and remediate malicious emails in users' Deleted Items folders. This enhances post-delivery protection by ensuring phishing, spam, and malware messages continue to be cleaned up even after users delete or report them.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1323263](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1323263)

### Mid-June 2026 – Microsoft 365 Packaging Update Adds New Security, Intune, and Storage Features

Ahead of the Microsoft 365 pricing taking effect on July 1, 2026, Microsoft is rolling out several new security, device management, and storage capabilities to eligible Microsoft 365, Office 365, and EMS suites, including:

*   Microsoft Defender for Office 365 Plan 1 and URL time-of-click protection.
*   Intune capabilities such as Remote Help, Advanced Analytics, Endpoint Privilege Management, Enterprise Application Management, and Cloud PKI.
*   An additional 50 GB of Exchange Online mailbox storage.

Defender protections will be enabled by default, while Intune capabilities require admin configuration before use.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1304290](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1304290)

### Late-June 2026 – Retention Based on “Last Accessed” for OneDrive and SharePoint

Previously, retention policies could delete content based on conditions such as ‘_When items were created’_ or ‘_When items were last modified’_. Microsoft is now enhancing Data Lifecycle Management by introducing a new _“When items were last accessed”_ condition for retention policies.

This feature allows admins to manage and automatically clean up OneDrive and SharePoint content based on access history. It improves storage hygiene and helps optimize Microsoft 365 Copilot responses.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442)

### Existing Functionality Changes

### June 1, 2026 – Microsoft Entra Blocks Hard Match for Users with Entra Roles

Hard match allows Microsoft Entra Connect Sync and Cloud Sync to link an on-premises user with an existing cloud-managed user and take over its source of authority. Starting June 1, 2026, hard-match operations will be blocked for cloud-managed users assigned Microsoft Entra roles, helping protect privileged accounts from unauthorized takeover attempts.

Hard matches for users without Entra roles, soft-match behavior, and synchronization of previously hard-matched users are not affected.

Ref: [https://learn.microsoft.com/en-us/entra/#microsoft-entra-connect-security-update-to-block-hard-match-for-users-with-microsoft-entra-roles](https://learn.microsoft.com/en-us/entra/fundamentals/whats-new?WT.mc_id=Portal-Microsoft_AAD_IAM#upcoming-change--microsoft-entra-connect-security-update-to-block-hard-match-for-users-with-microsoft-entra-roles)

### Early-June 2026 – Microsoft Purview Updates Search-UnifiedAuditLog ResultCount Behavior

Microsoft Purview is bringing the updated _Search-UnifiedAuditLog_ cmdlet experience to GCC High and DoD environments in June 2026. Currently, the _ResultCount_ parameter returns the total number of results expected from a query.

With this update, _ResultCount_ will display a running count of records retrieved during query execution, while a new _moreRecordsAvailable_ property will indicate whether additional records remain. Organizations using scripts or automation that rely on the current _ResultCount_ behavior should review and update them accordingly.

**_Ref_**: [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1310672](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1310672)

### Early-June 2026 – Decoupling Policy Tips & Email Notifications for SharePoint and OneDrive DLP

Currently, enabling email notifications in DLP policies for SharePoint and OneDrive also enforces policy tips, and vice versa. With this update, Microsoft introduces the ability to configure policy tips and email notifications independently, providing greater flexibility in how alerts are managed.

This feature will be available in general availability by early June 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC791114](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC791114)

### Mid-June 2026 - Microsoft Purview eDiscovery: Naming and Description Fields will Restrict Certain Special Characters

Microsoft Purview eDiscovery will restrict certain special characters, such as “+, =, @, /, and \*” in naming and description fields for new or edited cases, holds, searches, and review sets.  
  
If users include these characters, they will be prompted to remove them from the fields. Existing names and descriptions will remain unchanged until the user chooses to edit them.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1282562](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1282562)

### Mid-June 2026 – Profanity Filter Disabled by Default for Teams Live Captions

Microsoft is changing the default profanity filter setting for Teams live captions from **On** to **Off** for users who have not previously configured the setting. This allows captions to more accurately reflect spoken content while supporting accessibility and regional compliance requirements.

Users can enable or disable the profanity filter at any time, and existing user preferences will remain unchanged.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=560323](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=560323)

### Mid-June 2026 – Microsoft Clipchamp Updates License and Service Plan Names

Microsoft is updating Clipchamp license (SKU) and service plan names across Microsoft 365 licensing, billing, purchasing, and reporting experiences. For example, _Clipchamp Premium_ will be renamed to _Clipchamp Editor Premium_.

The change is automatic and does not affect features or user access, but organizations should update any documentation, reports, or scripts that reference existing Clipchamp license names after June 10, 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1325419](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1325419)

### Action Required

### June 1, 2026 – End of Sale of Standalone SharePoint and OneDrive Plans

Microsoft is ending the sale of standalone _SharePoint Online Plan 1 and Plan 2_ and _OneDrive for Business Plan 1 and Plan 2_. Starting June 1, 2026, new customers will no longer be able to purchase these standalone plans.

**Solution:** Move to Microsoft 365 suite offerings such as Business Basic, Business Standard, Business Premium, E1, E3, or E5 for continued service availability.

**_Ref:_** [https://learn.microsoft.com/en-us/partner-center/announcements/2026-january#retirement-of-standalone-sharepoint-online-and-onedrive-for-business-plans-plan-1-and-plan-2](https://learn.microsoft.com/en-us/partner-center/announcements/2026-january#retirement-of-standalone-sharepoint-online-and-onedrive-for-business-plans-plan-1-and-plan-2)

### June 5, 2026 – Action Required for Non-Migrated Teams Private Channels

Microsoft is migrating Teams private channels to a new group-based compliance model, increasing channel and membership limits while enabling meetings in private channels. However, some channels could not be migrated because they have no members or contain only guest users without an in-tenant owner.

Admins must identify affected channels and add at least one in-tenant owner by June 5, 2026. Otherwise, affected private channels will be soft deleted and remain recoverable for 30 days before permanent deletion.

**Solution:** Use the updated **_Get-TenantPrivateChannelMigrationStatus_** PowerShell cmdlet to identify affected channels. Add an in-tenant user as a channel owner to complete migration and avoid deletion.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1134737](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1134737)

### June 30, 2026 – Exchange Web Services Will Be Blocked for Kiosk and Frontline Licenses

Microsoft will block Exchange Web Services access for mailboxes that do not include EWS usage rights starting June 30, 2026. After enforcement, requests made without a supported license will return an HTTP 403 error. Impacted licenses include Exchange Online Kiosk, Microsoft 365/Office 365 F1, and F3.

**Solution:** To continue using EWS, assign a license that includes EWS access, such as **Exchange Online Plan 1 or 2** or **Microsoft 365 E3/E5**.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/update-to-ews-access-for-kiosk–frontline-worker-licensed-users/4474299](https://techcommunity.microsoft.com/blog/exchange/update-to-ews-access-for-kiosk--frontline-worker-licensed-users/4474299)

### Live In June

This update was released in May and is now available for you to start using.

### New License Requests Page Added to the Microsoft 365 Admin Center

Microsoft is introducing a dedicated **License Requests** page in the Microsoft 365 admin center to centralize Microsoft 365 Copilot license request management. Admins can view, review, and manage submitted license requests from a single location under **Billing > License requests**. The feature is enabled by default and does not change existing permissions, user request experiences, or custom license request workflows.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1296475](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1296475)

## July 2026

### Retirements

### July 2026 – SharePoint Alerts will be Fully Retired

Microsoft will discontinue support for SharePoint Alerts. Existing alerts can no longer be modified and will eventually stop functioning.

**Solution:** Microsoft recommends migrating SharePoint Alerts to Power Automate or SharePoint Rules. Use the Microsoft 365 Assessment tool to review alerts and plan the move.

**_Ref_**_:_ [https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f](https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f)

### July 2026 – SharePoint One-Time Passcode Retirement for External Sharing

Starting July 2026, Microsoft will retire SharePoint’s One-Time Passcode (OTP) authentication and transition all external sharing to Microsoft Entra B2B. External users who previously accessed content using OTP will receive access denied unless a corresponding guest account exists.

*   All external access shifts to Microsoft Entra B2B, enforcing Conditional Access, Identity Protection, and centralized guest governance.
*   Authentication, invitations, and audit tracking move from SharePoint OTP to Entra B2B and its audit logs.
*   Existing “specific people” links may fail for users without a corresponding guest account.

**Solution:** Create a guest account in Entra B2B or have an internal user re-share content to automatically provision the guest account and restore access.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1243549](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1243549)

### July 2026 - Credential Parameter Retirement in Exchange Online PowerShell

Exchange Online PowerShell is deprecating the _-Credential_ parameter as it relies on the legacy ROPC authentication flow that does not support MFA or Conditional Access. This change applies to both the _Connect-ExchangeOnline_ and _Connect-IppsSession_ cmdlets.

**Solution:** Move to secure authentication methods such as _interactive sign-in, app-only authentication, or managed identity authentication_ when connecting to Exchange Online PowerShell.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/deprecation-of-the--credential-parameter-in-exchange-online-powershell/4494584](https://techcommunity.microsoft.com/blog/exchange/deprecation-of-the--credential-parameter-in-exchange-online-powershell/4494584)

### July 2026 – Retirement of Viva Insights Export via Microsoft Graph Data Connect

Microsoft is retiring the Viva Insights export capability through Microsoft Graph Data Connect (MGDC) to simplify data export workflows and enhance security. Existing customers can continue using their current MGDC-based export pipelines until July 2026, when the capability will be fully retired.

**Solution:** Organizations should transition to supported alternatives, such as the **_Viva Insights Power BI Connector or CSV export_**. Admins should also complete the MGDC offboarding process and remove Viva Insights from the enabled datasets list in Microsoft Graph Data Connect settings.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1180889](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1180889)

### Early-July 2026 - Retirement of Noise Suppression Capability for OneDrive and SharePoint Video

Due to low usage, Microsoft will remove the noise suppression toggle from video playback controls for videos stored in OneDrive and SharePoint.

All other video and audio playback features will remain available without any changes.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1272549](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1272549)

### July 6, 2026 - Retirement of Top Domain Mail Flow Report in Exchange Online

The _Top domain mail flow status report_ in the Exchange Admin Center currently provides insights into inbound and outbound mail flow.

Microsoft will retire this report on July 6, 2026, as part of efforts to modernize reporting and introduce more flexible options. After this date, the report will no longer be available, and admins will need to use alternative methods to monitor mail flow.

**_Ref_**: [https://learn.microsoft.com/en-us/exchange/monitoring/mail-flow-reports/mfr-top-domain-mailflow-status-report](https://learn.microsoft.com/en-us/exchange/monitoring/mail-flow-reports/mfr-top-domain-mailflow-status-report)

### July 14, 2026- InfoPath 2013 Client and InfoPath Forms Services in SharePoint Online will be Retired

InfoPath Client 2013 will reach the end of its extended support period on July 14, 2026, and to keep an aligned experience across Microsoft products, InfoPath Forms Service will be retired from SharePoint Online.

**Solution:** To understand the usage of InfoPath within your organization, you can utilize the [Microsoft 365 Assessment tool](https://aka.ms/assessment/infopath) to scan your tenant and analyze InfoPath usage. If you are currently using InfoPath, you can initiate the migration process to modern alternatives such as Power Apps, Power Automate, or Forms.

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190](https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190)

### New Features

### July 01, 2026 – Microsoft 365 Price Increase

Starting July 1, 2026, Microsoft will implement a global price increase across all Microsoft 365 plans. Prices will increase by 5% to 33%, depending on the SKU. The increase reflects ongoing investments in AI capabilities, security enhancements, and advanced management features.

Alongside the price increase, Microsoft is adding value to select plans:

*   Microsoft 365 Business Premium will receive an additional 50 GB of email storage at no extra cost.
*   Advanced Microsoft Intune capabilities will be included with Microsoft 365 E3 and E5 subscriptions.
*   Microsoft will include Security Copilot in E5 subscriptions at no additional cost.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/blog/2025/12/04/advancing-microsoft-365-new-capabilities-and-pricing-update/](https://www.microsoft.com/en-us/microsoft-365/blog/2025/12/04/advancing-microsoft-365-new-capabilities-and-pricing-update/)

### Early-July 2026 – Centralized App and Agent Evaluation Experience in Microsoft Teams

Microsoft Teams is introducing a centralized evaluation experience in the Teams admin center to simplify app and agent approval decisions. Administrators can define organizational trust requirements once, after which Teams will automatically generate evaluation scores and detailed assessment reports for apps and agents based on compliance and security criteria.

The evaluation score settings will be available under _Teams admin center → Teams apps_, allowing admins to review, sort, and filter apps using trust and compliance insights. This feature is enabled by default and does not change existing app enablement or blocking behavior.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1218713](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1218713)

### Early-July 2026 - Promotions Email Tagging and Filtering in Microsoft Defender for Office 365

Microsoft Defender for Office 365 is improving how promotional emails are handled by tagging them as “promotions” and optionally moving them to a dedicated Promotions folder.

If the “Bulk moves enabled” setting is turned on, tagged emails will automatically move to the Promotions folder. Users can also create inbox rules based on the promotions tag, and the system will continue learning from user behavior to improve accuracy. It will be out in general availability by early July 2026.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1279093](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1279093)

### Early-July 2026 – Microsoft Teams Introduces Simplified Meeting Controls and a Redesigned Share Panel

Teams is refreshing the in-meeting experience to reduce mis-clicks and make meeting controls easier to use. The update introduces simplified, center-aligned controls, a redesigned share panel with live previews and two-step share confirmation, and customizable controls for quicker access to frequently used actions.

The new experience will be enabled by default for Teams users on Windows, Mac, and the web.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1317197](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1317197)

### July 2026 – Microsoft Teams Locks CAPTCHA Policy for Meeting Join

Microsoft Teams will lock the _“Require verification by participants (CAPTCHA)”_ policy starting early May 2026, preventing admins from enabling it. This marks the beginning of CAPTCHA retirement, with a transition to a default-on bot detection capability that requires organizer approval for external bots.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1262588](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1262588)

### July 2026 – New Secure Workflow to Bypass Legal Holds and Retention Policies in Microsoft Purview

Admins will have the ability to permanently delete sensitive Exchange mailbox content, bypassing retention policies and eDiscovery holds. This will be possible through the “Priority Cleanup Administrator” role, which grants authorized users’ permission to initiate Priority Cleanup for Exchange, allowing exceptions to standard retention and legal hold policies.

Since this process is irreversible and overrides existing policies, Microsoft has built-in approvals and special auditing for security.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=392838](https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=392838)

### July 2026 – Rule-Based Management of Microsoft 365 Certified Apps in Teams

To strengthen app governance and security, Microsoft is introducing rule-based controls for managing Microsoft 365 certified third-party apps in the Teams admin center. Administrators can define app availability based on criteria such as publisher names and app permissions, making it easier to allow trusted apps while maintaining control.

The feature will be disabled by default and no changes will be made unless configured by an administrator.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1085133](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1085133)

### July 2026 – Microsoft 365 Admin Center Introduces Agents Usage Report

A new Agents usage report will be available in the Microsoft 365 admin center, helping admins monitor agent adoption and usage across Microsoft 365 Copilot and Copilot Chat. The report provides visibility into active users and agents, helping organizations understand the usage of user-created, organization-built, Microsoft-built, and partner-built agents.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=497999](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=497999)

### Mid-July 2026 - New Security Detection Report in Teams Admin Center

Microsoft will introduce a new report in the Teams admin center called the “[Security Detection Report](https://blog.admindroid.com/security-detection-report-in-teams-admin-center/).” This report enables admins to review detection activities such as impersonation attempts, malicious URL detection, and identification of weaponizable file types.

Admins can also export detailed data from this centralized view for further investigation and analysis.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1311977](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1311977)

### Mid-July 2026 – OCR Support Enhances Microsoft Purview Data Security Investigations

Microsoft Purview Data Security Investigations is adding Optical Character Recognition (OCR) support to automatically extract and analyze text from images, screenshots, and other visual content.

This helps security and compliance teams identify sensitive information that may be embedded in images, improving investigation accuracy and risk detection. The feature is enabled by default and works with existing investigation workflows and Purview policies.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1301831](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1301831)

### Enhancements

### Early July 2026 – Microsoft Teams Introduces Digital Signage for Teams Panels

Microsoft Teams will support displaying digital signage on idle Teams panels, extending existing signage capabilities available on Teams Rooms displays. Admins will be able to configure signage at the tenant, device group, or device level through the Teams Rooms Pro Management portal using supported providers such as Appspace and XOGO.

The feature requires Teams Rooms Pro or Teams Shared Spaces licenses and will have no user impact unless enabled.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1311979](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1311979)

### July 2026 – Granular DLP Controls for Exchange Online Classification and Scan Failures

Microsoft Purview Data Loss Prevention introduces granular protections for Exchange Online, enabling administrators to create policies for specific classification and text extraction failure types. This allows targeted handling of scenarios such as timeouts, throttling, and other scan errors instead of relying on a single policy for all failure conditions.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=561916](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=561916)

### Existing Functionality Changes

### July 2026 - Expanded Archive Mailbox Capacity Beyond 1.5 TB With Consumption-Based Pricing

Previously, auto-expanding archive mailboxes were limited to 1.5 TB, after which they would stop working. This limit has now been removed, allowing archive mailboxes to grow beyond 1.5 TB automatically to support ongoing retention needs.

This feature follows a consumption-based pricing model for storage beyond 1.5 TB, costing $0.25 per GB per month (or $0.0082 per GB per day).

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=560820#Roadmap](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=560820#Roadmap)

### Late-July 2026 – Microsoft Planner Tab Support for Shared and Private Channels

Microsoft is expanding Planner integration within Teams by enabling Planner tabs in both Shared and Private channels. Starting mid-May 2026, users can add new or existing plans directly to these environments, allowing for seamless task management within the channel. The feature is enabled by default.

Users can add Planner via the “+” tab experience, with plans inheriting channel permissions and Microsoft 365 compliance controls. Existing Planner behavior remains unchanged, and all data continues to follow current storage and retention policies.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1262590](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1262590)

### Action Required

### July 1, 2026 – DNS Provisioning Change for Accepted Domains

Microsoft is updating DNS provisioning for new Accepted Domains to support DNSSEC adoption. Starting July 1, 2026, A records for newly added Accepted Domains will be created under **mx.microsoft** subdomains instead of _mail.protection.outlook.com_.

Organizations using automation or workflows that rely on _mail.protection.outlook.com_ for MX record configuration may experience mail flow issues unless updated. Going forward, the _List serviceConfigurationRecords_ Microsoft Graph API will become the authoritative source for retrieving MX record values.

**Solution:** Update domain provisioning or MX record automation to use the **List serviceConfigurationRecords** Graph API instead of relying on _mail.protection.outlook.com_ before July 1, 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1048624](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1048624)

### July 14, 2026 - End of Support for SharePoint Designer 2013

Microsoft will retire SharePoint Designer 2013 in accordance with the Microsoft Fixed Lifecycle Policy to support the transition toward modern workflow automation and customization experiences. After July 14, 2026, Microsoft will no longer provide technical support, security updates, or product fixes, and no extensions or exceptions will be available.

**Solution:** Use SharePoint Migration Tool (SPMT) 4.1 to assess existing workflows and migrate them to Power Automate by July 13, 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230891](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230891)

### July 15, 2026 – Upgrade macOS 13 Devices to Continue Using Teams Desktop

Microsoft Teams will end support for the desktop client on macOS 13 (Ventura). Starting in mid-July 2026, users on macOS 13 will no longer be able to access the Teams desktop app and must either upgrade to a supported macOS version or use Teams on the web.

**Solution:** Organizations should identify devices running macOS 13 and plan operating system upgrades before _July 15, 2026_.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1308857](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1308857)

### July 30, 2026 – Update Get-MailDetailTransportRuleReport and Get-MailTrafficPolicyReport Scripts

Microsoft is changing the behavior of the **_Get-MailDetailTransportRuleReport_** and **_Get-MailTrafficPolicyReport_** cmdlets. Starting July 30, 2026, these cmdlets will return transport rule data only when the _-EventType TransportRuleHits_ or _\-EventType TransportRuleActionHits_ parameter is explicitly specified. Scripts and automation that do not include these parameters may return incomplete or empty results.

**Solution:** Review scripts, scheduled jobs, and automation using these cmdlets. Update queries to explicitly include _\-EventType TransportRuleHits_ or _\-EventType TransportRuleActionHits_ before July 30, 2026.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1323250](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1323250)

### July 31, 2026 – Retirement of the Microsoft 365 Usage Analytics Power BI Template App

Microsoft is retiring the Microsoft 365 Usage Analytics Power BI template app to streamline reporting experiences and align with modern Microsoft 365 reporting solutions. Existing installations will stop receiving data and reports will no longer refresh after August 1, 2026, although previously exported data will remain accessible.

**Solution:** Move to supported reporting solutions, such as Microsoft 365 admin center reports or Microsoft Graph APIs, before August 1, 2026.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1324288](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1324288)

## August 2026 (Attention Needed: 4)

### Aug 1, 2026 – Microsoft Defender Threat Intelligence to Merge with Defender and Sentinel

Microsoft Defender Threat Intelligence will merge with Microsoft Defender and Microsoft Sentinel by August 1, 2026, bringing threat intelligence directly into the SecOps workflow. After the transition, threat insights will be available through the Microsoft Defender portal, with enhanced Threat Analytics that include:

*   Indicators of Compromise (IoCs) integrated into reports
*   MITRE ATT&CK mappings for tactics and techniques
*   Insights into threat actors and targeted industries
*   IoCs linked to cases for Microsoft Sentinel customers

After August 1, 2026, accessing MDTI capabilities will require an active Microsoft Defender or Microsoft Sentinel license.

**Solution:** Plan your transition to Microsoft Defender or Microsoft Sentinel before the deadline and review licensing to ensure uninterrupted access to MDTI capabilities.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1192257](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1192257)

### Early-August 2026 - Microsoft Entra ID Governance Account Discovery

Application accounts are accounts that exist directly within applications and are often created outside of Microsoft Entra ID. These may include local or orphaned accounts that are not centrally managed, making it difficult to track access and enforce governance.

Microsoft Entra ID Governance introduces Account Discovery to help administrators identify these accounts across connected applications. It can detect local and orphaned accounts and match them with Microsoft Entra ID users, improving visibility and access control.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1287372](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1287372)

### Aug 2026 – Exchange Online Message Recall Expands to Cross-Tenant Emails

Exchange Online currently supports message recall only within an organization. Beginning in August 2026, users will also be able to recall emails sent to external organizations that have added their tenant to a recall allow list.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=561330](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=561330)

### Late-August 2026 - Adaptive Scopes for DLP for SharePoint

Currently, admins must manually select and maintain SharePoint sites within DLP policies. To reduce this effort, Microsoft will introduce adaptive scopes for SharePoint DLP policies.

With a Microsoft 365 E5 or E5 Compliance license (add-on), admins can dynamically target SharePoint sites based on specific attributes such as URL, name, or metadata. This feature is not enabled by default and requires admins to configure adaptive scopes within DLP policies. Also, it will be out for general availability by late August 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1234571](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1234571)

## September 2026 (Attention Needed: 7)

### Sep 2026 – Update PowerPoint Client Versions to Access Captions & Subtitles

As part of a backend service upgrade for Captions & Subtitles in PowerPoint, users on older Microsoft 365 PowerPoint builds prior to 16.0.19426.20218 for Windows or 16.103.1207.4 for macOS will lose access to these features.

**Solution:** Update PowerPoint clients to Windows (Win32) 16.0.19426.20218 or macOS 16.103.1207.4 or later.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1231437](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1231437)

### Sep 2026 – Update Office Apps to Keep Read Aloud, Transcription, and Dictation Features

Read Aloud, Transcription, and Dictation features in Microsoft 365 Office apps will stop working on versions earlier than 16.0.18827.20202 because of backend upgrades. This change takes effect after September 2026 for Worldwide tenants and November 2026 for GCC, GCC High, and DoD environments.

**Solution:** Update all Office apps to 16.0.18827.20202 or later before the deadline.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1127222](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1127222)

**Sep 06, 2026 – Microsoft Entra ID SSPR Requires Registered Authentication Methods**

Microsoft Entra ID Self-Service Password Reset (SSPR) currently allows password reset verification using certain directory-stored contact details, even if they were never registered as authentication methods. Starting September 7, 2026, only explicitly registered authentication methods will be accepted for SSPR verification. Users without registered methods will be unable to complete password resets.

**Solution:** Ensure users have at least one registered authentication method that satisfies your SSPR policy via _Microsoft Entra admin center → Authentication methods → User registration details_.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1325414](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1325414)

### Sep 17, 2026 – Retirement of Legacy Education LTI Tools

On September 17, 2026, Microsoft will retire legacy Education LTI tools such as Teams Assignments, OneDrive, OneNote Class Notebook, and Reflect, transitioning to a single Microsoft 365 LTI unified tool that users and admins must adopt.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1160188](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1160188)

### Late-Sep 2026 - Teams Channel Whiteboard Storage Moves to SharePoint

The default storage location for whiteboards created in Teams Channel tabs will be updated. Starting in late Sep 2026, these files will be stored in the channel’s associated SharePoint site instead of the creator’s OneDrive. Enabled by default, this change prevents access issues caused by sharing settings, Information Barriers, and Conditional Access policies.

With this update, Whiteboards inherit SharePoint-based Microsoft Purview controls such as DLP, sensitivity labels, retention, eDiscovery, and audit logging, while also improving centralized compliance monitoring and reporting.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1253753](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1253753)

### Late-Sep 2026 – Unified Management of Teams Apps Across Microsoft 365

Microsoft is finalizing the rollout of Unified App Management for Teams, Outlook, and the Microsoft 365 app. This update simplifies app management by consolidating the separate admin experiences into a single, centralized management interface. The unified experience will be fully available to all organizations by the end of June 2026.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC796790](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC796790)

### Sep 30, 2026 - Deprecation of Custom Controls in Microsoft Entra Conditional Access

Conditional Access Custom Controls will be retired on September 30, 2026. This legacy preview feature is being replaced by External MFA, a more robust and integrated framework for third-party MFA providers.

**Solution:** Admins should migrate to External MFA before the retirement date to avoid disruption.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/external-mfa-in-microsoft-entra-id-is-now-generally-available/4488926](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/external-mfa-in-microsoft-entra-id-is-now-generally-available/4488926)

## Q4 2026 (Attention Needed: 9)

### Oct 2026 – Just in Time Protection on SharePoint in DLP

A new Just-in-Time protection capability for SharePoint will be added to Microsoft Purview Data Loss Prevention in preview.

With this feature, organizations can automatically apply DLP restrictions to unclassified files when they are accessed or shared externally. Instead of restricting files in advance, JIT protection enforces security measures only when there is a risk of data leaving the organization.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457)

### Oct 01, 2026- Retirement of Exchange Web Services in Exchange Online

October 1, 2026, Microsoft will start blocking EWS requests from non-Microsoft apps to Exchange Online. The changes in Exchange Online do not affect Outlook for Windows or Mac, Teams, or any other Microsoft product.

**Solution**: Migrate your applications to Microsoft Graph to access Exchange Online data and gain access to the latest features and functionality.

**_Ref_**_:_ [https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-exchange-web-services-in-exchange-online/ba-p/3924440](https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-exchange-web-services-in-exchange-online/ba-p/3924440)

### Oct 01, 2026- Sign-in Risk Policy and User Risk Policy Retirement from Entra ID Protection

User risk policy or Sign-in risk policy UX in Entra ID Protection (formerly Identity Protection) will be retired on October 1, 2026.

**Solution:** Migrate Sign-in risk and User risk policies to Conditional Access.

**_Ref_**_:_ [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/what-s-new-in-microsoft-entra/ba-p/3796395](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/what-s-new-in-microsoft-entra/ba-p/3796395)

### Oct 13, 2026- Retirement of Microsoft Publisher

In October 2026, Microsoft will discontinue Publisher in Microsoft 365, with on-premises suite support ending. While support lasts, they’re exploring modern alternatives across Word, PowerPoint, and Designer for common Publisher tasks, with updates forthcoming.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC716267](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC716267)

### Oct 13, 2026 - End of Support for Office LTSC 2021 And Additional Apps

Microsoft will retire Office LTSC 2021, Visio LTSC 2021, Microsoft Project LTSC 2021, and a few other products on October 13, 2026.

To continue receiving support and updates, Microsoft recommends upgrading to a Microsoft 365 or Office 365 plan that includes Microsoft 365 Apps. If a fully offline solution is required, upgrading to Office LTSC 2024 is recommended, which will be supported until October 2029.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1278920](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1278920)

### Oct 28, 2026 – Retirement of Microsoft Entra PIM Iteration 2 (Beta) APIs

Microsoft will retire Microsoft Entra Privileged Identity Management Iteration 2 (beta) APIs on October 28, 2026. After this date, applications and scripts using these APIs will fail because the endpoints will no longer return data.

**Solution:** Migrate to the Iteration 3 (GA) APIs, which are fully supported and more reliable. Stop new development on Iteration 2 APIs and begin migration planning.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1181281](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1181281)

### Dec 2026 – Custom Retention for Message Trace Logs in Exchange Online

Starting in December 2026, organizations will be able to select how long Message Trace data is retained by choosing from a set of predefined retention periods. This enhancement gives admins greater flexibility to align log retention with their compliance, audit, and operational requirements.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=542929](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=542929)

### End of Dec 2026 – Disable SMTP Auth for Basic Authentication

SMTP AUTH Basic Authentication will be disabled by default for existing tenants by Dec end, though admins can enable it if required.

**Solution:**

*   Migrate applications and devices to OAuth-based authentication.
*   Use alternatives such as High-Volume Email for Microsoft 365, Azure Communication Services for Email, or an on-premises Exchange.

**_Ref_**: [https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835](https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835)

### Dec 31, 2026 – End of Support for Dynamics 365 Guides and Remote Assist

Dynamics 365 Guides and Dynamics 365 Remote Assist will retire on December 31, 2026. After this date, the products will no longer receive security updates, bug fixes, or technical support.

**Solution:** Customers should plan their transition early by identifying dependent users and scenarios. Explore alternative mixed reality solutions available in the [Microsoft Marketplace](https://marketplace.microsoft.com/marketplace/apps?category=mixed-reality), and consider Microsoft Teams Mobile with [spatial annotation](https://learn.microsoft.com/en-us/dynamics365/mixed-reality/remote-assist/teams-mobile-annotate) for certain remote collaboration use cases.

**_Ref:_** [https://learn.microsoft.com/en-us/lifecycle/announcements/dynamics-365-guides-remote-assist-end-of-support](https://learn.microsoft.com/en-us/lifecycle/announcements/dynamics-365-guides-remote-assist-end-of-support)

## 2027 (Attention Needed: 6)

### Jan 2027 – Retirement of Basic Authentication for Client Submission in Exchange Online

Microsoft will disable Basic Authentication with Client Submission (SMTP AUTH) by default starting January 2027. OAuth will be the supported authentication method.

**Proactive Steps:**

*   Move applications and devices to OAuth-based authentication for SMTP AUTH.
*   If Basic Authentication is still needed, consider alternatives such as High-Volume Email for Microsoft 365, Azure Communication Services for Email, or an on-premises Exchange Server in a hybrid setup.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835](https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835)

### Jan 31, 2027 – Retirement of MDE and XDR Advanced Hunting APIs

To unify the interface across Microsoft Defender products, Microsoft will retire the Microsoft Defender for Endpoint (MDE) Advanced Hunting API and Microsoft Defender XDR Advanced Hunting API.

**Solution:** Move to Microsoft Graph Security API for broader data coverage, improved consistency, and better scalability for automation and security workflows.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1220762](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1220762)

### March 01, 2027 – Automatic Migration to New Outlook for Windows

Microsoft 365 Enterprise users will automatically switch to the new Outlook for Windows, gaining access to modern features like Copilot, theming, and time-saving options such as Pinning and Snoozing emails. A toggle will be available for users to revert to the classic Outlook. Admins can prevent this automatic migration via cloud policy.

The opt-out phase originally scheduled for April 2026 has been postponed to March 1, 2027, providing organizations with additional time to prepare.

**_Ref_**_:_ [https://admin.microsoft.com/#/MessageCenter/:/messages/MC949965](https://admin.microsoft.com/#/MessageCenter/:/messages/MC949965)

### March 2027 – Retirement of Security Questions in Microsoft Entra Self-Service Password Reset

Microsoft will retire security questions as an authentication method for Self-Service Password Reset (SSPR) in Microsoft Entra ID starting March 2027, due to security vulnerabilities and low verification reliability.

After this retirement, users will no longer be able to verify their identity using security questions during password reset. Organizations that continue relying on this method may experience failed password reset attempts, user lockouts, and increased help desk support requests.

**Solution:** Ensure users are registered with [supported authentication methods](https://learn.microsoft.com/en-us/entra/identity/authentication/tutorial-enable-sspr#select-authentication-methods-and-registration-options) before March 2027 to avoid Self-Service Password Reset failures.

**_Ref:_** [https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-security-questions](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-security-questions)

### Oct 2027 – Microsoft Teams Removes Passcode Option from Create Meeting API

In October 2027, Microsoft will remove the option to create meetings without passcodes. This means all online meetings created through the Microsoft Graph API will automatically require a passcode, and the _isPasscodeRequired_ property on the _joinMeetingIdSettings_ resource will be removed. This change ensures that every meeting is consistently secured with a passcode, simplifying meeting creation, and improving security.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC985483](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC985483)

### Oct 14, 2027 – Retirement of Duplicative Properties in Passkey (FIDO2) Authentication Methods Policy

To align with the updated passkey policy API schema that supports group-based passkey profiles, Microsoft will retire _isAttestationEnforced_ and _keyRestrictions_ from the fido2AuthenticationMethodConfiguration API. During the transition, these properties will sync with attestationEnforcement and keyRestrictions in the Default passkey profile.

**Solution:** Admins should update configurations, automations, and integrations to use the new schema.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1188230](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1188230)

In conclusion, navigating the ever-evolving landscape of Microsoft 365 requires staying informed about the changes 🔍. By proactively adapting to these changes, you can optimize your Microsoft 365 experience, maximize productivity, and effectively plan for the future. 💪

We are committed to keeping this blog updated with the latest information, so stay tuned for upcoming updates.

[https://blog.admindroid.com/microsoft-365-end-of-support-milestones/](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/)