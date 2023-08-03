# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.

Discover the **key changes, deprecations,** and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

Here is a list of changes categorized by month and year.

- Aug 2023 (New features: 5, Retirements: 4, Enhancements: 3, Functionality Changes: 2, Review Required: 1 )

- Sept 2023 (New feature: 2, Retirements: 8)

- Oct 2023 (New Features: 1, Retirements: 4)

- Nov 2023 (Major update: 1)

- Dec 2023 (Deprecation: 1)

- 2024 (Attention needed: 8)

- 2025 (Attention needed: 2)

- 2026 (Attention needed: 4)



## Aug 2023

(New Features:5 \| Retirements: 4 \| Enhancement:3 \| Functionality
Change:2 \| Review Required:1)

## New features:

### Aug 2023- Double-key Encryption to Protect Sensitive Files and Emails in
Microsoft 365 Apps.\
To protect sensitive content, Microsoft 365 Apps users can now use
Double Key Encryption (DKE) for files and emails using the built-in
labeling client.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC611732>

### Aug 2023- Introducing Voice OTP

Starting in early August, Microsoft is introducing Voice OTP (One-Time
Password) as an enhancement to registration campaigns. This new feature
will be specifically available for existing tenants utilizing Azure AD
free licenses. However, for new Azure AD free license tenants, Voice OTP
will be available starting from July.

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-new-feature-and-change-announcements/ba-p/3796396>

### New Features Aug 2023- Microsoft Teams: Teams Shared Device license on Teams mobile app for Android

To enable mobile and flexible work, Microsoft Teams Shared Device
license will be available to the Teams Android app. This allows Android
phones to function as shared devices with full calling features like
Walkie Talkie, call queues, auto attendants, and more.

***Ref:***
<https://learn.microsoft.com/en-us/microsoftteams/teams-add-on-licensing/teams-shared-device-license>

### Aug 2023- Microsoft Teams: Enable second video stream with \"Teams
Content Camera on Desktop\"\

Users can now enable a second video stream on Desktop, supporting both
Personal Video and Teams Content Camera. When activating Teams Content
Camera on Desktop, Personal Video will remain until the user chooses a
different Camera for the two video streams. This feature roll out will
begin in Aug for Targeted release customers.\

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC642270>

### Aug 2023- Microsoft Teams: New Admin Policy for Collaborative Annotations

Microsoft introduced a user-level IT admin policy, giving admins the
flexibility to decide if certain or all users in the company can utilize
Collaborative Annotations. The IT admins can easily control this feature
by toggling ON or OFF Collaborative Annotations from the Teams admin
center under Meetings \--\> Meeting policies

***Ref:***
https://www.microsoft.com/en-in/microsoft-365/roadmap?rtc=1&searchterms=92502&filters=&searchterms=92502

## Retirements

### Aug 2023- Basic Authentication Retirement in Microsoft 365 Apps 

Microsoft 365 Apps are disabling server sign-in prompts using Basic
authentication in Office Apps such as, Access, Excel, OneNote, Outlook. 

**Solution**: Instead of basic authentication, Microsoft recommends
using Modern Authentication, and enabling multi-factor authentication
based on OAuth2.0 token-based auth. 

***Ref:*** [[https://learn.microsoft.com/en-us/deployoffice/security/basic-authentication-prompts-blocked#versions-of-microsoft-365-apps-affected-by-this-change]{.underline}](https://learn.microsoft.com/en-us/deployoffice/security/basic-authentication-prompts-blocked#versions-of-microsoft-365-apps-affected-by-this-change) 

### Aug 15- Classic Stream Retirement

On August 15, as part of the Classic Stream retirement process, users
will no longer be able to create new Stream (Classic) web parts. This
change is a step towards the complete retirement of Classic Stream,
which is scheduled for April 15, 2024.

**Solution:** You can start to use Stream in SharePoint 

***Ref:***: [[https://learn.microsoft.com/en-us/stream/streamnew/stream-classic-to-new-migration-overview#upcoming]{.underline}](https://learn.microsoft.com/en-us/stream/streamnew/stream-classic-to-new-migration-overview#upcoming)

### Aug 31: Kaizala Retirement

Microsoft Kaizala is a communication tool designed for large groups,
particularly suitable for organizations with mobile workforces.
Microsoft will retire Kaizala on August 31, 2023. After the retirement
date, access to and support for Kaizala will be discontinued.   

**Solution:** Microsoft recommends moving to Microsoft Teams for
continued connection, sharing, and collaboration. 

***Ref:*** [[https://learn.microsoft.com/en-us/lifecycle/products/kaizala]{.underline}](https://learn.microsoft.com/en-us/lifecycle/products/kaizala?branch=live)

### Aug 31- Scheduler for Microsoft 365 Retirement

On September 1, 2023, Microsoft will retire Scheduler for Microsoft 365,
a tool that helps users automate the process of scheduling meetings and
delegate appointments. As a result, users will no longer be able to use
Cortana to automatically schedule meetings.  

**Solution**: At this time, Microsoft has not announced any alternative
solution, though they may include some of these features in a future
offering. 

***Ref:*** [[https://admin.microsoft.com/AdminPortal/?ref=MessageCenter/:/messages/MC424413]{.underline}](https://admin.microsoft.com/AdminPortal/?ref=MessageCenter/:/messages/MC424413)


### Enhancements:

### Early Aug 2023- Enhanced Support for Teams Video Clips

eDiscovery administrators collecting Teams video clips will now find
them as separate video recording files attached to the respective Teams
conversations. This enhancement allows for easier review and export of
the video clips as MP4 files, providing admins with a clearer
understanding of the content and context.

This feature is available for Microsoft Purview eDiscovery (Premium)

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC578238>

### Early Aug 2023- Microsoft Purview Insider Risk Management: Policy template limit increase

Insider Risk Management enables customers to create policies based on
their own internal policies, governance, and organizational
requirements. With this update, the maximum number of policies for each
insider risk policy template increases from 5 to 20.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC663628>

### Aug 2023- OneDrive Sync Account Detection

OneDrive Sync for work/school will display a one-time message to users
signing into a personal account on their work machine. The message
offers a one-click setup to configure their personal account with
OneDrive. Once enabled, users can access both personal and work/school
files in their OneDrive and File Explorer.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC626577>

## Functionality Change:

### Late Aug 2023- Microsoft 365 Apps: Encryption Algorithm Changes to AES256-CBC for Encrypting Emails and Files

Microsoft 365 Apps, Exchange Online, and SharePoint Online will use
AES256 in cipher block chaining (CBC) mode as the default encryption
method for emails and documents when using Microsoft Purview Information
Protection.

***Ref:***
<https://techcommunity.microsoft.com/t5/security-compliance-and-identity/encryption-algorithm-changes-in-microsoft-purview-information/ba-p/3831909>

### Late Aug 2023 - Windows Mail and Calendar are becoming Outlook

The Mail and Calendar apps for Windows are being replaced with the new
Outlook for Windows at the end of 2024. As part of this, in late August
of 2023, Windows Mail and Calendar apps will auto-migrate to the new
Outlook for Windows. Users can revert to the current apps by clicking a
toggle in the new Outlook.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC650424>

## Review Required

###Aug 10, 2023 -- New DMARC Policy Handling

Microsoft is updating its Anti-Phishing policy to automatically follow
DMARC policies by default. For emails that fail DMARC authentication,
the default actions will be set to \'reject\' and \'quarantine\' for
\'p=reject\' and \'p=quarantine\' respectively.

Now, recipient tenant admins will have the flexibility to choose whether
to retain the default settings or modify them. They can decide to
\'reject\' or \'junk\' messages based on their organizational needs.

***Ref:***
<https://www.microsoft.com/en-in/microsoft-365/roadmap?rtc=2&searchterms=117533&filters=&searchterms=117533>

## Sep 2023

New feature: 2 \| Retirement: 6

## New Feature: 

### Early-Sep 2023- Discover and Co-author Documents Labeled with User-defined Permissions.

SharePoint and OneDrive will support discovery and coauthoring of files
labeled with user-defined permissions. These files can be easily
accessed, edited, co-authored, and benefit from the AutoSave feature in
Word, Excel, and PowerPoint apps across all platforms.

***Ref***:
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC617055>

Sept 15, 2023- Microsoft Graph to Support HTTP/2

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

### Sep 15, 2023: Microsoft Will Retire the Stream Live Events

This affects customers who use Stream (Classic) or Yammer to create and
host Stream live events\
**Solution:** Microsoft Teams live events will become a new platform to
host and run live events.\
***Ref***:
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC513601>

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

Major update: 1

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

## Dec 2023

Deprecation: 1

### Dec 31, 2023 - Retirement of OMEv1 (Office 365 Message Encryption) 

OME v1 mail flow rules will be fully retired.

**Solution:** If you don't do anything, Microsoft will process all mail
flow rules that currently applies OME protection to Microsoft Purview
Message Encryption protection.

***Ref:***
<https://admin.microsoft.com/adminportal/home?ref=MessageCenter/:/messages/MC455516>

## 2024 (Attention needed: 8)

### Jan 2024- Wiki Retirement in Teams Channels

Wikis tab and wiki App wouldn't be able to accessible in Teams and users
wouldn't be able to export.

**Solution:** Your data is accessible from SharePoint as per retention
policy even after Wiki is deprecated. You can download wiki content from
SharePoint.

***Ref***:
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC496248>

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
