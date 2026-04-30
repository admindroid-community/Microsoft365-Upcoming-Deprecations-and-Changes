# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. 🌟 We’ll shed light on the features and products that are undergoing transformations or bidding farewell. Whether you’re a system administrator 🧑‍💻 managing the Microsoft 365 environment or an avid user 🙋‍♂️ staying ahead of the curve, this blog will provide invaluable insights and actionable recommendations.

🚀Discover the **key changes, deprecations,** and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we’ve got you covered! Make informed decisions and ensure a smooth transition.⚡️

## Microsoft 365 Upcoming Changes and Deprecations List:

Here is a list of changes categorized by month and year.

*   May 2026 (Retirements: 9, New Features: 14, Enhancements: 3, Existing Functionality Changes: 3, Action Needed: 2, Live Now: 2)
*   June 2026 (Retirements: 5, New Features: 13, Enhancements: 1, Existing Functionality Changes: 2, Action Needed: 2)
*   July 2026 (Attention Needed: 15)
*   August 2026 (Attention Needed: 2)
*   September 2026 (Attention Needed: 5)
*   Q4 2026 (Attention Needed: 9)
*   2027 (Attention Needed: 6)

## May 2026  

Retirements: 9 | New Features: 14 | Enhancements: 3 | Existing Functionality Changes: 3 | Action Needed: 2 | Live Now: 1

### Retirements

### May 1, 2026 – Retirement of IDCRL Authentication in SharePoint and OneDrive

As part of the Secure Future Initiative, Microsoft is deprecating the legacy IDCRL (Identity Client Run Time Library) authentication protocol in SharePoint and OneDrive for Business. Legacy authentication will be permanently blocked beginning May 1, 2026, with modern OpenID Connect and OAuth protocols taking precedence.

**Solution:** Organizations should transition to modern authentication as soon as possible.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184649](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184649)

### May 1, 2026 - Retirement of Agent Management Blades in Microsoft Entra

The “Agent registry” and “Agent collections” blades in the Entra admin center are currently used to view and manage agents in Microsoft 365. To simplify agent management through a unified platform, Microsoft is retiring these blades, along with the existing Agent Registry Graph API.

**Solution:** Admins should use the [Agent 365](https://blog.admindroid.com/microsoft-agent-365-unified-control-plane-to-manage-ai-agents/) page, which serves as a unified platform to view, discover, and manage agents. Admins will also need to adopt the new API (yet to be announced) for agent registration.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1275311](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1275311)

### Early-May 2026 - Retirement of Select IaaS and PaaS Detections in Defender for Cloud Apps

Microsoft is retiring a small set of Infrastructure as a Service (IaaS) and Platform as a Service (PaaS) threat detections within Microsoft Defender for Cloud Apps. This change reflects a refined focus on identity-related threats across Microsoft Entra, on-premises, and SaaS environments.

*   Affected alerts and behaviors (e.g., VM creation/deletion, CloudTrail changes, storage deletions) will no longer be generated.
*   Related built-in policies will be removed from the Policy management page.
*   Existing alerts remain available in Alerts, Incidents, and Advanced Hunting for historical analysis.
*   Links to removed policies will indicate they are deleted.

**Solution:** Review and update any operational processes, playbooks, or documentation that rely on these detections.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1254554](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1254554)

### Early-May 2026 - Retirement of Copilot-generated Recaps in Microsoft Loop

As Microsoft continues to invest in other Copilot capabilities, it plans to retire the Copilot-generated recap feature in Loop starting early May 2026. After this change, users will no longer be able to generate recaps using Copilot and will need to manually create and edit recaps within Loop. As a result, the recap entry point will no longer display the “with AI” label or sparkle icon.  
  
This change is irreversible and enabled by default.

**_Ref_**: [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1267976](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1267976)

### Early-May 2026 – Microsoft Teams Locks CAPTCHA Policy for Meeting Join

Microsoft Teams will lock the _“Require verification by participants (CAPTCHA)”_ policy starting early May 2026, preventing admins from enabling it. This marks the beginning of CAPTCHA retirement, with a transition to a default-on bot detection capability that requires organizer approval for external bots.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1262588](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1262588)

### May 9, 2026 - Retirement of Older Microsoft Defender for Endpoint Mobile App Versions

The Microsoft Defender for Endpoint mobile app is receiving continuous updates aimed at strengthening its security. These security enhancements are only available in app versions released on or after February 2026.

To ensure all devices remain protected with the latest security updates, Microsoft will retire older versions of the Defender for Endpoint mobile app released prior to February 2026 on both iOS and Android. After May 9, 2026, users relying on older versions will no longer be able to connect to Microsoft Defender cloud services or receive security updates.

**Solution**: Upgrade to the supported versions, such as:

*   Android: version 1.0.8605.0101
*   iOS: version 1.1.73270102

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1276511](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1276511)

### May 15, 2026 – Retirement of External Access Tokens for Actionable Messages

External access tokens for actionable messages will be retired on May 15, 2026, and organizations must transition to Microsoft Entra authentication to ensure continued functionality. After this date, any actionable message relying on external tokens will fail. This change strengthens security and aligns with modern identity standards.

**Solution:** Organizations using actionable messages should review their current implementations and update all integrations to Microsoft Entra authentication before the deadline to avoid disruptions.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1189663](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1189663)

### May 18, 2026 – Microsoft to Block InfoPath Form Publishing in SharePoint Online

In preparation for the full retirement of InfoPath Forms Services on July 14, 2026, Microsoft will prevent the publication of any new or updated InfoPath forms starting May 18, 2026. This change applies to all Microsoft 365 environments, including Government Clouds (GCC, GCC High, and DoD). Existing published forms will remain accessible but cannot be modified or republished.

**Solution:** Run the Microsoft 365 Assessment tool to identify InfoPath usage and migrate to Power Apps, Power Automate, or Microsoft Forms before the retirement date.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1255407](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1255407)

### May 25, 2026 - Complete Retirement of the Outlook Lite App

To reduce overlap and focus development efforts on Microsoft Outlook Mobile, Microsoft will retire the Outlook Lite app for mobile. The complete retirement is scheduled for May 25, 2026. After this date, users may still be able to launch the app, but mailbox access will be disabled.

**Solution:** Move to the Microsoft Outlook Mobile app, which offers full mailbox functionality along with enhanced compliance capabilities.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1276508](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1276508)

### New Features

### May 1, 2026 – General Availability of Microsoft 365 E7 Frontier Suite

Microsoft has announced the official launch of [Microsoft 365 E7](https://blog.admindroid.com/microsoft-365-e5-vs-e7/), a new premium licensing tier arriving May 1, 2026. Priced at $99 per user per month, the E7 suite is designed to securely govern AI agents with advanced security and compliance controls at an enterprise level.

E7 serves as a comprehensive bundle, unifying the existing Microsoft 365 E5 foundation with Microsoft 365 Copilot, the new Agent 365 governance platform, and the full Microsoft Entra Suite. This consolidation offers approximately 15% savings compared to purchasing these components individually.

**_Ref:_** [https://partner.microsoft.com/en-US/blog/article/agent-365-announcement?wt.mc\_id=mxhr8c6r8v](https://partner.microsoft.com/en-US/blog/article/agent-365-announcement?wt.mc_id=mxhr8c6r8v)

### Early-May 2026 – Brand Impersonation Protection for Teams Calling

A new feature called “Brand Impersonation Protection for Teams calling” will be introduced. This feature detects and warns users about fraudulent external callers impersonating trusted organizations.

Users will see a warning and can choose to accept, block, or end the call. The feature will be enabled by default and will evaluate incoming VoIP calls from first-time external callers.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1219793](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1219793)

### May 2026 – Microsoft Entra ID Account Recovery

A new [Entra ID Account Recovery](https://blog.admindroid.com/self-service-account-recovery-with-identity-verification-in-entra-id/) feature is being introduced to help users recover access to organizational accounts if all registered authentication methods are lost. Unlike a standard password reset, this feature securely verifies the user’s identity and re-establishes trust before allowing new authentication methods to be set up.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=529856](https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=529856)

### May 2026 – Sensitivity Label Inheritance for Teams Meeting Recordings

Microsoft Teams meeting recordings will automatically inherit the meeting’s sensitivity label when label inheritance is enabled. This ensures that access controls, data protection policies, and agent responses based on meeting transcript respect the meeting’s sensitivity classification end to end.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=557178](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=557178)

### May 2026 – Chat With Anyone in Teams Using an Email Address

Teams will soon allow users to chat with external contacts using their email addresses, even if those contacts do not have a Teams account. External users will receive an invitation to join as guests. This experience, which will be in General availability follows your organization’s B2B Guest policy and will be enabled by default.

Admins can disable chat with anyone using an email address by setting UseB2BInvitesToAddExternalUsers as false in _Set-CsTeamsMessagingPolicy_ cmdlet.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1182004](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1182004)

### May 2026 – Automate Microsoft Copilot Agents Lifecycle Management

  
Microsoft will enable admins to define rules for Copilot agent lifecycle management. Admins can configure automation for various scenarios, such as:

1.  Automatically blocking risky agents
2.  Automatically deleting inactive agents
3.  Automatically reassigning ownerless agents to their managers

This capability helps streamline governance and ensures better control over Copilot agents throughout their lifecycle.  
**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=481518#Roadmap](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=481518#Roadmap)

### May 2026 – Integration of Viva Engage Communities in Microsoft Teams

Viva Engage communities will be integrated into Microsoft Teams, enabling discoverable conversations, unified navigation, synced memberships, and enhanced admin controls. The feature is enabled by default, and administrators can disable it if required.

It is available to all Microsoft Teams customers with a standard Microsoft 365 and Teams license, with no additional licensing required.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1218423](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1218423)

  

### Early-May 2026 – New SharePoint Experience Introduced with Registered Navigation and AI Enhancements

  
A [new SharePoint experience](https://blog.admindroid.com/new-sharepoint-experience-in-microsoft-365/) is being introduced with a streamlined design and better navigation to help users discover content, publish information, and build solutions more efficiently. The update also includes AI-assisted capabilities, which require a Microsoft 365 Copilot license.  
  
This experience introduces a redesigned SharePoint app bar with options such as Discover, Publish, Build, OneDrive, and Home. It also brings refreshed pages, news, libraries, and lists to improve content visibility while preserving existing site branding. The targeted release is scheduled to begin in early May 2026.  
  
**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1240699](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1240699)

  

**Early-May 2026 – Create and Edit SharePoint Pages with Copilot-Powered AI**  
  
Microsoft is introducing Copilot-powered AI for creating and editing SharePoint pages, enabling admins and content authors to produce high-quality pages more efficiently. With a Copilot license, users can leverage natural language prompts to create, refine, and update page content through an AI-powered authoring panel.  
  
**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1282683](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1282683)

  

### Early-May 2026 – Auto-Enabling Passkey Profiles

  
Starting May 2026, Microsoft Entra ID introduces passkey profiles and synced passkeys to General Availability (GA) for tenants with Passkeys (FIDO2) enabled. This update brings a new passkeyType property, allowing admins to configure device-bound, synced, or both types of passkeys, along with support for group-based configurations.

Tenants that do not opt in during the rollout window will be automatically migrated to a default passkey profile. Existing configurations will be carried over, and no new authentication methods will be enabled.

  
**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1221452](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1221452)

  

### Mid-May 2026 – Microsoft Entra: Passkeys in Registration Campaigns

  
Microsoft previously announced support for passkeys (FIDO2) in Microsoft Entra Registration Campaigns. The latest update confirms that passkeys will continue to be a supported and prioritized authentication method. They will remain available in the Enabled state and will also be introduced under the Microsoft-managed state for eligible tenants.

As part of this update, Microsoft will automatically update certain campaign settings and start prompting users to register passkeys during sign-in after completing MFA.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1279092](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1279092)

### Mid-May 2026 – New Exchange Online PowerShell Cmdlet to Change Meeting Organizer

Beginning mid-May 2026, Exchange Online introduces a new PowerShell cmdlet to change meeting organizer for single meetings or recurring series. This helps maintain continuity during offboarding or role changes, without requiring attendees to respond again to the meeting.

Once transferred, the new organizer gains full control of the event, including recurrence, description, and attendees. Meetings for internal attendees are updated silently, while external attendees receive updated invites and must accept again.

The feature is enabled by default, preserves meeting history, and future support is planned in Outlook and Teams interfaces.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1227623](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1227623)  

### Late–May 2026 – AI in SharePoint Using Custom Skills

  
Custom AI skills are being introduced in SharePoint Online, allowing users to build and reuse structured AI tasks saved as Markdown files within the Agent Assets library. SharePoint AI can automatically identify and apply relevant skills based on a user’s query, or users can manually invoke a skill by name.

With this capability, users can guide AI to perform routine tasks, such as reviewing documents or organizing content in a consistent way without the need for code or external integrations. This feature is enabled by default, does not include a tenant-level toggle, and will reach general availability by late May 2026.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1269209](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1269209)

### Late-May 2026 – Enhanced Group Targeting for Sensitivity Label Policies in Microsoft Purview

  
Microsoft is introducing enhanced targeting capabilities for sensitivity label policies in Microsoft Purview. Admins will be able to exclude modern Microsoft 365 groups and include dynamic, non-mail-enabled security groups when assigning labels. This enhancement provides greater flexibility and precision in policy targeting. The feature is about to reach general availability by late May 2026.  
  
**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=558685](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=558685)

### Enhancements

### May 2026 – Insider Risk Management for AI Agents

As AI agents become more common in Microsoft 365, associated risks also continue to rise. Microsoft will extend Insider Risk Management to cover AI agents, enabling admins to define policies specifically for agent-driven activities. This enhancement helps detect, flag, or block risky behaviors when AI agents access sensitive data or perform high-risk actions across platforms like Copilot Studio, Azure AI Foundry, and Agent 365.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=516032](https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=516032)

### May 2026 – Hard Delete Configuration for SharePoint and OneDrive in Purview Priority Cleanup Policies

Microsoft Purview will allow admins to configure hard deletion in priority cleanup policies for SharePoint and OneDrive content, enabling items to bypass recycle bins during cleanup.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=558343](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=558343)

### Late-May 2026 – Retention Based on “Last Accessed” for OneDrive and SharePoint

Previously, retention policies could delete content based on conditions such as ‘_When items were created’_ or ‘_When items were last modified’_. Microsoft is now enhancing Data Lifecycle Management by introducing a new _“When items were last accessed”_ condition for retention policies.

This feature allows admins to manage and automatically clean up OneDrive and SharePoint content based on access history. It improves storage hygiene and helps optimize Microsoft 365 Copilot responses.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442)

### Existing Functionality Changes

### May 2026 - Windows Autopatch to Enable Hotpatch Updates by Default for Supported Intune Devices

Starting May 2026, Windows Autopatch will enable hotpatch updates by default for eligible Intune devices, delivering security updates without requiring restarts. Devices must meet prerequisites like enabling Virtualization-based Security (VBS). Restarts will occur only during baseline months, and admins can opt out using settings available from April 2026.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1248388](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1248388)

### Early-May 2026 – OneDrive Files Deleted from the Cloud will no Longer Appear in the Local Recycle Bin

Currently, when a synced file is deleted from OneDrive via the web, it is sent to both the SharePoint/OneDrive Recycle Bin and the local device’s Recycle Bin or Trash. While this may assist with recovery, it also consumes local disk space and can trigger unnecessary re-downloads and re-sync operations during restoration.

Microsoft is now updating this behavior. Starting early - May 2026, files deleted from OneDrive through the web or browser will no longer appear in the local Recycle Bin on synced devices. These files can be restored only from the OneDrive or SharePoint Recycle Bin.

**Note**: Cloud-only files will remain unaffected. Files deleted locally on a device will continue to appear in the local Recycle Bin or Trash as they do today.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1269861](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1269861)

### Mid-May 2026 - Microsoft Purview eDiscovery: Naming and Description Fields will Restrict Certain Special Characters

Microsoft Purview eDiscovery will restrict certain special characters, such as “+, =, @, /, and \*” in naming and description fields for new or edited cases, holds, searches, and review sets.  
  
If users include these characters, they will be prompted to remove them from the fields. Existing names and descriptions will remain unchanged until the user chooses to edit them.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1282562](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1282562)

### Action Required

### May 15, 2026 – Update Browsers for Microsoft Teams Web Access

Microsoft Teams on the web will require support for modern browser standards, including ECMAScript 2022 (ES2022). Users accessing Teams through unsupported browsers will see reminder banners until May 14, 2026, after which access will be blocked starting May 15, 2026.

This change is enabled by default and does not impact Teams desktop or mobile clients. Unsupported browsers may cause sign-in interruptions due to Conditional Access policy enforcement.

**Solution:** Ensure users access Microsoft Teams on the web using browser versions that support ECMAScript 2022 (ES2022).

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230888](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230888)

### May 18, 2026 – Retirement of Office 365 Connectors in Microsoft Teams

The retirement of Office 365 Connectors in Microsoft Teams has been finalized, with full decommissioning planned from May 18, 2026.

**Solution:** Plan and complete the transition from Office 365 Connectors to Workflows webhooks before the deadline to avoid disruption.

**_Ref:_** [https://devblogs.microsoft.com/microsoft365dev/retirement-of-office-365-connectors-within-microsoft-teams/](https://devblogs.microsoft.com/microsoft365dev/retirement-of-office-365-connectors-within-microsoft-teams/)

### Live In May

This update was released in April and is now available for you to start using.

### Modernized Change Management for Microsoft 365

Microsoft started rolling out a modernized change management model in mid-April 2026, giving IT teams greater control over how and when updates are adopted. It introduces flexible release audiences: Frontier (early access), Standard (default), and Deferred (30-day delay) to better align with organizational readiness and governance needs.

Message center communications have also been enhanced with more structured and actionable updates, helping admins clearly understand impact, required actions, and compliance considerations. In addition, AI-powered insights are now available through the Microsoft MCP Server, enabling natural language access to trusted roadmap, Message center, and service health data.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1282306](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1282306)

## June 2026

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

**Solution:** Migrate to Teams town halls and updated Teams meeting Graph APIs, and update workflows or applications that depend on the _isBroadcast_ property by _June 29, 2026_.

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

### June 2026 – New DLP Action to Trigger Custom Power Automate Workflows

Microsoft will introduce a new DLP action that can trigger custom Power Automate workflows when an item reaches the end of its retention period.

Admins can use this capability to automate complex disposition processes, such as initiating approval workflows or moving files to an archive after the retention period expires.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=558859](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=558859)

### June 2026 - Pre-built Template for Data Security Investigation in Purview

Microsoft will introduce new pre-built templates for data security investigations in Microsoft Purview. Instead of building queries from scratch, admins can use these templates to quickly scope and initiate investigations.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=560326#Roadmap](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=560326#Roadmap)

### June 2026 - Governance Reviews Dashboard for SharePoint Site Owners

A Governance Reviews Dashboard (Private Preview) will be introduced to consolidate all site governance tasks into a single unified view. With this dashboard, site owners can track pending reviews, such as inactivity checks, ownership validation, and attestation requirements across all managed sites.

It provides clear visibility into required actions, deadlines, and enforcement status, enabling faster responses without switching between multiple tools. By consolidating policy notifications into one place, it reduces reliance on scattered email alerts and delivers a more streamlined, action-oriented governance experience.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=560541#Roadmap](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=560541#Roadmap)

### June 2026 - New Security Detection Reports in Teams Admin Center

Microsoft will introduce a new report in the Teams admin center called the “Security Detection Report.” This report enables admins to review detection activities such as impersonation attempts, malicious URL detection, and identification of weaponizable file types.

Admins can also export detailed data from this centralized view for further investigation and analysis.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=560702#Roadmap](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=560702#Roadmap)

### Early-June 2026 - Identify External Bots Joining your Teams Meetings

Microsoft Teams is introducing automatic detection of external meeting assistant bots, providing organizations with greater visibility and control over automated participants. When a bot attempts to join a meeting, it will be clearly labeled in the lobby, allowing organizers to approve, block, or remove it.

Additionally, a new admin policy will enable administrators to define how such bots are handled across the organization. This feature will be enabled by default for all tenants, with rollout in general availability by mid-June 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1251206](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1251206)

### Early-June 2026 - File Quarantine Action for SharePoint and OneDrive for DLP

Microsoft will introduce a new option in Microsoft Purview Data Loss Prevention (DLP) for SharePoint and OneDrive called “File Quarantine.” When configured, any file that violates a DLP policy will be automatically moved to an admin-defined quarantine location.  
  
A tombstone file will be placed in the original location to inform users about the quarantine action, along with an admin-defined message. Admins can monitor these activities through Audit logs, DLP alerts, and Activity Explorer.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1288527](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1288527)

### Early-June 2026 - Adaptive Scopes for DLP for SharePoint

Currently, admins must manually select and maintain SharePoint sites within DLP policies. To reduce this effort, Microsoft will introduce adaptive scopes for SharePoint DLP policies.

With a Microsoft 365 E5 or E5 Compliance license (add-on), admins can dynamically target SharePoint sites based on specific attributes such as URL, name, or metadata. This feature is not enabled by default and requires admins to configure adaptive scopes within DLP policies. Also, it will be out for general availability by early June 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1234571](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1234571)

### Early-June 2026 – Teams Android Device Management Moves to Pro Management Portal

Teams Rooms on Android, Teams phones, Teams panels, and Teams displays will be managed through the Pro Management Portal (PMP) instead of the Teams Admin Center, unifying device management in one place.

As part of this transition, device inventory and health data will automatically appear in PMP. Admins performing management actions in TAC will be redirected to the new portal experience. The rollout is expected to reach general availability across Worldwide and GCC environments by early June 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1227622](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1227622)

### Late-June 2026 - Recipient Groups in eSignature for Microsoft 365

Microsoft will introduce a new feature called recipient groups for eSignature requests in Microsoft Word. This allows users to assign a group of up to 10 recipients for signing. Once any one recipient in the group completes the signature, the requirement is fulfilled.

This approach helps reduce delays by avoiding dependency on a single individual to complete the signing process. The feature will be enabled by default.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1290821](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1290821)

### Early June 2026 – New Data Security Posture Management Experience in Microsoft Purview

Starting early June 2026, Microsoft Purview introduces a new Data Security Posture Management (DSPM) experience, unifying visibility across traditional and AI-driven data with guided workflows to prioritize risks and accelerate remediation. It also adds AI observability, enhanced reporting, and Security Copilot agents to automate tasks like triage and policy management.

The new experience is available alongside DSPM (classic) and DSPM for AI (classic), with no default policy changes and existing onboarding configurations carried over.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1191257](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1191257)

### Late-June 2026 – Integration of Adaptive Protection with Data Lifecycle Management

Microsoft plans to make the Adaptive Protection and Data Lifecycle Management (DLM) integration generally available by late June 2026. This integration allows administrators to retain or restore items deleted by high-risk users, providing better safeguards against insider threats and accidental data loss.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110)

### End of June 2026 – Unified Management of Teams Apps Across Microsoft 365

Microsoft is finalizing the rollout of Unified App Management for Teams, Outlook, and the Microsoft 365 app. This update simplifies app management by consolidating the separate admin experiences into a single, centralized management interface. The unified experience will be fully available to all organizations by the end of June 2026.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC796790](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC796790)

### June 2026 – New Secure Workflow to Bypass Legal Holds and Retention Policies in Microsoft Purview

Admins will have the ability to permanently delete sensitive Exchange mailbox content, bypassing retention policies and eDiscovery holds. This will be possible through the “Priority Cleanup Administrator” role, which grants authorized users’ permission to initiate Priority Cleanup for Exchange, allowing exceptions to standard retention and legal hold policies.

Since this process is irreversible and overrides existing policies, Microsoft has built-in approvals and special auditing for security.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=392838](https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=392838)

### Enhancements

### June 2026 – Mail Merge (Advanced) in Outlook on the Web & New Outlook for Windows

Outlook on the web and the new Outlook for Windows will receive enhanced Mail Merge (Advanced) capabilities. With this update, users will be able to insert dynamic fields into email templates, enabling more personalized and customized communication at scale.

This enhancement simplifies the process of tailoring messages, making it more efficient to send targeted and professional emails.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047)

### Existing Functionality Changes

### June 1, 2026 – Microsoft Teams Disables Email Notifications for Meeting Recording Expiration

Starting June 1, 2026, Microsoft will disable email notifications for expiring Teams meeting recordings. This change aims to reduce notification fatigue and improve relevance based on customer feedback. While email notifications are removed, the underlying recording expiration and deletion policies remain unchanged.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1245635](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1245635)

### Early-June 2026 – Decoupling Policy Tips & Email Notifications for SharePoint and OneDrive DLP

Currently, enabling email notifications in DLP policies for SharePoint and OneDrive also enforces policy tips, and vice versa. With this update, Microsoft introduces the ability to configure policy tips and email notifications independently, providing greater flexibility in how alerts are managed.

This feature will be available in general availability by early June 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC791114](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC791114)

### Action Required

### June 1, 2026 – End of Sale of Standalone SharePoint and OneDrive Plans

Microsoft is ending the sale of standalone _SharePoint Online Plan 1 and Plan 2_ and _OneDrive for Business Plan 1 and Plan 2_. Starting June 1, 2026, new customers will no longer be able to purchase these standalone plans.

**Solution:** Move to Microsoft 365 suite offerings such as Business Basic, Business Standard, Business Premium, E1, E3, or E5 for continued service availability.

**_Ref:_** [https://learn.microsoft.com/en-us/partner-center/announcements/2026-january#retirement-of-standalone-sharepoint-online-and-onedrive-for-business-plans-plan-1-and-plan-2](https://learn.microsoft.com/en-us/partner-center/announcements/2026-january#retirement-of-standalone-sharepoint-online-and-onedrive-for-business-plans-plan-1-and-plan-2)

### June 30, 2026 – Exchange Web Services Will Be Blocked for Kiosk and Frontline Licenses

Microsoft will block Exchange Web Services access for mailboxes that do not include EWS usage rights starting June 30, 2026. After enforcement, requests made without a supported license will return an HTTP 403 error. Impacted licenses include Exchange Online Kiosk, Microsoft 365/Office 365 F1, and F3.

**Solution:** To continue using EWS, assign a license that includes EWS access, such as **Exchange Online Plan 1 or 2** or **Microsoft 365 E3/E5**.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/update-to-ews-access-for-kiosk–frontline-worker-licensed-users/4474299](https://techcommunity.microsoft.com/blog/exchange/update-to-ews-access-for-kiosk--frontline-worker-licensed-users/4474299)

## July 2026 (Attention Needed: 15)

### July 01, 2026 – Microsoft 365 Price Increase

Starting July 1, 2026, Microsoft will implement a global price increase across all Microsoft 365 plans. Prices will increase by 5% to 33%, depending on the SKU. The increase reflects ongoing investments in AI capabilities, security enhancements, and advanced management features.

Alongside the price increase, Microsoft is adding value to select plans:

*   Microsoft 365 Business Premium will receive an additional 50 GB of email storage at no extra cost.
*   Advanced Microsoft Intune capabilities will be included with Microsoft 365 E3 and E5 subscriptions.
*   Microsoft will include Security Copilot in E5 subscriptions at no additional cost.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/blog/2025/12/04/advancing-microsoft-365-new-capabilities-and-pricing-update/](https://www.microsoft.com/en-us/microsoft-365/blog/2025/12/04/advancing-microsoft-365-new-capabilities-and-pricing-update/)

### July 1, 2026 – DNS Provisioning Change for Accepted Domains

Microsoft is updating DNS provisioning for new Accepted Domains to support DNSSEC adoption. Starting July 1, 2026, A records for newly added Accepted Domains will be created under **mx.microsoft** subdomains instead of _mail.protection.outlook.com_.

Organizations using automation or workflows that rely on _mail.protection.outlook.com_ for MX record configuration may experience mail flow issues unless updated. Going forward, the _List serviceConfigurationRecords_ Microsoft Graph API will become the authoritative source for retrieving MX record values.

**Solution:** Update domain provisioning or MX record automation to use the **List serviceConfigurationRecords** Graph API instead of relying on _mail.protection.outlook.com_ before July 1, 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1048624](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1048624)

### July 2026 – SharePoint Alerts will be Fully Retired

Microsoft will discontinue support for SharePoint Alerts. Existing alerts can no longer be modified and will eventually stop functioning.

**Solution:** Microsoft recommends migrating SharePoint Alerts to Power Automate or SharePoint Rules. Use the Microsoft 365 Assessment tool to review alerts and plan the move.

**_Ref_**_:_ [https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f](https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f)

### July 2026 – SharePoint File-Level Archiving Coming to Microsoft 365 Archive

Microsoft 365 Archive will support file-level archiving in SharePoint, enabling more granular retention and storage control. This feature will reach general availability in July 2026.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=477371](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=477371)

### July 2026 - Expanded Archive Mailbox Capacity Beyond 1.5 TB With Consumption-Based Pricing

Previously, auto-expanding archive mailboxes were limited to 1.5 TB, after which they would stop working. This limit has now been removed, allowing archive mailboxes to grow beyond 1.5 TB automatically to support ongoing retention needs.

This feature follows a consumption-based pricing model for storage beyond 1.5 TB, costing $0.25 per GB per month (or $0.0082 per GB per day).

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=560820#Roadmap](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=560820#Roadmap)

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

### Early-July 2026 – Centralized App and Agent Evaluation Experience in Microsoft Teams

Microsoft Teams is introducing a centralized evaluation experience in the Teams admin center to simplify app and agent approval decisions. Administrators can define organizational trust requirements once, after which Teams will automatically generate evaluation scores and detailed assessment reports for apps and agents based on compliance and security criteria.

The evaluation score settings will be available under _Teams admin center → Teams apps_, allowing admins to review, sort, and filter apps using trust and compliance insights. This feature is enabled by default and does not change existing app enablement or blocking behavior.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1218713](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1218713)

### Early-July 2026 - Promotions Email Tagging and Filtering in Microsoft Defender for Office 365

Microsoft Defender for Office 365 is improving how promotional emails are handled by tagging them as “promotions” and optionally moving them to a dedicated Promotions folder.

If the “Bulk moves enabled” setting is turned on, tagged emails will automatically move to the Promotions folder. Users can also create inbox rules based on the promotions tag, and the system will continue learning from user behavior to improve accuracy. It will be out in general availability by early July 2026.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1279093](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1279093)

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

### July 14, 2026 - End of Support for SharePoint Designer 2013

Microsoft will retire SharePoint Designer 2013 in accordance with the Microsoft Fixed Lifecycle Policy to support the transition toward modern workflow automation and customization experiences. After July 14, 2026, Microsoft will no longer provide technical support, security updates, or product fixes, and no extensions or exceptions will be available.

**Solution:** Use SharePoint Migration Tool (SPMT) 4.1 to assess existing workflows and migrate them to Power Automate by July 13, 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230891](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230891)

### Late-July 2026 - Microsoft Planner Tab Support for Shared and Private Channels

Starting late July 2026, Microsoft Teams will support Planner tabs in Shared and Private channels, enabling users to add new or existing plans directly for seamless task tracking. The feature will be turned on by default.

Users can add Planner via the “+” tab experience, with plans inheriting channel permissions and Microsoft 365 compliance controls. Existing Planner behavior remains unchanged, and all data continues to follow current storage and retention policies.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1262590](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1262590)

### Late-July 2026 – Microsoft Planner Tab Support for Shared and Private Channels

Microsoft is expanding Planner integration within Teams by enabling Planner tabs in both Shared and Private channels. Starting mid-May 2026, users can add new or existing plans directly to these environments, allowing for seamless task management within the channel. The feature is enabled by default.

Users can add Planner via the “+” tab experience, with plans inheriting channel permissions and Microsoft 365 compliance controls. Existing Planner behavior remains unchanged, and all data continues to follow current storage and retention policies.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1262590](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1262590)

## August 2026 (Attention Needed: 2)

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

## September 2026 (Attention Needed: 5)

### Sep 2026 – Update PowerPoint Client Versions to Access Captions & Subtitles

As part of a backend service upgrade for Captions & Subtitles in PowerPoint, users on older Microsoft 365 PowerPoint builds prior to 16.0.19426.20218 for Windows or 16.103.1207.4 for macOS will lose access to these features.

**Solution:** Update PowerPoint clients to Windows (Win32) 16.0.19426.20218 or macOS 16.103.1207.4 or later.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1231437](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1231437)

### Sep 2026 – Update Office Apps to Keep Read Aloud, Transcription, and Dictation Features

Read Aloud, Transcription, and Dictation features in Microsoft 365 Office apps will stop working on versions earlier than 16.0.18827.20202 because of backend upgrades. This change takes effect after September 2026 for Worldwide tenants and November 2026 for GCC, GCC High, and DoD environments.

**Solution:** Update all Office apps to 16.0.18827.20202 or later before the deadline.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1127222](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1127222)

### Sep 17, 2026 – Retirement of Legacy Education LTI Tools

On September 17, 2026, Microsoft will retire legacy Education LTI tools such as Teams Assignments, OneDrive, OneNote Class Notebook, and Reflect, transitioning to a single Microsoft 365 LTI unified tool that users and admins must adopt.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1160188](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1160188)

### Sep 30, 2026 - Deprecation of Custom Controls in Microsoft Entra Conditional Access

Conditional Access Custom Controls will be retired on September 30, 2026. This legacy preview feature is being replaced by External MFA, a more robust and integrated framework for third-party MFA providers.

**Solution:** Admins should migrate to External MFA before the retirement date to avoid disruption.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/external-mfa-in-microsoft-entra-id-is-now-generally-available/4488926](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/external-mfa-in-microsoft-entra-id-is-now-generally-available/4488926)

### Late-Sep 2026 - Teams Channel Whiteboard Storage Moves to SharePoint

The default storage location for whiteboards created in Teams Channel tabs will be updated. Starting in late Sep 2026, these files will be stored in the channel’s associated SharePoint site instead of the creator’s OneDrive. Enabled by default, this change prevents access issues caused by sharing settings, Information Barriers, and Conditional Access policies.

With this update, Whiteboards inherit SharePoint-based Microsoft Purview controls such as DLP, sensitivity labels, retention, eDiscovery, and audit logging, while also improving centralized compliance monitoring and reporting.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1253753](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1253753)

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

### Mid-Oct 2026 – Content Security Policy for Entra ID Sign-in Experience

Microsoft Entra ID is enforcing a stricter Content Security Policy (CSP) for sign-ins starting mid-October 2026. Only trusted Microsoft scripts will be allowed, blocking injected code to reduce XSS risks. This applies to browser-based sign-ins on _login.microsoftonline.com_ and does not affect Entra External ID tenants.

**Solution:** If you use tools or extensions that inject code, switch to non-injecting alternatives and [test sign-in flows](https://learn.microsoft.com/en-us/entra/identity-platform/content-security-policy#how-to-prepare-for-csp-enforcement) before CSP enforcement begins.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1191924](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1191924)

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

### Oct 2027 – Removal of Passcode Option from Create Meeting API

In October 2027, Microsoft will remove the option to create meetings without passcodes. This means all online meetings created through the Microsoft Graph API will automatically require a passcode, and the _isPasscodeRequired_ property on the _joinMeetingIdSettings_ resource will be removed. This change ensures that every meeting is consistently secured with a passcode, simplifying meeting creation, and improving security.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC985483](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC985483)

### Oct 14, 2027 – Retirement of Duplicative Properties in Passkey (FIDO2) Authentication Methods Policy

To align with the updated passkey policy API schema that supports group-based passkey profiles, Microsoft will retire _isAttestationEnforced_ and _keyRestrictions_ from the fido2AuthenticationMethodConfiguration API. During the transition, these properties will sync with attestationEnforcement and keyRestrictions in the Default passkey profile.

**Solution:** Admins should update configurations, automations, and integrations to use the new schema.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1188230](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1188230)

In conclusion, navigating the ever-evolving landscape of Microsoft 365 requires staying informed about the changes 🔍. By proactively adapting to these changes, you can optimize your Microsoft 365 experience, maximize productivity, and effectively plan for the future. 💪

We are committed to keeping this blog updated with the latest information, so stay tuned for upcoming updates.

[https://blog.admindroid.com/microsoft-365-end-of-support-milestones/](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/)