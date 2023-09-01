# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.

Discover the **key changes, deprecations,** and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

Here is a list of changes categorized by month and year.


- Sept 2023 (New features: 3, Retirements: 7, Retirement Postponed: 1, Enhancement: 1, Action Required: 1)

- Oct 2023 (New Features: 1, Retirements: 4)

- Nov 2023 (Major update: 1; Retirement: 1)

- Dec 2023 (Deprecation: 1)

- 2024 (Attention needed: 8)

- 2025 (Attention needed: 2)

- 2026 (Attention needed: 4)

##Top Of The List:

### Multi-tenant Organization (MTO) capabilities in Azure AD 

This is one of the most awaited features from Microsoft. The Multi-tenant Organization (MTO) feature allows admins to create a tenant group within their organization. It can connect up to five tenants through cross-tenant access policies to enable smooth directory synchronization. 

MTO is particularly useful for organizations that maintain multiple Azure AD tenants, offering a streamlined approach to account management, especially in the context of mergers and acquisitions. 

***Ref***: 
<https://learn.microsoft.com/en-us/azure/active-directory/multi-tenant-organizations/multi-tenant-organization-overview>

## Private Preview:

### Microsoft Entra ID: Platform SSO for macOS

Platform SSO is an advancement of the current SSO Extension functionalities designed for macOS. It grants users the ability to access their Macs without entering traditional passwords. Instead, they can use passwordless login or synchronize their local credentials with their Entra ID credentials.

***Ref***: 
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/coming-soon-platform-sso-for-macos/ba-p/3902280>


## Sep 2023

Most Celebrated Update: 1 \| New features: 3 \| Retirements: 7 \| Retirement Postponed: 1 \| Enhancement: 1 \| Action Needed: 1

## Most Celebrated Update:

### Sep 2023- Default Microsoft 365 Audit Logging Retention Period Doubled

Starting from September 2023, the Microsoft Purview Audit supports expanded logging capabilities for standard customers at no additional cost. It includes, 

The extension of the default audit log retention period from 90 to 180 days for standard customers. . 

30+ new activities, such as Mail Item Accessed, Teams message read, Teams chat created, etc., have been added to the audit log, which were previously exclusive to the Microsoft Purview Audit (Premium) subscription.

***Ref***:  
<https://www.microsoft.com/en-us/security/blog/2023/07/19/expanding-cloud-logging-to-give-customers-deeper-security-visibility>


## New Feature: 

### Early-Sep 2023- Discover and Co-author Documents Labeled with User-defined Permissions.

SharePoint and OneDrive will support discovery and coauthoring of files
labeled with user-defined permissions. These files can be easily
accessed, edited, co-authored, and benefit from the AutoSave feature in
Word, Excel, and PowerPoint apps across all platforms.

***Ref***:
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC617055>

### Sep 2023 - Entra ID MFA Supports Text Message Delivery through Whatsapp

Starting September 2023, users in a specific regions like India,
Indonesia and New Zealand may start receiving multifactor authentication
(MFA) text messages via WhatsApp. Only users that are enabled to receive
MFA text messages and already have WhatsApp on their phone will get this
experience.

Note: Entra ID will expand this feature to other countries in Oct-Nov
2023.

**Solution:** If you do not want your users to get OTP through Whatsapp,
you need to disable text message as authentication in your organization.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC666628>

### Sept 15, 2023- Microsoft Graph to Support HTTP/2

Microsoft Graph service (graph.microsoft.com) will enable HTTP version 2
(HTTP/2) in addition to HTTP/1.1. for API requests

***Ref***:
https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC447341

## Retirements:

### Sep 01, 2023- Retirement of Get-ATPTotalTrafficReport Cmdlet

Microsoft retiring the *Get-ATPTotalTrafficReport* cmdlet from Microsoft
Defender for Office 365 beginning September 1st, 2023.

**Solution:** Instead of *Get-ATPTotalTrafficReport* cmdlet, you can use
the Get-*MailTrafficATPReport,* *Get-MailDetailATPReport*, and
*Get-Mailflowstatusreport*.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC588322>

### Sep 11, 2023 - Microsoft 365 connectors will no longer work on Viva Engage communities. From September 11, 2023, adding Microsoft 365 Apps to Yammer/Viva Engage communities via Microsoft 365 connectors will no longer be supported. Solution: If you are using a Microsoft 365 connector on a community, consider replacing your connector usage with the following:

-   Viva Engage [connectors in Power
    Automate](https://learn.microsoft.com/en-us/connectors/yammer/),
    which are configured outside of the community

-   Custom code using the [Viva Engage (Yammer) REST
    API](https://learn.microsoft.com/en-us/rest/api/yammer/rest-api-rate-limits)

***Ref:***
<https://support.microsoft.com/en-us/office/add-apps-to-viva-engage-bbb77f10-8779-4f3d-8096-db256f8653b8>

### Mid Sep 2023 -- Twitter Web Part Retirement

Due to a change in Twitter's terms of use for third-party access, the
Twitter web part in SharePoint in Microsoft 365 will no longer be
supported. Users may see error messages in pages that have Twitter web
part.

Solution: SharePoint administrators can remove the Twitter web part from
their SharePoint pages via the page authoring.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC662249>


### Sep 15, 2023- Disable Video Upload to Stream (Classic)

As part of Classic Stream retirement, you can't upload video to Stream
(Classic)

**Solution:** You can start to use Stream in SharePoint

***Ref:***
<https://learn.microsoft.com/en-us/stream/streamnew/stream-classic-to-new-migration-overview#upcoming>


### Sep 15, 2023- Ending Support for Microsoft Store for Business and Education Apps 

Microsoft Store for Business and Education apps will be removed from the
Intune admin center.

**Solution:** Add your apps through the new Microsoft Store app
experience in Intune.

***Ref***:
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC553242>

### Sep 30, 2023- Azure Automation Run as Accounts Retirement

All runbook executions using Run As accounts, including Classic Run As
accounts would not be supported after this date.

**Solution:** If you have existing Azure Automation runbooks using Run
As accounts, migrate them to Managed identities.

***Ref:***
<https://techcommunity.microsoft.com/t5/azure-governance-and-management/azure-automation-run-as-accounts-retiring-on-30-september-2023/ba-p/3744308>

### Sep 30, 2023- Deprecation of Client Access Rules (CAR) in Exchange Online 

Microsoft retiring CARs that provide granular access control based on
client properties such as IP addresses, protocol, or application.

**Solution:** Migrate CARs to Continuous Access Evaluation (CAE)

***Ref:***
<https://techcommunity.microsoft.com/t5/exchange-team-blog/update-deprecation-of-client-access-rules-in-exchange-online/ba-p/3790165>

## Retirement Postponed:

### Retirement of Stream Live Events Postponed to Jan 30, 2024

To provide ample time for organizations to implement Teams live events
with encoder support, Microsoft has postponed the retirement of Stream
live events from September 15, 2023, to January 30, 2024.

***Ref:***
<https://learn.microsoft.com/en-us/stream/streamnew/stream-classic-to-new-migration-overview#upcoming>

## Enhancement:

# Mid Sep - Microsoft Authenticator Lite (for Outlook) Support in Legacy, Per-user MFA Policy

For organizations using the legacy per-user MFA policy and having
\"Notification through mobile app\" enabled, users without the Microsoft
Authenticator app can see the option to set up \"Microsoft Authenticator
Lite\".

**Solution:** If your organization doesn\'t want to use Microsoft
Authenticator Lite,you can disable Authenticator Lite using the steps
given in the [MS
doc](https://learn.microsoft.com/en-us/azure/active-directory/authentication/how-to-mfa-authenticator-lite#disabling-authenticator-lite-in-azure-portal-ux).

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC664476>

## Action Required

### Sep 29, New PowerBI Admin Setting To be Turned ON by Default

The new setting \"*Users can view Power BI files saved in OneDrive and
SharePoint (Preview) - UPDATE*\" allows users to view Power BI reports
stored in OneDrive and SharePoint directly in their browsers. It will be
ON by default starting in early October unless you take action before
September 29th, 2023.

**Solution:** If you do not want users in your tenant to view Power BI
reports stored in OneDrive and SharePoint, turn off the settings from
admin portal **before September 29th, 2023**.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC666631>

## Oct 2023

New Feature: 1, Retirements: 4

##  New Feature

### Mid-Oct 2023, Meet App in Microsoft Teams

The Meet app serves as a centralized hub for all meeting activities and
content. It allows users to prepare for upcoming meetings, catch up on
missed content, and access meeting-related materials like agendas,
notes, chats, and recaps, all conveniently in one place.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC660610>

## Retirements

### Oct 2023- Classic Search in Purview Portal Retirement

From October 2023, Classic Search available in the Microsoft Purview
portal will be retired.\
Solution: Admins are encouraged to utilize the \"New search\" feature,
which offers faster search times, additional search options, the ability
to save searches, and more functionalities.

***Ref:*** <https://learn.microsoft.com/en-us/purview/audit-log-search>

### Oct 2023- Deprecation of Remote PowerShell (RPS) Protocol in Exchange Online PowerShell.

MS will block RPS for all tenants irrespective of the tenant creation
date, size, or opt-out status.

**Solution:** You can use Exchange Online PowerShellV3 module.

***Ref:***
<https://techcommunity.microsoft.com/t5/exchange-team-blog/deprecation-of-remote-powershell-in-exchange-online-re-enabling/ba-p/3779692>

### Oct 10, 2023- Older Office Versions Not Supported for Connecting to
Microsoft 365 Services

Older Office versions (Office 2016 & 2019) might still be able to
connect to Microsoft 365 services, but that connectivity isn't
supported.

**Solution:** You can use Microsoft 365 apps.

***Ref**:*
<https://learn.microsoft.com/en-us/deployoffice/endofsupport/microsoft-365-services-connectivity>

### Oct 15, 2023- Classic Stream Retirement.\
Users are no longer able to access or use Stream (Classic) unless admin
takes action to delay this change.

**Solution:** Admins can [extend the
date](https://learn.microsoft.com/en-us/stream/streamnew/migration-settings#delay-upload-block-setting).
This change can be delayed until April 15, 2024.

***Ref:***
https://learn.microsoft.com/en-us/stream/streamnew/stream-classic-to-new-migration-overview#upcoming

## Nov 2023

Major update: 1, Retirement: 1

## Major Update:

### Nov 1, 2023 -- New Requirements for SMTP Relay through Exchange Online

Effective from November 1, 2023, the matching condition for the SMTP P2
sender domain will be removed. This means that relaying email through
Exchange Online will require meeting the following criteria:

-   Accepted domain: The SMTP certificate domain on the SMTP connection
    or the SMTP envelope sender domain in the MAIL FROM command (P1
    sender domain) must be one of your organization\'s accepted domains.

-   Inbound Connector: The sending host\'s IP address or certificate
    domain on the SMTP connection must match your organization\'s
    Inbound Connector of on-premises type.

Failure to meet either of these conditions after November 1, 2023, will
result in the rejection of relay attempts from your on-premises
environment to Exchange Online

**Solution:** It is necessary to modify your Inbound Connector of the
on-premises type and switch from using IP addresses to a certificate
domain. Furthermore, you need to ensure that the certificate domain is
included as an accepted domain of your organization.

***Ref:***
https://techcommunity.microsoft.com/t5/exchange-team-blog/updated-requirements-for-smtp-relay-through-exchange-online/ba-p/3851357

## Retirement

### Nov 13, 2023 - Exchange Transport Rules (ETRs) stopping support for DLP scenarios

Beginning mid-November, Exchange DLP-related actions and
conditions/exceptions (predicates) will be removed from mail flow rules

**Solution:** You use Microsoft Purview Unified DLP, which provides DLP
protection to SharePoint Online, OneDrive for Business, Teams chats,
devices, and more.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC670895>

## Dec 2023

Deprecation: 1

### Dec 31, 2023 - Retirement of OMEv1 (Office 365 Message Encryption) 

OME v1 mail flow rules will be fully retired.

**Solution:** If you don't do anything, Microsoft will process all mail
flow rules that currently applies OME protection to Microsoft Purview
Message Encryption protection.

***Ref:***
<https://admin.microsoft.com/adminportal/home?ref=MessageCenter/:/messages/MC455516>

## 2024 (Attention needed: 9)

### Jan 2024- Wiki Retirement in Teams Channels

Wikis tab and wiki App wouldn't be able to accessible in Teams and users
wouldn't be able to export.

**Solution:** Your data is accessible from SharePoint as per retention
policy even after Wiki is deprecated. You can download wiki content from
SharePoint.

***Ref***:
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC496248>

### Jan 31, 2024: Microsoft Will Retire the Stream Live Events 

This affects customers who use Stream (Classic) or Yammer to create and
host Stream live events. New Stream live events can't be created, and
events scheduled after January 31, 2024, will be automatically removed.

**Solution:** Microsoft Teams live events will become a platform to host
and run live events.

***Ref***:
<https://learn.microsoft.com/en-us/stream/streamnew/stream-classic-to-new-migration-overview#upcoming>

### Mar 30, 2024 - Azure AD Graph Retirement and PowerShell Module Deprecation

Microsoft has postponed the deprecation date for MS Online, AzureAD, and
AzureAD Preview PowerShell modules to March 30, 2024.

**Solution:** Before the deprecation date, you can migrate your existing
scripts to MS Graph.

***Ref***:
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/important-azure-ad-graph-retirement-and-powershell-module/ba-p/3848270>

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
remaining content in Stream (Classic) that wasn\'t migrated will be
deleted.

**Solution:** You can use Stream on SharePoint.

***Ref***:
https://techcommunity.microsoft.com/t5/microsoft-stream-blog/update-on-stream-classic-retirement-last-day-of-service-set-for/ba-p/3712075

### Sep 30, 2024- Azure Multi-Factor Authentication Server 

Azure MFA Server deployments will no longer service MFA requests, which
could cause authentications to fail for your organization.

**Solution:** Organizations should migrate their users' authentication
data to the cloud-based Azure MFA service

***Ref:***
https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-september-2022-train/ba-p/2967454

### Sep 30, 2024- Retirement of Managing Authentication Methods in Legacy MFA & SSPR Policy 

Starting Oct 2024, Microsoft no longer allow authentication methods to
be managed in the legacy MFA and SSPR policies.

**Solution:** Organizations should use the converged authentication
methods policy where methods can be managed centrally for all
authentication scenarios including passwordless, MFA and SSPR.

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448>

### End of 2024- Retirement of Mail and Calendar Apps in Windows

At the end of 2024, Microsoft replacing the Mail and Calendar apps in
Windows with the new Outlook for Windows.

**Solution:** Start trying and testing the new Outlook for Windows.

***Ref***:
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC590123>

## 2025 (Attention needed: 2)

### Feb 01, 2025- Azure Key Vault: Soft-delete Will be Enabled on All Key Vaults 

Soft Delete preserves deleted key vaults and secrets for up to 90 days,
enabling customers to restore them through a self-serve process.

***Ref:***
<https://learn.microsoft.com/en-us/azure/key-vault/general/soft-delete-change>

### Oct 14, 2025- End of Extended Support for Office 2016 & Office 2019 

Office 2016 and Office 2019 extended support ends in 2025.\
**Solution:** You can start to use the latest supported versions.\
***Ref:***
https://learn.microsoft.com/en-us/lifecycle/products/microsoft-office-2016

## 2026 (Attention needed: 4)

### Jan 13, 2026- End of Extended Support for Microsoft Advanced Threat Analytics 1.x 

Microsoft Advanced Threat Analytics (ATA) extended support will be ended
on January 13, 2026.

**Solution**: Updates for Microsoft ATA are available from Microsoft
Update or by manual download.

***Ref:***
<https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c>

### Mar 31, 2026- Deprecation of 'Require Approved Client App' Conditional Access Grant 

The Require approved client app control in Azure Active Directory (Azure
AD) Conditional Access will be retired and no longer enforced.

**Solution:** You can make use of the "Require app protection policy"
control, which has all the same capabilities

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448>

### Apr 02, 2026- SharePoint 2013 Workflow Retirement\
SharePoint 2013 workflows will no longer be supported.

**Solution:** You can move to Power Automate or other supported
solutions.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC542767>

### July 14, 2026- InfoPath 2013 Client and InfoPath Forms Services in SharePoint Online will be Retired

InfoPath Client 2013 will reach the end of its extended support period
on July 14, 2026, and to keep an aligned experience across Microsoft
products, InfoPath Forms Service will be retired from SharePoint Online.

**Solution:** To understand the usage of InfoPath within your
organization, you can utilize the [Microsoft 365 Assessment
tool](https://aka.ms/assessment/infopath) to scan your tenant and
analyze InfoPath usage. If you are currently using InfoPath, you can
initiate the migration process to modern alternatives such as Power
Apps, Power Automate, or Forms.

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190>


In conclusion, navigating the ever-evolving landscape of Microsoft 365 requires staying informed about the changes. By proactively adapting to these changes, you can optimize your Microsoft 365 experience, maximize productivity, and effectively plan for the future. 

We are committed to keeping this blog updated with the latest information, so stay tuned for upcoming updates.
### Blog link: https://blog.admindroid.com/microsoft-365-end-of-support-milestones
