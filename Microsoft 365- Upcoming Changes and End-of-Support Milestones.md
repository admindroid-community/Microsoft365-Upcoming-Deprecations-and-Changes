# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. We will shed light on the features and products that are undergoing transformations or bidding farewell. Whether you are a system administrator managing the Microsoft 365 environment or an avid user staying ahead of the curve, this blog will provide you with invaluable insights and actionable recommendations.  
  
Discover the **key changes, deprecations**, and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we'll cover everything you need to make informed decisions and ensure a smooth transition.

## Microsoft 365 Upcoming Changes and Deprecations List:

  
Here is a list of changes categorized by month and year.  

*   August 2025 (Retirements: 7, New Features: 12, Enhancements: 5, Existing Functionality Changes: 8, Action Needed: 3, Retirement Postponed: 1)
*   September 2025 (Retirements: 3, New Features: 9, Enhancements: 7, Existing Functionality Changes: 2, Action Needed: 2)
*   October (Attention Needed: 8)
*   November (Attention Needed: 2)
*   December (Attention Needed: 4)
*   2026 (Attention Needed: 22)

  

## August 2025

## Retirements

### Aug 1, 2025 - Retirement of Organization Data Types in Microsoft Excel

The Organization Data Types in Excel, which allowed users to query Power BI datasets, will be retired on July 31, 2025. Starting August 1,2025, you no longer be able to convert values to new organization data types.

**Solution:** Switch to Power BI for data exploration or use custom Excel add-ins to meet similar data needs.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1107494](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1107494)

### Aug 1, 2025 - The "Monitoring" Feature will Retire from Conditional Access

The Monitoring feature in Conditional Access, which allowed admins to assess the impact of their policies, will be retired completely on August 1, 2025, due to low usage. After this date, the feature will no longer be available in the Conditional Access interface.

**Solution:** Use Conditional Access per-policy reporting and the Insights and Reporting dashboard to analyze and monitor policy effectiveness.

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/what%E2%80%99s-new-in-microsoft-entra-%E2%80%93-june-2025/4352579](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/what%E2%80%99s-new-in-microsoft-entra-%E2%80%93-june-2025/4352579)

### Aug 2025 - Retirement of Classic e-Discovery (Premium) in Microsoft Purview

Starting August 2025, Microsoft will retire Classic eDiscovery (Premium) from the Microsoft 365 Purview portal.

**Solution:** Transition to the new unified eDiscovery for faster and improved search and investigation capabilities.  

**_Ref:_** [https://learn.microsoft.com/en-us/purview/ediscovery-legacy-retirement](https://learn.microsoft.com/en-us/purview/ediscovery-legacy-retirement)

### Early-Aug 2025 - Retirement of Microsoft Project for the Web and Project in Teams

Microsoft Project for the web and Project in Teams will be retired in early August 2025. Users will be redirected to Planner for the web and Planner in Teams, where existing Project features will be integrated to ensure a seamless transition.

**Solution:** Users should migrate Roadmap data to Portfolios and re-pin Projects in Teams tabs using Planner.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1068905](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1068905)

### Aug 11, 2025 - Retirement of Power BI Cognitive Services and Azure Machine Learning Features

Microsoft is phasing out the Cognitive Services and Azure Machine Learning features in Power BI. Starting August 15, 2025, users will no longer be able to create new models using these services.

**Solution:** Transition to using Auto ML in Microsoft Fabric for supported AI and machine learning scenarios.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1124567](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1124567)

### Mid-Aug 2025 - Deprecation of Speaker Coach in Microsoft Teams

Speaker Coach in Microsoft Teams offers private, personalized feedback on speaking performance during meetings and provides a summary afterward. The feature will be retired starting mid-August 2025 across Teams for Windows, Mac, and the web.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1101903](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC1101903)

### Aug 30, 2025 - Client Access Rules Deprecation in Exchange Online

Client Access Rules (CARs), used to control access to Exchange Online services based on various conditions, will be deprecated by September 1, 2025.

**Solution:** Migrate to Conditional Access policies with Continuous Access Evaluation (CAE) enabled before August 30, 2025, to benefit from more advanced and flexible access control.

**_Ref_**: [https://techcommunity.microsoft.com/blog/exchange/update-on-client-access-rules-deprecation-in-exchange-online/4354809](https://techcommunity.microsoft.com/blog/exchange/update-on-client-access-rules-deprecation-in-exchange-online/4354809)

## New Features

### Aug 2025 - Microsoft Purview Launches AI-Powered Data Security Investigations Solution

Microsoft Purview Data Security Investigations (DSI) is an AI-driven solution designed to help security teams identify, analyze, and mitigate data risks. It enables deep content analysis, visualizes correlations, and supports policy refinement within a unified experience.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1047912](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1047912)

### Aug 2025 – Microsoft Purview DLP to Restrict Copilot from Processing Labeled Emails

Starting August 2025, Microsoft Purview Data Loss Prevention (DLP) will prevent Microsoft 365 Copilot from processing emails that contain sensitivity labels. The feature enhances data protection by using DLP policies to detect sensitivity labels and block access within Copilot chat experiences.

**_Ref_**: [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1088731](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1088731)

### Early-Aug 2025 - Insider Risk Management- Risky AI Usage

New detections in Insider Risk Management will be generally available, enabling admins to identify risky AI activity, such as sensitive prompts, risky intents, and AI-generated sensitive content. This applies to M365 Copilot, Copilot Studio, and ChatGPT Enterprise, contributing to Adaptive Protection risk levels.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC947048](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC947048)

### Early-Aug 2025 - SharePoint Online Library Permissions with Sensitivity Labeling

With this update, SharePoint Online document library owners can apply a sensitivity label directly at the library level. This label is automatically applied to any unprotected or unlabeled files.

This makes it easier to label files in bulk across your organization and ensures consistent protection. Also, when someone downloads a file from the labeled library, the file keeps the site’s permissions, even outside SharePoint.

**_Ref_**: [https://learn.microsoft.com/en-us/purview/sensitivity-labels-sharepoint-extend-permissions](https://learn.microsoft.com/en-us/purview/sensitivity-labels-sharepoint-extend-permissions)

### Early-Aug 2025 - Enhanced eDiscovery Premium APIs

eDiscovery APIs are being upgraded from Beta to V1, bringing enhanced capabilities. The updates include new parameters and export formats that boost search accuracy, offer richer insights, and simplify workflows.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=495458](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=495458)

### Early-Aug 2025 - Microsoft Teams to Support Silent Test Calls for Network Readiness

Microsoft Teams will allow IT admins to run silent call simulations to proactively test network readiness and detect issues early. Available for Windows and Mac desktops, this feature requires a Teams Premium license.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1089323](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1089323)

### Mid-Aug 2025 – New Delegation Feature in Viva Engage

Microsoft Viva Engage is introducing a new delegation feature that allows admins to assign others to manage Pulse surveys on their behalf. Delegates will be able to create, send, and manage surveys, while the original owner retains full visibility and ownership.

This feature is enabled by default, but admins can customize access via feature access policies in the Microsoft 365 admin center.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1053652](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1053652)

### Mid-Aug 2025 – Apple and Google Sign-in Support for Teams Web Users

Microsoft Teams on the web will introduce a new sign-in experience in mid-August 2025 that allows users to log in using Apple or Google credentials. Users will see two new options, “Continue with Apple” and “Continue with Google.” These options allow users to sign in to or create a personal Microsoft account using their Apple or Google login information. The rollout will begin with a limited set of Teams web users.  

**_Ref_**: [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/what%E2%80%99s-new-in-microsoft-entra-%E2%80%93-june-2025/4352579](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/what%E2%80%99s-new-in-microsoft-entra-%E2%80%93-june-2025/4352579)

### Mid-Aug 2025 - Microsoft Places Management Web portal

A new centralized Microsoft Places web portal is launching, giving admins an easier way to manage buildings, floors, rooms, and desks. Instead of using PowerShell, admins can now manage these spaces via the Places app or web interface, featuring a hierarchical space view, advanced filters, and more. The portal is on by default and accessible to Global admins, Exchange admins, and the Places Admin role.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1122163](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1122163)

### Mid-Aug 2025 - New Map-based Desk Booking Experience in Microsoft Places

Microsoft Places is rolling out a new map-based experience for reserving desks. Available to Teams Premium users, this feature allows employees to book desks through interactive floor maps, see where colleagues are seated, book partial or multi-day slots, delegate bookings, and enable admin check-ins.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1124563](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1124563)

### Mid-Aug 2025 – Drag and Drop Between Accounts Coming to New Outlook for Windows

The new Microsoft Outlook for Windows adds drag and drop support to attach emails and files between personal or enterprise accounts, improving cross-account productivity. This update also allows attaching content from shared mailboxes or shared folders into another mailbox. Admins can control this capability using the **_ItemsToOtherAccountsEnabled_** parameter in _OWAMailboxPolicy_.

**_Ref_**: [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1104315](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC1104315)

### Late -Aug2025 – IRM Alerts in Microsoft Defender XDR

Microsoft Purview’s Insider Risk Management (IRM) data will integrate with Microsoft Defender XDR, enabling comprehensive investigation and correlation. IRM data will be accessible through the unified alert and incident queue, advanced hunting with KQL queries, Graph API, and Microsoft Sentinel. This feature will roll out to general availability by late-August 2025.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC961761](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC961761)

## Enhancements

### Aug 2025 – Enhanced Backup and Restore for Microsoft Authenticator on iOS

Starting in August 2025, Microsoft Authenticator for iOS will support backing up all account names, including work or school accounts, Microsoft personal accounts, and third-party accounts like Google or Amazon, using iCloud and iCloud Keychain with end-to-end encryption.

  
This enhancement removes the previous requirement for a Microsoft personal account to enable backup. Users with iCloud backup already enabled will automatically benefit from this update. A private preview of this feature will begin in August 2025.

**_Ref_**: [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/what%E2%80%99s-new-in-microsoft-entra-%E2%80%93-june-2025/4352579](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/what%E2%80%99s-new-in-microsoft-entra-%E2%80%93-june-2025/4352579)

### Aug 2025: Microsoft Purview: Audit Log Message Update for Role Group Changes

Microsoft Purview enhances audit log messages for role group membership changes, specifically for _GrantPermission_ and _DeletePermission_ operations under the SecurityComplianceRBAC workload. The _PreExecutionMessage_ and _PostExecutionMessage_ fields will provide clearer insights. Organizations using these logs programmatically should update their parsing logic accordingly.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1090695](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1090695)

### Aug 1, 2025 - Microsoft Fabric to Enforce 1,000 User/Group Limit on Workspace Roles

Microsoft Fabric will limit each workspace to a maximum of 1,000 users or groups in workspace roles _(Admin, Member, Contributor, Viewer)_. Overlimit workspaces can’t add more users or groups until they are under the threshold.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1098946](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1098946)

### Mid-Aug 2025 - Updated Page Analytics in Microsoft SharePoint Online

SharePoint Page Analytics will receive new capabilities starting mid-August 2025. If your organization has Microsoft Viva Suite or Viva Pulse Communications and Communities, you’ll gain access to enhanced features such as long-term data retention, breakdowns by distribution lists, export options, and additional metrics. Organizations without these licenses will still have access to the current set of metrics, displayed with a modernized page design.

Currently, this rollout will be targeted to SharePoint News posts only.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1069561](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1069561)

### Late-Aug 2025 - Policy Alerts Improvements in Microsoft Purview Communication Compliance

Microsoft will enhance the customization options for policy alerts. Through a new alert page, admins will be able to set the alert frequency for each policy and adjust both the email frequency and recipient list. This feature will be out in General Availability and will be enabled by default.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920304](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC920304)

## Existing Functionality Changes

### Aug 2025 - Signed Adobe & Docusign Documents Saved to the Originating Folder

Documents signed via Adobe or DocuSign using SharePoint eSignature integration will now be saved in the original SharePoint folder where the signing process started, instead of being placed in the default "Apps" folder.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=498232](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=498232)

### Aug 2025 – Decoupling of Policy Tips and Email Notifications for SharePoint and OneDrive

Currently, enabling email notifications for a DLP policy also requires enabling the policy tips, and vice versa. However, Microsoft will soon admins to configure email notifications and policy tips independently for SharePoint and OneDrive DLP policies.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=394279](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=394279)

### Aug 2025 - Changing Output Format for Some Database Properties in Exchange Online Cmdlets

To improve performance, Microsoft is modifying the output format of certain database properties in Exchange Online cmdlets. For example, the Database property in the output of Get-Mailbox will change from: Database : APCP153DG038-db080 to a fully qualified path format: Database : APCP153.PROD.OUTLOOK.COM/7ad9dea1-26b7-4088-ad73-708c219faff6

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1108848](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1108848)

### Early-Aug 2025 - Know Your Customer Onboarding Process in Teams

Microsoft Teams phone numbers enable users to make and receive traditional PSTN calls, supporting external communication with customers, partners, and vendors.

To enhance compliance and reduce risks like spam or voice phishing, Microsoft is introducing a streamlined Know Your Customer (KYC) process. Teams administrators must now submit organizational details and supporting documents via the Teams Admin Center before requesting new phone numbers. This is a one-time verification step to validate the organization and authorize number provisioning.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1117815](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1117815)

### Aug 20, 2025 – Sender Email Address Update for Microsoft Teams DLP Generate Incident Report Emails

Microsoft is changing the sender address for Teams DLP Generate Incident Report (GIR) emails. After August 20, 2025, only the new address ([no-reply@teams.mail.microsoft.com](mailto:no-reply@teams.mail.microsoft.com)) will be used. If your inbox rules are set to act on the old sender address, update them to match the new address.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1064354](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1064354)

### Aug 25, 2025 - Microsoft Graph Metered API Update

Starting August 25, 2025, selected Microsoft Graph metered APIs such as Teams chat export and Teams meeting transcript will no longer incur usage-based charges. After this date, any calls made to these APIs will not trigger billing events.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1122144](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1122144)

### Late-Aug 2025 – Updates to the Get-FederationInformation Cmdlet in Exchange Online

Currently, the Get-FederationInformation cmdlet retrieves all federated domain information in the DomainNames field. After late-August 2025, the cmdlet will return details only for the domain explicitly specified as a parameter.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1081538](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1081538)

### After Aug 2025 – Microsoft 365 Default Setting Changes to Strengthen Security

As part of the Microsoft Secure Future Initiative and the _“Secure by Default”_ principle, Microsoft 365 is updating default settings to block legacy authentication and enforce admin consent for third-party app access.

**_Ref_**: [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1097272](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1097272)

## Action Needed

### Aug 2025 – Updates to Required Permissions for Microsoft Graph Beta API Device Management

Starting July 31, 2025, or soon after, the Microsoft Graph Beta API /deviceManagement endpoints will require _DeviceManagementScripts.Read.All or DeviceManagementScripts.ReadWrite.All_ permissions to operate.

**Solution:** Any existing apps, scripts, or tools using _DeviceManagementConfiguration.ReadWrite.All or DeviceManagementConfiguration.Read.All_ permissions must be updated to use the new permissions.

**_Ref:_** [https://admin.cloud.microsoft/?source=applauncher#/MessageCenter/:/messages/MC1107490](https://admin.cloud.microsoft/?source=applauncher#/MessageCenter/:/messages/MC1107490)

### Aug 31, 2025 - Legacy Message Trace Experience Retires in Exchange Online

With the introduction of the new Message Trace in Microsoft Exchange Online, the legacy experience will retire on September 1, 2025. The updated version offers improved performance and a modern interface, replacing:

1.  Legacy Message Trace UI in the EAC
2.  Legacy cmdlets: Get-MessageTrace, Get-MessageTraceDetail
3.  Reporting Web Service support for Message Trace data

**Solution:** As the new Message Trace becomes the default, admins should update scripts to use _Get-MessageTraceV2_ and _Get-MessageTraceDetailV2_, and complete the transition by August 31, 2025. The new UI remains enabled in the Exchange admin center.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1092458](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1092458)

### Aug 31, 2025 - Retirement of Azure AD Graph API

Azure AD Graph APIs will retire in early September 2025. Applications using them will stop working, and temporary outage tests will occur between late July and early September.

**Solution:** Use the _Recommendations_ tab in the Microsoft Entra admin center to identify affected apps and migrate to Microsoft Graph APIs by August 31, 2025.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1101901](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1101901)

### Retirement Postponed

### Aug 1, 2025 - Deprecation of "Send me an email notification" Action in Power Automate Postponed

The "Send me an email notification" action of Notifications connector in Power Automate was supposed to start failing 1% of the time from August 1, 2025, due to deprecation. However, Microsoft has now postponed this plan, so your flows will remain unaffected on that date. A new retirement date will be announced soon.

**Suggested action:** To stay prepared, switch to one of these supported actions - “Send an email (V2)” from the Outlook connector or “Send an email notification (V3)” from the Mail connector.

**_Ref_**: [https://community.powerplatform.com/forums/thread/details/?threadid=65cdc48a-fbdc-ef11-a730-000d3a14035a](https://community.powerplatform.com/forums/thread/details/?threadid=65cdc48a-fbdc-ef11-a730-000d3a14035a)

## September 2025

### Retirements

### Sep 1, 2025 - Retirement of Loop Component Rendering in Word for the Web

Previously, Microsoft had deprecated the ability to create Loop components in Word for the web. With this latest update, any existing Loop components in Word web documents will no longer appear in their interactive form. Instead, users will now see a read-only placeholder that includes a link. Clicking the link will open the component externally.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1107493](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1107493)

### Sep 15, 2025 - Retirement of Power BI Cognitive Services and Azure Machine Learning Features

Microsoft is retiring Cognitive Services and Azure Machine Learning features in Power BI by September 15, 2025. Existing models will continue to refresh until the retirement date. Microsoft recommends transitioning to Microsoft Fabric, where continued investments in AI capabilities will be made.

**Solution:** Move to Auto ML in Microsoft Fabric for supported AI scenarios.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1124567](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1124567)

### Mid-Sep 2025 - Microsoft Lists Mobile Apps to Be Removed from App Stores

Microsoft will retire the Microsoft Lists mobile apps for iOS and Android. Starting mid-September 2025, new users will no longer be able to install the apps. Users should switch to the mobile browser experience, which remains supported and regularly updated.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1087635](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1087635)

### New Features

### Early-Sep 2025 - General Availability of Progressive Alert Scoring in IRM

Microsoft will roll out a new feature -" Progressive alert scoring" in Microsoft Purview Insider Risk Management. Currently, user activities that could potentially result in data security incidents will be assessed once every 24 hours. After this rollout, the assessment of user activities will be done more frequently within a 24- hour period, along with alert insights. This feature will be generally available for GCC, GCC-High, DoD environments by early-Sep 2025.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC707653](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC707653)

### Early-Sep 2025 - Microsoft Rolls Out ‘Reject Direct Send’ Parameter in Exchange Online

Microsoft Exchange Online will roll out the _‘Reject Direct Send’_ parameter for the _Set-OrganizationConfig_ cmdlet in September 2025 to help block unwanted Direct Send traffic. This setting allows admins to prevent spoofed emails from on-premises or third-party sources using accepted domains.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/introducing-more-control-over-direct-send-in-exchange-online/4408790](https://techcommunity.microsoft.com/blog/exchange/introducing-more-control-over-direct-send-in-exchange-online/4408790)

### Sep 2025 – General Availability of High Volume Exchange Email for Microsoft 365

Microsoft will roll out High Volume Email (HVE) in general availability to support internal communication needs for line-of-business applications and high-volume SMTP use cases. HVE allows organizations to send internal emails well beyond the standard Exchange Online limits.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=382633](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=382633)

### Sep 2025 - Room Recommender for Teams Meetings

Microsoft Teams is getting a new AI-powered feature that recommends meeting rooms during chats when none are booked. The system considers participant locations, room availability, and capacity to suggest the best room for collaboration. This feature enhances meeting efficiency and requires a Teams Premium license to be enabled for organizers.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=482191](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=482191)

### Mid-Sep 2025 - Rule-based Enablement of Microsoft 365 third-party apps in the Teams admin center

To streamline app management in Teams, Microsoft is adding a new rule-based setting in the Teams admin center. This update allows administrators to manage Microsoft 365 certified apps in bulk by using controls available in the org-wide settings section. Admins can define availability based on permission scopes and publisher names. A 30-day review period will be provided before these changes affect app availability.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1085133](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1085133)

### Mid-Sep 2025 - Data Lifecycle Management: Retention Based on “last accessed” for OneDrive and SharePoint Files

Starting mid-Sep2025, Microsoft will introduce a "When items were last accessed" option in Purview retention policies. This will allow admins to configure retention policies based on file access history in OneDrive and SharePoint, enabling the removal of outdated data.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442)

### Mid-Sep 2025 - Microsoft Loop Usage Reports Coming to Microsoft 365 Admin Center

Microsoft Loop usage data will be available in the Microsoft 365 admin usage dashboards. This enables administrators to monitor adoption and activity without additional configuration.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC929020](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC929020)

### Late-Sep 2025 - New Secure Workflow to Bypass Legal Holds and Retention Policies in Microsoft Purview

Admins will have the ability to permanently delete sensitive Exchange mailbox content; bypassing retention policies and eDiscovery holds. This will be possible through the “Priority Cleanup Administrator” role, which grants authorized users’ permission to initiate Priority Cleanup for Exchange, allowing exceptions to standard retention and legal hold policies.

Since this process is irreversible and overrides existing policies, Microsoft has built-in approvals and special auditing for security.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC971035](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC971035)

### Late-Sep 2025 - Usage reports to Manage Metered Consumption Costs for Microsoft 365 Copilot Chat

To help organizations manage metered costs for Microsoft 365 Copilot Chat, Microsoft is rolling out a new Message Consumption Usage report in the Microsoft 365 admin center. This preview report offers detailed insights into billed messages, including total usage, daily usage patterns, and breakdowns by user, billing policy, agent, and agent-user pair.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1069563](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1069563)

### Enhancements

### Early-Sep 2025 - Microsoft Teams Expands Peripheral Health Reporting for BYOD Spaces

From mid-September 2025, admins can proactively monitor device issues in BYOD rooms and desks using enhanced peripheral health reports in the Pro Management portal. Reports detect faulty, missing, or undetectable devices before users are impacted.

**_Ref:_** [https://admin.microsoft.com/?#/MessageCenter/:/messages/MC1090689](https://admin.microsoft.com/?#/MessageCenter/:/messages/MC1090689)

### Early- Sep 2025 - Automatically Set Work Location by Connecting to a Wi-Fi Network

Microsoft Teams will introduce a feature that automatically sets users' work locations when they connect to the organization's Wi-Fi or certain peripherals. This helps deliver location-based experiences without manual input.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=488800](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=488800)

### Sep 2025 - Introducing the New Workflows Experience in Microsoft Teams

As part of Microsoft's push to make automation more accessible, a new Workflows experience is coming to Teams and SharePoint, starting rollout in public Preview by Sep 2025.

*   A streamlined UI across Teams chats, channels, and SharePoint.
*   A redesigned template library for quick workflow setup.
*   Natural language input to create flows by describing actions.
*   A Madlib-style editor for easy customization using plain language.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=491632](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=491632)

### Mid-Sep 2025 - Data Lifecycle Management: Separate Retention Policies for Copilot and AI Apps

Admins can configure distinct retention policies for Microsoft 365 Copilot, Copilot Studio, ChatGPT Enterprise, and other AI apps starting mid-September 2025. This allows faster deletion of Copilot and generative AI interactions for better data governance.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC973511](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC973511)

### Mid-Sep 2025 - Microsoft Purview: Separate Retention Policies for Copilot and Teams Chats

Starting mid-September 2025, admins can configure separate retention policies for Microsoft 365 Copilot interactions and Microsoft Teams chats using PowerShell or the compliance center UI. This feature requires a Microsoft 365 Copilot license and enhances flexibility in managing lifecycle policies for different communication types.

**_Ref:_** [https://admin.microsoft.com/?#/MessageCenter/:/messages/MC926899](https://admin.microsoft.com/?#/MessageCenter/:/messages/MC926899)

### Mid-Sep 2025 - Streamlined Same-Device Number Matching and First Run Experience (FRX) in Microsoft Authenticator

Starting mid-September 2025, Microsoft Authenticator will receive two updates to improve the user experience for Microsoft Entra sign-ins:

*   Same-device sign-ins will no longer require number matching. Users can simply tap "Yes" or "No" to confirm, reducing friction, especially on Android. iOS users will also benefit, though app switching may still be needed with the SSO extension.
*   The onboarding experience (FRX) is being refined by combining privacy screens, prioritizing Entra account setup, and making the QR code option more prominent for easier setup.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1117816](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1117816)

### Sep 30, 2025 - Teams Meeting Join URL Validation

To strengthen meeting security, Microsoft will begin validating Microsoft Teams meeting URLs. If your organization uses security tools that rewrite or modify these links, they could be flagged as malicious and impact the meeting experience. Admins can whitelist Microsoft Teams join URLs in the security tools. Also, review any URL rewriting or inspection rules to ensure they don't alter meeting links.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1120871](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1120871)

### Existing Functionality Changes

### September 2025 – Access Reviews Data Retention Policy Update

Beginning in September 2025, Microsoft Entra ID Access Reviews will retain history for only the past 12 months. Any review data older than one year will no longer be stored or retrievable through Microsoft Graph APIs or any other method. Organizations should take this into account if they require long-term access review data.  

**_Ref:_** [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/what%E2%80%99s-new-in-microsoft-entra-%E2%80%93-june-2025/4352579](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/what%E2%80%99s-new-in-microsoft-entra-%E2%80%93-june-2025/4352579)

### Sep 26, 2025 - Unlicensed OneDrive Accounts to Enter Read-Only Mode

Microsoft will begin transitioning OneDrive accounts that remain unlicensed before July 28, 2025, to read-only mode by September 26, 2025. Admins should monitor the Unlicensed OneDrive Accounts report and take appropriate actions such as renewing, archiving, or deleting accounts to ensure compliance and uninterrupted access.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC836942](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC836942)

### Action Required

### Sep 2, 2025 – Update Conditional Access Policies for Azure DevOps Sign-ins

Microsoft is removing Azure Resource Manager (ARM) as a dependency for Azure DevOps sign-ins and token refresh. Previously, Conditional Access policies targeting ARM would apply to Azure DevOps as well. With this change, those policies will no longer enforce access controls on Azure DevOps usage.

**Solution:** Admins should configure a separate Conditional Access policy specifically for Azure DevOps to maintain security controls.

**_Ref_**: [https://devblogs.microsoft.com/devops/removing-azure-resource-manager-reliance-on-azure-devops-sign-ins/](https://devblogs.microsoft.com/devops/removing-azure-resource-manager-reliance-on-azure-devops-sign-ins/)

### Sep 30, 2025 – Retirement of Managing Authentication Methods in Legacy MFA &SSPR Policy

Starting Oct 2025, Microsoft no longer allow authentication methods to be managed in the legacy MFA and SSPR policies.

**Solution:** Organizations should use the converged authentication methods policy where methods can be managed centrally for all authentication scenarios including passwordless, MFA and SSPR.

**_Ref:_** [https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-methods-manage#legacy-mfa-and-sspr-policies](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-methods-manage#legacy-mfa-and-sspr-policies)

## October (Attention Needed: 7)

### Oct 2025 – Adding Support for SMTP DANE with DNSSEC for Exchange Online

Microsoft is adding inbound support for SMTP DANE with DNSSEC to Exchange Online GCC High and DoD. This enhancement will be available in preview starting October 2025, further strengthening email security for these environments.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?featureid=361914&searchterms=361914](https://www.microsoft.com/en-in/microsoft-365/roadmap?featureid=361914&searchterms=361914)

### October 2025 - Just in Time Protection on SharePoint in DLP

Microsoft is introducing Just-in-Time protection for SharePoint in Microsoft Purview Data Loss Prevention in preview.

With this feature, organizations can automatically apply DLP restrictions to unclassified files when they are accessed or shared externally. Instead of restricting files in advance, JIT protection enforces security measures only when there is a risk of data leaving the organization.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457)

### October 2025 – New Personalization Settings in Microsoft Purview

Microsoft will introduce a new personalization page in Microsoft Purview, allowing admins to customize their experience. New features will include the ability to pin/unpin solutions, toggle solution bar visibility, access solution walk-throughs, export personalization data, and delete preferences. This update will help streamline the management of individual admin experiences within Microsoft Purview.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=483884](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=483884)

### Oct 10, 2025 – Changes to Access Package Visibility in My Access Portal

Starting October 10, 2025, access packages configured for “Specific users and groups” will become visible to all members, excluding guests, in the My Access portal. If you want to restrict visibility, you must manually hide the access package before this date. Additionally, Microsoft will introduce a new tenant-wide setting that gives admins more control over the visibility of group and app names within access packages.

**_Ref_**: [https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1113678](https://admin.cloud.microsoft/?source=applauncher&ref=MessageCenter/:/messages/MC1113678)

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

**_Ref_**:[https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC921752](https://admin.microsoft.com/Adminportal/Home?#/MessageCenter/:/messages/MC921752)

### After Oct 2025 – End of Support for Legacy Microsoft Outlook for Mac

As part of Microsoft's commitment to a more secure and robust email experience, Microsoft 365 subscriptions linked to a personal, work, or school account will no longer support the legacy version of Microsoft Outlook for Mac.

**Solution:** Upgrade to the latest version of Outlook for Mac, which is built on modern technology for improved performance, security, and reliability.

**_Ref:_** [https://support.microsoft.com/en-us/office/end-of-support-for-legacy-outlook-for-mac-7b9cf644-7035-4345-a151-8c1c7a65ac25](https://support.microsoft.com/en-us/office/end-of-support-for-legacy-outlook-for-mac-7b9cf644-7035-4345-a151-8c1c7a65ac25)

## November (Attention Needed: 2)

### Nov 2025 - Microsoft Entra ID to Support Passkey Profiles in Authentication Methods Policy

In November 2025, Microsoft Entra ID will introduce support for passkey profiles in the passkey (FIDO2) authentication methods policy. This update allows admins to apply different passkey configurations to specific user groups, offering more granular control. New schema changes will apply if configurations are made through the Azure or Entra portal during the preview.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1097225](https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC1097225)

### Nov 2025 - Introducing Data Lifecycle Management for Microsoft Planner

Compliance admins can now create retention policies to manage content in Microsoft Planner, including tasks from plans associated with Microsoft 365 groups.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=486828](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=486828)

## December (Attention Needed: 4)

### Dec 2025 - Integration of New ChatGPT Enterprise Connector with Microsoft Purview Compliance Portal

The ChatGPT Enterprise connector will be integrated into the Microsoft Purview Compliance portal, allowing admins to discover, collect, and store prompts and responses from users' interactions with ChatGPT.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=401125](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=401125)

### Dec 2025 – Microsoft Teams App Usage Report Renamed and Redesigned as Integrated Apps Usage Report

The Teams app usage report is being renamed and redesigned as the Integrated Apps usage report, featuring new charts and metrics. It provides insights into app usage across Teams, Outlook, Microsoft 365 apps, and Copilot extensions. The data is organized by Publishing Type, Host Product, and Platform, with detailed views on app and user activity.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=410248](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=410248)

### Dec 2025 – Microsoft Purview DLP Adds Actionable Email Notifications for End Users

Microsoft Purview Data Loss Prevention now supports actionable email notifications, enabling end users to remediate policy violations directly from their mailbox. For OneDrive and SharePoint files that trigger DLP policies, users can now stop sharing, delete files, apply labels, override policies, report false positives, or indicate they’re unable to act—streamlining the remediation process.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=464996](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=464996)

### Dec 2025 – Inline Detection of Sensitive Data Shared Over Network via Microsoft Purview

Microsoft Purview now integrates with your existing Secure Access Service Edge (SASE) solution, extending Data Loss Prevention (DLP) capabilities to the network layer. This enables admins to intercept, inspect, and enforce DLP policies on network traffic carrying sensitive data.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=488807](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=488807)

## 2026 (Attention Needed: 22)

### Jan 13, 2026 – End of Extended Support for Microsoft Advanced Threat Analytics 1.x

Microsoft Advanced Threat Analytics (ATA) extended support will be ended on January 13, 2026.

**Solution**: Updates for Microsoft ATA are available from Microsoft Update or by manual download.

**_Ref_**: [https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c](https://support.microsoft.com/en-us/topic/description-of-update-3-for-microsoft-advanced-threat-analytics-1-9-954cb9b7-9646-78ce-2000-2a257b64df7c)

### Jan 2026 – DLP Policy Tip Support Coming to Outlook for Mac

Microsoft is bringing Data Loss Prevention (DLP) policy tip support to Outlook for Mac. This helps users avoid accidental data leakage by showing policy tips when sensitive data is detected in emails. Users will be able to identify non-compliant recipients and take corrective actions, including overriding the policy when permitted.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=484854](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=484854)

### Jan 2026 - Microsoft Purview Insider Risk Management Adds OCR Support for Image-Based Risk Detection

Starting January 2026, Insider Risk Management in Microsoft Purview will support Optical Character Recognition (OCR) to detect sensitive content in images shared via SharePoint, Teams messages, and endpoints. This enhancement helps identify potential insider threats such as data leaks or intellectual property theft, while preserving user privacy through pseudonymization and audit controls.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=171185](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=171185)

### Jan 2026 - SharePoint File-Level Archiving Coming to Microsoft 365 Archive

Microsoft 365 Archive will support file-level archiving in SharePoint, enabling more granular retention and storage control. This feature enters public preview in January 2026.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=477371](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=477371)

### Early Feb 2026 – Automatic Data Preservation for High-Risk Users

Microsoft is rolling out the integration of Adaptive Protection with Data Lifecycle Management (DLM) by early February 2026. With this update, items deleted by high-risk users will be automatically preserved. This enables organizations to quickly restore data if needed and prevent intentional data loss.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110)

### March 2026 - Long-term Retention Period for Microsoft 365 Backup

Admins will be able to configure longer-term retention for Microsoft 365 backups, allowing data storage beyond one year. This feature will be available in preview by March 2026.  

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=481834](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=481834)

### Mar 2026 - Retirement of "Require Approved Client App" Grant Control" in Entra ID Conditional Access

The Conditional Access "Require approved client app" grant control is being retired from Microsoft Entra ID & Microsoft Intune by March 2026.

**Solution:** Use the "Require application protection policy" grant control, which offers the same data loss prevention while providing enhanced security benefits.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1029989](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1029989)

### Mar 2026 - Microsoft Purview Information Barriers v2 Now Available for New Customers

Information Barriers v2 (IB v2) will be available by default for all new onboarding tenants. It supports up to 5,000 segments, allows users to be in up to 10 segments, and offers flexible user discoverability while enforcing IB policies.

Existing IB v1 tenants must opt in to upgrade to IB v2 to use these new capabilities. This update applies only to IB v1 customers.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=402516](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=402516)

### Mar 2026 - New DLP Rule Action: Trigger Power Automate Workflows in Microsoft Purview

Starting March 2026, Microsoft Purview will support a new Data Loss Prevention (DLP) rule action that triggers custom Power Automate workflows when a policy match occurs.

Ref: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=380721](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=380721)

### Mar 31, 2026- Deprecation of ‘Require Approved Client App’ Conditional Access Grant

The Require approved client app control in Azure Active Directory (Azure AD) Conditional Access will be retired and no longer enforced.

**Solution:** You can make use of the “Require app protection policy” control, which has all the same capabilities

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448)

### April 2026 – External Recipient Rate Limit in Exchange Online

Exchange Online will begin enforcing an External Recipient Rate (ERR) limit of 2,000 recipients within 24 hours. This restriction will apply to the cloud-hosted mailboxes of all newly created tenants.

**Note:** Exchange Online currently enforces a Recipient Rate limit of 10,000 recipients for cloud-hosted mailboxes. The 2,000 ERR limit will be a sublimit within this 10,000 Recipient Rate limit.

**_Ref:_** [https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733](https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-introduce-external-recipient-rate-limit/ba-p/4114733)

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

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865)

### Apr 02, 2026 – Azure ACS Retirement in Microsoft 365

After April 2, 2026, existing tenants using Azure ACS for custom or third-party app access in SharePoint Online will no longer function due to its retirement.

**Solution:** Admins can utilize the Microsoft 365 Assessment tool to scan the tenants for any usage of Azure Access Control Service (ACS) and [migrating from Azure ACS to Microsoft Entra ID](https://aka.ms/retirement/acs/guidance).

**_Ref:_** [https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/retirement-announcement-for-azure-acs](https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/retirement-announcement-for-azure-acs)

### Apr 02, 2026 - Retirement of Domain Isolated Web Part in SharePoint Framework

  
From Apr 02, 2026, the domain isolated web part feature will be fully retired. Organizations using this feature will receive an error message.

**Solution:** Update your domain isolated web parts to regular web parts and redeploy them to ensure continued functionality.

**_Ref:_** [https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/](https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/)

### April 30, 2026 - Basic Auth for Client Submission (SMTP AUTH) Retirement in Exchange Online

Exchange Online will permanently remove support for Basic authentication with Client Submission (SMTP AUTH), reaching 100% rejection of such requests by April 30, 2026.

**Solution:** You can start to use OAuth with Client Submission (SMTP AUTH).

**_Ref_**: [https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-retire-basic-auth-for-client-submission-smtp/ba-p/4114750](https://techcommunity.microsoft.com/t5/exchange-team-blog/exchange-online-to-retire-basic-auth-for-client-submission-smtp/ba-p/4114750)

### July 14, 2026- InfoPath 2013 Client and InfoPath Forms Services in SharePoint Online Will be Retired

  
  
InfoPath Client 2013 will reach the end of its extended support period on July 14, 2026, and to keep an aligned experience across Microsoft products, InfoPath Forms Service will be retired from SharePoint Online.

**Solution:** To understand the usage of InfoPath within your organization, you can utilize the [Microsoft 365 Assessment tool](https://aka.ms/assessment/infopath) to scan your tenant and analyze InfoPath usage. If you are currently using InfoPath, you can initiate the migration process to modern alternatives such as Power Apps, Power Automate, or Forms.

**_Ref_**: [https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190](https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190)

### July 2026 - SharePoint Alerts Will be Fully Retired

Microsoft will discontinue support for SharePoint Alerts. Existing alerts can no longer be modified and will eventually stop functioning.

**Solution:** Microsoft recommends migrating SharePoint Alerts to Power Automate or SharePoint Rules. Use the Microsoft 365 Assessment tool to review alerts and plan the move.

**_Ref_**: [https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f](https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f)

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