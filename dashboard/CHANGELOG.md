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
