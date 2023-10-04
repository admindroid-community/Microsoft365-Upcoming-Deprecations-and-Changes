# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.

Discover the **key changes, deprecations,** and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

Here is a list of changes categorized by month and year.


- Oct 2023 (Public Preview: 1, New features: 3, Retirements: 7, Retirement Postponed: 1, Enhancements: 2, Functionality Changes: 1, Action Required: 1)

- Nov 2023 (Major update: 1, Retirements: 3)

- Dec 2023 (Deprecation: 1, Existing Feature Replacements: 2)

- 2024 (Attention needed: 11)

- 2025 (Attention needed: 3)

- 2026 (Attention needed: 6)

## **Retirement Postponed Announcement:** 

### **Migrate to the Authentication Methods Policy in Azure Active Directory** 

The retirement of the ability to manage authentication methods in the
legacy Multifactor Authentication (MFA) and Self-Service Password Reset
(SSPR) policies in Entra ID has been postponed. The new retirement date
has been extended from September 30th, 2024, to September 30th, 2025.

***Ref:***
<https://learn.microsoft.com/en-us/azure/active-directory/authentication/how-to-authentication-methods-manage#finish-the-migration>



## Oct 2023

Public Preview: 1 \| New features: 3 \| Retirements: 7 \| Retirement Postponed: 1 \| Enhancements: 2 \| Functionality Changes: 1 \| Action Needed: 1


## **Public Preview:**

### **Oct 2023- Teams Users can Transform Their Meetings into a 3D Experience.** 

Immersive Spaces in Teams take your meetings to a whole new level by
offering a 3D experience. With a simple click, you can seamlessly
connect with your team in a pre-designed immersive environment directly
from the Teams meetings view menu.

***Ref:***
<https://admin.microsoft.com/adminportal/home?ref=MessageCenter/:/messages/MC677830>

## **New Features:**

### **Oct 5, 2023- Town Halls in Microsoft Teams** 

Microsoft is introducing Town halls in Microsoft Teams to host and
deliver large-scale, internal events to create connections across an
organization. Town hall will replace Teams Live Events and be available
for Microsoft 365 and Office 365 customers

***Ref:***
<https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=123148>
  

### **Mid Oct 2023- Personal Plans in Planner** 

Currently, all created plans must be associated with an M365 group or a
roster in Planner. With the introduction of the new Personal plan,
Microsoft is introducing a new type of container known as 'user
containers.' Personal plans are exclusively shared with the creator and
will remain inaccessible to anyone else until explicitly shared.

***Ref:***
<https://admin.microsoft.com/adminportal/home?ref=MessageCenter/:/messages/MC677519>

### **Mid-Oct 2023- Meet App in Microsoft Teams** 

The Meet app serves as a centralized hub for all meeting activities and
content. It allows users to prepare for upcoming meetings, catch up on
missed content, and access meeting-related materials like agendas,
notes, chats, and recaps, all conveniently in one place.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC660610>

## **Retirements:**

### **Oct 1, 2023- Azure AD Connect V1 Retirement** 

From October, Azure AD cloud services will stop accepting connections
from Azure AD Connect V1 servers, and identities will no longer
synchronize.\
Solution: You must migrate to Cloud sync or Azure AD Connect V2 based on
the organization's requirement.

***Ref***:
<https://learn.microsoft.com/en-us/azure/active-directory/hybrid/decommission-connect-sync-v1>

### **Oct 2023- Deprecation of Remote PowerShell (RPS) Protocol in Exchange Online PowerShell**

MS will block RPS for all tenants irrespective of the tenant creation
date, size, or opt-out status.

**Solution:** You can use Exchange Online PowerShellV3 module.

***Ref:***
<https://techcommunity.microsoft.com/t5/exchange-team-blog/deprecation-of-remote-powershell-in-exchange-online-re-enabling/ba-p/3779692>

### **Oct 2023- Classic Search in Purview Portal Retirement** 

From October 2023, Classic Search available in the Microsoft Purview
portal will be retired.\
Solution: Admins are encouraged to utilize the "New search" feature,
which offers faster search times, additional search options, the ability
to save searches, and more functionalities.

***Ref:***
<https://learn.microsoft.com/en-us/purview/audit-log-search>

### **Oct 10, 2023- Older Office Versions Not Supported for Connecting to Microsoft 365 Services** 

Older Office versions (Office 2016 & 2019) might still be able to
connect to Microsoft 365 services, but that connectivity isn't
supported.

**Solution:** You can use Microsoft 365 apps.

***Ref**:*
<https://learn.microsoft.com/en-us/deployoffice/endofsupport/microsoft-365-services-connectivity>

### **Oct 10, 2023- Microsoft Office 2019 for Mac** 

Office 2019 for Mac reaches the end of support on October 10, 2023.
After that, Office 2019 for Mac will no longer receive security updates,
bug fixes, technical support, or online technical content support.

**Solution**: Microsoft recommend upgrading to Microsoft 365 E3, which
comes with Microsoft 365 Apps.

***Ref***:
<https://learn.microsoft.com/en-us/lifecycle/products/microsoft-office-2019-for-mac>

### **Oct 15, 2023- Classic Stream Retirement**

Users are no longer able to access or use Stream (Classic) unless admin
takes action to delay this change.

**Solution:** Admins can [[extend the
date]{.underline}](https://learn.microsoft.com/en-us/stream/streamnew/migration-settings#delay-upload-block-setting).
This change can be delayed until April 15, 2024.

***Ref:***
<https://learn.microsoft.com/en-us/stream/streamnew/stream-classic-to-new-migration-overview#upcoming>

### **Mid Oct 2023- Files Hub retiring from the new Outlook for Windows** 

Starting in mid-October 2023, Microsoft will be retiring the Files Hub
feature in the new Outlook for Windows. The Files Hub, which
consolidates all received attachments and files into one accessible
location via the paperclip icon on the leftmost vertical app bar, will
no longer be available

**Solution**: Instead of using the Files Hub, you can use the "Has
files" filter in the message list or the upcoming "Files" tab within
search results.

***Ref:***
<https://admin.microsoft.com/adminportal/home?ref=MessageCenter/:/messages/MC678067>

## **Enhancements:** 

### **Oct 2023- Limit Update in Tenant Allow/Block List per SKU** 

Currently, admins can only create 500 block and 500 allow entries in
sender, URL and file category in Tenant allow/block list. With this
update, admins can configure up to 10,000 block entries and 5,000 allow
entries based on the license type.

***Ref:***
<https://admin.microsoft.com/adminportal/home?ref=MessageCenter/:/messages/MC678057>

### **Oct 2023- Default Microsoft 365 Audit Logging Retention Period Doubled** 

Starting from Oct 2023, the Microsoft Purview Audit supports expanded
logging capabilities for standard customers at no additional cost. It
includes,

-   The extension of the **default audit log retention period from 90 to
    180 days** for standard customers. .

-   ***3*0+ new activities**, such as Mail Item Accessed, Teams message
    read, Teams chat created, etc., have been added to the audit log,
    which were previously exclusive to the Microsoft Purview Audit
    (Premium) subscription.

***Ref***:
<https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=171160>

## **Functionality Change:** 

### **Oct 2023- Web links from Microsoft Teams chats to open in Microsoft Edge** 

The Microsoft Teams desktop app for Windows will open web links from
Teams chats in Microsoft Edge to enable chat side-by-side experience. It
won't affect the device's default browser settings for Windows. This
Microsoft Teams change has started rolling out to Targeted Release.

**Solution:** If admins don't want to open the links through Edge,
change it via the Teams settings menu: Settings \> Files and links \>
Link open preferences.

***Ref:***
<https://www.microsoft.com/en-us/microsoft-365/blog/2023/02/16/discover-new-ways-to-multitask-with-microsoft-365-and-edge/>

## **Action Required:**

### **Mid Oct 2023- Self-service Trial Experience Available for Microsoft Purview** 

From mid-October, users in the M365 organization will be able to
initiate a self-service trial of Microsoft Purview.

**Solution**: You can [block self-service
purchases](https://blog.admindroid.com/block-self-service-purchase-for-power-platform-products-using-powershell/)
to prevent users from starting self-service trials and purchases.

***Ref:***
<https://admin.microsoft.com/adminportal/home?ref=MessageCenter/:/messages/MC676124>

## **November 2023** 

Major update: 1 \| Retirements: 3

## **Major Update:**

### **Nov 1, 2023 -- New Requirements for SMTP Relay through Exchange Online** 

Effective from November 1, 2023, the matching condition for the SMTP P2
sender domain will be removed. This means that relaying email through
Exchange Online will require meeting the following criteria:

-   Accepted domain: The SMTP certificate domain on the SMTP connection
    or the SMTP envelope sender domain in the MAIL FROM command (P1
    sender domain) must be one of your organization's accepted domains.

-   Inbound Connector: The sending host's IP address or certificate
    domain on the SMTP connection must match your organization's Inbound
    Connector of on-premises type.

Failure to meet either of these conditions after November 1, 2023, will
result in the rejection of relay attempts from your on-premises
environment to Exchange Online

**Solution:** It is necessary to modify your Inbound Connector of the
on-premises type and switch from using IP addresses to a certificate
domain. Furthermore, you need to ensure that the certificate domain is
included as an accepted domain of your organization.

***Ref:***
<https://techcommunity.microsoft.com/t5/exchange-team-blog/updated-requirements-for-smtp-relay-through-exchange-online/ba-p/3851357>

## **Retirements:**

### **Nov 2023- Translation Feature Retirement in OneNote for Windows 10** 

After this date, OneNote for Windows 10 will continue to be supported,
and the translation feature will remain visible but will show an error
when used.

**Solution**: If you wish to continue translating content in your
notebooks, you can use the OneNote app instead of OneNote for Windows
10.

***Ref***:
<https://support.microsoft.com/en-us/office/deprecating-translation-in-onenote-for-windows-10-7a09cfa4-32de-486a-9c7f-965eeeba3439?storagetype=live>

### **Nov 13, 2023 -- Exchange Transport Rules (ETRs) Stopping Support for DLP Scenarios** 

Beginning mid-November, Exchange DLP-related actions and
conditions/exceptions (predicates) will be removed from mail flow rules

**Solution:** You use Microsoft Purview Unified DLP, which provides DLP
protection to SharePoint Online, OneDrive for Business, Teams chats,
devices, and more.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC670895>

### **Nov 30, 2023- Exchange PowerShell: Retirement of Get, Set, and Remove UserPhotos Cmdlets** 

Microsoft is phasing out the Exchange PowerShell cmdlets used by tenant
administrators to manage user profile photos, including commands like:
*Get-UserPhoto*, *Set-UserPhoto*, and *Remove-UserPhoto*.

**Solution**: As an alternative admins can utilize MS Graph PowerShell
or Microsoft 365 admin center to manage user photos.

***Ref***:
<https://admin.microsoft.com/AdminPortal/Home?ref=MessageCenter/:/messages/MC678855>

## **December 2023** 

Retirement: 1 \| Existing Features Replacement: 2

## **Retirement:**

### **Dec 31, 2023 -- Retirement of OMEv1 (Office 365 Message Encryption)** 

OME v1 mail flow rules will be fully retired.

**Solution:** If you don't do anything, Microsoft will process all mail
flow rules that currently applies OME protection to Microsoft Purview
Message Encryption protection.

***Ref:***
<https://admin.microsoft.com/adminportal/home?ref=MessageCenter/:/messages/MC455516>

## **Existing Features Replacement:**

### **Dec 2023- Polling Feature in the 'Forms' App in Microsoft Teams Replaced by 'Polls' App**

Polling experience of Forms app in Teams meeting & chat scenarios will
be gradually replaced by Polls app. This is a dedicated app for all
polling and quiz needs to provide an intuitive and easy-to-access
experience.

***Ref***:
<https://techcommunity.microsoft.com/t5/microsoft-forms-blog/ultimate-polling-and-quiz-experience-with-polls-app-the/ba-p/3731630>

### **Dec 2023- Activity-Based Authentication Timeout for OWA Replacement** 

The Activity-Based Authentication Timeout for Outlook on the web will be
replaced by Idle Session Timeout for Microsoft 365.

When Idle Session Timeout is enabled, users receive a notification when
they reach the configured idle session duration. They can choose to
either stay signed in or be automatically signed out of Microsoft 365
web apps, including Outlook on the web.

***Ref***:
<https://admin.microsoft.com/adminportal/home?ref=MessageCenter/:/messages/MC674426>

## **2024 (Attention Needed: 11)** 

### **Jan 2024- Wiki Retirement in Teams Channels** 

Wikis tab and wiki App wouldn't be able to accessible in Teams and users
wouldn't be able to export.

**Solution:** Your data is accessible from SharePoint as per retention
policy even after Wiki is deprecated. You can download wiki content from
SharePoint.

***Ref***:
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC496248>

### **Jan 30, 2024 -- Retirement of Stream Live Events** 

This affects customers who use Stream (Classic) or Yammer to create and
host Stream live events

**Solution**: You can use the Teams live events with encoder support,

***Ref:***
<https://learn.microsoft.com/en-us/stream/streamnew/stream-classic-to-new-migration-overview#upcoming>

### **Mar 30, 2024 -- Azure AD Graph Retirement and PowerShell Module Deprecation** 

Microsoft has postponed the deprecation date for MS Online, AzureAD, and
AzureAD Preview PowerShell modules to March 30, 2024.

**Solution:** Before the deprecation date, you can migrate your existing
scripts to MS Graph.

***Ref***:
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/important-azure-ad-graph-retirement-and-powershell-module/ba-p/3848270>

### **Apr 02, 2024- SharePoint 2013 Workflow Retirement** 

Starting April 2nd, 2024, SharePoint 2013 workflows will be turned off
for newly created tenants. Starting April 2nd, 2026, SharePoint 2013
workflows will no longer be supported for existing tenants.

**Solution:** You can move to Power Automate or other supported
solutions.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC542767>

### **Apr 11, 2024- Retirement for the Azure Information Protection Unified Labeling Add-in for Office** 

The AIP Unified Labeling add-in for Office will reach end of
availability and support of the service.

**Solution:** You can use sensitivity labeling directly into Office
apps.

***Ref:***
<https://techcommunity.microsoft.com/t5/security-compliance-and-identity/retirement-notification-for-the-azure-information-protection/ba-p/3791908>

### **Apr 15, 2024- Stream (Classic) is Fully Retired & Automatically Disabled.** 

Users & admins are no longer able to access or use Stream (Classic). Any
remaining content in Stream (Classic) that wasn't migrated will be
deleted.

**Solution:** You can use Stream on SharePoint.

***Ref***:
<https://techcommunity.microsoft.com/t5/microsoft-stream-blog/update-on-stream-classic-retirement-last-day-of-service-set-for/ba-p/3712075>

### **Sep 30, 2024- Azure Multi-Factor Authentication Server** 

Azure MFA Server deployments will no longer service MFA requests, which
could cause authentications to fail for your organization.

**Solution:** Organizations should migrate their users' authentication
data to the cloud-based Azure MFA service

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-september-2022-train/ba-p/2967454>

### **Oct 14, 2024 -- Office 2016 End of Support** 

After Office 2016 reaches its end of support, Microsoft no longer
provides technical support, bug fixes, and security fixes for
vulnerabilities that are discovered

**Solution**: Microsoft recommend upgrading to Microsoft 365 E3, which
comes with Microsoft 365 Apps.

***Ref***:
<https://learn.microsoft.com/en-us/deployoffice/endofsupport/plan-upgrade-older-versions-office>

###  **Dec 31, 2024- Microsoft Teams Live Event Retirement** 

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
