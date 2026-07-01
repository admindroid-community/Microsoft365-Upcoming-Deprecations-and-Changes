# **What's** **Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements**

Join us in this blog as we explore the dynamic world of Microsoft 365. 🌟 We'll shed light on the features and products that are undergoing transformations or bidding farewell. Whether you're a system administrator 🧑‍💻 managing the Microsoft 365 environment or an avid user 🙋‍♂️ staying ahead of the curve, this blog will provide invaluable insights and actionable recommendations.

🚀Discover the **key changes, deprecations,** and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we've got you covered! Make informed decisions and ensure a smooth transition.⚡️

## **Microsoft 365 Upcoming Changes and Deprecations List:**

Here is a list of changes categorized by month and year.

* July 2026 (Retirements: 6, New Features: 12, Enhancements: 5, Existing Functionality Changes: 7, Action Needed: 3, Live: 1)
* August 2026 (Retirements: 2, New Features: 9, Enhancements: 3, Existing Functionality Changes: 1, Action Needed: 2)
* September 2026 (Attention Needed: 4)
* October 2026 (Attention Needed: 6)
* Q4 2026 (Attention Needed: 3)
* 2027 (Attention Needed: 6)

## **July 2026**

Retirements: 6 | New Features: 12 | Enhancements: 5 | Existing Functionality Changes: 6 | Action Needed: 3 | Live Now: 1

### **Retirements**

### **July 2026 - SharePoint Alerts will be Fully Retired**

Microsoft will discontinue support for creating new SharePoint Alerts for newly onboarded tenants. Existing alerts cannot be modified and will eventually stop functioning when Microsoft retires the feature.

**Solution:** Microsoft recommends [migrating SharePoint Alerts to Power Automate](https://blog.admindroid.com/sharepoint-alerts-retirement-and-alternatives-in-microsoft-365/#SetRuntimeNotificationUsingPowerAutomate) or SharePoint Rules. Use the Microsoft 365 Assessment tool to review alerts and plan the move.Use the Microsoft 365 Assessment tool to review alerts and plan the move.

***Ref***: [https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f](https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f)

### **July 2026 - Retirement of SharePoint One-Time Passcode for External Sharing**

Microsoft will retire SharePoint One-Time Passcode authentication for external sharing beginning in July 2026. As part of this change, external sharing authentication in OneDrive and SharePoint will transition to Microsoft Entra B2B. External users who previously accessed content using OTP will receive access denied unless a corresponding guest account exists.

* All external access shifts to Microsoft Entra B2B, enforcing Conditional Access, Identity Protection, and centralized guest governance.
* Authentication, invitations, and audit tracking move from SharePoint OTP to Entra B2B and its audit logs.
* Existing "specific people" links may fail for users without a corresponding guest account.

**Solution:** Create a guest account in Entra B2B or have an internal user re-share content to automatically provision the guest account and restore access.

***Ref:*** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1243549](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1243549)

### **July 2026 - Credential Parameter Retirement in Exchange Online PowerShell**

Exchange Online PowerShell is deprecating the *-Credential* parameter as it relies on the legacy ROPC authentication flow that does not support MFA or Conditional Access. This change applies to both the *Connect-ExchangeOnline* and *Connect-IppsSession* cmdlets.

**Solution:** Move to secure authentication methods such as *interactive sign-in,* *app-only authentication*, or *managed identity authentication* when connecting to Exchange Online PowerShell.

***Ref:*** [https://techcommunity.microsoft.com/blog/exchange/deprecation-of-the-credential-parameter-in-exchange-online-powershell/4494584](https://techcommunity.microsoft.com/blog/exchange/deprecation-of-the–credential-parameter-in-exchange-online-powershell/4494584)

### **Early-July 2026 - Retirement of "Add Note" Option for Support Tickets in Microsoft 365 Admin Center**

Microsoft is retiring the "Add note" option for support tickets in the Need Help experience of the Microsoft 365 admin center. This change aims to streamline communication with Microsoft Support by directing customers to more reliable and consistent support channels. The retirement does not affect support ticket creation or resolution workflows.

**Solution:** Users should communicate with Microsoft Support through supported channels, such as email with the assigned support engineer or scheduled phone calls.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1338811](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1338811)

### **Mid-July 2026: Microsoft Retires In-App OS Update Notifications in Defender for Endpoint on iOS**

To remove duplicate and potentially conflicting OS update notifications, Microsoft will retire OS update notifications and recommendations from the Microsoft Defender app on iOS. This change is intended to provide a more unified and secure experience across Microsoft's security and device management services.

**Solution:** Organizations should use Microsoft Intune and existing MDM capabilities to manage OS update compliance and enforcement, rather than relying on the Microsoft Defender app.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1381122](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1381122)

### **Late-July 2026 - Microsoft Teams Removes CAPTCHA Policy for Meeting Join**

Microsoft Teams will remove the "Require verification by participants (CAPTCHA)" policy from PowerShell starting late July 2026, preventing admins from enabling it. This marks the second stage of CAPTCHA retirement.

**Solution:** Microsoft will transition to a default-on bot detection capability that requires organizer approval for external bots.

***Ref:*** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1262588](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1262588)

### **New Features**

### **July 2026 - Change Meeting Organizer via PowerShell Cmdlet in Exchange Online**

Exchange Online is introducing a new PowerShell cmdlet for GCC High and DoD tenants to change meeting organizers. This update helps reduce disruption to existing meeting series and scheduled meetings. The new meeting organizer must accept the transfer request before the transfer is completed.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1227623](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1227623)

### **July 2026 - New Outlook for Windows Becomes Available for GCC High and DoD Environments**

Microsoft is introducing the new Outlook for Windows experience for all GCC High and DoD environments, providing users with access to modern Outlook features. The experience will be available as an opt-in feature and is off by default.

Existing organizational settings remain unchanged, and users are not automatically switched to the new Outlook. Users can switch between the new and classic Outlook experiences at any time using the built-in toggle.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1338816](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1338816)

### **July 2026 - Pay-as-You-Go Consumption-Based Billing for Extra OneDrive Storage**

Microsoft is introducing a pay-as-you-go billing model for OneDrive storage based on consumption. When storage usage exceeds the allocated quota, additional capacity is automatically made available and billed based on actual consumption.

The model enables organizations to scale storage flexibly and pay only for the additional capacity consumed, reducing the need to purchase fixed storage add-ons.

***Ref:*** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=562352](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=562352)

### **July 01, 2026 - Microsoft 365 Price Increase**

Starting July 1, 2026, Microsoft will implement a global price increase across all Microsoft 365 plans. Prices will increase by 5% to 33%, depending on the SKU. The increase reflects ongoing investments in AI capabilities, security enhancements, and advanced management features.

Alongside the price increase, Microsoft is adding value to select plans:

* Microsoft 365 Business Premium will receive an additional 50 GB of email storage at no extra cost.
* Advanced Microsoft Intune capabilities will be included with Microsoft 365 E3 and E5 subscriptions.
* Microsoft will include Security Copilot in E5 subscriptions at no additional cost.

***Ref:*** [https://www.microsoft.com/en-us/microsoft-365/blog/2025/12/04/advancing-microsoft-365-new-capabilities-and-pricing-update/](https://www.microsoft.com/en-us/microsoft-365/blog/2025/12/04/advancing-microsoft-365-new-capabilities-and-pricing-update/)

### **Early-July 2026 - File Quarantine Action for SharePoint and OneDrive in DLP**

Microsoft will introduce "File Quarantine" in Microsoft Purview Data Loss Prevention (DLP) for SharePoint and OneDrive, generally available in early July 2026. When configured, any file that violates a DLP policy will be automatically moved to an admin-defined quarantine location.

A tombstone file will be placed in the original location to inform users about the quarantine action, along with an admin-defined message. Admins can monitor these activities through audit logs, DLP alerts, and activity explorer.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1288527](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1288527)

### **Early-July 2026 - Entra ID Adds New Service Plans for Agent Conditional Access and Identity Protection**

Microsoft Entra ID is introducing two [new service plans](https://blog.admindroid.com/service-plans-for-agent-conditional-access-and-identity-protection/): Entra Conditional Access for Agents and Entra ID Protection for Agents. These plans will be included with Microsoft E7 and Microsoft 365 Agent licenses to support Conditional Access and Identity Protection for AI agents. Organizations that want to use these agent security capabilities will need to transition to the updated licensing model.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1395007](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1395007)

### **Early-July 2026 - Full Workload Backup for SharePoint, OneDrive, and Exchange Enters Public Preview**

A [Full Workload Backup](https://blog.admindroid.com/microsoft-365-backup-for-onedrive-sharepoint-and-exchange/#👉June-2026-Update:-Microsoft-Introduces-Full-Workload-Backup-for-SharePoint-Online,-Exchange-Online,-and-OneDrive) capability is being introduced for Microsoft 365 Backup, enabling organizations to create a single backup policy for an entire workload, including SharePoint, OneDrive, and Exchange Online. This policy will automatically protect all eligible artifacts within the selected workload.

This simplifies backup management and ensures coverage keeps pace with growing Microsoft 365 environments without requiring frequent policy updates.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1387526](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1387526)

### **Early-July 2026 - File-Level Archiving in SharePoint Online**

[File-level archiving in SharePoint](https://blog.admindroid.com/file-level-archiving-in-microsoft-365-archive/) is currently available in general availability alongside site-level archiving. This feature allows organizations to archive individual files within active SharePoint sites and move them to a lower-cost storage tier without impacting the site.

The capability is enabled by default for all SharePoint sites in tenants where Microsoft 365 Archive is activated. Billing is based on the existing pay-as-you-go model.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1381114](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1381114)

### **Early-July 2026: Block External Domain or User Access for SharePoint and OneDrive for Business Files**

Microsoft is introducing new Data Loss Prevention (DLP) capabilities that enable organizations to block access to SharePoint and OneDrive for Business files for specific external users or entire external domains based on SMTP email addresses. External users included in the block list will receive an "Access Denied" message and will be unable to open or download the protected files.

Administrators can also configure an allow list to grant access to trusted external domains or specific external users. This enhancement provides organizations with greater control over external access and helps reduce the risk of unintended data exposure.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1338823](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1338823)

### **July 6, 2026 - Windows Hello for Business and macOS Platform SSO Registration Evaluates Conditional Access Policies**

Currently, Windows Hello for Business and macOS Platform SSO registrations enforce MFA but do not evaluate Conditional Access policies. As a result, requirements such as authentication strength, trusted locations, and other Conditional Access grant controls are not enforced during registration.

Starting July 6, 2026, Windows Hello for Business and macOS Platform SSO registrations will also evaluate CA policies that target the Register security information user action.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1326253](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1326253)

### **Mid-July 2026 - New Security Detection Report in Teams Admin Center**

Microsoft will introduce a new report in the Teams admin center called the "Security Detection Report." This report enables admins to review detection activities such as impersonation attempts, malicious URL detection, and identification of weaponizable file types.

Admins can also export detailed data from this centralized view for further investigation and analysis.

***Ref:*** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1311977](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1311977)

### **Mid-July 2026: Hard Delete SharePoint and OneDrive Files in Microsoft Purview**

Microsoft Purview Data Lifecycle Management is introducing a new hard delete option in Priority Cleanup policies. The update adds a "Delete data permanently" action for supported SharePoint and OneDrive file types, allowing organizations to permanently remove files from storage. Deleted files will no longer be discoverable through Microsoft 365 services. The capability also applies to files governed by retention policies and retention labels.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1261587](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1261587)

### **Enhancements**

### **Early-July 2026 - Promotions Email Tagging and Filtering in Microsoft Defender for Office 365**

Microsoft Defender for Office 365 is improving how promotional emails are handled by tagging them as "promotions" and optionally moving them to a dedicated Promotions folder.

If the "Bulk moves enabled" setting is turned on, tagged emails will automatically move to the Promotions folder. Users can also create inbox rules based on the promotions tag, and the system will continue learning from user behavior to improve accuracy. It will be out in general availability by early July 2026.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1279093](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1279093)

### **Early-July 2026: Microsoft Purview Endpoint DLP Restricts File Extension Configuration with a Pre-Curated List**

Microsoft Purview Endpoint Data Loss Prevention (DLP) is updating the File Extension condition to use a pre-curated list of supported scannable file types. As part of this change, administrators will no longer be able to manually enter custom file extensions when configuring DLP policies. Existing policies will continue to function and be enforced without any changes. This update aligns Endpoint DLP configuration with supported file type protection capabilities, helping admins apply policies more consistently.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1384415](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1384415)

### **Early-July 2026: Retention for Unlicensed OneDrive Accounts**

A new staged retention lifecycle is coming for unlicensed OneDrive accounts starting in early July 2026. Enabled by default, the policy applies to OneDrive accounts that remain unlicensed for an extended period, giving admins time to take action before access deletion occur.

Under the new retention lifecycle, unlicensed OneDrive accounts will transition through three stages:

* After 60 days without a license, the OneDrive account becomes read-only.
* After 93 days, the OneDrive account enters an archived state. Users can no longer access its content, but it remains available for eDiscovery and Legal Hold.
* After 12 cumulative months without a license, the OneDrive account is permanently deleted.

If a valid OneDrive license is assigned before permanent deletion, the account will automatically return to its normal state.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1381110](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1381110)

### **Mid-July 2026 - Microsoft Purview DLP Policy Sync Time Reduced from 2 Hours to 30 Minutes**

Microsoft has reduced the synchronization interval for Microsoft Purview Data Loss Prevention (DLP) policies from 2 hours to 30 minutes. This change enables faster policy synchronization and enforcement across Microsoft 365 services. This helps organizations apply DLP protections more quickly.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1317834](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1317834)

### **July 27, 2026 - Enterprise Content Delivery Network (eCDN) Analytics Data Retention Reduced to 180 Days**

Enterprise Content Delivery Network (eCDN) analytics data will now be retained for 180 days instead of 360 days. Analytics data older than 180 days will be automatically deleted and will no longer be accessible. This change aligns data retention with operational insights and reporting requirements.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1403404](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1403404)

### **Existing Functionality Changes**

### **July 2026 - Microsoft Migrates On-Premises Sync from Entra Connect Sync to Entra Cloud Sync**

Microsoft is transitioning identity synchronization from Entra Connect Sync to the native Microsoft Entra Cloud Sync in a phased rollout. This change provides a simpler, cloud-based synchronization experience with reduced on-premises dependency and easier management.

The move also strengthens identity security by aligning synchronization with Microsoft's Zero Trust strategy and modern cloud-first identity architecture.

***Ref:*** [https://learn.microsoft.com/en-us/entra/fundamentals/whats-new?WT.mc\_id=Portal-Microsoft\_AAD\_IAM](https://learn.microsoft.com/en-us/entra/fundamentals/whats-new?WT.mc_id=Portal-Microsoft_AAD_IAM)

### **July 2026 - Microsoft Expands Archive Mailbox Capacity Beyond 1.5 TB**

Currently, auto-expanding archive mailboxes are limited to 1.5 TB, after which they stop working. This limit has now been removed, allowing archive mailboxes to grow beyond 1.5 TB automatically to support ongoing retention needs.

This feature follows a consumption-based pricing model for storage beyond 1.5 TB, costing $0.25 per GB per month (or $0.0082 per GB per day).

***Ref:*** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=\&searchterms=560820#Roadmap](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=560820#Roadmap)

### **Mid-July 2026 - Decoupling Policy Tips \& Email Notifications for SharePoint and OneDrive DLP**

Currently, enabling email notifications in DLP policies for SharePoint and OneDrive also enforces policy tips, and vice versa. With this update, Microsoft introduces the ability to configure policy tips and email notifications independently, providing greater flexibility in how alerts are managed.

This feature will be available in general availability by late July 2026.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC791114](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC791114)

### **Mid-July 2026 - OneDrive Centralizes Shortcuts in a Dedicated Folder**

OneDrive will introduce a dedicated "Shortcuts" folder that serves as a centralized location for all folders and files added as shortcuts. Currently, these items appear under "My Files" along with other files, making content scattered and harder to manage.

To improve organization, the new **Shortcuts** folder will provide a dedicated space for all shortcut-added files and folders. If a Shortcuts folder already exists, it will be reused.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1385585](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1385585)

### **Mid-July 2026 - Teams Android Device Management Moves to Pro Management Portal**

Teams Rooms on Android, Teams phones, Teams panels, and Teams displays will be managed through the Pro Management Portal (PMP) instead of the Teams admin center, unifying device management in one place.

As part of this transition, device inventory and health data will automatically appear in PMP. Admins performing management actions in Teams admin center will be redirected to the new portal experience. The rollout is expected to reach general availability by mid-July 2026.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1227622](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1227622)

### **Late July, 2026 - Action Required for Non-Migrated Teams Private Channels**

Microsoft is migrating Teams private channels to a new group-based compliance model, increasing channel and membership limits while enabling meetings in private channels. However, some channels could not be migrated because they have no members or contain only guest users without an in-tenant owner.

Admins must identify these channels using the *Get-TenantPrivateChannelMigrationStatus* PowerShell cmdlet and assign at least one in-tenant owner by June 5, 2026. Otherwise, affected private channels will be soft deleted and remain recoverable for 30 days before permanent deletion.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1134737](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1134737)

### **July 30, 2026 - Transport Rule Reporting Behaviour Changes for Exchange Online PowerShell Cmdlets**

Microsoft is changing the behavior of the *Get-MailDetailTransportRuleReport* and *Get-MailTrafficPolicyReport* cmdlets. Starting July 30, 2026, these cmdlets will return transport rule data only when the *-EventType TransportRuleHits* or *-EventType TransportRuleActionHits* parameter is explicitly specified. Scripts and automation that do not include these parameters may return incomplete or empty results.

Organizations should review scripts, scheduled jobs, and automation that use these cmdlets, and update queries to include the required -EventType parameter before July 30, 2026.

***Ref:*** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1323250](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1323250)

### **Action Required**

### **July 1, 2026 - DNS Provisioning Change for Accepted Domains**

Microsoft is updating DNS provisioning for new Accepted Domains to support DNSSEC adoption. Starting July 1, 2026, a record for newly added Accepted Domains will be created under mx.microsoft subdomains instead of mail.protection.outlook.com.

Organizations using automation or workflows that rely on mail.protection.outlook.com for MX record configuration may experience mail flow issues unless updated. Going forward, the List serviceConfigurationRecords Microsoft Graph API will become the authoritative source for retrieving MX record values.

**Solution:** Update domain provisioning or MX record automation to use the List serviceConfigurationRecords Graph API instead of relying on mail.protection.outlook.com before July 1, 2026.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1048624](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1048624)

### **July 14, 2026 - End of Support for SharePoint Designer 2013**

Microsoft will retire SharePoint Designer 2013 in accordance with the Microsoft Fixed Lifecycle Policy. This supports the transition toward modern workflow automation and customization experiences. After July 14, 2026, Microsoft will no longer provide technical support, security updates, or product fixes, and no extensions or exceptions will be available.

**Solution:** Use SharePoint Migration Tool (SPMT) 4.1 to assess existing workflows and migrate them to Power Automate by July 13, 2026.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230891](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230891)

### **July 15, 2026 - Upgrade macOS 13 Devices to Continue Using Teams Desktop**

Microsoft Teams will end support for the desktop client on macOS 13 (Ventura). Starting in mid-July 2026, users on macOS 13 will no longer be able to access the Teams desktop app and must either upgrade to a supported macOS version or use Teams on the web.

**Solution:** Organizations should identify devices running macOS 13 and plan operating system upgrades before July 15, 2026.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1308857](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1308857)

### **Live In July**

Released in June, this feature is now ready for you to use.

### **App Instance Lock Enabled by Default for New Entra Applications**

Microsoft Entra will enable App Instance Lock by default for newly created applications. Sensitive service principal properties, such as password credentials, will be protected by default and cannot be modified from outside the application's home tenant.

Organizations should review automation and provisioning workflows that update protected properties. If post-creation updates to protected properties are necessary, app owners and administrators can manually disable App Instance Lock for specific applications.

Without disabling this feature, any attempt to modify the protected properties of a locked application will fail, resulting in a 400 Bad Request error.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1300584](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1300584)

## **August 2026**

### **Retirements**

### **August 1, 2026 - Retirement of the Microsoft 365 Usage Analytics Power BI Template App**

Microsoft is retiring the Microsoft 365 Usage Analytics Power BI template app to streamline reporting experiences and align with modern Microsoft 365 reporting solutions. Existing installations will stop receiving data after August 1, 2026. Reports will no longer refresh, but previously exported data will remain accessible.

**Solution:** Move to supported reporting solutions, such as Microsoft 365 admin center reports or Microsoft Graph APIs, before August 1, 2026.

***Ref:*** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1324288](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1324288)

### **Mid-August - Outlook for Windows Report Retirement in the Exchange Admin Center**

Microsoft will retire the Outlook for Windows reports from the Exchange admin center. To streamline and improve the reporting experience, this report will be removed automatically, with no option to opt out.

**Solution:** Admins can continue accessing Outlook for Windows usage insights through the Microsoft 365 admin center under Reports → Usage → Microsoft 365 Apps → Usage → Outlook for Windows.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230889](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230889)

### **New Features**

### **August 2026 - Unified Management of Teams Apps Across Microsoft 365**

Microsoft is finalizing the rollout of Unified App Management for Teams, Outlook, and the Microsoft 365 app. This update simplifies app management by consolidating the separate admin experiences into a single, centralized management interface. The unified experience will be fully available to all organizations by August 2026.

***Ref:*** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC796790](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC796790)

### **Early-August 2026 - Microsoft Entra ID Governance Account Discovery**

Application accounts are accounts that exist directly within applications and are often created outside of Microsoft Entra ID. These may include local or orphaned accounts that are not centrally managed, making it difficult to track access and enforce governance.

Microsoft Entra ID Governance introduces Account Discovery to help administrators identify these accounts across connected applications. It can detect local and orphaned accounts and match them with Microsoft Entra ID users, improving visibility and access control.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1287372](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1287372)

### **Early-August 2026 - Archive Unused OneDrive and SharePoint Files in Microsoft Purview**

An Archive option will be introduced in Microsoft Purview Data Lifecycle Management to move inactive OneDrive and SharePoint files to Microsoft 365 Archive. This helps reduce storage costs and improve Microsoft 365 Copilot responses.

The feature is not enabled by default and requires administrator configuration.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1325441](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1325441)

### **Early-August 2026 - Automatic Recording and Transcription for Microsoft Teams Call Queues**

A new feature is being introduced to enable automatic recording and/or transcription of Microsoft Teams Queue calls when answered by agents. This can be configured via the Teams admin center or PowerShell.

Call recordings and transcripts are stored in SharePoint and made accessible through the Queues app call history. The capability supports shared customer callback scenarios and includes default system announcements, with support for custom audio files and text-to-speech features.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1401299](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1401299)

### **Early-August 2026 - Microsoft Teams Brings More Granular Controls for Channel Notifications**

Microsoft Teams is introducing more granular channel notification options, including presets such as All new messages, Mentions and replies, and Mute. Within each option, users can further customize notifications for thread follows, tag mentions, channel mentions, and Teams mentions.

The feature is enabled by default for all users, providing greater control over how channel activity is surfaced.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1388719](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1388719)

### **Mid-August 2026 - AI-Powered Meeting Recap Without Recording or Transcript in Microsoft Teams**

Microsoft Teams will introduce an AI-powered meeting recap feature that generates summaries without saving meeting transcripts or recordings. The feature will be available as an opt-in capability, and organizations with a Microsoft 365 Copilot (premium) license will be able to enable or disable it before or during meetings.

The AI-generated meeting summary will be saved as a document in the user's OneDrive by default for 120 days, with options to customize the retention period. Deletion of post-meeting AI summaries is also supported.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1275312](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1275312)

### **Mid-August 2026 - Granular DLP Controls for Exchange Online Classification and Scan Failures**

Microsoft Purview Data Loss Prevention introduces granular protections for Exchange Online, enabling administrators to create policies for specific classification and text extraction failure types. This allows targeted handling of scenarios such as timeouts, throttling, and other scan errors instead of relying on a single policy for all failure conditions.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1387682](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1387682)

### **Late-August 2026 - Adaptive Scopes for DLP for SharePoint**

Currently, admins must manually select and maintain SharePoint sites within DLP policies. To reduce this effort, Microsoft will introduce adaptive scopes for SharePoint DLP policies.

With a Microsoft 365 E5 or E5 Compliance license (add-on), admins can dynamically target SharePoint sites based on specific attributes such as URL, name, or metadata. This feature is not enabled by default and requires admins to configure adaptive scopes within DLP policies. Also, it will be out for general availability by late August 2026.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1234571](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1234571)

### **Late-August 2026 - Microsoft Teams Extends Support for Teams Rooms Devices to Attend Webinars on Android**

Microsoft is extending support for Teams Rooms devices with Teams Rooms Pro licenses to attend webinars and structured meetings as attendees on Android. The update enables Teams Rooms devices to use chat, reactions, raise hand, captions, participant roster, and visibility controls during meetings.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1317839](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1317839)

### **Enhancements**

### **Early-August 2026 - Microsoft 365 Packaging Update Adds New Security, Intune, and Storage Features**

Ahead of the Microsoft 365 pricing taking effect on July 1, 2026, Microsoft is rolling out several new security, device management, and storage capabilities to eligible Microsoft 365, Office 365, and EMS suites, including:

* Microsoft Defender for Office 365 Plan 1 and URL time-of-click protection.
* Intune capabilities such as Remote Help, Advanced Analytics, Endpoint Privilege Management, Enterprise Application Management, and Cloud PKI.
* An additional 50 GB of Exchange Online mailbox storage.

Defender protections will be enabled by default, while Intune capabilities require admin configuration before use.

***Ref:*** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1304290](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1304290)

### **Existing Functionality Changes**

### **August 2026 - Exchange Online Message Recall Expands to Cross-Tenant Emails**

Exchange Online currently supports message recall only within an organization. Beginning in August 2026, users will also be able to recall emails sent to external organizations that have added their tenant to a recall allow list.

***Ref:*** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=561330](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=561330)

### **Action Required**

### **August 1, 2026 - Microsoft Defender Threat Intelligence to Merge with Defender and Sentinel**

Microsoft Defender Threat Intelligence will merge with Microsoft Defender and Microsoft Sentinel by August 1, 2026, bringing threat intelligence directly into the SecOps workflow. After the transition, threat insights will be available through the Microsoft Defender portal, with enhanced Threat Analytics that include:

* Indicators of Compromise (IoCs) integrated into reports
* MITRE ATT\&CK mappings for tactics and techniques
* Insights into threat actors and targeted industries
* IoCs linked to cases for Microsoft Sentinel customers

After August 1, 2026, accessing MDTI capabilities will require an active Microsoft Defender or Microsoft Sentinel license.

**Solution:** Plan your transition to Microsoft Defender or Microsoft Sentinel before the deadline and review licensing to ensure uninterrupted access to MDTI capabilities.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1192257](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1192257)

## **September 2026 (Attention Needed: 4)**

### **September 2026 - Mail Merge (Advanced) in Outlook on the Web \& New Outlook for Windows**

Outlook on the web and the new Outlook for Windows will receive enhanced Mail Merge (Advanced) capabilities. With this update, users will be able to insert dynamic fields into email templates, enabling more personalized and customized communication at scale.

This enhancement simplifies the process of tailoring messages, making it more efficient to send targeted and professional emails.

***Ref:*** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=\&searchterms=423047](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047)

### **September 2026 - New Secure Workflow to Bypass Legal Holds and Retention Policies in Microsoft Purview**

Admins will have the ability to permanently delete sensitive Exchange mailbox content, bypassing retention policies and eDiscovery holds. This will be possible through the "Priority Cleanup Administrator" role, which grants authorized users' permission to initiate Priority Cleanup for Exchange, allowing exceptions to standard retention and legal hold policies.

Since this process is irreversible and overrides existing policies, Microsoft has built-in approvals and special auditing for security.

***Ref:*** [https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=\&searchterms=392838](https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=392838)

### **September 2026: Pay-As-You-Go Billing for Extra Microsoft SharePoint Storage**

Currently, organizations must purchase the Office 365 Extra File Storage add-on for additional SharePoint storage, which is billed in per-GB increments and can result in paying for unused capacity.

With this update, Microsoft introduces a [pay-as-you-go billing for extra SharePoint storage](https://blog.admindroid.com/pay-as-you-go-billing-for-extra-sharepoint-storage/) based on actual consumption. Storage is measured via a consumption-based meter, allowing organizations to pay only for what they use and improving overall cost efficiency.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1330893](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1330893)

### **Early-September 2026 - Microsoft Teams Adds Recap Content Deletion for GCC High Environments**

Microsoft Teams will allow organizers in GCC High environments to manage meeting-generated recap content using a new "Delete recap content" option available from the *More* menu on the meeting recap page. The feature is expected to be generally available starting September 2026.

This capability enables deletion of selected recap content; however, shared content, custom summaries, and audio recaps cannot be deleted using this option. Deleted content cannot be restored.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1289725](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1289725)

### **Early-September 2026 - eSignature for Microsoft 365 Recipient Groups**

When a specific signer is unavailable, workflows may be interrupted, causing delays in the signing process. To improve reliability, eSignature for Microsoft 365 recipient groups is being introduced, allowing a single recipient slot to be assigned to up to 10 people. The first available signer can complete the signing requirement. The feature is enabled by default and doesn't require any admin configuration.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1290821](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1290821)

### **September 7, 2026 - Microsoft Entra ID SSPR Requires Registered Authentication Methods**

Microsoft Entra ID Self-Service Password Reset (SSPR) currently allows password reset verification using certain directory-stored contact details, even if they were never registered as authentication methods. Starting September 7, 2026, only explicitly registered authentication methods will be accepted for SSPR verification. Users without registered methods will be unable to complete password resets.

**Solution:** Ensure users have at least one registered authentication method that satisfies your SSPR policy via Microsoft Entra admin center → Authentication methods → User registration details.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1325414](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1325414)

### **September 17, 2026 - Retirement of Legacy Education LTI Tools**

On September 17, 2026, Microsoft will retire legacy Education LTI tools such as Teams Assignments, OneDrive, OneNote Class Notebook, and Reflect, transitioning to a single Microsoft 365 LTI unified tool that users and admins must adopt.

***Ref:*** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1160188](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1160188)

### **Late-September 2026 - Update PowerPoint Client Versions to Access Captions \& Subtitles**

Microsoft is upgrading the backend service that supports Captions \& Subtitles in PowerPoint. As a result, users running Microsoft 365 PowerPoint app versions earlier than 16.0.19426.20218 (Windows) or 16.103.1207.4 (macOS) will lose access to caption and subtitle features after the update.

**Solution:** Update PowerPoint clients to Windows (Win32) 16.0.19426.20218 or macOS 16.103.1207.4 or later.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1231437](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1231437)

### **Late-September 2026 - Update Office Apps to Keep Read Aloud, Transcription, and Dictation Features**

Read Aloud, Transcription, and Dictation features in Microsoft 365 Office apps will stop working on versions earlier than 16.0.18827.20202 because of backend upgrades. This change takes effect after September 2026 for Worldwide tenants and November 2026 for GCC, GCC High, and DoD environments.

**Solution:** Update all Office apps to 16.0.18827.20202 or later before the deadline.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1127222](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1127222)

### **Late-September 2026 - Teams Channel Whiteboard Storage Moves to SharePoint**

Microsoft is updating the default storage location for whiteboards created in Teams Channel tabs. Starting in late Sep 2026, these files will be stored in the channel's associated SharePoint site instead of the creator's OneDrive. Enabled by default, this change prevents access issues caused by sharing settings, Information Barriers, and Conditional Access policies.

With this update, Whiteboards inherit SharePoint-based Microsoft Purview controls such as DLP, sensitivity labels, retention, eDiscovery, and audit logging, while also improving centralized compliance monitoring and reporting.

***Ref:*** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1253753](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1253753)

### **September 30, 2026 - Deprecation of Custom Controls in Microsoft Entra Conditional Access**

Microsoft is officially retiring Conditional Access Custom Controls on September 30, 2026. This legacy preview feature is being replaced by External MFA, a more robust and integrated framework for third-party MFA providers.

**Solution:** Admins should migrate to External MFA before the retirement date to avoid disruption.

***Ref:*** [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/external-mfa-in-microsoft-entra-id-is-now-generally-available/4488926#:\~:text=Migration%20from%20Custom%20Controls](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/external-mfa-in-microsoft-entra-id-is-now-generally-available/4488926#:~:text=Migration%20from%20Custom%20Controls)

## **October 2026 (Attention Needed: 6)**

### **October 1, 2026 - Exchange Web Services Will Be Blocked for Kiosk and Frontline Licenses**

Microsoft will block Exchange Web Services access for mailboxes that do not include EWS usage rights starting June 30, 2026. After enforcement, requests made without a supported license will return an HTTP 403 error. Impacted licenses include Exchange Online Kiosk, Microsoft 365/Office 365 F1, and F3.

**Solution:** To continue using EWS, assign a license that includes EWS access, such as Exchange Online Plan 1 or 2 or Microsoft 365 E3/E5.

***Ref:*** [https://techcommunity.microsoft.com/blog/exchange/update-to-ews-access-for-kiosk-frontline-worker-licensed-users/4474299](https://techcommunity.microsoft.com/blog/exchange/update-to-ews-access-for-kiosk–frontline-worker-licensed-users/4474299)

### **October 01, 2026- Retirement of Exchange Web Services in Exchange Online**

October 1, 2026, Microsoft will start blocking EWS requests from non-Microsoft apps to Exchange Online. The changes in Exchange Online do not affect Outlook for Windows or Mac, Teams, or any other Microsoft product.

**Solution:** Migrate your applications to Microsoft Graph to access Exchange Online data and gain access to the latest features and functionality.

***Ref:*** [https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-exchange-web-services-in-exchange-online/ba-p/3924440](https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-exchange-web-services-in-exchange-online/ba-p/3924440)

### **October 01, 2026- Sign-in Risk Policy and User Risk Policy Retirement from Entra ID Protection**

User risk policy or Sign-in risk policy UX in Entra ID Protection (formerly Identity Protection) will be retired on October 1, 2026.

**Solution:** Migrate Sign-in risk and User risk policies to Conditional Access.

***Ref:*** [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/what-s-new-in-microsoft-entra/ba-p/3796395](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/what-s-new-in-microsoft-entra/ba-p/3796395)

### **October 2026 - Microsoft Purview Adds Inline DLP Controls for Prompts in Microsoft Foundry Apps and Agents**

Microsoft Purview Data Loss Prevention (DLP) will support inline DLP policies for built-in apps and agents in Microsoft Foundry. Organizations will be able to enable Microsoft Purview within Foundry to apply these policies. The integration helps prevent sensitive data from being shared through prompts and AI interactions, strengthening data protection controls.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1304291](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1304291)

### **October 2026 - Just in Time Protection on SharePoint in DLP**

Microsoft is introducing Just-in-Time protection for SharePoint in Microsoft Purview Data Loss Prevention in preview.

With this feature, organizations can automatically apply DLP restrictions to unclassified files when they are accessed or shared externally. Instead of restricting files in advance, JIT protection enforces security measures only when there is a risk of data leaving the organization.

***Ref:*** [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457)

### **Early-October 2026 - Credential scanning in Microsoft Purview Data Security Posture Agent**

A new Credential Scanning capability is introduced in Microsoft Purview Data Security Posture Agent to identify exposed credentials and related security risks across configured data sources. The AI-powered scanning engine uses large language models (LLMs) to detect sensitive credentials, including Microsoft Entra ID credentials, private keys, and API keys.

Scan results are presented through a dashboard with risk scores, AI-generated insights, and confidence ratings, enabling administrators to prioritize and remediate credential exposure more effectively.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1259828](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1259828)

### **October 13, 2026- Retirement of Microsoft Publisher**

In October 2026, Microsoft will discontinue Publisher in Microsoft 365, with on-premises suite support ending. While support lasts, they're exploring modern alternatives across Word, PowerPoint, and Designer for common Publisher tasks, with updates forthcoming.

***Ref:*** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC716267](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC716267)

### **October 13, 2026 - End of Support for Office LTSC 2021 And Additional Apps**

Microsoft will retire Office LTSC 2021, Visio LTSC 2021, Microsoft Project LTSC 2021, and a few other products on October 13, 2026.

To continue receiving support and updates, Microsoft recommends upgrading to a Microsoft 365 or Office 365 plan that includes Microsoft 365 Apps. If a fully offline solution is required, upgrading to Office LTSC 2024 is recommended, which will be supported until October 2029.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1278920](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1278920)

### **Mid-October 2026 - Content Security Policy for Entra ID Sign-in Experience**

Microsoft Entra ID is enforcing a stricter Content Security Policy (CSP) for sign-ins starting mid-October 2026. Only trusted Microsoft scripts will be allowed, blocking injected code to reduce XSS risks. This applies to browser-based sign-ins on login.microsoftonline.com and does not affect Entra External ID tenants.

**Solution:** If you use tools or extensions that inject code, switch to non-injecting alternatives and test sign-in flows before CSP enforcement begins.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1191924](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1191924)

### **October 28, 2026 - Retirement of Microsoft Entra PIM Iteration 2 (Beta) APIs**

Microsoft will retire Microsoft Entra Privileged Identity Management Iteration 2 (beta) APIs on October 28, 2026. After this date, applications and scripts using these APIs will fail because the endpoints will no longer return data.

**Solution:** Migrate to the Iteration 3 (GA) APIs, which are fully supported and more reliable. Stop new development on Iteration 2 APIs and begin migration planning.

Ref: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1181281](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1181281)

### **October 31, 2026 - Retirement of Microsoft Defender for Endpoint on Amazon Linux 2 (ARM64)**

From October 31, 2026, Microsoft will retire support for Microsoft Defender for Endpoint on Amazon Linux (ARM64). Linux versions beyond 101.25122.0004 will no longer install on AL2 environments, and affected devices will miss security enhancements and feature updates.

**Solution:** Organizations should migrate to a supported Linux distribution for Microsoft Defender for Endpoint before October 31, 2026, to ensure continued security updates and feature support.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1392568](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1392568)

## **Q4 2026 (Attention Needed: 3)**

### **December 2026 - Custom Retention for Message Trace Logs in Exchange Online**

Starting in December 2026, organizations will be able to select how long Message Trace data is retained by choosing from a set of predefined retention periods. This enhancement gives admins greater flexibility to align log retention with their compliance, audit, and operational requirements.

Ref: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=542929](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=542929)

### **End of December 2026 - Disable SMTP Auth for Basic Authentication**

SMTP AUTH Basic Authentication will be disabled by default for existing tenants by Dec end, though admins can enable it if required.

**Solution:**

* Migrate applications and devices to OAuth-based authentication.
* Use alternatives such as High-Volume Email for Microsoft 365, Azure Communication Services for Email, or an on-premises Exchange.

***Ref:*** [https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835](https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835)

### **December 31, 2026 - End of Support for Dynamics 365 Guides and Remote Assist**

Dynamics 365 Guides and Dynamics 365 Remote Assist will retire on December 31, 2026. After this date, the products will no longer receive security updates, bug fixes, or technical support.

**Solution:** Customers should plan their transition early by identifying dependent users and scenarios. Explore alternative mixed reality solutions available in the Microsoft Marketplace, and consider Microsoft Teams Mobile with spatial annotation for certain remote collaboration use cases.

***Ref:*** [https://learn.microsoft.com/en-us/lifecycle/announcements/dynamics-365-guides-remote-assist-end-of-support](https://learn.microsoft.com/en-us/lifecycle/announcements/dynamics-365-guides-remote-assist-end-of-support)

## **2027 (Attention Needed: 6)**

### **January 2027 - Retirement of Basic Authentication for Client Submission in Exchange Online**

Microsoft will disable Basic Authentication with Client Submission (SMTP AUTH) by default starting January 2027. OAuth will be the supported authentication method.

**Proactive Steps:**

* Move applications and devices to OAuth-based authentication for SMTP AUTH.
* If Basic Authentication is still needed, consider alternatives such as High-Volume Email for Microsoft 365, Azure Communication Services for Email, or an on-premises Exchange Server in a hybrid setup.

***Ref:*** [https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835](https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835)

### **January 2027 - End of Life of Standalone SharePoint Online and OneDrive for Business Plans**

Microsoft is ending the lifecycle of standalone SharePoint Online Plan 1 and Plan 2 and OneDrive for Business Plan 1 and Plan 2. In June 2026, new customers are no longer able to purchase these standalone plans. From June 2027, renewals will no longer be permitted, although existing subscriptions will continue until their expiration.

**Solution:** Move to Microsoft 365 suite offerings such as Business Basic, Business Standard, Business Premium, E1, E3, or E5 for continued service availability.

***Ref:*** [https://learn.microsoft.com/en-us/partner-center/announcements/2026-january#retirement-of-standalone-sharepoint-online-and-onedrive-for-business-plans-plan-1-and-plan-2](https://learn.microsoft.com/en-us/partner-center/announcements/2026-january#retirement-of-standalone-sharepoint-online-and-onedrive-for-business-plans-plan-1-and-plan-2)

### **Late-January 2027 - Microsoft Extends DLP to Restrict Processing of External Emails in Copilot**

Microsoft is extending Data Loss Prevention (DLP) support for Microsoft 365 Copilot and Copilot Chat by introducing a new capability to exclude emails from external or untrusted domains. These emails will not be used for summarization, responses, or grounding data in Copilot experiences.

The feature is available as an opt-in option. Once enabled, emails from trusted internal sources will continue to be used for Copilot responses, while content from external untrusted domains will be restricted.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1301714](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1301714)

### **January 31, 2027 - Retirement of MDE and XDR Advanced Hunting APIs**

To unify the interface across Microsoft Defender products, Microsoft will retire the Microsoft Defender for Endpoint (MDE) Advanced Hunting API and Microsoft Defender XDR Advanced Hunting API.

**Solution:** Move to Microsoft Graph Security API for broader data coverage, improved consistency, and better scalability for automation and security workflows.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1220762](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1220762)

### **January 31,2027 - Full Retirement of Restricted SharePoint Search**

Microsoft will fully retire Restricted SharePoint Search (RSS), which limits how SharePoint content appears in Microsoft Search and Microsoft 365 Copilot, by January 31, 2027. Existing Restricted SharePoint Search configurations will not be automatically migrated to Restricted Content Discovery (RCD).

**Solution:** Organizations should migrate from Restricted SharePoint Search to Restricted Content Discovery (RCD) or adopt another appropriate control for managing content discoverability before the retirement date.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1395311](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC13953114)

### **March 01, 2027 - Automatic Migration to New Outlook for Windows**

Microsoft 365 Enterprise users will automatically switch to the new Outlook for Windows, gaining access to modern features like Copilot, theming, and time-saving options such as Pinning and Snoozing emails. A toggle will be available for users to revert to the classic Outlook. Admins can prevent this automatic migration via cloud policy.

The opt-out phase originally scheduled for April 2026 has been postponed to March 1, 2027, providing organizations with additional time to prepare.

***Ref:*** [https://admin.microsoft.com/#/MessageCenter/:/messages/MC949965](https://admin.microsoft.com/#/MessageCenter/:/messages/MC949965)

### **March 2027 - Retirement of Security Questions in Microsoft Entra Self-Service Password Reset**

Microsoft will retire security questions as an authentication method for Self-Service Password Reset (SSPR) in Microsoft Entra ID starting March 2027, due to security vulnerabilities and low verification reliability.

After this retirement, users will no longer be able to verify their identity using security questions during password reset. Organizations that continue relying on this method may experience failed password reset attempts, user lockouts, and increased help desk support requests.

**Solution:** Ensure users are registered with supported authentication methods before March 2027 to avoid Self-Service Password Reset failures.

***Ref:*** [https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-security-questions](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-security-questions)

### **March 31, 2027 - Microsoft Sentinel Retirement in Azure Portal**

Microsoft is migrating Microsoft Sentinel from the Azure portal to the Microsoft Defender portal. After March 31, 2027, Microsoft Sentinel will no longer be supported in the Azure portal, and must be accessed through the Microsoft Defender portal.

The Microsoft Defender portal will become the primary management experience for Microsoft Sentinel and can be used even without Microsoft Defender XDR or a Microsoft 365 E5 license.

***Ref:*** [https://learn.microsoft.com/en-us/azure/sentinel/overview?tabs=defender-portal#microsoft-sentinel-in-the-azure-portal-retirement-timeline](https://learn.microsoft.com/en-us/azure/sentinel/overview?tabs=defender-portal#microsoft-sentinel-in-the-azure-portal-retirement-timeline)

### **October 2027 - Removal of Passcode Option from Create Meeting API**

In October 2027, Microsoft will remove the option to create meetings without passcodes. This means all online meetings created through the Microsoft Graph API will automatically require a passcode, and the isPasscodeRequired property on the joinMeetingIdSettings resource will be removed. This change ensures that every meeting is consistently secured with a passcode, simplifying meeting creation, and improving security.

***Ref:*** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC985483](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC985483)

### **October 14, 2027 - Retirement of Duplicative Properties in Passkey (FIDO2) Authentication Methods Policy**

To align with the updated passkey policy API schema that supports group-based passkey profiles, Microsoft will retire isAttestationEnforced and keyRestrictions from the fido2AuthenticationMethodConfiguration API. During the transition, these properties will sync with attestationEnforcement and keyRestrictions in the Default passkey profile.

**Solution:** Admins should update configurations, automations, and integrations to use the new schema.

***Ref:*** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1188230](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1188230)

In conclusion, navigating the ever-evolving landscape of Microsoft 365 requires staying informed about the changes 🔍. By proactively adapting to these changes, you can optimize your Microsoft 365 experience, maximize productivity, and effectively plan for the future. 💪

We are committed to keeping this blog updated with the latest information, so stay tuned for upcoming updates.

[https://blog.admindroid.com/microsoft-365-end-of-support-milestones/](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/)

