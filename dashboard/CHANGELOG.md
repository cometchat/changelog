# Dashboard v3.15.22 | 2025-12-02

## New
- Added a **Knowledge Base** option in the AI Agent Builder, allowing you to connect a content source and sync your data—via file uploads or text entries—as a reference for your agent. This knowledge will be used by the agent to provide informed and context-aware responses during conversations.

## Enhancements
- Added a (*) indicator in the AI Agent Builder’s **MCP Tools** and **Custom API Tools** add/edit forms to clearly denote that all fields are mandatory.

## Fixes
- None
<br/>


# Dashboard v3.15.21 | 2025-11-29

## New
- Added support for the **Report Message** feature in the UI Kit Builder, Widget Builder, and Preview, allowing users to report inappropriate or harmful messages directly from the chat. An option is now available to enable or disable this feature based on your app’s requirements.
- Added support for **`@all` mentions** in the UI Kit Builder, Widget Builder, and Preview, enabling users to mention all members of a group with a single mention. This feature can also be enabled or disabled as needed.

## Enhancements
- Updated the **React UI Kit** to the latest version **6.3.5** in UI Kit Builder, Widget Builder & Agent Builder, providing improved performance and updated components.
- Updated **documentation links for the Android platform** to reflect the latest compatibility for **Quoted Replies**, **Conversation Search**, and **Report Message** under Chat Feature Compatibility.

## Fixes
- None
<br/>


# Dashboard v3.15.20 | 2025-11-21

## New
- Introduced a new **Flag & Review** moderation workflow, enabling end users to report messages with a reason and allowing moderators to review or approve blocked messages and block or review flagged messages directly from the dashboard.
- Added the ability for app owners to **create custom flag reasons** directly in the dashboard to tailor their moderation experience.
- Added support for customers in the **UAE region** for UI Kit Builder preview and the No-Code Widget Builder.

## Enhancements
- None

## Fixes
- Fixed an issue where saving Email and SMS Notification settings and then resetting them to default did not behave as expected.
- Fixed UI issues on the Calling Screen within the No-Code Widget Builder.
<br/>


# Dashboard v3.15.19 | 2025-11-20

## New
- Added a new option to **enable/disable “Ignore end user mute preferences on @all”** under Push Notifications.

## Enhancements
- Updated text and labels related to **Slack support** for improved clarity.
- Applied minor UI improvements under app section for a smoother experience.

## Fixes
- Fixed an issue where the "Delete Chat" option remained enabled for already deleted group conversations, which previously resulted in an API error in Widget Builder.
- Renamed Custom Tabs to More and fixed an issue where this section displayed a blank screen during page refresh.
<br/>


# Dashboard v3.15.18 | 2025-11-19

## New
- Added an option to **edit existing agents** in Agent Builder, allowing easier updates and modifications.
- Added support for the new **Zendesk** & **Google Suite** tools, including a guided authentication form to help users provide required details seamlessly.
- Added a new **Custom Tabs** option in app navigation, allowing teams to tailor in-app workflows to their specific needs.

## Enhancements
- Added **icon display support** in the **Custom API Tools** list for better visual identification of tools.
- Added **Agent UID** display in the Edit Agent form with copy option for easier reference and management.

## Fixes
- None
<br/>


# Dashboard v3.15.17 | 2025-11-14

## New
- Added a **Friends Only** option in the No-Code Widget Builder, allowing apps to filter the user list to show only friends.
- Added **Shopify support** for no-code integration, enabling easier embedding of chat experiences in Shopify stores.
- Added support for **React Native UI Kit Builder** in Low Code, enabling easier customization and integration for React Native apps.

## Enhancements
- Added support for the **setStorageMode** method, enabling developers to switch between `sessionStorage` and `localStorage` for more flexible session persistence control.
- Updated **React UI Kit** to version **6.3.4** and **Calls SDK** to version **4.2.1** for improved performance and stability.

## Fixes
- Fixed a UI issue affecting **polls** in the Widget Builder.
- Fixed an issue where the **agent icon** was not visible in the Agent Builder app navigation.
- Fixed an issue where the **"Delete Chat"** option remained enabled for already deleted group conversations, which previously resulted in an API error in Widget Builder.
<br/>


# Dashboard v3.15.16 | 2025-11-07

## New
- **AI Agent Builder**  
  Introduced the **Agent Builder**, an integrated platform within CometChat that enables users to create, customize, and deploy AI agents directly.  
  The new **Deploy Agent Builder UI** streamlines and accelerates the setup process, allowing seamless management of agent creation, configuration, and deployment with improved efficiency.  
  It supports multiple LLMs (e.g., OpenAI), MCP, and ready-to-use tools, providing a complete end-to-end agent management experience.

## Enhancements
- **Bring Your Own Agents (BYO Agents)**  
  Renamed the **Third-Party Agents** section to **Bring Your Own Agents (BYO Agents)**.  
  Combined the **BYO Agents**, **Actions**, and **Tools** sections into a unified **BYO Agents** section to simplify navigation and enhance usability.

## Fixes
- None
<br/>


# Dashboard v3.15.15 | 2025-10-29

## New
- **Optional Auth Key in No-Code Widget Builder**  
  Made the **Auth Key** optional when using **Auth Token** in the No-Code Widget Builder for easier setup and configuration.  

## Enhancements
- **Updated Upgrade Tag to Premium Tag**  
  Replaced the “Upgrade” tag with a **“Premium”** tag for chat features that are part of restricted or paid plans, improving clarity in feature accessibility.  

## Fixes
- **Webhook List Toggle UI**  
  Fixed an issue with the toggle UI in the webhook list on the **Edit Webhook** form for more consistent interaction.  
- **Preview to Dashboard State Persistence**  
  Resolved an issue where returning from preview to the dashboard for existing users did not clear previously selected settings, causing problems when launching variants after reaching the variant limit.  

## Reversions
- Reverted a previous change where **Custom Bots** were marked as legacy and deprecated for new apps created after **August 15, 2025**, for non–multi-tenant accounts.  
- Custom Bots are now fully available for all new apps, restoring previous functionality and compatibility.
<br/>


# Dashboard v3.15.14 | 2025-10-24

## New
- Added a new section for **AI Agents (Beta)** featuring a **Contact Us** option and a **Coming Soon** view to preview upcoming capabilities.  
- **UI Kit Builder**:  
  - Added an option to manage **showing or hiding group action messages** for greater customization.  
  - Added support for **Flutter integration**, enabling developers to easily use UI Kit Builder within Flutter applications.  
- **Widget Builder**: Added options to manage **showing or hiding group action messages** and **unread count bubbles in the docked layout **.  

## Enhancements
- Renamed existing **AI Agents** to **Third-Party Agents** for improved clarity and categorization.  
- Upgraded the React UI Kit in UI Kit Builder, Widget Builder and Preview to version **6.3.2**, delivering improved performance, refined design components, and a smoother development experience.  
- Updated the **Chat Builder logo** to align with the new nomenclature — **UI Kit Builder** for Code integrations and **Widget Builder** for No Code integrations.  

## Fixes
- Fixed an issue where the **enable/disable option** for **Third-Party Agents** was not functioning as expected.
<br/>


# Dashboard v3.15.13 | 2025-10-22

## New
- None

## Enhancements
- None

## Fixes
- Fixed an issue where updating a custom bot was not working as expected.
<br/>


# Dashboard v3.15.12 | 2025-10-21

## New
- None

## Enhancements
- Added a condition to **exclude multi-tenancy apps** created after **August 15th** from **deprecation checks** applied to **Custom Bots (Legacy)**, ensuring continued support for newer multi-tenant implementations.

## Fixes
- None
<br/>


# Dashboard v3.15.11 | 2025-10-14

## New
- Added detailed **platform support and compatibility information** for Chat features to help developers better understand feature availability across platforms.  
- Added **UI Kit Builder options** for **iOS** and **Android** under *Getting Started → Chats* for easier setup and integration.  
- Added an option to **request to join shared Slack Channel with CometChat Engineers directly from the Dashboard**.  

## Enhancements
- Delivered multiple **UI and UX improvements** across various app sections.  
- Enhanced **empty views** across app modules for a clearer and more informative user experience.  
- **Renamed modules for better clarity**:  
  - *Chat Builder* → **UI Kit Builder**  
  - *Chat Widget Builder (No Code)* → **Widget Builder**  
  - Combined **Legacy AI Bots**, **AI Instructions**, and **Custom Bots** into one unified module called **Custom Bots (Legacy)**.  
  - Updated nomenclature in **Custom Bots (Legacy)** from *Agent* to *Bot*.  
- **Webhooks**: Improved the *Edit Webhooks* experience in the new UI for better usability.  
- **React UI Kit**: Updated to the latest version across the **Demo**, **AI Agent Builder**, **UI Kit Builder**, and **Widget Builder** for improved stability and performance.  
- **Moderation**: Introduced an option to **enable Moderation** in Blocked message logs, when the Moderation feature is disabled.  

## Fixes
- Implemented multiple **UI fixes** across the platform to enhance consistency and visual polish.
<br/>


# Dashboard v3.15.10 | 2025-09-25

## New
- Added support for **Quoted Replies** in Chat Builder (Demo, Code, and No Code Widget), with the option to enable or disable the feature as needed.  

## Enhancements
- **UI Kit**: Updated to version `6.3.0` for the latest improvements and stability.  
- Delivered minor **UI enhancements** across both App and non-App sections for improved usability.  
- **Webhooks**:  
  - Renamed *Legacy Webhooks* to **Webhooks (Legacy)** for better clarity.  
  - Introduced a **new UI for Webhooks add and edit forms**, improving ease of configuration.  
  
## Fixes
- Chat Builder - Fixed an issue where **conversation search** was not working as expected when launches from Chats list.
<br/>


# Dashboard v3.15.9 | 2025-09-25

## New
- None

## Enhancements
- **Chat Builder (Preview, Code, and No-Code modes)**: Updated React UI Kit to version `6.2.6` for improved stability and feature support.
- Delivered minor **App navigation UI enhancements** for improved consistency and usability.  

## Fixes
- Fixed an issue where **launching the Agent Chat Builder** occasionally did not work.  
- **No Code Chat Builder Widget** - Fixed a **theming issue in Firefox** for deployed **No Code Chat Builder**, ensuring consistent appearance across browsers.
- Fixed an issue where searching for an app returned an empty view with no results after switching from the **Accounts** screen.  
- Fixed an issue in **Account Settings** where roles were displayed as raw values instead of role names for older roles.
<br/>


# Dashboard v3.15.8 | 2025-09-19

## New
- Introduced a **new onboarding flow** to help users get started more quickly and efficiently.  
- Added **Get Started guides** for easier navigation and setup.  
- Added support for **Login or Signup with Google and GitHub** for faster and more convenient authentication.  

## Enhancements
- Delivered multiple **UI and UX improvements across the App section**, including:  
  - Improved tables for better readability.  
  - Consistent button styling.  
  - Updated app navigation for a smoother experience.  
  - General **UX enhancements** to improve usability throughout the app.  
- Updated **labels & titles for legacy features** such as Moderation, AI Bots, and Notifications to improve clarity.  
- **UI Kit**: Updated to version `6.2.5` in Chat Builder (demo, Code, and No Code apps).  
- Added **instructions in the Chat Builder preview** before redirecting users to the dashboard, improving clarity in the flow.  
- Updated **Chat Builder No Code embed code** to use version `1.x.x` (`https://cdn.jsdelivr.net/npm/@cometchat/chat-embed@1.x.x/dist/main.js`) instead of `latest` for more stable integrations.

## Fixes
- Fixed an issue where **role IDs were displayed in capitalized format** in the users list.  
- Fixed a **pagination issue** in the users list when handling a large number of users.
<br/>


# Dashboard v3.15.7 | 2025-09-10

## New
- **Chat Builder (Code and No Code)**: Added new chat and delete conversation option in the CometChatAIAssistantChatHistory component.

## Enhancements
- **UI Kit**: Updated to version `6.2.3` across the Chat Builder demo, Code apps, and No Code apps.

## Fixes
- Fixed an issue where the **selected timezone under App Settings** was not working for certain options due to UTC handling in Insights.
- Fixed an issue where the Chat Builder view was blocked on certain desktop devices.
- Chat Builder (Code and No code)
  - Fixed inconsistent conversation header height across different views for a more uniform interface.
  - Fixed an issue where audio files became distorted after sending.
  - Fixed the hideReceipts prop in the CometChatThreadHeader component so it now updates correctly at runtime.
  - Fixed an issue where adding a new template for custom messages failed to display the default statusInfoView.
- Agent Builder
  - Fixed an issue where **switching between agents** did not refresh and display the correct message list.
<br>


# Dashboard v3.15.6 | 2025-09-04

## New
- Introduced a new category of messages, **Agentic**, now available in App → Chats (both live and history).

## Enhancements
- **Documentation**: Updated No code Chat builder links to match the new documentation.  
- **App Navigation**: Minor enhancements for smoother user experience.  

## Fixes
- Fixed an issue where the **docked layout** was incorrectly visible in rare cases in the Code version of the demo Chat Builder on the dashboard.  
- Fixed an issue where **role IDs appeared capitalized** in the users list and user detail views.
- Fixed an issue in the **AI Agent Chat Builder** where changing the active agent in the multiple agents list did not work as expected.
<br>


# Dashboard v3.15.5 | 2025-09-01

## New
- **Mobile Chat Builder Support**: Added support for Android and iOS apps with live preview capability via QR code scanning.  

- **Downloadable Apps with Chat Builder Settings**: Enabled the ability to download Android and iOS apps pre-configured with selected Chat Builder settings, making integration and testing easier.  

## Enhancements
- **Chat Builder Moderation**:  
  - Renamed *Moderator controls* to **Moderation** for improved clarity.  
  - Updated the *Moderation* option: it is now called **Blocked Message Feedback** and is accessible under Moderation.

- **Integrate** - Updated links for **Chat Builder** to point to the new documentation.

- **AI Agents**: Minor updates to the **Get Started** screen for improved clarity.

## Fixes
- Fixed an issue where the **Chat Builder view was blocked on certain desktop devices**.
<br>


# Dashboard v3.15.4 | 2025-08-28

## New
- Introduced options to customize **email notification payloads**, allowing users to include or exclude the message object and metadata for greater control over notification content.

- Introduced options to customize **SMS notification payloads**, giving users flexibility to include or exclude the message object and metadata.

- Added support for **Moderation**, with the ability to enable or disable the feature directly in Chat Builder (available in both code and no-code variations).

- Added an option to **launch the builder with a selected default agent from the AI Agents list**, streamlining setup and improving workflow efficiency.

## Enhancements
- Updated **React UI Kit** to the latest version `6.2.1`.

- Enhanced **Chat Builder demo and preview** to fetch agentic users using the CometChat SDK.

- Minor UI enhancements on Dashboard navigation.

## Fixes
- UI fixes on AI Agents Chat.
<br>


# Dashboard v3.15.3 | 2025-08-26

## New
- **AI Agents**  
  Expanded availability of AI Agents to **IN and EU regions** in addition to the US.  

- **Chat Builder Preview**  
  Updated the mechanism for applying preview settings by introducing temporary builder settings in the dashboard flow, with an automatic time-to-live (TTL) of 24 hours.

- **Conversation Search Toggle in Chat Builder**  
  Introduced the option to enable or disable the conversation search feature in both code and no-code variations of Chat Builder.  
  Moved conversation search settings in the dashboard from **Chat > Settings** to **Chat > Features** for improved accessibility.

## Enhancements
- **UI Improvements in AI Agent Chat Builder**  
  Applied multiple UI refinements to improve usability and overall chat experience.  

- **One-on-One Chat Behavior**  
  Resolved an issue in both code and no-code apps where opening an agent conversation from the **Chats** tab incorrectly launched the one-on-one user chat instead of the intended AI Assistant chat.

- **Legacy Widgets UI Improvements (Dashboard)**  
  Enhanced the design and usability of Legacy Widgets within the dashboard for a smoother setup and management experience.  

## Fixes
- AI Agents displayed **unread message count** in the docked layout when accessed from chat history.  
- Fixed an issue where messages disappeared in Agent Builder after a theme change or when switching between web and mobile views. 
- Fixed an issue where, on certain occasions, creating a new app incorrectly redirected users to the **Apps Listing** page.

## Deprecations
- Removed Sans-serif option from typography font family list in Chat Builder.
<br>


# Dashboard v3.15.2 | 2025-08-22

## New
- None

## Enhancements
- AI Bots and Instructions are now marked as Legacy (instead of Deprecated) and remain visible for apps created before 15th August 2025.

## Fixes
- Corrected missing configuration in Custom Subscription Options where the Bypass Preferences setting was not available earlier.
<br>


# Dashboard v3.15.1 | 2025-08-14

## New
- **AI Agents** 
  Introduced AI Agents to help businesses easily create, customise, and deploy intelligent chatbots, copilots, and agents directly into their applications — without the complexity of traditional AI integrations.  
  - **Faster setup** – Launch production-ready AI agents in minutes using our no-code widget. 
  - **Seamless integration** – Use our integration wizard and embeddable widget to add AI to your web apps effortlessly.  
  - US apps only release — coming soon for EU and IN regions.

- **Chat Builder (No code - widget) Launch with AI Agent Support**  
  Released the new Chat Builder with built-in AI Agent integration, allowing users to design, customise, and deploy AI-powered chat experiences directly from the Chat Builder interface.

- **Updated React UI Kit and JavaScript SDK in Chat Builder**  
  Upgraded to the latest versions of the React UI Kit and JavaScript SDK within Chat Builder, delivering improved performance, refreshed UI components, and a better developer experience.

## Enhancements
- Enhanced the design and usability of **Legacy Widgets**, providing a cleaner interface and improved user experience for existing widget implementations.

## Fixes
- None
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


