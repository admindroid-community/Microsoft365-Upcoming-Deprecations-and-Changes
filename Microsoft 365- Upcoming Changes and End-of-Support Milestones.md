# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.

Discover the **key changes, deprecations,** and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

Here is a list of changes categorized by month and year.

 

- Mar 2024 (Most Expected Feature: 1, In the Spotlight: 2, New Features: 4, Retirements: 7, Enhancements: 2, Existing Feature Change: 1 )

- Apr 2024 (Attention needed: 6)

- May 2024 (Attention needed: 1)

- June 2024 (Attention needed: 3)

- Q3-2024 (Attention needed: 4)

- Q4-2024 (Attention needed: 6)

- 2025 (Attention needed: 5)

- 2026 (Attention needed: 7)






## **March 2024**
Most Expected Feature: 1 \| In the Spotlight: 2 \| New Features: 4 \| Retirements: 7 \| Enhancements: 2 \| Existing Feature Change: 1

## **Most Expected Feature:** 

### 'View Another Mailbox' in the New Exchange Admin Center

Microsoft has introduced the highly anticipated \"**view another
mailbox**\" capability in the new Exchange admin center, enabling
administrators to manage all mailboxes seamlessly.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC720777>

## **In the Spotlight:**

### Microsoft Entra License Utilization Insights

The Entra ID License utilization portal provides insights into your
Entra ID P1 and P2 license counts and usage metrics for their
corresponding key features. Currently, it includes Conditional Access
and risk-based Conditional Access usage in public preview.

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-entra-blog/introducing-microsoft-entra-license-utilization-insights/ba-p/3796393>

### Prompt Users for Reauthentication on Sensitive Apps and High-risk Actions with Conditional Access

Microsoft has expanded support for Conditional Access reauthentication
policies. This enables users to interactively provide their credentials
again before accessing critical apps or performing sensitive actions.

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-entra-blog/prompt-users-for-reauthentication-on-sensitive-apps-and-high/ba-p/4062703>

## **New Features:**

### Mar 2024- 19 Premium Audit Logs are Available for Standard Users

To improve cloud security Microsoft provides 19 Microsoft Purview
Premium audit logs to standard users. It includes Exchange, SharePoint,
and Teams events.

Here are the new standard logs:

**Exchange:** Send, MailItemsAccessed, SearchQueryInitiatedExchange

**SharePoint:** SearchQueryInitiatedSharepoint

**Teams:** MeetingParticipantDetail, MessageSent, MessagesListed,
MeetingDetail, MessageUpdated, ChatRetrieved, MessageRead,
MessageHostedContentRead, SubscribedtoMessages,
MessageHostedContentsListed, ChatCreated, ChatUpdated,
MessageCreatedNotification, MessageDeletedNotification,
MessageUpdatedNotification.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC711333>

### Mar 2024- Microsoft Purview: Audit Search Graph API

Microsoft Purview introduces a new Audit Log Query API, allowing admins
to programmatically retrieve their organization\'s Audit activity logs.
To access this API, admins must register their application with
Microsoft Graph and add the necessary Graph permissions.

***Ref:***
<https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=117587>

### Mar 2024- OneDrive: Sync Admin Reports

Microsoft has introduced support for bulk export of device status,
encompassing username, sync app version, known folders, last sync date,
and sync errors. The rollout begins in March 2024.

***Ref:***
<https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=In%20development&searchterms=88870>

### Mid-Mar 2024- Microsoft Purview: Restrict unintentional sharing (macOS)

The new settings in the Microsoft Purview compliance portal will
restrict users from unintentionally sharing sensitive items with
unallowed cloud apps and monitor sensitive activities in macOS
environments.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC720178>

### Mid-March 2024- Microsoft Teams: Archive Channels

Microsoft Teams introduces the ability for channel owners and
administrators to archive channels for paused or completed projects.
Archiving a channel removes it from the teams and channels list,
preventing any actions on it.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC696576>

## **Retirements**

### Mar 2024- Exchange PowerShell: Retirement of Get, Set, and Remove UserPhotos Cmdlets 

Microsoft is phasing out the Exchange PowerShell cmdlets used by tenant
administrators to manage user profile photos, including commands like:
*Get-UserPhoto*, *Set-UserPhoto*, and *Remove-UserPhoto*.

**Solution**: As an alternative admins can utilize MS Graph PowerShell
or Microsoft 365 admin center to manage user photos.

**Ref:**
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC678855>

### Mar 2024: Microsoft 365 Apps: Retirement of Microsoft Office Online Services Translator in the Research Pane

Following the retirement, users will no longer have the capability to
perform translations in the Research pane using the Microsoft Office
Online Services translator. Instead, they will encounter a \"The service
did not respond\" error.

**Solution:** Microsoft recommends using either Microsoft Translator in
the Research pane, or the new modern translation pane.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC709263>

### Mar 2024 -- Custom Script Settings Removal from OneDrive and SharePoint Web

The Custom Script setting in OneDrive and SharePoint web will be removed
in March 2024. After that, users cannot change the look, feel, and
behavior of sites and pages to meet their organizational objectives or
individual needs.

**Proactive step:** A new PowerShell command property
*DelayDenyAddAndCustomizePagesEnforcement*, has been introduced to delay
the change to custom script set on the Tenant until May 2024.

Set-SPOTenant DelayDenyAddAndCustomizePagesEnforcement \$True

**Note:** This property is available in the SharePoint Online Management
Shell version 16.0.24524.12000, or above.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC714186>

### Mar 01, 2024 - Retirement of Search-Mailbox Cmdlet

The *Search-Mailbox* cmdlet is useful for searching and exporting
mailbox data for legal and compliance purposes. After the deprecation
date, the *Search-Mailbox* cmdlet will no longer be supported.

**Solution**: You can use the alternative cmdlet *New-ComplianceSearch*
for this purpose.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC703706>

### Mar 15, 2024 -- Retirement of few Properties in Get-CsOnlineUser and Get-CsUserPolicyAssignment Cmdlets

Microsoft retiring LocationPolicy, OptionFlags and VoicePolicy
attributes from Get-CsOnlineUser and Get-CsUserPolicyAssignment cmdlets
in the Teams PowerShell Module version 6.1.0 (planned to be released on
15th March 2024) and any later versions.

**Solution:** Administrators can utilize Get-CsPhoneNumberAssignment
-IsoCountryCode to get the LocationPolicy information.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC720181>

### Mar 30, 2024 -- Azure AD Graph Retirement and PowerShell Module Deprecation 

Microsoft has postponed the deprecation date for MS Online, AzureAD, and
AzureAD Preview PowerShell modules to March 30, 2024.

**Solution:** Before the deprecation date, you can migrate your existing
scripts to MS Graph.

***Ref***:
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/important-azure-ad-graph-retirement-and-powershell-module/ba-p/3848270>

### Mar 31, 2024- Classic Teams Users Will be Automatically Updated to New Teams 

Classic Teams users will be automatically updated to the new Teams
client after March 31st 2024. If you are still using Teams classic by
that date. New Teams is up to 2x faster and use 50% less memory. There
is no major impact to the user experience for new Teams.

**Tip:** You can deploy the new Teams client in your organization by
updating Teams Update policy in Microsoft Teams admin center.

***Ref***:
<https://learn.microsoft.com/en-us/MicrosoftTeams/new-teams-automatic-upgrade-announced>

## **Enhancements**

### Mid-Mar 2024- Microsoft 365 Admin Center: Usage Reports - Redesign

The Overview page of the Microsoft 365 admin center Usage report has
been revamped for improved accessibility to vital usage insights. This
redesign introduces fresh engagement metrics such as enabled and active
users, user state breakdowns (e.g., new vs. returning users), storage
distribution across products, and critical usage statistics for
Microsoft 365 offerings.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC692467>

### Mar 2024- The New RBAC Role for Managing Telephony-related Functions

The Microsoft Teams Admin Center is introducing a new RBAC role known as
the Teams Telephony Admin. This role is tailored for managing
telephony-related functions, offering standalone management capabilities
for telephony areas. Key functionalities include user management, voice
management, and analytics and reporting.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC715426>

## **Existing Feature Change**

### Mar 2024- Removing a Recommendation from Secure Score

Microsoft plans to remove the Secure Score recommendation \"*Remove the
attribute \'password never expires\' from accounts in your domain*\"
from Microsoft Defender for Identity

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC722587>

## April 2024

## **Retirements**

### Apr 02, 2024- SharePoint 2013 Workflow Retirement 

Starting April 2nd, 2024, SharePoint 2013 workflows will be turned off
for newly created tenants. Starting April 2nd, 2026, SharePoint 2013
workflows will no longer be supported for existing tenants.

**Solution:** You can move to Power Automate or other supported
solutions.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC542767>

### Apr 11, 2024- Retirement for the Azure Information Protection Unified Labeling Add-in for Office 

The AIP Unified Labeling add-in for Office will reach end of
availability and support of the service.

**Solution:** You can use sensitivity labeling directly into Office
apps.

***Ref:***
<https://techcommunity.microsoft.com/t5/security-compliance-and-identity/retirement-notification-for-the-azure-information-protection/ba-p/3791908>

### Apr 15, 2024- Stream (Classic) is Fully Retired & Automatically Disabled. 

Users & admins are no longer able to access or use Stream (Classic). Any
remaining content in Stream (Classic) that wasn't migrated will be
deleted.

**Solution:** You can use Stream on SharePoint.

***Ref***:
<https://techcommunity.microsoft.com/t5/microsoft-stream-blog/update-on-stream-classic-retirement-last-day-of-service-set-for/ba-p/3712075>

### Apr 30,2024- Retirement of AdminAuditLog and MailboxAuditLog cmdlets

Microsoft retiring the following Exchange Online PowerShell cmdlets from
Apr 30, 2024.

1.  Search-AdminAuditLog

2.  Search-MailboxAuditLog

3.  New-AdminAuditLogSearch

4.  New-MailboxAuditLogSearch

**Solution:** You can utilize the Search-UnifiedAuditLog cmdlet or the Microsoft Purview portal to access your audit logs.

***Ref:***
<https://techcommunity.microsoft.com/t5/security-compliance-and-identity/important-announcement-deprecation-of-adminauditlog-and/ba-p/4036537>

### Apr 30, 2024- Privileged Access Management (PAM) for Microsoft Graph Data Connect (MGDC) Retirement

Microsoft will retire Privileged Access Management (PAM) for Microsoft
Graph Data Connect (MGDC) on April 30, 2024.

**Solution:** To adapt, all tenants must utilize the new MGDC onboarding
experience post this date.

Migration to the new interface can be accomplished through a one-click
process in MGDC settings or automatic migration during pipeline runs
until April 30, 2024. MGDC will seamlessly convert approved PAM requests
into app registrations. Failure to migrate by April 30, 2024, will
necessitate manual onboarding for pipelines.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC715688>

## Existing Functionality Change

### Apr 2024: View Websites in New Teams Client

Beginning in April 2024, Microsoft Teams will no longer support loading
websites within the new Teams client when using the Website tab.
Instead, the Website tab will open in a new browser tab.

**Note:** This update won't affect EDU customers.

***Ref:***
<https://devblogs.microsoft.com/microsoft365dev/upcoming-updates-to-loading-websites-in-teams-tabs/>

## May 2024

### May 2024 -- Contact De-duplication Feature in OWA 

Maintaining a clean, updated contact list is crucial for enhanced
collaboration and productivity. Microsoft introducing a new feature to
cleaning up duplicate contacts with the de-duplication feature in
Outlook Web App (OWA)

***Ref***:
<https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=In%20development&searchterms=98124>

### May 2024- Retirement of the ApplicationImpersonation Role Based Access Control (RBAC) Role in Exchange Online. 

Starting May 2024, Microsoft will block the assignment of the
ApplicationImpersonation role in Exchange Online to accounts.

**Solution:** To comply with these upcoming changes, apps must undergo
an App Registration, utilize Application permissions (not Delegated),
and implement secure credentials for access.

***Ref:***
<https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-rbac-application-impersonation-in-exchange-online/ba-p/4062671>



### May 1, 2024: Azure Information Protection Add-in for Office Retirement

From May 1st, 2024, AIP Unified Labeling add-in permanently disabled in
Office.

**Solution:** If you are using AIP Add-in for Office, you can use
<playbook>(https://microsoft.github.io/ComplianceCxE/playbooks/AIP2MIPPlaybook/)
to plan and execute the transition to built-in labeling in Office apps.

***Ref:***
<https://techcommunity.microsoft.com/t5/security-compliance-and-identity/retirement-notification-for-the-azure-information-protection/ba-p/3791908>

### Mid-May 2024- Retirement of Entity-based Contextual Outlook Add-ins

After retirement, contextual add-ins won\'t detect entities in mail
items to perform tasks. Support for Microsoft add-ins reliant on this,
like Bing Maps, Action Items, and Suggested Meetings, will be
discontinued.

**Solution:** You can configure add-in with regular expression rules as
an alternative solution.

***Ref:***
<https://devblogs.microsoft.com/microsoft365dev/retirement-of-entity-based-contextual-outlook-add-ins/>

## June 2024

### June 2024- Microsoft Teams: Workspace Management 

Workspace management offers a unified perspective of Teams devices and
peripherals, categorized by location, accompanied by insightful details.
IT admins can now efficiently oversee connected devices, monitor
workspace health, assess utilization, and ensure adherence to standards
across all locations.

***Ref***:
<https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=In%20development&searchterms=88326>

### June 2024- Microsoft Teams: Loop components in Teams Chat for GCC 

In Teams chat, loop components empower users to send messages containing
tables, action items, or lists that everyone in the conversation can
collaborate on and edit together

***Ref***:
<https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=In%20development&searchterms=93163>

### June 30, 2024- Retirement of Classic Teams for VDI 

Classic Teams for VDI (Virtualized Desktop Infrastructure) will no
longer be available after June 30th, 2024. Users will be prompted to
transition to the new Teams interface post this date.

***Ref:***
<https://learn.microsoft.com/en-us/MicrosoftTeams/new-teams-vdi-requirements-deploy>

## July 2024

### July 01 - SharePoint Add-in Retirement 

As part of SharePoint add-in retirement, starting July 01, 2024, you
can't install them from public marketplace. SharePoint Add-Ins will stop
working for new tenants as of November 1, 2024, and they will be fully
retired as of April 2nd, 2026.

**Solution**: Admins can run the Microsoft 365 Assessment
tool to scan their
tenants for SharePoint Add-In usage.

***Ref***:
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865>

## August 2024

### Aug 30, 2024 -- Intune Ending Support for Android Device Administrator on GMS Access Devices

After Intune ends support for Android device administrator, devices with
access to GMS will be impacted in the following ways:

1.  Users will not be able to enroll devices with Android device
    administrator.

2.  Intune technical support will no longer support these devices.

***Ref***:
<https://techcommunity.microsoft.com/t5/intune-customer-success/microsoft-intune-ending-support-for-android-device-administrator/ba-p/3915443>

## September 2024

### Sep 30, 2024- Azure Multi-Factor Authentication Server 

Azure MFA Server deployments will no longer service MFA requests, which
could cause authentications to fail for your organization.

**Solution:** Organizations should migrate their users' authentication
data to the cloud-based Azure MFA service

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-september-2022-train/ba-p/2967454>

### **Sep 30, 2024 -- Business Connectivity Services Retirement in Microsoft 365** 

Microsoft will retire Business Connectivity Services features in
Microsoft 365.

**Solution**: Microsoft recommends using Power Apps to replace their
Business Connectivity Services solutions in SharePoint in Microsoft 365.

***Ref***:
<https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-business-connectivity-services-in-microsoft/ba-p/3938773>

## **October 2024**

### **Oct 14, 2024 -- Office 2016 End of Support** 

After Office 2016 reaches its end of support, Microsoft no longer
provides technical support, bug fixes, and security fixes for
vulnerabilities that are discovered

**Solution**: Microsoft recommend upgrading to Microsoft 365 E3, which
comes with Microsoft 365 Apps.

***Ref***:
<https://learn.microsoft.com/en-us/deployoffice/endofsupport/plan-upgrade-older-versions-office>

## **November 2024**

### **Nov 01, 2024- Azure ACS Retirement in Microsoft 365** 

Microsoft is retiring the use of Azure ACS as auth platform for
SharePoint Online. Starting November 1st, 2024, new tenants will not be
able use Azure ACS. For existing tenants that currently rely on Azure
ACS to provide custom-developed or third-party applications access to
SharePoint Online, this functionality will cease to work after April 2,
2026.

**Solution**: Admins can utilize the Microsoft 365 Assessment tool to
scan the tenants for any usage of Azure Access Control Service (ACS) and
migrating from Azure ACS to Microsoft Entra ID.

***Ref***:
<https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/retirement-announcement-for-azure-acs>

### **Nov 01, 2024- SharePoint Add-in Retirement** 

SharePoint Add-Ins will stop working for new tenants as of November 1,
2024, and they will be fully retired as of April 2nd, 2026.

**Solution**: Admins can run the Microsoft 365 Assessment
tool to scan their
tenants for SharePoint Add-In usage.

***Ref***:
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865>

## **December 2024**

### **Dec 16, 2024 -- Delve Web Retirement** 

Microsoft retiring Delve on December 16th, 2024. Many Delve features are
now available and improved in other Microsoft 365 experiences.

**Solution:** Key alternatives include:

-   Discover documents: Use Office.com, Office apps, and Profile Cards.

-   View profile data: Utilize Profile Cards, people search on
    Office.com, and SharePoint search.

-   Edit profile: A new edit profile experience will be released in H2
    2024 and can also be edited in SharePoint.

-   Organizational view: Available in the Profile Card and Org Explorer.

-   Favorites: Use favorites on Office.com and OneDrive for similar
    functionality.

-   Boards: Will not be replaced.

***Ref***:
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC698136>

### **Dec 31, 2024- Microsoft Teams Live Event Retirement** 

As part of MS Teams live event retirement (planned on Sep 30, 2024),
existing recordings will be accessible till Dec 31, 2024. If you want to
keep the recording, download and upload them to a different location
before December 31.

**Solution**: You can start to use town halls.

***Ref***:
<https://admin.microsoft.com/adminportal/home?ref=MessageCenter/:/messages/MC678003>

### **End of 2024- Retirement of Mail and Calendar Apps in Windows** 

At the end of 2024, Microsoft replacing the Mail and Calendar apps in
Windows with the new Outlook for Windows.

**Solution:** Start trying and testing the new Outlook for Windows.

***Ref***:
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC590123>


## **2025 (Attention Needed: 3)** 

### Feb 2025- Removal of the ApplicationImpersonation Role Based Access Control (RBAC) role in Exchange Online. 

Microsoft is going to remove ApplicationImpersonation Role Based Access
Control (RBAC) role and its feature set from Exchange Online.

***Ref:***
<https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-rbac-application-impersonation-in-exchange-online/ba-p/4062671>

### **Feb 01, 2025- Azure Key Vault: Soft-delete Will be Enabled on All Key Vaults** 

Soft Delete preserves deleted key vaults and secrets for up to 90 days,
enabling customers to restore them through a self-serve process.

***Ref:***
<https://learn.microsoft.com/en-us/azure/key-vault/general/soft-delete-change>

### **Feb 22, 2025- Viva Topics Retirement**

Viva Topics will be discontinued on February 22, 2025, and Microsoft
will no longer pursue new feature enhancements for the platform.

Existing Topic pages will transition to standard SharePoint pages. Users
can edit and publish updates as other SharePoint pages. AI-generated
Topic pages will no longer be accessible.

***Ref:***
<https://learn.microsoft.com/en-us/microsoft-365/topics/changes-coming-to-topics>

### **Sep 30, 2025- Retirement of Managing Authentication Methods in Legacy MFA & SSPR Policy** 

Starting Oct 2025, Microsoft no longer allow authentication methods to
be managed in the legacy MFA and SSPR policies.

**Solution:** Organizations should use the converged authentication
methods policy where methods can be managed centrally for all
authentication scenarios including passwordless, MFA and SSPR.

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448>

### **Oct 14, 2025- End of Extended Support for Office 2016 & Office 2019** 

Office 2016 and Office 2019 extended support ends in 2025.

**Solution:** You can start to use the latest supported versions.

***Ref:***
<https://learn.microsoft.com/en-us/lifecycle/products/microsoft-office-2016>

## **2026 (Attention Needed: 6)** 

### **Jan 13, 2026- End of Extended Support for Microsoft Advanced Threat Analytics 1.x** 

Microsoft Advanced Threat Analytics (ATA) extended support will be ended
on January 13, 2026.

**Solution**: Updates for Microsoft ATA are available from Microsoft
Update or by manual download.

***Ref:***
<https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c>

### **Mar 31, 2026- Deprecation of 'Require Approved Client App' Conditional Access Grant** 

The Require approved client app control in Azure Active Directory (Azure
AD) Conditional Access will be retired and no longer enforced.

**Solution:** You can make use of the "Require app protection policy"
control, which has all the same capabilities

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448>

### **Apr 02, 2026- SharePoint 2013 Workflow Retirement** 

SharePoint 2013 workflows will no longer be supported.

**Solution:** You can move to Power Automate or other supported
solutions.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC542767>

### **July 14, 2026- InfoPath 2013 Client and InfoPath Forms Services in SharePoint Online will be Retired** 

InfoPath Client 2013 will reach the end of its extended support period
on July 14, 2026, and to keep an aligned experience across Microsoft
products, InfoPath Forms Service will be retired from SharePoint Online.

**Solution:** To understand the usage of InfoPath within your
organization, you can utilize the <<Microsoft 365 Assessment
tool>{.underline}>(https://aka.ms/assessment/infopath) to scan your
tenant and analyze InfoPath usage. If you are currently using InfoPath,
you can initiate the migration process to modern alternatives such as
Power Apps, Power Automate, or Forms.

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190>

### **Oct 01, 2026- Retirement of Exchange Web Services in Exchange Online** 

October 1, 2026, Microsoft will start blocking EWS requests from
non-Microsoft apps to Exchange Online. The changes in Exchange Online do
not affect Outlook for Windows or Mac, Teams, or any other Microsoft
product.

**Solution**: Migrate your applications to Microsoft Graph to access
Exchange Online data and gain access to the latest features and
functionality.

***Ref***:
<https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-exchange-web-services-in-exchange-online/ba-p/3924440>

### **Oct 01, 2026- Sign-in Risk Policy and User Risk Policy Retirement from Entra ID Protection** 

User risk policy or Sign-in risk policy UX in Entra ID Protection
(formerly Identity Protection) will be retired on October 1, 2026.

**Solution:** Migrate Sign-in risk and User risk policies to Conditional
Access.

***Ref***:
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/what-s-new-in-microsoft-entra/ba-p/3796395)>

### Oct 13, 2026- Retirement of Microsoft Publisher

In October 2026, Microsoft will discontinue Publisher in Microsoft 365,
with on-premises suite support ending. While support lasts, they\'re
exploring modern alternatives across Word, PowerPoint, and Designer for
common Publisher tasks, with updates forthcoming.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC716267>


In conclusion, navigating the ever-evolving landscape of Microsoft 365 requires staying informed about the changes. By proactively adapting to these changes, you can optimize your Microsoft 365 experience, maximize productivity, and effectively plan for the future. 

We are committed to keeping this blog updated with the latest information, so stay tuned for upcoming updates.
### Blog link: https://blog.admindroid.com/microsoft-365-end-of-support-milestones
