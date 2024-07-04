# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.

Discover the **key changes, deprecations**, and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

Here is a list of changes categorized by month and year.

- July 2024 (New Features: 4, Retirements: 9, Enhancements: 2, Existing Functionality Changes: 3, Action Required: 4)
- Aug 2024 (Attention needed: 12)
- Sep 2024 (Attention needed: 5)
- Q4-2024 (Attention needed: 7)
- 2025 (Attention needed: 13)
- 2026 (Attention needed: 9)





## July 2024

New Features: 4 | Retirements: 9 | Enhancements: 2 | Existing Functionality Changes: 3 | Action Needed: 4

## New Features

### July 2024 – Microsoft will Require MFA for All Azure Users

Starting in July 2024, all users signing into the Azure portal, CLI, PowerShell, or Terraform to administer Azure resources will be required to use MFA (Multi-Factor Authentication).  

**Note:** The enforcement will begin with a gradual rollout for the Azure portal by early July 2024. After the portal rollout is complete, a similar gradual rollout will start for CLI, PowerShell, and Terraform. 

***Ref:*** 
<https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/microsoft-will-require-mfa-for-all-azure-users/ba-p/4140391>  

### Early-July 2024 - Adaptive Protection + Conditional Access in General Availability

The Adaptive Protection integrated with Conditional Access, currently in public preview, will become generally available from early July 2024. After this rollout, you will be able to set up or view Conditional Access policies with the Insider Risk Condition in Purview > *Insider risk management > Adaptive Protection.*

**Note:** 

- With this rollout, Microsoft also changes the default Insider Risk Conditional Access policy to block elevated risk users *from all Microsoft 365 applications instead of all applications*. If you configured the default Insider Risk Conditional Access policy during the public preview, your policy would remain unchanged.

- Also, you need an Entra ID P2 license to use Adaptive Protection integrated with Conditional Access policies.

***Ref:*** 
<https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC802699>


### Mid-July 2024 - Automatically Hide Inactive Channels in Microsoft Teams

Microsoft Teams will automatically identify and hide channels that you haven't interacted with recently, starting mid-July 2024 (Targeted release). Once hidden, you'll receive a notification that says, "We're hiding some inactive channels for you." 
This feature is ON by default. If you want to keep all the channels visible, just navigate to Teams > Settings > Chats and channels > Hide inactive channels and toggle it off.

**Note:** Users with EDU licenses assigned will not receive this change.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC804771>
###
### Mid-July 2024 – Microsoft Teams: Custom Emoji and Reactions

Users will be able to add their own custom emojis and reactions by uploading an image or GIF file starting from mid-July 2024. The newly added emojis will be accessible to all users within the organization. An organization can have up to 5000 custom emojis. 

Admins can turn off this feature or restrict which users can create new emojis via the Teams Admin Center. 

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC795750>

## Retirements

### July 01, 2024 - SharePoint Add-in Retirement    

As part of SharePoint add-in retirement, starting July 01, 2024, you can’t install them from public marketplace. SharePoint add-Ins will stop working for new tenants as of November 1, 2024, and they will be fully retired as of April 2nd, 2026.   

**Solution**: Admins can run the [Microsoft 365 Assessment tool](https://aka.ms/assessment/addinsacs) to scan their tenants for SharePoint Add-In usage.   

***Ref***: 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865> 

### July 1, 2024 - Retirement for Risk-Based Policies in Entra ID Protection 

Starting July 1, 2024, existing legacy user risk policies or sign-in risk policies in Entra ID Protection will become uneditable. 

**Solution:** To modify them, please migrate them to Conditional Access. 

***Ref:*** 
<https://techcommunity.microsoft.com/t5/microsoft-entra-blog/what-s-new-in-microsoft-entra/ba-p/3796391> 

### July 1, 2024 - Classic Teams End of Support 

Beginning July 1, 2024, classic Teams will no longer receive support. Users using classic Teams will receive in-app notifications indicating the end of support. These notifications can be dismissed but will reappear at intervals. 

Note: The end of availability for the classic Teams client starts July 1, 2025. 

**Solution:** Upgrade to new Teams. 

***Ref:*** 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783985> 

### July 01, 2024- Stream Mobile App Retirement 

Starting July 01, 2024, Microsoft is retiring the Stream Mobile App. Users can switch to using the OneDrive and Microsoft 365 mobile apps instead. However, it's important to note that if the block download policy is enabled in OneDrive, users will only be able to play videos online. 

***Ref:*** 
<https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC789607> 

### July 2024 - Cloud Discovery Anomaly Detection Policy Retirement 

Microsoft retiring the "Cloud Discovery anomaly" support from Microsoft Defender for Cloud Apps by July 2024 due to high rate of false positive alerts. 

**Solution:** You can use the "*App discovery policy*" and create dedicated policies, under "*Trigger a policy match if all the following occur on the same day*" set the filters accordingly. 

***Ref:***
<https://learn.microsoft.com/en-us/defender-cloud-apps/cloud-discovery-anomaly-detection-policy>  

Note: Similarly, “[Investigation priority score increase](https://learn.microsoft.com/en-us/defender-cloud-apps/tutorial-ueba)” support from Microsoft Defender for cloud apps will be retired from July 2024. 

### Mid-July 2024 - Legacy Outlook Clients Retirement Plan

Microsoft will retire legacy Outlook clients across various platforms, starting mid-July 2024. This change will affect users running outdated versions on iOS, Android, Mac, and Windows Mail and Calendar applications. Beginning mid-August 2024, users with outdated browsers will encounter errors when accessing Outlook on the web.

**Solution:** Switch to the new Outlook for Windows, and update to the latest versions of Outlook on iOS, Android, and Mac.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC801980>

### July 22, 2024 - Microsoft Teams Extended Directory Retirement

Due to low usage, Microsoft will retire the extended directory (Preview) in Teams starting July 22, 2024. After retirement, users won't be able to search external users by name or establish 1:1 group chat with them. Chats initiated with an Extended Directory contact will continue to function as long as external access policies are enabled..

**Solution:** Instead, admins can use Teams connect chat supported by external access.

***Ref:*** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC805189>







### July 22, 2024 - SharePoint News Connectors Retirement in Microsoft Teams

The SharePoint news connector is going to be retired. Starting July 22, 2024, users will not be able to create SPO news connectors and the existing ones will retire by August 26, 2024.

**Solution:** Move to alternatives like Viva Connections News notifications, Viva Amplify, or Teams Workflow. 

***Ref:*** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC803508>



### July 29, 2024 - Retirement of "Remove-SPOExternalUser" PowerShell Cmdlet

Microsoft plans to retire the SharePoint Online PowerShell cmdlet "Remove-SPOExternalUser" starting July 29, 2024. This decision aims to enhance security, streamline scope and permissions for external users.

**Solution:** Admins can use the "Remove-MgUser" cmdlet for Entra ID user management. 

**Ref:**
<https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC806103>

## Enhancements 

### July 2024 - Breakout Rooms Support for Microsoft Teams Rooms on Windows

With breakout room support, Teams Rooms on Windows can be seamlessly integrated into breakout sessions and transitioned in and out of the main room. 

***Ref:*** 
<https://www.microsoft.com/en-in/microsoft-365/roadmap?&filters=&searchterms=95680>  

### Mid-July 2024- New Cmdlet for Content Explorer 

Currently, the Content Explorer Export feature has a limitation of exporting data only after drilling down to a specific location. With this update, admins can use a new cmdlet, ***Export-ContentExplorerData***, to export all rows of data for the content on the Content Explorer. 

Note: The new cmdlet is available in Security & Compliance PowerShell. 

***Ref:*** 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC698421>  

## Existing Functionality Changes

### July 2024- DLP Admin can Rename the existing DLP Policies 

Starting from July 2024, DLP Admins can rename existing policies or rules without recreating them from scratch. 

***Ref:*** 
<https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=95680>  

### Mid-July 2024: View Websites in New Teams Client  

From July 2024, Microsoft Teams will no longer support loading websites within the new Teams client when using the Website tab. Instead, the Website tab will open in a new browser tab.  

**Note**: This update won’t affect EDU customers.  

***Ref:*** 
<https://devblogs.microsoft.com/microsoft365dev/upcoming-updates-to-loading-websites-in-teams-tabs/> 

### Late-July 2024 - Changes to OneDrive Shared Folder Experience

Currently, opening a shared folder in OneDrive directs users to the sharer's OneDrive view. Starting late July 2024, opening a shared folder will direct users to the "People" view section in their own OneDrive. Alternatively, users can view the shared folder directly from the "People" section of their OneDrive.

***Ref**:*
<https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC806523>

## Action Required 

### July 10, 2024 – Intune: Migrate Classic Conditional Access Policies 

In the transition from Azure AD Graph to MS Graph, Microsoft is shifting the Intune Company Portal infrastructure to MS Graph. Admins are required to migrate classic Conditional Access policies to the new by July 10, 2024, to ensure uninterrupted functionality. 

If the policies are not migrated, users can’t enroll new devices or make non-compliant devices compliant via the Company Portal. 

**Solution:** Migrate from a classic policy for uninterrupted service. 

***Ref:*** 
<https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC781581> 

### July 10, 2024- Microsoft Intune: Update to the latest Company Portal for All Platforms
As part of an Intune Company Portal infrastructure update, users must update to the minimum Company Portal app version by July 10, 2024, or lose access to the app. 

**Proactive step:** Notify your users to update to the latest Company Portal version prior to July 10, 2024. 

***Ref:*** 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783213> 

### Late-July 2024 - New Outlook for Windows will Open Web Links in Edge Side-by-side

Starting late July 2024, the New Outlook for Windows will open web links in Microsoft Edge side-by-side, like how this feature works for Teams chat web links. This update applies to Outlook web links from Azure Active Directory accounts and Microsoft accounts. Importantly, links will open in Microsoft Edge even if it is not the system default browser in Windows.

**Solution:** To manage this change and ensure web links open in users’ preferred browser, you will need to configure the "Choose which browser opens web links" policy. This policy can be configured through the [Microsoft 365 Apps admin center.](https://config.office.com/)

***Ref:***
<https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC803892>

### Late-July 2024 - Replace COM Add-ins with Web add-ins in New Outlook for Windows

Microsoft is encouraging users to transition to the new Outlook for Windows. During this transition, users will be prompted to consent to installing equivalent web add-ins for COM add-ins (which are not supported in the new Outlook). If you need add-ins in your new Outlook for Windows, you need to install the equivalent web add-ins using the prompt. This consent process will begin rolling out in late July 2024.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC804770>

## August 2024

## New Features

### Early-August 2024 - Public Preview of Progressive Alert Scoring

Microsoft is rolling out a new feature -" Progressive alert scoring" in public review, starting in early August 2024. Currently, user activities that could potentially result in data security incidents will be assessed once every 24 hours. After this rollout, the assessment of user activities will be done more frequently within a 24- hour period, along with alert insights.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC707653>

### Mid-Aug 2024 - Outlook: Folder/Subfolder Recursive Search 

With this feature, when a user searches for content in an Outlook folder, all its subfolders are also searched, and the results are displayed. 

***Ref:***  <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC802699>






### Aug 2024 - New Authentication Method "QR Code Sign-in"

Microsoft is introducing a new authentication method, "QR code sign-in," in a private preview by August 2024. This feature allows users on mobile devices (Android/iOS/iPadOS) to authenticate using a QR code and PIN.

**Ref:**
<https://techcommunity.microsoft.com/t5/microsoft-entra-blog/what-s-new-in-microsoft-entra-june-2024/>

## Retirements

### Aug 5, 2024 - Microsoft 365 Groups Connectors Retirement

Microsoft 365 group connectors, which deliver notifications from online tools and services to group emails, will no longer be available for New Outlook for Windows & Outlook on the Web users from Aug 5, 2024. Existing group connectors will not receive any updates after this date.

**Solution**: Use the Power Automate app as an alternative to receive notifications and updates on Group email.

**Ref:**
<https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC798683>

### Aug 20, 2024 – All Contents from Stream (Classic) will be Deleted 

With the retirement of Stream Classic on April 15, 2024, all content will be deleted starting August 20, 2024. 

**Solution:** Migrate your Stream (Classic) content to Stream (on SharePoint) to ensure continued access. 

***Ref:*** 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC764452> 

### August 26, 2024 – Existing SharePoint News Connectors Retirement

All existing SPO news connectors will be retired by August 26, 2024. Also, users can’t create new SPO news connectors from July 22, 2024.

**Solution:** Move to alternatives like Viva Connections News notifications, Viva Amplify, or Teams Workflow.

***Ref:***
<https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC803508>

### Aug 30, 2024 - Intune Ending Support for Android Device Administrator on GMS Access Devices

After Intune ends support for Android device administrator, devices with access to GMS will be impacted in the following ways: 

- Users will not be able to enroll devices with Android device administrator. 
- Intune technical support will no longer support these devices. 

***Ref***: 
<https://techcommunity.microsoft.com/t5/intune-customer-success/microsoft-intune-ending-support-for-android-device-administrator/ba-p/3915443> 

### Aug 31, 2024 - Retiring Support for Older Browsers by August 31, 2024

Microsoft Power BI is retiring support for older browsers on September 1, 2024. To avoid interruptions in functionality, users should upgrade their browsers by August 31, 2024.

**Ref:** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC802696>


### Aug 31, 2024 - Azure AD Graph API Retirement

The initial phase of Azure AD Graph API retirement begins on Aug 31, 2024. Entra ID apps created after this date and trying to use the Azure AD Graph API will face errors. Applications that are created *before Aug 31, 2024,* will not be impacted at this stage. 

***Ref:*** 
[https://techcommunity.microsoft.com/t5/microsoft-entra-blog/what-s-new-in-microsoft-entra-june-2024/ba-p/3796387](https://techcommunity.microsoft.com/t5/microsoft-entra-blog/what-s-new-in-microsoft-entra-june-2024/ba-p/3796387#:~:text=Important%20Update%3A%20Azure%20AD%20Graph%20Retirement)

## Enhancements

### Aug 2024- Microsoft SharePoint Document Libraries: Improved Version History Controls

Microsoft is introducing new version controls to assist tenant and site admins, as well as document library owners, in reducing storage consumption caused by low-value file versions. With this update, admins can configure two version history settings.  

- ***Automatic Mode:*** This mode automatically expires both new and existing versions based on their age and the probability of restoration.  
- ***Manual Mode:*** In this mode, admins can set time-based version expiration and count limits for both new and existing versions according to their preferences.  

Admins can opt into the Public Preview by running the SharePoint Online Management PowerShell cmdlet.  

` `Set-SPOTenant -EnableVersionExpirationSetting $true   

Note: Public preview for this feature was released in May 2024, and the General Availability is scheduled for August 2024, 

***Ref:*** 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC789209> 

### Mid-August 2024 - Audit: New Cloud Policy Service Audit Logs for Policy Changes



Microsoft will soon integrate cloud policy service into Microsoft Purview Compliance portal. Admins can search and review Microsoft 365 cloud policy changes (Create, update, delete) using unified audit logs from mid-August 2024. These logs will be available to **Purview Audit Standard** users.

***Ref:*** <https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC789309>

### Mid-August 2024 - SharePoint eSignature Service in Canada, the UK, and Selected European Countries

Microsoft's SharePoint eSignature service, initially launched in the US in late November 2023, is now expanding its availability to include users in the UK, Canada, and selected European countries. Starting mid-August 2024, users from these regions will be able to utilize SharePoint online to request eSignatures on PDF documents.

**Ref:**
<https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC800502>

## September 2024

## New Features

### Sep 2024 – Exchange - High Volume Email for Microsoft 365 (General Availability) 

High Volume Email (HVE) is designed for large-scale internal communications, facilitating mass mailing needs.  

Note: In public preview, you can send emails to up to 100k recipients per 24 hours, with a maximum of 2,000 external users. 

***Ref:***
<https://learn.microsoft.com/en-us/Exchange/mail-flow-best-practices/high-volume-mails-m365>  

### Sep 2024 - New "Resources" Category in Microsoft Entra Conditional Access

Microsoft Entra Conditional Access will streamline the "Target resources" assignment by combining the current options "Cloud apps" and "Global Secure Access" into a single category named "Resources."


***Ref:*** 
<https://techcommunity.microsoft.com/t5/microsoft-entra-blog/what-s-new-in-microsoft-entra-june-2024/>



## Retirements

### Sep 30, 2024- Azure Multi-Factor Authentication Server   

Azure MFA Server deployments will no longer service MFA requests, which could cause authentications to fail for your organization.  

**Solution:** Organizations should migrate their users’ authentication data to the cloud-based Azure MFA service    

***Ref:*** 
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-september-2022-train/ba-p/2967454> 

### Sep 30, 2024 – Business Connectivity Services Retirement in Microsoft 365  

Microsoft will retire Business Connectivity Services features in Microsoft 365.   

**Solution**: Microsoft recommends using Power Apps to replace their Business Connectivity Services solutions in SharePoint in Microsoft 365.  

***Ref***: 
<https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-business-connectivity-services-in-microsoft/ba-p/3938773>  
## Existing Functionality Changes

### Sep 2024 - Changes to Phone Call Settings in Entra ID

Entra will relocate phone call settings (custom greetings and caller ID) from the multifactor authentication blade to the voice authentication method within the authentication method policy.

***Ref:*** 
<https://techcommunity.microsoft.com/t5/microsoft-entra-blog/what-s-new-in-microsoft-entra-june-2024/>


## October 2024 

### Oct 01, 2024- Classic Teams in VDI End of Support 

The end of support for the classic Teams client in VDI starts October 1, 2024, and the end of availability for the classic Teams client in VDI starts July 1, 2025. 

***Ref:*** 
<https://learn.microsoft.com/en-us/MicrosoftTeams/new-teams-vdi-requirements-deploy>   

### Oct 23, 2024- Classic Teams Desktop App End of Availability 

Beginning on October 23, 2024, the classic Teams desktop app will no longer be available for Windows 7, 8, 8.1, and Mac OS Sierra (10.12). 

Starting July 1, 2025, classic Teams desktop app will reach end of availability for all users. Also, the “New” label will be removed from the new Teams app by mid-July 2024. 

**Solution:** Users need to update their OS, or they can use the new Teams web app (on supported browser) as an alternative. 

***Ref:***
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783985> 

## November 2024

### Nov 01, 2024- Azure ACS Retirement in Microsoft 365

Microsoft is retiring the use of Azure ACS as auth platform for SharePoint Online. Starting November 1st, 2024, new tenants will not be able use Azure ACS. For existing tenants that currently rely on Azure ACS to provide custom-developed or third-party applications access to SharePoint Online, this functionality will cease to work after April 2, 2026.  

**Solution**: Admins can utilize the Microsoft 365 Assessment tool to scan the tenants for any usage of Azure Access Control Service (ACS) and [migrating from Azure ACS to Microsoft Entra ID](https://aka.ms/retirement/acs/guidance).  

***Ref***:
<https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/retirement-announcement-for-azure-acs>  

### Nov 01, 2024- SharePoint Add-in Retirement  
SharePoint Add-Ins will stop working for new tenants as of November 1, 2024, and they will be fully retired as of April 2nd, 2026.  

**Solution**: Admins can run the [Microsoft 365 Assessment tool](https://aka.ms/assessment/addinsacs) to scan their tenants for SharePoint Add-In usage.  

***Ref***: 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865> 

## December 2024

### Dec 16, 2024 - Delve Web Retirement 

Microsoft retiring Delve on December 16th, 2024. Many Delve features are now available and improved in other Microsoft 365 experiences.  

**Solution:** Key alternatives include: 

- Discover documents: Use Office.com, Office apps, and Profile Cards. 
- View profile data: Utilize Profile Cards, people search on Office.com, and SharePoint search. 
- Edit profile: A new edit profile experience will be released in H2 2024 and can also be edited in SharePoint. 
- Organizational view: Available in the Profile Card and Org Explorer. 
- Favorites: Use favorites on Office.com and OneDrive for similar functionality. 
- Boards: Will not be replaced. 

***Ref***: 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC698136> 
##
## Dec 21, 2024: Intune Ending Support for Android Device Administrators on Devices with GMS Access
Google has decided to phase out Android device administrator management. In response, Microsoft Intune will stop supporting this management type on devices using Google Mobile Services (GMS) starting December 21, 2024.

**Solution:** Stop enrolling devices into Android device administrator and migrate impacted devices to other management methods. 

***Ref:***
<https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC674247>

### End of 2024- Retirement of Mail and Calendar Apps in Windows  

At the end of 2024, Microsoft replacing the Mail and Calendar apps in Windows with the new Outlook for Windows.    

**Solution:** Start trying and testing the new Outlook for Windows.  

***Ref***: 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC590123> 

## 2025 (Attention Needed: 13)

### Jan 01, 2025- External Recipient Rate Limit in Exchange Online 

Exchange Online will begin enforcing an external recipient rate (ERR) limit of 2000 recipients in 24 hours. This restriction will be applicable to the cloud-hosted mailboxes of all newly created tenants. 

For existing tenants, this limit will be enforced in the second half of 2025. 

**Note:** Exchange Online enforces a Recipient Rate limit of 10000 recipients for cloud-hosted mailboxes. The 2000 ERR limit will become a sublimit within this 10000 Recipient Rate limit. 

***Ref:*** 
<https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733> 

### Early 2025 - MFA Enforcement for CLI, Azure PowerShell, IaC Tools

As part of enforcing MFA for all Azure users, MFA enforcement for Azure Command Line Interface (CLI), Azure PowerShell, and Infrastructure as Code (IaC) tools will gradually be introduced to all tenants starting in early 2025.

***Ref:*** 
<https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/update-on-mfa-requirements-for-azure-sign-in/>



### Feb 2025- Removal of the ApplicationImpersonation Role Based Access Control (RBAC) in Exchange Online  

Microsoft is going to remove ApplicationImpersonation Role Based Access Control (RBAC) role and its feature set from Exchange Online. 

***Ref:*** 
<https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-rbac-application-impersonation-in-exchange-online/ba-p/4062671> 

### Feb 01, 2025- Azure Key Vault: Soft-delete Will be Enabled on All Key Vaults**    

Soft Delete preserves deleted key vaults and secrets for up to 90 days, enabling customers to restore them through a self-serve process.   

***Ref:*** <https://learn.microsoft.com/en-us/azure/key-vault/general/soft-delete-change> 

### Feb 22, 2025- Viva Topics Retirement 
Viva Topics will be discontinued on February 22, 2025, and Microsoft will no longer pursue new feature enhancements for the platform. 

Existing Topic pages will transition to standard SharePoint pages. Users can edit and publish updates as other SharePoint pages. AI-generated Topic pages will no longer be accessible. 

***Ref:*** 
<https://learn.microsoft.com/en-us/microsoft-365/topics/changes-coming-to-topics> 

### Mar 30, 2025- Azure AD and MSOnline PowerShell Modules may Stop Working
Microsoft has officially deprecated the Azure AD and MSOnline PowerShell modules Mar’24. However, they will remain functional until March 30, 2025, with support limited to critical security fixes.  

**Note:** Only MSOnline versions 1.1.166.0 (2017) and later are guaranteed to function as expected.  

***Ref:*** 
<https://techcommunity.microsoft.com/t5/microsoft-entra-blog/important-update-deprecation-of-azure-ad-powershell-and-msonline/ba-p/4094536>   

### April 2025 - Insider Risk Management- Risk AI Usage

Microsoft plans to introduce a new feature in Insider Risk Management, which will be widely available from April 2025. This feature aims to detect potentially risky use of AI. It includes monitoring activities involving sensitive information in prompts generated by AI assistants, covering both copilots and third-party AI applications.


**Ref:** 
<https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=In%20development&searchterms=394281>

### Apr 02, 2025 – Retirement of Domain Isolated Web Part in SharePoint Framework 

As part of the SharePoint Framework domain isolated web parts retirement, this feature will be turned off for newly created tenants starting from Apr 02, 2025. 

**Note:** From Apr 02, 2026, existing tenants will no longer be able to use this feature. 

***Ref:***
<https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/>  

### H2 2025- External Recipient Rate Limit in Exchange Online 

In the second half of 2025, Exchange Online will start enforcing an external recipient rate (ERR) limit of 2000 recipients within a 24-hour period for all existing tenants. This restriction was already implemented for all newly created tenants in January 2025. 

**Note**: Exchange Online enforces a Recipient Rate limit of 10000 recipients for cloud-hosted mailboxes. The 2000 ERR limit will become a sublimit within this 10000 Recipient Rate limit. 

***Ref:*** 
<https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733> 

### July 1, 2025- Classic Teams Desktop App End of Availability 
Starting July 1, 2025, classic Teams desktop app will reach end of availability for all users irrespective of OS. 

**Note**: From Oct 23, 2024, classic Teams desktop app on Windows 7,8,8.1 and Mac OS Sierra (10.12) will reach end of availability. 

**Solution:** Users need to switch to new Teams, or they can use Teams web app (on supported browser) as an alternative. 

***Ref:*** 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC783985> 

### Sep 2025- Basic Auth for Client Submission (SMTP AUTH) Retirement in Exchange Online 

Exchange Online will permanently remove support for Basic authentication with Client Submission (SMTP AUTH) in September 2025. 

**Solution:** You can start to use OAuth with Client Submission (SMTP AUTH). 

***Ref:*** 
<https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-retire-basic-auth-for-client-submission-smtp/ba-p/4114750> 

### Sep 30, 2025 – Retirement of Managing Authentication Methods in Legacy MFA &SSPR Policy

Starting Oct 2025, Microsoft no longer allow authentication methods to be managed in the legacy MFA and SSPR policies.   

**Solution:** Organizations should use the converged authentication methods policy where methods can be managed centrally for all authentication scenarios including passwordless, MFA and SSPR.   

***Ref:***
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448> 

### Oct 14, 2025- End of Extended Support for Office 2016 & Office 2019   

Office 2016 and Office 2019 extended support ends in 2025. 

**Solution:** You can start to use the latest supported versions. 

***Ref:***
<https://learn.microsoft.com/en-us/lifecycle/products/microsoft-office-2016>

## 2026 (Attention Needed: 9)

### Jan 13, 2026 – End of Extended Support for Microsoft Advanced Threat Analytics 1.x

Microsoft Advanced Threat Analytics (ATA) extended support will be ended on January 13, 2026.   

**Solution**: Updates for Microsoft ATA are available from Microsoft Update or by manual download.   

***Ref:*** 
<https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c> 

### Mar 31, 2026- Deprecation of ‘Require Approved Client App’ Conditional Access Grant    

The Require approved client app control in Azure Active Directory (Azure AD) Conditional Access will be retired and no longer enforced.   

**Solution:** You can make use of the “Require app protection policy” control, which has all the same capabilities   

***Ref:*** 
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448> 
### 
### Apr 02, 2026 – SharePoint 2013 Workflow Retirement

SharePoint 2013 workflows will no longer be supported. 

**Solution:** You can move to Power Automate or other supported solutions. 

***Ref:*** 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC542767> 

### Apr 02, 2026- SharePoint Add-in Retirement
SharePoint Add-Ins will stop working for existing tenants from April 2nd, 2026.   

**Solution:** Admins can run the [Microsoft 365 Assessment tool](https://aka.ms/assessment/addinsacs) to scan their tenants for SharePoint Add-In usage.   

***Ref:*** 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865> 

### Apr 02, 2026 – Azure ACS Retirement in Microsoft 365

After April 2, 2026, existing tenants using Azure ACS for custom or third-party app access in SharePoint Online will no longer function due to its retirement.  

**Solution:** Admins can utilize the Microsoft 365 Assessment tool to scan the tenants for any usage of Azure Access Control Service (ACS) and [migrating from Azure ACS to Microsoft Entra ID](https://aka.ms/retirement/acs/guidance).   

***Ref:*** 
<https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/retirement-announcement-for-azure-acs>  


### Apr 02, 2026 - Retirement of Domain Isolated Web Part in SharePoint Framework 

From Apr 02, 2026, the domain isolated web part feature will be fully retired. Organizations using this feature will receive an error message. 

**Solution:** Update your domain isolated web parts to regular web parts and redeploy them to ensure continued functionality. 

***Ref:*** 
<https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/>  

### July 14, 2026- InfoPath 2013 Client and InfoPath Forms Services in SharePoint Online will be Retired


InfoPath Client 2013 will reach the end of its extended support period on July 14, 2026, and to keep an aligned experience across Microsoft products, InfoPath Forms Service will be retired from SharePoint Online. 

**Solution:** To understand the usage of InfoPath within your organization, you can utilize the [Microsoft 365 Assessment tool](https://aka.ms/assessment/infopath) to scan your tenant and analyze InfoPath usage. If you are currently using InfoPath, you can initiate the migration process to modern alternatives such as Power Apps, Power Automate, or Forms. 

***Ref:*** 
<https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190> 

### Oct 01, 2026- Retirement of Exchange Web Services in Exchange Online 

October 1, 2026, Microsoft will start blocking EWS requests from non-Microsoft apps to Exchange Online. The changes in Exchange Online do not affect Outlook for Windows or Mac, Teams, or any other Microsoft product. 

**Solution**: Migrate your applications to Microsoft Graph to access Exchange Online data and gain access to the latest features and functionality. 

***Ref***: 
<https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-exchange-web-services-in-exchange-online/ba-p/3924440> 

### Oct 01, 2026 – Sign-in Risk Policy and User Risk Policy Retirement from Entra ID Protection

User risk policy or Sign-in risk policy UX in Entra ID Protection (formerly Identity Protection) will be retired on October 1, 2026. 

**Solution:** Migrate Sign-in risk and User risk policies to Conditional Access. 

***Ref***:
<https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/what-s-new-in-microsoft-entra/ba-p/3796395> 

### Oct 13, 2026- Retirement of Microsoft Publisher 

In October 2026, Microsoft will discontinue Publisher in Microsoft 365, with on-premises suite support ending. While support lasts, they're exploring modern alternatives across Word, PowerPoint, and Designer for common Publisher tasks, with updates forthcoming. 

***Ref:*** 
<https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC716267> 

In conclusion, navigating the ever-evolving landscape of Microsoft 365 requires staying informed about the changes. By proactively adapting to these changes, you can optimize your Microsoft 365 experience, maximize productivity, and effectively plan for the future.

We are committed to keeping this blog updated with the latest information, so stay tuned for upcoming updates.
### <https://blog.admindroid.com/microsoft-365-end-of-support-milestones/>




