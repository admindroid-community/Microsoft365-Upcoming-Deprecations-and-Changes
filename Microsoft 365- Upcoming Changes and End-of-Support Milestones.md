# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.

Discover the **key changes, deprecations,** and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

Here is a list of changes categorized by month and year.

 


- May 2024 (Spotlight Features: 3, Deprecation Postponed: 1, New Features: 6, Retirements: 7, Enhancements: 3, Action Required: 1 )

- June 2024 (Attention needed: 8)

- Q3-2024 (Attention needed: 12)

- Q4-2024 (Attention needed: 7)

- 2025 (Attention needed: 10)

- 2026 (Attention needed: 9)




## May 2024
Spotlight Features: 3 \| Deprecation Postponed: 1\| New Features: 6 \| Retirements: 7 \| Enhancements: 3  \| Action Required: 1

## In the Spotlight:

### Platform SSO for macOS

Platform SSO is an advancement of the current SSO Extension
functionalities designed for macOS. It grants users the ability to
access their Macs without entering traditional passwords. Instead, they
can use passwordless login or synchronize their local credentials with
their Entra ID credentials.

Currently, this feature is in Public Preview.

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-entra-blog/platform-sso-for-macos-now-in-public-preview/ba-p/4051574>

### Organizational Messages in Microsoft 365 Admin Center

Organizational messages enable you to create and deliver short-form
communications to people in your organization through the Microsoft
products they use every day, like Microsoft Windows 11 or Microsoft 365
apps.

Currently, this feature is in Public Preview and available for all
licenses.

***Ref:*** <https://techcommunity.microsoft.com/t5/microsoft-365-blog/introducing-organizational-messages-preview-in-the-microsoft-365/ba-p/4123890>

### General Availability of Microsoft Entra External ID

The Microsoft Entra External ID feature is an advanced customer identity
and access management (CIAM) solution designed to handle external
identities comprehensively. It offers a unified platform to manage
various types of external identities, including customers, partners,
suppliers, and contractors.

***Ref:*** <https://techcommunity.microsoft.com/t5/microsoft-entra-blog/announcing-general-availability-of-microsoft-entra-external-id/ba-p/3974961>



## Deprecation Postponed:

### Retirement of Search-AdminAuditLog and MailboxAuditLog Cmdlets Postponed

Microsoft scheduled to deprecate Search-MailboxAuditLog and
Search-AdminAuditLog, and they were supposed to stop working from May
2024. However, according to the latest announcement, Microsoft has
postponed the retirement of these cmdlets without announcing a new date.

***Ref:***
<https://techcommunity.microsoft.com/t5/security-compliance-and-identity/important-announcement-deprecation-of-adminauditlog-and/ba-p/4036537>


## New Features:

### May 2024- Microsoft 365: Archive Feature for Inactive Sites on SharePoint

The feature enables admins to save on costs of storage exceeding the
quota limit by archiving the inactive sites in SharePoint.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC789317>

### May 2024 -- Contact De-duplication Feature in OWA 

Maintaining a clean, updated contact list is crucial for enhanced
collaboration and productivity. Microsoft introducing a new feature to
cleaning up duplicate contacts with the de-duplication feature in
Outlook Web App (OWA)

***Ref***:
<https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=In%20development&searchterms=98124>

### May 2024: Change SharePoint Domain Name for Larger Environments

With Advanced Tenant Rename, organizations with up to 100,000 total
sites can change their domain name. It would be helpful in cases like
rebranding, mergers, acquisitions, etc.

Note: Advanced Tenant Rename is a part of SharePoint Advanced
Management.

***Ref:***
<https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC789608>

### May 2024- Microsoft Purview: Audit Search with Microsoft Graph API

Admins can programmatically query and retrieve the activity log through
the new Audit Log Query Graph API.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC720778>

### Mid-May 2024- Data Loss Prevention for Endpoint: Optical Character Recognition (OCR) for Mac Devices

Microsoft is introducing Optical Character Recognition (OCR) support on
Mac devices to detect sensitive content in images and apply policies to
protect these images.

To utilize this feature, Global admin must set up pay-as-you-go billing
to enable OCR. The charge for using OCR is \$1.00 for every 1,000 items
scanned.

***Ref:***
<https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=392840>

### Mid-May 2024- MTO in Microsoft Teams

MTO capabilities in MS Teams cover search, chat, calling, meetings,
content sharing, and facilitating collaboration across tenant
boundaries.

***Ref:***
<https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC711026>



## Retirements:

### May 2024- Retirement of the ApplicationImpersonation Role Based Access Control (RBAC) Role in Exchange Online. 

Starting May 2024, Microsoft will block the assignment of the
ApplicationImpersonation role in Exchange Online to accounts.

**Solution:** To comply with these upcoming changes, apps must undergo
an App Registration, utilize Application permissions (not Delegated),
and implement secure credentials for access.

***Ref:***
<https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-rbac-application-impersonation-in-exchange-online/ba-p/4062671>

### May 2024 -- Custom Script Settings Removal from OneDrive and SharePoint Web 

The Custom Script setting in OneDrive and SharePoint web will be removed
in early-May 2024. After that, users cannot change the look, feel, and
behavior of sites and pages to meet their organizational objectives or
individual needs.

**Proactive step:** A new PowerShell command property
*DelayDenyAddAndCustomizePagesEnforcement*, has been introduced to delay
the change to custom script set on the Tenant until mod-November 2024.

Set-SPOTenant DelayDenyAddAndCustomizePagesEnforcement \$True

**Note:** This property is available in the SharePoint Online Management
Shell version 16.0.24524.12000, or above.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC714186>



### May 1, 2024: Azure Information Protection Add-in for Office Retirement

From May 1st, 2024, AIP Unified Labeling add-in permanently disabled in
Office.

**Solution:** If you are using AIP Add-in for Office, you can use
<playbook>(https://microsoft.github.io/ComplianceCxE/playbooks/AIP2MIPPlaybook/)
to plan and execute the transition to built-in labeling in Office apps.

***Ref:***
<https://techcommunity.microsoft.com/t5/security-compliance-and-identity/retirement-notification-for-the-azure-information-protection/ba-p/3791908>

### May 1, 2024- Legacy PowerBI Apps Retirement

Starting May 1, 2024, legacy Power BI apps (pre-audiences) will no
longer receive support. While these apps may continue to function, they
will no longer receive technical assistance beyond May 2024.

**Solution:** Upgrade legacy Power BI apps directly from the workspace
your app is in or from the **Update app** option in the authoring view.

***Ref:***
<https://powerbi.microsoft.com/en-us/blog/announcing-the-retirement-of-legacy-power-bi-apps-pre-audiences/>

### May 1, 2024 - Retirement for Risk-Based Policies in Entra ID Protection

Beginning May 1, 2024, the creation of new legacy user risk policies or
sign-in risk policies in Entra ID Protection will no longer be
supported.

**Solution:** To create and enable new risk-based policies, please
utilize Conditional Access.

***Ref:***
https://techcommunity.microsoft.com/t5/microsoft-entra-blog/what-s-new-in-microsoft-entra/ba-p/3796391

### Mid-May 2024- Retirement of Entity-based Contextual Outlook Add-ins

After retirement, contextual add-ins won\'t detect entities in mail
items to perform tasks. Support for Microsoft add-ins reliant on this,
like Bing Maps, Action Items, and Suggested Meetings, will be
discontinued.

**Solution:** You can configure add-in with regular expression rules as
an alternative solution.

***Ref:***
<https://devblogs.microsoft.com/microsoft365dev/retirement-of-entity-based-contextual-outlook-add-ins/>

### May 31, 2024 - Test Base for Microsoft 365 Retirement

Microsoft is retiring Test Base, the platform crucial for data-driven
application testing worldwide. As of May 31, 2024, all customer
environments and associated data will undergo permanent deletion.

***Ref:***
<https://techcommunity.microsoft.com/t5/windows-it-pro-blog/test-base-for-microsoft-365-end-of-life-announcement/ba-p/4094588>

## Enhancements:

### Early May 2024- Microsoft SharePoint Document Libraries: Improved Version History Controls (Public Preview)

Microsoft is introducing new version controls to assist tenant and site
admins, as well as document library owners, in reducing storage
consumption caused by low-value file versions. With this update, admins
can configure two version history settings.

1.  Automatic Mode: This mode automatically expires both new and
    existing versions based on their age and the probability of
    restoration.

2.  Manual Mode: In this mode, admins can set time-based version
    expiration and count limits for both new and existing versions
    according to their preferences.

Admins can opt into the Public Preview by running the SharePoint Online
Management PowerShell cmdlet.

Set-SPOTenant -EnableVersionExpirationSetting \$true

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC789209>

### Mid-May 2024- Global Reader Role for Teams Devices in Teams Admin Center 

The Global reader role in Microsoft 365 provides admins with the ability
to view all administrative features and settings without the ability to
edit or modify them. With this update, Global readers will now have
read-only access to the Teams devices section within the Teams admin
center.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC711015>

### Late May 2024- Microsoft Purview: New logs for audit activities

Microsoft Purview will now log activities such as submitting an Audit
search query, viewing and exporting Audit logs, and deleting search
history within the Purview Audit feature.

Preview available from May 2024 and Rollout starts from June 2024.

***Ref:***
<https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=385346>

## Action Required:

### May 17, 2024- MSCommerce PowerShell Module Requires to Update 

Microsoft recently released MSCommerce PowerShell module 2.2 version
with critical security updates. Starting May 17, 2024, all previous
versions of the module will not work.

**Solution:** Users must install the new version to manage self-service
purchases and trials.

Note: Existing policies will remain valid, but new changes require the
updated module.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC767477>


## June 2024

## New Features

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

### June 2024- MS Teams: New Controls on who can Download Meeting Transcript

Administrators can restrict permissions for downloading meeting
transcript files to specific security groups. Additionally, Microsoft
updates the default transcript permissions: only owners (the recording
initiator or organizer) can download and delete the transcript file,
while participants can only view it.

***Ref:***
<https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=332800>

### Mid-June 2024 - New & Improved Design for Microsoft 365 Admin Center Usage Report

The Microsoft 365 admin center Usage report Overview page has been
revamped for improved navigation of vital usage insights. The redesign
includes new metrics like enabled and active users, user state
compositions (e.g., distinguishing first-time from returning users),
storage by product, and key usage metrics for Microsoft 365 products.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC692467>

##Retirements

### June 2024- Voicemail: Retirement of Automatic activation of OOF greetings based on OOF Calendar events

The voicemail feature, which automatically activates an out-of-office
greeting based on an out-of-office event in the Outlook calendar, will
be retired in early June 2024.

Solution: To manage their out-of-office greetings, users can utilize two
available options within the Teams client by navigating to Settings -\>
Calls -\> Configure Voicemail:

1.All the time
2.When I have an Outlook auto reply

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC727450>

### June 30, 2024- Azure AD Graph API Retirement

The initial phase of Azure AD Graph API retirement begins on June 30,
2024. Entra ID apps created after this date and trying to use the Azure
AD Graph API will face errors. Applications that are created *before
June 30, 2024* will not be impacted at this stage.

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-entra-blog/important-update-azure-ad-graph-api-retirement/ba-p/4090534>


##Existing Functionality Changes

### Early-June 2024- Teams Meeting Recordings will be Saved in Organizer's OneDrive

After this rollout, Teams meeting recordings will be stored in
organizer's OneDrive instead of the person who initiates the recording.

Admins can temporarily override this rollout through the PowerShell
policy *TeamsRecordingRollOutPolicy*.

***Ref:***
<https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC772558>


### June 30, 2024 -- AllowMeetingRegistration in Set-CsTeamsMeetingPolicy will not work

Microsoft Teams is phasing out the \'Add registrations to meetings\'
feature in favor of the new \'Webinar\' meeting type. Consequently,
Teams Admins won\'t be able to assign the *"-AllowMeetingRegistration*"
policy to new users.

After June 30th, 2024, users with this policy will no longer be able to
create new \'meetings with registration\'.

**Solution:** Users can create a webinar using the new 'Webinar' meeting
type available in the 'New Meeting' drop down in Teams Calendar.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC762511>


## July 2024

##Retirements

### July 1, 2024- Classic Teams End of Support

Beginning July 1, 2024, classic Teams will no longer receive support.
Users using classic Teams will receive in-app notifications indicating
the end of support. These notifications can be dismissed but will
reappear at intervals.

Note: The end of availability for the classic Teams client starts July
1, 2025.

**Solution:** Upgrade to new Teams.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783985>

### July 01, 2024- Stream Mobile App Retirement

Starting July 01, 2024, Microsoft is retiring the Stream Mobile App.
Users can switch to using the OneDrive and Microsoft 365 mobile apps
instead. However, it\'s important to note that if the block download
policy is enabled in OneDrive, users will only be able to play videos
online.

***Ref:***
<https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC789607>


### July 01, 2024 - SharePoint Add-in Retirement 

As part of SharePoint add-in retirement, starting July 01, 2024, you
can't install them from public marketplace. SharePoint Add-Ins will stop
working for new tenants as of November 1, 2024, and they will be fully
retired as of April 2nd, 2026.

**Solution**: Admins can run the Microsoft 365 Assessment
tool to scan their
tenants for SharePoint Add-In usage.

***Ref***:
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865>

### July 1, 2024 - Retirement for Risk-Based Policies in Entra ID Protection

Starting July 1, 2024, existing legacy user risk policies or sign-in
risk policies in Entra ID Protection will become uneditable.

**Solution:** To modify them, please migrate them to Conditional Access.

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-entra-blog/what-s-new-in-microsoft-entra/ba-p/3796391>


### July 2024- Cloud Discovery Anomaly Detection Policy Retirement

Microsoft retiring the \"Cloud Discovery anomaly\" support from
Microsoft Defender for Cloud Apps by July 2024 due to high rate of false
positive alerts.

**Solution:** You can use the \"*App discovery policy*\" and create
dedicated policies, under \"*Trigger a policy match if all the following
occur on the same day*\" set the filters accordingly.

***Ref:***
<https://learn.microsoft.com/en-us/defender-cloud-apps/cloud-discovery-anomaly-detection-policy>

Note: Similarly, "[Investigation priority score
increase](https://learn.microsoft.com/en-us/defender-cloud-apps/tutorial-ueba)"
support from Microsoft Defender for cloud apps will be retired from July
2024.

##Enhancements

### Mid-July 2024- New cmdlet for Content Explorer

Currently, the Content Explorer Export feature has a limitation of
exporting data only after drilling down to a specific location. With
this update, admins can use a new cmdlet,
***Export-ContentExplorerData***, to export all rows of data for the
content on the Content Explorer.

Note: The new cmdlet is available in Security & Compliance
PowerShell.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC698421>

## Existing Functionality Changes

### Mid-July 2024: View Websites in New Teams Client 

From July 2024, Microsoft Teams will no longer support loading websites
within the new Teams client when using the Website tab. Instead, the
Website tab will open in a new browser tab.

**Note**: This update won't affect EDU customers.

***Ref:***
<https://devblogs.microsoft.com/microsoft365dev/upcoming-updates-to-loading-websites-in-teams-tabs>

##Action Required

### July 10, 2024 -- Intune: Migrate Classic Conditional Access Policies

In the transition from Azure AD Graph to MS Graph, Microsoft is shifting
the Intune Company Portal infrastructure to MS Graph. Admins are
required to migrate classic Conditional Access policies to the new by
July 10, 2024, to ensure uninterrupted functionality.

If the policies are not migrated, users can't enroll new devices or make
non-compliant devices compliant via the Company Portal.

**Solution:** Migrate from a classic policy for uninterrupted service.

***Ref:***
<https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC781581>

### July 10, 2024- Microsoft Intune: Update to the latest Company Portal for All Platforms

As part of an Intune Company Portal infrastructure update, users must
update to the minimum Company Portal app version by July 10, 2024, or
lose access to the app.

**Proactive step:** Notify your users to update to the latest Company
Portal version prior to July 10, 2024.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783213>


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

### Oct 01, 2024- Classic Teams in VDI End of Support

The end of support for the classic Teams client in VDI starts October 1,
2024, and the end of availability for the classic Teams client in VDI
starts July 1, 2025.

***Ref:***
<https://learn.microsoft.com/en-us/MicrosoftTeams/new-teams-vdi-requirements-deploy>


### **Oct 14, 2024 -- Office 2016 End of Support** 

After Office 2016 reaches its end of support, Microsoft no longer
provides technical support, bug fixes, and security fixes for
vulnerabilities that are discovered

**Solution**: Microsoft recommend upgrading to Microsoft 365 E3, which
comes with Microsoft 365 Apps.

***Ref***:
<https://learn.microsoft.com/en-us/deployoffice/endofsupport/plan-upgrade-older-versions-office>

### Oct 23, 2024- Classic Teams Desktop App End of Availability

Beginning on October 23, 2024, the classic Teams desktop app will no
longer be available for Windows 7, 8, 8.1, and Mac OS Sierra (10.12).

Starting July 1, 2025, classic Teams desktop app will reach end of
availability for all users

**Solution:** Users need to update their OS, or they can use Teams web
app (on supported browser) as an alternative.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783985>

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

### Jan 01, 2025- External Recipient Rate Limit in Exchange Online

Exchange Online will begin enforcing an external recipient rate (ERR)
limit of 2000 recipients in 24 hours. This restriction will be
applicable to the cloud-hosted mailboxes of all newly created tenants.

For existing tenants, this limit will be enforced in the second half of
2025.

Note: Exchange Online enforces a Recipient Rate limit of
10000 recipients for cloud-hosted mailboxes. The 2000 ERR limit will
become a sublimit within this 10000 Recipient Rate limit.

***Ref:***
<https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733>


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

### Mar 30, 2025- Azure AD and MSOnline PowerShell Modules may Stop Working 

Microsoft has officially deprecated the Azure AD and MSOnline PowerShell
modules Mar'24. However, they will remain functional until March 30,
2025, with support limited to critical security fixes.

**Note:** Only MSOnline versions 1.1.166.0 (2017) and later are
guaranteed to function as expected.

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-entra-blog/important-update-deprecation-of-azure-ad-powershell-and-msonline/ba-p/4094536>

### H2 2025- External Recipient Rate Limit in Exchange Online

In the second half of 2025, Exchange Online will start enforcing an
external recipient rate (ERR) limit of 2000 recipients within a 24-hour
period for all existing tenants. This restriction was already
implemented for all newly created tenants in January 2025.

[Note:]{.underline} Exchange Online enforces a Recipient Rate limit of
10000 recipients for cloud-hosted mailboxes. The 2000 ERR limit will
become a sublimit within this 10000 Recipient Rate limit.

***Ref:***
<https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733>

### July 1, 2025- Classic Teams Desktop App End of Availability

Starting July 1, 2025, classic Teams desktop app will reach end of
availability for all users irrespective of OS.

[Note:]{.underline} From Oct 23, 2024, classic Teams desktop app on
Windows 7,8,8.1 and Mac OS Sierra (10.12) will reach end of
availability.

**Solution:** Users need to switch to new Teams, or they can use Teams
web app (on supported browser) as an alternative.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783985>

### Sep 2025- Basic Auth for Client Submission (SMTP AUTH) Retirement in Exchange Online

Exchange Online will permanently remove support for Basic authentication
with Client Submission (SMTP AUTH) in September 2025.

**Solution:** You can start to use OAuth with Client Submission (SMTP
AUTH).

***Ref:***
<https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-retire-basic-auth-for-client-submission-smtp/ba-p/4114750>

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

### Apr 02, 2026- SharePoint Add-in Retirement 

SharePoint Add-Ins will stop working for existing tenants from April
2nd, 2026.

**Solution:** Admins can run the [[Microsoft 365 Assessment
tool]{.underline}](https://aka.ms/assessment/addinsacs) to scan their
tenants for SharePoint Add-In usage.

***Ref:***
[[https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865]{.underline}](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865)

### Apr 02, 2026- Azure ACS Retirement in Microsoft 365 

After April 2, 2026, existing tenants using Azure ACS for custom or
third-party app access in SharePoint Online will no longer function due
to its retirement.

**Solution:** Admins can utilize the Microsoft 365 Assessment tool to
scan the tenants for any usage of Azure Access Control Service (ACS) and
migrating from Azure ACS to Microsoft Entra
ID.

***Ref:***
<https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/retirement-announcement-for-azure-acs>


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
