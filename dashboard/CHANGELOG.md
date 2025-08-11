# Dashboard v3.15.2 | 2025-08-11

## New
- Added support in Chat Builder to enable or disable the conversation search feature.
- Moved conversation search settings in the dashboard from **Chat > Settings** to **Chat > Features** for improved accessibility.
- Added support to integrate Chat Builder with Android and iOS apps, including downloadable app versions for both platforms.
- Introduced real-time preview via QR code scanning from Android and iOS apps.

## Enhancements
- Updated the mechanism for applying preview settings by introducing temporary builder settings in the dashboard flow, with an automatic time-to-live (TTL) of 24 hours.
- Android and iOS integrations are available for the code-based version of Chat Builder only.

## Fixes
- Implemented bug fixes and UI enhancements for the conversation feature in React code and no-code apps, covering threaded view, user/group info, and user profile view.
<br>


# Dashboard v3.15.0 | 2025-07-30

## New
- Added no-code widget support in Chat Builder, allowing users to embed chat functionality without writing any code.
- Introduced conversation search functionality in Chat Builder, available in both code and no-code implementations.
- Added support for integrating **Chat Builder** with platforms such as **HTML** and **WordPress**, making it easier to embed chat experiences with minimal setup. 
- **Coming soon**: Support for **Shopify**, **Squarespace**, **Wix**, and **Webflow**.

## Enhancements
- Renamed "Visual Builder" to "Chat Builder" for improved clarity and alignment with product direction.
- The new Chat Builder widget includes all existing functionality, layout options (docked and embedded), advanced methods and customisations from Legacy Widgets.
- No-code widget now fully supports all features available in the code-based version of Chat Builder.
- Updated the UI for the Create App screen and the Welcome screen in the onboarding flow to enhance the user experience.
- Updated UI Kit and SDK versions to their latest versions in Chat Builder for improved performance and visual consistency.

## Fixes
- None

## Deprecations
- Legacy Widgets are now deprecated for newer customer accounts. Users are encouraged to use Chat Builder for the latest features and customisation options.
<br>


# Dashboard v3.14.12 | 2025-07-16

## New

- **"Get Started" Screen for AI Agents**  
  A new **Get Started** screen has been introduced under the **AI Agents** section to assist users in setting up AI-powered chat experiences.  
  Selecting "Get Started" navigates users directly to the **Custom Agents** configuration screen for a streamlined onboarding process.

## Enhancements

- The **"AI Chatbot"** section has been renamed to **"AI Agents"** in the navigation menu to reflect expanded capabilities and improve clarity.
- **"Custom Bots"** have been renamed to **"Custom Agents"** for greater alignment with current terminology and feature scope.

## Deprecations

- **AI Bots and Personalities**  
  The legacy **AI Bots** and **Personalities** features have been deprecated and are no longer available for new configurations.  
  Existing configurations will continue to function as expected but are no longer supported for new setup.

## Fixes

- **Moderation – Get Started and Overview Screens**  
  Addressed various UI and content-related issues in the **Moderation Get Started** and **Overview** screens, enhancing layout consistency, readability, and overall usability.
<br>


# Dashboard v3.14.11 | 2025-07-04

## New

- **"Get Started" Section for Moderation**  
  A new **Get Started** section has been added under the **Moderation** tab to help users easily understand and set up moderation in their apps.

  Highlights include:
  - A visual overview of how moderation works, with an example of a flagged message.
  - Easy access to key setup actions:
    - **Set Up Rules**
    - **Configure Moderation Webhook**
    - **Integrate & Test Moderation API**
  - Quick links to tutorial, documentation, and relevant app sections to guide users through the process.
  - Users can intuitively switch between the **_Get Started_ and _Setup_ views** for a smoother experience.

  This update streamlines the moderation onboarding experience and helps teams get started faster with content safety tools.
  
  ## Enhancements
  - None
  
  ## Fixes
  - None
<br/>


# Dashboard v3.14.10 | 2025-07-01

## New
- None

## Enhancements
- Renamed **“Non AI Bots”** to **“Custom Bots”** for improved clarity in bot configuration.
- Removed the **Upgrade plan banner** from the **Legacy Moderation** screen as **Legacy Moderation** is now deprecated for newer apps.
- Updated the **Current Usage** display in **App Overview** to show **monthly usage** for annual plans, providing more relevant insights.

## Fixes
- Fixed an issue with the **Insights calendar** where date selection was not functioning correctly.
- Resolved a **UI bug with radio button options** in the Visual Builder.
- Fixed UI issues in the **App/Builder Creation success/failure modals** for a smoother user experience.
- Fixed **loader alignment issues** on buttons to ensure proper layout and feedback.
- Removed inconsistent **background image** from onboarding screens for a cleaner appearance.
<br/>


# Dashboard v3.14.9 | 2025-06-11

## New
- [Visual Builder] Added `showScrollbar` prop support to the following components for improved UI control:
  - `CometChatConversations`
  - `CometChatUsers`
  - `CometChatGroups`
  - `CometChatMessageList`
  - `CometChatMessageComposer`

## Enhancements
- Added support for **React UI Kit version 6.0.7**, bringing the latest improvements and refinements to the Visual Builder experience.

## Deprecations
- Deprecated the following **legacy extensions** for apps where they have not been enabled:
  - **Mentions**
  - **Reactions**
  - **Smart Reply**
  - **Legacy Notifications**
  - **Legacy Moderation**

  These extensions will no longer appear for new or inactive apps, ensuring a cleaner and more streamlined configuration experience.

## Fixes
- Addressed UI issues across multiple sections, including Integrate, Groups, App navigation, Visual Builder, Moderation, Chats, Bots, and Notifications for improved user experience.
- [Visual Builder] Resolved an issue where the **message list** caused the entire webpage to scroll to the bottom on load.
- [Visual Builder] Fixed a **UI spacing issue** where there was a missing space between the **member count** and the **member** keyword.
- [Visual Builder] Fixed a **crash** caused by **unsupported regular expression features** in certain JavaScript engines, improving cross-browser stability.
<br/>


# Dashboard v3.14.8 | 2025-06-04

## New
- **Call Notification Preferences**  
  Added a new option under **Notifications → Preferences → Common Preferences** to configure all call notifications behaviour.

- **Custom Push Notification Payloads**  
  Customers can now customise push notification payloads and include additional metadata via  
  **Notifications → Preferences → Push Notification Preferences**, offering greater flexibility and control.

- **Extensions Update**  
  A new extension lifecycle model has been implemented. Extension states are reflected in **Chat Features**, **Legacy Moderation**, and **Legacy Notifications** sections:
  
  - **Legacy Extensions**  
    - A **"Legacy" tag** will appear next to these extensions in the UI.  
    - **Email Replies, Mentions, Reactions, Smart Reply** are now marked as Legacy.

  - **Deprecated Extensions**  
    - Extensions are completely removed from the dashboard.  
    - No longer available to any users.  
    - **Slow Mode, XSS Filter, E2E Encryption, Applozic, Video Broadcasting, Emojis, Gfycat, Avatar** are now deprecated.

## Enhancements
- **Two-Factor Authentication (2FA) Defaults Updated**  
  - **Free plan users**: 2FA is now **disabled by default**, but can be manually enabled from Account Settings.  
  - **Paid plan users**: 2FA is **enabled by default** upon subscription, with the option to disable it.  
  - **No impact** on existing users — their current 2FA settings remain unchanged.

- **AI Settings Migration**  
  - AI settings have been moved from the **AI Chatbot** section to **Chat Settings → AI User Copilot**.  
  - The **"Enable AI" toggle has been removed** — AI activates automatically when valid settings (Model, API Key, Temperature, etc.) are provided.  
  - During bot creation, users are now redirected to configure AI settings before proceeding.  
  - This update streamlines configuration and improves the overall AI setup experience.

## Fixes
- Fixed an issue where the **Upgrade tag** appeared on **Message Basic Webhooks** for users on the **Advanced plan**.
- Fixed an issue where an **incorrect label** was displayed for the **Group Type** field on the **Add Group** screen.
<br/>


# Dashboard v3.14.7 | 2025-04-19
## New
- **AI-Based Moderation**  
  - Introduced support for **OpenAI-based content moderation** and a **Custom Moderation API**, enabling more intelligent and context-aware filtering of user messages.
  - Configure your own **OpenAI key, model, temperature**, and **prompt** directly from the dashboard.
  - Use **custom APIs** for moderation with flexible error-handling options.
  - Added new moderation list types: **OpenAI Prompt** and **Custom Moderation API**.
  - **Default AI moderation rules** are now added automatically to help users get started quickly.
  - App owners can **define custom rules** for both OpenAI and Custom API-based moderation.
  - Available for **Build** and **Enterprise** plans only.
  
 - **Notification Preference Toggle for Mentions**  
  Added a toggle under **Notifications > Common Preferences** to **ignore end-user mute settings when the user is mentioned in a message**, ensuring important mentions are delivered.

- Added **Push Notification Logs** in the dashboard, enabling app owners to view logs of failed push notifications—helping diagnose delivery issues.
  
- Added **"Upgrade" tags** to premium features based on the user's current plan. Tags now appear on:
  - **Chat Features**
  - **Webhooks (New)**
  - **Legacy Notifications**

## Enhancements
- Added **hover states** for buttons and links across the dashboard to improve interactivity and visual feedback.
- Updated text and made visual improvements to the **Upgrade banner** for better clarity and engagement.
- Visual Builder: **App Export Improvements** - App credentials are now included by default when exporting a **React app**, simplifying setup and reducing integration steps.
- Visual Builder: **AI Settings Control** - Disabled **AI features by default**, giving developers more control over when and how AI is used in the Visual Builder.
- Visual Builder: **Codebase Consistency** - Updated **nomenclature in core files** to improve code clarity, readability, and maintainability.

## Fixes
- Fixed an issue where users were **unable to scroll** on the Moderation Settings page.
- Fixed a bug where the **"Cancel" button** on the "Add User Role" dialog was not working.
- Resolved an **overflow issue** with graphs on the App Overview page, ensuring content stays within bounds.
- Fixed **double border rendering** in Webhooks forms for a cleaner UI.
- Fixed UI issue being faced after page reload in create application.
- Fixed success notification issue on enabling Conversation search feature.
- Fixed a UI issue where **feature toggle borders** were inconsistent on the Visual Builder toggle list.
- Resolved an issue where the toggle for **Custom Push Notification Provider** was **enabled by default** when it shouldn't be.
- Visual Builder: Fixed an issue where the "Show Back Button" setting in the sample app was not applying correctly.
- Visual Builder: Fixed a bug where the Owner scope was not updating when a user left a password-protected group.
- Visual Builder: Resolved a problem where the delete chat toggle was not working for new conversations.
- Visual Builder: Fixed a UI issue in the voice calling screen, ensuring consistent visual behavior during calls.
- Visual Builder: Fixed a bug where the Leave Group option appeared even when the owner was the only member in the group.
- Visual Builder: Fixed an issue where the Info page did not close after creating a new group.
- Visual Builder: Fixed a bug where pressing Enter in the group member search box triggered the last performed action prior to opening the search.
- Visual Builder: Fixed a layout issue where, on clicking "Add Members", the user list appeared on only half the screen and overlapped with the group info panel.
<br/>


# Dashboard v3.14.6 | 2025-05-08
## New
- Added **Next.js** to the technology list when creating a new app, expanding framework options.
- Added a **React Integration video** to the "Integrate" page, guiding users on how to integrate React apps using Visual Builder.
- Included a **Status Page** link under both **Resources** and **Quick Links** on the dashboard for easier access to system health updates.
- Introduced a **"Subscribe Plan" banner** for expired apps, displayed regardless of usage status to encourage timely reactivation.

## Enhancements
- Renamed **Next JS** to **Next.js** across the dashboard for naming consistency.
- Updated the title text for **upselling banners** across the dashboard to improve clarity and consistency.

## Fixes
- Redirected users with **expired apps** to the **Plans and Billing** section instead of the Integrate page for a more relevant experience.
- Fixed broken UI in the **restricted view of the Integrate section** when accessed from an expired app.
- Resolved an issue where the **Upgrade Plan banner** was affecting the layout of the app navigation.
- Fixed navigation issues on **smaller screen resolutions** for improved accessibility and usability.
<br/>


# Dashboard v3.14.5 | 2025-05-05
## New
- Added a banner prompting users to subscribe to a plan for free apps with active usage.

## Enhancements
- Updated UI Kit to version **6.0.5**
- Removed Chat SDK as a direct dependency; it is now managed as a **peer dependency** via the updated UI Kit.
- Changed the "Current Usage" label in the App Overview from *CCU* to *PCC* for improved clarity.
- Added explanatory text to the App Overview noting that "Current Usage" reflects the current billing cycle.
- Updated the subtext for the Sample App link in Quick Links to: “Explore ready-to-use app examples on GitHub.”
- Made the order of items in the Resources and Quick Links lists consistent across the dashboard.
- Improved app navigation by adding scroll functionality and refining scrolling behavior on smaller resolutions.

## Fixes
- Fixed a UI issue with selecting list inputs in the Moderation rule Add/Edit interface.
- Fixed a bug where the Voice Message feature appeared in the Chat Widget settings, despite not being configurable.
<br/>


# Dashboard v3.14.4 | 2025-04-30
## New
- None

## Enhancements
- None

## Fixes
- Fixed an issue with Conversation Search setting on Chat settings.
<br/>


# Dashboard v3.14.3 | 2025-04-28
## New
- None

## Enhancements
- Updated React UI Kit version to 6.0.4, including changes to the CSS import path.
- Updated JS Chat SDK version to 4.0.12.

## Fixes
- Fixed a UI issue with the download modal that caused display inconsistencies.
- Redirected users to the "Integrate" section instead of "Overview" when current usage is 0, improving onboarding flow.
- Fixed UI issues on the Chat Settings and App General Settings pages for a more consistent experience.
- Fixed an incorrect documentation link for Next.js, ensuring accurate developer resources.
- Handled validation errors for incorrect pattern values entered in rule conditions.
<br/>


# Dashboard v3.14.2 | 2025-04-21
## New
- Added a dashboard toggle to enable or disable the Conversation Search feature.

## Enhancements
- None

## Fixes
- None
<br/>


# Dashboard v3.14.1 | 2025-04-15
## New
- None

## Enhancements
- Enhanced the webhooks create/update page to support the **Retry on Failure** option. When enabled, failed webhook events will automatically be retried, improving reliability.
- Updated text in the **Integrate** section for improved clarity.

## Fixes
- Resolved a broken link in multi-tenancy child apps that prevented users from accessing the parent app's billing screen.
- Fixed an issue where multiple visual builder creation attempts were triggered from the **Integrate** screen.
- Fixed an issue where customized builder settings in preview were not being cleared on the client side.
<br/>


# Dashboard v3.14.0 | 2025-04-08
## New

### Integrate Section Added 
A new **Integrate** section has been added under the app, making it easier for users to discover and follow integration steps directly.

### Visual Builder Support 
We’re excited to introduce **Visual Builder** support! 🎉 

New users can now preview their selected settings immediately after signing up.

Users can create, update, and reset their Visual Builder settings effortlessly.

Option to download a ready-to-use sample app based on the chosen customisations.

## Enhancements
- None.

## Fixes
- None   
<br/>


# Dashboard v3.13.2 | 2025-03-18
## New
### Custom Providers for Notifications

Introducing Custom Providers for Push, Email, and SMS notifications, giving customers greater flexibility in their notification delivery. This feature allows the use of alternatives to:

- FCM and APNs for Push notifications
- SendGrid for Email notifications
- Twilio for SMS notifications
- Customers can now add, modify, enable, and disable these providers, tailoring their notification infrastructure to better suit their needs.

## Enhancements
- None.

## Fixes
- Resolved incorrect scroll behaviour while fetching chat history in the dashboard. Addressed an issue where "Load More" was not working when auto-refresh was disabled. Improved performance and optimisations in fetching previous chat history.   
<br/>


# Dashboard v3.13.1 | 2025-03-12
## New
**Multi-tenant customers can now track cumulative usage across all their apps with flexible billing period options:**

- Current Period – Ongoing billing cycle.
- Previous Period (Including Current) – Last period + current cycle.
- Previous Period (Excluding Current) – Last period only.

## Enhancements
- None.

## Fixes
- UI fix in the overview screen.   
<br/>


# Dashboard v3.13.0 | 2025-02-10
## New
- Introduced a revamped **App Module Design**, featuring a modern interface with enhanced usability and smoother navigation.

## Enhancements
- Restructured **App Sections** to improve accessibility and streamline workflows, making it easier to access key features.

## Fixes
- Addressed various performance-related issues to enhance reliability and provide a smoother user experience.
- When adding or editing a rule in the category of conditions, selecting a pattern-type keyword list now correctly adds the category as "Pattern" instead of "Word."
- Resolved an issue where duplicate chat messages appeared in the live section of Chat History.   
<br/>


# Dashboard v3.12.8 | 2025-01-30
### New
- None

### Enhancements
-  None

### Fixes
- Fixed an issue that required a page reload to sign in after session expiration.   
<br/>


# Dashboard v3.12.7 | 2025-01-20
### New

- Added Two-Factor Authentication (2FA) for enhanced security during customer login.

### Enhancements

- None

### Fixes

- None   
<br/>


# Dashboard v3.12.4 | 2024-11-25
### New

**Moderation Feature Updates:**

- Filters in Rules: Added filters for Sender's and Receiver's messages based on properties like UID, GUID, name, created at, type, etc.
- New Condition Categories: Introduced categories such as AI Toxicity, AI Sentence Similarity, and AI Sentiment Analysis.
- Default Rules: Added default rules for Platform Circumvention, Scam Detection, Spam Detection, and AI Toxicity.
- Message Approval: Introduced the option to approve blocked messages.
- Sentence Similarity Lists: Added support for managing lists of the Sentence Similarity type.

### Enhancements
-  UI / UX changes to the Moderation feature.

### Fixes
- None
   
<br/>


# Dashboard v3.12.3 | 2024-11-12
### New
- None

### Enhancements
-  None

### Fixes
- Fixed an issue where a customer without an existing account could not be onboarded as a team collaborator to an app owned by another app owner.
   
<br/>


# Dashboard v3.12.2 | 2024-10-30
### New
- None

### Enhancements
-  Updated the Overview section terminology by changing "CCU" to "PCC" and "Concurrent Users" to "Concurrent Connections" for clearer, industry-aligned language.

### Fixes
- None
   
<br/>


# Dashboard v3.12.1 | 2024-09-30
### New
- None

### Enhancements
-  Updated notification preferences for **Message Edited** and **Message Deleted** events, enabling user customisation.

### Fixes
- None
   
<br/>


# Dashboard v3.12.0 | 2024-09-23
### New
- **New Pricing Plans**: We've introduced three new subscription plans—**Basic**, **Advanced**, and **Enterprise**—available for both monthly and annual billing. The **Basic** and **Advanced** plans are self-serve, offering streamlined pricing options, while the **Enterprise** plan includes customised solutions tailored to your business needs.

### Enhancements
- **Improved Plans & Billing UI**: The **Plans** listing on the **Plans & Billing** screen has been updated for a cleaner, more intuitive user experience, making it easier to compare and select the right plan.

### Fixes
- None
   
<br/>


# Dashboard v3.11.7 | 2024-09-12
### New
- Added app setting to enable Enable Enhanced Messaging Status, allowing group members to see when messages are delivered to and read by all, and to mark messages as unread. 
- Added two new message webhooks, one that indicates when message is delivered to all group members and second to  indicate when message is read by all group members.

### Enhancements
- None

### Fixes
- None
   
<br/>


# Dashboard v3.11.6 | 2024-09-09
### New
None

### Enhancements
- Introduced a toggle to activate or deactivate the Moderation feature for an app.

### Fixes
- None
   
<br/>


# Dashboard v3.11.5 | 2024-08-29
### New
- None

### Enhancements

- Optimised the Operational Data view by removing redundant data for a clearer presentation.
- Combined Users & Calls Operational Data view.
- The current Operational Data view now includes five graphs: Peak Concurrent Connections (past 30 days), Monthly Active Users (past 3 months), Voice Minutes (past 30 days), Video Minutes (past 30 days), and Recording Minutes (past 30 days).
- Current usage now displays data for apps with billing based on either Monthly Concurrent Users (MCU) or Daily Active Users (DAU) in addition to Monthly Active Users (MAU).

### Fixes
- None
   
<br/>


# Dashboard v3.11.4 | 2024-08-29
### New
- None

### Enhancements
- None

### Fixes
- Fixed the issue where the enabled status of Push, SMS, and Email notifications was not retained after page refresh.   
<br/>


# Dashboard v3.11.3 | 2024-08-21
### New
-  Added demo views for Push, Email, and SMS notifications across current (Growth & Scale) and all legacy plans.

### Enhancements
- Updated the 'Contact Us' link for apps scheduled for deletion to direct customers to the CometChat Help Center's new request form, replacing the previous link to the website's contact sales page.
- Renaming settings labels under Email and SMS notifications to better align with their intended actions.

### Fixes
- None
   
<br/>


# Dashboard v3.11.2 | 2024-08-21
### New
- None

### Enhancements
- None

### Fixes
- Resolved minor issues in the Operational Data section on the Overview page.   
<br/>


# Dashboard v3.11.1 | 2024-08-07
## New

-   None

## Enhancements

-   New medal images have been added to the login and signup screens.

## Fixes

-   Updated documentation links on the widgets Install page to match the new documentation.
-   Resolved minor issues in the Notifications module to improve user experience.   
<br/>


# Dashboard v3.11.0 | 2024-08-07
## New

-   Introduced new self-serve Scale plans with both monthly and annual subscriptions.

## Enhancements

-   None

## Fixes

-   Fixed an issue where the Invoice list was empty when navigating from the Plans tab to the Invoices tab.   
<br/>


# Dashboard v3.10.0 | 2024-08-07
## New

-   Configurations for Enhanced Email Notifications.
-   Configurations for Enhanced SMS Notifications.

## Enhancements

-   None

## Fixes

-   None   
<br/>

