# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.  
  
Discover the **key changes, deprecations**, and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

  
Here is a list of changes categorized by month and year.  

*   Jan 2025 (New Features: 11, Retirements: 6, Enhancements: 7, Existing Functionality Changes: 2, Action Needed: 2)
*   Feb 2025 (New Features: 5, Retirements: 2, Enhancements: 2, Existing Functionality Changes: 1, Action Needed: 2)
*   Mar 2025 (Attention Needed:5)
*   Apr 2025 (Attention Needed: 6)
*   May 2025 (Attention Needed: 2)
*   June 2025 (Attention Needed: 3)
*   Q3 2025 (Attention Needed: 3)
*   Q4 2025 (Attention Needed: 4)
*   2026 (Attention needed: 11)

  

## Jan 2025

New Features: 11 | Retirements: 6 | Enhancements: 7 | Existing Functionality Changes: 2 | Action Needed: 2

### New Features:

### Jan 2025 - Enhanced Information Barriers with New Capabilities

Microsoft will upgrade Information Barriers (IB) from version 1 to version 2, introducing new capabilities like:

*   Larger segment scale
*   Multi-segment support
*   Flexible people discoverability

  
Existing IB v1 users can upgrade to IB v2 to access these enhanced features.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=115482](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=115482)

### Mid-Jan 2025 - Block User Feature in Microsoft Teams

Starting January 2025, Microsoft will introduce a block user feature, allowing admins to create a block list that prevents specific users from participating in 1:1 and group chats with the organization.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC888879](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC888879)

### Mid-Jan 2025 - Move Emails Between Accounts in the New Outlook for Windows.

Admins will soon have the option to let users move emails between accounts in the new Outlook for Windows. This can be controlled using the new _Set-OWNMailboxPolicy_ parameter “_\-ItemsToOtherAccountsEnabled”_. By default, this policy is set to False, meaning users won’t be able to move emails between accounts unless explicitly enabled by admins.

**Note:** This feature is not available for GCC High and DoD clouds.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=470018](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=470018)

### Mid-Jan 2025 - Move Email Between Mailbox and PST file in New Outlook for Windows

The new Microsoft Outlook for Windows will soon enable users to transfer emails between mailboxes and PST files. The rollout begins in mid-January 2025.  

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC966640](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC966640)

### Mid-Jan 2025 - IRM Alerts in Microsoft Defender XDR

Microsoft Purview's Insider Risk Management (IRM) data will integrate with Microsoft Defender XDR, enabling comprehensive investigation and correlation. IRM data will be accessible through the unified alert and incident queue, advanced hunting with KQL queries, Graph API, and Microsoft Sentinel. This feature will roll out to public preview by mid-January 2025.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC961761](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC961761)

Mid-Jan 2025 - Best Practices Configuration Dashboard in Teams Admin Center

A Best Practices Configuration dashboard will be available in the Teams Admin Center starting January 2025. This dashboard will help admins confirm that settings align with Microsoft-recommended best practices in areas like:

*   Updating outdated client versions
*   Enabling appropriate ports and protocols
*   Implementing split tunneling for VPNs

Non-conformance will be highlighted, and the dashboard will be enabled by default.

  
**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC929034](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC929034)

### Mid-Jan 2025 - Org Explorer Feature for Enterprise Users

Starting mid-January 2025, the Org Explorer feature will be available to all enterprise users, providing insights into internal structures and connections.

**Note**: Switch to the new Outlook for Windows or Outlook for web to have early access to this new feature.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC939925](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC939925)

### Mid-Jan 2025 - Manage External Access Policies in Teams Admin Center

External access policies in the Teams admin center are currently manageable only through PowerShell cmdlets. However, starting mid-January 2025, admins will be able to use the new external access policy management page to manage policies for users.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC938541](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC938541)

### Mid-Jan 2025 - Email OTP Verification for External Participants to Join Teams Meetings

Microsoft Teams will introduce email OTP (one-time passcode) verification for external participants to join meetings. Meeting organizers can require external attendees to verify their email before joining. Admins will have a new meeting policy in the Teams admin center to manage this setting.

**Note:** Applicable to Teams on Windows, Mac, web, iOS, and Android.

**_Ref_**: [https://techcommunity.microsoft.com/blog/microsoftteamsblog/enhance-meeting-security-with-teams-premium%E2%80%99s-email-verification-for-external-me/4292196](https://techcommunity.microsoft.com/blog/microsoftteamsblog/enhance-meeting-security-with-teams-premium%E2%80%99s-email-verification-for-external-me/4292196)

### Late-Jan 2025 – General Availability of New Conditions in Data Loss Prevention for Mac Endpoints

By late Jan 2025, Microsoft will add seven new Data Loss Prevention (DLP) conditions for Mac endpoints, enhancing sensitive data management. These are the seven new conditions applicable to Mac endpoints:

*   Document is unscannable
*   The document didn't complete the scanning
*   Document name matches patterns
*   Document size equals or is greater than
*   Document Property Is
*   Document name contains words or phrases
*   The document is password-protected.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC901829](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC901829)

### Late-Jan 2025 - Unified Management of Teams Apps in Teams, Outlook, and the Microsoft 365 App

Starting in late January 2025, the Unified App Management feature will streamline app management across Teams, Outlook, and the Microsoft 365 App. Previously managed separately in Teams and Microsoft 365 admin centers, apps will be consistently managed across all platforms.

**Note:** This feature is available only if you use App Center management in your organization.

**_Ref:_** [https://learn.microsoft.com/en-us/MicrosoftTeams/manage-apps-across-m365](https://learn.microsoft.com/en-us/MicrosoftTeams/manage-apps-across-m365)

### Retirements:

### January 2025 – Office 365 Connectors Retirement from Microsoft Teams

Owners of webhook-based Office 365 connectors in Teams must update their URLs to a new structure by January 31, 2025. Immediate updates are crucial to avoid service disruptions, as all webhook-based connectors must be updated to continue posting messages in Teams.

Note that the O365 Connectors service will be retired at the end of 2025.

**Solution**: Consider migrating your webhooks to the Workflows app within Teams.

**_Ref:_** [https://devblogs.microsoft.com/microsoft365dev/retirement-of-office-365-connectors-within-microsoft-teams/](https://devblogs.microsoft.com/microsoft365dev/retirement-of-office-365-connectors-within-microsoft-teams/)

### Early- Jan 2025 - Deprecation of Get-CsDialPlan Cmdlet from Teams PowerShell Module

Microsoft will deprecate the _Get-CsDialPlan_ cmdlet in the Teams PowerShell module. Additionally, the _DialPlan_ attribute in Get-CsOnlineUser and the LocationProfile attribute in Get-CsUserPolicyAssignment will be retired.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC950879](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC950879)

### Jan 6, 2025 - Retirement of Tag Feature in Microsoft 365 Apps

Microsoft will retire the "Tags" feature in Microsoft 365 apps between Jan 6, 2025, and Jan 10, 2025. After this period, users will no longer be able to view or apply tags.

**Solution**: Use the "Favorites" feature as an alternative to access important content easily.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC961601](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC961601)

### Jan 13, 2025 - Microsoft Viva Engage: Retirement of Private Unlisted Groups in External Networks

Microsoft Viva Engage will retire private unlisted groups in external networks on January 13, 2025. After this date, users will no longer be able to create, export, access, or participate in unlisted groups within external networks.

**Solution:** Admins are advised to convert them to listed ones to secure their data.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC867664](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC867664)

Jan 14, 2025: The PowerPoint QuickStarter Feature will be Completely Retired

The PowerPoint QuickStarter feature will be completely retired by Jan 14, 2025, for Office versions 2409 for Windows and 2410 for Mac.

**_Ref:_** [https://support.microsoft.com/en-us/office/research-a-topic-with-powerpoint-quickstarter-4784f273-0b2c-456c-9c89-24e5b977c224](https://support.microsoft.com/en-us/office/research-a-topic-with-powerpoint-quickstarter-4784f273-0b2c-456c-9c89-24e5b977c224)

### Mid-Jan 2025 - ‘Alert Notifications’ Feature Retirement in Microsoft Defender

The "Alerts notifications" feature in Microsoft Defender for Identity will be retired starting mid-Jan 2025.

**Solution:** As an alternative, you can use the "Incident email notifications" page in Microsoft Defender XDR. Admins are encouraged to transfer all existing notification settings to the Email Notifications page in Microsoft Defender XDR.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC912708](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC912708)

## Enhancements

### Early 2025 - MFA Enforcement for CLI, Azure PowerShell, IaC Tools

As part of enforcing MFA for all Azure users, MFA enforcement for Azure Command Line Interface (CLI), Azure PowerShell, and Infrastructure as Code (IaC) tools will gradually be introduced to all tenants starting in early 2025.

**_Ref:_** [https://learn.microsoft.com/en-us/entra/identity/authentication/concept-mandatory-multifactor-authentication#enforcement-phases](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-mandatory-multifactor-authentication#enforcement-phases)

### Early-Jan 2025 – Add Approvals to Any Document Library in SharePoint

With this feature, admins can enable or disable approvals using the “Configure Approvals” option found under the “Automate” dropdown in the SharePoint Online document library. This feature will be enabled by default.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC912181](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC912181)

### Jan 2025 - Add Shared Mailbox as Accounts in New Outlook for Windows

Starting January 2025, you’ll be able to add shared mailboxes as accounts in the New Outlook for Windows. With the necessary permissions, you can access these shared mailboxes by providing the user’s credentials.

  
**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=375635](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=375635)

### Jan 4, 2025 - Public Preview Refresh for Hardware OATH Tokens

Microsoft introduced the Hardware OAuth token in public preview, which can be managed via the Microsoft Entra admin center. Following that, Microsoft will allow admins to create tokens using the MS Graph API.

Tokens created with the new API can only be managed through the Graph API, not the admin center. The new experience will run alongside the legacy version until its deprecation.

**_Ref:_** [https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-oath-tokens?WT.mc\_id=Portal-Microsoft\_AAD\_IAM#hardware-oath-tokens-preview](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-oath-tokens?WT.mc_id=Portal-Microsoft_AAD_IAM#hardware-oath-tokens-preview)

### Mid-Jan 2025 - Enablement of Passkeys in Authenticator for passkey (FIDO2) Organizations

Starting mid-January 2025, organizations with passkey (FIDO2) authentication enabled with no key restrictions will support passkeys in the Microsoft Authenticator app, in addition to FIDO2 security keys. Users can add "Passkey in Microsoft Authenticator" through aka.ms/MySecurityInfo. If you choose not to enable this change for your users, you can manage it by setting key restrictions in the passkey (FIDO2) policy.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC920300](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC920300)

### Mid-Jan 2025 - Microsoft Copilot in Teams and Outlook

From mid-January 2025, Entra account users can access Microsoft Copilot in Teams and Outlook, with the option to pin it on the left navigation panel. It will also be listed in the Store for users to install, following existing admin controls for app management.

**Note**: During deployment, the Copilot app will briefly appear for Semi-Annual Channel users of classic Outlook for Windows but will no longer be visible after they upgrade to Version 2408 or higher.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC922627](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC922627)

### Late-Jan 2025 - Enhancements to Copilot Administrative Page in Microsoft 365

The Copilot page in the Microsoft 365 admin center will feature an enhanced Overview section and a new Health section. The Overview will provide key metrics such as active user rate, AI assistance score, and user sentiment. The Health section will offer Copilot-specific health insights, including device update statuses for M365 apps.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC961759](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC961759)

## Existing Functionality Changes

### Jan 2025 - Decoupling of Policy Tips and Email Notifications for SharePoint and OneDrive

Currently, enabling email notifications for a DLP policy also requires enabling the policy tips, and vice versa. However, Microsoft will soon allow admins to configure email notifications and policy tips independently for SharePoint and OneDrive DLP policies. This update will be available in Preview by January 2025.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=394279](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=394279)

### Jan 6, 2025 - Update to Get-CsPhoneNumberAssignment Cmdlet

Starting January 6, 2025, the page size limit for the Get-CsPhoneNumberAssignment cmdlet (phone number retrieval API) will be updated to a maximum of 1,000 numbers per query. Any request with a "-top" parameter exceeding 1,000 will result in a "Bad request" error.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC950880](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC950880)

## Action Required:

### Jan 17, 2025 - Upcoming Changes to Message Center Email Service Notification Recipients

Currently, email notifications are sent to users with the System Administrator role, with an option to add other recipients via PowerShell. Starting January 17, 2025, only users assigned the Dynamics 365 or Power Platform administrator role in Microsoft 365 or Entra admin centers will receive these notifications.

**Solution:** Review and assign the required roles to the intended recipients for email notifications.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC964456](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC964456)

### Late-Jan 2025 - Microsoft Auto-Archives Unlicensed OneDrive Accounts

Starting in **late January 2025**, any OneDrive accounts left unlicensed for more than 90 days will be automatically archived, hitting you with extra costs to regain access in Microsoft Archive. Yes! You will be charged $0.05 per GB per month to store unlicensed OneDrive content and $0.60 per GB to reactivate the account in the Microsoft 365 archive.

**Solution:** Either delete the unlicensed OneDrive accounts or assign the necessary licenses to them.

**_Ref:_** [https://learn.microsoft.com/en-us/sharepoint/unlicensed-onedrive-accounts](https://learn.microsoft.com/en-us/sharepoint/unlicensed-onedrive-accounts)

## Feb 2025 (Attention Needed: 12)

## New Features

### Feb 2025 - Insider Risk Management- Risk AI Usage

Microsoft plans to introduce a new feature in Insider Risk Management, which will be widely available from April 2025. This feature aims to detect potentially risky use of AI. It includes monitoring activities involving sensitive information in prompts generated by AI assistants, covering both copilots and third-party AI applications.

  
**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=In%20development&searchterms=394281](https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=In%20development&searchterms=394281)

### Feb 2025 - New DLP action to Trigger Custom Power Automate Workflows

Microsoft will introduce a new DLP action that triggers custom Power Automate workflows when a DLP policy is violated.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=380721](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=380721)

### Early-Feb 2025 - Microsoft Teams: New policy for voice and face enrollment will default to "On"

In February 2025, Microsoft will update the Teams meeting policy by replacing the current **_csTeamsMeetingPolicy_** with the new **_csTeamsAIPolicy_**, which defaults to ON. The new policy will split the single setting for managing both face and voice profiles, known as EnrollUserOverride, into two separate settings: EnrollFace and EnrollVoice. These new settings will allow for independent management of face and voice profiles for users.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC912707](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC912707)

### Mid -Feb 2025 - Third-party add-in User Report can be Sent to Microsoft for Analysis

Microsoft will allow admins using third-party add-ins for report message solutions to configure Defender for Office 365 to automatically send user-reported messages to Microsoft for analysis.

Sending these messages to Microsoft for analysis not only provides valuable insights for security analysts but also improves the accuracy of Defender for Office 365 filters.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC962528](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC962528)

### Mid –Feb 2025 - New Filters in Microsoft Purview Audit Search  

To help you retrieve relevant logs in the Microsoft Purview audit search, Microsoft will include four additional filters in public preview. They are,  

Id - Unique identifier of an audit record.

UserType - The type of user that performed the operation.

UserKey-Azure Active Directory Object ID in GUID format.

ClientIP - The IP address of the device that was used when the activity was logged.

  
**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC789312](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC789312)

## Retirements

### Feb 22, 2025- Viva Topics Retirement

Viva Topics will be discontinued on February 22, 2025, and Microsoft will no longer pursue new feature enhancements for the platform.

Existing Topic pages will transition to standard SharePoint pages. Users can edit and publish updates as other SharePoint pages. AI-generated Topic pages will no longer be accessible.

**_Ref:_** [https://learn.microsoft.com/en-us/microsoft-365/topics/changes-coming-to-topics](https://learn.microsoft.com/en-us/microsoft-365/topics/changes-coming-to-topics)

### Late- Feb 2025: Retirement of Monitor Action in the Safe Attachments

Starting February 2025, Microsoft will remove the "Monitor" action in the Safe Attachments policy. Any existing policies set to "Monitor" will be automatically changed to "Block". The recipients, status, or priority configured in the policy will remain unchanged.

Post-retirement, the only available actions in the Safe Attachments policy will be Off, Block, and Dynamic Delivery. Note that you will also lose the ability to "Redirect messages with detected attachments," as this action applies only to the Monitor.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC918563](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC918563)

## Existing Functionality Changes

### Mid-Feb 2025 - Short Meeting URLs for Microsoft Teams

Microsoft plans to shorten the meeting URLs for easy sharing across all Teams platforms. The URL will contain only the meeting ID and other parameters such as tenant ID, Organizer ID, Conversation ID, and message ID will not be there.

This will be the new URL format: [https://teams.microsoft.com/meet/<meeting\_id>?p=<HashedPasscode>](https://teams.microsoft.com/meet/%3Cmeeting_id%3E?p=%3CHashedPasscode%3E)

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC772556](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC772556)

### Feb 01, 2025 - Azure Key Vault: Soft-delete Will be Enabled in All Key Vaults

Soft Delete preserves deleted key vaults and secrets for up to 90 days, enabling customers to restore them through a self-serve process.

**_Ref:_** [https://learn.microsoft.com/en-us/azure/key-vault/general/soft-delete-change](https://learn.microsoft.com/en-us/azure/key-vault/general/soft-delete-change)

## Enhancements

### Feb 2025 - General Availability of New Modernized eDiscovery in Purview

The modernized Microsoft Purview eDiscovery experience will be rolled out to general availability in the Purview portal. This update integrates Content Search, eDiscovery Standard, and eDiscovery Premium into a single, streamlined workflow, providing users with an easier way to switch between premium and non-premium features. Added to that, new features like Advanced Data Source Mapping, and Statistics will be available for GA.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC808165](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC808165)

## Action Needed

### Feb 10, 2025 - Private Unlisted Groups in External Networks Will Be Deleted

Private unlisted groups in external networks on Viva Engage will be deleted along with their data by February 10, 2025.  

**Solution:** Convert these groups to listed ones to preserve the data

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC867664](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC867664)

### Feb 2025- Removal of the ApplicationImpersonation Role Based Access Control (RBAC) in Exchange Online

Microsoft is going to remove ApplicationImpersonation Role Based Access Control (RBAC) role and its feature set from Exchange Online.

**Solution**: Transition your applications to Microsoft Graph for accessing Exchange Online data, as EWS is approaching retirement

**_Ref_**: [https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-rbac-application-impersonation-in-exchange-online/ba-p/4062671](https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-rbac-application-impersonation-in-exchange-online/ba-p/4062671)  

## Mar 2025 (Attention Needed:5)

### Early March 2025 - Disable the Ability to Send Messages in Meeting Chat

Microsoft Teams admin center will soon introduce two new options in meeting control: _In-meeting only for everyone and In-meeting only except for anonymous users. This helps_ admins to disable the ability to send messages in meeting chat before and after a meeting.

**_Note:_** Applicable for Teams for Windows desktops and Mac desktops, Teams on the web, and Teams for iOS/Android.

**_Ref:_** [https://admin.microsoft.com/#/MessageCenter/:/messages/MC920298](https://admin.microsoft.com/#/MessageCenter/:/messages/MC920298)

### March 1, 2025 - Retirement of .FBX and .SKP 3D file Format Support in the Microsoft 365 App

Microsoft 365 will retire support for Filmbox (.FBX) and SketchUp (.SKP) file formats on March 1, 2025. Users will no longer be able to insert these file types after the change, but any previously inserted .FBX or .SKP models will remain in documents.

**_Ref:_** [https://admin.microsoft.com/#/MessageCenter/:/messages/MC950892](https://admin.microsoft.com/#/MessageCenter/:/messages/MC950892)

### Mar 2025 - Optical Character Recognition Support for SharePoint Online and OneDrive for Business

Microsoft is bringing Optical Character Recognition (OCR) support to SharePoint Online and OneDrive for Business. This update will allow automated detection of sensitive content within images and enable the application of DLP policies to safeguard data and prevent exfiltration.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=160010](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=160010)

### Late-Mar 2025 - File Interactive Previews for GCC Environment

Microsoft Teams will roll out interactive file previews for chats and channels in the GCC environment. Initially, users will be able to preview PDFs, with plans to expand to other formats. This feature allows users to view files directly within Teams, reducing context switches and improving workflow efficiency.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC934727](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC934727)

### Mar 30, 2025- Azure AD and MSOnline PowerShell Modules may Stop Working

Microsoft has officially deprecated the Azure AD and MSOnline PowerShell modules Mar’24. However, they will remain functional until March 30, 2025, with support limited to critical security fixes.

**Note:** Only MSOnline versions 1.1.166.0 (2017) and later are guaranteed to function as expected.

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-blog/important-update-deprecation-of-azure-ad-powershell-and-msonline/ba-p/4094536](https://techcommunity.microsoft.com/t5/microsoft-entra-blog/important-update-deprecation-of-azure-ad-powershell-and-msonline/ba-p/4094536)

## April 2025 (Attention Needed: 4)

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

## May 2025 (Attention Needed: 2)

### May 2025: OneDrive Sync Admin Reports for GCC

Microsoft will roll out OneDrive Sync Admin Reports in the Microsoft 365 admin center for GCC users by May 2025. These reports will help admins monitor sync client usage and errors across the organization.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=393333](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=393333)

### Mid-May 2025 - New Cmdlet for Content Explorer

A new cmdlet, _Export-ContentExplorerData_, will be fully rolled out to General Availability by mid-May 2025. This cmdlet allows admins to export all scanned content data from Content Explorer, providing a streamlined way to manage and analyze content data.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC698421](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC698421)

## June 2025 (Attention Needed: 3)

### June 2025 - Message Recall Feature for Outlook for Mac

The Cloud-based Exchange Online Message Recall feature will soon be available for Outlook for Mac users, with a preview rollout scheduled for June 2025.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=189804](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=189804)

### June 2025: Block Specific Folders from OneDrive Sync

Starting June 2025, admins can block not just files or extensions but also specific folders from syncing with OneDrive through Group Policy.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=178292](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=178292)

### June 2025 - Date Lifecycle Management and Power Automate Integration in U.S Government Clouds

U.S. government cloud users can automate actions on items at the end of their retention period using Power Automate by June 2025.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=117523](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=117523)

## Q3 2025 (Attention Needed: 3)

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

## Q4 2025 (Attention Needed: 4)

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