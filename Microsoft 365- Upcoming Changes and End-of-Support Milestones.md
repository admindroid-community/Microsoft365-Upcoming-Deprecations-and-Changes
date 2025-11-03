# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.  
  
Discover the **key changes, deprecations**, and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

  
Here is a list of changes categorized by month and year.  

*   November 2025 (Retirements: 6, New Features: 11, Enhancements: 6, Existing Functionality Changes: 2, Action Needed: 3)
*   December 2025 (Retirements: 2, New Features: 10, Enhancements: 5, Existing Functionality Changes: 2, Action Needed: 1)
*   Q1 2026 (Attention Needed: 19)
*   Q2 2026 (Attention Needed: 9)
*   Q3 2026 (Attention Needed: 3)
*   Q4 2026 (Attention Needed: 3)

  

### November 2025

### Retirements

### Nov 1, 2025 – Retirement of the SharePoint SendEmail API

The SharePoint SendEmail API (SP.Utilities.Utility.SendEmail) is used to send emails directly from SharePoint through custom code, workflows, or Power Automate flows. Microsoft will retire this API on October 31, 2025, after which emails sent through it will no longer work. Admins can use Microsoft Purview audit logs to identify where this API is currently in use.

**Solution**: Move to modern alternatives like the Microsoft Graph API or Outlook connector to handle email-related automation.

**_Ref_**: [https://support.microsoft.com/en-us/office/retirement-of-the-sharepoint-sendemail-api-b35bbab1-7d09-455f-8737-c2de63fe0821](https://support.microsoft.com/en-us/office/retirement-of-the-sharepoint-sendemail-api-b35bbab1-7d09-455f-8737-c2de63fe0821)

### Nov 6, 2025 – ‘Mobile Devices’ Settings Page to Be Removed in Outlook  

The ‘Mobile Devices’ page in Outlook Web and the new Outlook currently allows users to view and manage all devices syncing with their mailbox. Microsoft will retire this page completely by Nov 6, 2025, as part of the shift toward modern device management tools.

**Solution:** Users can use the **My Account portal or native iOS/Android tools** to view, manage, and remotely wipe their connected devices.  
  
**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1130607](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1130607)

### Mid-Nov 2025 - Retirement of Power BI “Visualize the List” and “Visualize the Library” Features in SharePoint Online

The “Visualize the List” and “Visualize the Library” features in SharePoint Online allow users to quickly generate Power BI reports directly from SharePoint lists or libraries. To streamline the reporting experience, Microsoft has planned to retire these features.

After this retirement, users will no longer be able to use legacy integration to create new reports directly from SharePoint lists and libraries. In addition, previously published reports created using legacy integration will also no longer be accessible.

**Solution**: Users will need to use alternatives like Export to Power BI or Power BI Desktop to create reports from SharePoint data.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1156359](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1156359)

### Mid-Nov 2025 – Retirement of Viva Engage Desktop Notifications

Microsoft will retire desktop notifications in Viva Engage by mid-November 2025 to align with Microsoft 365’s unified notification system. The “Allow users to enable desktop notifications” and “Desktop push notifications” options will no longer be available for both admins and end users respectively. As a result, users will no longer receive @mention and community announcement notifications via desktop push.

**Solution:** Encourage users to rely on in-app notifications through Teams, Outlook, and Viva Engage.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1169069](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1169069)

### Mid-Nov 2025 – Retirement of Microsoft Lists Mobile Apps for iOS and Android

  
Microsoft will retire the Microsoft Lists mobile apps for iOS and Android by mid-November 2025. After this date, the app will no longer appear in Google Play or the Apple App Store for installation.

**Solution**: Switch to Microsoft List mobile web version.

**_Ref_**: [https://support.microsoft.com/en-us/office/microsoft-lists-mobile-apps-retirement-f8645669-d5d1-401f-afc5-295e529ddaaf](https://support.microsoft.com/en-us/office/microsoft-lists-mobile-apps-retirement-f8645669-d5d1-401f-afc5-295e529ddaaf)

### Nov 15, 2025 – Retirement of the “Refresh All on Page” Button in OneNote Meeting Details

The “Refresh All on Page” option in OneNote for Windows Meeting Details pane is used to update meeting information inserted from Outlook or Teams. Microsoft will remove this feature on November 15, 2025.

**Solution**: Users can manually update meeting details by reselecting the meeting from the right pane.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1171847](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1171847)

### New Features

**Nov 1, 2025 - Knowledge Agent in Microsoft SharePoint**  
  
Knowledge Agent brings AI-powered features directly into SharePoint to streamline content management and boost Copilot capabilities. It helps to:

*   Organize and enrich content for Copilot and agents to provide accurate answers.
*   Improve metadata and tagging with auto-fill suggestions and classification.
*   Keep content up-to-date by detecting broken links, retiring inactive pages, and identifying content gaps.
*   Assist as a co-author with templates, layout suggestions, and FAQs.
*   Respond to natural language questions and guide users to the right information.

From November 1, 2025, individual sites can opt in at their own pace.

**_Ref_**: [https://techcommunity.microsoft.com/blog/spblog/introducing-knowledge-agent-in-sharepoint/4454154](https://techcommunity.microsoft.com/blog/spblog/introducing-knowledge-agent-in-sharepoint/4454154)

### Nov 3, 2025 – Entra Authentication Support for Agents and Bots in Teams Group Chats

Microsoft Teams now supports Entra-based authentication for agents and bots in group chats. When a bot or app requests a user’s Entra token, Teams will verify whether the user has the app installed and the necessary consent granted. If not, a private prompt appears, guiding the user to install the app and authorize permissions. Once consent is complete, the app can securely access requested permissions.

Ref: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=503557](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=503557)

### Early-Nov 2025 - Chat with Anyone in Teams Using Email Address

Microsoft will soon allow users to chat with external contacts using their email addresses, even if they don’t have a Teams account. This way, external users will receive an invitation to join the session as a guest. This experience will be governed by your organization’s B2B Guest policy. Also, this feature will be enabled by default.

If you want to disable this feature, set the _UseB2BInvitesToAddExternalUsers_ attribute of _Set-CsTeamsMessagingPolicy_ to false.

**_Ref_**: [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1182004](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1182004)

### Early-Nov 2025 – Enhancements to Quarantine View in Microsoft Defender for Office 365

Microsoft is updating the quarantine view to improve usability and consistency:

*   Quarantined messages will now be displayed per individual recipient instead of grouping multiplerecipients in one row.
*   The _ReleaseToAll_ parameter of the _Release-QuarantineMessage_ cmdlet will now target each mailbox separately.
*   Backend performance improvements will enhance reliability and consistency.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1171845](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1171845)

### Early-Nov 2025 – Malicious URL Protection for Microsoft Teams Chat and Channels

  
To improve protection against phishing attacks, Microsoft will display a warning in Teams when users receive malicious URLs in Teams chats and channels. Admins can manage this link protection feature in the Microsoft Teams Admin Center or by using the _\-UrlReputationCheck_ parameter in the _Set-CsTeamsMessagingConfiguration_ PowerShell cmdlet. This feature will reach general availability by November 2025.

**_Ref_**: [https://learn.microsoft.com/en-us/microsoftteams/malicious-url-protection-teams](https://learn.microsoft.com/en-us/microsoftteams/malicious-url-protection-teams)

### Early-Nov 2025 – SMTP Onboarding to App RBAC in Microsoft 365

Granting apps permission to send emails on behalf of mailboxes is now simpler. Currently, admins have to assign permissions individually for each mailbox using PowerShell. With App Role-Based Access Control (RBAC), admins can assign the _SMTP.SendAsApp_ role to an app for group-based or scoped mailbox access. This eliminates per-mailbox configuration and streamlines OAuth SMTP onboarding.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=498356](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=498356)

### Early-Nov 2025 - Microsoft Entra ID to Support Passkey Profiles in Authentication Methods Policy

Microsoft Entra ID will introduce support for passkey profiles in the passkey (FIDO2) authentication methods policy. This update allows admins to apply different passkey configurations to specific user groups, offering more granular control. New API schema changes will apply if configurations are made through the Azure or Entra portal during the preview. This update will be rolled out in Public Preview starting early-Nov 2025.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1097225](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1097225)

### Nov 2025 – Enterprise Application Insights for SharePoint Sites

  
SharePoint admins can use the new “Enterprise Application Insights” report to gain visibility into sites accessed by third-party applications registered in the tenant. The report shows detailed information such as application permissions and request counts, helping admins take action more effectively.  
  
**Note**: This is part of SharePoint Advanced Management capabilities.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=417481](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=417481)

### Nov 2025 - Integration of Insider Risk Management and Data Security Investigation

Microsoft Purview now integrates Insider Risk Management (IRM) with Data Security Investigation (DSI). This update allows data security admins to launch a pre-scoped investigation directly from an IRM case. Also, this enhancement streamlines the process of investigating risky user activities and assessing potential impact following an incident.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=486827](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=486827)

### Nov 14, 2025 – Immersive Events in Microsoft Teams

Starting November 14, 2025, Immersive Events in Microsoft Teams will reach general availability. This feature lets participants engage in a 3D virtual environment, move freely through space, express themselves with avatar reactions, and interact in a more dynamic way.

**Note:** Meeting organizers must have Teams Premium or Mesh Trial licenses to schedule immersive events, which currently support up to 300 attendees.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1123552](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1123552)

### Nov 15, 2025 – Auto-Archive for Exchange Online

Microsoft is launching Auto-Archiving for Exchange Online in public preview by November 15,2025 (for tenants opted into Target release option). When a mailbox exceeds 96% of its quota and archive mailbox is present, older emails (excluding those tagged _Never Move to Archive_) will be automatically transferred to the archive mailbox. This prevents storage overflow and ensures uninterrupted mail flow.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/auto-archiving-for-exchange-online/4459735](https://techcommunity.microsoft.com/blog/exchange/auto-archiving-for-exchange-online/4459735)

### Mid-Nov 2025 – New Workflows Experience in SharePoint

Microsoft is introducing a modern Workflows experience in SharePoint, enhancing automation across lists, libraries, and chats using Power Automate.  
Key improvements include:

*   A new Workflows button on list and library command bars.
*   A simplified builder interface for creating automations directly in SharePoint or Teams.
*   A redesigned template library for easier discovery.
*   Natural language-to-flow creation and a Madlib-style editor for quick customization.

This aligns SharePoint’s automation capabilities with those already available in Teams. Also, this feature will be on by default.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1138798](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1138798)

### Enhancements

### Early-Nov 2025 – Improvements to Email Quarantine Preview in Microsoft Defender for Office 365

Microsoft Defender for Office 365 is upgrading the email quarantine preview experience to be more consistent, secure, and user-friendly.  
Key improvements include:

*   Removal of the plain text view for uniformity.
*   Hover-over URL previews will no longer allow clickable links for added protection.
*   The “Load external content” option will be restricted to enhance security.

This update affects both admins and end users reviewing quarantined emails.

**_Ref_:** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1166867](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1166867)

### Nov 2025 – Version History Optimization for SharePoint Lists and Libraries

SharePoint is improving version history handling for lists and document libraries edited in grid view. This update merges rapid, consecutive edits into a single version, reducing version clutter and saving storage. It also ensures smoother performance for automation rules and Power Automate flows connected to these edits.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=511800](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=511800)

### Mid-Nov 2025 - Microsoft Purview Integration with Entra GSA Internet Access

Microsoft is extending Purview Data Loss Prevention (DLP) policies to the network layer through integration with Entra Global Secure Access Internet Access. This enables organizations to inspect and control file traffic in transit and enforce conditions defined in DLP policies. With this update, admins can prevent data leakage by blocking sensitive information from being shared with untrusted apps, cloud services, or generative AI platforms.

**Note:** This update is for Microsoft 365 tenants with E3 or E5 licenses.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1181769](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1181769)

### Late-Nov 2025 – Secure by Default Updates for Exchange and Teams APIs

Microsoft will now require admin consent for all third-party apps accessing Teams and Exchange APIs. Previously, this requirement applied only to SharePoint Online and OneDrive, now expanding to Exchange and Teams. With this expansion, user consent will no longer be sufficient for app integrations.

**_Ref_**: [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1163922](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1163922)

### Late-Nov 2025 - Conditional Access Policies for eDiscovery Admins

Microsoft Purview is enhancing security and compliance by enforcing Entra Conditional Access policies for eDiscovery admins and introducing a new **‘FilePreviewed’** audit log activity.

In clear, currently, eDiscovery admins can access SharePoint Online content in Purview regardless of compliance with Conditional Access policies. With this update, non-compliant admins, such as those not meeting MFA or trusted network requirements, will be blocked from accessing SharePoint content through the Purview portal. Additionally, every file preview action will now be recorded under the new ‘FilePreviewed’ activity in audit logs.

**_Ref_:** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1181768](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1181768)

### Existing Functionality Changes

### Nov 2025 - Shared Tab in Microsoft Teams Channels

The “Files” tab in Microsoft Teams channels will be renamed to “Shared.” Currently, it only displays files from the channel’s document library. With the upcoming update, it will also include all files and links shared in channel conversations, making it easier to find and access all shared content in one place.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=470597](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=470597)

### Early-Nov 2025 - New Calendar Experience in Microsoft Teams

Microsoft Teams is introducing a new calendar experience to enhance productivity across Microsoft 365. It combines familiar features with Microsoft Copilot and Microsoft Places for seamless collaboration. As part of this change, the legacy calendar will be retired, and the toggle to switch between old and new calendars will be removed.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1129730](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1129730)

### Action Required

### Nov 3, 2025 – Retirement of Microsoft Places Team Guidance Feature

  
The Team Guidance feature in Microsoft Places, which helped managers manage in-office days and team priorities, is retiring. Microsoft is retiring to simplify collaboration and encourage teams to use Microsoft 365 Groups for scheduling and coordination.

**Solution:** Begin transitioning to Microsoft 365 Groups for team scheduling.

**_Ref_**: [https://support.microsoft.com/en-us/office/retirement-of-places-team-guidance-ba959478-e979-4f76-b235-1afacf1b6185](https://support.microsoft.com/en-us/office/retirement-of-places-team-guidance-ba959478-e979-4f76-b235-1afacf1b6185)

### Nov 14, 2025 – Retirement of UKG and Blue Yonder Managed Connectors in Teams Shifts

The UKG and Blue Yonder managed connectors that synchronize workforce management data with the Teams Shifts app will be retired on November 14, 2025. These connectors currently enable frontline workers and managers to manage schedules, time off, and shift swaps directly in Teams.

**Solution:** UKG users can transition to the UKG Flow app, while others can build custom integrations to continue syncing workforce management systems with Teams Shifts.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1166868](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1166868)

### Late-Nov 2025 – Retirement of Viva Insights Export via Microsoft Graph Data Connect (MGDC)

Microsoft is retiring the Viva Insights export option through Microsoft Graph Data Connect (MGDC) to simplify data handling and strengthen security. New organizations will no longer be able to configure this export 30 days after the announcement, while existing users can continue until the feature is fully retired in late November 2025.

**Solution:** Switch to the Power BI Connector in Microsoft Fabric or use CSV export for reporting needs by Nov 27, 2025.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1180889](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1180889)

### December 2025

### Retirements

### Dec 2025 – Removal of the “Reuse Slides” Feature in PowerPoint

The Reuse Slides feature in PowerPoint helps users insert slides from other presentations. Microsoft plans to discontinue the Reuse Slides feature in PowerPoint for Window and Mac Desktops starting December 2025.

**Solution**: After this change, users will need to manually copy and paste slides between files.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1179161](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1179161)

### Late-Dec 2025 – End of Support for Teams on Android 8

By late December 2025, Microsoft will completely end all security updates and bug fixes for the Teams app on devices running Android 8. This change is part of Microsoft’s effort to transition users to newer Android versions that offer better performance, stability, and security. Although the app will continue to function on Android 8, no future enhancements or maintenance updates will be provided.

**Solution**: Upgrade to a device running Android 10 or later to continue receiving updates.

**_Ref_**: [http://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1181212](http://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1181212)

### New Features

### Dec 2025 – Automatically Set Work Location by Connecting to a Wi-Fi Network

Microsoft Teams will introduce a feature that automatically sets users’ work locations when they connect to the organization’s Wi-Fi or certain peripherals. This helps deliver location-based experiences without manual input. The feature will be disabled by default. Tenant admins will have the option to enable it and will require end-user consent to proceed.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=488800](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=488800)

### Dec 2025 – Power Automate Integration with Data Lifecycle Management

Power Automate will integrate with Data Lifecycle Management, enabling administrators to automate actions when items reach the end of their retention period. For instance, organizations can design flows to initiate approval workflows before permanently deleting data.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=117523](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=117523)

### Dec 2025 – PST Import Support in the New Outlook for Windows

The new Outlook for Windows will soon provide a feature to import email messages directly from .pst files (Outlook Data File) into user mailboxes, simplifying mailbox migration and recovery.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=485739](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=485739)

### Dec 2025 – ChatGPT Enterprise Connector Integration with Microsoft Purview

The ChatGPT Enterprise Connector will be integrated into the Microsoft Purview Compliance Portal, enabling administrators to collect, retain, and review prompts and responses from organizational ChatGPT usage.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=401125](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=401125)

### Early-Dec 2025 – Rule-Based Management for Microsoft 365 Third-Party Apps in Teams

Microsoft is adding a rule-based configuration option in the Teams admin center to simplify app management. With this update, administrators can control Microsoft 365 certified third-party apps in bulk from the _Org-wide settings_ section. Also, app availability can be determined using publisher information and permission scopes.  

**_Ref_**:[https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1085133](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1085133)

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

### December 2025 - Two New Email Indicators in Insider Risk Management

Admins can use the two new email indicators in Insider Risk Management as triggers.  
They are,

1.  **Emails with attachments to free public domains** – Flags users when business-sensitive data is sent from a work account to a free public domain email.
2.  **Emails with attachments to self** – Flags users when business-sensitive data is sent from a work account to their personal email or themselves.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=496149](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=496149)

### Dec 2025 – Inline Detection of Sensitive Data Shared Over Network via Microsoft Purview

Microsoft Purview now integrates with your existing Secure Access Service Edge (SASE) solution, extending Data Loss Prevention (DLP) capabilities to the network layer. This enables admins to intercept, inspect, and enforce DLP policies on network traffic carrying sensitive data.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=488807](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=488807)

### Early-Dec 2025 – eDiscovery (Premium): Support for Non-Microsoft 365 Data in Review Sets

Microsoft Purview’s eDiscovery (Premium) will soon support importing and reviewing non-Microsoft 365 data alongside Microsoft 365 content. A new upload option within review sets will allow investigators to bring external data into the same workspace. All imported content (Microsoft and non-Microsoft) can then be searched, viewed, and analyzed together for a unified review experience.

This feature will be available by default. It may impact how your organization manages eDiscovery workflows, so internal processes and team training should be updated to ensure smooth adoption and awareness of the new capability.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1176369](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1176369)

### Enhancements

### Dec 2025 – Multi-Selectable DLP Policies as Insider Risk Management Triggers

  
Currently, Insider Risk Management (IRM) policies can only use one DLP policy as a triggering event. With this update, admins will be able to select multiple DLP policies as triggers in an IRM policy, giving them more flexibility and stronger coverage.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=493757](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=493757)

### Dec 2025 – SMTP DANE with DNSSEC Support for Exchange Online

Microsoft is adding inbound support for SMTP DANE with DNSSEC to Exchange Online environments in GCC High and DoD. This security enhancement strengthens email validation and encryption for government cloud users.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?featureid=361914&searchterms=361914](https://www.microsoft.com/en-in/microsoft-365/roadmap?featureid=361914&searchterms=361914)

### Dec 2025 – Require Explicit Consent for Recording and Transcription in Teams 1:1 Calls

  
Microsoft Teams is expanding the consent requirement for recording and transcription to include 1:1 calls. Admins can enforce this via a new Teams Calling policy setting. When a call is recorded or transcribed, the other participant’s camera, microphone, and screen sharing are automatically disabled until they provide explicit consent.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=503295](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=503295)

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

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1150664](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1150664)

### Action Required

### End of 2025 – Retirement of Mailbox Audit Log Cmdlets in Exchange Online

By late December 2025, Microsoft will retire the Search-MailboxAuditLog and New-MailboxAuditLogSearch cmdlets in Exchange Online.  
  
**Solution**: Use Search-UnifiedAuditLog instead.  
**_Ref_**: [https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310](https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310)

## Q1 2026 (Attention Needed: 19)

### Early-Jan 2026 – Retirement of Activity-Based Authentication Timeout for Outlook on the Web

Microsoft will retire the Activity-Based Authentication Timeout setting for Outlook on the Web (OWA) starting in early January 2026. This feature currently signs users out after a period of inactivity.

**Solution:** Configure Idle session timeout to maintain similar session control behavior.

**_Ref:_** [https://support.microsoft.com/en-us/topic/activity-based-authentication-timeout-for-outlook-on-the-web-in-office-365-0c101e1b-020e-69c1-a0b0-26532d60c0a4](https://support.microsoft.com/en-us/topic/activity-based-authentication-timeout-for-outlook-on-the-web-in-office-365-0c101e1b-020e-69c1-a0b0-26532d60c0a4)

### Jan 4, 2026 – Outlook for Android to Require Android 10.0 or Higher

Starting January 5, 2026, the Outlook for Android app will require devices to run Android 10.0 or later to continue receiving updates, security patches, and new features. Users on earlier Android versions will retain app access temporarily but will not receive further updates.

**Solution:** Advise users to upgrade their Android OS to version 10.0 or higher by Jan 4 to ensure ongoing support.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1163756](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1163756)

### Early-Jan 2026 - Policy Alerts Improvements in Microsoft Purview Communication Compliance

Communication Compliance is enhancing policy alert customization. Admins will have the ability to set the alert frequency for each policy and adjust the email alert frequency and recipients directly within the policy creation wizard, via the new alerts page. This update will be generally available from early-Jan 2026.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920304](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920304)

### Jan 12, 2026 – Deprecation of “When Sending a Message” Group Policy in Classic Outlook for Windows

The “When Sending a Message” policy is currently used to manage grouped email-sending settings in classic Outlook for Windows. This feature will be retired by January 13, 2026. These configurations will be replaced with new, separate Group Policy settings that provide granular control over individual mail-sending behaviors.

**Solution**: Migrate existing configurations to the new individual policy settings before January 12, 2026.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1164375](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1164375)

### Jan 13, 2026 – End of Extended Support for Microsoft Advanced Threat Analytics 1.x

Microsoft Advanced Threat Analytics (ATA) extended support will be ended on January 13, 2026.

**Solution**: Updates for Microsoft ATA are available from Microsoft Update or by manual download.

**_Ref_**: [https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c](https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c)

### Jan 2026 – DLP Policy Tip Support Coming to Outlook for Mac

Microsoft is bringing Data Loss Prevention (DLP) policy tip support to Outlook for Mac. This helps users avoid accidental data leakage by showing policy tips when sensitive data is detected in emails. Users will be able to identify non-compliant recipients and take corrective actions, including overriding the policy when permitted.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=484854](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=484854)

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

### Jan 2026 - SharePoint File-Level Archiving Coming to Microsoft 365 Archive

Microsoft 365 Archive will support file-level archiving in SharePoint, enabling more granular retention and storage control. This feature enters public preview in January 2026.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=477371](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=477371)

### Late-Jan 2026 – Insider Risk Management User Analytics in Microsoft Purview

Microsoft Purview will introduce User Activity Summaries within Insider Risk Management (IRM) to help analysts better assess risk context during incident reviews. These insights consolidate data from multiple security and compliance solutions, providing a unified view of user behavior and potential policy violations.

Insights will be available in:

1.  Microsoft Purview Data Loss Prevention alerts.
2.  Microsoft Defender user entity pages and alerts.
3.  Communication Compliance policy reports.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1045212](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1045212)

### Late-Jan 2026 – Retention Based on “Last Accessed” for OneDrive and SharePoint

Microsoft is enhancing Data Lifecycle Management by introducing a new “When items were last accessed” condition for retention policies. This feature allows admins to manage and automatically clean up OneDrive and SharePoint content based on access history, improving storage hygiene and optimizing Microsoft 365 Copilot responses.  

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442)

### Feb 2026 – Jailbreak and Root Detection in Microsoft Authenticator App

Microsoft will enhance the Microsoft Authenticator app with jailbreak and root detection capabilities for Entra credentials on both iOS and Android platforms. Once this feature is active, Entra credentials on jailbroken or rooted devices will stop functioning. And any existing ones will be automatically wiped for security reasons.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1179154](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1179154)

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

### Mar 31, 2026- Deprecation of ‘Require Approved Client App’ Conditional Access Grant

The Require approved client app control in Azure Active Directory (Azure AD) Conditional Access will be retired and no longer enforced.

**Solution:** You can make use of the “Require app protection policy” control, which has all the same capabilities

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448)

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

### Late-June 2026 – Integration of Adaptive Protection with Data Lifecycle Management

Microsoft plans to make the Adaptive Protection and Data Lifecycle Management (DLM) integration generally available by late June 2026. This integration allows administrators to retain or restore items deleted by high-risk users, providing better safeguards against insider threats and accidental data loss.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110)

### End of June 2026 – Unified Management of Teams Apps Across Microsoft 365

Microsoft is finalizing the rollout of Unified App Management for Teams, Outlook, and the Microsoft 365 app. This update simplifies app management by consolidating the separate admin experiences into a single, centralized management interface. The unified experience will be fully available to all organizations by the end of June 2026.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC796790](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC796790)

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