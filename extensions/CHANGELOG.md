# Extensions v3.0.8 | 2025-01-23
## New

- None.

## Enhancements

- None.

## Fixes

- Fixed a bug in the Avatars extension for users without an avatar caused by a missing null check during the set avatar operation.   
<br/>


# Extensions v3.0.7 | 2025-01-01
## New

- None.

## Enhancements

- None.

## Fixes

- Fixed an issue where VoIP notifications sent via Apple Push Notifications service (APNs) failed intermittently for one-on-one calls.   
<br/>


# Extensions v3.0.5 | 2024-11-20
## New

- None

## Enhancements

- Added a new setting to the Push notifications extension to control the trimming of the message text in notifications.

## Fixes

- None   
<br/>


# Extensions v3.0.4 | 2024-11-19
## New

- None

## Enhancements

- Modified the Push Notifications extension to allow removal of sender metadata, receiver metadata, and message metadata from the message object in the push payload. This helps ensure the payload size remains within the 4 KB limit set by Firebase Cloud Messaging (FCM) and Apple Push Notifications service (APNs), preventing push notification delivery failures.

## Fixes

- Fixed a bug in the Push Notifications extension by including the required `content-available` key in the FCM payload for React Native on iOS.
- Fixed a bug in the Push Notifications extension by including the `sound` and `icon` keys in the FCM payload for Android.   
<br/>


# Extensions v3.0.3 | 2024-08-07
## New

-   None

## Enhancements

-   None

## Fixes

-   Fixed a bug in the Push notifications extension that notified deactivated users for messages sent in groups.   
<br/>


# Extensions v3.0.2 | 2024-08-07
## New

-   None

## Enhancements

-   None

## Fixes

-   Fixed a bug in Push notifications extension that stopped sending badge count details to APNs native and FCM HTTP v1 API.
   
<br/>


# Extensions v3.0.1 | 2024-08-07
## New

-   None

## Enhancements

-   Modified feature Push Notifications extension to ensure support for the new FCM HTTP v1 APIs.

## Fixes

-   None   
<br/>


# Extensions v3.0.0 | 2024-08-07
## New

-   None

## Enhancements

-   None

## Fixes

-   Fixed an issue with the thumbnail generation not working correctly with token-based file access.
   
<br/>