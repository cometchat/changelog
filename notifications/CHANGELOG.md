# Notifications v1.6.11 | 2025-09-09

## New
- None

## Enhancements
- Introduced notifications for agentic messages.
 
## Fixes
- Fixed an issue where call notifications were not received for custom providers.
</br>

# Notifications v1.6.10 | 2025-08-26

## New
- None

## Enhancements
- Introduced options to customize email notification payloads, allowing inclusion or exclusion of the message object and metadata for greater control over notification content.
- Introduced options to customize SMS notification payloads, allowing inclusion or exclusion of the message object and metadata for greater control over notification content.
 
## Fixes
- Fixed an issue where call notifications were not received for custom providers.
</br>

# Notifications v1.6.7 | 2025-08-04

## New
- None

## Enhancements
- None
 
## Fixes
- Fixed an issue in email notifications where `Body (Fallback)` was prioritized over `Body` for custom messages in the notifications template.
</br>

# Notifications v1.6.6 | 2025-07-09

## New
- None

## Enhancements
- Added validation to ensure provider ID is valid and matches the device platform during push token registration.
 
## Fixes
- Fixed an issue where the metadata was missing from call notifications.
</br>

# Notifications v1.6.4 | 2025-06-25

## New
- None

## Enhancements
- None
 
## Fixes
- Fixed an issue where sender and receiver metadata were missing from call notifications.
- Resolved an issue where notification sounds would not play with FCM on iOS devices.
- Fixed a bug where FCM notifications on iOS did not apply the configured notification key settings.
</br>

# Notifications v1.6.3 | 2025-06-16

## New
- None

## Enhancements
- None

## Fixes
- Fixed an issue where additional data in the payload was missing from the APNS VoIP notification.
</br>

# Notifications v1.6.1 | 2025-05-22

## New
- None

## Enhancements
- None

## Fixes
- Fixed an issue where the `conversationId` was missing from the APNS payload, which occurred in version v1.6.0. This ensures proper deep linking for a notification on iOS devices.
</br>

# Notifications v1.6.0 | 2025-05-20
## New
- None

## Enhancements
- Added the ability to configure notification preferences related to calls through the Dashboard and REST API, giving more control over how call alerts are delivered.
- Introduced options to customize push notification payloads, allowing inclusion or exclusion of the message object and metadata for greater control over notification content.
- Increased the delay between SMS and email notifications to 1 minute to help prevent duplicate or closely timed alerts.

## Fixes
- Fixed an issue where pagination in the notification logs failed to work correctly, ensuring smooth navigation through log entries.
</br>

# Notifications v1.5.0 | 2025-04-24
## New
- Introduced the ability to bypass notification preferences for mentions, ensuring users always receive alerts when they are mentioned.

## Enhancements
- None

## Fixes
- None
<br/>

# Notifications v1.4.0 | 2025-04-10
## New
- Introduced **Notification Logs** feature, allowing customers to view and track notification history for easier investigation and debugging.

## Enhancements
- None.

## Fixes
- None.   
<br/>


# Notifications v1.3.0 | 2025-03-18
## New
- Custom providers for triggering Email, SMS, and Push notifications.

## Enhancements
- None.

## Fixes
- None.   
<br/>


# Notifications v1.2.4 | 2025-02-10
### New
- None

### Enhancements
- None

### Fixes
- Fixed an issue where push notifications were mistakenly sent to deactivated users for messages and events in groups.   
<br/>


# Notifications v1.2.2 | 2024-11-28
### New
- None

### Enhancements
-  None

### Fixes
- Resolved an issue where the required details, such as type, receiver's avatar URL, receiver's uid, etc. were missing in the APNs payload.
- Resolved an issue where the list of muted conversations was always returned empty.   
<br/>


# Notifications v1.2.1 | 2024-10-01
### New
- None

### Enhancements
-  Updated notification preferences for **Message Edited** and **Message Deleted** events, enabling user customisation.

### Fixes
- None
   
<br/>


# Notifications v1.2.0 | 2024-08-29
## New

-  None

## Enhancements

-  Modified the template data structure to include `uid` and `guid` for creating the Email and SMS content using templates.

## Fixes

-  None   
<br/>


# Notifications v1.1.1 | 2024-08-07
## New

-   None

## Enhancements

-   None

## Fixes

-   Fixed a bug in Push notifications where the user_blocked event was not handled properly.
-   Fixed a bug in email notifications that was forcing privacy templates for all the emails.   
<br/>


# Notifications v1.1.0 | 2024-08-07
## New

-   Added enhanced Email notifications with improved control over notifications and preferences.
-   Added enhanced SMS notifications with improved control over notifications and preferences.

## Enhancements

-   None

## Fixes

-   None   
<br/>


# Notifications v1.0.0 | 2024-08-07
## New

-   Introduced a new notifications service with enhanced push notifications for improved control over notifications and preferences.

## Enhancements

-   None

## Fixes

-   None
   
<br/>
