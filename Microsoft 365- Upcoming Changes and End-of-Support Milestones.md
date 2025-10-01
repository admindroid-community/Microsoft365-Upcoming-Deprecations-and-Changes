# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.  
  
Discover the **key changes, deprecations**, and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

  
Here is a list of changes categorized by month and year.  

*   October 2025 (Retirements: 6, New Features: 10, Enhancements: 6, Existing Functionality Changes: 5, Action Needed: 4)
*   November 2025 (Retirements: 3, New Features: 9, Enhancements: 1, Existing Functionality Changes: 1, Action Needed: 1)
*   December 2025 (Attention Needed: 11)
*   Q1 2026 (Attention Needed: 13)
*   Q2 2026 (Attention Needed: 7)
*   Q3 2026 (Attention Needed: 3)
*   Q4 2026 (Attention Needed: 3)

  

## October 2025

### Retirements

### Oct 1, 2025 – Retirement of “Add to existing remediation” Option in Microsoft Defender for Office 365

When running a remediation on phishing emails, admins have the option “Add to existing remediation” to apply actions to messages as part of an ongoing remediation job. Since this option was rarely used, Microsoft has decided to retire the option.

**Solution:** Use the “Create new remediation” option instead, which allows admins to start a fresh remediation process for the selected emails.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1146813](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1146813)

### Oct 3, 2025 - Retirement of Web-based “Share to Teams” Experience from Outlook

The “Share to Teams” option in Outlook allows users to share Outlook content directly to Teams chat or channels. Microsoft plans to retire this standalone experience for users who do not have the Teams desktop installed. When such users try to use this option, they will be prompted to install the Teams desktop app via a launcher page. This update affects Outlook for Windows (new and classic), Outlook for Mac (new and legacy), and Outlook Web App (OWA) clients. The retirement will complete on Oct 3, 2025.

**Solution**: Install Teams desktop app to use the “Share to Teams” option.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1140180](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1140180)

### Oct 6, 2025 – Retirement of Outlook Lite App

Microsoft will retire the Outlook Lite app starting Oct 6, 2025, with new installations blocked after this date.

**Solution:** Use the Outlook Mobile app for secure and feature-rich email experience.

**_Ref_**: [https://support.microsoft.com/en-us/office/get-help-with-outlook-lite-for-android-78eb02b2-1c16-4da3-90e2-5edd14bcafa0](https://support.microsoft.com/en-us/office/get-help-with-outlook-lite-for-android-78eb02b2-1c16-4da3-90e2-5edd14bcafa0)

### Oct 14, 2025 - Microsoft OneNote for Windows 10 retirement

To offer a unified and modern OneNote experience, Microsoft will retire the OneNote for Windows 10 app on October 14, 2025. After this date, the app will become read-only and will no longer receive support.

**Solution:** Switch users to the Microsoft OneNote for Windows app, which features a sleek, modernized interface and enhanced security.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC899174](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC899174)

### Oct 31, 2025 - Retirement of the SharePoint SendEmail API

The _SP.Utilities.Utility.SendEmail_ API in SharePoint will be retired on October 31, 2025. Admins can identify the usage of the API via Purview audit log. Any components, custom code, or Power Automate flows relying on this API should be updated before its retirement.

**Solution:** Consider transitioning to modern solutions such as the Microsoft Graph API or Power Automate’s Outlook connector for email functionality.

**_Ref_**: [https://support.microsoft.com/en-us/office/retirement-of-the-sharepoint-sendemail-api-b35bbab1-7d09-455f-8737-c2de63fe0821](https://support.microsoft.com/en-us/office/retirement-of-the-sharepoint-sendemail-api-b35bbab1-7d09-455f-8737-c2de63fe0821)

### After Oct 2025 – End of Support for Legacy Microsoft Outlook for Mac

As part of Microsoft's commitment to a more secure and robust email experience, Microsoft 365 subscriptions linked to a personal, work, or school account will no longer support the legacy version of Microsoft Outlook for Mac.

**Solution:** Upgrade to the latest version of Outlook for Mac, which is built on modern technology for improved performance, security, and reliability.

**_Ref:_** [https://support.microsoft.com/en-us/office/end-of-support-for-legacy-outlook-for-mac-7b9cf644-7035-4345-a151-8c1c7a65ac25](https://support.microsoft.com/en-us/office/end-of-support-for-legacy-outlook-for-mac-7b9cf644-7035-4345-a151-8c1c7a65ac25)

### New Features

### Early-Oct 2025 – New Admin Control in Microsoft 365 Admin Center for Org-wide Sharing of User-built Copilot Agents

Admins can control who can create org-wide sharing links for agents built using Copilot Studio agent builders. This allows admins to achieve granular control, governance, and better alignment with organizational policies.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1138797](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1138797)

### Early-Oct 2025 – Microsoft Entra ID Free Subscription

  
Microsoft is adding a free subscription called Entra ID Free to help you keep track of which tenants you own. It will start showing up in Microsoft 365 and Azure portals from October. Microsoft is adding a free subscription called Entra ID Free to help you keep track of which tenants you own.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1156361](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1156361)

### Early-Oct 2025 – AI-Powered Data Security Investigations in Microsoft Purview

Microsoft Purview is launching Data Security Investigations (DSI), an AI-driven solution that helps security teams detect, analyze, and mitigate data risks. It provides deep content analysis, visualizes correlations, and simplifies policy refinement, all within a unified experience. It will be available in general availability by early-Oct 2025.  
  
**_Ref_**: [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1047912](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1047912)

### Early-Oct 2025 – New SharePoint Assessment and Dashboard to Streamline Site Governance

Microsoft will introduce a Content Management Assessment (CMA) in SharePoint Advanced Management. This allows admins to view site health, permissions, and lifecycle readiness from a single console. The dashboard consolidates multiple reports such as Data Access Governance and Site Lifecycle Management and provides recommendations.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1148538](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1148538)

### Early-Oct 2025 – Streamlined Same-Device Number Matching and First Run Experience (FRX) in Microsoft Authenticator

Microsoft Authenticator will receive two updates to improve the users’ sign-in experience within early-oct 2025:

*   **Same-device sign-ins will no longer require number matching**: Users can simply tap “Yes” or “No” to confirm, reducing friction, especially on Android. iOS users will also benefit, though app switching may still be needed with the SSO extension.
*   **Improved First Run Experience (FRX):** Microsoft simplifies account setup by combining multiple consent pages into consolidated one. It also prioritizes signing in with a Microsoft Entra account (work or school) instead of a personal Microsoft account.

**_Ref_:** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1117816](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1117816)

### Oct 2025 - Information Barriers Upgrade from IB v1 to IB v2

Information Barriers V2 introduces larger segment support, multi-segment capabilities, and flexible discoverability. Tenants that have not yet enabled Information Barriers will automatically get IB V2 when they turn it on for the first time. Those already using IB V1 must upgrade to V2 to benefit from these enhancements.  
  
**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=115482](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=115482)

### October 2025 - Just in Time Protection on SharePoint in DLP

Microsoft is introducing Just-in-Time protection for SharePoint in Microsoft Purview Data Loss Prevention in preview.

With this feature, organizations can automatically apply DLP restrictions to unclassified files when they are accessed or shared externally. Instead of restricting files in advance, JIT protection enforces security measures only when there is a risk of data leaving the organization.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457)

### Mid-Oct 2025 – Cross-cloud Synchronization in Microsoft Entra

Microsoft Entra will introduce cross-cloud synchronization in public preview. This helps admins automate user lifecycle management across Microsoft commercial, US Government, and China clouds, allowing the automated creation, updating, and deletion of users across supported cloud pairs. This is an opt-in feature and will be available completely by mid-Oct 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1124558](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1124558)

### Mid-Oct 2025 – Drag and Drop Between Accounts Coming to New Outlook for Windows

The new Microsoft Outlook for Windows adds drag and drop support to attach emails and files between personal or enterprise accounts, improving cross-account productivity. This update also allows attaching content from shared mailboxes or shared folders into another mailbox. Admins can control this capability using the _ItemsToOtherAccountsEnabled_ parameter in _OWAMailboxPolicy_. The feature will be rolled out in general availability by mid-Oct 2025.

**_Ref_**: [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1104315](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1104315)

### Late-Oct 2025 – Control External Access by Domain for Specific Users and Groups in Teams

Currently, external access settings can only be configured at the tenant level. Microsoft Teams is adding a new external collaboration feature that lets admins control which users or groups can interact with specific external domains. This provides more granular control, such as piloting with certain departments, restricting high-risk roles, or enabling broader federation.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1150123](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1150123)

### Enhancements

### Early-Oct 2025 – Updated Sender Email Address for Channel Guest Invitations in Teams

To support backend service improvements and enhance email deliverability, Microsoft Teams is updating the default sender address used for guest access invitations to Teams channels. The sender address will change from [noreply@microsoft.com](mailto:noreply@microsoft.com) to [no-reply@teams.mail.microsoft](mailto:no-reply@teams.mail.microsoft). Admins need to manage the allow lists or email filtering policies to permit the new sender address.

**_Ref:_** [https://admin.microsoft.com/#/MessageCenter/:/messages/MC1148535](https://admin.microsoft.com/#/MessageCenter/:/messages/MC1148535)

### Oct 2025 – OCR Support for Endpoint in Microsoft Purview Compliance Portal  

Microsoft Purview Compliance Portal will gain Optical Character Recognition (OCR) support on Windows endpoints. With this update, DLP policies will be able to detect and act on sensitive content within images, helping prevent data leaks. Supported file types include JPG, JPEG, PNG, TIFF, BMP, and image-based PDFs.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=160008](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=160008)

### Oct 2025 – Adding Support for SMTP DANE with DNSSEC for Exchange Online

Microsoft is adding inbound support for SMTP DANE with DNSSEC to Exchange Online GCC High and DoD. This enhancement will be available in preview starting October 2025, further strengthening email security for these environments.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?featureid=361914&searchterms=361914](https://www.microsoft.com/en-in/microsoft-365/roadmap?featureid=361914&searchterms=361914)

### Mid-Oct 2025 – Unified Licensing View in Microsoft 365 Admin Center

Microsoft is rolling out a refreshed licensing experience in the Microsoft 365 admin center to improve visibility into license assignments.  

1.  A **unified licensing view** will consolidate both user-based and group-based license assignments into a single list.
2.  The **Licensing Errors** tab will highlight user-level issues from group-based assignments, categorize them, and suggest resolutions.
3.  A **Users without licenses** page will show users in licensed groups who haven’t received licenses due to insufficient availability.

**_Ref:_** [https://admin.microsoft.com/#/MessageCenter/:/messages/MC1160187](https://admin.microsoft.com/#/MessageCenter/:/messages/MC1160187)

### Late-Oct 2025 – UX Improvements to DLP Alerts in Purview Portal

For faster alert investigation, Microsoft will roll out a unified view experience in the DLP alerts page in Microsoft 365.  
1\. Events related to each alert will be available directly on the alerts page.  
2\. Admins can access event details from the events page itself, reducing triage time.  
3\. Four new columns - Location, DLP policy name, DLP rule name, and Rule action, will provide better visibility.  
4\. Cache improvements will ensure faster load times and a smoother experience.

**_Ref:_** [https://admin.microsoft.com/#/MessageCenter/:/messages/MC1148526](https://admin.microsoft.com/#/MessageCenter/:/messages/MC1148526)

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

### Oct 27, 2025 – Changes to Office Script Admin Settings in Excel

Office Script settings let you control whether users in your organization can create and run scripts in Excel Online to automate tasks. Scripts can be run directly in Excel or integrated into Power Automate flows.  
  
Now, Microsoft is moving these settings from the Microsoft 365 admin center to Cloud Policy service for easier management. Admins should manage three specific settings:

1.  Let users automate their tasks in Excel
2.  Let users with access to Office Scripts share their scripts with others in the organization
3.  Let users with access to Office Scripts run their scripts with Power Automate.

If you leave these settings unchanged, they will be enabled by default.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1150681](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1150681)

### Late-Oct 2025 – Short Meeting URLs for Microsoft Teams

Microsoft plans to shorten the meeting URLs for easier sharing across all Teams platforms. The URL will contain only the meeting ID, and other parameters such as tenant ID, organizer ID, conversation ID, and message ID will not be included. The new URL format will be: [https://teams.microsoft.com/meet/<meeting\_id>?p=<HashedPasscode>](https://teams.microsoft.com/meet/%3Cmeeting_id%3E?p=%3CHashedPasscode%3E).  
  
By late October 2025, GCC High and DoD environments will be able to experience this change.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC772556](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC772556)

### Late-Oct 2025 – Removal of Microsoft Graph Beta API Property

By late October 2025, the _sendDeviceOwnershipChangePushNotification_ property will be removed from Microsoft Graph Beta API. This property previously triggered notifications when device ownership changed from personal to corporate, but it is now redundant since notifications are automatically sent.  
  
**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1127211](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1127211)

### Action Required

### Oct 14, 2025 – End of Support for Office 2016, Office 2019, and Additional Apps

Support for Office 2016, Office 2019, Visio 2016/2019, and Microsoft Project 2016/2019 will end on Oct 14, 2025. After this date, relying on unsupported software can cause security risks, system incompatibilities, and other issues.

**Solution:** Upgrade devices to Microsoft 365, Office LTSC 2024, or Office 365 suite that includes Microsoft 365 apps to mitigate the risks.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1154299](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1154299)

### Oct 20, 2025 – Legacy TLS Cipher Suites will be Deprecated in M365 Services

Microsoft 365 will deprecate legacy TLS cipher suites lacking forward secrecy on October 20, 2025. Only specified TLS 1.3 and 1.2 cipher suites will be supported.

**Solution:** Admins need to ensure all systems and clients support these approved suites, update legacy operating systems, adjust security or Group Policy settings if needed.

**_Ref_**: [https://admin.microsoft.com/#/MessageCenter/:/messages/MC1155427](https://admin.microsoft.com/#/MessageCenter/:/messages/MC1155427)

### Oct 20, 2025 – MFA Requirement for Credential Management

Microsoft will require users to complete an MFA prompt for all credential management activities performed on the “My sign-ins” page. Users will have to complete MFA if they have not authenticated within the last 10 minutes of their current session.  
  
**Solution**: Prepare your users for this change by informing them that they may be required to re-authenticate more frequently whenever they perform actions like password changes.

**_Note_**: In Message Center, there is a date inconsistency. Enforcement begins on August 15, while Microsoft sets the action deadline as Oct 20, 2025. It’s recommended to take precautionary steps early to prevent any disruption.  
**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1135479](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1135479)

### Oct 31, 2025 – Retirement of Deception Feature in Microsoft Defender for Endpoint

The Deception feature, which used decoys and lures to detect intrusions, will be retired.  
  
**Solution**: Adopt automatic attack disruption and exposure management features before October 30, 2025.  
  
**_Ref:_** [https://learn.microsoft.com/en-us/defender-xdr/deception-overview](https://learn.microsoft.com/en-us/defender-xdr/deception-overview)

### November 2025

### Retirements

### Nov 6, 2025 – ‘Mobile Devices’ Settings Page to Be Removed in Outlook  

The ‘Mobile Devices’ page in Outlook Web and the new Outlook currently allows users to view and manage all devices syncing with their mailbox. Microsoft will retire this page completely by Nov 6, 2025, as part of the shift toward modern device management tools.

**Solution:** Users can use the My Account portal or native iOS/Android tools to view, manage, and remotely wipe their connected devices.  
  
**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1130607](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1130607)

### Mid-Nov 2025 - Retirement of Power BI “Visualize the List” and “Visualize the Library” Features in SharePoint Online

The “Visualize the List” and “Visualize the Library” features in SharePoint Online allow users to quickly generate Power BI reports directly from SharePoint lists or libraries. To streamline the reporting experience, Microsoft has planned to retire these features.

**Solution**: Users will need to use Export to Power BI or Power BI Desktop to create reports from SharePoint data.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1156359](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1156359)

### Mid-Nov 2025 – Retirement of Microsoft Lists Mobile Apps for iOS and Android

  
Microsoft will retire the Microsoft Lists mobile apps for iOS and Android by mid-November 2025. After this date, the app will no longer appear in Google Play or the Apple App Store for installation.

**Solution**: Switch to Microsoft List mobile web version.

**_Ref_**: [https://support.microsoft.com/en-us/office/get-started-with-the-microsoft-lists-mobile-app-6abf88b7…](https://support.microsoft.com/en-us/office/get-started-with-the-microsoft-lists-mobile-app-6abf88b7-4c91-4af2-87c5-8d94afe34623)

### New Features

  

### Nov 1, 2025 - Knowledge Agent in SharePoint

Knowledge Agent brings AI-powered features directly into SharePoint to streamline content management and boost Copilot capabilities. It helps to:

*   Organize and enrich content for Copilot and agents to provide accurate answers.
*   Improve metadata and tagging with auto-fill suggestions and classification.
*   Keep content up-to-date by detecting broken links, retiring inactive pages, and identifying content gaps.
*   Assist as a co-author with templates, layout suggestions, and FAQs.
*   Respond to natural language questions and guide users to the right information.

From November 1, 2025, individual sites can opt in at their own pace.

Ref: [https://techcommunity.microsoft.com/blog/spblog/introducing-knowledge-agent-in-sharepoint/4454154](https://techcommunity.microsoft.com/blog/spblog/introducing-knowledge-agent-in-sharepoint/4454154)

### Early-November 2025 – Data Loss Prevention: New Inline Protection Controls for AI Apps in Microsoft Edge for Business

  
Microsoft Data Loss Prevention will roll out new inline protection capabilities for Microsoft Edge for Business. This helps admins block users from interacting with sensitive data in AI apps. For example, if users type prompts containing sensitive data into ChatGPT, Google Gemini, or Deepseek, it will be blocked. The inline protection capability complements existing endpoint DLP controls for uploading or pasting sensitive content in the browser.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=486368](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=486368)

### Early-Nov 2025 – Malicious URL Protection for Teams Chat and Channels

  
To improve protection against phishing attacks, Microsoft will display a warning in Teams when users receive malicious URLs in Teams chats and channels. Admins can manage this link protection feature in the Microsoft Teams Admin Center or by using the _\-UrlReputationCheck_ parameter in the _Set-CsTeamsMessagingConfiguration_ PowerShell cmdlet. This feature will reach general availability by November 2025.

**_Ref_**: [https://learn.microsoft.com/en-us/microsoftteams/malicious-url-protection-teams](https://learn.microsoft.com/en-us/microsoftteams/malicious-url-protection-teams)

### Early-Nov 2025 – SMTP Onboarding to App RBAC in Microsoft 365

Granting apps permission to send emails on behalf of mailboxes is now simpler. Currently, admins have to assign permissions individually for each mailbox using PowerShell. With App Role-Based Access Control (RBAC), admins can assign the _SMTP.SendAsApp_ role to an app for group-based or scoped mailbox access. This eliminates per-mailbox configuration, streamlines OAuth SMTP onboarding.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=498356](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=498356)

### Nov 2025 - Microsoft Entra ID to Support Passkey Profiles in Authentication Methods Policy

Microsoft Entra ID will introduce support for passkey profiles in the passkey (FIDO2) authentication methods policy. This update allows admins to apply different passkey configurations to specific user groups, offering more granular control. New schema changes will apply if configurations are made through the Azure or Entra portal during the preview.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1097225](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1097225)

### Early-Nov 2025 – Weaponizable File Protection in Microsoft Teams

  
To reduce malware risks, Microsoft will introduce a new feature that blocks messages containing weaponizable file types such as .ace, .ani, .apk, .app, .appx, .arj, .bat, and .cab in Teams chats and channels. Admins can enable this feature in the Microsoft Teams Admin Center or by using the _\-FileTypeCheck_ parameter in the _Set-CsTeamsMessagingConfiguration_ PowerShell cmdlet.

**_Ref:_** [https://learn.microsoft.com/en-us/microsoftteams/weaponizable-file-protection-teams](https://learn.microsoft.com/en-us/microsoftteams/weaponizable-file-protection-teams)

### Nov 2025 – Microsoft Purview Compliance Portal: Scan Existing Files in SharePoint and OneDrive for Sensitive Information

A new capability in the Microsoft Purview Compliance Portal will allow admins to scan existing files at rest in SharePoint and OneDrive for Business to detect sensitive information. This feature will roll out in preview by November 2025.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=499076](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=499076)

### Nov 2025 – Enterprise Application Insights for SharePoint Sites

  
SharePoint admins can use the new “Enterprise Application Insights” report to gain visibility into sites accessed by third-party applications registered in the tenant. The report shows detailed information such as application permissions and request counts, helping admins take action more effectively.  
  
**Note**: This is part of SharePoint Advanced Management capabilities.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=417481](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=417481)

### November 2025 - Insider Risk Management- Risky AI Usage

New detections in Insider Risk Management will be generally available, enabling admins to identify risky AI activity, such as sensitive prompts, risky intents, and AI-generated sensitive content. This applies to M365 Copilot, Copilot Studio, and ChatGPT Enterprise, contributing to Adaptive Protection risk levels.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=480730](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=480730)

### Nov 2025 - Integration of Insider Risk Management and Data Security Investigation

Microsoft Purview now integrates Insider Risk Management (IRM) with Data Security Investigation (DSI). This update allows data security admins to launch a pre-scoped investigation directly from an IRM case, simplifying the investigation of risky user behavior and assessing potential impact after an incident.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=486827](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=486827)

### Nov 2025 - New Message Trace on Graph API

Microsoft plans to launch the new Message Trace on Microsoft Graph API in Public Preview by a tentative timeline of November 2025.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1092458](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1092458)

### Enhancements

### Nov 2025 – Require Explicit Consent for Recording and Transcription in Teams 1:1 Calls

  
Microsoft Teams is expanding the consent requirement for recording and transcription to include 1:1 calls. Admins can enforce this via a new Teams Calling policy setting. When a call is recorded or transcribed, the other participant’s camera, microphone, and screen sharing are automatically disabled until they provide explicit consent.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=503295](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=503295)

### Existing Functionality Changes

### Nov 2025 - New Calendar Experience in Microsoft Teams

Microsoft Teams is introducing a new calendar experience to enhance productivity across Microsoft 365. It combines familiar features with Microsoft Copilot and Microsoft Places for seamless collaboration. As part of this change, the legacy calendar will be retired, and the toggle to switch between old and new calendars will be removed.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1129730](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1129730)

### Action required

### Nov 2025 – Retirement of Microsoft Places Team Guidance Feature

  
The Team Guidance feature in Microsoft Places, which helped managers manage in-office days and team priorities, is being retired. Microsoft is retiring it to simplify collaboration and encourage teams to use Microsoft 365 Groups for scheduling and coordination.

**Solution:** Begin transitioning to Microsoft 365 Groups for team scheduling.

**_Ref_**: [https://support.microsoft.com/en-us/office/retirement-of-places-team-guidance-ba959478-e979-4f76-b235-1afacf1b6185](https://support.microsoft.com/en-us/office/retirement-of-places-team-guidance-ba959478-e979-4f76-b235-1afacf1b6185)

### December (Attention Needed: 11)

### Dec 2025 – Automatically Set Work Location by Connecting to a Wi-Fi Network

Microsoft Teams will introduce a feature that automatically sets users’ work locations when they connect to the organization’s Wi-Fi or certain peripherals. This helps deliver location-based experiences without manual input.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=488800](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=488800)

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

### December 2025 - Two New Email Indicators in Insider Risk Management

Admins can use the two new email indicators in Insider Risk Management as triggers.  
They are,

1.  **Emails with attachments to free public domains** – Flags users when business-sensitive data is sent from a work account to a free public domain email.
2.  **Emails with attachments to self** – Flags users when business-sensitive data is sent from a work account to their personal email or themselves.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=496149](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=496149)

### Dec 2025 – Inline Detection of Sensitive Data Shared Over Network via Microsoft Purview

Microsoft Purview now integrates with your existing Secure Access Service Edge (SASE) solution, extending Data Loss Prevention (DLP) capabilities to the network layer. This enables admins to intercept, inspect, and enforce DLP policies on network traffic carrying sensitive data.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=488807](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=488807)

### Dec 2, 2025- Update Firewall Rules for Intune via Azure Front Door

As part of Microsoft’s Secure Future Initiative (SFI), starting on or after December 2, 2025, Microsoft Intune network endpoints will use Azure Front Door IP addresses. Since Basic Mobility and Security for Microsoft 365 relies on Intune, customers using firewall allowlists based on IP addresses or service tags must update them.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1150664](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1150664)

### Mid-Dec 2025 - Data Lifecycle Management: Retention based on “last accessed” for OneDrive and SharePoint files

Microsoft will introduce a "When items were last accessed" option in Purview retention policies. This will allow admins to configure retention policies based on file access history in OneDrive and SharePoint, enabling the removal of outdated data and enhancing Microsoft 365 Copilot responses. This update will be rolled out to preview by mid-Dec 2025.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442)

### End of 2025 – Retirement of Mailbox Audit Log Cmdlets in Exchange Online

By late December 2025, Microsoft will retire the Search-MailboxAuditLog and New-MailboxAuditLogSearch cmdlets in Exchange Online.  
  
**Solution**: Use Search-UnifiedAuditLog instead.  
**_Ref_**: [https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310](https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310)

## Q1 2026 (Attention Needed: 13)

### Early-Jan 2026 - Policy Alerts Improvements in Microsoft Purview Communication Compliance

Communication Compliance is enhancing policy alert customization. Admins will have the ability to set the alert frequency for each policy and adjust the email alert frequency and recipients directly within the policy creation wizard, via the new alerts page. This update will be generally available from mid-May 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920304](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920304)

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

## Q2 2026 (Attention Needed: 7)

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

### Sep 17, 2026 - Retirement of Legacy Education LTI Tools

Microsoft is retiring legacy Education LTI tools (Teams Assignments, OneDrive, OneNote Class Notebook, Reflect) on September 17, 2026, replacing them with a unified Microsoft 365 LTI tool. Users and admins will need to transition to the Microsoft 365 LTI unified tool.

Ref:

[https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1160188](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1160188)

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