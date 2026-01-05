# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.

Discover the **key changes, deprecations**, and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

Here is a list of changes categorized by month and year.

*   [Jan 2026](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/#Jan%202026) (Retirements: 6, New Features: 13, Enhancements: 5, Existing Functionality Changes: 3, Action Needed: 4)
*   [Feb 2026](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/#Feb%202026) (Retirements: 2, New Features: 10, Enhancements: 3, Existing Functionality Changes: 2, Action Needed: 1)
*   [Mar 2026](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/#Mar%202026) (Attention Needed: 12)
*   [Q2 2026](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/#Q2%202026) (Attention Needed: 13)
*   [Q3 2026](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/#Q3%202026) (Attention Needed: 6)
*   [Q4 2026](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/#Q4%202026) (Attention Needed: 6)

## January 2026

[Retirements](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/#Retirements): 6 | [New Features](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/#New%20Features): 13 | [Enhancements](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/#Enhancements): 5 | [Existing Functionality Changes](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/#Existing%20Functionality%20Changes) : 3 | [Action Needed](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/#Action%20Needed): 4

### Retirements

### Early-Jan 2026 – Retirement of Activity-Based Authentication Timeout for Outlook on the Web

Microsoft will retire the activity-based authentication timeout setting for Outlook on the Web (OWA) starting in early January 2026. This feature, which signed users out after inactivity, is being retired to simplify session timeout management.

**Solution:** Configure Idle session timeout to maintain similar session control behavior.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher#/MessageCenter/:/messages/MC1163753](https://admin.cloud.microsoft/?source=applauncher#/MessageCenter/:/messages/MC1163753)

### Jan 7, 2026 – Removal of Legacy Anthropic Toggle in Microsoft 365 Admin Center

Anthropic will be enabled as a Microsoft subprocessor by default starting January 7, 2026. As a result, the legacy admin toggle to opt-in to Anthropic’s commercial terms is deprecated. To continue using Anthropic models in regions (EU, EFTA, and the UK) where the new subprocessor toggle is OFF by default, admins must explicitly enable the new toggle.

**_Ref:_** [https://learn.microsoft.com/en-us/copilot/microsoft-365/connect-to-ai-subprocessor#deprecation-of-legacy-anthropic-admin-toggle](https://learn.microsoft.com/en-us/copilot/microsoft-365/connect-to-ai-subprocessor#deprecation-of-legacy-anthropic-admin-toggle)

### Jan 12, 2026 – Deprecation of “When Sending a Message” Group Policy in Classic Outlook for Windows

The “When Sending a Message” group policy is currently used to manage grouped email-sending settings in Classic Outlook for Windows. This feature will be retired by January 13, 2026. These configurations will be replaced with new, separate Group Policy settings that provide granular control over individual mail-sending behaviors.

**Solution**: Migrate existing configurations to the new individual policy settings before January 12, 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1164375](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1164375)

### Jan 13, 2026 – End of Extended Support for Microsoft Advanced Threat Analytics 1.x

Microsoft Advanced Threat Analytics (ATA) extended support will be ended on January 13, 2026.

**Solution**: You can access Microsoft ATA updates either through Microsoft Update or by downloading them manually.

Ref: [https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c](https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c)

### Jan 13, 2026 – Retirement of App-V Package Creation for Microsoft 365 Apps

Microsoft is retiring the ability to create new App-V packages for Microsoft 365 Apps. While App-V has been used to virtualize and deliver applications without installing them directly on user devices, Microsoft is now shifting toward the modern Click-to-Run deployment model.

Existing App-V packages will continue to function, but starting January 13, 2026, new App-V packages for Microsoft 365 Apps can no longer be created.

**Solution**: Shift to Click-to-Run deployment for better performance and reliability.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1183012](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1183012)

### Jan 15, 2026 - Technology Experience Score Retirement from Microsoft Adoption Score

Adoption Score in the Microsoft 365 admin center measures how effectively your organization adopts Microsoft 365, based on People experiences (user collaboration) and Technology experiences (device & network performance).

Between Jan 15–Jan 30, 2026, Microsoft will retire the Technology experience score and its sub-scores (Network Connectivity, Microsoft 365 Apps Health, and Endpoint Analytics). As a result, the maximum score will be reduced from 900 to 600.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1193412](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1193412)

### New Features

### Early Jan 2026 – Purge Mitigation Action in Microsoft Purview Data Security Investigations

Microsoft is introducing a purge mitigation action in Microsoft Purview Data Security Investigations (DSI) that allows admins to delete sensitive or overshared content directly during investigations. Integrated with DSI’s AI-powered capabilities such as content categorization, AI search, and risk analysis, this action helps security teams respond to incidents faster and reduce data exposure.

The feature is enabled by default and continues to respect existing DLP, retention, and sensitivity label policies.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=542930](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=542930)

### Early Jan 2026 - Auto-Archiving for Exchange Online to Prevent Mail Flow Disruption

Auto-archiving for Exchange Online is now generally available. When an archived mailbox exceeds 96% of its quota, older emails are automatically moved to the archive, excluding items tagged _‘Never Move to Archive’_. This helps prevent quota overruns and maintain uninterrupted mail flow.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1191923](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1191923)

### Early Jan 2026 - Wait on Send for DLP in New Outlook for Windows

Microsoft is introducing Wait on Send for Data Loss Prevention in the new Outlook for Windows. This feature temporarily delays email delivery until DLP evaluation is complete, reducing the risk of sensitive data exposure.

The feature is disabled by default and is managed through Exchange mailbox settings. Admins can control DLP send delays by configuring mailbox parameters:

*   **DLPWaitOnSendEnabled** – Enables or disables the wait-on-send experience
*   **DLPWaitOnSendTimeout** – Defines how long Outlook waits before allowing an override

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1198702](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1198702)

### Early Jan 2026 - Block Teams External Users from Microsoft Defender

Previously, blocking external users in Microsoft Teams was limited to the Teams admin center, offering minimal control for security teams. Microsoft now integrates Teams with Microsoft Defender, allowing admins to manage external user access directly from the Tenant Allow/Block List.

Admins can block up to **4,000 domains** and **200 email addresses**, with full audit logging and no impact on existing Teams configurations. To use this capability, admins must enable the “Block specific users from communicating with people in my organization” and **_“Allow my security team to manage blocked domains and blocked users”_** settings in the Teams admin center.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1200058](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1200058)

### Jan 2026 – DLP Policy Tip Support Coming to Outlook for Mac

Microsoft is bringing Data Loss Prevention (DLP) policy tip support to Outlook for Mac. This helps users avoid accidental data leakage by showing policy tips when sensitive data is detected in emails. Users will be able to identify non-compliant recipients and take corrective actions, including overriding the policy when permitted.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=484854](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=484854)

### Mid-Jan - 2026 Apps Now Supported in Teams Private Channels

Following the introduction of [app support for shared channels](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1168294), Microsoft is extending the same capability to private channels. Apps such as bots, tabs, and message extensions can now be added to private channels, expanding beyond the earlier limited set of supported tabs.

Apps must be configured at the channel level, as team-level app settings do not apply to shared or private channels. This capability is enabled by default.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197145](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197145)

### Mid-Jan 2026 – New Permissions Report in SharePoint Admin Center

Starting mid-January 2026, admins will see a new Permissions report under Data Access Governance in the SharePoint admin center. This report displays all SharePoint sites a user can access, showing both direct and group-based permissions. It also indicates whether access is granted to the full site or only specific sections.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197128](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197128)

### Mid-Jan 2026 - OneNote File Usage Data in SharePoint Site Analytics

SharePoint site analytics now include OneNote (.one) file usage, counting toward _Unique viewers_ and _Site visits_. Frequently accessed OneNote files will also appear in _Popular content_ when heavily used in the last 7 days.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=537285](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=537285)

### Mid-Jan 2026 Copilot Readiness Packages in Microsoft 365 Admin Center

Microsoft is introducing Copilot Readiness Packages under Copilot > Settings in the Microsoft 365 admin center. This experience provides centralized, Microsoft-recommended presets, readiness assessments, and guided actions to help admins deploy Copilot securely.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1192665](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1192665)

### Jan 15, 2026 - New Pay-As-You-Go Billing Experience in Microsoft 365 Admin Center

A new pay-as-you-go (PAYG) billing experience is coming to the Microsoft 365 admin center, centralizing billing for **Microsoft 365 Backup** and **Copilot** under the Billing node.

*   Admins can manage billing policies, set budgets, and track usage & spending directly in the admin center.
*   Subscriptions and resource groups can also be created without switching to Azure.
*   PAYG setup for other services will continue under Org Settings > PAYG until they are migrated. Additional PAYG-enabled services will be added to the Billing node over time.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1186367](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1186367)

### Late-Jan 2026 – Insider Risk Management User Analytics in Microsoft Purview

Microsoft Purview will introduce User Activity Summaries within Insider Risk Management (IRM) to help analysts better assess risk context during incident reviews. These insights consolidate data from multiple security and compliance solutions, providing a unified view of user behavior and potential policy violations.

Insights will be available in:

1.  Microsoft Purview Data Loss Prevention alerts.
2.  Microsoft Defender user entity pages and alerts.
3.  Communication Compliance policy reports.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1045212](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1045212)

### Late-Jan 2026 – Enhanced Troubleshooting for Teams Meetings and Calls

Microsoft adds enhanced tools in the Teams admin center to help admins quickly diagnose and resolve meeting and call issues. These include:

*   **Automatic issue detection** – Identifies and summarizes audio, video, & screen-sharing issues and shows how many participants are affected.
*   **Richer participant insights** – Provides clearer participant-level device and network details, with signal charts and telemetry export for deeper analysis.
*   **Smarter search and filters** – Enables finding meetings by ID and filtering or sorting issues by type and time.
*   **Copilot-assisted troubleshooting** – Integrates Copilot to analyze telemetry, explain issues, and suggest resolutions within the Teams admin center.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1193405](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1193405)

### Late-Jan 2026 – Cross-tenant Security Group Synchronization

Previously, cross-tenant synchronization supported only users. Microsoft is now extending this capability to security groups in Microsoft Entra, allowing centralized group management and cross-tenant access.

The feature enters public preview in late January 2026 and requires admin opt-in with configured attribute mappings and access policies.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1198077](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1198077)

### Enhancements

### Jan 2026 – Shorter Meeting URLs for Microsoft Teams

Microsoft plans to shorten meeting URLs for easier sharing across all Teams platforms. The URL will contain only the meeting ID. Other parameters such as tenant ID, organizer ID, conversation ID, and message ID will not be included. The new URL format will be: https://teams.microsoft.com/meet/<meeting\_id>?p=<HashedPasscode>.

To enhance security, these new URLs will expire **60 days** after scheduled meetings or **8 hours** after _Meet Now_ creation.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC772556](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC772556)

### Jan 2026 – Redesigned Workflows Experience in Microsoft Teams

Microsoft Teams will launch a reimagined Workflows experience powered by Power Automate, offering a faster, simpler, and more intuitive automation platform. This new version enables users to automate tasks such as approvals, message scheduling, and data synchronization directly within Teams.

**Key Improvements Include:**

*   A modern and streamlined interface optimized for chats, channels, and SharePoint lists and libraries.
*   A revamped template gallery for easy discovery and setup of automation flows.
*   Natural language automation capabilities that let users describe what they want to automate in plain English.
*   A Madlib-style editor for simple customization using placeholders and dynamic tokens.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1121517](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1121517)

### Jan 2026 - Microsoft Purview Insider Risk Management Adds OCR Support for Image-Based Risk Detection

Starting January 2026, Insider Risk Management in Microsoft Purview will support Optical Character Recognition (OCR) to detect sensitive content in images shared via SharePoint, Teams messages, and endpoints. This enhancement helps identify potential insider threats such as data leaks or intellectual property theft, while preserving user privacy through pseudonymization and audit controls.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=171185](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=171185)

### Jan 2026 - Update to Insider Risk Management Limits

Microsoft Purview Insider Risk Management is increasing key limits to support larger detection workloads:

*   **Variants per indicator:** 3 → 10
*   **Total variants across all indicators:** 100 → 400
*   **Items per detection group:** 200 → 500

These updates enhance scalability and allow for more robust insider risk scenarios.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=518291](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=518291)

### Early-Jan 2026 - Policy Alerts Improvements in Microsoft Purview Communication Compliance

Communication Compliance is enhancing policy alert customization. Admins will have the ability to set the alert frequency for each policy and adjust the email alert frequency and recipients directly within the policy creation wizard, via the new alerts page. This update will be generally available from early-Jan 2026.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920304](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920304)

### Existing Functionality Changes

### Early-Jan 2026 - Automatic Windows Event Auditing in Defender for Identity Unified Sensors (v3.x)

Microsoft is introducing an opt-in automatic Windows event auditing configuration for Microsoft Defender for Identity unified sensors (v3.x). When enabled, the required auditing settings are automatically applied during new sensor activation. For existing sensors, any misconfigurations are automatically corrected, reducing manual effort and ensuring consistent sensor health.

The feature is **disabled** by default and must be enabled by admins via the UI or Graph API.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1193410](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1193410)

### Early-Jan 2026 - Upcoming Change to Teams Desktop Client on Windows

To improve the calling performance and startup timing, Microsoft Teams Desktop for Windows will run a new process “teams\_modulehost.exe,” which will handle the calling features separately. So, this child process will handle the calling stack separately from the main process (ms-teams.exe).

So, admins need to update the endpoint and security software to allow this new process.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1189656](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1189656)

### Jan 12, 2026 - Messaging Safety Settings Turned on by Default in Teams Admin Center

Starting January 12, 2026, Microsoft will enable the following messaging safety settings by default in the Teams admin center for tenants using the default configuration:

*   Weaponizable file type protection
*   Malicious URL protection
*   Report incorrect security detections

As a result, users may see warning labels on malicious links, and messages containing risky file types will be blocked. They will also have the option to report false positives.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1200576](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1200576)

### Action Required

### Jan 4, 2026 – Outlook for Android to Require Android 10.0 or Higher

Starting January 5, 2026, the Outlook for Android app will require devices to run Android 10.0 or later to continue receiving updates, security patches, and new features. Users on earlier Android versions will retain app access temporarily but will not receive further updates.

**Solution:** Advise users to upgrade their Android OS to version 10.0 or higher by Jan 4 to ensure ongoing support.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1163756](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1163756)

### Jan 7, 2026 - Updated Certificate Trust Requirement for Microsoft Entra Services

Microsoft will migrate Microsoft Entra services from DigiCert Global Root G1 to DigiCert Global Root G2 certificates starting January 7, 2026. Organizations that do not trust the DigiCert G2 root CA, or that pin to the G1 root, may experience authentication failures when accessing Entra services.

Affected domains include login.live.com, login.windows.net, autologon.microsoftazuread-sso.com, and graph.windows.net. The login.microsoftonline.com domain was already migrated in February 2025 and is not impacted by this update.

**Solution:** Trust DigiCert Global Root G2 and its subordinate CAs. Remove any client-side pinning to DigiCert Global Root G1 before January 7, 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1193408](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1193408)

### Jan 30, 2026 -Retirement of IDCRL Authentication in SharePoint and OneDrive

Microsoft is retiring the legacy IDCRL (Identity Client Run Time Library) authentication protocol in SharePoint and OneDrive for Business as part of the Secure Future Initiative. Legacy authentication will be blocked by default beginning January 31, 2026, with modern OpenID Connect and OAuth protocols taking precedence.

**Solution:** A temporary re-enablement option is available until April 2026. Organizations should transition to modern authentication as soon as possible.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184649](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184649)

**Jan 30, 2026 - Outlook Events from Email: Transition from Legacy Extraction to Schema.org**

Outlook’s Events from email feature automatically adds reservations such as flights, hotels, rental cars, and deliveries to users’ calendars. This feature relies on legacy extraction, which is unsupported and unreliable, causing missing events and incorrect calendar entries.

**Solution:** Organizations should coordinate with their email providers to adopt Schema.org markup by January 30, 2026, to ensure reliable event extraction.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1158908](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1158908)

## Feb 2026

### Retirements

### Mid-Feb 2026 - Retirement of Microsoft Planner Features

Microsoft will roll out a major update to Microsoft Planner in early 2026. While new capabilities such as task chats and custom templates are being introduced, several existing features will be retired or become unavailable by mid-February 2026.

**Features being retired:**

*   Legacy task comments (replaced by task chat)
*   Whiteboard tab for premium plans
*   Planner component in Loop pages
*   Planner integration with Viva Goals
*   iCalendar feed for Planner tasks

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1193421](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1193421)

### Feb 27, 2026 - Retirement of Designer Bot and Banners in Microsoft Teams

Microsoft will retire the Designer bot and Designer banners in Microsoft Teams by February 27, 2026. After this change, users will no longer be able to use the Designer bot in chats or create channel announcement banners with Designer.

**Solution:** Organizations should transition image generation workflows to Copilot in Microsoft Teams going forward.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197104](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197104)

### New Features

### Early-Feb 2026 - Cost Estimator and Transparency Report for Data Security Investigations

Microsoft is adding new capabilities to improve cost visibility for Data Security Investigations (DSI):

*   **Lightweight Cost Estimator:** Helps model and forecast storage and compute costs based on investigation scenarios.
*   **Usage Dashboard Report:** Provides granular insights into billed storage and compute units, helping admins identify cost-saving opportunities.

These enhancements support pay-as-you-go billing, require no configuration changes, and will be generally available starting early February 2026.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1186360](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1186360)

### Early-Feb 2026 - New Voice and Face Enrollment Dashboard in Teams Admin Center

Microsoft is introducing a new voice and face enrollment dashboard in the usage reports of the Teams admin center. The dashboard gives admins visibility into user voice and face enrollment used by AI-powered features such as speaker attribution, voice isolation, and face-based room experiences.

Admins can view enrollment status and related metrics. They can also permanently delete voice or face enrollment data for individual users or in bulk, improving data control and compliance.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1191921](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1191921)

### Feb 2026 - Automatically Set Work Location by Connecting to a Wi-Fi Network

Microsoft Teams will introduce a feature that automatically sets users’ work locations when they connect to the organization’s Wi-Fi or certain peripherals. This helps deliver location-based experiences without manual input. The feature will be disabled by default. Tenant admins will have the option to enable it and will require end-user consent to proceed.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=488800](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=488800)

### Feb 2026 - PST Import Support in the New Outlook for Windows

The new Outlook for Windows will soon provide a feature to import email messages directly from .pst files (Outlook Data File) into user mailboxes, simplifying mailbox migration and recovery.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=485739](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=485739)

### Feb 2026 - Content Security Policy in SharePoint Online

Microsoft introduced Content Security Policy (CSP) in SharePoint as a browser-level security standard that controls which scripts, styles, images, and other resources a site is allowed to load. If a resource isn’t explicitly approved, the browser blocks it. This helps protect SharePoint sites from threats like cross-site scripting (XSS), clickjacking, and other code injection attacks.

**_Ref_**: [https://techcommunity.microsoft.com/blog/spblog/sharepoint-online-content-security-policy-csp-enforcement-dates-and-guidance/4472662](https://techcommunity.microsoft.com/blog/spblog/sharepoint-online-content-security-policy-csp-enforcement-dates-and-guidance/4472662)

### Feb 2026 – Classifier Simulation Mode in Microsoft Purview Information Protection

As part of classifier health monitoring, Microsoft Purview is introducing Classifier Simulation Mode, generally available from February 2026. The feature is available to all tenants, and simulation is optional for admins.

*   Simulate custom classifiers on production data before publishing to optimize logic and reduce false positives and performance issues.
*   View simulation controls and classifier health insights directly in the Microsoft Purview compliance portal.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1185445](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1185445)

### Feb 2026 – New External Domain Anomalies Report in Teams Admin Center

Microsoft Teams will roll out a new External Domain Anomalies report in February 2026. The report helps admins detect unusual or risky external interactions by flagging spikes, new domains, and abnormal communication patterns. This provides early visibility into potential data sharing and security risks.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=536572](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=536572)

### Feb 2026 – Chat With Anyone in Teams Using an Email Address

Teams will soon allow users to chat with external contacts using their email addresses, even if those contacts do not have a Teams account. External users will receive an invitation to join as guests. This experience follows your organization’s B2B Guest policy and will be enabled by default.

Admins can disable chat with anyone using an email address by setting UseB2BInvitesToAddExternalUsers as false in _Set-CsTeamsMessagingPolicy_ cmdlet.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1182004](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1182004)

### Mid-Feb 2026 – Streamlined Admin Controls for External Collaboration in Teams Admin Center

Microsoft is simplifying external collaboration settings across chats, calls, meetings, Teams, and shared channels. This update reaches general availability in mid-February 2026 and introduces a new interface with three predefined collaboration modes:

*   **Open:** Allows chats, calls, and meetings with all external domains and Teams personal accounts via federation or external access.
*   **Controlled:** Matches the current default for enterprise and EDU tenants and blocks shared channel collaboration.
*   **Custom:** Allows complete customization of external collaboration settings across all Teams surfaces.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1183006](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1183006)

### Late-Feb 2026 – Soft Deletion and Restoration of Cloud Security Groups

Microsoft is introducing soft deletion support for cloud security groups. Deleted groups can be restored for up to 30 days, along with their settings, membership, and properties. Audit logs will track deletion, restoration, and hard deletion events.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1183299](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1183299)

### Enhancements

### Feb 2026 – Jailbreak and Root Detection in Microsoft Authenticator App

Microsoft will enhance the Microsoft Authenticator app with jailbreak and root detection capabilities for Entra credentials on both iOS and Android platforms. Once this feature is active, Entra credentials on jailbroken or rooted devices will stop functioning. And any existing ones will be automatically wiped for security reasons.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1179154](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1179154)

### Mid-Feb 2026 Microsoft Purview Admin Roles to Sync with New Microsoft Entra Roles

Microsoft Purview will map certain high-privileged Purview admin roles to new roles in Microsoft Entra such as _Purview Workload Content Reader, Purview Workload Content Writer, and Purview Workload Content Administrator_.

Role assignments will sync automatically, and admins will receive the appropriate Entra role based on their Purview permissions. These roles should not be assigned directly in Entra, as Purview manages and overwrites them. Admins may also see new Purview-specific Entra roles in audit logs.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1199765](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1199765)

### Mid-Feb 2026 – Rule-Based Management for Microsoft 365 Third-Party Apps in Teams

Microsoft is adding a rule-based configuration option in the Teams admin center to simplify app management. With this update, administrators can control Microsoft 365 certified third-party apps in bulk from the _Org-wide settings_ section. Also, app availability can be determined using publisher information and permission scopes.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1085133](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1085133)

### Existing Functionality Changes

### Feb 2026 – Exchange Online Moderation Approvals via Actionable Messages

The Exchange Online Moderation feature allows moderators to approve or reject messages before they’re sent. Currently, this can only be done in Outlook Desktop or Outlook on the web. With the new update using Actionable Messages, moderators can now approve or reject moderated messages from any Microsoft email client, including Outlook for Windows, Mac, iOS, and Android.  
  
**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=492743](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=492743)

### Feb 2026 – Microsoft Entra Replaces “Revoke MFA Sessions” with “Revoke Sessions”

Microsoft Entra will remove “Revoke multifactor authentication sessions”, which applied only to per-user MFA, and replace it with “Revoke sessions” in February 2026. The new Revoke sessions action will invalidate all active user sessions, including MFA, regardless of whether MFA is enforced through Conditional Access or per-user policies.

**_Ref:_** [https://learn.microsoft.com/en-us/entra/fundamentals/whats-new#plan-for-change---update-to-revoke-multifactor-authentication-sessions](https://learn.microsoft.com/en-us/entra/fundamentals/whats-new#plan-for-change---update-to-revoke-multifactor-authentication-sessions)

### Action Required

### Feb 28, 2026 - Exchange Online to Block ActiveSync Versions below 16.1

Exchange Online will block devices using Exchange ActiveSync (EAS) versions below 16.1 starting March 1, 2026, to improve security and reliability. Devices running older EAS versions will no longer connect, while Outlook Mobile is not affected.

**Solution:** Use the _Get-MobileDevice_ PowerShell command to identify devices running unsupported EAS versions and prompt users to upgrade before enforcement.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197103](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197103)

### March 2026 (Attention Needed: 12)

### Early-March 2026 - Featured Links Retirement on SharePoint Online Start Page

From March 2026, Microsoft will retire the Featured Links capability in SharePoint Online. Admins will no longer be able to create, edit, update, or access Featured Links. As part of this change, existing Featured Links will be removed from the SharePoint Online start page and the mobile app.

**Solution:** Highlight important sites and content using alternatives such as global navigation links and Viva Connections Resources.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197131](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197131)

### March 2026 – SharePoint File-Level Archiving Coming to Microsoft 365 Archive

Microsoft 365 Archive will support file-level archiving in SharePoint, enabling more granular retention and storage control. This feature enters the public preview in March 2026.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=477371](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=477371)

### March 2026 - Long-term Retention Period for Microsoft 365 Backup

Admins will be able to configure longer-term retention for Microsoft 365 backups, allowing data storage beyond one year. This feature will be available in preview by March 2026.  

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=481834](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=481834)

### Mar 2026 - Microsoft Purview Information Barriers v2 Now Available for New Customers

Information Barriers v2 (IB v2) will be available by default for all new onboarding tenants. It supports up to 5,000 segments, allows users to be in up to 10 segments, and offers flexible user discoverability while enforcing IB policies.

Existing IB v1 tenants must opt in to upgrade to IB v2 to use these new capabilities. This update applies only to IB v1 customers.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=402516](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=402516)

### Mar 2026 – Organizational Messages Now Support Hybrid-Joined Devices

Microsoft is expanding Organizational Messages to support Entra ID Hybrid-joined devices in addition to fully cloud-joined devices. This allows organizations to deliver customized messaging to a wider range of enrolled endpoints.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=503564](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=503564)

### Mar 2026 – Conditional Access for Microsoft Entra Account Recovery

Microsoft Entra ID has introduced Account Recovery to help users regain access when all registered authentication methods are unavailable. The recovery flow is secured with Conditional Access policies and will be available in public preview in March.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=529855](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=529855)

### Mar 2026 - New DLP Rule Action: Trigger Power Automate Workflows in Microsoft Purview

Starting March 2026, Microsoft Purview will support a new Data Loss Prevention (DLP) rule action that triggers custom Power Automate workflows when a policy match occurs.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=380721](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=380721)

### Mar 2026 – Decoupling Policy Tips & Email Notifications for SharePoint and OneDrive DLP

Currently, enabling email notifications in DLP policies for SharePoint and OneDrive also forces policy tips to be enabled, and vice versa. With this update, admins will be able to configure policy tips and email notifications independently, providing more flexibility in how alerts are managed.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=396575](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=396575)

### Mar 31, 2026 – Retirement of Office 365 Connectors in Microsoft Teams

The retirement deadline for Office 365 Connectors in Microsoft Teams has been extended to March 31, 2026, giving organizations additional time to migrate.

**Solution:** Plan and complete the transition from Office 365 Connectors to Workflows webhooks to avoid disruption.

**_Ref:_** [https://devblogs.microsoft.com/microsoft365dev/retirement-of-office-365-connectors-within-microsoft-teams/](https://devblogs.microsoft.com/microsoft365dev/retirement-of-office-365-connectors-within-microsoft-teams/)

### Mar 18, 2026 - Deprecation of Reporting Web Service Support for Exchange Online Message Trace Data

The Reporting Web Service for Message Trace will start phasing out by March 18, 2026.

**Solution**: Use the new Message Trace PowerShell cmdlets instead.

**_Ref_**: [https://techcommunity.microsoft.com/blog/exchange/announcing-general-availability-ga-of-the-new-message-trace-in-exchange-online/4420243](https://techcommunity.microsoft.com/blog/exchange/announcing-general-availability-ga-of-the-new-message-trace-in-exchange-online/4420243)

### Mar 30, 2026 - Retirement of External Access Token for Actionable Messages

External access tokens for actionable messages will be retired on March 31, 2026, and organizations must transition to Microsoft Entra authentication to ensure continued functionality. After this date, any actionable message relying on external tokens will fail. This change strengthens security and aligns with modern identity standards.

**Solution:** Organizations using actionable messages should review their current implementations and update all integrations to Microsoft Entra authentication before the deadline to avoid disruptions.

**_Ref_**: [https://learn.microsoft.com/en-us/outlook/actionable-messages/](https://learn.microsoft.com/en-us/outlook/actionable-messages/)

### Mar 31, 2026- Deprecation of ‘Require Approved Client App’ Conditional Access Grant

The Require approved client app control in Azure Active Directory (Azure AD) Conditional Access will be retired and no longer enforced.

**Solution:** You can make use of the “Require app protection policy” control, which has all the same capabilities

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448)

### Mar 31, 2026 – Retirement of Legacy SharePoint Online CDN Domain

Microsoft will retire the legacy CDN domain publiccdn.sharepointonline.com by late April 2026. Organizations must update any hardcoded references to the new domain public-cdn.sharepointonline.com to avoid broken links or 404 errors.

Recommendation: Complete validation and updates before March 31, 2026, for uninterrupted access to SharePoint resources.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184996](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184996)

## Q2 2026 (Attention Needed: 13)

### April 2026 - Retirement of SharePoint Online Legacy Information Management Features

Starting April 2026, SharePoint Online will retire several legacy compliance and records management features, including Information Management Policies, In-Place Records Management, and deletion-only policies for documents and site closure. These features will no longer be supported or accessible through the UI or APIs.

Solution: Organizations should [migrate to modern Microsoft Purview capabilities](https://learn.microsoft.com/sharepoint/migration-strategies), including Data Lifecycle Management and Purview Records Management.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1211579](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1211579)

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

### May 2026 – Retention Based on “Last Accessed” for OneDrive and SharePoint

Previously, retention policies could delete content based on conditions such as ‘_When items were created’_ or ‘_When items were last modified’_. Microsoft is now enhancing Data Lifecycle Management by introducing a new _“When items were last accessed”_ condition for retention policies.

This feature allows admins to manage and automatically clean up OneDrive and SharePoint content based on access history. It improves storage hygiene and helps optimize Microsoft 365 Copilot responses.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442)

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

## Q4 2026 (Attention Needed: 6)

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

### Dec 31, 2026 - End of Support for Dynamics 365 Guides and Remote Assist

Dynamics 365 Guides and Dynamics 365 Remote Assist will retire on December 31, 2026. After this date, the products will no longer receive security updates, bug fixes, or technical support.

**Solution:** Customers should plan their transition early by identifying dependent users and scenarios. Explore alternative mixed reality solutions available in the [Microsoft Marketplace](https://marketplace.microsoft.com/marketplace/apps?category=mixed-reality), and consider Microsoft Teams Mobile with [spatial annotation](https://learn.microsoft.com/en-us/dynamics365/mixed-reality/remote-assist/teams-mobile-annotate) for certain remote collaboration use cases.

**_Ref:_** [https://learn.microsoft.com/en-us/lifecycle/announcements/dynamics-365-guides-remote-assist-end-of-support](https://learn.microsoft.com/en-us/lifecycle/announcements/dynamics-365-guides-remote-assist-end-of-support)

  
In conclusion, navigating the ever-evolving landscape of Microsoft 365 requires staying informed about the changes. By proactively adapting to these changes, you can optimize your Microsoft 365 experience, maximize productivity, and effectively plan for the future.

We are committed to keeping this blog updated with the latest information, so stay tuned for upcoming updates.

[https://blog.admindroid.com/microsoft-365-end-of-support-milestones/](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/)