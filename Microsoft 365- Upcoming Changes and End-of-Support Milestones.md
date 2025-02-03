# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.  
  
Discover the **key changes, deprecations**, and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

  
Here is a list of changes categorized by month and year.  

*   Feb 2025 (Retirements: 6, New Features: 9, Enhancements: 5, Existing Functionality Changes: 7, Action Needed: 2, Readiness Check: 1)
*   Mar 2025 (Retirements: 3, New Features: 7, Enhancements: 3, Existing Functionality Changes: 1, Action Needed: 1)
*   Apr 2025 (Attention Needed: 6)
*   May 2025 (Attention Needed: 4)
*   June 2025 (Attention Needed: 5)
*   Q3 2025 (Attention Needed: 5)
*   Q4 2025 (Attention Needed: 5)
*   2026 (Attention needed: 11)

  

## Feb 2025

Retirements: 6 | New Features: 9 | Enhancements: 5 | Existing Functionality Changes: 7 | Action Needed: 2 |Readiness Check: 1

### Retirements

### Feb 1, 2025 - Apps Can’t Make Requests to Azure AD Graph APIs

Microsoft began deprecating the Azure AD Graph API service in September 2024. Entering the next phase of retirement, starting February 1, 2025, both new and existing applications will be blocked from calling Azure AD Graph APIs unless explicitly configured for an extension.

**Solution**: Review the application that uses the Azure AD Graph API and migrate them to Microsoft Graph. If not, set an extension to allow the application access to Azure AD Graph through June 30, 2025.

**_Ref:_** [https://techcommunity.microsoft.com/blog/identity/take-action-by-february-1-azure-ad-graph-is-retiring/4365743](https://techcommunity.microsoft.com/blog/identity/take-action-by-february-1-azure-ad-graph-is-retiring/4365743)

### Feb 2025 – Legacy Exchange Online Tokens to Be Turned Off

Microsoft will deprecate and disable Legacy Exchange Online tokens across all Microsoft 365 tenants starting February 2025.

**Solution**: Migrate Outlook add-ins to use Entra ID tokens with Nested App Authentication (NAA) and Microsoft Graph instead of legacy tokens.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/security-related-updates-in-exchange-online/4303525](https://techcommunity.microsoft.com/blog/exchange/security-related-updates-in-exchange-online/4303525)

### Mid-Feb 2025 - Exposure Management Recommendations Retirement from Microsoft Defender  

Microsoft is retiring some SaaS security posture recommendations from Exposure Management in Microsoft Defender to improve the security posture accuracy.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC971037](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC971037)

### Mid-Feb 2025 – Deprecation of Get-CsDialPlan Cmdlet from Teams PowerShell Module

Microsoft plans to deprecate the _Get-CsDialPlan_ cmdlet from the Teams PowerShell module. Also, Microsoft is deprecating the DialPlan attribute from the _Get-CsOnlineUser_ and LocationProfile attribute from the _Get-CsUserPolicyAssignment_ cmdlet.

**Solution:** Use the _Get-CsEffectiveTenantDialPlan_ cmdlet, which will return the returned effective Tenant Dial Plan contains the EffectiveTenantDialPlanName and the Normalization rules that are effective for the user while using the EnterpriseVoice features.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC950879](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC950879)

### Feb 22, 2025- Viva Topics Retirement

Viva Topics will be discontinued on February 22, 2025, and Microsoft will no longer pursue new feature enhancements for the platform.

Existing Topic pages will transition to standard SharePoint pages. Users can edit and publish updates as other SharePoint pages. AI-generated Topic pages will no longer be accessible.

**_Ref:_** [https://learn.microsoft.com/en-us/microsoft-365/topics/changes-coming-to-topics](https://learn.microsoft.com/en-us/microsoft-365/topics/changes-coming-to-topics)

### Late- Feb 2025: Retirement of Monitor Action in the Safe Attachments

Starting February 2025, Microsoft will remove the "Monitor" action in the Safe Attachments policy. Any existing policies set to "Monitor" will be automatically changed to "Block". The recipients, status, or priority configured in the policy will remain unchanged.

Post-retirement, the only available actions in the Safe Attachments policy will be Off, Block, and Dynamic Delivery. Note that you will also lose the ability to "Redirect messages with detected attachments," as this action applies only to the Monitor.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC918563](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC918563)

### New Features

### Early-Feb 2025 – New People Administrator Role in Microsoft Entra

Microsoft Entra introduces the People Administrator role to enhance and simplify administrative tasks in Microsoft 365. Those assigned the People Administrator role will have the ability to:

*   Update profile photos for all users, including admins
*   Modify people settings for pronouns and name pronunciation
*   Configure profile card settings
*   Adjust photo update settings for all users.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC992218](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC992218)

### Early-Feb 2025 - App Management Unification Impact report in MS Teams Admin Center

Microsoft is introducing Unified App Management for Teams apps. To bring awareness to the expected changes, the new App Management Unification Impact Report will be rolled out. It provides a comprehensive preview of changes to app and tenant settings. Admins can use this report to review and update settings in the Teams Admin Center or Microsoft 365 Admin Center before the changes take effect.

**Note**: This report will be available only for tenants who migrated to Microsoft App-Centric Management.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC982569](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC982569)

### Feb 2025 - New Scenario-based Policy Templates in Insider Risk Management

In addition to the current quick policy templates for data leak and data theft, Microsoft will introduce two new templates in Insider Risk Management for crown jewel protection and email exfiltration. These scenario-based templates make it easier for admins to deploy targeted protection policies.  

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=409966](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=409966)

### Feb 2025 - Insider Risk Management- Risky AI Usage

New detections in Insider Risk Management will be generally available, enabling admins to identify risky AI activity, such as sensitive prompts, risky intents, and AI-generated sensitive content. This applies to M365 Copilot, Copilot Studio, and ChatGPT Enterprise, contributing to Adaptive Protection risk levels.

  
**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC947048](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC947048)

### Early - Feb 2025 - New Secure Workflow to Bypass Legal Holds and Retention Policies in Microsoft Purview

Admins will have the ability to permanently delete sensitive Exchange mailbox content, bypassing retention policies and eDiscovery holds. This will be possible through the **"Priority Cleanup Administrator"** role, which grants authorized users permission to initiate **Priority Cleanup for Exchange**, allowing exceptions to standard retention and legal hold policies.

Since this process is irreversible and overrides existing policies, Microsoft has built-in approvals and special auditing for security.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC971035](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC971035)

### Mid-Feb 2025 - Microsoft Teams: SMS for Calling Plans

Microsoft Teams will support SMS messaging for U.S. and Canada users with Calling Plans, allowing seamless communication with external contacts. Admins must enable SMS functionality for users with calling plans. While the feature is available by default, enabling 10-digit long code (10DLC) numbers requires administrative action.

**Note**: This feature applies to Teams for Windows desktop, Teams for Mac desktop, and Teams for iOS/Android.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=470999](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=470999)

### Late-Feb 2025 – Org Explorer Feature for Enterprise Users

The Org Explorer feature will be available to all enterprise users, offering insights into internal structures and connections.

**Note**: Get early access by switching to the new Outlook for Windows or Outlook for the web.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC939925](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC939925)

### Late-Feb 2025 - New User Department Graph in Data Security Posture Management for AI

Microsoft Purview Data Security Posture Management for AI is adding a new graph to display the departments of users interacting with AI apps. The department data will be sourced from Entra ID user profiles.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC988145](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC988145)

### Late-Feb 2025 - Move Emails Between Accounts in the New Outlook for Windows.

Admins will have the option to let users move emails between accounts in the new Outlook for Windows. This can be controlled using the new _Set-OWNMailboxPolicy_ parameter “_\-ItemsToOtherAccountsEnabled”_. By default, this policy is set to False, meaning users won’t be able to move emails between accounts unless explicitly enabled by admins.

**Note:** This feature is not available for GCC High and DoD clouds.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=470018](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=470018)

### Enhancements

### Early-Feb 2025 - Data Loss Prevention: Gain Policy Insights with Microsoft 365 Copilot for Security

Microsoft 365 Copilot for Security will provide insights into Microsoft Purview DLP policies. Admins will be able to review policy coverage based on location, classifiers, and notifications, making it easier to adjust policies as needed. This rollout will be generally available by early-Feb 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC949003](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC949003)

### Feb 2025 - General Availability of New Modernized eDiscovery in Purview

The modernized Microsoft Purview eDiscovery experience will be rolled out to general availability in the Purview portal. This update integrates Content Search, eDiscovery Standard, and eDiscovery Premium into a single, streamlined workflow, providing users with an easier way to switch between premium and non-premium features. Added to that, new features like Advanced Data Source Mapping, and Statistics will be available for GA.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC808165](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC808165)

### Mid-Feb 2025 - Enhancements to Microsoft Purview eDiscovery Export

Microsoft is enhancing the export functionality in Microsoft Purview eDiscovery to improve efficiency and usability. The updates include a unified structure, direct browser downloads for Standard users, faster exports, enhanced reporting, expanded options, and additional columns in the Export item report.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC939916](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC939916)

### Mid-Feb 2025 - Data Lifecycle Management: Separate Retention Policies for Copilot and AI Apps

Starting mid-February 2025, organizations will be able to set separate retention policies for Microsoft Teams Chat, Copilot, Copilot Studio, and ChatGPT Enterprise. This feature will be enabled by default.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC973511](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC973511)

### Late-Feb 2025 Endpoint Data Loss Prevention: Paste to Browser Restriction on macOS Device

Currently, DLP policies that restrict users from pasting sensitive content into browsers apply only to Windows devices. However, starting late February 2025, these policies will automatically extend to macOS devices as well.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC987324](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC987324)

### Existing Functionality Changes

### Early-Feb 2025 – Update to Get-CsPhoneNumberAssignment Cmdlet

The page size limit for the Get-CsPhoneNumberAssignment cmdlet (phone number retrieval API) will be updated to a maximum of 1,000 numbers per query. Any request with a “-top” parameter exceeding 1,000 will result in a “Bad request” error.  

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC950880](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC950880)

### Early-Feb 2025 - Enable Transcription Policy by Default in Micrsoft Teams

Microsoft Teams is updating its default transcription policy for new tenants. Starting early February 2025, transcription setting will be enabled by default in global meeting policies for new tenants.

For existing tenants, this change will apply only if no customizations have been made to their Teams meeting policies.

**Note:** This update applies to Teams for Windows desktop and Teams for Mac desktop.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=468282](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=468282)

### Feb 01, 2025 - Azure Key Vault: Soft-delete Will be Enabled in All Key Vaults

Soft Delete preserves deleted key vaults and secrets for up to 90 days, enabling customers to restore them through a self-serve process.

**_Ref:_** [https://learn.microsoft.com/en-us/azure/key-vault/general/soft-delete-change](https://learn.microsoft.com/en-us/azure/key-vault/general/soft-delete-change)

### Mid-Feb 2025 - Data Lifecycle Management: Separate Copilot Retention Policies from Teams Chats

Starting mid-February 2025, admins will be able to configure separate retention policies for Microsoft Teams chats and Microsoft 365 Copilot interactions in Microsoft Purview Data Lifecycle Management.

Previously, both were managed together under the same policy. With this update, organizations can apply distinct retention settings based on their compliance needs. This feature will be enabled by default.

**_Ref:_** [https://admin.microsoft.com/#/MessageCenter/:/messages/MC926899](https://admin.microsoft.com/#/MessageCenter/:/messages/MC926899)

### Mid-Feb 2025 - Microsoft Teams: New Policy for Voice and Face Enrollment will Default to "On"

In February 2025, Microsoft will update the Teams meeting policy by replacing the current **_csTeamsMeetingPolicy_** with the new **_csTeamsAIPolicy_**, which defaults to ON. The new policy will split the single setting for managing both face and voice profiles, known as EnrollUserOverride, into two separate settings: EnrollFace and EnrollVoice. These new settings will allow for independent management of face and voice profiles for users.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC912707](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC912707)

### Mid-Feb 2025 - Short Meeting URLs for Microsoft Teams

Microsoft plans to shorten the meeting URLs for easy sharing across all Teams platforms. The URL will contain only the meeting ID and other parameters such as tenant ID, Organizer ID, Conversation ID, and message ID will not be there.

This will be the new URL format: [https://teams.microsoft.com/meet/<meeting\_id>?p=<HashedPasscode>](https://teams.microsoft.com/meet/%3Cmeeting_id%3E?p=%3CHashedPasscode%3E)

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC772556](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC772556)

### Mid-Feb 2025 - Microsoft Teams: Shifts Graph APIs in Beta Moved to Production

The Shifts Graph APIs for Microsoft Teams are transitioning from beta to production, improving stability and reliability. Organizations are advised to migrate to the production endpoints and update their API calls from beta to version 1.0.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC916866](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC916866)

### Action Needed

### Feb 10, 2025 - Private Unlisted Groups in External Networks on Viva Engage Will Be Deleted

Private unlisted groups in external networks on Viva Engage will be deleted along with their data by February 10, 2025.  

**Solution:** Convert these groups to listed ones to preserve the data.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC867664](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC867664)

### Feb 2025- Removal of the ApplicationImpersonation Role Based Access Control (RBAC) in Exchange Online

Microsoft is going to remove ApplicationImpersonation Role Based Access Control (RBAC) role and its feature set from Exchange Online.

**Solution**: Transition your applications to Microsoft Graph for accessing Exchange Online data, as EWS is approaching retirement.

**_Ref_**: [https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-rbac-application-impersonation-in-exchange-online/ba-p/4062671](https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-rbac-application-impersonation-in-exchange-online/ba-p/4062671)

### Readiness Check

### February 28, 2025 – Temporary Outage of MSOnline PowerShell Module

As the retirement of the MSOnline module approaches, Microsoft has scheduled a series of temporary outages. Before February 28, 2025, users will experience at least two outages, each lasting between 3 to 8 hours, at different times of the day. During these outages, attempts to use MSOnline cmdlets will fail, with a message indicating that MSOnline PowerShell is no longer allowed.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991)

  

## Mar 2025

### Retirements

### March 1, 2025 - Retirement of .FBX and .SKP 3D file Format Support in the Microsoft 365 App

Microsoft 365 will retire support for Filmbox (.FBX) and SketchUp (.SKP) file formats on March 1, 2025. Users will no longer be able to insert these file types after the change, but any previously inserted .FBX or .SKP models will remain in documents.

**_Ref:_** [https://admin.microsoft.com/#/MessageCenter/:/messages/MC950892](https://admin.microsoft.com/#/MessageCenter/:/messages/MC950892)

### March 1, 2025 - Retirement of Search-MailboxAuditLog and New-MailboxAuditLogSearch Cmdlets

Microsoft will retire the Search-MailboxAuditLog and New-MailboxAuditLogSearch cmdlets in Microsoft Exchange Online starting March 1, 2025.

**Solution**: Use "Search-UnifiedAuditLog" as an alternative.

**_Ref_**: [https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310](https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310)

### March 31, 2025 - Retirement of Old Search Usage Reports in Microsoft 365 Admin Center

To enhance consistency and user experience, the legacy Search usage reports in Microsoft 365 will be retired. However, this change will not impact the existing default reports in the Search and Intelligence portal.

**Solution:** Download the old Search usage reports by March 31, 2025, if needed. Afterward, use the new Search usage report under the Insights tab in the Microsoft 365 Admin Center.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=976821](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=976821)

### New Features

### Mid-Mar 2025 – Move Email Between Mailbox and PST File in New Outlook for Windows

The new Microsoft Outlook for Windows will soon allow users to drag and drop emails between mailboxes and PST files. The update will be generally available from early March 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC966640](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC966640)

### Mar 2025 – New DLP action to Trigger Custom Power Automate Workflows

Microsoft will introduce a new DLP action that triggers custom Power Automate workflows when a DLP policy is violated.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=380721](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=380721)

### Early-March 2025 - Data Loss Prevention (DLP) Alerts as Indicators in IRM Policies

Microsoft Purview Insider Risk Management will enable admins to use Data Loss Prevention alerts as indicators within IRM policies. This feature will help admins track DLP alerts tied to specific policies in IRM, making it easier to detect high-risk alerts without the need to switch to DLP.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=475057](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=475057)

### Early March 2025 - Disable the Ability to Send Messages in Meeting Chat

Microsoft Teams will soon offer more control over meeting chat settings. Admins can enable two new options:

*   **In-meeting only for everyone**: This setting allows participants to send messages only while the meeting is active.
*   **In-meeting only except anonymous users**: This option allows only authenticated users to send messages while the meeting is active, preventing anonymous users from sending messages before or after the meeting.

**_Note:_** Applicable for Teams for Windows desktops and Mac desktops, Teams on the web, and Teams for iOS/Android.

**_Ref:_** [https://admin.microsoft.com/#/MessageCenter/:/messages/MC920298](https://admin.microsoft.com/#/MessageCenter/:/messages/MC920298)

### Mid-Mar 2025 - Integration of Adaptive Protection with Data Lifecycle Management

Microsoft will roll out the integration of Adaptive Protection with Data Lifecycle Management (DLM) in general availability by mid-March 2025. This integration will allow admins to preserve items deleted by high-risk users, enabling easy restoration when needed.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110)

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

### Mar 2025 - Optical Character Recognition Support for SharePoint Online and OneDrive for Business

Microsoft is bringing Optical Character Recognition (OCR) support to SharePoint Online and OneDrive for Business. This update will allow automated detection of sensitive content within images and enable the application of DLP policies to safeguard data and prevent exfiltration.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=160010](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=160010)

### Late-March 2025 - The New Streamlined Chat and Channels Experience in Microsoft Teams

Microsoft Teams has started merging the Chat and Teams views into a single 'Chat' view, uniting chats, teams, and channels for easier navigation. This new view offers filters for Unread, Chats, Channels, and Meetings, an @mentions list for tracking mentions, and a Favorites section for pinned items. This update will be generally available starting late March 2025.

**Note:** This experience applies to Teams on Windows desktops, Mac desktops, the web, and iOS and Android devices.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/blog/2024/10/28/streamline-collaboration-with-the-new-chat-and-channels-experience-in-microsoft-teams/?](https://www.microsoft.com/en-us/microsoft-365/blog/2024/10/28/streamline-collaboration-with-the-new-chat-and-channels-experience-in-microsoft-teams/?)

### Existing Functionality Changes

### Mar 2025 – Decoupling of Policy Tips and Email Notifications for SharePoint and OneDrive

Currently, enabling email notifications for a DLP policy also requires enabling the policy tips, and vice versa. However, Microsoft will soon allow admins to configure email notifications and policy tips independently for SharePoint and OneDrive DLP policies.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=394279](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=394279)

### Action Needed

### Mar 30, 2025 – End of Support for Azure AD and MSOnline PowerShell Modules

Azure AD and MSOnline PowerShell modules will reach end of support by March 2025.

**Note:** Identify and migrate your scripts to use Microsoft Graph.  
  
**_Ref_**: [https://techcommunity.microsoft.com/t5/microsoft-entra-blog/important-update-deprecation-of-azure-ad-powershell-and-msonline/ba-p/4094536](https://techcommunity.microsoft.com/t5/microsoft-entra-blog/important-update-deprecation-of-azure-ad-powershell-and-msonline/ba-p/4094536)

## April 2025 (Attention Needed: 6)

### Early-April 2025 – MSOnline PowerShell Retirement

Microsoft will retire the MSOnline PowerShell module between early April 2025 and late May 2025.  

**Solution:** Migrate to Microsoft Graph PowerShell SDK or Microsoft Entra PowerShell module.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991)

### April 2025 - Mail Merge (Advanced) on Outlook on the Web and New Outlook for Windows  

Enhanced mail merge features are coming to Outlook on the Web and the new Outlook for Windows in April 2025. Users will be able to insert dynamic fields into email templates for personalized emails and advanced customizations.  

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=423047)

### Apr 2025 -General Availability of Microsoft Copilot for GCC Environments  

Microsoft Copilot will be available for GCC users at no additional cost when signed in with a Microsoft Entra account (no Copilot license required).  

**_Ref_**: [https://techcommunity.microsoft.com/blog/publicsectorblog/microsoft-365-copilot-gcc-ga-update-empowering-public-sector-innovation---update/4222952](https://techcommunity.microsoft.com/blog/publicsectorblog/microsoft-365-copilot-gcc-ga-update-empowering-public-sector-innovation---update/4222952)

### Apr 02, 2025 – Retirement of Domain Isolated Web Part in SharePoint Framework

  
As part of the SharePoint Framework domain isolated web parts retirement, this feature will be turned off for newly created tenants starting from Apr 02, 2025.

**Note:** From Apr 02, 2026, existing tenants will no longer be able to use this feature.

**_Ref_**: [https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/](https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/)

### Apr 2, 2025 - Upgrade to the latest version of Microsoft Entra Connect by April 2, 2025

In early October 2024, a new version (2.4.XX.0) of Microsoft Entra Connect Sync was released, featuring a backend service update to improve security. Customers are required to upgrade to this version by early April 2025 to prevent any potential service interruptions.

**_Ref:_** [https://entra.microsoft.com/#view/Microsoft\_AAD\_IAM/ChangeManagementHubList.ReactView?Microsoft\_AAD\_IAM\_legacyAADRedirect=true](https://entra.microsoft.com/#view/Microsoft_AAD_IAM/ChangeManagementHubList.ReactView?Microsoft_AAD_IAM_legacyAADRedirect=true)

### Late - April- 2025 – New Cmdlet for Content Explorer

A new cmdlet, _Export-ContentExplorerData_, will be available by late-April 2025. This cmdlet allows admins to export all scanned content data from Content Explorer, providing a streamlined way to manage and analyze content data.  

**Ref:** [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC698421](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC698421)

## May 2025 (Attention Needed: 4)

### May 2025: OneDrive Sync Admin Reports for GCC

Microsoft will roll out OneDrive Sync Admin Reports in the Microsoft 365 admin center for GCC users by May 2025. These reports will help admins monitor sync client usage and errors across the organization.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=393333](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=393333)

### Mid -May 2025 - Third-party Add-in User Report can be Sent to Microsoft for Analysis

Microsoft will allow admins using third-party add-ins for report message solutions to configure Defender for Office 365 to automatically send user-reported messages to Microsoft for analysis.

Sending these messages to Microsoft for analysis not only provides valuable insights for security analysts but also improves the accuracy of Defender for Office 365 filters.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC962528](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC962528)

### Mid-May 2025 - Policy Alerts Improvements in Microsoft Purview Communication Compliance

Communication Compliance is enhancing policy alert customization. Admins will have the ability to set the alert frequency for each policy and adjust the email alert frequency and recipients directly within the policy creation wizard, via the new alerts page. This update will be generally available from mid-May 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920304](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920304)

### Mid-May 2025 – New Filters in Microsoft Purview Audit Search

To help you retrieve relevant logs in the Microsoft Purview audit search, Microsoft will include four additional filters in general availability. They are,  

Id – Unique identifier of an audit record.

UserType – The type of user that performed the operation.

UserKey-Azure Active Directory Object ID in GUID format.

ClientIP – The IP address of the device that was used when the activity was logged.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC789312](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC789312)

## June 2025 (Attention Needed: 5)

### June 2025 - Message Recall Feature for Outlook for Mac

The Cloud-based Exchange Online Message Recall feature will soon be available for Outlook for Mac users, with a preview rollout scheduled for June 2025.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=189804](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=189804)

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

## Q3 2025 (Attention Needed: 5)

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

### Sep 2025- Basic Auth for Client Submission (SMTP AUTH) Retirement in Exchange Online

Exchange Online will permanently remove support for Basic authentication with Client Submission (SMTP AUTH) in September 2025.

**Solution:** You can start to use OAuth with Client Submission (SMTP AUTH).

**_Ref_**: [https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-retire-basic-auth-for-client-submission-smtp/ba-p/4114750](https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-retire-basic-auth-for-client-submission-smtp/ba-p/4114750)

### Sep 30, 2025 – Retirement of Managing Authentication Methods in Legacy MFA &SSPR Policy

Starting Oct 2025, Microsoft no longer allow authentication methods to be managed in the legacy MFA and SSPR policies.

**Solution:** Organizations should use the converged authentication methods policy where methods can be managed centrally for all authentication scenarios including passwordless, MFA and SSPR.

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448)

## Q4 2025 (Attention Needed: 5)

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

### Dec 2025 - Existing Office 365 Connectors will stop Working

Existing Office 365 connectors will continue to work until December 2025, after which they will no longer work.

**_Ref:_** [https://learn.microsoft.com/en-us/power-bi/connect-data/service-publish-from-excel](https://learn.microsoft.com/en-us/power-bi/connect-data/service-publish-from-excel)

### Dec 2025 - Integration of New ChatGPT Enterprise Connector with Microsoft Purview Compliance Portal

The ChatGPT Enterprise connector will be integrated into the Microsoft Purview Compliance portal, allowing admins to discover, collect, and store prompts and responses from users' interactions with ChatGPT.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=401125](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=401125)

## 2026 (Attention Needed: 11)

### Jan 13, 2026 – End of Extended Support for Microsoft Advanced Threat Analytics 1.x

Microsoft Advanced Threat Analytics (ATA) extended support will be ended on January 13, 2026.

**Solution**: Updates for Microsoft ATA are available from Microsoft Update or by manual download.

**_Ref_**: [https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c](https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c)

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