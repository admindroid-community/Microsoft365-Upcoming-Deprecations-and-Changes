# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.

Discover the **key changes, deprecations,** and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

Here is a list of changes categorized by month and year.

 

- Jan 2024 (Public Preview: 1; New Features: 2, Retirements: 8, Enhancements: 2, Existing Functionality Change: 2, Action Needed: 1) 

- Feb 2024 (Attention needed: 4)

- Mar 2024 (Attention needed: 4)

- Q2-2024 (Attention needed: 6)

- Q3-2024 (Attention needed: 3)

- Q4-2024 (Attention needed: 6)

- 2025 (Attention needed: 3)

- 2026 (Attention needed: 6)




## **January 2024** 
Public Preview: 1 \| New Features: 2 \| Retirements: 8 \| Enhancements: 2 \| Existing Functionality Change: 2 \| Action Needed: 1


## **Public Preview** 

### **Microsoft 365 Backup** 

Microsoft 365 backup is a new storage architecture for backup and data
protection inside Microsoft 365. It's helpful to recover M365 data from
cataclysmic events such as: at scale ransomware attacks, or
malicious/accidental data deletion/corruption by end users.

It has the capability to

-   Backup all or select SharePoint sites, OneDrive accounts, and
    Exchange mailboxes in your tenant.     

-   Restore OneDrive accounts, SharePoint sites, and mailbox items to a
    prior point in time for your entire tenant.  

The paid public preview of Microsoft 365 Backup will begin in Jan 2024
(postponed from Dec 2023).

***Ref:***
[https://techcommunity.microsoft.com/t5/microsoft-365-blog/microsoft-365-backup-and-microsoft-365-backup-storage-at-ignite/ba-p/3981049]

## **New Features:** 

### **Jan 2024 -- Device-bound Passkeys in Microsoft Entra** 

Microsoft Entra ID will support device-bound passkeys stored on
computers and mobile devices as an authentication method.

***Ref***:
[https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC690185]

### **Jan 2024- eDiscovery (Premium) -- Hold reports** 

The hold report is a report on all hold policies within the tenant and
lists all locations that are part of any hold policies within the tenant

***Ref***:
[https://www.microsoft.com/en-in/microsoft-365/roadmap?rtc=1&searchterms=93268&filters=&searchterms=93268]

## **Retirements:**

### **Jan 2024- Wiki Retirement in Teams Channels** 

Wikis tab and wiki App wouldn't be able to accessible in Teams and users
wouldn't be able to export.

**Solution:** Your data is accessible from SharePoint as per retention
policy even after Wiki is deprecated. You can download wiki content from
SharePoint.

***Ref***:
[https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC496248]

### **Jan 01, 2024 -- Social Rating App Retirement in SharePoint** 

Microsoft will start retiring the number of social rating APIs starting
January 2024, including *CountRatingsOnUrl, GetRatingsOfUser.*

**Solution**: You can use the *SetRating (string URL, int rating, string
title, FeedbackData analysisDataEntry), PropagateRating (string URL) ,
and GetRatingAverageOnUrl (string URL)* as a replacement.

***Ref:***
[https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC683665]

### **Early Jan 2024- Retirement of Legacy SharePoint Invitation Manager** 

Microsoft is retiring the legacy SharePoint Invitation Manager for
guests. It's currently used only for external Document Library sharing
or when an external user is shared with a custom role.

Solution: You can use the [[Entra B2B Invitation
Manager]{.underline}](https://learn.microsoft.com/en-us/entra/external-id/what-is-b2b)
instead.

***Ref***:
[https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC696169]

### **Jan 08, 2024 -- Business Connectivity Services retirement in Microsoft 365** 

As part of Business Connectivity Services retirement in Microsoft 365,
Microsoft will block Business Connectivity Services features in new
Microsoft 365 tenants by default from Jan 08, 2024.

Note: From Sep 30, 2024, Business Connectivity Services will be fully
retired.

**Solution**: Microsoft encourages customers to use Power Apps to
replace their Business Connectivity Services solutions in SharePoint in
Microsoft 365.

***Ref***:
[https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-business-connectivity-services-in-microsoft/ba-p/3938773]

### **Jan 15 -- Microsoft 365 Browser Extension Retirement** 

The Microsoft 365 browser extension, previously known as the Office
browser extension, is a free add-on accessible on Microsoft Edge and
Google Chrome. It allows users to access their Microsoft 365
applications and documents directly through the web browser. This
extension will reach retirement and end of support on January 15th,
2024.

**Proactive step**: Remove the Microsoft 365 browser extension from
Microsoft Edge and Chrome.

***Ref***:
[https://support.microsoft.com/en-au/office/end-of-support-for-the-microsoft-365-browser-extension-dc1024b4-92be-46eb-81a7-aea85368baa0]

### **Mid Jan 2024 -- Defender Evaluation Lab Retirement** 

Microsoft will start to retire Evaluation lab in mid-January 2024 and
expect to complete by late January 2024. After retirement, you cannot
access the resources below.

-   <https://security.microsoft.com/evaluation>

-   <https://security.microsoft.com/tutorials>

-   subsequent APIs

***Ref***:
[https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC698829]

### **Jan 30, 2024 -- Retirement of Stream Live Events** 

This affects customers who use Stream (Classic) or Yammer to create and
host Stream live events

**Solution**: You can use the Teams live events with encoder support,

***Ref:***
[https://learn.microsoft.com/en-us/stream/streamnew/stream-classic-to-new-migration-overview#upcoming]

### **Jan 31, 2024 -- Threat Protection Report Page Retirement** 

Microsoft retiring the Threat Protection report page --
<https://security.microsoft.com/mde-reports/threatProtection> (accessed
through Reports \> Endpoints \> Threat protection).

Solution: You can utilize the Advanced hunting queries and Alert queue
filter in Defender XDR.

***Ref***:
[https://learn.microsoft.com/en-us/microsoft-365/security/defender-endpoint/threat-protection-reports?view=o365-worldwide]

## **Enhancements:** 

### **Jan 2024 -- New & Improved Design for Microsoft 365 Admin Center Usage Report** 

The Microsoft 365 admin center Usage report Overview page has been
revamped for improved navigation of vital usage insights. The redesign
includes new metrics like enabled and active users, user state
compositions (e.g., distinguishing first-time from returning users),
storage by product, and key usage metrics for Microsoft 365 products.

***Ref***:
[https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC692467]

### **Jan 2024 -- New Recommendations for Microsoft Purview Insider Risk Management** 

Microsoft will introduce additional recommended actions for fine-tuning
insider risk policies and implementing advanced configurations in
Microsoft Purview Insider Risk Management.

***Ref***:
[https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC692019]

## **Existing Features Replacement:**

### **Mid Jan 2024 -- Activity-Based Authentication Timeout for OWA Replacement** 

The Activity-Based Authentication Timeout for Outlook on the web will be
replaced by Idle Session Timeout for Microsoft 365.

When Idle Session Timeout is enabled, users receive a notification when
they reach the configured idle session duration. They can choose to
either stay signed in or be automatically signed out of Microsoft 365
web apps, including Outlook on the web.

***Ref***:
[https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC694387]

### **Jan 2024 -- Microsoft Retiring Mail Flow Rules for Tracking End User Reporting** 

Microsoft will be retiring the mail flow rule which helps you track end
user reporting. The roll out will be complete in Late Jan 2024.

**Solution:** If you want to route messages to a mailbox, you can
configure them in the user reported settings in Microsoft Defender.

***Ref***:
[https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC690173]

## **Action Required**

### **Auto-rollout of Conditional Access Policy** 

Microsoft has started pushing auto-rollout of Conditional Access
Policies to automatically protect tenants. Once the policies are visible
in your tenant, you'll have 90 days to review and customize or disable
them before Microsoft turns them on. For those 90 days, the policies
will be in report-only mode. So, take action based on your
organization's needs.

***Ref***:
[https://www.microsoft.com/en-us/security/blog/2023/11/06/automatic-conditional-access-policies-in-microsoft-entra-streamline-identity-protection/]

## **February 2024**

### **Feb 2024- Microsoft Teams: Forward Messages Between Chat Conversations** 

Microsoft Teams will allow users to forward messages to 1:1 chats,
meeting chats, and group chats. The forward messages feature simplifies
the sharing of important information and facilitates tracking of
discussions for future reference.

***Ref:***
[https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=90585]

### **Feb 2024 -- MS Teams Users can Delete/Remove Items from Activity Feed** 

Microsoft Teams users can delete unwanted items from their activity
feed. The feature \[provides clutter-free experience and allows users to
focus on the most relevant and important information in their feed.

Standard release will begin rolling out early-Feb 2024.

***Ref***:
[https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=181794]

### **Feb 2024- OneNote Feed feature Replaced with New Sticky Notes** 

After this change, Users will no longer be able to access OneNote Feed
within their OneNote app on Windows. Instead, from the same location,
they will be able to launch a new Sticky Notes experience.

Note: It won't affect OneNote on Web or Outlook on Web

***Ref***:
[https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC696853]

### **Feb 02, 2024 -- Managing Audit Permission from EAC Retirement** 

Starting February 2, 2024, you will no longer be able to manage Audit
permissions using the Exchange Admin Center.

**Solution**: You can use the Purview Compliance portal to manage Audit
permissions.

*Note*: Audit permission assigned in the EAC will be automatically
replicated into the permissions tab of the Microsoft Purview Compliance
portal on February 2, 2024.

***Ref***:
[https://learn.microsoft.com/en-us/purview/audit-standard-setup#step-2-assign-permissions-to-search-the-audit-log]

## **March 2024**

### **Mar 2024- Exchange PowerShell: Retirement of Get, Set, and Remove UserPhotos Cmdlets** 

Microsoft is phasing out the Exchange PowerShell cmdlets used by tenant
administrators to manage user profile photos, including commands like:
*Get-UserPhoto*, *Set-UserPhoto*, and *Remove-UserPhoto*.

**Solution**: As an alternative admins can utilize MS Graph PowerShell
or Microsoft 365 admin center to manage user photos.

**Ref:**
[https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC678855]

### **Mar 01, 2024 -- Retirement of Search-Mailbox Cmdlet**

The *Search-Mailbox* cmdlet is useful for searching and exporting
mailbox data for legal and compliance purposes. After the deprecation
date, the *Search-Mailbox* cmdlet will no longer be supported.

**Solution**: You can use the alternative cmdlet *New-ComplianceSearch*
for this purpose.

***Ref:***
[https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC703706]

### **Mar 30, 2024 -- Azure AD Graph Retirement and PowerShell Module Deprecation** 

Microsoft has postponed the deprecation date for MS Online, AzureAD, and
AzureAD Preview PowerShell modules to March 30, 2024.

**Solution:** Before the deprecation date, you can migrate your existing
scripts to MS Graph.

***Ref***:
[https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/important-azure-ad-graph-retirement-and-powershell-module/ba-p/3848270]

### **Mar 31, 2024- Classic Teams Users Will be Automatically Updated to New Teams** 

Classic Teams users will be automatically updated to the new Teams
client after March 31st 2024. If you are still using Teams classic by
that date. New Teams is up to 2x faster and use 50% less memory. There
is no major impact to the user experience for new Teams.

**Tip:** You can deploy the new Teams client in your organization by
updating Teams Update policy in Microsoft Teams admin center.

***Ref***:
[https://learn.microsoft.com/en-us/MicrosoftTeams/new-teams-automatic-upgrade-announced]

## **April 2024**

### **Apr 02, 2024- SharePoint 2013 Workflow Retirement** 

Starting April 2nd, 2024, SharePoint 2013 workflows will be turned off
for newly created tenants. Starting April 2nd, 2026, SharePoint 2013
workflows will no longer be supported for existing tenants.

**Solution:** You can move to Power Automate or other supported
solutions.

***Ref:***
[https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC542767]

### **Apr 11, 2024- Retirement for the Azure Information Protection Unified Labeling Add-in for Office** 

The AIP Unified Labeling add-in for Office will reach end of
availability and support of the service.

**Solution:** You can use sensitivity labeling directly into Office
apps.

***Ref:***
[https://techcommunity.microsoft.com/t5/security-compliance-and-identity/retirement-notification-for-the-azure-information-protection/ba-p/3791908]

### **Apr 15, 2024- Stream (Classic) is Fully Retired & Automatically Disabled.** 

Users & admins are no longer able to access or use Stream (Classic). Any
remaining content in Stream (Classic) that wasn't migrated will be
deleted.

**Solution:** You can use Stream on SharePoint.

***Ref***:
[https://techcommunity.microsoft.com/t5/microsoft-stream-blog/update-on-stream-classic-retirement-last-day-of-service-set-for/ba-p/3712075]

## **May 2024**

### **May 2024 -- Contact De-duplication Feature in OWA** 

Maintaining a clean, updated contact list is crucial for enhanced
collaboration and productivity. Microsoft introducing a new feature to
cleaning up duplicate contacts with the de-duplication feature in
Outlook Web App (OWA)

***Ref***:
[https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=In%20development&searchterms=98124]

## **June 2024**

### **June 2024- Microsoft Teams: Workspace Management** 

Workspace management offers a unified perspective of Teams devices and
peripherals, categorized by location, accompanied by insightful details.
IT admins can now efficiently oversee connected devices, monitor
workspace health, assess utilization, and ensure adherence to standards
across all locations.

***Ref***:
[https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=In%20development&searchterms=88326]

### **June 2024- Microsoft Teams: Loop components in Teams Chat for GCC** 

In Teams chat, loop components empower users to send messages containing
tables, action items, or lists that everyone in the conversation can
collaborate on and edit together

***Ref***:
[https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=In%20development&searchterms=93163]

## **August 2024**

### **Aug 30, 2024 -- Intune Ending Support for Android Device Administrator on GMS Access Devices**

After Intune ends support for Android device administrator, devices with
access to GMS will be impacted in the following ways:

1.  Users will not be able to enroll devices with Android device
    administrator.

2.  Intune technical support will no longer support these devices.

***Ref***:
[https://techcommunity.microsoft.com/t5/intune-customer-success/microsoft-intune-ending-support-for-android-device-administrator/ba-p/3915443]

## **September 2024**

### **Sep 30, 2024- Azure Multi-Factor Authentication Server** 

Azure MFA Server deployments will no longer service MFA requests, which
could cause authentications to fail for your organization.

**Solution:** Organizations should migrate their users' authentication
data to the cloud-based Azure MFA service

***Ref:***
[https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-september-2022-train/ba-p/2967454]

### **Sep 30, 2024 -- Business Connectivity Services Retirement in Microsoft 365** 

Microsoft will retire Business Connectivity Services features in
Microsoft 365.

**Solution**: Microsoft recommends using Power Apps to replace their
Business Connectivity Services solutions in SharePoint in Microsoft 365.

***Ref***:
[https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-business-connectivity-services-in-microsoft/ba-p/3938773]

## **October 2024**

### **Oct 14, 2024 -- Office 2016 End of Support** 

After Office 2016 reaches its end of support, Microsoft no longer
provides technical support, bug fixes, and security fixes for
vulnerabilities that are discovered

**Solution**: Microsoft recommend upgrading to Microsoft 365 E3, which
comes with Microsoft 365 Apps.

***Ref***:
[https://learn.microsoft.com/en-us/deployoffice/endofsupport/plan-upgrade-older-versions-office]

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
[https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/retirement-announcement-for-azure-acs]

### **Nov 01, 2024- SharePoint Add-in Retirement** 

SharePoint Add-Ins will stop working for new tenants as of November 1,
2024, and they will be fully retired as of April 2nd, 2026.

**Solution**: Admins can run the Microsoft 365 Assessment
tool to scan their
tenants for SharePoint Add-In usage.

***Ref***:
[https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865]

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
[https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC698136]

### **Dec 31, 2024- Microsoft Teams Live Event Retirement** 

As part of MS Teams live event retirement (planned on Sep 30, 2024),
existing recordings will be accessible till Dec 31, 2024. If you want to
keep the recording, download and upload them to a different location
before December 31.

**Solution**: You can start to use town halls.

***Ref***:
[https://admin.microsoft.com/adminportal/home?ref=MessageCenter/:/messages/MC678003]

### **End of 2024- Retirement of Mail and Calendar Apps in Windows** 

At the end of 2024, Microsoft replacing the Mail and Calendar apps in
Windows with the new Outlook for Windows.

**Solution:** Start trying and testing the new Outlook for Windows.

***Ref***:
[https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC590123]


## **2025 (Attention Needed: 3)** 

### **Feb 01, 2025- Azure Key Vault: Soft-delete Will be Enabled on All Key Vaults** 

Soft Delete preserves deleted key vaults and secrets for up to 90 days,
enabling customers to restore them through a self-serve process.

***Ref:***
<https://learn.microsoft.com/en-us/azure/key-vault/general/soft-delete-change>

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
organization, you can utilize the [[Microsoft 365 Assessment
tool]{.underline}](https://aka.ms/assessment/infopath) to scan your
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


In conclusion, navigating the ever-evolving landscape of Microsoft 365 requires staying informed about the changes. By proactively adapting to these changes, you can optimize your Microsoft 365 experience, maximize productivity, and effectively plan for the future. 

We are committed to keeping this blog updated with the latest information, so stay tuned for upcoming updates.
### Blog link: https://blog.admindroid.com/microsoft-365-end-of-support-milestones
