# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.  
  
Discover the **key changes, deprecations**, and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

With November wrapping up and December on the horizon, it’s time to revisit the standout November Ignite updates. Microsoft shipped six major updates that hint at the powerful capabilities coming next:

*   [Microsoft Baseline Security Mode (BSM)](https://blog.admindroid.com/baseline-security-mode-in-microsoft-365-admin-center/) - BSM provides a default, tenant-wide security foundation by automatically applying Microsoft’s core protection settings. It removes the need for admins to configure every security control manually.
*   [Microsoft Entra Agent ID](https://blog.admindroid.com/new-microsoft-entra-agent-id-to-secure-and-manage-ai-agents/) - Entra Agent ID introduces structured identity, governance, and protection for AI agents. It’s now in public preview with expanded management and security capabilities.
*   [AI Access Security Features](https://blog.admindroid.com/secure-ai-access-with-microsoft-entra-internet-access/) - Microsoft adds four AI-focused safeguards: prompt injection defense, network file filtering, shadow AI detection, and blocking unapproved MCPs. These capabilities help organizations use AI safely.
*   [New Microsoft 365 Agents](https://blog.admindroid.com/ai-agents-in-microsoft-intune/) - Three new agents streamline Intune admins’ work: Change Review Agent, Device Offboarding Agent, and Policy Configuration Agent. Each one automates specific operational and security tasks in Microsoft Intune.
*   [Microsoft Agent 365](https://blog.admindroid.com/microsoft-agent-365-unified-control-plane-to-manage-ai-agents/) - Agent 365 is the central hub for deploying, managing, and securing AI agents across the organization. It brings unified controls, monitoring, and insights for all agent activity.
*   [Work IQ](https://blog.admindroid.com/work-iq-in-microsoft-365/) - Work IQ powers Copilot with contextual knowledge about whom you are working with, the projects you’re involved in, your work patterns, and more. This enables more accurate, personalized, and meaningful assistance.  
    

Now, let’s shift gears and dive into what’s coming next!

## Microsoft 365 Upcoming Changes and Deprecations List:

  
Here is a list of changes categorized by month and year.  

*   December 2025 (Retirements: 6, New Features: 11, Enhancements: 8, Existing Functionality Changes: 3, Action Needed: 3)
*   Jan 2026 (Retirements: 6, New Features: 9, Enhancements: 6, Existing Functionality Changes: 1, Action Needed: 1)
*   Feb 2026 (Attention Needed: 4)
*   Mar 2026 (Attention Needed: 6)
*   Q2 2026 (Attention Needed: 9)
*   Q3 2026 (Attention Needed: 3)
*   Q4 2026 (Attention Needed: 3)

  

## December 2025

### Retirements

### Early-Dec 2025 – Retirement of “Favorite Contacts” in Microsoft Places

Microsoft will retire the Favorite Contacts feature in early December 2025. It will be replaced by the new Frequent Contacts logic used across other Microsoft 365 apps. So, users will no longer manage a favorites list in the Places app. Additionally, admins will lose the ability to control favorite contacts through the _Set-PlacesSetting -AllowConnectionList_ cmdlet.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1182693](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1182693)

### Early-Dec 2025 – Retirement of App Skills in Microsoft 365

The App Skills feature in Copilot for Excel, which helps users derive insights directly within spreadsheets, will be retired in early December 2025. Microsoft is introducing Agent Mode in Excel as a more capable replacement.

**Solution:** Use alternatives such as Microsoft Copilot Chat.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184407](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184407)

### Dec 8, 2025 – Retirement of TeamworkDevice (Beta) API in Microsoft Graph

Microsoft will retire the TeamworkDevice (beta) API used for managing room devices on Windows from Microsoft Graph.

**Solution**: Admins should now use the Teams Rooms Pro Management Portal (PMP) to manage Teams Rooms on Android, Teams Phones, and Teams Panels.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1183294](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1183294)

### Dec 2025 – Removal of the “Reuse Slides” Feature in PowerPoint

The Reuse Slides feature in PowerPoint helps users insert slides from other presentations. Microsoft plans to discontinue the Reuse Slides feature in PowerPoint for Window and Mac Desktops starting December 2025.

**Solution**: After this change, users will need to manually copy and paste slides between files.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1179161](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1179161)

### Late-Dec 2025 – End of Support for Teams on Android 8

By late December 2025, Microsoft will completely end all security updates and bug fixes for the Teams app on devices running Android 8. This change is part of Microsoft’s effort to transition users to newer Android versions that offer better performance, stability, and security. Although the app will continue to function on Android 8, no future enhancements or maintenance updates will be provided.

**Solution**: Upgrade to a device running Android 10 or later to continue receiving updates.

**_Ref_**: [http://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1181212](http://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1181212)

### Dec 31, 2025 – Retirement of Assignments and Courses ACEs in Viva Connections and SharePoint

To modernize Viva Connections, Microsoft will retire the Assignments and Courses adaptive card extensions (ACEs) and their SharePoint dashboard web parts for Education tenants. These SPFx components currently surface assignment and course information on the dashboard, and their removal aims to reduce redundancy and streamline the user experience. Also, the existing components will reach the end of support on June 30, 2026.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184647](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184647)

### New Features

### Late-Dec 2025 – Priority Cleanup in Purview Data Lifecycle Management

Microsoft is introducing a new Priority Cleanup feature in Purview Data Lifecycle Management. This allows admins to delete OneDrive and SharePoint content _before_ existing retention or hold periods expire, useful for items like Teams recordings and transcripts. The feature includes capabilities such as simulation mode, audit logs, and review workflows, but it is not enabled by default.

To ensure proper control and security, two roles are required:

*   A Priority Cleanup Admin to create the policy.
*   A Retention Management Admin to review and approve it.

**_Ref_**: [https://learn.microsoft.com/en-us/purview/priority-cleanup-exchange](https://learn.microsoft.com/en-us/purview/priority-cleanup-exchange)

### Early-Dec 2025 - Protection Against Tenant-owned Domain Impersonation in Team Chat

Microsoft Teams currently detects brand impersonation, and it will soon extend this capability to detect tenant-owned domain impersonation as well. In simple terms, when external collaboration is enabled and an external user initiates contact with someone in your organization, Teams will automatically verify whether the external user’s domain is trying to impersonate your organization’s domain.

*   For example, if your organization uses **_contoso.com_** and an external user tries to message you from a look-alike domain such as **_c0ntoso.com_,** Teams will flag it as a potential impersonation attempt.

Once detected, Teams will display a high-risk alert, prompting the user to review and confirm the contact before continuing the conversation. This protection will be enabled by default.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1187679](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1187679)

### Early - Dec 2025 – Maintain Accurate Presence in Teams on the Web

Microsoft Teams on the web currently switches a user’s status to “_Away_” when the browser tab becomes inactive. With the new update, Teams will detect overall device activity, not just tab activity. This ensures that if the user is actively working on the device, even if the Teams tab isn’t active; their presence remains “Available.” It will be rolled out to Chrome v94+ and Edge v114+ in the initial phase.

To use this feature, users need to enable “Keep my current status when I'm active outside of Teams on the web” setting in Teams (which is off by default). Once enabled, the browser will prompt users to grant permission to detect their activity.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184412](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184412)

### Early-Dec 2025 – Cost Estimator and Transparency Report for Data Security Investigations

Microsoft is adding new capabilities to improve cost visibility for Data Security Investigations (DSI):

*   **Lightweight Cost Estimator:** Helps model and forecast storage and compute costs based on investigation scenarios.
*   **Usage Dashboard Report:** Provides granular insights into billed storage and compute units, helping admins identify cost-saving opportunities.

These enhancements support pay-as-you-go billing, require no configuration changes, and will be enabled by default in Public Preview starting early December 2025.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1186360](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1186360)

### Dec 2025 – Automatically Set Work Location by Connecting to a Wi-Fi Network

Microsoft Teams will introduce a feature that automatically sets users’ work locations when they connect to the organization’s Wi-Fi or certain peripherals. This helps deliver location-based experiences without manual input. The feature will be disabled by default. Tenant admins will have the option to enable it and will require end-user consent to proceed.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=488800](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=488800)

### Dec 2025 – Integration of Insider Risk Management and Data Security Investigation

Microsoft Purview is integrating Insider Risk Management (IRM) with Data Security Investigation (DSI). Data security admins can now launch a pre-scoped DSI directly from an IRM case, simplifying investigations into risky user activity and enabling faster assessment of potential impact.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=501781](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=501781)

### Dec 2025 – Backup Activity Logs in Microsoft 365

Microsoft will begin tracking backup-related activities, such as backup policy changes and restore operations, directly within monitoring logs. This provides better visibility for troubleshooting, auditing, and monitoring.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=500019](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=500019)

### Dec 2025 – Actionable Email Notifications for Enhanced Incident Remediation

Microsoft will soon allow users to take direct actions from DLP email notifications. These actions include: Stop sharing files, delete files, apply labels, overriding the policy, reporting false positives, and unable to take action.

These actions apply to OneDrive and SharePoint files involved in a DLP policy match.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=464996](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=464996)

### Dec 2025 – PST Import Support in the New Outlook for Windows

The new Outlook for Windows will soon provide a feature to import email messages directly from .pst files (Outlook Data File) into user mailboxes, simplifying mailbox migration and recovery.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=485739](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=485739)

### Dec 2025 – ChatGPT Enterprise Connector Integration with Microsoft Purview

The ChatGPT Enterprise Connector will be integrated into the Microsoft Purview Compliance Portal, enabling administrators to collect, retain, and review prompts and responses from organizational ChatGPT usage.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=401125](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=401125)

### Early-Dec 2025 – eDiscovery (Premium): Support for Non-Microsoft 365 Data in Review Sets

Microsoft Purview’s eDiscovery (Premium) will soon support importing and reviewing non-Microsoft 365 data alongside Microsoft 365 content. A new upload option within review sets will allow investigators to bring external data into the same workspace. All imported content (Microsoft and non-Microsoft) can then be searched, viewed, and analyzed together for a unified review experience.

This feature will be available by default. It may impact how your organization manages eDiscovery workflows, so internal processes and team training should be updated to ensure smooth adoption and awareness of the new capability.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1176369](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1176369)

### Enhancements

### Dec 2025 - Microsoft Purview Compliance Portal: Sensitive Label Group Modernization

In the current model, sensitivity labels consist of two levels: parent labels and sublabels. Parent labels act only as containers, while sublabels are the ones actually applied to emails and documents. However, since parent labels still appear in the UI, even though they cannot be applied, they often create confusion.

To streamline the experience, Microsoft is replacing parent labels with Label Groupings. These groupings are designed solely for organizing and categorizing labels. Users will now directly select the applicable labels instead of parent-level groupings**.**

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=386900](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=386900)

### Dec 11, 2025 - Changes to Entra Identity Protection Alert Settings in Defender XDR

Microsoft Defender XDR is adding more granular configuration options for identity-related alerts from Entra ID Protection to improve clarity and reduce alert fatigue. Alert ingestion will now be based directly on risk levels, allowing admins to choose whether to ingest only High-risk detections, High + Medium, or all detections.  
  
The default setting is shifting from ingesting all severities to only High-risk alerts, which may reduce alert volume unless adjusted. You’ll also see updated UI text and visuals that make the settings easier to understand and manage. It will be rolled out in Public Preview starting Dec 11, 2025.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1190195](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1190195)

### Dec 2025 – Organizational Messages Now Support Hybrid-Joined Devices

Microsoft is expanding Organizational Messages to support Entra ID Hybrid-joined devices in addition to fully cloud-joined devices. This allows organizations to deliver customized messaging to a wider range of enrolled endpoints.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=503564](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=503564)

### Dec 2025 – Update to Insider Risk Management Limits

Microsoft Purview Insider Risk Management is increasing key limits to support larger detection workloads:

*   **Variants per indicator:** 3 → 10
*   **Total variants across all indicators:** 100 → 400
*   **Items per detection group:** 200 → 500

These updates enhance scalability and allow for more robust insider risk scenarios.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=518291](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=518291)

### Dec 2025 – Multi-Selectable DLP Policies as Insider Risk Management Triggers

  
Currently, Insider Risk Management (IRM) policies can only use one DLP policy as a triggering event. With this update, admins will be able to select multiple DLP policies as triggers in an IRM policy, giving them more flexibility and stronger coverage.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=493757](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=493757)

### Dec 2025 – SMTP DANE with DNSSEC Support for Exchange Online

Microsoft is adding inbound support for SMTP DANE with DNSSEC to Exchange Online environments in GCC High and DoD. This security enhancement strengthens email validation and encryption for government cloud users.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?featureid=361914&searchterms=361914](https://www.microsoft.com/en-in/microsoft-365/roadmap?featureid=361914&searchterms=361914)

### Dec 2025 – Microsoft 365 Backup Service Expands to GCC Tenants

The Microsoft 365 Backup service will become available for GCC organizations beginning December 2025.  
This rollout will provide GCC customers with the ability to restore their Microsoft 365 data in cases of ransomware attacks, accidental deletions, or other critical loss scenarios.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=494517](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=494517)

### December 2025 – Data Lifecycle Management for Microsoft Planner

Microsoft will introduce Data Lifecycle Management capabilities to Microsoft Planner.  
Admins will be able to create retention policies that safeguard Planner content, ensuring compliance with organizational data governance standards.

**Ref:** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=486828](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=486828)

### Existing Functionality Changes

### Dec 2025 – Microsoft Teams App Usage Report Renamed and Redesigned as Integrated Apps Usage Report

The Teams app usage report is being renamed and redesigned as the Integrated Apps usage report, featuring new charts and metrics. It provides insights into app usage across Teams, Outlook, Microsoft 365 apps, and Copilot extensions. The data is organized by Publishing Type, Host Product, and Platform, with detailed views on app and user activity.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=410248](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=410248)

### Dec 2, 2025- Update Firewall Rules for Intune via Azure Front Door

As part of Microsoft’s Secure Future Initiative (SFI), starting on or after December 2, 2025, Microsoft Intune network endpoints will use Azure Front Door IP addresses. Since Basic Mobility and Security for Microsoft 365 relies on Intune, customers using firewall allowlists based on IP addresses or service tags must update them.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1150664](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1150664)

### Dec 2025 – Changes to SharePoint Agent Usage Statistics

Microsoft is changing the way SharePoint agent usage statistics are displayed. Instead of showing usage per site, all usage data across the tenant will now be aggregated and shown together to the tenant administrator.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=480729](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=480729)

### Action Required

### Dec 7, 2025 – Retirement of UKG and Blue Yonder Managed Connectors in Teams Shifts

The managed connectors that sync workforce management data from UKG and Blue Yonder into Teams Shifts will be retired on December 7, 2025. These connectors currently support scheduling, time-off requests, and shift swaps.

**Solution:**

*   UKG customers: Transition to the UKG Flow app.
*   Others: Build custom integrations to maintain synchronization with Teams Shifts.

**Ref**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1166868](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1166868)

### Dec 7, 2025 – Retirement of Visio Data Visualizer Add-in for Excel

Starting December 8, 2025, the Visio Data Visualizer add-in will be removed from the Excel add-in store, templates, and ribbon. Users will no longer be able to create new diagrams using the add-in.

**Solution:** Disable the Data Visualizer add-in and encourage users to save existing diagrams as Visio (.vsdx) files.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1182535](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1182535)

### End of 2025 – Retirement of Mailbox Audit Log Cmdlets in Exchange Online

By late December 2025, Microsoft will retire the Search-MailboxAuditLog and New-MailboxAuditLogSearch cmdlets in Exchange Online.  
  
**Solution**: Use Search-UnifiedAuditLog instead.  
**_Ref_**: [https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310](https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310)

## Jan 2026

### Retirements

### Early-Jan 2026 – Retirement of Themes in Viva Engage User Settings

Microsoft will remove the ability for users to personalize their Viva Engage interface using themes. This decision supports accessibility improvements and aligns with the upcoming centralized admin-managed theme experience. Also, existing themes will be removed, and users will be reverted to the default Viva Engage theme.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1162958](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1162958)

### Early-Jan 2026 – Retirement of Activity-Based Authentication Timeout for Outlook on the Web

Microsoft will retire the Activity-Based Authentication Timeout setting for Outlook on the Web (OWA) starting in early January 2026. This feature currently signs users out after a period of inactivity.

**Solution:** Configure Idle session timeout to maintain similar session control behavior.

**_Ref:_** [https://support.microsoft.com/en-us/topic/activity-based-authentication-timeout-for-outlook-on-the-web-in-office-365-0c101e1b-020e-69c1-a0b0-26532d60c0a4](https://support.microsoft.com/en-us/topic/activity-based-authentication-timeout-for-outlook-on-the-web-in-office-365-0c101e1b-020e-69c1-a0b0-26532d60c0a4)

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

Existing App-V packages will continue to function, but starting January 13, 2026, new App-V packages for Microsoft 365 Apps can no longer be created .

**Solution**: Shift to Click-to-Run deployment for better performance and reliability.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1183012](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1183012)

### Jan 31, 2026 – Retirement of IDCRL Authentication in SharePoint and OneDrive

Microsoft is retiring the legacy IDCRL (Identity Client Run Time Library) authentication protocol in SharePoint and OneDrive for Business as part of the Secure Future Initiative. Legacy authentication will be blocked by default beginning January 31, 2026, with modern OpenID Connect and OAuth protocols taking precedence.

**Solution:** A temporary re-enablement option is available until April 2026. Organizations should transition to modern authentication as soon as possible.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184649](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184649)

### New Features

### Jan 2026 - SharePoint File-Level Archiving Coming to Microsoft 365 Archive

Microsoft 365 Archive will support file-level archiving in SharePoint, enabling more granular retention and storage control. This feature enters the public preview in January 2026.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=477371](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=477371)

### Jan 2026 – DLP Policy Tip Support Coming to Outlook for Mac

Microsoft is bringing Data Loss Prevention (DLP) policy tip support to Outlook for Mac. This helps users avoid accidental data leakage by showing policy tips when sensitive data is detected in emails. Users will be able to identify non-compliant recipients and take corrective actions, including overriding the policy when permitted.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=484854](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=484854)

### Jan 2026 – Rule-Based Management for Microsoft 365 Third-Party Apps in Teams

Microsoft is adding a rule-based configuration option in the Teams admin center to simplify app management. With this update, administrators can control Microsoft 365 certified third-party apps in bulk from the _Org-wide settings_ section. Also, app availability can be determined using publisher information and permission scopes.  

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1085133](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1085133)

### Jan 2026 – Chat With Anyone in Teams Using an Email Address

Teams will soon allow users to chat with external contacts using their email addresses, even if those contacts do not have a Teams account. External users will receive an invitation to join as guests. This experience follows your organization’s B2B Guest policy and will be enabled by default.

Admins can disable by setting UseB2BInvitesToAddExternalUsers as false in _Set-CsTeamsMessagingPolicy_ cmdlet.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1182004](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1182004)

### Mid-Jan 2026 – New Copilot Security Controls in Microsoft Admin Center

Microsoft is adding new security controls to help admins manage Microsoft 365 Copilot usage more effectively. These capabilities include visibility into data oversharing, remediation options, and the ability to apply DLP policies directly within the admin center. General availability begins mid-January 2026.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1182689](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1182689)

### Mid-Jan 2026 – Apps Now Supported in Microsoft Teams Shared Channels

Microsoft will now allow apps including bots and tabs to be added to shared channels, expanding beyond the previously limited tab support. Apps must be configured per channel, as team-level app settings do not apply to shared or private channels. This capability will be enabled by default.

Also, new admin settings will also be introduced to control who can add apps in shared channels.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1168294](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1168294)

### Mid-Jan 2026 – SharePoint Branding Experience via PowerShell

Tenant admins will be able to centrally manage SharePoint site branding using PowerShell. This includes enforcing consistent branding, applying enterprise themes, disabling custom branding on specific sites, and auditing branding changes across the organization.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=503563&searchterms=526794](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=503563&searchterms=526794)

### Late-Jan 2026 – Admin Controls for External Collaboration in Teams Admin Center

Microsoft is simplifying external collaboration settings across chats, calls, meetings, Teams, and shared channels. A new interface provides three predefined collaboration modes:

*   **Open:** Allows chats, calls, and meetings with all external domains and Teams personal accounts via federation or external access.
*   **Controlled:** Matches the current default for enterprise and EDU tenants and blocks shared channel collaboration.
*   **Custom:** Allows complete customization of external collaboration settings across all Teams surfaces.

Also, general availability begins late January 2026.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1183006](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1183006)

### Late-Jan 2026 – Insider Risk Management User Analytics in Microsoft Purview

Microsoft Purview will introduce User Activity Summaries within Insider Risk Management (IRM) to help analysts better assess risk context during incident reviews. These insights consolidate data from multiple security and compliance solutions, providing a unified view of user behavior and potential policy violations.

Insights will be available in:

1.  Microsoft Purview Data Loss Prevention alerts.
2.  Microsoft Defender user entity pages and alerts.
3.  Communication Compliance policy reports.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1045212](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1045212)

### Existing Functionality Changes

### Jan 2026 – Explicit Consent Required for Recording and Transcription in Teams 1:1 Calls

Microsoft Teams is extending the consent requirement for recording and transcription to include 1:1 calls. Admins can enforce this behavior using a new Teams Calling policy setting. When recording or transcription starts, the other participant’s camera, microphone, and screen sharing will automatically turn off until they provide explicit consent.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=503295](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=503295)

### Early-Jan 2026 - Upcoming Change to Teams Desktop Client on Windows

To improve the calling performance and startup timing, Microsoft Teams Desktop for Windows will run a new process “teams\_modulehost.exe,” which will handle the calling features separately. So, this child process will handle the calling stack separately from the main process (ms-teams.exe).

So, admins need to update the endpoint and security software to allow this new process.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1189656](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1189656)

### Enhancements

### Early-Jan 2025 – Enhancements to Quarantine View in Microsoft Defender for Office 365

Microsoft is improving the quarantine experience with:

*   Message display per individual recipient instead of grouping.
*   The _ReleaseToAll_ parameter will now target each mailbox individually.
*   Backend performance enhancements for better reliability and consistency.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1171845](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1171845)

### Early-Jan 2026 – Modern Access Request and Access Denied Pages

Microsoft is rolling out modernized Access Request and Access Denied pages across Microsoft 365, with updated visuals, clearer messaging, and subtle animations. This helps users understand permissions and request access more easily.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1188599](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1188599)

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

### Late-Jan 2026 – Retention Based on “Last Accessed” for OneDrive and SharePoint

Microsoft is enhancing Data Lifecycle Management by introducing a new “When items were last accessed” condition for retention policies. This feature allows admins to manage and automatically clean up OneDrive and SharePoint content based on access history, improving storage hygiene and optimizing Microsoft 365 Copilot responses.  

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442)

### Early-Jan 2026 - Policy Alerts Improvements in Microsoft Purview Communication Compliance

Communication Compliance is enhancing policy alert customization. Admins will have the ability to set the alert frequency for each policy and adjust the email alert frequency and recipients directly within the policy creation wizard, via the new alerts page. This update will be generally available from early-Jan 2026.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920304](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920304)

### Action Required

### Jan 4, 2026 – Outlook for Android to Require Android 10.0 or Higher

Starting January 5, 2026, the Outlook for Android app will require devices to run Android 10.0 or later to continue receiving updates, security patches, and new features. Users on earlier Android versions will retain app access temporarily but will not receive further updates.

**Solution:** Advise users to upgrade their Android OS to version 10.0 or higher by Jan 4 to ensure ongoing support.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1163756](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1163756)

## Feb 2026 (Attention Needed: 4)

### Feb 2026 - Content Security Policy in SharePoint Online

Microsoft introduced Content Security Policy (CSP) in SharePoint as a browser-level security standard that controls which scripts, styles, images, and other resources a site is allowed to load. If a resource isn’t explicitly approved, the browser blocks it. This helps protect SharePoint sites from threats like cross-site scripting (XSS), clickjacking, and other code injection attacks.

**_Ref_**: [https://techcommunity.microsoft.com/blog/spblog/sharepoint-online-content-security-policy-csp-enforcement-dates-and-guidance/4472662](https://techcommunity.microsoft.com/blog/spblog/sharepoint-online-content-security-policy-csp-enforcement-dates-and-guidance/4472662)

### Feb 2026 – Jailbreak and Root Detection in Microsoft Authenticator App

Microsoft will enhance the Microsoft Authenticator app with jailbreak and root detection capabilities for Entra credentials on both iOS and Android platforms. Once this feature is active, Entra credentials on jailbroken or rooted devices will stop functioning. And any existing ones will be automatically wiped for security reasons.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1179154](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1179154)

### Feb 2026 – Exchange Online Moderation Approvals via Actionable Messages

The Exchange Online Moderation feature allows moderators to approve or reject messages before they’re sent. Currently, this can only be done in Outlook Desktop or Outlook on the web. With the new update using Actionable Messages, moderators can now approve or reject moderated messages from any Microsoft email client, including Outlook for Windows, Mac, iOS, and Android.  
  
**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=492743](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=492743)

### Feb 28, 2026 - Deprecation of Reporting Web Service Support for Exchange Online Message Trace Data

The Reporting Web Service for Message Trace will begin to be phased out by Feb 28, 2026.

**Solution**: Use the new Message Trace PowerShell cmdlets instead.

**_Ref_**: [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1092458](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1092458)

### Late-Feb 2026 – Soft Deletion and Restoration of Cloud Security Groups

Microsoft is introducing soft deletion support for cloud security groups. Deleted groups can be restored for up to 30 days, along with their settings, membership, and properties. Audit logs will track deletion, restoration, and hard deletion events.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1183299](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1183299)

### March 2026 (Attention Needed:6)

### March 2026 - Long-term Retention Period for Microsoft 365 Backup

Admins will be able to configure longer-term retention for Microsoft 365 backups, allowing data storage beyond one year. This feature will be available in preview by March 2026.  

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=481834](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=481834)

### Mar 2026 - Microsoft Purview Information Barriers v2 Now Available for New Customers

Information Barriers v2 (IB v2) will be available by default for all new onboarding tenants. It supports up to 5,000 segments, allows users to be in up to 10 segments, and offers flexible user discoverability while enforcing IB policies.

Existing IB v1 tenants must opt in to upgrade to IB v2 to use these new capabilities. This update applies only to IB v1 customers.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=402516](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=402516)

### Mar 2026 - New DLP Rule Action: Trigger Power Automate Workflows in Microsoft Purview

Starting March 2026, Microsoft Purview will support a new Data Loss Prevention (DLP) rule action that triggers custom Power Automate workflows when a policy match occurs.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=380721](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=380721)

### Mar 2026 – Decoupling Policy Tips & Email Notifications for SharePoint and OneDrive DLP

Currently, enabling email notifications in DLP policies for SharePoint and OneDrive also forces policy tips to be enabled, and vice versa. With this update, admins will be able to configure policy tips and email notifications independently, providing more flexibility in how alerts are managed.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=396575](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=396575)

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

## Q2 2026 (Attention Needed: 9)

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

### June 2026 – Power Automate Integration with Data Lifecycle Management

Power Automate will integrate with Data Lifecycle Management, enabling administrators to automate actions when items reach the end of their retention period. For instance, organizations can design flows to initiate approval workflows before permanently deleting data.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=117523](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=117523)

### June 2026 – New Retention Actions in Power Automate Integration

As part of Power Automate’s integration with Microsoft Purview Records Management, new retention actions will roll out in December 2025. At the end of a retention period, admins will be able to:

*   Relabel files or emails
*   Apply retention labels to SharePoint files
*   Delete items across SharePoint, OneDrive, and Exchange

All retention actions will be logged in the Microsoft Purview Audit log for tracking.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=117425](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=117425)

### Late-June 2026 – Integration of Adaptive Protection with Data Lifecycle Management

Microsoft plans to make the Adaptive Protection and Data Lifecycle Management (DLM) integration generally available by late June 2026. This integration allows administrators to retain or restore items deleted by high-risk users, providing better safeguards against insider threats and accidental data loss.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110)

### End of June 2026 – Unified Management of Teams Apps Across Microsoft 365

Microsoft is finalizing the rollout of Unified App Management for Teams, Outlook, and the Microsoft 365 app. This update simplifies app management by consolidating the separate admin experiences into a single, centralized management interface. The unified experience will be fully available to all organizations by the end of June 2026.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC796790](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC796790)

## Q3 2026 (Attention Needed: 3)

### July 14, 2026- InfoPath 2013 Client and InfoPath Forms Services in SharePoint Online Will be Retired

  
  
InfoPath Client 2013 will reach the end of its extended support period on July 14, 2026, and to keep an aligned experience across Microsoft products, InfoPath Forms Service will be retired from SharePoint Online.

**Solution:** To understand the usage of InfoPath within your organization, you can utilize the [Microsoft 365 Assessment tool](https://aka.ms/assessment/infopath) to scan your tenant and analyze InfoPath usage. If you are currently using InfoPath, you can initiate the migration process to modern alternatives such as Power Apps, Power Automate, or Forms.

**_Ref_**: [https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190](https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190)

### July 2026 - SharePoint Alerts Will be Fully Retired

Microsoft will discontinue support for SharePoint Alerts. Existing alerts can no longer be modified and will eventually stop functioning.

**Solution:** Microsoft recommends migrating SharePoint Alerts to Power Automate or SharePoint Rules. Use the Microsoft 365 Assessment tool to review alerts and plan the move.

**_Ref_**: [https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f](https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f)

### Sep 17, 2026 - Retirement of Legacy Education LTI Tools

Microsoft will retire the legacy Education LTI tools including Teams Assignments, OneDrive, OneNote Class Notebook, and Reflect on September 17, 2026. These will be replaced by the new Microsoft 365 LTI unified tool, and users and admins will need to transition to this updated experience.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1160188](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1160188)

## Q4 2026 (Attention Needed: 3)

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