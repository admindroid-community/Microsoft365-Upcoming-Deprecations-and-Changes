# What's Changing in Microsoft 365? A Guide to Feature Deprecations and Upcoming Enhancements

Join us in this blog as we explore the dynamic world of Microsoft 365. 🌟 We’ll shed light on the features and products that are undergoing transformations or bidding farewell. Whether you’re a system administrator 🧑‍💻 managing the Microsoft 365 environment or an avid user 🙋‍♂️ staying ahead of the curve, this blog will provide invaluable insights and actionable recommendations.

🚀Discover the **key changes, deprecations,** and **end-of-support** scenarios that require your attention. From deprecated features to configuration modifications and essential upgrade plans, we’ve got you covered! Make informed decisions and ensure a smooth transition.⚡️

## Microsoft 365 Upcoming Changes and Deprecations List:

Here is a list of changes categorized by month and year.

*   **Mar 2026** (Retirements: 8, New Features: 13, Enhancements: 5, Existing Functionality Changes: 4, Action Needed: 6)
*   **April 2026** (Retirements: 6, New Features: 10, Enhancements: 5, Existing Functionality Changes: 2, Action Needed: 2)
*   **May 2026** (Attention Needed: 7)
*   **June 2026** (Attention Needed: 11)
*   **Q3 2026** (Attention Needed: 9)
*   **Q4 2026** (Attention Needed: 9)
*   **2027** (Attention Needed: 6)

## March 2026

Retirements: 8 | New Features: 13 | Enhancements: 5 | Existing Functionality Changes : 4 | Action Needed: 6

### Retirements

### Early-Mar 2026 - Retirement of Personal Account Integration in Outlook Web App

The OneView and TrueTime features in Outlook Web App, which allow users to connect personal email accounts and personal calendars, will be retired starting early March 2026.

As a result, users will no longer be able to connect personal accounts or view combined personal and work calendars in OWA. Any existing connected personal accounts will be automatically disconnected.

**Solution:** Users must manage personal and work calendars separately. Recommend Outlook desktop applications for multi-account access and calendar management.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1226749](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1226749)

### Early-Mar 2026 - Deprecation of Web Search Image Pivot in SharePoint Pages

The Web Search image pivot in SharePoint Pages, which allowed authors to search the web for images using Bing and insert them directly into pages, is being retired by Microsoft. This change is due to the retirement of the Bing Search API.

Authors will no longer be able to search and insert web images directly but can continue using Stock images, local uploads, site and tenant assets, and recent files. This change is enabled by default.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230452](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230452)

### Early-Mar 2026 – Featured Links Retirement on SharePoint Online Start Page

From early-March 2026, Microsoft will retire the Featured Links capability in SharePoint Online. Admins will no longer be able to create, edit, update, or access Featured Links. As part of this change, existing Featured Links will be removed from the SharePoint Online start page and the mobile app.

**Solution:** Highlight important sites and content using alternatives such as global navigation links or Viva Connections resources.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197131](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197131)

### March 13, 2026 - Retirement of Data Export Options in Viva Engage Admin Center

The legacy “Include attachments” and “Include external network” data export options in the Viva Engage admin center will be retired on March 13, 2026, to streamline the export experience. Since these options applied only to legacy Yammer networks, they are not relevant for Viva Engage networks operating in native mode.

**Solution:** Admins can access exported files through SharePoint links provided after the export process. For external networks, admins must sign in to each modern network individually and run exports separately.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230453](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230453)

### March 19, 2026 - Retirement of Azure AD Account Linking for Microsoft Rewards

Starting March 19, 2026, Microsoft will retire the Azure AD account linking feature that allowed users to link work and personal Microsoft accounts to earn Microsoft Rewards points. Linking options will be removed from Bing, Edge, MSN, and the Microsoft 365 admin center, while existing reward point balances will remain unaffected.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1234567](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1234567)

### Mid-Mar 2026 – Defender for Android Ending Support for Enrolled Personal Profiles

Microsoft Defender for Android will stop protecting personal profiles on enrolled devices managed through MDM configuration policies and will instead focus exclusively on work profiles.

This change improves corporate security while preserving user privacy and requires no action from admins or users. Work profiles and mobile application management (MAM)-enabled devices, including unenrolled devices, are not affected.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1221927](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1221927)

### Mar 30, 2026 – Retirement of External Access Token for Actionable Messages

External access tokens for actionable messages will be retired on March 31, 2026, and organizations must transition to Microsoft Entra authentication to ensure continued functionality. After this date, any actionable message relying on external tokens will fail. This change strengthens security and aligns with modern identity standards.

**Solution:** Organizations using actionable messages should review their current implementations and update all integrations to Microsoft Entra authentication before the deadline to avoid disruptions.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1189663](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1189663)

### March 30, 2026 – Retirement of Contact Masking in Microsoft Outlook

The Contact Masking feature, which hides suggested recipients, will be retired on March 31, 2026. As a result, previously hidden contacts may reappear in recipient suggestions, People suggestions, and search.

**Solution:** Admins should review alternative controls such as Address Book Policies, hiding recipients from the GAL, or Information Barriers based on organizational requirements.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1234566](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1234566)

### New Features

### March 1, 2026 – Content Security Policy in SharePoint Online

Microsoft introduced Content Security Policy (CSP) in SharePoint as a browser-level security standard that controls which scripts, styles, images, and other resources a site is allowed to load. If a resource isn’t explicitly approved, the browser blocks it. This helps protect SharePoint sites from threats like cross-site scripting (XSS), clickjacking, and other code injection attacks. This CSP will be enforced for all tenants starting March 1, 2026.

**_Ref_**: [https://techcommunity.microsoft.com/blog/spblog/sharepoint-online-content-security-policy-csp-enforcement-dates-and-guidance/4472662](https://techcommunity.microsoft.com/blog/spblog/sharepoint-online-content-security-policy-csp-enforcement-dates-and-guidance/4472662)

### Early-March 2026 – Defender for Office 365 URL Click Alerts Extended to Microsoft Teams

Microsoft is extending Microsoft Defender for Office 365 (MDO) URL click alerts to Microsoft Teams, enabling detection of malicious or suspicious link clicks shared in Teams messages. Teams-based URL alerts will now appear in the Microsoft Defender portal alongside existing email alerts, improving threat visibility and investigation across collaboration workloads.

*   Alerts such as _“A user clicked through to a potentially malicious URL”_ and _“A potentially malicious URL click was detected”_ will now trigger for Teams messages.
*   Alert evidence will include the associated Teams message for improved investigation context.
*   The feature is enabled by default for organizations licensed with _Microsoft Defender for Office 365 Plan 2 or Microsoft 365 E5_. No user workflow changes are required.
*   _Automated Investigation and Response (AIR)_ is not supported for Teams URL click alerts.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=557549](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=557549)

### Early-March 2026 – New SharePoint Experience Introduced with Redesigned Navigation and AI Enhancements

Microsoft is introducing a new SharePoint experience with a simplified design and improved navigation to help users discover content, publish information, and build solutions more efficiently. The update also brings AI-assisted capabilities, which require a _Microsoft 365 Copilot license_.

The experience includes a redesigned SharePoint app bar with _Discover, Publish, Build, OneDrive, and Home_ options, along with refreshed pages, news, libraries, and lists for improved content visibility while preserving existing site branding. The new experience will begin rolling out in _public preview starting March 2026_ and can be enabled optionally by administrators.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1240699](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1240699)

### Mar 2026 – Conditional Access for Microsoft Entra Account Recovery

Microsoft Entra ID has introduced Account Recovery to help users regain access when all registered authentication methods are unavailable. The recovery flow is secured with Conditional Access policies and will be available in public preview in March.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=529855](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=529855)

### March 2026 – High Volume Email in Exchange Online Reaches General Availability

High Volume Email (HVE) in Exchange Online enables organizations to send large volumes of internal emails such as notifications, alerts, and automated messages without affecting regular user mail flow or requiring separate email infrastructure.

This capability has now reached General Availability in March 2026, allowing organizations to manage bulk internal communications reliably within Microsoft 365.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/high-volume-email-continued-support-for-basic-authentication--other-important-up/4411197](https://techcommunity.microsoft.com/blog/exchange/high-volume-email-continued-support-for-basic-authentication--other-important-up/4411197)

### Mar 2026 – New DLP Rule Action: Trigger Power Automate Workflows in Microsoft Purview

Starting March 2026, Microsoft Purview will support a new Data Loss Prevention (DLP) rule action that triggers custom Power Automate workflows when a policy match occurs.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=380721](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=380721)

### Mar 2026 – SharePoint File-Level Archiving Coming to Microsoft 365 Archive

Microsoft 365 Archive will support file-level archiving in SharePoint, enabling more granular retention and storage control. This feature enters the preview in March 2026.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=477371](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=477371)

### Mar 2026 – Microsoft Purview Information Barriers v2 Now Available for New Customers

Information Barriers v2 (IB v2) will be available by default for all new onboarding tenants. It supports up to 5,000 segments, allows users to be in up to 10 segments, and offers flexible user discoverability while enforcing IB policies.

Existing IB v1 tenants must opt in to upgrade to IB v2 to use these new capabilities. This update applies only to IB v1 customers.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=402516](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=402516)

### Mar 2026 – Auto-Enabling Passkey Profiles in Microsoft Entra ID

Microsoft Entra ID will bring passkey profiles and synced passkeys to general availability starting March 2026. This update gives admins the option to enable a new passkey profiles experience that supports _group-based passkey assignments_ and introduces a _passkeyType_ property to improve management and customization.

Tenants that do not opt in during the rollout window will be automatically migrated, with existing FIDO2 and passkey settings preserved and moved into a default passkey profile. Microsoft-managed registration campaigns will also update target passkeys where synced passkeys are enabled.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1221452](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1221452)

### Mid-March 2026 – New Protection Reports in Teams Admin Center

Building on existing message reporting and newly introduced call reporting, Microsoft is introducing Protection reports in the Teams admin center. This enables admins to review and export user-reported suspicious messages and calls, provided that user reporting settings are enabled.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1227625](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1227625)

### Mid-March 2026 – SharePoint Branding Governance Using PowerShell

Microsoft is enabling centralized SharePoint site branding management using PowerShell. Tenant admins can apply enterprise themes, enable or disable custom branding for specific sites, audit branding changes, and apply branding during site creation.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1186372](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1186372)

### Mid-Mar 2026 – Data Security Posture Agent in Microsoft Purview

Microsoft Purview will introduce the Data Security Posture Agent to continuously discover sensitive data and assess data risks across the environment.

The agent uses AI to analyze content intent and meaning, delivering clearer insights and summaries that help security teams quickly identify risks and take corrective actions. It will be out for general availability by mid-Mar 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1217155](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1217155)

### Late March 2026 – Purview DLP Enforcement Expanded for Microsoft 365 Copilot Across All File Locations

Microsoft is expanding Microsoft Purview Data Loss Prevention (DLP) enforcement for Microsoft 365 Copilot, ensuring sensitivity label–based DLP policies block Copilot from processing protected _Word, Excel, and PowerPoint files_ across all storage locations, including local devices.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1234661](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1234661)

### Enhancements

### Early-March 2026 – New Registration Policy for Teams Events

Microsoft Teams is introducing a new **Registration** policy setting in Teams Events policies to control whether organizers can schedule events that require registration. Enabled by default, this setting works alongside the existing **AllowWebinars** policy, which continues to govern webinar creation from the Teams Calendar app.

Admins can disable event registration through the **_Set-CsTeamsEventsPolicy_** PowerShell cmdlet by setting the **_\-Registration_** parameter to **_Disabled_**, if required. Additionally, if _AllowWebinars_ is set to Disabled while _Registration_ remains Enabled, organizers can schedule events with registration but will not be able to create webinars from the Teams Calendar app.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1226497](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1226497)

### Early-March 2026 - Defender Antivirus Exclusions No Longer Stored in Local Registry

Starting March 2026, Microsoft Defender Antivirus devices managed through Microsoft Defender for Endpoint (MDE) security settings management will no longer store readable exclusion values in the local registry. As a result, registry-based monitoring or scripts used to retrieve antivirus exclusions will stop working. Devices not managed via MDE are unaffected.

Update monitoring scripts to use PowerShell cmdlets like **Get-MpPreference** instead of registry-based queries and inform relevant teams of this change.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1227621](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1227621)

### Mar 2026 – Organizational Messages Now Support Hybrid-Joined Devices

Microsoft is expanding Organizational Messages to support Entra ID Hybrid-joined devices in addition to fully cloud-joined devices. This allows organizations to deliver customized messaging to a wider range of enrolled endpoints.

**_Ref_**: [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=503564](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=503564)

**Mar 2026 – Email Support for Organizational Messages**

Organizational messages currently support delivery through Windows Taskbar, Notifications, Spotlight, and Teams popovers. Microsoft is adding email as a delivery channel, enabling admins to send tenant-wide informational messages via email.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=503562](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=503562)

### Mar 2026 – Data Loss Prevention for Microsoft 365 Copilot

Microsoft is expanding DLP support to Microsoft 365 Copilot. Admins can configure DLP policies to block Copilot responses when prompts involve sensitive data from Microsoft 365 or the web.

This helps prevent data leakage and strengthens compliance controls across Copilot interactions.

**_Ref_**: [https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=515945](https://www.microsoft.com/en-in/microsoft-365/roadmap?searchterms=515945)

### Existing Functionality Changes

### Mid-March 2026 – Search by Meeting ID May Not Work in Call Quality Dashboard

Starting mid-March 2026, searching by _Meeting ID_ in the Call Quality Dashboard (CQD) may not return expected results. CQD is updating the _Meeting ID_ field to align with the _numeric Meeting ID_ used in Teams meeting invites, while the previously used value will be available under a new _Thread ID_ dimension.

Existing CQD reports or queries relying on the old Meeting ID must be updated to ensure accurate results.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1228315](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1228315)

### Mar 27, 2026 – Improved Enforcement for Conditional Access Resource Exclusions

Before March 27, 2026, Conditional Access policies targeting All resources with exclusions were not consistently enforced for apps requesting limited scopes, such as OIDC. This allowed users to sign in without meeting requirements like MFA, even when the app was not explicitly excluded.

Starting March 27, 2026, these policies will be enforced consistently for all apps, ensuring users must complete required authentication and access controls unless an app is explicitly excluded.

**_Ref_**: [https://techcommunity.microsoft.com/blog/microsoft-entra-blog/upcoming-conditional-access-change-improved-enforcement-for-policies-with-resour/4488925](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/upcoming-conditional-access-change-improved-enforcement-for-policies-with-resour/4488925)

### Mar 31, 2026 – Azure Subscription Required for Entra ID Guest Governance Access Reviews

Microsoft Entra ID Governance now requires organizations to link an Azure subscription to continue creating or updating guest governance actions. As part of the March 2026 update, this requirement also extends to access reviews for guest users, ensuring governance activities follow the Monthly Active User (MAU) billing model.

Without a linked Azure subscription, admins will be unable to create or modify guest-scoped governance policies or access reviews, although existing configurations will continue to run.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1225192](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1225192)

### Mar 2026 – Decoupling Policy Tips & Email Notifications for SharePoint and OneDrive DLP

Currently, enabling email notifications in DLP policies for SharePoint and OneDrive also forces policy tips to be enabled, and vice versa. With this update, admins will be able to configure policy tips and email notifications independently, providing more flexibility in how alerts are managed.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC791114](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC791114)

### Action Required

### Mar 14, 2026 – Retirement of Microsoft Teams App in Amazon Appstore

Microsoft is retiring the Microsoft Teams app from the Amazon Appstore on March 14, 2026. Existing installations will no longer receive updates or support and may eventually lose connectivity.

**Solution:** Organizations should move users to the Teams web app or the Android app via Google Play Store.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1234560](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1234560)

### Mar 16, 2026 – Context IQ Retirement in Outlook

The Context IQ feature in the new Outlook and Outlook on the web will be retired starting March 16, 2026, removing the “/” suggestions used to insert files while composing emails.

**Solution:** Users can continue attaching files using alternatives such as paste, drag-and-drop, or the Insert option.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230455](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230455)

### Mar 18, 2026 – End of Support for Suspected Identity Theft (Pass-the-Ticket) Classic Alert

The Suspected identity theft (Pass-the-Ticket) classic alert will be retired between March 18 and 22, 2026, while historical alerts will remain accessible. Detection will continue through the Pass-the-Ticket (PtT) attack XDR detector (ID: _xdr\_PassTheTicketAttack_).

**Solution:** Admins should update workflows and automation to reference the XDR detector ID and adjust existing alert tuning rules.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1234542](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1234542)

### Mar 31, 2026- Deprecation of ‘Require Approved Client App’ Conditional Access Grant

The Require approved client app control in Entra ID Conditional Access will be retired and no longer enforced.

**Solution:** You can make use of the “Require app protection policy” control, which has all the same capabilities.

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-change-announcements-march-2023-train/ba-p/2967448)

### Mar 31, 2026 – Retirement of Legacy SharePoint Online CDN Domain

Microsoft will retire the legacy CDN domain publiccdn.sharepointonline.com between March 31, 2026, and late April 2026. Organizations must update any hardcoded references to the new domain public-cdn.sharepointonline.com to avoid broken links or 404 errors.

**Solution**: Complete validation and updates before March 31, 2026, for uninterrupted access to SharePoint resources.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1184996](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC1184996)

### Mar 31, 2026 – Microsoft Defender for Android Requires Android 11 or Later

Microsoft Defender for Android will end support for devices running Android 10. Starting March 31, 2026, Android 11.0 or later will be required to receive updates, security patches, and new features.

**Action Required:** Advise users to upgrade their devices to Android 11.0 or later.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1222977](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1222977)

## April 2026

### Retirements

### April 2026 – Retirement of SharePoint Online Legacy Information Management Features

Starting April 2026, SharePoint Online will retire several legacy compliance and records management features, including Information Management Policies, In-Place Records Management, and deletion-only policies for documents and site closure. These features will no longer be supported or accessible through the UI or APIs.

Solution: Organizations should migrate to modern Microsoft Purview capabilities, including Data Lifecycle Management and Purview Records Management.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1211579](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1211579)

### Apr 02, 2026 – SharePoint 2013 Workflow Retirement

SharePoint 2013 workflows will no longer be supported.

**Solution:** You can move to Power Automate or other supported solutions.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC542767](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC542767)

### Apr 02, 2026 – SharePoint Add-in Retirement

SharePoint Add-Ins will stop working for existing tenants from April 2nd, 2026.

**Solution:** Admins can run the Microsoft 365 Assessment tool to scan their tenants for SharePoint Add-In usage.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC693865](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC693865)

### Apr 02, 2026 – Azure ACS Retirement in Microsoft 365

After April 2, 2026, existing tenants using Azure ACS for custom or third-party app access in SharePoint Online will no longer function due to its retirement.

**Solution:** Admins can utilize the Microsoft 365 Assessment tool to scan the tenants for any usage of Azure Access Control Service (ACS) and migrating from Azure ACS to Microsoft Entra ID.

**_Ref:_** [https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/retirement-announcement-for-azure-acs](https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/retirement-announcement-for-azure-acs)

**Apr 02, 2026 – Retirement of Domain Isolated Web Part in SharePoint Framework**

From Apr 02, 2026, the domain isolated web part feature will be fully retired. Organizations using this feature will receive an error message.

**Solution:** Update your domain isolated web parts to regular web parts and redeploy them to ensure continued functionality.

**_Ref:_** [https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/](https://devblogs.microsoft.com/microsoft365dev/retiring-sharepoint-framework-domain-isolated-web-parts-for-sharepoint-online/)

### Apr 15, 2026 - Deprecation of Engage Live Events Powered by Teams Live Events

Viva Engage is retiring live events powered by Teams Live Events on April 15, 2026. After this date, organizers will no longer be able to schedule new live events in Engage using Teams Live Events. Existing events scheduled before the retirement date will continue to be supported until February 28, 2027.

**Solution:** Migrate to Viva Engage events powered by Teams town halls.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1227085](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1227085)

### New Features

### Early-April 2026 – Rule-Based Management for Microsoft 365 Third-Party Apps in Teams

Microsoft is adding a rule-based configuration option in the Teams admin center to simplify app management. With this update, administrators can control Microsoft 365 certified third-party apps in bulk from the _Org-wide settings_ section. Also, app availability can be determined using publisher information and permission scopes.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1085133](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1085133)

### Early-April 2026 – Private Organizer Chat for Teams Meetings, Webinars, and Town Halls

Microsoft Teams is introducing a private chat experience for organizers, co-organizers, and presenters across structured meetings, webinars, and town halls. This dedicated chat allows event teams to collaborate privately before, during, and after sessions without involving attendees.

The update also standardizes backroom chat behavior in town halls, removing inconsistencies previously caused by streaming chat settings or Teams Premium licensing. Backroom chat will be enabled by default after rollout.

*   If admins disable the backroom chat policy, previously scheduled town halls may lose organizer backroom chat access once meeting options are updated.
*   Town halls that previously did not have backroom chat enabled may automatically gain access after the rollout.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1188222](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1188222)

### Early-April 2026 - Microsoft Teams Express Voice Enrollment

Microsoft Teams is introducing Express Voice Enrollment, allowing users to quickly register voice profiles through an in-meeting prompt. Voice profiles enable features such as voice isolation, speaker recognition, improved transcripts, and Microsoft 365 Copilot–powered meeting insights.

The feature will be enabled by default for enterprise tenants (excluding EDU). Organizations that previously disabled voice enrollment policies will remain unaffected. Admins can manage this feature using new PowerShell cmdlets available under the _PassiveVoiceEnroll_ setting in _CsTeamsAIPolicy_.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197146](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1197146)

### Early-April 2026 – Brand Impersonation Protection for Teams Calling

Microsoft is introducing Brand Impersonation Protection for Teams calling. This feature detects and warns users about fraudulent external callers impersonating trusted organizations.

Users will see a warning and can choose to accept, block, or end the call. The feature will be enabled by default and will evaluate incoming VoIP calls from first-time external callers.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1219793](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1219793)

### April 2026 – Automatically Set Work Location by Connecting to a Wi-Fi Network

Microsoft Teams will introduce a feature that automatically sets users’ work locations when they connect to the organization’s Wi-Fi or certain peripherals. This helps deliver location-based experiences without manual input. The feature will be disabled by default. Tenant admins will have the option to enable it and will require end-user consent to proceed.

**_Ref:_** [https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=488800](https://www.microsoft.com/en-US/microsoft-365/roadmap?filters=&searchterms=488800)

### April 2026 – New External Domain Anomalies Report in Teams Admin Center

Microsoft Teams will roll out a new External Domain Anomalies report in March 2026. The report helps admins detect unusual or risky external interactions by flagging spikes, new domains, and abnormal communication patterns. This provides early visibility into potential data sharing and security risks.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=536572](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=536572)

### April 2026 - Integration of Viva Engage Communities in Microsoft Teams

Microsoft is integrating Viva Engage communities into Microsoft Teams, enabling discoverable conversations, unified navigation, synced memberships, and enhanced admin controls. The feature is enabled by default, and administrators can disable it if required.

It is available to all Microsoft Teams customers with a standard Microsoft 365 and Teams license, with no additional licensing required.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1218423](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1218423)

### April 2026– Sensitivity Label Inheritance for Teams Meeting Recordings

Microsoft Teams meeting recordings will automatically inherit the meeting’s sensitivity label when label inheritance is enabled. This ensures that access controls, data protection policies, and agent responses based on meeting transcript respect the meeting’s sensitivity classification end to end.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=557178](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=557178)

### Apr 5, 2026 – Message Trace Support in Microsoft Graph API

Microsoft will introduce Microsoft Graph API support for Message Trace in public preview starting April 5, 2026.

Organizations currently relying on the Reporting Web Service API for Message Trace should begin transitioning to this Graph API, as the Reporting Web Service API will be deprecated.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1221939](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1221939)

### Late-April 2026 – OneDrive Simplified File Transfer for Departing Employees

Microsoft has enhanced OneDrive file management for departing employees, simplifying how managers access, review, and transfer files while preserving existing sharing permissions. These improvements help ensure important organizational content remains accessible during employee offboarding.

The update introduces improved and more visible notifications, enhanced filtering to quickly identify shared or important files, and bulk file transfer capabilities using _Move and keep sharing,_ which retains existing access permissions. Additionally, collaborators receive a single consolidated notification when multiple files are moved, while managers or designated owners automatically gain access to departing users’ OneDrive content.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1164381](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1164381)

### Enhancements

### Apr 1, 2026 – Extended Access to Advanced Capabilities in Microsoft Teams and Places

Effective April 1, 2026, Microsoft is updating Teams and Places licensing to bring several high-value features directly into core Teams Enterprise licenses, making collaboration, space management, and large-scale events easier for all users:

*   **Microsoft Places Explorer and Places Finder for end-users** → now included in licenses with Teams/Outlook calendar (E3/E5, Business, Exchange Online, etc.)
*   **Teams Shared Space license** → renamed and expanded; admins get space management + analytics; 4 desks per license.
*   **Town halls & webinars** → advanced features now available for all Teams Enterprise users, up to 3,000 interactive attendees (10,000 view-only)
*   **New Attendee pack add-ons** → extend town hall capacity from 5,000 up to 100,000 participants.

**_Ref_**: [https://techcommunity.microsoft.com/blog/microsoftteamsblog/licensing-updates-extend-access-to-advanced-capabilities-in-microsoft-teams-and-/4488312](https://techcommunity.microsoft.com/blog/microsoftteamsblog/licensing-updates-extend-access-to-advanced-capabilities-in-microsoft-teams-and-/4488312)

### April 2026 – Cross-tenant Security Group Synchronization

Previously, cross-tenant synchronization supported only users. Microsoft is now extending this capability to security groups in Microsoft Entra, allowing centralized group management and cross-tenant access.

The feature will enter **general availability by late-April** and requires admin opt-in with configured attribute mappings and access policies.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1198077](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1198077)

### April 2026 – Jailbreak and Root Detection in Microsoft Authenticator App

Microsoft will enhance the Microsoft Authenticator app with jailbreak and root detection capabilities for Entra credentials on iOS platforms. Once this feature is active, Entra credentials on jailbroken or rooted devices will stop functioning. And any existing ones will be automatically wiped for security reasons.

Ref: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1179154](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1179154)

### April 2026 – Insider Risk Management for AI Agents

As AI agents become more common in Microsoft 365, associated risks also continue to rise. Microsoft will extend Insider Risk Management to cover AI agents, enabling admins to define policies specifically for agent-driven activities. This enhancement helps detect, flag, or block risky behaviors when AI agents access sensitive data or perform high-risk actions across platforms like Copilot Studio, Azure AI Foundry, and Agent 365.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=516032](https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=516032)

### April 2026 – Enhancements to Microsoft Purview Data Security Triage Agent

Microsoft is introducing several enhancements to the **Data Security Triage Agent** in Microsoft Purview to improve alert investigation and administrative management.

*   **Metadata-supported custom instructions (DLP):** The agent now supports metadata-based instructions in addition to content-based rules, enabling contextual alert analysis—for example, focusing on alerts related to sensitive documents shared by a specific user within the last 20 days.
*   **Consolidated agent settings:** Deployment configuration and trigger settings are unified into a single management view, simplifying administration and updates.
*   **Support for non-content condition alerts (DLP):** Alerts generated from non-content conditions can now be triaged and categorized instead of being marked unsupported.
*   **Agent identity support:** The triage agent can now operate using its own Microsoft Entra identity instead of the configuring user’s identity, improving auditability and operational transparency.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=557552](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=557552)

### Existing Functionality Changes

### April 2026 - Customize OneDrive Sync Folder Names on Windows

By default, the local OneDrive sync folder is named “OneDrive – Organization Name,” which can consume available path length for deeply nested files and folders. Microsoft is introducing a new policy that allows administrators to customize the local OneDrive sync root folder name on users’ Windows devices.

This enables shorter sync folder names, improving usability and reducing issues caused by long file paths.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=557562](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=557562)

### April 2026 – Hard Delete Configuration for SharePoint and OneDrive in Purview Priority Cleanup Policies

Microsoft Purview will allow admins to configure hard deletion in priority cleanup policies for SharePoint and OneDrive content, enabling items to bypass recycle bins during cleanup.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=557188](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=557188)

### Action Required

### Apr 14, 2026 – Outlook for Windows Usage Report Retirement in the Exchange Admin Center

Microsoft is retiring the Outlook for Windows usage report from the Exchange admin center as part of ongoing efforts to streamline and modernize reporting experiences. Starting April 14, 2026, this report will no longer be available, and the change will occur automatically with no opt-out or admin control.

**Solution:** Administrators can continue accessing Outlook for Windows usage insights from the _Microsoft 365 admin center → Reports → Usage → Microsoft 365 Apps → Outlook for Windows._

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230889](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230889)

### Apr 30, 2026 – Retirement of Office 365 Connectors in Microsoft Teams

The retirement deadline for Office 365 Connectors in Microsoft Teams has been extended to April 30, 2026, giving organizations additional time to migrate.

**Solution:** Plan and complete the transition from Office 365 Connectors to Workflows webhooks to avoid disruption.

**_Ref:_** [https://devblogs.microsoft.com/microsoft365dev/retirement-of-office-365-connectors-within-microsoft-teams/](https://devblogs.microsoft.com/microsoft365dev/retirement-of-office-365-connectors-within-microsoft-teams/)

## May 2026 (Attention Needed: 7)

### Early May 2026 – Centralized App and Agent Evaluation Experience in Microsoft Teams

Microsoft Teams is introducing a centralized evaluation experience in the Teams admin center to simplify app and agent approval decisions. Administrators can define organizational trust requirements once, after which Teams will automatically generate evaluation scores and detailed assessment reports for apps and agents based on compliance and security criteria.

The evaluation score settings will be available under _Teams admin center → Teams apps_, allowing admins to review, sort, and filter apps using trust and compliance insights. This feature is enabled by default and does not change existing app enablement or blocking behavior.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1218713](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1218713)

### May 2026 – Microsoft Entra ID Account Recovery

Microsoft is introducing Entra ID Account Recovery, a new advanced recovery feature that helps users regain access to organizational accounts if they lose all registered authentication methods. Unlike a standard password reset, this feature securely verifies the user’s identity and re-establishes trust before allowing new authentication methods to be set up.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=529856](https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=529856)

### May 2026 – Retention Based on “Last Accessed” for OneDrive and SharePoint

Previously, retention policies could delete content based on conditions such as ‘_When items were created’_ or ‘_When items were last modified’_. Microsoft is now enhancing Data Lifecycle Management by introducing a new _“When items were last accessed”_ condition for retention policies.

This feature allows admins to manage and automatically clean up OneDrive and SharePoint content based on access history. It improves storage hygiene and helps optimize Microsoft 365 Copilot responses.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC999442)

### May 2026 – Chat With Anyone in Teams Using an Email Address

Teams will soon allow users to chat with external contacts using their email addresses, even if those contacts do not have a Teams account. External users will receive an invitation to join as guests. This experience, which will be in General availability follows your organization’s B2B Guest policy and will be enabled by default.

Admins can disable chat with anyone using an email address by setting UseB2BInvitesToAddExternalUsers as false in _Set-CsTeamsMessagingPolicy_ cmdlet.

**_Ref:_** [https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1182004](https://admin.cloud.microsoft/?ref=MessageCenter/:/messages/MC1182004)

### May 1, 2026 – Retirement of IDCRL Authentication in SharePoint and OneDrive

Microsoft is retiring the legacy IDCRL (Identity Client Run Time Library) authentication protocol in SharePoint and OneDrive for Business as part of the Secure Future Initiative. Legacy authentication will be permanently blocked beginning May 1, 2026, with modern OpenID Connect and OAuth protocols taking precedence.

**Solution:** Organizations should transition to modern authentication as soon as possible.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184649](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184649)

### May 15, 2026 – Update Browsers for Microsoft Teams Web Access

Microsoft Teams on the web will require support for modern browser standards, including ECMAScript 2022 (ES2022). Users accessing Teams through unsupported browsers will see reminder banners until May 14, 2026, after which access will be blocked starting May 15, 2026.

This change is enabled by default and does not impact Teams desktop or mobile clients. Unsupported browsers may cause sign-in interruptions due to Conditional Access policy enforcement.

**Solution:** Ensure users access Microsoft Teams on the web using browser versions that support ECMAScript 2022 (ES2022).

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230888](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230888)

### Mid-May 2026 - Exchange Online PowerShell Cmdlet to Change Meeting Organizer

Microsoft is introducing a new **Exchange Online PowerShell cmdlet** that allows administrators to change the organizer of an existing meeting or meeting series. This long-awaited capability ensures meeting continuity when the original organizer changes roles or leaves the organization, eliminating the need to recreate recurring meetings. The feature is enabled by default.

*   New organizers can manage meeting settings and attendees after transfer.
*   Internal attendees’ calendars update automatically with the new organizer.
*   External attendees receive updated meeting notifications and must ~reaccept~accept the meeting.
*   Meeting history is preserved, preventing abandoned meeting series.
*   Future updates will allow organizer changes directly from Outlook on the web, the new Outlook, and Teams calendars.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1227623](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1227623)

## June 2026 (Attention Needed: 11)

### June 2026 – New Secure Workflow to Bypass Legal Holds and Retention Policies in Microsoft Purview

Admins will have the ability to permanently delete sensitive Exchange mailbox content, bypassing retention policies and eDiscovery holds. This will be possible through the “Priority Cleanup Administrator” role, which grants authorized users’ permission to initiate Priority Cleanup for Exchange, allowing exceptions to standard retention and legal hold policies.

Since this process is irreversible and overrides existing policies, Microsoft has built-in approvals and special auditing for security.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=392838](https://www.microsoft.com/en-in/microsoft-365/roadmap?filters=&searchterms=392838)

### June 2026 - Credential Parameter Retirement in Exchange Online PowerShell

Exchange Online PowerShell is deprecating the **_-Credential_** parameter in versions released after June 2026, as it relies on the legacy ROPC authentication flow that does not support MFA or Conditional Access. This change applies to both the **_Connect-ExchangeOnline_** and **_Connect-IppsSession_** cmdlets.

**Solution:** Move to secure authentication methods such as _interactive sign-in, app-only authentication, or managed identity authentication_ when connecting to Exchange Online PowerShell.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/deprecation-of-the--credential-parameter-in-exchange-online-powershell/4494584](https://techcommunity.microsoft.com/blog/exchange/deprecation-of-the--credential-parameter-in-exchange-online-powershell/4494584)

### June 2026 - Admin Policy Support for Expiring “People in Your Organization” Links

Microsoft is introducing admin policies to automatically expire _“People in your organization”_ sharing links in SharePoint Online, enabling tighter control over internal content sharing. Administrators can now define organization-wide expiration periods such as _30 days, 90 days, or a custom duration_ based on data governance requirements.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=553220#Roadmap](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=553220#Roadmap)

### June 2026 – Microsoft Teams Pro Management Portal for Teams Devices

Microsoft is transitioning Teams Android device management to the **Teams Pro Management portal**, enabling centralized management of devices such as Android-based Teams Rooms, panels, and Teams phones. Administrators can use this portal for device inventory management, health monitoring, analytics, and lifecycle management across Windows and Android Teams devices from multiple manufacturers.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=555235](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=555235)

### June 1, 2026 – Retirement of the Sway Windows Desktop App

Microsoft is retiring the Sway Windows desktop app to streamline app management and focus on a single, fully supported web platform.

**Solution:** Users should switch to the web version at _sway.cloud.microsoft_, which provides the same features, preserves all content, and offers improved accessibility and updates.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1213784](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1213784)

### June 1, 2026 – End of Sale of Standalone SharePoint and OneDrive Plans

Microsoft is ending the sale of standalone _SharePoint Online Plan 1 and Plan 2_ and _OneDrive for Business Plan 1 and Plan 2_. Starting June 1, 2026, new customers will no longer be able to purchase these standalone plans.

**Solution:** Move to Microsoft 365 suite offerings such as **Business Basic,** **Business Standard, Business Premium, E1, E3, or E5** for continued service availability.

**_Ref_**: [https://learn.microsoft.com/en-us/partner-center/announcements/2026-january#retirement-of-standalone-sharepoint-online-and-onedrive-for-business-plans-plan-1-and-plan-2](https://learn.microsoft.com/en-us/partner-center/announcements/2026-january#retirement-of-standalone-sharepoint-online-and-onedrive-for-business-plans-plan-1-and-plan-2)

### Late-June 2026 – Integration of Adaptive Protection with Data Lifecycle Management

Microsoft plans to make the Adaptive Protection and Data Lifecycle Management (DLM) integration generally available by late June 2026. This integration allows administrators to retain or restore items deleted by high-risk users, providing better safeguards against insider threats and accidental data loss.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC791110)

### End of June 2026 – Unified Management of Teams Apps Across Microsoft 365

Microsoft is finalizing the rollout of Unified App Management for Teams, Outlook, and the Microsoft 365 app. This update simplifies app management by consolidating the separate admin experiences into a single, centralized management interface. The unified experience will be fully available to all organizations by the end of June 2026.

**_Ref:_** [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC796790](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC796790)

### June 29, 2026 – Deprecation of Teams Live Events

Microsoft is retiring Teams Live Events and related Microsoft Graph APIs on June 30, 2026. Existing live events will continue to function until _February 28, 2027_, but customers will no longer be able to schedule new Teams Live Events, including through Dynamics 365, after the retirement date. The _isBroadcast_ property in the _onlineMeeting_ Graph resource will remain available only until June 30, 2026.

**Solution:** Migrate to **Teams town halls** and updated **Teams meeting Graph APIs**, and update workflows or applications that depend on the _isBroadcast_ property by **_June 29, 2026_**.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1226495](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1226495)

### June 30, 2026 – Retirement of Assignments and Courses ACEs in Viva Connections and SharePoint

To modernize Viva Connections, Microsoft will retire the Assignments and Courses adaptive card extensions (ACEs) and their SharePoint dashboard web parts for Education tenants. These SPFx components currently surface assignment and course information on the dashboard, and their removal aims to reduce redundancy and streamline the user experience. Also, the existing components will reach the end of support on June 30, 2026.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184647](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1184647)

### June 30, 2026 – Exchange Web Services Will Be Blocked for Kiosk and Frontline Licenses

Microsoft will block Exchange Web Services access for mailboxes that do not include EWS usage rights starting June 30, 2026. After enforcement, requests made without a supported license will return an HTTP 403 error. Impacted licenses include Exchange Online Kiosk, Microsoft 365/Office 365 F1, and F3.

**Solution:** To continue using EWS, assign a license that includes EWS access, such as **Exchange Online Plan 1 or 2** or **Microsoft 365 E3/E5**.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/update-to-ews-access-for-kiosk–frontline-worker-licensed-users/4474299](https://techcommunity.microsoft.com/blog/exchange/update-to-ews-access-for-kiosk--frontline-worker-licensed-users/4474299)

## Q3 2026 (Attention Needed: 9)

### July 01, 2026 – Microsoft 365 Price Increase

Starting July 1, 2026, Microsoft will implement a global price increase across all Microsoft 365 plans. Prices will increase by 5% to 33%, depending on the SKU. The increase reflects ongoing investments in AI capabilities, security enhancements, and advanced management features.

Alongside the price increase, Microsoft is adding value to select plans:

*   **Microsoft 365 Business Premium** will receive an **additional 50 GB of email storage** at no extra cost.
*   **Advanced Microsoft Intune capabilities** will be included with **Microsoft 365 E3 and E5** subscriptions.
*   Microsoft will include **Security Copilot in E5** subscriptions at no additional cost.

**_Ref:_** [https://www.microsoft.com/en-us/microsoft-365/blog/2025/12/04/advancing-microsoft-365-new-capabilities-and-pricing-update/](https://www.microsoft.com/en-us/microsoft-365/blog/2025/12/04/advancing-microsoft-365-new-capabilities-and-pricing-update/)

### July 1, 2026 – DNS Provisioning Change for Accepted Domains

Microsoft is updating DNS provisioning for new Accepted Domains to support DNSSEC adoption. Starting July 1, 2026, A records for newly added Accepted Domains will be created under **mx.microsoft** subdomains instead of _mail.protection.outlook.com_.

Organizations using automation or workflows that rely on _mail.protection.outlook.com_ for MX record configuration may experience mail flow issues unless updated. Going forward, the _List serviceConfigurationRecords_ Microsoft Graph API will become the authoritative source for retrieving MX record values.

**Solution:** Update domain provisioning or MX record automation to use the **List serviceConfigurationRecords** Graph API instead of relying on _mail.protection.outlook.com_ before July 1, 2026.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1048624](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1048624)

### July 14, 2026- InfoPath 2013 Client and InfoPath Forms Services in SharePoint Online will be Retired

InfoPath Client 2013 will reach the end of its extended support period on July 14, 2026, and to keep an aligned experience across Microsoft products, InfoPath Forms Service will be retired from SharePoint Online.

**Solution:** To understand the usage of InfoPath within your organization, you can utilize the [Microsoft 365 Assessment tool](https://aka.ms/assessment/infopath) to scan your tenant and analyze InfoPath usage. If you are currently using InfoPath, you can initiate the migration process to modern alternatives such as Power Apps, Power Automate, or Forms.

**_Ref:_** [https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190](https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/support-update-for-infopath-forms-services-in-microsoft-365/ba-p/3858190)

### July 14, 2026 - End of Support for SharePoint Designer 2013

Microsoft will retire SharePoint Designer 2013 in accordance with the Microsoft Fixed Lifecycle Policy to support the transition toward modern workflow automation and customization experiences. After July 14, 2026, Microsoft will no longer provide technical support, security updates, or product fixes, and no extensions or exceptions will be available.

**Solution:** Use SharePoint Migration Tool (SPMT) 4.1 to assess existing workflows and migrate them to Power Automate by **July 13, 2026**.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230891](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1230891)

### July 2026 – SharePoint Alerts will be Fully Retired

Microsoft will discontinue support for SharePoint Alerts. Existing alerts can no longer be modified and will eventually stop functioning.

**Solution:** Microsoft recommends migrating SharePoint Alerts to Power Automate or SharePoint Rules. Use the Microsoft 365 Assessment tool to review alerts and plan the move.

**_Ref_**_:_ [https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f](https://support.microsoft.com/en-us/office/sharepoint-alerts-retirement-813a90c7-3ff1-47a9-8a2f-152f48b2486f)

### Aug 1, 2026 – Microsoft Defender Threat Intelligence to Merge with Defender and Sentinel

Microsoft Defender Threat Intelligence will merge with Microsoft Defender and Microsoft Sentinel by August 1, 2026, bringing threat intelligence directly into the SecOps workflow. After the transition, threat insights will be available through the Microsoft Defender portal, with enhanced Threat Analytics that include:

*   Indicators of Compromise (IoCs) integrated into reports
*   MITRE ATT&CK mappings for tactics and techniques
*   Insights into threat actors and targeted industries
*   IoCs linked to cases for Microsoft Sentinel customers

After August 1, 2026, accessing MDTI capabilities will require an **active Microsoft Defender or Microsoft Sentinel license**.

**Solution:** Plan your transition to Microsoft Defender or Microsoft Sentinel before the deadline and review licensing to ensure uninterrupted access to MDTI capabilities.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1192257](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1192257)

### Sep 2026 – Update PowerPoint Client Versions to Access Captions & Subtitles

Microsoft is upgrading the backend service that supports Captions & Subtitles in PowerPoint. As a result, users running Microsoft 365 PowerPoint app versions earlier than 16.0.19426.20218 (Windows) or 16.103.1207.4 (macOS) will lose access to caption and subtitle features after the update.

**Solution:** Update PowerPoint clients to Windows (Win32) 16.0.19426.20218 or macOS 16.103.1207.4 or later.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1231437](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1231437)

### Sep 2026 – Update Office Apps to Keep Read Aloud, Transcription, and Dictation Features

Read Aloud, Transcription, and Dictation features in Microsoft 365 Office apps will stop working on versions earlier than 16.0.18827.20202 because of backend upgrades. This change takes effect after September 2026 for Worldwide tenants and November 2026 for GCC, GCC High, and DoD environments.

**Solution:** Update all Office apps to 16.0.18827.20202 or later before the deadline.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1127222](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1127222)

### Sep 17, 2026 – Retirement of Legacy Education LTI Tools

Microsoft is retiring legacy Education LTI tools (Teams Assignments, OneDrive, OneNote Class Notebook, Reflect) on September 17, 2026, replacing them with a unified Microsoft 365 LTI tool. Users and admins will need to transition to the Microsoft 365 LTI unified tool.

**_Ref_**: [https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1160188](https://admin.microsoft.com/Adminportal/Home#/MessageCenter/:/messages/MC1160188)

## Q4 2026 (Attention Needed: 9)

### Oct 2026 – Just in Time Protection on SharePoint in DLP

Microsoft is introducing Just-in-Time protection for SharePoint in Microsoft Purview Data Loss Prevention in preview.

With this feature, organizations can automatically apply DLP restrictions to unclassified files when they are accessed or shared externally. Instead of restricting files in advance, JIT protection enforces security measures only when there is a risk of data leaving the organization.

**_Ref_**: [https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457](https://www.microsoft.com/en-us/microsoft-365/roadmap?searchterms=139457)

### Oct 01, 2026- Retirement of Exchange Web Services in Exchange Online

October 1, 2026, Microsoft will start blocking EWS requests from non-Microsoft apps to Exchange Online. The changes in Exchange Online do not affect Outlook for Windows or Mac, Teams, or any other Microsoft product.

**Solution**: Migrate your applications to Microsoft Graph to access Exchange Online data and gain access to the latest features and functionality.

**_Ref_**_:_ [https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-exchange-web-services-in-exchange-online/ba-p/3924440](https://techcommunity.microsoft.com/t5/exchange-team-blog/retirement-of-exchange-web-services-in-exchange-online/ba-p/3924440)

### Oct 01, 2026- Sign-in Risk Policy and User Risk Policy Retirement from Entra ID Protection

User risk policy or Sign-in risk policy UX in Entra ID Protection (formerly Identity Protection) will be retired on October 1, 2026.

**Solution:** Migrate Sign-in risk and User risk policies to Conditional Access.

**_Ref_**_:_ [https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/what-s-new-in-microsoft-entra/ba-p/3796395](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/what-s-new-in-microsoft-entra/ba-p/3796395)

### Oct 13, 2026- Retirement of Microsoft Publisher

In October 2026, Microsoft will discontinue Publisher in Microsoft 365, with on-premises suite support ending. While support lasts, they’re exploring modern alternatives across Word, PowerPoint, and Designer for common Publisher tasks, with updates forthcoming.

**_Ref:_** [https://admin.microsoft.com/?ref=MessageCenter/:/messages/MC716267](https://admin.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC716267)

### Mid-Oct 2026 – Content Security Policy for Entra ID Sign-in Experience

Microsoft Entra ID is enforcing a stricter Content Security Policy (CSP) for sign-ins starting mid-October 2026. Only trusted Microsoft scripts will be allowed, blocking injected code to reduce XSS risks. This applies to browser-based sign-ins on _login.microsoftonline.com_ and does not affect Entra External ID tenants.

**Solution:** If you use tools or extensions that inject code, switch to non-injecting alternatives and [test sign-in flows](https://learn.microsoft.com/en-us/entra/identity-platform/content-security-policy#how-to-prepare-for-csp-enforcement) before CSP enforcement begins.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1191924](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1191924)

### Oct 28, 2026 – Retirement of Microsoft Entra PIM Iteration 2 (Beta) APIs

Microsoft will retire Microsoft Entra Privileged Identity Management Iteration 2 (beta) APIs on October 28, 2026. After this date, applications and scripts using these APIs will fail because the endpoints will no longer return data.

**Solution:** Migrate to the Iteration 3 (GA) APIs, which are fully supported and more reliable. Stop new development on Iteration 2 APIs and begin migration planning.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1181281](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1181281)

### Dec 2026 – Custom Retention for Message Trace Logs in Exchange Online

Starting in December 2026, organizations will be able to select how long Message Trace data is retained by choosing from a set of predefined retention periods. This enhancement gives admins greater flexibility to align log retention with their compliance, audit, and operational requirements.

**_Ref:_** [https://www.microsoft.com/en-in/microsoft-365/roadmap?id=542929](https://www.microsoft.com/en-in/microsoft-365/roadmap?id=542929)

### End of Dec 2026 – Disable SMTP Auth for Basic Authentication

SMTP AUTH Basic Authentication will be disabled by default for existing tenants by Dec end, though admins can enable it if required.

**Solution:**

*   Migrate applications and devices to OAuth-based authentication.
*   Use alternatives such as High-Volume Email for Microsoft 365, Azure Communication Services for Email, or an on-premises Exchange.

**_Ref_**: [https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835](https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835)

### Dec 31, 2026 – End of Support for Dynamics 365 Guides and Remote Assist

Dynamics 365 Guides and Dynamics 365 Remote Assist will retire on December 31, 2026. After this date, the products will no longer receive security updates, bug fixes, or technical support.

**Solution:** Customers should plan their transition early by identifying dependent users and scenarios. Explore alternative mixed reality solutions available in the [Microsoft Marketplace](https://marketplace.microsoft.com/marketplace/apps?category=mixed-reality), and consider Microsoft Teams Mobile with [spatial annotation](https://learn.microsoft.com/en-us/dynamics365/mixed-reality/remote-assist/teams-mobile-annotate) for certain remote collaboration use cases.

**_Ref:_** [https://learn.microsoft.com/en-us/lifecycle/announcements/dynamics-365-guides-remote-assist-end-of-support](https://learn.microsoft.com/en-us/lifecycle/announcements/dynamics-365-guides-remote-assist-end-of-support)

## 2027 (Attention Needed: 6)

### Jan 2027 – Retirement of Basic Authentication for Client Submission in Exchange Online

Microsoft will disable Basic Authentication with Client Submission (SMTP AUTH) by default starting January 2027. OAuth will be the supported authentication method.

**Proactive Steps:**

*   Move applications and devices to OAuth-based authentication for SMTP AUTH.
*   If Basic Authentication is still needed, consider alternatives such as High-Volume Email for Microsoft 365, Azure Communication Services for Email, or an on-premises Exchange Server in a hybrid setup.

**_Ref:_** [https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835](https://techcommunity.microsoft.com/blog/exchange/updated-exchange-online-smtp-auth-basic-authentication-deprecation-timeline/4489835)

### Jan 31, 2027 – Retirement of MDE and XDR Advanced Hunting APIs

To unify the interface across Microsoft Defender products, Microsoft will retire the Microsoft Defender for Endpoint (MDE) Advanced Hunting API and Microsoft Defender XDR Advanced Hunting API.

**Solution:** Move to Microsoft Graph Security API for broader data coverage, improved consistency, and better scalability for automation and security workflows.

**_Ref:_** [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1220762](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1220762)

### March 01, 2027 – Automatic Migration to New Outlook for Windows

Microsoft 365 Enterprise users will automatically switch to the new Outlook for Windows, gaining access to modern features like Copilot, theming, and time-saving options such as Pinning and Snoozing emails. A toggle will be available for users to revert to the classic Outlook. Admins can prevent this automatic migration via cloud policy.

The opt-out phase originally scheduled for April 2026 has been postponed to March 1, 2027, providing organizations with additional time to prepare.

**_Ref_**_:_ [https://admin.microsoft.com/#/MessageCenter/:/messages/MC949965](https://admin.microsoft.com/#/MessageCenter/:/messages/MC949965)

### March 2027 – Retirement of Security Questions in Microsoft Entra Self-Service Password Reset

Microsoft will retire security questions as an authentication method for Self-Service Password Reset (SSPR) in Microsoft Entra ID starting March 2027, due to security vulnerabilities and low verification reliability.

After this retirement, users will no longer be able to verify their identity using security questions during password reset. Organizations that continue relying on this method may experience failed password reset attempts, user lockouts, and increased help desk support requests.

**Solution:** Ensure users are registered with [supported authentication methods](https://learn.microsoft.com/en-us/entra/identity/authentication/tutorial-enable-sspr#select-authentication-methods-and-registration-options) before March 2027 to avoid Self-Service Password Reset failures.

**_Ref:_** [https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-security-questions](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-security-questions)

### Oct 2027 – Removal of Passcode Option from Create Meeting API

In October 2027, Microsoft will remove the option to create meetings without passcodes. This means all online meetings created through the Microsoft Graph API will automatically require a passcode, and the _isPasscodeRequired_ property on the _joinMeetingIdSettings_ resource will be removed. This change ensures that every meeting is consistently secured with a passcode, simplifying meeting creation, and improving security.

**_Ref:_** [https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC985483](https://admin.cloud.microsoft/#/MessageCenter/:/messages/MC985483)

### Oct 14, 2027 – Retirement of Duplicative Properties in Passkey (FIDO2) Authentication Methods Policy

To align with the updated passkey policy API schema that supports group-based passkey profiles, Microsoft will retire _isAttestationEnforced_ and _keyRestrictions_ from the fido2AuthenticationMethodConfiguration API. During the transition, these properties will sync with attestationEnforcement and keyRestrictions in the Default passkey profile.

**Solution:** Admins should update configurations, automations, and integrations to use the new schema.

**_Ref_**: [https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1188230](https://admin.cloud.microsoft/?#/MessageCenter/:/messages/MC1188230)

In conclusion, navigating the ever-evolving landscape of Microsoft 365 requires staying informed about the changes 🔍. By proactively adapting to these changes, you can optimize your Microsoft 365 experience, maximize productivity, and effectively plan for the future. 💪

We are committed to keeping this blog updated with the latest information, so stay tuned for upcoming updates.

[https://blog.admindroid.com/microsoft-365-end-of-support-milestones/](https://blog.admindroid.com/microsoft-365-end-of-support-milestones/)