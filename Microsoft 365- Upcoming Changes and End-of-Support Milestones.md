# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.  
  
Discover the **key changes, deprecations**, and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

  
Here is a list of changes categorized by month and year.  

*   May 2025 (Retirements: 6, New Features: 13; Enhancements: 7, Existing Functionality Changes: 5, Action Needed: 2)
*   June 2025 (Retirements: 1, New Features: 7; Enhancements: 4, Existing Functionality Changes: 2, Action Needed: 1)
*   Q3 2025 (Attention Needed: 11)
*   Q4 2025 (Attention Needed: 10)
*   2026 (Attention needed: 14)

  

## May 2025

### Retirements

### Mid-May 2025 - Retirement of "Document Name Matches Patterns" Condition from Data Loss Prevention

The 'Document name matches patterns' condition helps detect documents where the file name matches specific patterns. Due to performance concerns, Microsoft will retire this condition from Purview Data Loss Prevention for Endpoint.

**Solution:** Use the 'Document name contains words or phrases' condition, where Microsoft will continue to invest development resources.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1042927](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1042927)

### May 17, 2025 - Retirement of SMS Invitations from Teams to External Partners

Microsoft will retire the ability to send SMS invitations to external partners to join Teams and continue the conversation.

**Solution:** To continue inviting external partners to Teams via SMS, sign up for a two-way SMS calling plan.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1057714](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1057714)

### Late-May 2025 - Complete Retirement of MSOnline PowerShell Module

The MSOnline PowerShell module will be completely retired late-May 2025.

**Solution:** Migrate to Graph PowerShell SDK as soon as possible.

**_Ref_**: [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991)

### May 8, 2025 - End of Support for “Draft Well-Written Input Text with Copilot” in Power Apps

The "Draft well-written input text" feature, available as a preview in Power Apps, assists users in drafting text in input fields within canvas apps. However, this feature will be removed starting May 8, 2025, and end users will no longer be able to use Copilot for drafting text in canvas apps.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1052019](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1052019)

### May 26, 2025 - Retirement of Classic Content Search, Classic eDiscovery (Standard) Cases, and Export PowerShell Parameters in Purview

Microsoft Purview will retire Classic Content Search, Classic eDiscovery (Standard) Cases, and Export PowerShell Parameters on May 26, 2025.

**Solution:** Users should transition to the new Content Search, Cases tab in Purview eDiscovery, and Microsoft Graph eDiscovery APIs for a more streamlined and modern experience.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-security-blog/upcoming-changes-to-microsoft-purview-ediscovery/4405084](https://techcommunity.microsoft.com/blog/microsoft-security-blog/upcoming-changes-to-microsoft-purview-ediscovery/4405084)

### May 30, 2025 - Retirement of "Code Snippets" Feature for Chats and Channels in Teams

The "Code snippets" feature for Teams chats and channels will begin retiring by May 30, 2025. This applies to Teams for Windows desktop, Teams for Mac desktop, and Teams for the web.

**Solution:** Switch to using code blocks, which offer a faster and more efficient way to create, edit, and share code directly in the compose box without requiring a title.

**_Ref_**: [https://support.microsoft.com/en-us/office/send-code-snippets-in-a-message-in-microsoft-teams-5406fe2b-2771-4b9a-bd73-656914f6ab3c](https://support.microsoft.com/en-us/office/send-code-snippets-in-a-message-in-microsoft-teams-5406fe2b-2771-4b9a-bd73-656914f6ab3c)

### New Features

### May 2025 - New Insider Risk Management Reporting Capabilities

Insider Risk Management will introduce a centralized hub for all reports, including analytics and user activity reports. New reports will also be available, providing summaries of alert trends and case creation patterns.  

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=470027](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=470027)

### May 2025: OneDrive Sync Admin Reports for GCC

Microsoft will roll out OneDrive Sync Admin Reports in the Microsoft 365 admin center for GCC users by May 2025. These reports will help admins monitor sync client usage and errors across the organization.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=393333](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=393333)

### May 2025 – Inline Discovery of Sensitive Data Shared Over the Network in Microsoft Purview

Microsoft Purview will extend its policies to the network by integrating the existing Secure Access Service Edge solution. This integration enables admins to intercept and inspect network traffic, detect sensitive data, and enforce Data Loss Prevention policies in real time. The update will be available in preview by May 2025.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=488807](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=488807)

### May 2025 – Enterprise Application Insights for SharePoint Sites

Microsoft will introduce a new report on enterprise application insights, helping SPO admins monitor SharePoint sites accessed by third-party apps registered in the tenant.  
The report provides detailed insights into app permissions and the number of requests, assisting admins in ensuring the security of the site. This report is a part of SharePoint Advanced Management capabilities.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=417481](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=417481)

### May 2025 - Data Loss Prevention (DLP) Alerts as Indicators in IRM Policies

Microsoft Purview Insider Risk Management will enable admins to use Data Loss Prevention alerts as indicators within IRM policies. This feature will help admins track DLP alerts tied to specific policies in IRM, making it easier to detect high-risk alerts without the need to switch to DLP.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=475057](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=475057)

### Early-May 2025 - New “Report a Security Concern” Feature in Microsoft Teams Admin Center

Microsoft 365 admin center is introducing a new setting, "Report a Security Concern." Admins can enable this feature to allow users to report security risks involving external users in one-on-one chats, group chats, and meeting chats.

**Note**: Shared channels are not supported at this time

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1037768](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1037768)

### Early-May 2025 – New Sensitivity Labels for Microsoft Loop Components

Microsoft will introduce the ability to apply sensitivity labels to Microsoft Loop components within Teams messages. This feature allows users to set, apply, and view sensitivity labels to classify and protect content in Loop components shared through Teams messages.

  
**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1064352](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1064352)

### Early-May 2025 - Automatically Display Automapped Calendars in Microsoft Outlook

Microsoft is encouraging users to switch to the new Outlook for Windows. To make the transition smoother, they have introduced an auto-mapping feature that ensures users can seamlessly access their automapped calendars when moving from classic Outlook to the new Outlook for Windows.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=415168](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=415168)

### Mid-May 2025 – New Filters in Microsoft Purview Audit Search

To help you retrieve relevant logs in the Microsoft Purview audit search, Microsoft will include four additional filters in general availability. They are,  

*   Id – Unique identifier of an audit record.
*   UserType – The type of user that performed the operation.
*   UserKey-Azure Active Directory Object ID in GUID format.
*   ClientIP – The IP address of the device that was used when the activity was logged.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC789312](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC789312)

### Mid -May 2025 - Third-party Add-in User Report can be Sent to Microsoft for Analysis

Admins using third-party add-ins for report message solutions can now configure Defender for Office 365 to automatically send user-reported messages to Microsoft for analysis.

Sending these messages to Microsoft for analysis not only provides valuable insights for security analysts but also improves the accuracy of Defender for Office 365 filters.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC962528](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC962528)

### Mid-May 2025 – New Compromised User Context in Insider Risk Management

Microsoft Entra provides two types of compromised user detections: Sign-in risk and User risk detections. These detections will now be integrated into the Insider Risk Management alert investigation experience.

With this update, admins can view compromised user alerts from Microsoft Entra while investigating users, enabling them to take appropriate action and faster remediation.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1006621](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1006621)

### Late-May 2025 - Org Explorer Feature for Enterprise Users

Starting late-May 2025, the Org Explorer feature will be available to all enterprise users using new Outlook for Windows, Outlook for Web, and Outlook for Mac. It provides insights into internal structures and connections.

**Note**: Switch to the new Outlook for Windows or Outlook for web to have early access to this new feature.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC939925](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC939925)

### Late-May 2025 - Data Loss Prevention: New Data Protection in Microsoft Edge for Business on Unmanaged Devices

Microsoft is adding Data Loss Prevention capabilities to the Microsoft Edge for Business browser. Once available, admins can configure DLP policies to monitor and control user activities, such as, sharing data to or exfiltrating data from organization-managed cloud apps—when using Edge for Business on unmanaged devices.

**_Ref:_** [https://admin.microsoft.com/#/MessageCenter/:/messages/MC1045278](https://admin.microsoft.com/#/MessageCenter/:/messages/MC1045278)

### Enhancements

### Early-May 2025 – Customize SharePoint Sites with Multi-Color Themes

Microsoft SharePoint will offer site owners the ability to apply multi-color themes. This feature can be used through the Site branding options or the organization’s brand center, giving more flexibility in customizing site appearances.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1062451](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1062451)

### May 2025 - Add Shared Mailbox as Accounts in New Outlook for Windows

Starting May 2025, you’ll be able to add shared mailboxes as accounts in the New Outlook for Windows. With the necessary permissions, you can access these shared mailboxes by providing the user’s credentials.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=375635](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=375635)

### May 2025 – Updates to Existing IRM Office Indicator

Microsoft will enhance the existing IRM Office Indicator to provide more comprehensive tracking of sensitivity label changes. Currently, it tracks sensitivity label changes only on the SharePoint Web app. With the upcoming update, it will also capture sensitivity label changes (such as downgrades or removals) across OneDrive, AIP, and endpoints. This includes SharePoint files opened in Office apps and sensitivity label changes on local files on your device.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=473431](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=473431)

### May 2025 - Multi-policy Selection in Adaptive Protection of IRM

In Insider Risk Management, the "Risk levels for Adaptive Protection" setting lets admins assign risk levels to configured policies. Previously, admins could apply risk levels to only one policy at a time. With this update, they can now select multiple policies at once, making it easier to manage risk levels in Adaptive Protection.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=171735](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=171735)

### Mid-May 2025 - Policy Alerts Improvements in Microsoft Purview Communication Compliance

Communication Compliance is enhancing policy alert customization. Admins will have the ability to set the alert frequency for each policy and adjust the email alert frequency and recipients directly within the policy creation wizard, via the new alerts page. This update will be generally available from mid-May 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920304](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920304)

### May 19, 2025 – Microsoft Defender for Mobile: Logging Open Wi-Fi Connections and Suspicious Certificate Detections

Microsoft will enhance the Open Wi-Fi and Cert Detection for Android features in Microsoft Defender for Mobile to help reduce alert fatigue. From this update, when a user connects to an open Wi-Fi network or encounters a suspicious certificate during the download or installation process, these activities will be logged instead of triggering alerts. This allows admins to track and review these events without overwhelming them with constant alerts.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1057719](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1057719)

### Late-May 2025 - Endpoint Data Loss Prevention Supports Microsoft Edge to Enforce Restrictions on Files

Microsoft will extend Endpoint Data Loss Prevention (EDLP) policies in Microsoft Purview to apply restrictions on the Microsoft Edge browser. Previously, admins could configure restrictions on removable USB devices, network shares, and printer groups within EDLP policies. With this update, these same restrictions will now be enforceable in Microsoft Edge, providing organizations with more granular control over data loss prevention.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=486370](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=486370)

### Existing Functionality Changes

### Early-May 2025 – Microsoft OneDrive: Removal of the Enable OCSI for Tenants Group Policy

Starting early May 2025, Microsoft will enforce the "EnableAllOcsiClients" setting for all tenants, which allows multiple users to co-author Office files in OneDrive using Microsoft 365 Apps, Office 2019, or Office 2016 desktop apps. This setting also enables in-app file sharing. Previously, admins could disable this setting to block co-authoring and sharing. However, with this update, the GPO will be removed, ensuring smooth functionality for features such as AutoSave, version history, real-time collaboration, and conflict merging.

**_Ref:_** [https://learn.microsoft.com/en-us/sharepoint/use-group-policy#coauthor-and-share-in-office-desktop-apps](https://learn.microsoft.com/en-us/sharepoint/use-group-policy#coauthor-and-share-in-office-desktop-apps)

### Early-May 2025 – Data Lifecycle Management: Separate Copilot Retention Policies from Teams Chats

Currently, Teams chat and Copilot interactions share the same Purview Data Lifecycle Management policy. After the update, admins can create separate retention policies for Copilot interactions, managing them independently from Teams chat. This feature will be rolled out to public preview by early-May 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC926899](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC926899)

### May 12, 2025 - Sender Email Address Update for Microsoft Teams DLP Generate Incident Report Emails

Microsoft is changing the sender address for Teams DLP Generate Incident Report (GIR) emails. From May 12 to May 26, 2025, emails will come from either the old address ([no-reply-MicrosoftInformationProtectionOnline@microsoft.com](mailto:no-reply-MicrosoftInformationProtectionOnline@microsoft.com)) or the new one ([no-reply@teams.mail.microsoft.com](mailto:no-reply@teams.mail.microsoft.com)). After May 26, 2025, only the new address ([no-reply@teams.mail.microsoft.com](mailto:no-reply@teams.mail.microsoft.com)) will be used.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1064354](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1064354)

### Mid-May- 2025 - Updates to App Governance Pre-Defined Policies in Defender for Cloud Apps

Starting mid-May 2025, Microsoft Defender for Cloud Apps will disable three pre-defined policies by default to improve alert accuracy. The policies being disabled are

*   Increase in data usage by an overprivileged or highly privileged app
*   Unusual activity from an app with priority account consent
*   Access to sensitive data

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1036568](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1036568)

### Mid-May 2025 – Report Conversations Feature in the New Microsoft Viva Engage Admin Center

The report conversations feature in Viva Engage helps admins set up a reporting mechanism for Engage conversations within their network. This feature will be moved from the legacy Microsoft Yammer Admin Center and made available in the new Microsoft Viva Engage Admin Center.

**_Ref_**: [https://admin.microsoft.com/#/MessageCenter/:/messages/MC1061721](https://admin.microsoft.com/#/MessageCenter/:/messages/MC1061721)

### May 26, 2025 - Limited Microsoft Planner Functionality for Shared Mailbox Users

  
Due to permission model limitations, Microsoft will no longer allow shared mailbox accounts to perform actions like adding or editing tasks, uploading attachments, or adding task comments in Planner (both in Teams and on the web).

**Solution:** Convert shared mailboxes to user mailboxes to allow users to interact with Planner tasks.

**Note:** A temporary workaround is available but will be phased out in 30 days. Contact Microsoft to enable the temporary workaround.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1064044](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1064044)

### Action Required

### May 1, 2025 - Microsoft Defender for Cloud Apps Network Configuration Changes

Due to ongoing updates in Microsoft Defender for Cloud Apps, admins are required to update firewall rules and third-party services with new network information to maintain uninterrupted service access. Admins need to ensure that the following endpoints are allowed:

*   discoveryresources-cdn-prod.cloudappsecurity.com
*   discoveryresources-cdn-gov.cloudappsecurity.us

If updates aren't made, admins may no longer see the organization logo on the Microsoft 365 portal overview page once the change goes live.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1060467](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1060467)

### Mid-May 2025 - Intune Service Administrator Role will be Required for Device Limit Restrictions

Starting mid-May 2025, configuring device limit enrollment restrictions will require the 'Intune Service Administrator' RBAC permission.

**Solution:** Review and update your RBAC assignments as needed to maintain full control.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1034571](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1034571)

## June 2025 (Attention Needed: 15)

### Retirements:

### June 30, 2025 - Retirement of Private Content Mode in Via Engage

Microsoft Viva Engage will retire the "Private Content Mode" by June 30, 2025. After this date, verified admins will no longer be able to enable or disable this feature.

**Solution:**

The following alternatives will be available:

*   Admins can join private communities without approval: Global or Groups Administrators can now access private communities directly, with no approval needed.
*   Group members and owners visible in Entra ID: All users can see group members and owners in Entra ID, even without being part of the community.
*   eDiscovery admins can access private content: Compliance and eDiscovery admins can search and export private content for legal or audit purposes.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1045211](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1045211)

### New Features

  

### Early-June 2025 - Insider Risk Management: Enhanced Alert and User Investigation with Microsoft Copilot for Security

Admins will gain enhanced alert and user investigation capabilities with Insider Risk Management (IRM) using Microsoft Copilot for Security. Along with concise alert summaries, admins can delve into specific user activities with Copilot for Security. These enhancements will help admins make informed decisions on whether to investigate users further or dismiss the alerts appropriately.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC851630](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC851630)

### June 2025 - Just in Time Protection on SharePoint in DLP

Microsoft is introducing Just-in-Time protection for SharePoint in Microsoft Purview Data Loss Prevention.

With this feature, organizations can automatically apply DLP restrictions to unclassified files when they are accessed or shared externally. Instead of restricting files in advance, JIT protection enforces security measures only when there is a risk of data leaving the organization.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457)

### June 2025 - Message Recall Feature for Outlook for Mac

The Cloud-based Exchange Online Message Recall feature will soon be available for Outlook for Mac users, with a preview rollout scheduled for June 2025.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=189804](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=189804)

### June 2025 - Date Lifecycle Management and Power Automate Integration in U.S Government Clouds

U.S. government cloud users can automate actions on items at the end of their retention period using Power Automate by June 2025.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=117523](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=117523)

### Mid-June 2025 - New Email Indicators in Insider Risk Management

Microsoft Purview Insider Risk Management will introduce two new email indicators:

1.  **Email with Attachments to Free Public Domains**: Alerts when sensitive data is sent to free public domain emails.
2.  **Email with Attachments to Self**: Alerts when sensitive data is sent to a personal email or self.  
    

Admins can use these two email indicators within the Data Leaks or Data Theft policy templates to enhance monitoring and protection.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1051101](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1051101)

### Mid-June 2025 - Insider Risk Management- Risky AI Usage

New detections in Insider Risk Management will be generally available, enabling admins to identify risky AI activity, such as sensitive prompts, risky intents, and AI-generated sensitive content. This applies to M365 Copilot, Copilot Studio, and ChatGPT Enterprise, contributing to Adaptive Protection risk levels.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC947048](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC947048)

### Late-June 2025 – IRM Alerts in Microsoft Defender XDR

Microsoft Purview’s Insider Risk Management (IRM) data will integrate with Microsoft Defender XDR, enabling comprehensive investigation and correlation. IRM data will be accessible through the unified alert and incident queue, advanced hunting with KQL queries, Graph API, and Microsoft Sentinel. This feature will roll out to general availability by mid-June 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC961761](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC961761)

### Enhancements

### June 2025: Block Specific Folders from OneDrive Sync

Starting June 2025, admins can block not just files or extensions but also specific folders from syncing with OneDrive through Group Policy.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=178292](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=178292)

### June 2025 – Information Protection: On-demand Classification of Files in SharePoint and OneDrive for Business

Microsoft Purview is introducing on-demand classification for files in SharePoint Online and OneDrive, enabling the discovery and classification of sensitive content in historical data—including files that were never scanned or haven't been scanned in a while. On-demand classification of files is a pay-as-you-go feature (not part of the E5 license).  
  
Ref: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1013459](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1013459)

### Early – June 2025 - Changes to Threat Protection Capabilities in Microsoft Defender for Cloud Apps

Microsoft Defender for Cloud Apps is rolling out a new dynamic detection model starting June 2025. This model allows Microsoft to automatically update, add, or remove detection policies based on emerging threats.

As part of this change, legacy built-in policies will be disabled (but temporarily visible), and their associated governance actions will not carry over. The first set of policies transitioning to this new model includes:

1.  Suspicious inbox manipulation rule
2.  Suspicious email deletion activity
3.  Suspicious email forwarding rule
4.  Activity from an anonymous proxy
5.  Activity from a botnet-associated IP address.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1061724](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1061724)

### Late-June 2025 – Insider Risk Management: Enhancements to User Scoping Features in Policies

Insider Risk Management admins with appropriate permissions can now select combinations of users, groups, and adaptive scopes to include or exclude from Insider Risk Management policies in the Microsoft Purview portal. Microsoft is also adding support for non-email enabled Security Groups within Insider Risk Management policies.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1047928](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1047928)

### Existing Functionality Changes

### Late - June 2025 - Search-MailboxAuditLog and New-MailboxAuditLogSearch Cmdlets Will Become Static

Microsoft plans to deprecate the Search-MailboxAuditLog and New-MailboxAuditLogSearch cmdlets. However, admins can continue to access the old logs and download data using these cmdlets until late June 2025. After that, the cmdlets will become read-only, and no further changes or downloads will be possible.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310](https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310)

### Late - June 2025 – Decoupling of Policy Tips and Email Notifications for SharePoint and OneDrive

Currently, enabling email notifications for a DLP policy also requires enabling the policy tips, and vice versa. However, Microsoft will soon allow admins to configure email notifications and policy tips independently for SharePoint and OneDrive DLP policies. This update will be rolled out to Public preview by late June 2025.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=394279](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=394279)

### Action Required:  

### June 1, 2025– Microsoft Viva Engage: External Networks are Being Modernized

Microsoft Viva Engage will modernize External Networks. So, legacy external networks will be retired starting June 1, 2025.

**Solution:** Admins must migrate to the new platform before May 31, 2025, to avoid data loss.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1036575](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1036575)

## Q3 2025 (Attention Needed: 11)

### July 2025 – New Cmdlet for Content Explorer

A new cmdlet, _Export-ContentExplorerData_, will be rolled out to U.S Government clouds by July 2025. This cmdlet allows admins to export all scanned content data from Content Explorer, providing a streamlined way to manage and analyze content data.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=117531](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=117531)

### After July 1, 2025 – Azure AD PowerShell Retirement

The Azure AD PowerShell module will be retired after July 1, 2025.  

**Solution**: Migrate to Microsoft Graph PowerShell SDK or Microsoft Entra PowerShell module.  

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991)

### July 1, 2025 – Azure AD Graph API Will Be Fully Retired

If you've extended the use of Azure AD Graph API, it will no longer work after June 30, 2025. Azure AD Graph will be fully retired, and all Azure AD Graph API requests will stop functioning from July 1, 2025.

**Solution**: Review the application that uses the Azure AD Graph API and migrate them to Microsoft Graph.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-azure-ad-graph-api-retirement/4090533](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-azure-ad-graph-api-retirement/4090533)

**July 1, 2025 – DNS Provision Change**  
  
Starting July 1, 2025, A records for new Accepted Domains will move from mail.protection.outlook.com to subdomains under mx.microsoft to support DNSSEC.

**Action Required:** If you have automation that configures MX records, you must update it to use the **List serviceConfigurationRecords Graph API** to retrieve the correct MX values. After July 1, this API will be the only reliable source for MX records. Failing to update may result in mail flow issues for new domains.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1064044](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1064044)

### July 1, 2025- Classic Teams Desktop App End of Availability

Starting July 1, 2025, classic Teams desktop app will reach end of availability for all users irrespective of OS.

**Note**: From Oct 23, 2024, classic Teams desktop app on Windows 7,8,8.1 and Mac OS Sierra (10.12) will reach end of availability.

**Solution:** Users need to switch to new Teams, or they can use Teams web app (on supported browser) as an alternative.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783985](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783985)

### August 1, 2025 - Retirement of Classic e-Discovery in Microsoft Purview

Starting August 1, 2025, Microsoft will retire Classic eDiscovery, including Content Search, eDiscovery (Standard), and eDiscovery (Premium), from the Microsoft 365 Purview portal.

**Solution:** Transition to the new unified eDiscovery for faster and improved search and investigation capabilities.  

**_Ref:_** [https://learn.microsoft.com/en-us/purview/ediscovery-legacy-retirement](https://learn.microsoft.com/en-us/purview/ediscovery-legacy-retirement)

### August 2025 - Mail Merge (Advanced) on Outlook on the Web and New Outlook for Windows  

Enhanced mail merge features are coming to Outlook on the Web and the new Outlook for Windows in August 2025. Users will be able to insert dynamic fields into email templates for personalized emails and advanced customizations.  

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047)

### Sep 2025- Basic Auth for Client Submission (SMTP AUTH) Retirement in Exchange Online

Exchange Online will permanently remove support for Basic authentication with Client Submission (SMTP AUTH) in September 2025.

**Solution:** You can start to use OAuth with Client Submission (SMTP AUTH).

**_Ref_**: [https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-retire-basic-auth-for-client-submission-smtp/ba-p/4114750](https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-retire-basic-auth-for-client-submission-smtp/ba-p/4114750)

### Early-Sep 2025 - General Availability of Progressive Alert Scoring in IRM

Microsoft will roll out a new feature -" Progressive alert scoring" in Microsoft Purview Insider Risk Management. Currently, user activities that could potentially result in data security incidents will be assessed once every 24 hours. After this rollout, the assessment of user activities will be done more frequently within a 24- hour period, along with alert insights. This feature will be generally available for GCC, GCC-High, DoD environments by early-Sep 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC707653](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC707653)

### Mid-Sep - 2025 - Data Lifecycle Management: Retention Based on “last accessed” for OneDrive and SharePoint Files

Starting mid-Sep2025, Microsoft will introduce a "When items were last accessed" option in Purview retention policies. This will allow admins to configure retention policies based on file access history in OneDrive and SharePoint, enabling the removal of outdated data.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442  
](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442)

### Late-Sep 2025 - New Secure Workflow to Bypass Legal Holds and Retention Policies in Microsoft Purview

Admins will have the ability to permanently delete sensitive Exchange mailbox content; bypassing retention policies and eDiscovery holds. This will be possible through the “Priority Cleanup Administrator” role, which grants authorized users’ permission to initiate Priority Cleanup for Exchange, allowing exceptions to standard retention and legal hold policies.

Since this process is irreversible and overrides existing policies, Microsoft has built-in approvals and special auditing for security.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC971035](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC971035)

### Sep 30, 2025 – Retirement of Managing Authentication Methods in Legacy MFA &SSPR Policy

Starting Oct 2025, Microsoft no longer allow authentication methods to be managed in the legacy MFA and SSPR policies.

**Solution:** Organizations should use the converged authentication methods policy where methods can be managed centrally for all authentication scenarios including passwordless, MFA and SSPR.

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448)

## Q4 2025 (Attention Needed: 10)

### Oct 2025 – External Recipient Rate Limit in Exchange Online

Exchange Online will begin enforcing an External Recipient Rate (ERR) limit of 2,000 recipients within 24 hours. This restriction will apply to the cloud-hosted mailboxes of all newly created tenants.

**Note:** Exchange Online currently enforces a Recipient Rate limit of 10,000 recipients for cloud-hosted mailboxes. The 2,000 ERR limit will be a sublimit within this 10,000 Recipient Rate limit.

Ref: [https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733](https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733)

### Oct 2025 – Adding Support for SMTP DANE with DNSSEC for Exchange Online

Microsoft is adding inbound support for SMTP DANE with DNSSEC to Exchange Online GCC High and DoD.

Ref: [https://www.microsoft.com/en-in/microsoft-365/roadmap?featureid=361914&searchterms=361914](https://www.microsoft.com/en-in/microsoft-365/roadmap?featureid=361914&searchterms=361914)

### October 2025 – New Personalization Settings in Microsoft Purview

Microsoft will introduce a new personalization page in Microsoft Purview, allowing admins to customize their experience. New features will include the ability to pin/unpin solutions, toggle solution bar visibility, access solution walk-throughs, export personalization data, and delete preferences. This update will help streamline the management of individual admin experiences within Microsoft Purview.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=483884](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=483884)

### October 2025 – Enhanced Capabilities in Information Barriers V2

Microsoft will upgrade Information Barriers (IB) from version 1 to version 2, introducing new capabilities like:

*   Larger segment scale
*   Multi-segment support
*   Flexible people discoverability

Existing IB v1 users can upgrade to IB v2 to access this enhanced feature.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=115482](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=115482)

  

### Oct 14, 2025 - End of Office 2016 and Office 2019 Support

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

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC921752](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC921752)

### After Oct 2025 – End of Support for Legacy Microsoft Outlook for Mac

As part of Microsoft's commitment to a more secure and robust email experience, Microsoft 365 subscriptions linked to a personal, work, or school account will no longer support the legacy version of Microsoft Outlook for Mac.

**Solution:** Upgrade to the latest version of Outlook for Mac, which is built on modern technology for improved performance, security, and reliability.

**_Ref:_** [https://support.microsoft.com/en-us/office/end-of-support-for-legacy-outlook-for-mac-7b9cf644-7035-4345-a151-8c1c7a65ac25](https://support.microsoft.com/en-us/office/end-of-support-for-legacy-outlook-for-mac-7b9cf644-7035-4345-a151-8c1c7a65ac25)

### Dec 2025 - Existing Office 365 Connectors will stop Working

Existing Office 365 connectors will continue to work until December 2025, after which they will no longer work.

**_Ref:_** [https://learn.microsoft.com/en-us/power-bi/connect-data/service-publish-from-excel](https://learn.microsoft.com/en-us/power-bi/connect-data/service-publish-from-excel)

### Dec 2025 - Integration of New ChatGPT Enterprise Connector with Microsoft Purview Compliance Portal

The ChatGPT Enterprise connector will be integrated into the Microsoft Purview Compliance portal, allowing admins to discover, collect, and store prompts and responses from users' interactions with ChatGPT.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=401125](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=401125)

## 2026 (Attention Needed: 14)

### Jan 13, 2026 – End of Extended Support for Microsoft Advanced Threat Analytics 1.x

Microsoft Advanced Threat Analytics (ATA) extended support will be ended on January 13, 2026.

**Solution**: Updates for Microsoft ATA are available from Microsoft Update or by manual download.

**_Ref_**: [https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c](https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c)

### March 2026 - Long-term Retention Period for Microsoft 365 Backup

Admins will be able to configure longer-term retention for Microsoft 365 backups, allowing data storage beyond one year. This feature will be available in preview by March 2026.  

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=481834](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=481834)

### Mar 31, 2026- Deprecation of ‘Require Approved Client App’ Conditional Access Grant

The Require approved client app control in Azure Active Directory (Azure AD) Conditional Access will be retired and no longer enforced.

**Solution:** You can make use of the “Require app protection policy” control, which has all the same capabilities

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448)

### April 2025 - Retirement of Certain Dynamic Data Exchange features in Microsoft Word

Microsoft Word will retire some Dynamic Data Exchange features that were previously disabled in 2017. These features, controlled by a registry key, will be fully removed in April 2025, and the registry key will no longer be available.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC863140](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC863140)

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

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865)

### Apr 02, 2026 – Azure ACS Retirement in Microsoft 365

After April 2, 2026, existing tenants using Azure ACS for custom or third-party app access in SharePoint Online will no longer function due to its retirement.

**Solution:** Admins can utilize the Microsoft 365 Assessment tool to scan the tenants for any usage of Azure Access Control Service (ACS) and [migrating from Azure ACS to Microsoft Entra ID](https://aka.ms/retirement/acs/guidance).

**_Ref:_** [https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/retirement-announcement-for-azure-acs](https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/retirement-announcement-for-azure-acs)

### Apr 02, 2026 - Retirement of Domain Isolated Web Part in SharePoint Framework

  
From Apr 02, 2026, the domain isolated web part feature will be fully retired. Organizations using this feature will receive an error message.

**Solution:** Update your domain isolated web parts to regular web parts and redeploy them to ensure continued functionality.

**_Ref:_** [https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/](https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/)

### Mar 2026 - Retirement of "Require Approved Client App" Grant Control" in Entra ID Conditional Access

The Conditional Access "Require approved client app" grant control is being retired from Microsoft Entra ID & Microsoft Intune by March 2026.

**Solution:** Use the "Require application protection policy" grant control, which offers the same data loss prevention while providing enhanced security benefits.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1029989](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1029989)

### July 14, 2026- InfoPath 2013 Client and InfoPath Forms Services in SharePoint Online will be Retired

  
  
InfoPath Client 2013 will reach the end of its extended support period on July 14, 2026, and to keep an aligned experience across Microsoft products, InfoPath Forms Service will be retired from SharePoint Online.

**Solution:** To understand the usage of InfoPath within your organization, you can utilize the [Microsoft 365 Assessment tool](https://aka.ms/assessment/infopath) to scan your tenant and analyze InfoPath usage. If you are currently using InfoPath, you can initiate the migration process to modern alternatives such as Power Apps, Power Automate, or Forms.

**_Ref_**: [https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190](https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190)

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