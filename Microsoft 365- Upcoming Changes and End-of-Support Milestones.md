# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.  
  
Discover the **key changes, deprecations**, and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

  
Here is a list of changes categorized by month and year.  

*   September 2025 (Retirements: 7, New Features: 11, Enhancements: 9, Existing Functionality Changes: 4, Action Needed: 5)
*   October (Retirements: 5, New Features: 7, Enhancements: 2, Existing Functionality Changes: 3, Action Needed: 1)
*   November (Attention Needed: 3)
*   December (Attention Needed: 7)
*   Q1 2026 (Attention Needed: 12)
*   Q2 2026 (Attention Needed: 8)
*   Q3 2026 (Attention Needed: 2)
*   Q4 2026 (Attention Needed: 3)

  

## September 2025

### Retirements

### Sep 1, 2025 – Legacy Message Trace Experience Retires in Exchange Online

With the introduction of the new Message Trace in Microsoft Exchange Online, the legacy experience will retire on September 1, 2025. The updated version offers improved performance and a modern interface, replacing:

1.  Legacy Message Trace UI in the EAC
2.  Legacy cmdlets: Get-MessageTrace, Get-MessageTraceDetail

**Solution:** As the new Message Trace becomes the default, admins should update scripts to use _Get-MessageTraceV2_ and _Get-MessageTraceDetailV2_, and complete the transition. The new UI remains enabled in the Exchange admin center.

**_Ref_**: [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1092458](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1092458)

### Sep 1, 2025 – Client Access Rules Deprecation in Exchange Online

Client Access Rules (CARs), used to control access to Exchange Online services based on various conditions, will be deprecated by September 1, 2025.

**Solution:** Migrate to Conditional Access policies with Continuous Access Evaluation (CAE) to benefit from more advanced and flexible access control.

**_Ref_**: [https://techcommunity.microsoft.com/blog/exchange/update-on-client-access-rules-deprecation-in-exchange-online/4354809](https://techcommunity.microsoft.com/blog/exchange/update-on-client-access-rules-deprecation-in-exchange-online/4354809)

### Sep 1, 2025 – Retirement of Classic eDiscovery (Premium) in Microsoft Purview

Microsoft will retire Classic eDiscovery (Premium) experience from the Microsoft 365 Purview portal by Aug 31, 2025. So, starting Sep 1, 2025, the classic eDiscovery (Premium) experience will not be available as an experience option in Microsoft Purview portal.

  
**Solution:** Transition to the new unified eDiscovery for faster and improved search and investigation capabilities.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1107493](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1107493)

### Sep 9, 2025 – ‘Mobile Devices’ Settings Page to Be Removed in Outlook

The ‘Mobile devices’ page in Outlook Web and the new Outlook currently allows users to view and manage all devices syncing with their mailbox. Microsoft will retire this page starting September 9, 2025, as part of the shift toward modern device management tools.  
  
**Solution:** Users can use the My Account portal or iOS/Android native tools to view, manage, and remotely wipe their connected devices.  
  
**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1130607](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1130607)

### Sep 15, 2025 - Retirement of Power BI Cognitive Services and Azure Machine Learning Features

Microsoft is retiring Cognitive Services and Azure Machine Learning features in Power BI by September 15, 2025. Existing models will continue to refresh until the retirement date. Microsoft recommends transitioning to Microsoft Fabric, where continued investments in AI capabilities will be made.  

**Solution:** Move to Auto ML in Microsoft Fabric for supported AI scenarios.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1124567](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1124567)

### Mid-Sep 2025 – Microsoft To Do Ending Support for iOS 16 and macOS 12

After mid-Sep 2025, users running iOS 16 or earlier and macOS 12 or earlier will no longer receive updates to Microsoft To Do. For better performance and stronger security, Microsoft To do require updated operating systems.  
  
**Solution**: Update the devices to iOS 17 or later and macOS 13 or later. Also, review your organization’s device management policies to confirm they’re compatible with these OS versions.  
  
**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1129721](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1129721)

### Sep 22, 2025 - Retirement of Sub-Domains Feature in Defender for Cloud Apps – Cloud Discovery

The sub-domains feature in Microsoft Defender for Cloud Apps – Cloud Discovery gives admins detailed visibility into app usage at the sub-domain level.  
Due to low usage, Microsoft will retire this feature starting September 22, 2025. After that, sub-domain insights will no longer be available.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1141957](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1141957)

### New Features

### Early-Sep 2025 - General Availability of Progressive Alert Scoring in IRM

Microsoft will roll out a new feature -" Progressive alert scoring" in Microsoft Purview Insider Risk Management. Currently, user activities that could potentially result in data security incidents will be assessed once every 24 hours. After this rollout, the assessment of user meeactivities will be done more frequently within a 24- hour period, along with alert insights. This feature will be generally available for GCC, GCC-High, DoD environments by early-Sep 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC707653](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC707653)

### Sep 2025 – General Availability of High Volume Exchange Email for Microsoft 365

Microsoft will roll out High Volume Email (HVE) in general availability to support internal communication needs for line-of-business applications and high-volume SMTP use cases. HVE allows organizations to send internal emails well beyond the standard Exchange Online limits.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=382633](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=382633)

### Early-Sep 2025 – Information Barrier Support in Microsoft Planner

Currently, when sharing a Planner plan, users can view the full tenant member list, which creates a potential risk of data exposure. To address this, Microsoft is adding Information Barriers support in both the Planner web app and the Planner app in Teams. With this update, users will only be able to discover members within their assigned segments.

**Note:** Information Barrier functionality will not be available in the Planner mobile app or when using Planner through mobile browsers.  
  
**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1139487](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1139487)

### Early-Sep 2025 – Microsoft Teams to Support Silent Test Calls for Network Readiness  

Microsoft Teams will allow IT admins to run silent call simulations to proactively test network readiness and detect issues early. Available for Windows and Mac desktops, this feature requires a Teams Premium license.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1089323](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1089323)

### Mid-Sep 2025 - Rule-based Enablement of Microsoft 365 third-party apps in the Teams admin center

To streamline app management in Teams, Microsoft is adding a new rule-based setting in the Teams admin center. This update allows administrators to manage Microsoft 365 certified apps in bulk by using controls available in the _org-wide settings_ section. Admins can define availability based on permission scopes and publisher names. A 30-day review period will be provided before these changes affect app availability.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1085133](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1085133)

### Mid-Sep 2025 – New Recommendations Added to Microsoft Secure Score

To further strengthen security posture, Microsoft Secure Score will introduce two new recommendations:

*   Remove inactive service accounts
*   Remove discovered passwords in Active Directory account attributes

These recommendations will appear only if your tenant has a Defender for Identity sensor deployed. It will be rolled out in General availability by mid-September 2025.  
  
**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1130384](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1130384)

### Mid-Sep 2025 – Microsoft Teams Integration with Microsoft Defender for Office 365 Tenant Allow/Block List

Admins can currently configure allow/block lists for domains in Teams admin center. With this update, Microsoft enables organizations to manage blocked external domains centrally through the Tenant Allow/Block List (TABL) in the Microsoft Defender portal.  
  
This feature ensures consistent domain management across Microsoft 365 services. It will be available only for customers with Microsoft Defender for Office 365 Plan 1/2 and Microsoft Teams.  
  
**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1133508](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1133508)

### Mid-Sep 2025 – New Workflows Experience in SharePoint

Microsoft is rolling out a new Workflows experience in SharePoint for enhanced automation in lists, libraries and chats, powered by Power Automate. Key updates include:

*   A new workflows button on list and library command bars.
*   A streamlined interface for building automations directly in SharePoint and Teams
*   A refreshed template library for easier workflow discovery
*   Natural language-to-flow capabilities and a Madlib-style editor for quick customization

This brings the same intuitive automation experience already available in Teams to SharePoint.  
  
**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1138798](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1138798)

### Mid-Sep 2025 - Data Lifecycle Management: Retention Based on “last accessed” for OneDrive and SharePoint Files

Starting mid-Sep2025, Microsoft will introduce a "When items were last accessed" option in Purview retention policies. This will allow admins to configure retention policies based on file access history in OneDrive and SharePoint, enabling the removal of outdated data.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442)

### Mid-Sep 2025 – Priority Cleanup in Purview Data Lifecycle Management

Microsoft is adding a new ‘Priority Cleanup’ feature in Purview Data Lifecycle Management. This lets admins delete OneDrive and SharePoint content before existing retention or hold periods end, giving more control over items like Teams recordings and transcripts. The feature includes options such as simulation mode, audit logs, and reviews, but it isn’t on by default.

To ensure security and avoid mistakes, at least two admins are required: one with the _Priority Cleanup Admin_ role to draft the policy, and another with the _Retention Management role_ to review and approve it. The rollout starts with Public Preview in mid–September 2025.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC971035](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC971035)

### Late-Sep 2025 - Usage Reports to Manage Metered Consumption Costs for Microsoft 365 Copilot Chat

To help organizations manage metered costs for Microsoft 365 Copilot Chat, Microsoft is rolling out a new Message Consumption Usage report in the Microsoft 365 admin center. This preview report offers detailed insights into billed messages, including total usage, daily usage patterns, and breakdowns by user, billing policy, agent, and agent-user pair.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1069563](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1069563)

### Enhancements

### Early- Sep 2025 - Automatically Set Work Location by Connecting to a Wi-Fi Network

Microsoft Teams will introduce a feature that automatically sets users' work locations when they connect to the organization's Wi-Fi or certain peripherals. This helps deliver location-based experiences without manual input.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=488800](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=488800)

### Early-Sep 2025 – Updated Page Analytics in Microsoft SharePoint Online

SharePoint Page Analytics will receive new capabilities starting early-Sep 2025. If your organization has Microsoft Viva Suite or Viva Pulse Communications and Communities, you’ll gain access to enhanced features:

*   View analytics data for up to 365 days (increased from 90 days).
*   See how news posts were viewed across Outlook, SharePoint, Teams, and Viva Engage. This applies to all charts, including _Unique viewers, Total views,_ and _Average time spent per user_.
*   Export analytics data directly to Excel or PowerPoint for reporting.
*   New Reactions and Promotions metrics show how many times users reacted to a post, along with the total number of shares, mentions, etc.
*   Improved layout and visuals for a better analytics experience and a few more features.

Organizations without these licenses will still have access to the current set of metrics, displayed with a modernized page design.

Currently, this rollout will be targeted to SharePoint News posts only.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1069561](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1069561)

### Sep 2025 – Microsoft Purview Diagnostics Access Now Available to More Admin Roles

Diagnostics access in the Purview compliance portal will be expanded beyond Global Admins. Compliance Administrators, Security Administrators, and Organization Management roles will also gain access, enabling broader troubleshooting and issue resolution. This update will be rolled out in preview by Sep 2025.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=500894](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=500894)

### Sep 2025 – Mail Merge (Advanced) in Outlook on the Web & New Outlook for Windows

Outlook on the Web and the new Outlook for Windows will receive enhanced Mail Merge (Advanced) capabilities. Users will be able to insert dynamic fields into email templates for personalized messages and advanced customizations, making it easier to tailor communications.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047)

### Mid-Sep 2025 - Streamlined Same-Device Number Matching and First Run Experience (FRX) in Microsoft Authenticator

Starting mid-September 2025, Microsoft Authenticator will receive two updates to improve the users’ sign-in experience:

*   **Same-device sign-ins will no longer require number matching**: Users can simply tap "Yes" or "No" to confirm, reducing friction, especially on Android. iOS users will also benefit, though app switching may still be needed with the SSO extension.
*   **Improved First Run Experience (FRX):** Microsoft simplifies account setup by combining multiple consent pages into consolidated one. It also prioritizes signing in with a Microsoft Entra account (work or school) instead of a personal Microsoft account.

**_Ref_**: [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1117816](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1117816)

### Late-Sep 2025 - Enable Smart Tagging for eSigned Documents in SharePoint

Microsoft SharePoint Online will automatically add the “Signed” tag to documents when they are electronically signed. In addition, two metadata columns—“Electronically Signed” and “Signature Provider”, will be added to indicate whether the document is e-signed and to identify the service used for the e-signature.

**Note**: This feature is available only for tenants with e-signature enabled.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1143282](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1143282)

### Sep 30, 2025 - Teams Meeting Join URL Validation

To strengthen meeting security, Microsoft will begin validating Microsoft Teams meeting URLs. If your organization uses security tools that rewrite or modify these links, they could be flagged as malicious and impact the meeting experience.

**Proactive step**: Admins can whitelist Microsoft Teams join URLs in the security tools. Also, review any URL rewriting or inspection rules to ensure they don't alter meeting links.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1120871](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1120871)

### Late-Sep 2025 – Improved Insights on License Assignment Path in Microsoft 365 Admin Center

Microsoft will fully update the product licensing page by late -September 2025. Admins will be able to view separate tabs for direct license assignments and group-based assignments, making it easier to clearly understand how licenses are distributed.  
  
**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1102762](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1102762)

### Late-Sep 2025 – Enhancements in Microsoft Teams Private Channels

Microsoft is expanding Teams private channel capabilities:

*   Increase from 30 to 1000 private channels per team
*   Up to 5000 members per private channel
*   Ability to schedule meetings in private channels
*   Compliance policies (DLP, retention, etc.) applied at the group level

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1134737](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1134737)

### Existing Functionality Changes

### September 2025 – Access Reviews Data Retention Policy Update

Beginning in September 2025, Microsoft Entra ID Access Reviews will retain history for only the past 12 months. Any review data older than one year will no longer be stored or retrievable through Microsoft Graph APIs or any other method. Organizations should take this into account if they require long-term access review data.  

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/what%E2%80%99s-new-in-microsoft-entra-%E2%80%93-june-2025/4352579](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/what%E2%80%99s-new-in-microsoft-entra-%E2%80%93-june-2025/4352579)

### Sep 18, 2025 – Microsoft Defender for Identity Alerts Transitioning to XDR

Microsoft Defender for Identity classic alerts will transition to the XDR detection platform on September 18, 2025. This change improves detection accuracy and performance. Users must update workflows with new Detector IDs and reconfigure alert exclusions using XDR Alert Tuning rules.  
  
**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1137610](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1137610)

### Sep 26, 2025 - Unlicensed OneDrive Accounts to Enter Read-Only Mode

Microsoft will begin transitioning OneDrive accounts that remain unlicensed before July 28, 2025, to read-only mode by September 26, 2025. Admins should monitor the Unlicensed OneDrive Accounts report and take appropriate actions such as renewing, archiving, or deleting accounts to ensure compliance and uninterrupted access.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC836942](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC836942)

### Sep 26, 2025 - Changes to Microsoft Purview DLP Alert Settings

In a few tenants, DLP rules showed alerts as enabled in the Purview portal, while they were actually disabled through PowerShell. To address this inconsistency, Microsoft Purview will align DLP alert settings between the portal and PowerShell.

If a rule’s alerts were disabled using PowerShell, the portal will now also display them as disabled. If you want to continue receiving alerts, you’ll need to re-enable them either in the portal or through PowerShell.  

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1143996](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1143996)

### Action Required

### Early -Sep 2025 – Retirement of Azure AD Graph API

Starting early September 2025, applications that were granted extended access and still rely on Azure AD Graph APIs will no longer be able to use these APIs.

**Solution:** Use the **_Recommendations_** tab in the Microsoft Entra admin center to identify affected apps and migrate to Microsoft Graph APIs.

**_Ref_**: [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1101901](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1101901)

### Sep 2, 2025 – Update Conditional Access Policies for Azure DevOps Sign-ins

Microsoft is removing Azure Resource Manager (ARM) as a dependency for Azure DevOps sign-ins and token refresh. Previously, Conditional Access policies targeting ARM would apply to Azure DevOps as well. With this change, those policies will no longer enforce access controls on Azure DevOps usage.

**Solution:** Admins should configure a separate Conditional Access policy specifically for Azure DevOps to maintain security controls.

**_Ref_**: [https://devblogs.microsoft.com/devops/removing-azure-resource-manager-reliance-on-azure-devops-sign-ins/](https://devblogs.microsoft.com/devops/removing-azure-resource-manager-reliance-on-azure-devops-sign-ins/)

### Sep 14, 2025 – New Authentication Requirements for Teams PowerShell Module

Microsoft is updating the authentication requirements for application-based authentication in the Microsoft Teams PowerShell Module.

**Solution**: If your organization is currently using Entra applications to automate or manage Microsoft Teams via PowerShell, you must update your application permissions to include: GroupMember.Read.All and RoleManagement.Read.Directory.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1134747](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1134747)

### Sep 15, 2025 – MFA Requirement for Credential Management

Microsoft will require users to complete an MFA prompt for all credential management activities performed on the “My sign-ins” page. Users will have to complete MFA if they have not authenticated within the last 10 minutes of their current session.  
  
**Solution**: Prepare your users for this change by informing them that they may be required to re-authenticate more frequently whenever they perform actions like password changes.

**_Note_**: In Message Center, there is a date inconsistency. Enforcement begins on August 15, while Microsoft sets the action deadline as September 15. It’s recommended to take precautionary steps early to prevent any disruption.

  
**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1135479](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1135479)

### Sep 30, 2025 – Retirement of Managing Authentication Methods in Legacy MFA &SSPR Policy

Starting Oct 2025, Microsoft no longer allow authentication methods to be managed in the legacy MFA and SSPR policies.

**Solution:** Organizations should use the converged authentication methods policy where methods can be managed centrally for all authentication scenarios including passwordless, MFA and SSPR.

**_Ref:_** [https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-methods-manage#legacy-mfa-and-sspr-policies](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-methods-manage#legacy-mfa-and-sspr-policies)

## October 2025

### Retirements

### After Oct 1, 2025 – Retirement of Rewrite Suggestions in Word

The Rewrite Suggestions feature in Microsoft Word, which offered AI-generated alternatives for improving clarity, grammar, and tone, will be deprecated after October 1, 2025.  
  
**Solution:** Transition to Copilot’s Auto-Rewrite for advanced writing assistance.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1129729](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1129729)

### Oct 15, 2025 - End of Office 2016 and Office 2019 Support

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

### New Features

### Early-Oct 2025 – AI-Powered Data Security Investigations in Microsoft Purview

Microsoft Purview is launching Data Security Investigations (DSI), an AI-driven solution that helps security teams detect, analyze, and mitigate data risks. It provides deep content analysis, visualizes correlations, and simplifies policy refinement, all within a unified experience.  
  
**_Ref_**: [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1047912](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1047912)

### Oct 2025 - Information Barriers Upgrade from IB v1 to IB v2

Information Barriers V2 introduces larger segment support, multi-segment capabilities, and flexible discoverability. Tenants that have not yet enabled Information Barriers will automatically get IB V2 when they turn it on for the first time. Those already using IB V1 must upgrade to V2 to benefit from these enhancements.  
  
**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=115482](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=115482)

### October 2025 - Just in Time Protection on SharePoint in DLP

Microsoft is introducing Just-in-Time protection for SharePoint in Microsoft Purview Data Loss Prevention in preview.

With this feature, organizations can automatically apply DLP restrictions to unclassified files when they are accessed or shared externally. Instead of restricting files in advance, JIT protection enforces security measures only when there is a risk of data leaving the organization.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457)

### Oct 2025 - Room Recommender for Teams Meetings

When no room is booked for a meeting, a new AI feature will suggest available rooms directly in the meeting chat. Suggestions are based on attendee locations and room availability. About an hour before the meeting starts, if two or more attendees are in the same building, the feature will recommend a room to make in-person collaboration easier.  
  
This feature enhances meeting efficiency and requires a Teams Premium license to be enabled for organizers.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=482191](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=482191)

### October 2025 – New Personalization Settings in Microsoft Purview

Microsoft will introduce a new personalization page in Microsoft Purview, allowing admins to customize their experience. New features will include the ability to pin/unpin solutions, toggle solution bar visibility, access solution walk-throughs, export personalization data, and delete preferences. This update will help streamline the management of individual admin experiences within Microsoft Purview.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=483884](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=483884)

### Mid-Oct 2025 – Prevent Screen Capture in Microsoft Teams

  
Microsoft is adding a new “Prevent screen capture” feature to help protect meeting confidentiality. Available with Teams Premium, this capability blocks users from taking screenshots or recordings during meetings across supported platforms.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1140178](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1140178)

### Mid-Oct 2025 – Drag and Drop Between Accounts Coming to New Outlook for Windows

The new Microsoft Outlook for Windows adds drag and drop support to attach emails and files between personal or enterprise accounts, improving cross-account productivity. This update also allows attaching content from shared mailboxes or shared folders into another mailbox. Admins can control this capability using the _ItemsToOtherAccountsEnabled_ parameter in _OWAMailboxPolicy_.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1104315](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1104315)

### Enhancements

### Oct 2025 – OCR Support for Endpoint in Microsoft Purview Compliance Portal  

Microsoft Purview Compliance Portal will gain Optical Character Recognition (OCR) support on Windows endpoints. With this update, DLP policies will be able to detect and act on sensitive content within images, helping prevent data leaks. Supported file types include JPG, JPEG, PNG, TIFF, BMP, and image-based PDFs.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=160008](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=160008)

### Oct 2025 – Adding Support for SMTP DANE with DNSSEC for Exchange Online

Microsoft is adding inbound support for SMTP DANE with DNSSEC to Exchange Online GCC High and DoD. This enhancement will be available in preview starting October 2025, further strengthening email security for these environments.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?featureid=361914&searchterms=361914](https://www.microsoft.com/en-in/microsoft-365/roadmap?featureid=361914&searchterms=361914)

### Existing Functionality Changes

### Oct 2025 – Decoupling Policy Tips & Email Notifications for SharePoint and OneDrive DLP

  
Currently, enabling email notifications in DLP policies for SharePoint and OneDrive also forces policy tips to be enabled, and vice versa. With this update, admins will be able to configure policy tips and email notifications independently, providing more flexibility in how alerts are managed.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=396575](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=396575)

### Oct 2025 – Changing Output Format for Some Database Properties in Exchange Online Cmdlets

To improve performance, Microsoft is modifying the output format of certain database properties in Exchange Online cmdlets. For example, the Database property in the output of Get-Mailbox will change from: Database : APCP153DG038-db080 to a fully qualified path format: Database : APCP153.PROD.OUTLOOK.COM/7ad9dea1-26b7-4088-ad73-708c219faff6

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1108848](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1108848)

### Oct 15, 2025 – Limiting onmicrosoft.com Domain Usage for Sending Emails

During initial tenant setup, organizations are provided with a default onmicrosoft.com domain, which can be used to test mail flow. However, this default domain does not reflect the company’s brand, which may impact reputation. To encourage the use of custom domains for sending emails, Microsoft will throttle outbound emails sent from default onmicrosoft.com domains. Organizations will be limited to 100 messages per 24 hours.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/limiting-onmicrosoft-domain-usage-for-sending-emails/4446167](https://techcommunity.microsoft.com/blog/exchange/limiting-onmicrosoft-domain-usage-for-sending-emails/4446167)

### Late-Oct 2025 – Removal of Microsoft Graph Beta API Property

By late October 2025, the _sendDeviceOwnershipChangePushNotification_ property will be removed from Microsoft Graph Beta API. This property previously triggered notifications when device ownership changed from personal to corporate, but it is now redundant since notifications are automatically sent.  
  
**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1127211](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1127211)

### Action Required

### Oct 31, 2025 – Retirement of Deception Feature in Microsoft Defender for Endpoint

The Deception feature, which used decoys and lures to detect intrusions, will be retired.  
  
**Solution**: Adopt automatic attack disruption and exposure management features before October 30, 2025.  
  
**_Ref:_** [https://learn.microsoft.com/en-us/defender-xdr/deception-overview](https://learn.microsoft.com/en-us/defender-xdr/deception-overview)

### November (Attention Needed: 3)

### Nov 2025 - Microsoft Entra ID to Support Passkey Profiles in Authentication Methods Policy

In November 2025, Microsoft Entra ID will introduce support for passkey profiles in the passkey (FIDO2) authentication methods policy. This update allows admins to apply different passkey configurations to specific user groups, offering more granular control. New schema changes will apply if configurations are made through the Azure or Entra portal during the preview.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1097225](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1097225)

### November 2025 – Retention Policies for Microsoft Planner Content

  
Microsoft is introducing data lifecycle management to Microsoft Planner. This will allow admins to apply retention policies to Planner content, ensuring governance and compliance for project-related data.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=486828](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=486828)

### Nov 2025 - Introducing Data Lifecycle Management for Microsoft Planner

Compliance admins can now create retention policies to manage content in Microsoft Planner, including tasks from plans associated with Microsoft 365 groups.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=486828](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=486828)

### Nov 2025 - New Message Trace on Graph API

Microsoft plans to launch the new Message Trace on Microsoft Graph API in Public Preview by a tentative timeline of November 2025.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1092458](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1092458)

### December (Attention Needed: 4)

### Dec 2025 – Multi-Selectable DLP Policies as Insider Risk Management Triggers

  
Currently, Insider Risk Management (IRM) policies can only use one DLP policy as a triggering event. With this update, admins will be able to select multiple DLP policies as triggers in an IRM policy, giving them more flexibility and stronger coverage.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=493757](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=493757)

### Dec 2025 - Integration of New ChatGPT Enterprise Connector with Microsoft Purview Compliance Portal

The ChatGPT Enterprise connector will be integrated into the Microsoft Purview Compliance portal, allowing admins to discover, collect, and store prompts and responses from users' interactions with ChatGPT.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=401125](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=401125)

### Dec 2025 – Microsoft Teams App Usage Report Renamed and Redesigned as Integrated Apps Usage Report

The Teams app usage report is being renamed and redesigned as the Integrated Apps usage report, featuring new charts and metrics. It provides insights into app usage across Teams, Outlook, Microsoft 365 apps, and Copilot extensions. The data is organized by Publishing Type, Host Product, and Platform, with detailed views on app and user activity.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=410248](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=410248)

### Dec 2025 – Microsoft Purview DLP Adds Actionable Email Notifications for End Users

Microsoft Purview Data Loss Prevention now supports actionable email notifications, enabling end users to remediate policy violations directly from their mailbox. For OneDrive and SharePoint files that trigger DLP policies, users can now stop sharing, delete files, apply labels, override policies, report false positives, or indicate they’re unable to act—streamlining the remediation process.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=464996](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=464996)

### Dec 2025 – New Retention Actions in Power Automate Integration

As part of Power Automate’s integration with Microsoft Purview Records Management, new retention actions will roll out in December 2025. At the end of a retention period, admins will be able to:

*   Relabel files or emails
*   Apply retention labels to SharePoint files
*   Delete items across SharePoint, OneDrive, and Exchange

All retention actions will be logged in the Microsoft Purview Audit log for tracking.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=117425](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=117425)

### Dec 2025 – Inline Detection of Sensitive Data Shared Over Network via Microsoft Purview

Microsoft Purview now integrates with your existing Secure Access Service Edge (SASE) solution, extending Data Loss Prevention (DLP) capabilities to the network layer. This enables admins to intercept, inspect, and enforce DLP policies on network traffic carrying sensitive data.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=488807](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=488807)

### Late-Dec 2025 – Retirement of Mailbox Audit Log Cmdlets in Exchange Online

By late December 2025, Microsoft will retire the Search-MailboxAuditLog and New-MailboxAuditLogSearch cmdlets in Exchange Online.  
  
**Solution**: Use Search-UnifiedAuditLog instead.  
**_Ref_**: [https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310](https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310)

## Q1 2026 (Attention Needed: 12)

### Jan 13, 2026 – End of Extended Support for Microsoft Advanced Threat Analytics 1.x

Microsoft Advanced Threat Analytics (ATA) extended support will be ended on January 13, 2026.

**Solution**: Updates for Microsoft ATA are available from Microsoft Update or by manual download.

**_Ref_**: [https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c](https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c)

### Jan 2026 – DLP Policy Tip Support Coming to Outlook for Mac

Microsoft is bringing Data Loss Prevention (DLP) policy tip support to Outlook for Mac. This helps users avoid accidental data leakage by showing policy tips when sensitive data is detected in emails. Users will be able to identify non-compliant recipients and take corrective actions, including overriding the policy when permitted.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=484854](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=484854)

### Jan 2026 - Microsoft Purview Insider Risk Management Adds OCR Support for Image-Based Risk Detection

Starting January 2026, Insider Risk Management in Microsoft Purview will support Optical Character Recognition (OCR) to detect sensitive content in images shared via SharePoint, Teams messages, and endpoints. This enhancement helps identify potential insider threats such as data leaks or intellectual property theft, while preserving user privacy through pseudonymization and audit controls.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=171185](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=171185)

### Jan 2026 - SharePoint File-Level Archiving Coming to Microsoft 365 Archive

Microsoft 365 Archive will support file-level archiving in SharePoint, enabling more granular retention and storage control. This feature enters public preview in January 2026.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=477371](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=477371)

### Early Feb 2026 – Automatic Data Preservation for High-Risk Users

Microsoft is rolling out the integration of Adaptive Protection with Data Lifecycle Management (DLM) by early February 2026. With this update, items deleted by high-risk users will be automatically preserved. This enables organizations to quickly restore data if needed and prevent intentional data loss.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110)

### Feb 2026 – Exchange Online Moderation Approvals via Actionable Messages

The Exchange Online Moderation feature allows moderators to approve or reject messages before they’re sent. Currently, this could only be done in Outlook Desktop or Outlook on the web. With the new update using Actionable Messages, moderators can now approve or reject moderated messages from any Microsoft email client, including Outlook for Windows, Mac, iOS, and Android.  
  
**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=492743](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=492743)

### Feb 28, 2026 - Deprecation of Reporting Web Service Support for Exchange Online Message Trace Data

The Reporting Web Service for Message Trace will begin to be phased out by Feb 28, 2026.

**Solution**: Use the new Message Trace PowerShell cmdlets instead.

**_Ref_**: [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1092458](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1092458)

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

## Q2 2026 (Attention Needed: 8)

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

## Q3 2026 (Attention Needed: 2)

### July 14, 2026- InfoPath 2013 Client and InfoPath Forms Services in SharePoint Online Will be Retired

  
  
InfoPath Client 2013 will reach the end of its extended support period on July 14, 2026, and to keep an aligned experience across Microsoft products, InfoPath Forms Service will be retired from SharePoint Online.

**Solution:** To understand the usage of InfoPath within your organization, you can utilize the [Microsoft 365 Assessment tool](https://aka.ms/assessment/infopath) to scan your tenant and analyze InfoPath usage. If you are currently using InfoPath, you can initiate the migration process to modern alternatives such as Power Apps, Power Automate, or Forms.

**_Ref_**: [https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190](https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190)

### July 2026 - SharePoint Alerts Will be Fully Retired

Microsoft will discontinue support for SharePoint Alerts. Existing alerts can no longer be modified and will eventually stop functioning.

**Solution:** Microsoft recommends migrating SharePoint Alerts to Power Automate or SharePoint Rules. Use the Microsoft 365 Assessment tool to review alerts and plan the move.

**_Ref_**: [https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f](https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f)

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