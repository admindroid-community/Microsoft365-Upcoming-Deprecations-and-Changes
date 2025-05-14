# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.  
  
Discover the **key changes, deprecations**, and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

  
Here is a list of changes categorized by month and year.  

*   Apr 2025 (Retirements: 5, New Features: 10; Enhancements: 8, Existing Functionality Changes: 5, Action Needed: 2)
*   May 2025 (Retirements: 2, New Features: 7; Enhancements: 2, Existing Functionality Changes: 1, Action Needed: 1)
*   June 2025 (Attention Needed: 11)
*   Q3 2025 (Attention Needed: 9)
*   Q4 2025 (Attention Needed: 7)
*   2026 (Attention needed: 13)

  

## April 2025

Retirement: 5 | New Features: 10 | Enhancements: 8 | Existing Functionality Changes: 5 | Action Needed: 2

### Retirements

### Early- Apr 2025 – MSOnline PowerShell Retirement

Microsoft will retire the MSOnline PowerShell module between early April 2025 and late May 2025.  

**Solution:** Migrate to Microsoft Graph PowerShell SDK or Microsoft Entra PowerShell module.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991)

### Apr 02, 2025 – Retirement of Domain Isolated Web Part in SharePoint Framework

  
As part of the SharePoint Framework domain isolated web parts retirement, this feature will be turned off for newly created tenants starting from Apr 02, 2025.

**Note:** From Apr 02, 2026, existing tenants will no longer be able to use this feature.

**_Ref_**: [https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/](https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/)

### Apr 10, 2025 - Removal of EEEU Permission from Root Web and Default Document Library in OneDrive

To prevent data oversharing, Microsoft is removing the Everyone Except External Users (EEEU) permission from the root site and default document library in OneDrive, starting April 10, 2025.

**Solution**: Admins can grant explicit permissions to individual files and folders as needed.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?source=applauncher#/MessageCenter/:/messages/MC1013464](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/MessageCenter/:/messages/MC1013464)

### Apr 15, 2025 - Retirement of Azure AD Graph API

Microsoft has started retiring Azure AD Graph APIs, impacting both new and existing applications unless an extension is configured. By April 15, 2025, the retirement will be fully enforced, and Azure AD Graph API requests will stop functioning after this date unless opted for a temporary extension.

**Solution:** Review applications using Azure AD Graph API and migrate them to Microsoft Graph.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?source=applauncher#/MessageCenter/:/messages/MC989967](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/MessageCenter/:/messages/MC989967)

### Late-Apr 2025 - Retirement of Three Microsoft Secure Score SCIDs

Starting late April 2025, admins will no longer see the following Microsoft Secure Score recommendations in Microsoft Defender for Endpoint.

*   **SCID-84** – Enable Local Admin password management
*   **SCID-2020** – Turn on all system-level Exploit Protection settings
*   **SCID-2051** – Turn on Microsoft Defender Application Guard

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?source=applauncher#/MessageCenter/:/messages/MC1041962](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/MessageCenter/:/messages/MC1041962)

### New Features

### Early – Apr 2025 - Data Loss Prevention: Network Share Coverage and Exclusion Support on Mac Endpoints

Starting early April 2025, Microsoft will enable admins to configure DLP policies for sensitive files on network shares and mapped drives on Mac endpoints. This will help prevent actions like copying to USB drives or clipboard. Admins will also have the flexibility to exclude specific network shares from these policies based on their requirements.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=410397](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=410397)

### Early-Apr 2025 - Optical Character Recognition (OCR) for OneDrive for Business

Starting early April 2025, admins will have the ability to enable Optical Character Recognition (OCR) for OneDrive for Business directly from the Microsoft 365 admin center. This update ensures that all files become searchable, enhancing discoverability and supporting compliance efforts like eDiscovery.

**Note:** OCR is a pay-as-you-go feature.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?source=applauncher#/MessageCenter/:/messages/MC1041953](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/MessageCenter/:/messages/MC1041953)

### Early-Apr 2025 – New Compromised User Context in Insider Risk Management

Microsoft Entra provides two types of compromised user detections: Sign-in risk and User risk detections. These detections will now be integrated into the Insider Risk Management alert investigation experience.

With this update, admins can view compromised user alerts from Microsoft Entra while investigating users, enabling them to take appropriate action and faster remediation.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1006621](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1006621)

### Early-Apr 2025 - New Data Security Investigation Contributor Role in IRM

Microsoft Purview Insider Risk Management is introducing a new role: “Data Security Investigation Contributor” to the Insider Risk Management Investigators role group.

DSI is an AI-powered solution designed to detect, analyze, and mitigate data security risks. With this update, IRM investigators can initiate _Data Security Investigations_ directly from IRM cases, enhancing their ability to detect, analyze, and mitigate data security risks.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?source=applauncher#/MessageCenter/:/messages/MC1041756](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/MessageCenter/:/messages/MC1041756)

### Apr 3, 2025 – New Tenant-level Outbound Email Limits in Exchange Online

Microsoft will enforce Tenant External Recipient Rate Limits (TERRL), restricting outbound emails based on the number of purchased or trial licenses. These limits operate on a 24-hour rolling window, continuously tracking sent emails. And the enforcement starts in stages from April 3, 2025.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/introducing-exchange-online-tenant-outbound-email-limits/4372797](https://techcommunity.microsoft.com/blog/exchange/introducing-exchange-online-tenant-outbound-email-limits/4372797)

### Apr 9, 2025 - New Purview Data Security Investigations Solution in Microsoft Purview

DSI helps admins quickly find incident-related content across Microsoft 365, including emails, Teams messages, Copilot prompts, and documents. Its generative AI uncovers security risks and sensitive data, providing deeper insights.

Additionally, DSI maps connections between data, users, and activities. These insights help strengthen security policies and enhance overall protection. This feature will be rolled out to public preview by Apr 9, 2025.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-security-blog/accelerate-data-security-investigations-with-ai-powered-deep-content-analysis/4396099](https://techcommunity.microsoft.com/blog/microsoft-security-blog/accelerate-data-security-investigations-with-ai-powered-deep-content-analysis/4396099)

### Mid- Apr 2025 - Move Emails Between Accounts in the New Outlook for Windows

Admins will have the option to let users move emails between accounts in the new Outlook for Windows and Outlook for the web. This can be controlled using the new _Set-OWAMailboxPolicy_ parameter “_\-ItemsToOtherAccountsEnabled”_. By default, this policy is set to False, meaning users won’t be able to move emails between accounts unless explicitly enabled by admins. This feature will be out for General Availability by mid-April 2025.

**Note:** This feature is not available for GCC High and DoD clouds.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?source=applauncher#/MessageCenter/:/messages/MC994289](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/MessageCenter/:/messages/MC994289)

### Late-Apr 2025 - Microsoft PowerShell Cmdlet to Allow Federation with Specific Trial Tenant Domains

Microsoft Teams introduced the **\-ExternalAccessWithTrialTenants** setting in the Set-CsTenantFederationConfiguration cmdlet, enabling organizations to block all external access with trial-only tenants.

Now, expanding on this, Microsoft is introducing the **\-AllowedTrialTenantDomains** setting, offering more flexibility in managing federation. This new setting allows organizations to maintain the _block on trial-only tenants_ while explicitly permitting federation with _trusted trial tenant domains._

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?source=applauncher#/MessageCenter/:/messages/MC994289](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/MessageCenter/:/messages/MC994289)

### Late-Apr 2025 - New Predicates for Email DLP in Microsoft Purview

Microsoft is introducing new predicates in email Data Loss Prevention to enhance security and compliance. The "Recipient/Domain Count Over**"** feature is designed to help admins manage and control the distribution of sensitive information via email. With this feature, admins can set policies that trigger alerts or actions when an email exceeds a defined number of recipients or domains. This feature will enter public preview in late April 2025.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=483158](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=483158)

### Late-Apr 2025 – Client Health Dashboards in Teams Admin Center

Microsoft is introducing a new “Teams Client Health” page in the Teams admin center to help admins monitor the health of the Teams desktop client for Windows and Mac. This page will provide insights into version adoption, version health, and key client metrics such as crashes and launch/update failures.

**Note:** Only users with the following roles can access this page: Teams Administrator, Teams Communication Administrator, and Teams Communications Support Engineer.

**_Ref:_** [https://learn.microsoft.com/en-us/microsoftteams/teams-client-health](https://learn.microsoft.com/en-us/microsoftteams/teams-client-health)

### Enhancements

### Apr 2025 - Enriched Details of Auto-forwarded Emails in Exchange DLP

Microsoft will roll out an upgrade to Data Loss Prevention that provides more precise details for auto-forwarded emails. This enhancement ensures that forwarding users, recipients, and email evidence are accurately reflected in alerts, audit logs, and activity explorer.  

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=481343](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=481343)

Apr 1, 2025 - Public Preview Refresh for Hardware OATH Tokens

Microsoft introduced the Hardware OAuth token in public preview, which can be managed via the Microsoft Entra admin center. Following that, Microsoft will allow admins to create tokens using the MS Graph API.

Tokens created with the new API can only be managed through the Graph API, not the admin center. The new experience will run alongside the legacy version until its deprecation.

**_Ref:_** [https://entra.microsoft.com/#view/Microsoft\_Azure\_WhatsNew/ChangeManagementHubList.ReactView?Microsoft\_AAD\_IAM\_legacyAADRedirect=true](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-oath-tokens?WT.mc_id=Portal-Microsoft_AAD_IAM#hardware-oath-tokens-preview)

### Early-Apr 2025 - Updates to Data Loss Prevention Scopes

Currently, admins can create an Endpoint Data Loss Prevention (DLP) policy scoped to specific users or user groups. With this update, Microsoft Purview DLP will support scoping policies based on both users and machines, allowing admins to create and assign policies to devices and device groups in Endpoint.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=480732](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=480732)

### Early-Apr 2025 - Updates to Community Membership Approval in Microsoft Viva Engage

Microsoft Viva Engage is introducing a centralized approval page for Community Admins to manage multiple membership requests efficiently.

When a request is made, admins will receive an email notification. Clicking the link in the email will redirect them to a single console where they can review and approve all pending requests in one place.

**Note:** Applies to Engage app in desktop, Microsoft Outlook, Microsoft Teams, web.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=479406](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=479406)

### Mid-Apr 2025 - Updates to eSignature Service in SharePoint Online

Microsoft is enhancing the eSignature service in SharePoint Online. Currently, users must wait for their eSignature request on a PDF to process before creating another. With this update, users can initiate multiple requests without waiting for the previous one to complete.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1034583](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1034583)

### Mid-Apr 2025 – Policy Alerts Improvements in Microsoft Purview Communication Compliance

Communication Compliance is enhancing policy alert customization. Admins will have the ability to set the alert frequency for each policy and adjust the email alert frequency and recipients directly within the policy creation wizard, via the new alerts page. This update will be in public preview from mid-April 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920304](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920304)

### Late-Apr- 2025 - Data Loss Prevention: Gain Policy Insights with Microsoft 365 Copilot for Security

Microsoft 365 Copilot for Security will provide insights into Microsoft Purview DLP policies. Admins will be able to review policy coverage based on location, classifiers, and notifications, making it easier to adjust policies as needed. This rollout will be generally available by late-Apr 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC949003](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC949003)

### Late-Apr 2025 - Add a Loop Workspace Tab to Standard Channels in Microsoft Teams

Microsoft Teams is introducing the ability to add a Loop workspace tab to standard channels, enabling real-time collaboration. With this update, teams can co-create, collect, and organize content together seamlessly.

**Note:** Applies to Teams on Windows desktop, Teams on Mac desktop, and Teams on the web.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?source=applauncher#/MessageCenter/:/messages/MC973493](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/MessageCenter/:/messages/MC973493)

### Existing Functionality Changes

### Early-April 2025 - Changing the Storage Location for Whiteboards Created from the Teams Channel Tab

Currently, whiteboards created from the Teams channel tab are stored in the initiator's OneDrive, which can cause access issues due to sharing settings and information barriers. To address this, Microsoft is moving storage to the corresponding SharePoint site of the Teams channel. This change ensures seamless access for all channel members while maintaining security policies.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1024395](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1024395)

### Early-April 2025 - New Limit for Dynamic Distribution Groups in Exchange Online

Starting April 2025, Microsoft 365 organizations will be limited to 3,000 Dynamic Distribution Groups. Once this limit is enforced, admins won't be able to create additional DDGs unless they delete existing ones to stay within the limit.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1024399](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1024399)

### Apr-2025 - Migration to App-centric Management for Teams Apps

Microsoft has introduced App-centric management for Teams, a streamlined way to manage app access for users and groups. This replaces Teams app permission policies, providing greater flexibility and control over app management.

The migration to app-centric management began in March 2025 and is progressing in three phases. Phase 3 is now underway, automatically migrating users who skipped Phases 1 and 2.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC688930](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC688930)

### Apr 15, 2025 - Exchange Online to Reject Emails with Multiple From Addresses

Starting April 15, 2025, Exchange Online will reject emails with multiple From addresses unless a Sender header is included. This change ensures compliance with RFC 5322 and enhances security against spoofing. Tenants sending high volumes of affected emails are temporarily exempt.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC886603](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC886603)

### Apr 21, 2025 - Updates to App Governance Pre-Defined Policies in Defender for Cloud Apps

Starting April 21, 2025, Microsoft Defender for Cloud Apps will disable three pre-defined policies by default to improve alert accuracy. The policies being disabled are

*   Increase in data usage by an overprivileged or highly privileged app
*   Unusual activity from an app with priority account consent
*   Access to sensitive data

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1036568](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1036568)

### Action Required

### Apr 7, 2025 – Upgrade to the Latest Version of Microsoft Entra Connect

### Microsoft Entra Connect Sync 2.4.xx.0 was released in October 2024 with security enhancements. Using older versions may cause AD FS and PingFederate configuration failures in the Connect Sync wizard.

**Solution**: Upgrade to this version by April 7, 2025, to prevent any potential service interruptions.

**_Ref_**: [https://docs.azure.cn/en-us/entra/identity/hybrid/connect/harden-update-ad-fs-pingfederate](https://docs.azure.cn/en-us/entra/identity/hybrid/connect/harden-update-ad-fs-pingfederate)

### Mid-Apr 2025 - Intune Service Administrator Role will be Required for Device Limit Restrictions

Starting mid-April 2025, configuring device limit enrollment restrictions will require the 'Intune Service Administrator' RBAC permission.

**Solution:** Review and update your RBAC assignments as needed to maintain full control.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1034571](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1034571)

## May 2025 (Attention Needed: 13)

### Retirements

### Mid-May 2025 - Retirement of "Document Name Matches Patterns" Condition from Data Loss Prevention

The 'Document name matches patterns' condition helps detect documents where the file name matches specific patterns. Due to performance concerns, Microsoft will retire this condition from Purview Data Loss Prevention for Endpoint.

**Solution:** Use the 'Document name contains words or phrases' condition, where Microsoft will continue to invest development resources.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1042927](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1042927)

### Late-May 2025 - Complete Retirement of MSOnline PowerShell Module

The MSOnline PowerShell module will be completely retired late-May 2025.

**Solution:** Migrate to Graph PowerShell SDK as soon as possible.

**_Ref_**: [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/action-required-msonline-and-azuread-powershell-retirement---2025-info-and-resou/4364991)

### New Features

### May 2025 - New Insider Risk Management Reporting Capabilities

Insider Risk Management will introduce a centralized hub for all reports, including analytics and user activity reports. New reports will also be available, providing summaries of alert trends and case creation patterns.  

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=470027](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=470027)

### May 2025: OneDrive Sync Admin Reports for GCC

Microsoft will roll out OneDrive Sync Admin Reports in the Microsoft 365 admin center for GCC users by May 2025. These reports will help admins monitor sync client usage and errors across the organization.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=393333](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=393333)

### Early-May 2025 - New “Report a Security Concern” Feature in Microsoft Teams Admin Center

Microsoft 365 admin center is introducing a new setting, "Report a Security Concern." Admins can enable this feature to allow users to report security risks involving external users in one-on-one chats, group chats, and meeting chats.

**Note**: Shared channels are not supported at this time

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1037768](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1037768)

### Early-May 2025 - Automatically Display Automapped Calendars in Microsoft Outlook

Microsoft is encouraging users to switch to the new Outlook for Windows. To make the transition smoother, they have introduced an auto-mapping feature that ensures users can seamlessly access their automapped calendars when moving from classic Outlook to the new Outlook for Windows.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=415168](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=415168)

### Mid-May 2025 – New Filters in Microsoft Purview Audit Search

To help you retrieve relevant logs in the Microsoft Purview audit search, Microsoft will include four additional filters in general availability. They are,  

Id – Unique identifier of an audit record.

UserType – The type of user that performed the operation.

UserKey-Azure Active Directory Object ID in GUID format.

ClientIP – The IP address of the device that was used when the activity was logged.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC789312](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC789312)

### Mid -May 2025 - Third-party Add-in User Report can be Sent to Microsoft for Analysis

Admins using third-party add-ins for report message solutions can now configure Defender for Office 365 to automatically send user-reported messages to Microsoft for analysis.

Sending these messages to Microsoft for analysis not only provides valuable insights for security analysts but also improves the accuracy of Defender for Office 365 filters.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC962528](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC962528)

### Late-May 2025 - Org Explorer Feature for Enterprise Users

Starting late-May 2025, the Org Explorer feature will be available to all enterprise users using new Outlook for Windows, Outlook for Web, and Outlook for Mac. It provides insights into internal structures and connections.

**Note**: Switch to the new Outlook for Windows or Outlook for web to have early access to this new feature.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC939925](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC939925)

### Enhancements

### May 2025 - Add Shared Mailbox as Accounts in New Outlook for Windows

Starting May 2025, you’ll be able to add shared mailboxes as accounts in the New Outlook for Windows. With the necessary permissions, you can access these shared mailboxes by providing the user’s credentials.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=375635](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=375635)

### May 2025 - Multi-policy Selection in Adaptive Protection of IRM

In Insider Risk Management, the "Risk levels for Adaptive Protection" setting lets admins assign risk levels to configured policies. Previously, admins could apply risk levels to only one policy at a time. With this update, they can now select multiple policies at once, making it easier to manage risk levels in Adaptive Protection.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=171735](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=171735)

### Existing Functionality Changes

### Early-May 2025 – Data Lifecycle Management: Separate Copilot Retention Policies from Teams Chats

Currently, Teams chat and Copilot interactions share the same Purview Data Lifecycle Management policy. After the update, admins can create separate retention policies for Copilot interactions, managing them independently from Teams chat. This feature will be rolled out to public preview by early-May 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC926899](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC926899)

### Action Required

### May 31, 2025 - Microsoft Viva Engage: External Networks are Being Modernized

Microsoft Viva Engage will modernize External Networks. So, legacy external networks will be retired starting June 1, 2025.

**Solution:** Admins must migrate to the new platform before May 31, 2025, to avoid data loss.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1036575](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1036575)

## June 2025 (Attention Needed: 10)

### June 2025 - Message Recall Feature for Outlook for Mac

The Cloud-based Exchange Online Message Recall feature will soon be available for Outlook for Mac users, with a preview rollout scheduled for June 2025.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=189804](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=189804)

### June 2025 - Bulk Data Export for OneDrive Sync Admin Reports

Admins will soon be able to export OneDrive sync data in bulk via Microsoft Graph Data Connect. This includes device status, usernames, sync app versions, known folders, last sync dates, and sync errors.  

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC844917](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC844917)

### June 2025 - Just in Time Protection on SharePoint in DLP

Microsoft is introducing Just-in-Time protection for SharePoint in Microsoft Purview Data Loss Prevention.

With this feature, organizations can automatically apply DLP restrictions to unclassified files when they are accessed or shared externally. Instead of restricting files in advance, JIT protection enforces security measures only when there is a risk of data leaving the organization.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457)

### June 2025: Block Specific Folders from OneDrive Sync

Starting June 2025, admins can block not just files or extensions but also specific folders from syncing with OneDrive through Group Policy.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=178292](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=178292)

### June 2025 - Date Lifecycle Management and Power Automate Integration in U.S Government Clouds

U.S. government cloud users can automate actions on items at the end of their retention period using Power Automate by June 2025.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=117523](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=117523)

### Mid-June 2025 - Insider Risk Management- Risky AI Usage

New detections in Insider Risk Management will be generally available, enabling admins to identify risky AI activity, such as sensitive prompts, risky intents, and AI-generated sensitive content. This applies to M365 Copilot, Copilot Studio, and ChatGPT Enterprise, contributing to Adaptive Protection risk levels.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC947048](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC947048)

### Late-June 2025 - Availability of Microsoft Loop Admin Usage Reports

Admins can be able to monitor Loop usage through existing Microsoft 365 admin dashboards, starting mid-June 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC929020](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC929020)

### Late - June 2025 - Search-MailboxAuditLog and New-MailboxAuditLogSearch Cmdlets Will Become Static

Microsoft plans to deprecate the Search-MailboxAuditLog and New-MailboxAuditLogSearch cmdlets. However, admins can continue to access the old logs and download data using these cmdlets until late June 2025. After that, the cmdlets will become read-only, and no further changes or downloads will be possible.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310](https://techcommunity.microsoft.com/blog/microsoft-security-blog/microsoft-exchange-online-search-mailboxauditlog-and-new-mailboxauditlogsearch-w/4366310)

### Late-June 2025 – IRM Alerts in Microsoft Defender XDR

Microsoft Purview’s Insider Risk Management (IRM) data will integrate with Microsoft Defender XDR, enabling comprehensive investigation and correlation. IRM data will be accessible through the unified alert and incident queue, advanced hunting with KQL queries, Graph API, and Microsoft Sentinel. This feature will roll out to general availability by mid-June 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC961761](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC961761)

### Late - June 2025 – Decoupling of Policy Tips and Email Notifications for SharePoint and OneDrive

Currently, enabling email notifications for a DLP policy also requires enabling the policy tips, and vice versa. However, Microsoft will soon allow admins to configure email notifications and policy tips independently for SharePoint and OneDrive DLP policies. This update will be rolled out to Public preview by late June 2025.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=394279](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=394279)

### June 30, 2025 - Retirement of Private Content Mode in Via Engage

Microsoft Viva Engage will retire the "Private Content Mode" by June 30, 2025. After this date, verified admins will no longer be able to enable or disable this feature.

**Solution:**

The following alternatives will be available:

*   Admins can join private communities without approval: Global or Groups Administrators can now access private communities directly, with no approval needed.
*   Group members and owners visible in Entra ID: All users can see group members and owners in Entra ID, even without being part of the community.
*   eDiscovery admins can access private content: Compliance and eDiscovery admins can search and export private content for legal or audit purposes.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1045211](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1045211)

## Q3 2025 (Attention Needed: 8)

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

### Late-Sep 2025 - New Secure Workflow to Bypass Legal Holds and Retention Policies in Microsoft Purview

Admins will have the ability to permanently delete sensitive Exchange mailbox content, bypassing retention policies and eDiscovery holds. This will be possible through the “Priority Cleanup Administrator” role, which grants authorized users’ permission to initiate Priority Cleanup for Exchange, allowing exceptions to standard retention and legal hold policies.

Since this process is irreversible and overrides existing policies, Microsoft has built-in approvals and special auditing for security.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC971035](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC971035)

### Sep 30, 2025 – Retirement of Managing Authentication Methods in Legacy MFA &SSPR Policy

Starting Oct 2025, Microsoft no longer allow authentication methods to be managed in the legacy MFA and SSPR policies.

**Solution:** Organizations should use the converged authentication methods policy where methods can be managed centrally for all authentication scenarios including passwordless, MFA and SSPR.

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448)

## Q4 2025 (Attention Needed: 7)

### Oct 2025- External Recipient Rate Limit in Exchange Online

Exchange Online will begin enforcing an external recipient rate (ERR) limit of 2000 recipients in 24 hours. This restriction will be applicable to the cloud-hosted mailboxes of all newly created tenants.

**Note:** Exchange Online enforces a Recipient Rate limit of 10000 recipients for cloud-hosted mailboxes. The 2000 ERR limit will become a sublimit within this 10000 Recipient Rate limit.

**_Ref:_** [https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733](https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733)

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

## 2026 (Attention Needed: 13)

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