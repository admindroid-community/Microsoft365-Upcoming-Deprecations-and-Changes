# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.

Discover the **key changes, deprecations,** and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

Here is a list of changes categorized by month and year.

 

- Nov 2023 (General Availability: 1; New Features: 3, Retirements: 6, Enhancements: 1, Existing Functionality Change: 1, Action Needed: 1, Retirement Postponed: 1)

- Dec 2023 (Deprecation: 1, Existing Feature Replacements: 2)

- 2024 (Attention needed: 16)

- 2025 (Attention needed: 3)

- 2026 (Attention needed: 6)

## **Retirement Postponed Announcement:** 

### **Exchange PowerShell: Retirement of Get, Set, and Remove UserPhotos Cmdlets** 

Microsoft has postponed the retirement of PowerShell cmdlets to manage
user profile photos like: *Get-UserPhoto*, *Set-UserPhoto*, and
*Remove-UserPhoto*.

The retirement is scheduled for late March 2024 (previously November 30,
2023).

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC678855>



## **November 2023** 

General Availability: 1 \| New Features: 3 \| Retirements: 6 \| Enhancements: 1 \| Existing Functionality Change: 1 \| Action Needed: 1 

## General Availability:

### Nov 01, 2023 - Microsoft 365 Copilot Generally Available

Microsoft 365 Copilot, an AI-powered tool, seamlessly integrates
Microsoft 365 data with Microsoft Graph and M365 apps. It empowers users
with various tasks and boost productivity in Microsoft 365 ecosystem.

***Ref:***
<https://www.microsoft.com/en-us/microsoft-365/blog/2023/09/21/announcing-microsoft-365-copilot-general-availability-and-microsoft-365-chat/>

## New Features:

### Nov 2023- Auto Rollout of Conditional Access Policies 

Microsoft will begin automatically protecting customers with Microsoft
managed Conditional Access policies. It includes following policies,

-   MFA for admin portals

-   MFA for per-user MFA users

-   MFA for high-risk sign-ins

***Ref:***
<https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=183905>

### Nov 2023 -- Option to Disable Roaming Signatures in Outlook on the Web 

Admins can disable roaming signatures themselves for their tenants for
Outlook on the web using the PowerShell cmdlet 'Set-OrganizationConfig'.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC684213>

### Nov 2023- Admin can Control Users' Inbox and Calendar Sharing in Outlook 

Outlook users, whether on Outlook Web Access (OWA) or Outlook for
Windows, have the ability to share their mail and calendar with others
at varying permission levels. With this new feature, administrators can
now control and disable users\' sharing capabilities through the Office
cloud policy service

**Note**: Users who have previously been granted permissions to access
inboxes and calendars will remain unaffected by this change.

***Ref:***
<https://www.microsoft.com/en-in/microsoft-365/roadmap?rtc=1&searchterms=182261&filters=&searchterms=182261>

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

### **Nov 2023- Classic Search in Purview Portal Retirement** 

From Nov2023, Classic Search available in the Microsoft Purview portal
will be retired.

**Solution:** Admins are encouraged to utilize the "New search" feature,
which offers faster search times, additional search options, the ability
to save searches, and more functionalities.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC683034>

### **Nov 11, 2023 -- Deprecation of Secret Groups in Viva Engage** 

Private unlisted groups (secret groups) in Yammer will be **permanently
deleted and deprecated** on November 11, 2023.

**Note**: If you\'ve already received an exception approval from
Microsoft support, your private unlisted groups won\'t be affected by
this change.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC683925>

### **Nov 13, 2023 - Exchange Transport Rules (ETRs) Stopping Support for DLP Scenarios** 

Beginning mid-November, Exchange DLP-related actions and
conditions/exceptions (predicates) will be removed from mail flow rules

**Solution:** You use Microsoft Purview Unified DLP, which provides DLP
protection to SharePoint Online, OneDrive for Business, Teams chats,
devices, and more.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC670895>

### **Nov 15, 2023 - Users will no Longer be able to Add Password SSO to Apps** 

Starting from November 15, 2023, end users will no longer have the
capability to incorporate password SSO Apps into their My Apps gallery.
Previously added password SSO apps remain available in My Apps.

**Note**: Admins can still add password SSO apps.

***Ref***:
<https://learn.microsoft.com/en-us/entra/fundamentals/whats-new>

### **Nov 30, 2023- Exchange PowerShell: Retirement of Get, Set, and Remove User Photos Cmdlets** 

Microsoft is phasing out the Exchange PowerShell cmdlets used by tenant
administrators to manage user profile photos, including commands like:
*Get-UserPhoto*, *Set-UserPhoto*, and *Remove-UserPhoto*.

**Solution**: As an alternative admins can utilize MS Graph PowerShell
or Microsoft 365 admin center to manage user photos.

***Ref***:
<https://admin.microsoft.com/AdminPortal/Home?ref=MessageCenter/:/messages/MC678855>

## **Enhancement:**

### **Nov 2023- Ability to View Declined Meetings in Outlook** 

A new calendar setting Preserve Declined Meeting (PDM) in Outlook will
enable users to choose if they want their declined meetings to be
removed or kept on their calendar. But in case, if admins want to
disable PDM availability for their entire tenant, they can do it through
PowerShell.

***Ref:***
<https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=154056>

## **Existing Functionality Change:**

### **Nov 01, 2023- Pin Based Verification Process for Support Callers** 

Starting November 1, 2023, enhanced verification will be required to
open and manage a phone-initiated case with Microsoft Support.

**Proactive steps:** To help an expedited Support experience, M365admins can
update their profile contact information: *Admin center-\>Users-\>Active
users-\>Admin Name-\>Manage contact information*.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC680788>

## **Action Required:** 

### **Nov 1, 2023 -- New Requirements for SMTP Relay through Exchange Online** 

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
<https://techcommunity.microsoft.com/t5/exchange-team-blog/updated-requirements-for-smtp-relay-through-exchange-online/ba-p/3851357>


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

### **Jan 01, 2024 -- Social Rating App Retirement in SharePoint**

Microsoft will start retiring the number of social rating APIs starting
January 2024, including *CountRatingsOnUrl, GetRatingsOfUser.*

**Solution:** You can use the *SetRating (string URL, int rating, string
title, FeedbackData analysisDataEntry), PropagateRating (string URL) ,
and GetRatingAverageOnUrl (string URL)* as a replacement.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC683665>

### **Jan 08, 2024 - Business Connectivity Services retirement in Microsoft 365**

As part of Business Connectivity Services retirement in Microsoft 365,
Microsoft will block Business Connectivity Services features in new
Microsoft 365 tenants by default from Jan 08, 2024.

**Note:** From Sep 30, 2024, Business Connectivity Services will be
fully retired.

**Solution:** Microsoft encourages customers to use Power Apps to
replace their Business Connectivity Services solutions in SharePoint in
Microsoft 365.

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-business-connectivity-services-in-microsoft/ba-p/3938773>

### **Jan 30, 2024 -- Retirement of Stream Live Events** 

This affects customers who use Stream (Classic) or Yammer to create and
host Stream live events

**Solution**: You can use the Teams live events with encoder support,

***Ref:***
<https://learn.microsoft.com/en-us/stream/streamnew/stream-classic-to-new-migration-overview#upcoming>

### **Feb 2024- Microsoft Teams: Forward Messages Between Chat Conversations** 

Microsoft Teams will allow users to forward messages to 1:1 chats,
meeting chats, and group chats. The forward messages feature simplifies
the sharing of important information and facilitates tracking of
discussions for future reference.

***Ref:***
<https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=90585>

### **Mar 2024- Exchange PowerShell: Retirement of Get, Set, and Remove UserPhotos Cmdlets** 

Microsoft is phasing out the Exchange PowerShell cmdlets used by tenant
administrators to manage user profile photos, including commands like:
*Get-UserPhoto*, *Set-UserPhoto*, and *Remove-UserPhoto*.

**Solution**: As an alternative admins can utilize MS Graph PowerShell
or Microsoft 365 admin center to manage user photos.


### **Mar 30, 2024 -- Azure AD Graph Retirement and PowerShell Module Deprecation** 

Microsoft has postponed the deprecation date for MS Online, AzureAD, and
AzureAD Preview PowerShell modules to March 30, 2024.

**Solution:** Before the deprecation date, you can migrate your existing
scripts to MS Graph.

***Ref***:
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/important-azure-ad-graph-retirement-and-powershell-module/ba-p/3848270>

### **Mar 31, 2024- Classic Teams Users Will be Automatically Updated to New Teams**

Classic Teams users will be automatically updated to the new Teams
client after March 31, 2024. If you are still using Teams classic by
that date. New Teams is [up to 2x faster and use 50% less
memory](https://research.gigaom.com/report/new-microsoft-teams-performance-benchmark).
There is no major impact to the user experience for new Teams.

**Tip:** You can deploy the new Teams client in your organization by
updating Teams Update policy in Microsoft Teams admin center.

***Ref:***
https://learn.microsoft.com/en-us/MicrosoftTeams/new-teams-automatic-upgrade-announced


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

### **Sep 30, 2024 - Business Connectivity Services retirement in Microsoft 365**

Microsoft will retire Business Connectivity Services features in
Microsoft 365 from Jan 08, 2024.

**Solution:** Microsoft recommends using Power Apps to replace their
Business Connectivity Services solutions in SharePoint in Microsoft 365.

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-business-connectivity-services-in-microsoft/ba-p/3938773>

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
