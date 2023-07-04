# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.

Discover the **key changes, deprecations,** and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

Here is a list of changes categorized by month and year.

- July 2023 (New Feature: 5, Retirement: 5, Enhancement: 2, Configuration
Change:1, Major Announcement:2)

- Aug 2023 (New feature: 2, Enhancement: 1)

- Sept 2023 (New feature: 2, Retirement: 6)

- Oct 2023 (Deprecation: 3)

- Nov 2023 (Major update: 1)

- Dec 2023 (Deprecation: 1)

- 2024 (Attention needed: 8)

- 2025 (Attention needed: 2)

- 2026 (Attention needed: 4)

### July 2023

(New Feature:5 \| Retirement: 5 \| Enhancement:2 \| Configuration
Change:1 \| Major Announcement:1)

### New Features:

### July 2023: Collaborative Meeting Notes in Microsoft Teams

Users will see a Notes button during meetings. Participants can
collaborate in real time, create an agenda, take notes and add tasks.
The rollout will complete in Mid-July.\
***Ref**:*
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC538385>

### Mid July 2023- New Microsoft Teams Rollout

Starting in late July 2023, Microsoft will introduce the \"Try the new
Teams\" toggle within the classic Microsoft Teams client. In September
2023, the new Teams app will become the default option.

**Solution:** Administrators have the ability to manage this change by
configuring the \"Use new Teams client\" policy and setting \"New Teams
as default\" for their users.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC617066>

### Mid July 2023- Schedule Send on Outlook for Android

The latest update of Outlook for Android introduces the new 'Schedule
send' feature, enabling you to compose emails and schedule them to be
sent later.

Note: 'Schedule send' is already available in Outlook for iOS.

***Ref:***
<https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=98927>

### Mid July 2023- Microsoft Purview eDiscovery (Premium): Tenant-wide Jobs Report

With tenant-wide job report, administrators get visibility into all
eDiscovery jobs in the tenant, allowing administrators to track and
monitor them in relation to the specified limits.

***Ref:***
<https://learn.microsoft.com/en-us/microsoft-365/compliance/ediscovery-managing-jobs>

### Mid July 2023- New Insider Risk Analytics Capabilities and Email Notifications in Insider Risk Management.

Admins can manage email notifications through the "Admin notifications"
section of Insider risk settings, see recommended thresholds in the
policy wizard, and see the new insights in insider risk analytics.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC572514>

### Enhancements

### Mid July 2023- Data Loss Prevention for EXO - Deliver the Message to the
Hosted Quarantine.\
Microsoft is introducing a new column in the \"Data Loss Prevention\"
section that allows easy viewing of messages delivered to hosted
quarantine. This enhancement eliminates the need to filter these
messages under transport rules.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC609877>

### 

### Mid July 2023- Microsoft Secure Score is Adding New Improvement Actions

Microsoft has introduced Secure Score improvement actions to enhance the
accuracy of your security posture. These actions include managing
accounts with passwords older than 180 days, removing the attribute
\'password never expires\' from domain accounts, and eliminating local
admins on identity assets.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC574388>

### Retirements

### July 01, 2023: Retirement of Remote PowerShell (RPS) Protocol in
Exchange Online PowerShell.\
If you are using RPS to establish an Exchange Online connection, you
will not be able to do so after July 1, 2023.\
**Solution:** You can use the EXO V3 module.\
***Ref:***
https://techcommunity.microsoft.com/t5/exchange-team-blog/announcing-deprecation-of-remote-powershell-rps-protocol-in/ba-p/3695597

### July 15, 2023- RPS Retirement in SCC

Microsoft is deprecating the legacy RPS protocol in the Security and
Compliance PowerShell module.

**Solution:** Use the latest EXO PowerShell module to ensure REST is
used.

***Ref:***
[*https://techcommunity.microsoft.com/t5/exchange-team-blog/deprecation-of-remote-powershell-rps-protocol-in-security-and/ba-p/3815432*](https://techcommunity.microsoft.com/t5/exchange-team-blog/deprecation-of-remote-powershell-rps-protocol-in-security-and/ba-p/3815432)

### July 15,2023 - Microsoft Bookings - Mobile Apps Retirement

As Microsoft has removed the mobile apps from the Google Play Store and
Apple App Store, users who already have the apps installed will still be
able to access them. However, starting from July 15, users in
organizations who have installed the Bookings Mobile Apps will no longer
be able to access Bookings through these installed apps.

**Solution:** Users currently using the mobile apps are advised to
transition to the mobile-friendly web version by accessing the Bookings
web page ([https://book.ms](https://book.ms/)) through their mobile
browser.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC590142>

### Mid July 2023- PDF Tools app retirement

Microsoft retiring the PDF Tools app from Teams, Office and Outlook
store by mid-July 2023. This change will not affect the ability to open
PDFs in existing apps like Teams and Outlook, nor will it impact the
conversion of files to PDF within the Word, Excel, or PowerPoint apps.

**Solution:** By accessing Office.com, you can right click on any file
without opening it and select \"Convert to PDF\" to directly convert the
file to PDF.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC584834>

### July 2023: Changes are Coming to the Minimum Supported Browsers &
Versions for Microsoft 365 Web Apps.\
Unsupported browsers will no longer be able to connect to the Microsoft
365 web applications. applications.\
**Solution:** Ensure all devices in the organization are using a
Microsoft 365 supported browser, and that browsers have been updated to
the latest version.\
***Ref:***
https://admin.microsoft.com/adminportal/home?ref=MessageCenter/:/messages/MC518729\
\
Configuration Change:

### July 11, 2023 - Azure Information Protection Add-in will be Disabled by Default for Office Apps

Azure Information Protection Add-in will be disabled by default for
Office Apps for the Semi-Annual Enterprise Channel.

**Solution:** You will need to configure the policy setting \"Use the
Azure Information Protection add-in for sensitivity labeling\" to keep
using the Add-in.\
***Ref:***
<https://admin.microsoft.com/adminportal/home?ref=MessageCenter/:/messages/MC500902>

## Major Announcements:

### Azure AD Graph PowerShell Deprecation Postponed

Previously, Microsoft had announced that the retirement of Azure AD
PowerShell modules and Graph was scheduled for June 30, 2023. This meant
that these modules would no longer function as expected starting from
July 2023. However, the deprecations have now been postponed to March
30, 2024.

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/important-azure-ad-graph-retirement-and-powershell-module/ba-p/3848270>

### July 10, 2023: Changes to the Registration Campaign Feature in Azure AD

Starting July 10th, 2023, users in your organization that are relying on
SMS and voice for MFA will be prompted to use the **Microsoft
Authenticator** app. They can skip this prompt for a maximum of 3 times,
after which registration of the app will be required.

**Solution:** Admins can [run a registration campaign to set up Microsoft Authenticator](https://learn.microsoft.com/en-us/azure/active-directory/authentication/how-to-mfa-registration-campaign)

***Ref***:
https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-new-feature-and-change-announcements/ba-p/3796396

## Aug 2023

New feature: 2 \| Enhancements: 1

## New feature:

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

### Enhancement:

### Early Aug 2023- Enhanced Support for Teams Video Clips

eDiscovery administrators collecting Teams video clips will now find
them as separate video recording files attached to the respective Teams
conversations. This enhancement allows for easier review and export of
the video clips as MP4 files, providing admins with a clearer
understanding of the content and context.

This feature is available for Microsoft Purview eDiscovery (Premium)

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC578238>

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

Deprecation: 3

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
