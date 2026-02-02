# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.

Discover the **key changes, deprecations**, and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

Here is a list of changes categorized by month and year.

*   Feb 2026 (Retirements: 4, New Features: 13, Enhancements: 5, Existing Functionality Changes: 6, Action Needed: 2)
*   Mar 2026 Retirements: 5, New Features: 12, Enhancements: 3, Existing Functionality Changes: 3, Action Needed: 3)
*   Q2 2026 (Attention Needed: 19)
*   Q3 2026 (Attention Needed: 6)
*   Q4 2026 (Attention Needed: 9)
*   2027 (Attention Needed: 4)

## Feb 2026

Retirements: 4 | New Features: 13 | Enhancements: 5 | Existing Functionality Changes : 6 | Action Needed: 2

### Retirements

### Mid-Feb 2026 - Retirement of Microsoft Planner Features

Microsoft is completing a major update to Microsoft Planner, with the new experience becoming fully available to all users by mid-February 2026. This update introduces new capabilities such as task chats and custom templates. Once the rollout is complete, several existing Planner features will be retired and will no longer be accessible.

**Features being retired:**

*   Legacy task comments (replaced by task chat)
*   Whiteboard tab for premium plans
*   Planner component in Loop pages
*   Planner integration with Viva Goals
*   iCalendar feed for Planner tasks

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1193421](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1193421)

### Feb 16, 2026 – Retirement of Endpoint DLP Sensitive Data Alerting in Microsoft Defender

Microsoft retires the endpoint-sensitive data alerting in the Microsoft Defender portal and moves this functionality entirely to Microsoft Purview DLP. From February 16, 2026, new Defender alert policies can no longer be used to monitor endpoint sensitive data activities.

**Solution:** Re-create required alerting using Microsoft Purview DLP policies by February 15, 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1217649](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1217649)

### Feb 28, 2026 – Retirement of Custom Greetings in Voice Call Authentication

Microsoft will retire the custom greeting feature for voice call MFA by February 28, 2026. After this date, voice call authentication will use Microsoft’s default voice recordings.

**Solution:** Prepare users for the transition to Microsoft’s default voice greetings.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1219798](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1219798)

### Feb 27, 2026 - Retirement of Designer Bot and Banners in Microsoft Teams

Microsoft will retire the Designer bot and Designer banners in Microsoft Teams by February 27, 2026. After this change, users will no longer be able to use the Designer bot in chats or create channel announcement banners with Designer.

**Solution:** Organizations should transition image generation workflows to Copilot in Microsoft Teams going forward.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197104](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197104)

### New Features

### Early-Feb 2026 – New Microsoft Graph APIs for Copilot Agent and App Management

Starting early February 2026, Microsoft will introduce two new Microsoft Graph APIs to manage Copilot agents and apps:

1.  GET graph.microsoft.com/copilot/admin/catalog/packages  
    Returns a full inventory of all Copilot agents and apps available in the tenant, including Microsoft-built, third-party (external), shared, and custom packages.  
    
2.  GET graph.microsoft.com/copilot/admin/catalog/packages/{id}  
    Returns detailed information of a specific Copilot agent or app, including its manifest, configuration, and related metadata.

These APIs enable automated reporting and integration for admins managing Copilot agents and apps across Microsoft 365, with no additional license requirements.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1173195](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1173195)

### Early-Feb 2026 – New Teams External Collaboration Administrator Role

Microsoft is introducing a new built-in RBAC role in the Teams admin center called **Teams External Collaboration Administrator**. Admins assigned to this role can manage external access policies to allow/block external domains and external access settings for federated domains.

This role allows delegated admins to manage external collaboration settings via PowerShell without requiring full Teams administrator permissions, making it well suited for scoped delegation scenarios.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1215071](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1215071)

### Feb 29, 2026 - Content Security Policy in SharePoint Online

Microsoft introduced Content Security Policy (CSP) in SharePoint as a browser-level security standard that controls which scripts, styles, images, and other resources a site is allowed to load. If a resource isn’t explicitly approved, the browser blocks it. This helps protect SharePoint sites from threats like cross-site scripting (XSS), clickjacking, and other code injection attacks. This CSP will be in report-only mode starting Feb 29, 2026.

**_Ref_**: [https://techcommunity.microsoft.com/blog/spblog/sharepoint-online-content-security-policy-csp-enforcement-dates-and-guidance/4472662](https://techcommunity.microsoft.com/blog/spblog/sharepoint-online-content-security-policy-csp-enforcement-dates-and-guidance/4472662)

### Feb 2026 – Chat With Anyone in Teams Using an Email Address

Teams will soon allow users to chat with external contacts using their email addresses, even if those contacts do not have a Teams account. External users will receive an invitation to join as guests. This experience, which will be in General availability follows your organization’s B2B Guest policy and will be enabled by default.

Admins can disable chat with anyone using an email address by setting UseB2BInvitesToAddExternalUsers as false in _Set-CsTeamsMessagingPolicy_ cmdlet.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1182004](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1182004)

### Feb 2026 – Item-Level Investigation and Remediation in Purview Data Risk Assessments

Microsoft Purview Data Risk Assessments is expanding its capabilities to include item-level investigations for SharePoint content.

With this update, admins can drill down into individual items to view key details such as applied sensitivity labels and existing sharing links, making it easier to detect and assess overshared content. From the same experience, admins can take direct remediation actions including,

*   Resolving findings
*   Notifying users
*   Applying sensitivity labels
*   Removing sharing links

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=523202](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=523202)

### Feb 5, 2026 – New Built-In Alert Tuning Rules in Microsoft Defender XDR

Beginning February 5, 2026, Microsoft Defender XDR will activate built-in alert tuning rules that automatically process selected low-severity and informational alerts from Microsoft Defender for Office 365.

This update introduces 12 predefined rules that leverage Automated Investigation and Response (AIR) to triage alerts in the background. Alerts that require analyst attention are automatically reopened and returned to the queue. In multi-tenant environments, settings can be centrally managed and distributed using the Multi-Tenant Management (MTO) portal.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1222979](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1222979)

### Feb 9, 2026 – Paid Extended Service Term for Microsoft 365 Subscriptions

Microsoft is introducing a Paid Extended Service Term (EST) for direct Microsoft 365 subscriptions under the Microsoft Customer Agreement, effective February 9, 2026.

EST replaces the automatic grace period and allows customers to extend services on a monthly, paid basis with a 3% prorated premium, ensuring uninterrupted access while renewal decisions are finalized.

When a subscription reaches the end of its term, customers can:

*   Renew on time to continue without disruption
*   Extend the service using the paid EST
*   Cancel the subscription, with data retained for 90 days before deletion

This applies to Microsoft purchases or renewals made directly on or after February 9, 2026.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1216259](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1216259)

### Mid-Feb 2026 – Block External Teams Users via Microsoft Defender

Microsoft is extending Teams external user management into Microsoft Defender, allowing security teams to block external users directly from the Tenant Allow/Block List.

Admins can block up to 4,000 domains and 200 email addresses, with full audit logging and no impact on existing Teams configurations. To enable this capability, the following settings must be turned on by navigating to Teams admin center > ‘External collaboration’ section > External access.

*   Block specific users from communicating with people in my organization
*   Allow my security team to manage blocked domains and blocked users

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1200058](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1200058)

### Mid-Feb 2026 – Streamlined Admin Controls for External Collaboration in Teams Admin Center

Microsoft is simplifying external collaboration settings across chats, calls, meetings, Teams, and shared channels. This update reaches general availability in mid-February 2026 and introduces a new interface with three predefined collaboration modes:

*   **Open:** Allows chats, calls, and meetings with all external domains and Teams personal accounts via federation or external access.
*   **Controlled:** Matches the current default for enterprise and EDU tenants and blocks shared channel collaboration.
*   **Custom:** Allows complete customization of external collaboration settings across all Teams surfaces.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1183006](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1183006)

### Mid-Feb 2026 – Tenant-Level Process Report in Microsoft Purview eDiscovery

Microsoft Purview eDiscovery (Premium) will introduce a new tenant-level process report. Admins and users with eDiscovery Manager roles can use this report to centrally monitor and manage all eDiscovery processes. This enhancement provides faster operational oversight, clear end-to-end visibility, and improved tracking of eDiscovery activities across the tenant. Also, this feature will be enabled by default.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1225187](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1225187)

### Late-Feb 2026 – Pre-Built Insider Risk Templates for Data Theft Detection

Microsoft Purview Insider Risk Management will introduce new pre-built templates to help detect potential data theft involving non-Microsoft 365 data sources.

These templates help identify risky activities across platforms such as Microsoft Fabric, Box, Dropbox, Azure, and AWS, particularly for:

*   Users leaving the organization
*   Users whose accounts have been deleted in Microsoft Entra ID

This feature is not enabled by default.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1221449](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1221449)

### Late-Feb 2026 – Soft Deletion and Restoration of Cloud Security Groups

Microsoft is introducing soft deletion support for cloud security groups. Deleted groups can be restored for up to 30 days, along with their settings, membership, and properties. Audit logs will track deletion, restoration, and hard deletion events.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1183299](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1183299)

### End of Feb 2026 – SharePoint Branding Governance Using PowerShell

Microsoft is enabling centralized SharePoint site branding management using PowerShell. Tenant admins can apply enterprise themes, enable or disable custom branding for specific sites, audit branding changes, and apply branding during site creation.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1186372](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1186372)

### Enhancements

### Mid-Feb 2026 Microsoft Purview Admin Roles to Sync with New Microsoft Entra Roles

Microsoft Purview will map certain high-privileged Purview admin roles to new roles in Microsoft Entra such as _Purview Workload Content Reader, Purview Workload Content Writer, and Purview Workload Content Administrator_.

Role assignments will sync automatically, and admins will receive the appropriate Entra role based on their Purview permissions. These roles should not be assigned directly in Entra, as Purview manages and overwrites them. Admins may also see new Purview-specific Entra roles in audit logs.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1199765](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1199765)

### Mid-Feb 2026 – Expanded Eligibility to Create Microsoft Loop Workspaces

Currently, only users with licenses such as Microsoft 365 E3/E5/A3/A5, Business Standard, Business Premium, or Microsoft 365 Copilot can create Loop workspaces.

Microsoft is expanding this capability so that other users (for example, Office 365 E1/E3/E5 and Microsoft 365 F1/F3) can create Loop workspaces if they have OneDrive or SharePoint storage. Admins who want to prevent workspace creation can configure a cloud policy with the setting:  
“Create Loop workspaces in Loop” = Disabled.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1217996](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1217996)

### Mid-Feb 2026 – Enable Users to Report Suspicious Teams Messages with Defender Plan 1

Currently, the ability to report suspicious Teams messages was limited to users of Microsoft Defender for Office 365 Plan 2. Microsoft is now expanding this capability to customers with Microsoft Defender for Office 365 Plan 1.

Also, users can report Teams messages as:

*   Security risks (phishing, malware, or malicious content)
*   Not a security risk (false positives)

This enhancement helps security teams detect, investigate, and respond to threats across Teams chats, channels, and meetings while strengthening overall Defender protection.

**_Ref_**: [https://admin.microsoft.com/#/MessageCenter/:/messages/MC1219788](https://admin.microsoft.com/#/MessageCenter/:/messages/MC1219788)

### Late-Feb 2026 - Apps Now Supported in Teams Private Channels

Following the introduction of app support for shared channels, Microsoft is extending the same capability to private channels. Apps such as bots, tabs, and message extensions can now be added to private channels, expanding beyond the earlier limited set of supported tabs.

Apps must be configured at the channel level, as team-level app settings do not apply to shared or private channels. This capability will reach general availability by late February, will be enabled by default.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197145](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197145)

### End of Feb 2026 – Jailbreak and Root Detection in Microsoft Authenticator App

Microsoft will enhance the Microsoft Authenticator app with jailbreak and root detection capabilities for Entra credentials on both iOS and Android platforms. Once this feature is active, Entra credentials on jailbroken or rooted devices will stop functioning. And any existing ones will be automatically wiped for security reasons.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1179154](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1179154)

### Existing Functionality Changes

### Feb 2026 – Microsoft Entra Replaces “Revoke MFA Sessions” with “Revoke Sessions”

Microsoft Entra will remove “Revoke multifactor authentication sessions”, which applied only to per-user MFA, and replace it with “Revoke sessions” in February 2026. The new Revoke sessions action will invalidate all active user sessions, including MFA, regardless of whether MFA is enforced through Conditional Access or per-user policies.

**_Ref:_** [https://learn.microsoft.com/en-us/entra/fundamentals/whats-new#plan-for-change---update-to-revoke-multifactor-authentication-sessions](https://learn.microsoft.com/en-us/entra/fundamentals/whats-new#plan-for-change---update-to-revoke-multifactor-authentication-sessions)

### Feb 2026 – Shortened Microsoft Teams Meeting URLs

Microsoft is simplifying Teams meeting URLs to improve sharing. The new format includes only the meeting ID and a hashed passcode, removing tenant and organizer details.

**New format:**  
https://teams.microsoft.com/meet/<meeting\_id>?p=<HashedPasscode>

This change will roll out to GCC High and DoD environments by February 2026.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC772556](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC772556)

### Feb 2026 – Updated Output Format for Database Properties in Exchange Online Cmdlets

Microsoft is updating the string format of certain database-related properties returned by Exchange Online PowerShell cmdlets. This change reduces unnecessary data retrieval and improves service consistency.

Example (Get-Mailbox output):

*   Before:  
    Database : APCP153DG038-db080
*   After:  
    Database : APCP153.PROD.OUTLOOK.COM/7ad9dea1-26b7-4088-ad73-708c219faff6

This change applies only to Exchange Online. On-premises Exchange environments are not affected.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1108848](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1108848)

### Feb 2026 – Exchange Online Moderation Approvals via Actionable Messages

The Exchange Online Moderation feature allows moderators to approve or reject messages before they’re sent. Currently, this can only be done in Outlook Desktop or Outlook on the web. With the new update using Actionable Messages, moderators can now approve or reject moderated messages from any Microsoft email client, including Outlook for Windows, Mac, iOS, and Android.  
  
**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=492743](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=492743)

### Feb 16, 2026 – Direct Export Expiry Change in Microsoft Purview eDiscovery

When performing a direct export from an eDiscovery case, Microsoft packages the selected data into a secure, temporary container for download. Starting February 16, 2026, these export containers will expire 14 days from the date of creation, and the exported data will be automatically deleted. This change improves both storage efficiency and security.

This update applies only to exports created after February 16, 2026. Exports created before this date and exports from Review Sets are not affected.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1217141](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1217141)

### Feb 16, 2026 – Changes to Microsoft Purview eDiscovery Content Search Cases

Review sets store and analyze collected data such as emails, documents, and Teams messages, while case-level data sources define shared locations used across searches.

Starting February 16, 2026, modern eDiscovery Content Search cases will no longer support review sets and case-level data sources. These capabilities will remain available in dedicated non-Content Search eDiscovery cases, which should be used when structured reviews and centralized data scoping are required.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1216266](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1216266)

### Action Required

### Feb 2026 – Microsoft 365 Admin Center Multifactor Authentication Enforcement

Microsoft began a gradual rollout of MFA enforcement for Microsoft 365 admin center sign-ins in February 2025\. From February 2026 onward, MFA enforcement is active, and users will no longer be able to sign in to Microsoft 365 admin center without completing MFA.

**Solution:**  
Admins should enable MFA now to avoid access issues and ensure all users have valid MFA methods configured.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1215070](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1215070)

### Feb 28, 2026 - Exchange Online to Block ActiveSync Versions below 16.1

Exchange Online will block devices using Exchange ActiveSync (EAS) versions below 16.1 starting March 1, 2026, to improve security and reliability. Devices running older EAS versions will no longer connect, while Outlook Mobile is not affected.

**Solution:** Use the _Get-MobileDevice_ PowerShell command to identify devices running unsupported EAS versions and prompt users to upgrade before enforcement.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197103](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197103)

## March 2026

### Retirements

### Early-Mar 2026 - Featured Links Retirement on SharePoint Online Start Page

From March 2026, Microsoft will retire the Featured Links capability in SharePoint Online. Admins will no longer be able to create, edit, update, or access Featured Links. As part of this change, existing Featured Links will be removed from the SharePoint Online start page and the mobile app.

**Solution:** Highlight important sites and content using alternatives such as global navigation links or Viva Connections Resources.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197131](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197131)

### Mar 20, 2026 – Microsoft Defender for Android Requires Android 11 or Later

Microsoft Defender for Android will end support for devices running Android 10. Starting January 5, 2026, Android 11.0 or later will be required to receive updates, security patches, and new features.

**Action Required:** Advise users to upgrade their devices to Android 11.0 or later.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1222977](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1222977)

### Late Mar 2026 – Defender for Android Ending Support for Enrolled Personal Profiles

Microsoft Defender for Android will stop protecting personal profiles on enrolled devices and will focus exclusively on work profiles.

This change improves corporate security while preserving user privacy and requires no action from admins or users. Work profiles and unenrolled devices are not affected.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1221927](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1221927)

### Mar 30, 2026 - Retirement of External Access Token for Actionable Messages

External access tokens for actionable messages will be retired on March 31, 2026, and organizations must transition to Microsoft Entra authentication to ensure continued functionality. After this date, any actionable message relying on external tokens will fail. This change strengthens security and aligns with modern identity standards.

**Solution:** Organizations using actionable messages should review their current implementations and update all integrations to Microsoft Entra authentication before the deadline to avoid disruptions.

**_Ref_**: [https://learn.microsoft.com/en-us/outlook/actionable-messages/](https://learn.microsoft.com/en-us/outlook/actionable-messages/)

### New Features

### Mar 2026 – New External Domain Anomalies Report in Teams Admin Center

Microsoft Teams will roll out a new External Domain Anomalies report in March 2026. The report helps admins detect unusual or risky external interactions by flagging spikes, new domains, and abnormal communication patterns. This provides early visibility into potential data sharing and security risks.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=536572](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=536572)

### Mar 2026 – Conditional Access for Microsoft Entra Account Recovery

Microsoft Entra ID has introduced Account Recovery to help users regain access when all registered authentication methods are unavailable. The recovery flow is secured with Conditional Access policies and will be available in public preview in March.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=529855](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=529855)

### Mar 2026 - New DLP Rule Action: Trigger Power Automate Workflows in Microsoft Purview

Starting March 2026, Microsoft Purview will support a new Data Loss Prevention (DLP) rule action that triggers custom Power Automate workflows when a policy match occurs.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=380721](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=380721)

### Mar 2026 – SharePoint File-Level Archiving Coming to Microsoft 365 Archive

Microsoft 365 Archive will support file-level archiving in SharePoint, enabling more granular retention and storage control. This feature enters the public preview in March 2026.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=477371](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=477371)

### Mar 2026 - Long-term Retention Period for Microsoft 365 Backup

Admins will be able to configure longer-term retention for Microsoft 365 backups, allowing data storage beyond one year. This feature will be available in preview by March 2026.  

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?id=481834](https://www.microsoft.com/en-us/microsoft-365/roadmap?id=481834)

### Mar 2026 - Microsoft Purview Information Barriers v2 Now Available for New Customers

Information Barriers v2 (IB v2) will be available by default for all new onboarding tenants. It supports up to 5,000 segments, allows users to be in up to 10 segments, and offers flexible user discoverability while enforcing IB policies.

Existing IB v1 tenants must opt in to upgrade to IB v2 to use these new capabilities. This update applies only to IB v1 customers.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=402516](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=402516)

### Mar 2026 - Automatically Set Work Location by Connecting to a Wi-Fi Network

Microsoft Teams will introduce a feature that automatically sets users’ work locations when they connect to the organization’s Wi-Fi or certain peripherals. This helps deliver location-based experiences without manual input. The feature will be disabled by default. Tenant admins will have the option to enable it and will require end-user consent to proceed.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=488800](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=488800)

### Mar 2026 – Auto-Enabling Passkey Profiles in Microsoft Entra ID

Microsoft Entra ID will bring passkey profiles and synced passkeys to general availability starting March 2026. This update gives admins the option to enable a new passkey profiles experience that supports _group-based passkey assignments_ and introduces a _passkeyType_ property to improve management and customization.

Tenants that do not opt in during the rollout window will be automatically migrated, with existing FIDO2 and passkey settings preserved and moved into a default passkey profile. Microsoft-managed registration campaigns will also update target passkeys where synced passkeys are enabled.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1221452](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1221452)

### Mid-Mar 2026 – Brand Impersonation Protection for Teams Calling

Microsoft is introducing Brand Impersonation Protection for Teams calling. This feature detects and warns users about fraudulent external callers impersonating trusted organizations.

Users will see a warning and can choose to accept, block, or end the call. The feature will be enabled by default and will evaluate incoming VoIP calls from first-time external callers.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1219793](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1219793)

### Mid-Mar 2026 - New Voice and Face Enrollment Dashboard in Teams Admin Center

Microsoft is introducing a new voice and face enrollment dashboard in the usage reports of the Teams admin center. The dashboard gives admins visibility into user voice and face enrollment used by AI-powered features such as speaker attribution, voice isolation, and face-based room experiences.

Admins can view enrollment status and related metrics. They can also permanently delete voice or face enrollment data for individual users or in bulk, improving data control and compliance.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1191921](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1191921)

### Mid-Mar 2026 – Rule-Based Management for Microsoft 365 Third-Party Apps in Teams

Microsoft is adding a rule-based configuration option in the Teams admin center to simplify app management. With this update, administrators can control Microsoft 365 certified third-party apps in bulk from the _Org-wide settings_ section. Also, app availability can be determined using publisher information and permission scopes.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1085133](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1085133)

### Mid-Mar 2026 – Data Security Posture Agent in Microsoft Purview

Microsoft Purview will introduce the Data Security Posture Agent to continuously discover sensitive data and assess data risks across the environment.

The agent uses AI to analyze content intent and meaning, delivering clearer insights and summaries that help security teams quickly identify risks and take corrective actions. It will be out for general availability by mid-Mar 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1217155](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1217155)

### Enhancements

### Mar 2026 – Organizational Messages Now Support Hybrid-Joined Devices

Microsoft is expanding Organizational Messages to support Entra ID Hybrid-joined devices in addition to fully cloud-joined devices. This allows organizations to deliver customized messaging to a wider range of enrolled endpoints.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=503564](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=503564)

### Mar 2026 – Email Support for Organizational Messages

Organizational messages currently support delivery through Windows Taskbar, Notifications, Spotlight, and Teams popovers. Microsoft is adding email as a delivery channel, enabling admins to send tenant-wide informational messages via email.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=503562](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=503562)

### Mar 2026 – Data Loss Prevention for Microsoft 365 Copilot

Microsoft is expanding DLP support to Microsoft 365 Copilot. Admins can configure DLP policies to block Copilot responses when prompts involve sensitive data from Microsoft 365 or the web.

This helps prevent data leakage and strengthens compliance controls across Copilot interactions.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=515945](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=515945)

### Existing Functionality Changes

### Mar 27, 2026 – Improved Enforcement for Conditional Access Resource Exclusions

Before March 27, 2026, Conditional Access policies targeting All resources with exclusions were not consistently enforced for apps requesting limited scopes, such as OIDC. This allowed users to sign in without meeting requirements like MFA, even when the app was not explicitly excluded.

Starting March 27, 2026, these policies will be enforced consistently for all apps, ensuring users must complete required authentication and access controls unless an app is explicitly excluded.

**_Ref_**: [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/upcoming-conditional-access-change-improved-enforcement-for-policies-with-resour/4488925](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/upcoming-conditional-access-change-improved-enforcement-for-policies-with-resour/4488925)

### Mar 31, 2026 – Azure Subscription Required for Entra ID Guest Governance

Microsoft introduced the Microsoft Entra ID Governance guest billing meter last year. Starting March 31, 2026, guest-related governance features will require an Azure subscription to be linked.

This requirement applies to access reviews scoped to guest users, including:

*   Inactive user reviews
*   User-to-group affiliation helper reviews

Without a linked Azure subscription, admins will be blocked from creating or updating guest-scoped governance policies.

**_Ref:_** [https://learn.microsoft.com/en-us/entra/fundamentals/whats-new#general-availability---entra-id-governance-guest-billing-meter-enforcement](https://learn.microsoft.com/en-us/entra/fundamentals/whats-new#general-availability---entra-id-governance-guest-billing-meter-enforcement)

### Mar 2026 – Decoupling Policy Tips & Email Notifications for SharePoint and OneDrive DLP

Currently, enabling email notifications in DLP policies for SharePoint and OneDrive also forces policy tips to be enabled, and vice versa. With this update, admins will be able to configure policy tips and email notifications independently, providing more flexibility in how alerts are managed.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC791114](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC791114)

### Action Required:

### Mar 31, 2026- Deprecation of ‘Require Approved Client App’ Conditional Access Grant

The Require approved client app control in Azure Active Directory (Azure AD) Conditional Access will be retired and no longer enforced.

**Solution:** You can make use of the “Require app protection policy” control, which has all the same capabilities

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448)

### Mar 31, 2026 – Retirement of Office 365 Connectors in Microsoft Teams

The retirement deadline for Office 365 Connectors in Microsoft Teams has been extended to March 31, 2026, giving organizations additional time to migrate.

**Solution:** Plan and complete the transition from Office 365 Connectors to Workflows webhooks to avoid disruption.

**_Ref:_** [https://devblogs.microsoft.com/microsoft365dev/retirement-of-office-365-connectors-within-microsoft-teams/](https://devblogs.microsoft.com/microsoft365dev/retirement-of-office-365-connectors-within-microsoft-teams/)

### Mar 31, 2026 – Retirement of Legacy SharePoint Online CDN Domain

Microsoft will retire the legacy CDN domain publiccdn.sharepointonline.com by late April 2026. Organizations must update any hardcoded references to the new domain public-cdn.sharepointonline.com to avoid broken links or 404 errors.

**Solution**: Complete validation and updates before March 31, 2026, for uninterrupted access to SharePoint resources.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184996](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184996)

## Q2 2026 (Attention Needed: 19)

### Apr 2026 – Cross-tenant Security Group Synchronization

Previously, cross-tenant synchronization supported only users. Microsoft is now extending this capability to security groups in Microsoft Entra, allowing centralized group management and cross-tenant access.

The feature will enter general availability by late-April and requires admin opt-in with configured attribute mappings and access policies.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1198077](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1198077)

### Apr 2026 - Retirement of SharePoint Online Legacy Information Management Features

Starting April 2026, SharePoint Online will retire several legacy compliance and records management features, including Information Management Policies, In-Place Records Management, and deletion-only policies for documents and site closure. These features will no longer be supported or accessible through the UI or APIs.

Solution: Organizations should [migrate to modern Microsoft Purview capabilities](https://learn.microsoft.com/sharepoint/migration-strategies), including Data Lifecycle Management and Purview Records Management.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1211579](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1211579)

### Apr 2026 – Insider Risk Management for AI Agents

As AI agents become more common in Microsoft 365, associated risks also continue to rise. Microsoft will extend Insider Risk Management to cover AI agents, enabling admins to define policies specifically for agent-driven activities. This enhancement helps detect, flag, or block risky behaviors when AI agents access sensitive data or perform high-risk actions across platforms like Copilot Studio, Azure AI Foundry, and Agent 365.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=516032](https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=516032)

### Apr 1, 2026 – Extended Access to Advanced Capabilities in Microsoft Teams and Places

Effective April 1, 2026, Microsoft is updating Teams and Places licensing to bring several high-value features directly into core Teams Enterprise licenses, making collaboration, space management, and large-scale events easier for all users:

*   **Microsoft Places Explorer and Places Finder for end-users** → now included in licenses with Teams/Outlook calendar (E3/E5, Business, Exchange Online, etc.)
*   **Teams Shared Space license** → renamed and expanded; admins get space management + analytics; 4 desks per license.
*   **Town halls & webinars** → advanced features now available for all Teams Enterprise users, up to 3,000 interactive attendees (10,000 view-only)
*   **New Attendee pack add-ons** → extend town hall capacity from 5,000 up to 100,000 participants.

**_Ref_**: [https://techcommunity.microsoft.com/blog/microsoftteamsblog/licensing-updates-extend-access-to-advanced-capabilities-in-microsoft-teams-and-/4488312](https://techcommunity.microsoft.com/blog/microsoftteamsblog/licensing-updates-extend-access-to-advanced-capabilities-in-microsoft-teams-and-/4488312)

### Apr 1, 2026 - Automatic Migration to New Outlook for Windows

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

### Apr 5, 2026 – Message Trace Support in Microsoft Graph API

Microsoft will introduce Microsoft Graph API support for Message Trace in public preview starting April 5, 2026.

Organizations currently relying on the Reporting Web Service API for Message Trace should begin transitioning to this Graph API, as the Reporting Web Service API will be deprecated.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1221939](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1221939)

### May 2026 – Microsoft Entra ID Account Recovery

Microsoft is introducing Entra ID Account Recovery, a new advanced recovery feature that helps users regain access to organizational accounts if they lose all registered authentication methods. Unlike a standard password reset, this feature securely verifies the user’s identity and re-establishes trust before allowing new authentication methods to be set up.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=529856](https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=529856)

### May 2026 – Retention Based on “Last Accessed” for OneDrive and SharePoint

Previously, retention policies could delete content based on conditions such as ‘_When items were created’_ or ‘_When items were last modified’_. Microsoft is now enhancing Data Lifecycle Management by introducing a new _“When items were last accessed”_ condition for retention policies.

This feature allows admins to manage and automatically clean up OneDrive and SharePoint content based on access history. It improves storage hygiene and helps optimize Microsoft 365 Copilot responses.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442)

### May 1, 2026 –Retirement of IDCRL Authentication in SharePoint and OneDrive

Microsoft is retiring the legacy IDCRL (Identity Client Run Time Library) authentication protocol in SharePoint and OneDrive for Business as part of the Secure Future Initiative. Legacy authentication will be permanently blocked beginning May 1, 2026, with modern OpenID Connect and OAuth protocols taking precedence.

**Solution:** Organizations should transition to modern authentication as soon as possible.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184649](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184649)

### June 2026 - New Secure Workflow to Bypass Legal Holds and Retention Policies in Microsoft Purview

Admins will have the ability to permanently delete sensitive Exchange mailbox content, bypassing retention policies and eDiscovery holds. This will be possible through the “Priority Cleanup Administrator” role, which grants authorized users’ permission to initiate Priority Cleanup for Exchange, allowing exceptions to standard retention and legal hold policies.

Since this process is irreversible and overrides existing policies, Microsoft has built-in approvals and special auditing for security.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=392838](https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=392838)

### June 1, 2026 – Retirement of the Sway Windows Desktop App

Microsoft is retiring the Sway Windows desktop app to streamline app management and focus on a single, fully supported web platform.

**Solution:** Users should switch to the web version at _sway.cloud.microsoft_, which provides the same features, preserves all content, and offers improved accessibility and updates.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1213784](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1213784)

### Late-June 2026 – Integration of Adaptive Protection with Data Lifecycle Management

Microsoft plans to make the Adaptive Protection and Data Lifecycle Management (DLM) integration generally available by late June 2026. This integration allows administrators to retain or restore items deleted by high-risk users, providing better safeguards against insider threats and accidental data loss.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110)

### June 30, 2026 - Retirement of Assignments and Courses ACEs in Viva Connections and SharePoint

To modernize Viva Connections, Microsoft will retire the Assignments and Courses adaptive card extensions (ACEs) and their SharePoint dashboard web parts for Education tenants. These SPFx components currently surface assignment and course information on the dashboard, and their removal aims to reduce redundancy and streamline the user experience. Also, the existing components will reach the end of support on June 30, 2026.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184647](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184647)

### June 30, 2026 - Exchange Web Services Will Be Blocked for Kiosk and Frontline Licenses

Microsoft will block Exchange Web Services access for mailboxes that do not include EWS usage rights starting June 30, 2026. After enforcement, requests made without a supported license will return an HTTP 403 error. Impacted licenses include Exchange Online Kiosk, Microsoft 365/Office 365 F1, and F3.

**Solution:** To continue using EWS, assign a license that includes EWS access, such as **Exchange Online Plan 1 or 2** or **Microsoft 365 E3/E5**.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/update-to-ews-access-for-kiosk--frontline-worker-licensed-users/4474299](https://techcommunity.microsoft.com/blog/exchange/update-to-ews-access-for-kiosk--frontline-worker-licensed-users/4474299)

### End of June 2026 – Unified Management of Teams Apps Across Microsoft 365

Microsoft is finalizing the rollout of Unified App Management for Teams, Outlook, and the Microsoft 365 app. This update simplifies app management by consolidating the separate admin experiences into a single, centralized management interface. The unified experience will be fully available to all organizations by the end of June 2026.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC796790](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC796790)

## Q3 2026 (Attention Needed: 6)

### July 01, 2026 – Microsoft 365 Price Increase

Starting July 1, 2026, Microsoft will implement a global price increase across all Microsoft 365 plans. Prices will increase by 5% to 33%, depending on the SKU. The increase reflects ongoing investments in AI capabilities, security enhancements, and advanced management features.

Alongside the price increase, Microsoft is adding value to select plans:

*   **Microsoft 365 Business Premium** will receive an **additional 50 GB of email storage** at no extra cost.
*   **Advanced Microsoft Intune capabilities** will be included with **Microsoft 365 E3 and E5** subscriptions.
*   Microsoft will include **Security Copilot in E5** subscriptions at no additional cost.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/blog/2025/12/04/advancing-microsoft-365-new-capabilities-and-pricing-update/](https://www.microsoft.com/en-us/microsoft-365/blog/2025/12/04/advancing-microsoft-365-new-capabilities-and-pricing-update/)

### July 14, 2026- InfoPath 2013 Client and InfoPath Forms Services in SharePoint Online Will be Retired  
  
InfoPath Client 2013 will reach the end of its extended support period on July 14, 2026, and to keep an aligned experience across Microsoft products, InfoPath Forms Service will be retired from SharePoint Online.

**Solution:** To understand the usage of InfoPath within your organization, you can utilize the [Microsoft 365 Assessment tool](https://aka.ms/assessment/infopath) to scan your tenant and analyze InfoPath usage. If you are currently using InfoPath, you can initiate the migration process to modern alternatives such as Power Apps, Power Automate, or Forms.

**_Ref_**: [https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190](https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190)

### July 2026 – SharePoint Alerts will be Fully Retired

Microsoft will discontinue support for SharePoint Alerts. Existing alerts can no longer be modified and will eventually stop functioning.

**Solution:** Microsoft recommends migrating SharePoint Alerts to Power Automate or SharePoint Rules. Use the Microsoft 365 Assessment tool to review alerts and plan the move.

**_Ref_**_:_ [https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f](https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f)

### Aug 1, 2026 - Microsoft Defender Threat Intelligence to Merge with Defender and Sentinel

Microsoft Defender Threat Intelligence will merge with Microsoft Defender and Microsoft Sentinel by August 1, 2026, bringing threat intelligence directly into the SecOps workflow. After the transition, threat insights will be available through the Microsoft Defender portal, with enhanced Threat Analytics that include:

*   Indicators of Compromise (IoCs) integrated into reports
*   MITRE ATT&CK mappings for tactics and techniques
*   Insights into threat actors and targeted industries
*   IoCs linked to cases for Microsoft Sentinel customers

After August 1, 2026, accessing MDTI capabilities will require an **active Microsoft Defender or Microsoft Sentinel license**.

**Solution:** Plan your transition to Microsoft Defender or Microsoft Sentinel before the deadline and review licensing to ensure uninterrupted access to MDTI capabilities.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1192257](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1192257)

### Sep 2026 - Update Office Apps to Keep Read Aloud, Transcription, and Dictation Features

Read Aloud, Transcription, and Dictation features in Microsoft 365 Office apps will stop working on versions earlier than 16.0.18827.20202 because of backend upgrades. This change takes effect after September 2026 for Worldwide tenants and November 2026 for GCC, GCC High, and DoD environments.

**Solution:** Update all Office apps to 16.0.18827.20202 or later before the deadline.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1127222](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1127222)

### Sep 17, 2026 - Retirement of Legacy Education LTI Tools

Microsoft will retire the legacy Education LTI tools including Teams Assignments, OneDrive, OneNote Class Notebook, and Reflect on September 17, 2026. These will be replaced by the new Microsoft 365 LTI unified tool, and users and admins will need to transition to this updated experience.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1160188](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1160188)

## Q4 2026 (Attention Needed: 9)

### Oct 2026 - Just in Time Protection on SharePoint in DLP

Microsoft is introducing Just-in-Time protection for SharePoint in Microsoft Purview Data Loss Prevention in preview.

With this feature, organizations can automatically apply DLP restrictions to unclassified files when they are accessed or shared externally. Instead of restricting files in advance, JIT protection enforces security measures only when there is a risk of data leaving the organization.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457)

### Oct 01, 2026- Retirement of Exchange Web Services in Exchange Online  
October 1, 2026, Microsoft will start blocking EWS requests from non-Microsoft apps to Exchange Online. The changes in Exchange Online do not affect Outlook for Windows or Mac, Teams, or any other Microsoft product.

**Solution**: Migrate your applications to Microsoft Graph to access Exchange Online data and gain access to the latest features and functionality.

**_Ref:_** [https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-exchange-web-services-in-exchange-online/ba-p/3924440](https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-exchange-web-services-in-exchange-online/ba-p/3924440)

### Oct 01, 2026 – Sign-in Risk Policy and User Risk Policy Retirement from Entra ID Protection

User risk policy or Sign-in risk policy UX in Entra ID Protection (formerly Identity Protection) will be retired on October 1, 2026.

**Solution:** Migrate Sign-in risk and User risk policies to Conditional Access.

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/what-s-new-in-microsoft-entra/ba-p/3796395](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/what-s-new-in-microsoft-entra/ba-p/3796395)

### Mid-Oct 2026 - Content Security Policy for Entra ID Sign-in Experience

Microsoft Entra ID is enforcing a stricter Content Security Policy (CSP) for sign-ins starting mid-October 2026. Only trusted Microsoft scripts will be allowed, blocking injected code to reduce XSS risks. This applies to browser-based sign-ins on _login.microsoftonline.com_ and does not affect Entra External ID tenants.

**Solution:** If you use tools or extensions that inject code, switch to non-injecting alternatives and [test sign-in flows](https://learn.microsoft.com/en-us/entra/identity-platform/content-security-policy#how-to-prepare-for-csp-enforcement) before CSP enforcement begins.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1191924](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1191924)

### Oct 13, 2026- Retirement of Microsoft Publisher  
In October 2026, Microsoft will discontinue Publisher in Microsoft 365, with on-premises suite support ending. While support lasts, they're exploring modern alternatives across Word, PowerPoint, and Designer for common Publisher tasks, with updates forthcoming.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC716267](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC716267)

### Oct 28, 2026 - Retirement of Microsoft Entra PIM Iteration 2 (Beta) APIs

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

### Dec 31, 2026 - End of Support for Dynamics 365 Guides and Remote Assist

Dynamics 365 Guides and Dynamics 365 Remote Assist will retire on December 31, 2026. After this date, the products will no longer receive security updates, bug fixes, or technical support.

**Solution:** Customers should plan their transition early by identifying dependent users and scenarios. Explore alternative mixed reality solutions available in the [Microsoft Marketplace](https://marketplace.microsoft.com/marketplace/apps?category=mixed-reality), and consider Microsoft Teams Mobile with [spatial annotation](https://learn.microsoft.com/en-us/dynamics365/mixed-reality/remote-assist/teams-mobile-annotate) for certain remote collaboration use cases.

**_Ref:_** [https://learn.microsoft.com/en-us/lifecycle/announcements/dynamics-365-guides-remote-assist-end-of-support](https://learn.microsoft.com/en-us/lifecycle/announcements/dynamics-365-guides-remote-assist-end-of-support)

## 2027 (Attention Needed: 4)

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

### Oct 2027 - Removal of Passcode Option from Create Meeting API

In October 2027, Microsoft will remove the option to create meetings without passcodes. This means all online meetings created through the Microsoft Graph API will automatically require a passcode, and the _isPasscodeRequired_ property on the _joinMeetingIdSettings_ resource will be removed. This change ensures that every meeting is consistently secured with a passcode, simplifying meeting creation, and improving security.

[https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC985483](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC985483)

### Oct 14, 2027 – Retirement of Duplicative Properties in Passkey (FIDO2) Authentication Methods Policy

To align with the updated passkey policy API schema that supports group-based passkey profiles, Microsoft will retire _isAttestationEnforced_ and _keyRestrictions_ from the fido2AuthenticationMethodConfiguration API. During the transition, these properties will sync with attestationEnforcement and keyRestrictions in the Default passkey profile.

**Solution:** Admins should update configurations, automations, and integrations to use the new schema.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1188230](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1188230)

  
In conclusion, navigating the ever-evolving landscape of Microsoft 365 requires staying informed about the changes. By proactively adapting to these changes, you can optimize your Microsoft 365 experience, maximize productivity, and effectively plan for the future.

We are committed to keeping this blog updated with the latest information, so stay tuned for upcoming updates.

[https://blog.admindroid.com/microsoft-365-end-of-support-milestones/](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/)