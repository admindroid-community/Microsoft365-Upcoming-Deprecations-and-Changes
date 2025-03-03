# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.  
  
Discover the **key changes, deprecations**, and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

  
Here is a list of changes categorized by month and year.  

*   Mar 2025 (Retirements: 7, New Features: 17; Enhancements: 9, Existing Functionality Changes: 2, Action Needed: 3)
*   Apr 2025 (Retirements: 2, New Features: 2; Enhancements: 3, Existing Functionality Changes: 1, Action Needed: 1)
*   May 2025 (Attention Needed: 4)
*   June 2025 (Attention Needed: 7)
*   Q3 2025 (Attention Needed: 6)
*   Q4 2025 (Attention Needed: 6)
*   2026 (Attention needed: 12)

  

## Mar 2025

## Retirement: 7 | New Features: 17 | Enhancements: 9 | Existing Functionality Changes: 2 | Action Needed: 3

### Retirements

### March 1, 2025 - Retirement of .FBX and .SKP 3D file Format Support in the Microsoft 365 App

Microsoft 365 will retire support for Filmbox (.FBX) and SketchUp (.SKP) file formats on March 1, 2025. Users will no longer be able to insert these file types after the change, but any previously inserted .FBX or .SKP models will remain in documents.

**_Ref:_** [https://admin.microsoft.com/#/MessageCenter/:/messages/MC950892](https://admin.microsoft.com/#/MessageCenter/:/messages/MC950892)

### March 1, 2025 - Retirement of Search-MailboxAuditLog and New-MailboxAuditLogSearch Cmdlets

Microsoft will retire the Search-MailboxAuditLog and New-MailboxAuditLogSearch cmdlets in Microsoft Exchange Online starting March 1, 2025.

**Solution**: Use "Search-UnifiedAuditLog" as an alternative.

**_Ref_**: [https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310](https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310)

### March 10, 2025 - Retirement of Spaces Feature in Microsoft SharePoint

Microsoft is retiring the Spaces feature in SharePoint Online due to low usage, prioritizing Microsoft Mesh for a more advanced immersive 3D experience.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1002417](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1002417)

### Mid-Mar 2025 - Creating Personal Pages from SharePoint "start" (Preview) will be Retired

Microsoft introduced SharePoint Start (Preview) as a user-friendly way to create sites and pages. However, due to content policy concerns related to personal pages, Microsoft will retire the ability to create personal pages from SharePoint Start (Preview)starting mid-March 2025. Other features in SharePoint Start (Preview) will remain available.

**Solution:** Create a new page from a page template in SharePoint start (Preview) that is connected to a SharePoint site.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1018344](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1018344)

### Mar 24, 2025 - Retirement of Alerts Policy Cmdlets in Microsoft Purview Audit

Starting March 24, 2025, Microsoft will retire the event alerts capability in the Purview Audit solution. As a result, admins will no longer be able to create event alert policies through Purview Audit. Additionally, related cmdlets such as _Get-AuditConfigurationRule, New-AuditConfigurationRule, Remove-AuditConfigurationRule, and Set-AuditConfigurationRule_ will also be retired.

**Solution:** If you have any alert policies created using Purview Audit that you wish to retain, please re-create those alert policies through Purview DLP.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1006620](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1006620)

### Mar 24, 2025 - Retirement of Sway Feature from Create Tab of Microsoft 365 Copilot App

Due to low usage, Microsoft will remove the Sway feature from the ‘Create’ tab in the Microsoft 365 Copilot app.

**Solution:** You can access Sway from the _Apps_ section of the Microsoft 365 Copilot app.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1013463](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1013463)

### March 31, 2025 - Retirement of Old Search Usage Reports in Microsoft 365 Admin Center

To enhance consistency and user experience, the legacy Search usage reports in Microsoft 365 will be retired. However, this change will not impact the existing default reports in the Search and Intelligence portal.

**Solution:** Download the old Search usage reports by March 31, 2025, if needed. Afterward, use the new Search usage report under the Insights tab in the Microsoft 365 Admin Center.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC976821](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC976821)

### New Features

### March 2025 - Create Dynamic Rule-based Policies for Microsoft 365 Backup

Admins can now create dynamic rule-based backup policies for SharePoint, OneDrive, and Exchange using distribution lists and security group memberships. This feature will automatically update policies as users are added or removed from these groups.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?id=464989](https://www.microsoft.com/en-us/microsoft-365/roadmap?id=464989)

### Mar 2025 – New DLP action to Trigger Custom Power Automate Workflows

Microsoft will introduce a new DLP action that triggers custom Power Automate workflows when a DLP policy is violated.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=380721](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=380721)

### March 2025 - Permanently Delete Protection Units from Microsoft 365 Backup

OneDrive accounts, SharePoint sites, and Exchange Online mailboxes protected in the Microsoft 365 Backup are considered protection units. Now, Microsoft is introducing the ability to permanently delete these protection units from backup after a set grace period, ensuring better data management and compliance.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=464994](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=464994)

### March 2025 - Insider Risk Management User Analytics in Microsoft Purview Compliance Portal

Microsoft Purview Insider Risk Management is introducing user analytics in Preview to enhance insights into risky behaviors. These insights will appear in DLP alerts, Communication Compliance, Defender XDR, and Advanced Hunting. It is enabled by default for users using Insider Risk Management analytics.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=475058](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=475058)

### Early-Mar 2025 – Move Email Between Mailbox and PST File in New Outlook for Windows

The new Microsoft Outlook for Windows will soon allow users to drag and drop emails between mailboxes and PST files. The update will be generally available from early March 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC966640](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC966640)

### Early-Mar 2025 - New Microsoft Outlook for Windows Usage report for Microsoft 365 Apps

  
Microsoft will introduce a new “Outlook for Windows migration progress” report to help admins track the adoption and usage of the new Outlook for Windows. This report will provide detailed metrics on active users who have transitioned from classic Outlook to the new version.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1013460](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1013460)

### Early-March 2025 - Data Loss Prevention (DLP) Alerts as Indicators in IRM Policies

Microsoft Purview Insider Risk Management will enable admins to use Data Loss Prevention alerts as indicators within IRM policies. This feature will help admins track DLP alerts tied to specific policies in IRM, making it easier to detect high-risk alerts without the need to switch to DLP.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=475057](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=475057)

### Early-March 2025 - Disable the Ability to Send Messages in Meeting Chat

Microsoft Teams will offer more control over meeting chat settings. Admins can enable two new options:

*   **In-meeting only for everyone**: This setting allows participants to send messages only while the meeting is active.
*   **In-meeting only except anonymous users**: This option allows only authenticated users to send messages while the meeting is active, preventing anonymous users from sending messages before or after the meeting.

**_Note:_** Applicable for Teams for Windows desktops and Mac desktops, Teams on the web, and Teams for iOS/Android.

**_Ref:_** [https://admin.microsoft.com/#/MessageCenter/:/messages/MC920298](https://admin.microsoft.com/#/MessageCenter/:/messages/MC920298)

### Mar 1, 2025 - New Usage Reports through Microsoft PowerShell for the SharePoint Agents Trial

  
Starting March 1, 2025, Microsoft will introduce a new SharePoint PowerShell cmdlet, _Get-SPOCopilotPromoUsage_. Admins can use this cmdlet to review tenant-level usage data for the SharePoint agent's trial.

**Note:** This requires SharePoint PowerShell version 16.0.25813.12000.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1015905](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1015905)

### March 2025 - New Tenant-level Outbound Email Limits in Exchange Online

Starting March 3, 2025, Microsoft will enforce Tenant External Recipient Rate Limits (TERRL), restricting outbound emails based on the number of purchased or trial licenses. These limits operate on a 24-hour rolling window, continuously tracking sent emails. Also, the rollout will be staggered based on tenant size, progressing from March 3 to March 31, 2025.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/introducing-exchange-online-tenant-outbound-email-limits/4372797](https://techcommunity.microsoft.com/blog/exchange/introducing-exchange-online-tenant-outbound-email-limits/4372797)

### Mid-Mar 2025 - Integration of Adaptive Protection with Data Lifecycle Management

Microsoft will roll out the integration of Adaptive Protection with Data Lifecycle Management in general availability by mid-March 2025. This integration will allow admins to preserve items deleted by high-risk users, enabling easy restoration when needed.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC79111](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110)

### Late- Mar 2025 – New Secure Workflow to Bypass Legal Holds and Retention Policies in Microsoft Purview

  
Admins will have the ability to permanently delete sensitive Exchange mailbox content, bypassing retention policies and eDiscovery holds. This will be possible through the “Priority Cleanup Administrator” role, which grants authorized users' permission to initiate Priority Cleanup for Exchange, allowing exceptions to standard retention and legal hold policies.

  
Since this process is irreversible and overrides existing policies, Microsoft has built-in approvals and special auditing for security.  
**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC971035](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC971035)

### Late-Mar 2025 - New License Request and Self-Service Purchase Feature for Microsoft 365 Copilot

  
Microsoft 365 Copilot will support end-user license requests and self-service purchases. Users can request a Copilot license from admins, while global and license admins can manage these requests via a new interface in the Microsoft 365 Admin Center. For self-service purchases, admins retain control and can track user-purchased licenses directly in the admin center.

**Note:** This feature will be available for users with Microsoft 365 E1, Microsoft 365 E3, Microsoft 365 E5, Microsoft Office 365 Plan E1, Microsoft Office 365 Plan E3, Enterprise Mobility + Security E3, Enterprise Mobility + Security E5, Microsoft 365 Apps for Business and standalone products.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1017114](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1017114)

### Late-Mar 2025 - Client Health Dashboards in Teams Admin Center

Microsoft is introducing a new "Teams Client Health" page in the Teams admin center to help admins monitor the health of the Teams desktop client for Windows and Mac.

This page will provide insights into version adoption, version health, and key client metrics such as crashes and launch/update failures.

**Note:** Only users with the following roles can access this page: Teams Administrator, Teams Communication Administrator, and Teams Communications Support Engineer.

**_Ref:_** [https://learn.microsoft.com/en-us/microsoftteams/teams-client-health](https://learn.microsoft.com/en-us/microsoftteams/teams-client-health)

### Late-March 2025 - New Compromised User Context in Insider Risk Management

Microsoft Entra provides two types of compromised user detections: Sign-in risk and User risk detections. These detections will now be integrated into the Insider Risk Management alert investigation experience.

With this update, admins can view compromised user alerts from Microsoft Entra while investigating users, enabling them to take appropriate action and faster remediation.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1006621](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1006621)

### Late-Mar 2025 – Email OTP Verification for External Participants to Join Teams Meetings

Microsoft Teams will introduce email OTP (one-time passcode) verification for external participants to join meetings in general availability. Meeting organizers can require external attendees to verify their email before joining. Admins will have a new meeting policy in the Teams admin center to manage this setting.

**Note:** Applicable to Teams on Windows, Mac, web, iOS, and Android.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoftteamsblog/enhance-meeting-security-with-teams-premium%E2%80%99s-email-verification-for-external-me/4292196](https://techcommunity.microsoft.com/blog/microsoftteamsblog/enhance-meeting-security-with-teams-premium%E2%80%99s-email-verification-for-external-me/4292196)

### Late-Mar 2025 - File Interactive Previews for GCC Environment

Microsoft Teams will roll out interactive file previews for chats and channels in the GCC environment. Initially, users will be able to preview PDFs, with plans to expand to other formats. This feature allows users to view files directly within Teams, reducing context switches and improving workflow efficiency.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC934727](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC934727)

### Enhancements

### Early-Mar 2025 – Add Approvals to Any Document Library in SharePoint

This feature allows admins to enable or disable approvals via the “Configure Approvals” option in the “Automate” dropdown in the SharePoint Online document library. It will be enabled by default and will be generally available starting early March 2025.  

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC912181](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC912181)

### Mar 2025 - External Auth Methods Support for System Preferred MFA

Starting March 2025, Microsoft will support External Authentication Methods (EAM) as a sign-in option when System Preferred Authentication is enabled. EAM will be prioritized third in the authentication order, following Temporary Access Pass (TAP) and Passkey (FIDO2).

**_Ref:_** [https://entra.microsoft.com/#view/Microsoft\_AAD\_IAM/ChangeManagementHubList.ReactView?Microsoft\_AAD\_IAM\_legacyAADRedirect=true](https://entra.microsoft.com/#view/Microsoft_AAD_IAM/ChangeManagementHubList.ReactView?Microsoft_AAD_IAM_legacyAADRedirect=true)

### Mar 2025 - Optical Character Recognition Support for SharePoint Online and OneDrive for Business

Microsoft is bringing Optical Character Recognition (OCR) support to SharePoint Online and OneDrive for Business. This update will allow automated detection of sensitive content within images and enable the application of DLP policies to safeguard data and prevent exfiltration.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=160010](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=160010)

### Mid-Mar 2025-Create Allow Entries Directly in the Tenant Allow/Block List of Microsoft Defender

Starting mid-March 2025, Microsoft Defender will allow admins to create allow entries for domains, addresses, and URLs directly from the Tenant Allow/Block Lists page. This can also be done using the _New-TenantAllowBlockListItems_ cmdlet, simplifying the management of allowed entities.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1009923](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1009923)

### Mid-Mar 2025 - Data Lifecycle Management: Retention Based on “last accessed” for OneDrive and SharePoint Files

Starting mid-March 2025, Microsoft will introduce a "When items were last accessed" option in Purview retention policies. This will allow admins to configure retention policies based on file access history in OneDrive and SharePoint, enabling the removal of outdated data.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442)

### Late-Mar 2025 - Updates to Sensitivity Label Changes Monitoring in IRM

Currently, Insider Risk Management captures sensitivity label changes only in the SharePoint web app. However, starting late March 2025, IRM will also track sensitivity label changes across OneDrive, Azure Information Protection, and endpoints, including SharePoint. Additionally, Microsoft will enhance and rename existing Microsoft 365 indicators for better clarity.

*   _Downgrading sensitivity labels applied to SharePoint files ->Downgrading sensitivity labels applied to files_
*   _Removing sensitivity labels from SharePoint files_ \->_Removing sensitivity labels from files._

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC934733](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC934733)

### Late-March 2025 - The New Streamlined Chat and Channels Experience in Microsoft Teams

Microsoft Teams has started merging the Chat and Teams views into a single 'Chat' view, uniting chats, teams, and channels for easier navigation. This new view offers filters for Unread, Chats, Channels, and Meetings, an @mentions list for tracking mentions, and a Favorites section for pinned items. This update will be generally available starting late March 2025.

**Note:** This experience applies to Teams on Windows desktops, Mac desktops, the web, and iOS and Android devices.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920179](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920179)

### Late-Mar 2025 - Updates to Microsoft Lists forms in SharePoint Online

Starting late March 2025, Microsoft Lists forms will be enhanced with new features, including notifications, form scheduling, conditional branching, quick form creation, and support for additional field types. These updates will provide a more streamlined and efficient way to collect information within Microsoft Lists.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=124865](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=124865)

### Late-Mar 2025 - M365 Copilot Chat with Link Safety

Starting late March 2025, Microsoft will enhance M365 Copilot Chat with new security features:

*   **SafeLinks Integration**: Copilot Chat will use SafeLinks in Defender for Office 365 to scan and protect URLs in its responses at the time of clicking.
*   **Built-in URL Reputation Check**: For users without SafeLinks, Copilot Chat will still perform time-of-click URL checks to detect potential threats.
*   **Hyperlink Redaction Update**: Copilot Chat will no longer redact URLs if they exist in the source data used to generate responses.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1013453](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1013453)

### Existing Functionality Changes

### Mid-Mar 2025 - Increasing Policy Template Limits in Insider Risk Management

Currently, Insider Risk Management allows up to 20 policies per template. However, Microsoft is increasing the limit to 100 active policies in total, removing template-specific restrictions. This means you can now create up to 100 policies across all templates instead of being limited per template.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=477364](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=477364)

### Mid-Mar 2025 - Data Lifecycle Management: Separate Copilot Retention policies from Teams chats

Currently, Teams chat and Copilot interactions share the same Purview Data Lifecycle Management policy. After the update, admins can create separate retention policies for Copilot interactions, managing them independently from Teams chat.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC926899](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC926899)

### Action Needed

### Mar 30, 2025 – End of Support for Azure AD and MSOnline PowerShell Modules

Azure AD and MSOnline PowerShell modules will reach end of support by March 2025.

**Note:** Identify and migrate your scripts to use Microsoft Graph.  
  
**_Ref_**: [https://techcommunity.microsoft.com/t5/microsoft-entra-blog/important-update-deprecation-of-azure-ad-powershell-and-msonline/ba-p/4094536](https://techcommunity.microsoft.com/t5/microsoft-entra-blog/important-update-deprecation-of-azure-ad-powershell-and-msonline/ba-p/4094536)

### Mar 31, 2025 - Retirement of App-only Authentication for OneNote Microsoft Graph APIs

Microsoft is deprecating app-only authentication for Microsoft Graph OneNote APIs. Starting March 31, 2025, requests using application permissions (app-only tokens) will fail with 401 unauthorized errors.

**Solution:** Transition to delegated authentication tokens to prevent access issues.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1011142](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1011142)

### March 31, 2025 - Power Apps to Use New Endpoint

Starting March 31, 2025, Power Apps will use the new endpoint: \*.powerplatformusercontent.com.

**Action Needed:** Admins must update firewalls to allow this endpoint and its subdomains.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1019302](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1019302)

## April 2025 (Attention Needed: 9)

### Retirements

### Early-April 2025 – MSOnline PowerShell Retirement

Microsoft will retire the MSOnline PowerShell module between early April 2025 and late May 2025.  

**Solution:** Migrate to Microsoft Graph PowerShell SDK or Microsoft Entra PowerShell module.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991)

### Apr 02, 2025 – Retirement of Domain Isolated Web Part in SharePoint Framework

  
As part of the SharePoint Framework domain isolated web parts retirement, this feature will be turned off for newly created tenants starting from Apr 02, 2025.

**Note:** From Apr 02, 2026, existing tenants will no longer be able to use this feature.

**_Ref_**: [https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/](https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/)

### New Features

### Early- April 2025 - Facilitator Agent in Microsoft Teams

Microsoft Teams will introduce a Facilitator Agent to enhance collaboration by automating notetaking and summarizing key discussions during meetings and chats. This feature also enables real-time co-authoring, allowing participants to edit and collaborate on notes seamlessly.

**Note:** It applies to Teams for Windows desktop, Teams for Mac desktop, Teams for the web, and Teams for iOS/Android. Also, a Microsoft Copilot license is required to use this feature.  

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1017117](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1017117)

### Early - April 2025 - Data Loss Prevention: Network Share Coverage and Exclusion Support on Mac Endpoints

Starting early April 2025, Microsoft will enable admins to configure DLP policies for sensitive files on network shares and mapped drives on Mac endpoints. This will help prevent actions like copying to USB drives or clipboard. Admins will also have the flexibility to exclude specific network shares from these policies based on their requirements.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=410397](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=410397)

### Late - April- 2025 – New Cmdlet for Content Explorer

A new cmdlet, _Export-ContentExplorerData_, will be available by late-April 2025. This cmdlet allows admins to export all scanned content data from Content Explorer, providing a streamlined way to manage and analyze content data.  

**Ref:** [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC698421](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC698421)

### Enhancements

### April 2025 - Mail Merge (Advanced) on Outlook on the Web and New Outlook for Windows  

Enhanced mail merge features are coming to Outlook on the Web and the new Outlook for Windows in April 2025. Users will be able to insert dynamic fields into email templates for personalized emails and advanced customizations.  

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047)

### April 2025 - Enriched Details of Auto-forwarded Emails in Exchange DLP

Microsoft will roll out an upgrade to Data Loss Prevention that provides more precise details for auto-forwarded emails. This enhancement ensures that forwarding users, recipients, and email evidence are accurately reflected in alerts, audit logs, and activity explorer.  

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=481343](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=481343)

### Mid-April 2025 – Policy Alerts Improvements in Microsoft Purview Communication Compliance

Communication Compliance is enhancing policy alert customization. Admins will have the ability to set the alert frequency for each policy and adjust the email alert frequency and recipients directly within the policy creation wizard, via the new alerts page. This update will be in public preview from mid-April 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920304](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920304)

### Existing Functionality Changes

### April 10, 2025 - Removal of Everyone Except External Users Permission in OneDrive

The Everyone Except External Users (EEEU) permission in SharePoint and OneDrive grants access to all internal users while excluding external users. However, due to concerns over unintentional data oversharing, Microsoft has decided to remove this permission from the root web and default document library in OneDrive.  

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1013464](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1013464)

### Action Required

### Apr 2, 2025 - Upgrade to the latest version of Microsoft Entra Connect by April 2, 2025

In early October 2024, a new version (2.4.XX.0) of Microsoft Entra Connect Sync was released, featuring a backend service update to improve security. Customers are required to upgrade to this version by early April 2025 to prevent any potential service interruptions.

**_Ref:_** [https://entra.microsoft.com/#view/Microsoft\_AAD\_IAM/ChangeManagementHubList.ReactView?Microsoft\_AAD\_IAM\_legacyAADRedirect=true](https://entra.microsoft.com/#view/Microsoft_AAD_IAM/ChangeManagementHubList.ReactView?Microsoft_AAD_IAM_legacyAADRedirect=true)

## May 2025 (Attention Needed: 4)

### May 2025 - New Insider Risk Management Reporting Capabilities

Insider Risk Management will introduce a centralized hub for all reports, including analytics and user activity reports. New reports will also be available, providing summaries of alert trends and case creation patterns.  

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=470027](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=470027)

### May 2025: OneDrive Sync Admin Reports for GCC

Microsoft will roll out OneDrive Sync Admin Reports in the Microsoft 365 admin center for GCC users by May 2025. These reports will help admins monitor sync client usage and errors across the organization.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=393333](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=393333)

### Mid -May 2025 - Third-party Add-in User Report can be Sent to Microsoft for Analysis

Microsoft will allow admins using third-party add-ins for report message solutions to configure Defender for Office 365 to automatically send user-reported messages to Microsoft for analysis.

Sending these messages to Microsoft for analysis not only provides valuable insights for security analysts but also improves the accuracy of Defender for Office 365 filters.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC962528](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC962528)

### Mid-May 2025 – New Filters in Microsoft Purview Audit Search

To help you retrieve relevant logs in the Microsoft Purview audit search, Microsoft will include four additional filters in general availability. They are,  

Id – Unique identifier of an audit record.

UserType – The type of user that performed the operation.

UserKey-Azure Active Directory Object ID in GUID format.

ClientIP – The IP address of the device that was used when the activity was logged.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC789312](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC789312)

## June 2025 (Attention Needed: 7)

### June 2025 - Message Recall Feature for Outlook for Mac

The Cloud-based Exchange Online Message Recall feature will soon be available for Outlook for Mac users, with a preview rollout scheduled for June 2025.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=189804](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=189804)

### June 2025 - Bulk Data Export for OneDrive Sync Admin Reports

Admins will soon be able to export OneDrive sync data in bulk via Microsoft Graph Data Connect. This includes device status, usernames, sync app versions, known folders, last sync dates, and sync errors.  

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC844917](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC844917)

### June 2025: Block Specific Folders from OneDrive Sync

Starting June 2025, admins can block not just files or extensions but also specific folders from syncing with OneDrive through Group Policy.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=178292](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=178292)

### June 2025 - Date Lifecycle Management and Power Automate Integration in U.S Government Clouds

U.S. government cloud users can automate actions on items at the end of their retention period using Power Automate by June 2025.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=117523](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=117523)

### Late - June 2025 - Search-MailboxAuditLog and New-MailboxAuditLogSearch Cmdlets Will Become Static

Microsoft plans to deprecate the Search-MailboxAuditLog and New-MailboxAuditLogSearch cmdlets. However, admins can continue to access the old logs and download data using these cmdlets until late June 2025. After that, the cmdlets will become read-only, and no further changes or downloads will be possible.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310](https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310)

### Late-June 2025 – IRM Alerts in Microsoft Defender XDR

Microsoft Purview’s Insider Risk Management (IRM) data will integrate with Microsoft Defender XDR, enabling comprehensive investigation and correlation. IRM data will be accessible through the unified alert and incident queue, advanced hunting with KQL queries, Graph API, and Microsoft Sentinel. This feature will roll out to general availability by mid-June 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC961761](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC961761)

### Late - June 2025 – Decoupling of Policy Tips and Email Notifications for SharePoint and OneDrive

Currently, enabling email notifications for a DLP policy also requires enabling the policy tips, and vice versa. However, Microsoft will soon allow admins to configure email notifications and policy tips independently for SharePoint and OneDrive DLP policies. This update will be rolled out to Public preview by late June 2025.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=394279](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=394279)

## Q3 2025 (Attention Needed: 6)

### After July 1, 2025 – Azure AD PowerShell Retirement

The Azure AD PowerShell module will be retired after July 1, 2025.  

**Solution**: Migrate to Microsoft Graph PowerShell SDK or Microsoft Entra PowerShell module.  

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991)

### July 1, 2025 – Azure AD Graph API Will Be Fully Retired

If you've extended the use of Azure AD Graph API, it will no longer work after June 30, 2025. Azure AD Graph will be fully retired, and all Azure AD Graph API requests will stop functioning from July 1, 2025.

**Solution**: Review the application that uses the Azure AD Graph API and migrate them to Microsoft Graph.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-azure-ad-graph-api-retirement/4090533](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-azure-ad-graph-api-retirement/4090533)

### July 1, 2025- Classic Teams Desktop App End of Availability

Starting July 1, 2025, classic Teams desktop app will reach end of availability for all users irrespective of OS.

**Note**: From Oct 23, 2024, classic Teams desktop app on Windows 7,8,8.1 and Mac OS Sierra (10.12) will reach end of availability.

**Solution:** Users need to switch to new Teams, or they can use Teams web app (on supported browser) as an alternative.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783985](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783985)

### August 1, 2025 - Retirement of Classic e-Discovery in Microsoft Purview

Starting August 1, 2025, Microsoft will retire Classic eDiscovery, including Content Search, eDiscovery (Standard), and eDiscovery (Premium), from the Microsoft 365 Purview portal.

**Solution:** Transition to the new unified eDiscovery for faster and improved search and investigation capabilities.  

**_Ref:_** [https://learn.microsoft.com/en-us/purview/ediscovery-legacy-retirement](https://learn.microsoft.com/en-us/purview/ediscovery-legacy-retirement)

### Sep 2025- Basic Auth for Client Submission (SMTP AUTH) Retirement in Exchange Online

Exchange Online will permanently remove support for Basic authentication with Client Submission (SMTP AUTH) in September 2025.

**Solution:** You can start to use OAuth with Client Submission (SMTP AUTH).

**_Ref_**: [https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-retire-basic-auth-for-client-submission-smtp/ba-p/4114750](https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-retire-basic-auth-for-client-submission-smtp/ba-p/4114750)

### Sep 30, 2025 – Retirement of Managing Authentication Methods in Legacy MFA &SSPR Policy

Starting Oct 2025, Microsoft no longer allow authentication methods to be managed in the legacy MFA and SSPR policies.

**Solution:** Organizations should use the converged authentication methods policy where methods can be managed centrally for all authentication scenarios including passwordless, MFA and SSPR.

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448)

## Q4 2025 (Attention Needed: 6)

### Oct 2025- External Recipient Rate Limit in Exchange Online

Exchange Online will begin enforcing an external recipient rate (ERR) limit of 2000 recipients in 24 hours. This restriction will be applicable to the cloud-hosted mailboxes of all newly created tenants.

**Note:** Exchange Online enforces a Recipient Rate limit of 10000 recipients for cloud-hosted mailboxes. The 2000 ERR limit will become a sublimit within this 10000 Recipient Rate limit.

**_Ref:_** [https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733](https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733)

### Oct 14, 2025 - End of Office 2016 and Office 2019 Support

Support for Office 2016 and Office 2019 will end on October 15, 2026. After this date, these versions will no longer receive updates or support.

**Solution:** Upgrade to Microsoft 365 E3 or Office LTSC 2024 for continued updates and support

**_Ref:_** [https://techcommunity.microsoft.com/blog/officeeos/get-ready-now-one-year-until-office-20162019-end-of-support/4267801](https://techcommunity.microsoft.com/blog/officeeos/get-ready-now-one-year-until-office-20162019-end-of-support/4267801)

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

## 2026 (Attention Needed: 12)

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