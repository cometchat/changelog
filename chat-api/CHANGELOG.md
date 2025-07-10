# Chat API v3.9.32 | 2025-07-03
## New
- Introduced separate REST API endpoints for Moderation, enabling it to operate independently from the core chat service.

## Enhancements
- None

## Fixes
- Masked `apiKey` and `authToken` values in error responses to enhance security.
- Fixed an issue where the action message contained incorrect user information when changing user scope.
<br/>

# Chat API v3.9.31 | 2025-06-02
## New
- None

## Enhancements
- Added support for the `attachmentTypes` query parameter in the List Messages API, enabling more precise filtering of message attachments for the Advanced Search service.

## Fixes
- Fixed an issue where the List Conversations API, when called with `includeBlockedUsers` set to `1`, incorrectly displayed a blocked user after the conversation with them was reset.
- Resolved a bug in the Import Users API that caused request failures when importing a mix of deactivated and active users.
<br/>

# Chat API v3.9.30 | 2025-05-19
## New
- None

## Enhancements
- None

## Fixes
- Fixed an issue where `membersCount` did not update correctly when users were kicked or banned from a group.
- Resolved a problem where `callToken` size exceeded acceptable limits by omitting user metadata during token generation.
- Fixed a bug that allowed a user to react to a message after blocking another user.
- Ensured `unreadMessageCount` is set to 0 when a conversation is reset.
- Corrected the behavior of `category` and `type` filters in the list messages API, which previously caused empty message lists in UI Kits when the search service was enabled.
- Fixed a bug where group conversations were not added to the conversation list when a user was added to a group with "Include Group Actions" disabled in the Conversation Preview configuration. This issue was introduced in version v3.9.26.
<br/>


# Chat API v3.9.29 | 2025-05-06
## New
- None

## Enhancements
- Added the ability to filter members by status in the List Group Members API.

## Fixes
- Updated the Stats API to leverage the new metrics service for improved accuracy and performance.
- Ensured user and group tags are passed to the moderation event bus during message sending, allowing tag-based filters to function correctly.
<br/>


# Chat API v3.9.28 | 2025-04-23
## New
- None

## Enhancements
- None

## Fixes
- Resolved an issue where messages sent before a conversation reset were still visible when fetching message details.
- Corrected the API response structure when modifying the scope of an admin user.
- Enabled the ability to search soft-deleted messages through the Admin API.
- Fixed incorrect conversation ordering when the enhanced message status service was enabled.
<br/>


# Chat API v3.9.27 | 2025-03-21
## New
- None

## Enhancements
- Optimized the query for updating member counts when adding new members to a group, improving performance and accuracy.

## Fixes
- Fixed an issue where moderation was not applied to edited messages.   
<br/>


# Chat API v3.9.26 | 2025-03-12
## New
- None

## Enhancements
- None

## Fixes
- Resolved an issue where the message metrics endpoint did not return data correctly.
- Fixed an issue where the Update Role API could be assigned an empty value.
- Corrected a bug that caused **system messages** to appear as the last message in the conversation list when members were added to a group, even when disabled in the conversation preview settings.
- Fixed an issue where messages were not listed correctly when the app was in a migrating state, sent via the v2 endpoint, and retrieved through the v3 list messages endpoint.   
<br/>


# Chat API v3.9.25 | 2025-02-12
## New
- None

## Enhancements
- None

## Fixes
- Fixed an issue where the unread message count was sometimes incorrect by ensuring message read receipts are processed properly when a new message is sent via API.  
- Resolved a bug in group chats where message receipts were not displaying correctly, ensuring accurate delivery and read status for all participants.  
- Corrected an issue where users were incorrectly assigned the default role when the role ID was set to `"0"`.     
<br/>


# Chat API v3.9.24 | 2025-02-03
## New
- None

## Enhancements
- Implemented Role-Based Access Control (RBAC) restrictions for updating user details, ensuring better security and permission management.

## Fixes
- Fixed an issue where the group members count was displayed incorrectly in certain scenarios.
   
<br/>


# Chat API v3.9.23 | 2025-01-17
## New
- None
## Enhancements
- None
## Fixes
- Resolved an issue with the List Unread Messages API to ensure it accurately retrieves unread messages.
- Fixed a bug where the group owner did not receive real-time messages if their UID included mixed-case characters.   
<br/>


# Chat API v3.9.22 | 2024-12-31
## New
- None
## Enhancements
- None
## Fixes
- Fixed the groupOnlineMembersCount issue in the List Groups API.   
<br/>


# Chat API v3.9.21 | 2024-12-18
### New
- None

### Enhancements
- Added caching for group tags to improve performance.

### Fixes
- Resolved an issue where the sender's object was incorrectly displayed in the receipts in the get message API for the message sent in a group.
- Fixed a bug where archived conversations were accessible to the Get/Update Conversation API.
- Resolved an issue with updating tags on a custom message.   
<br/>


# Chat API v3.9.20 | 2024-10-03
## New
- None
## Enhancements
- None

## Fixes
- Added the missing updatedAt property in the response of the Update User API.
- Fixed incorrect lastActiveAt/status property in the response of the Get User API.   
<br/>


# Chat API v3.9.18 | 2024-09-18
## New
- None

## Enhancements
- The apps created after August 12th, 2024, contain the new sample users and group. This includes changes to the unique identifiers (`uid` and `guid`), names, user avatars, and the group icon. Sample users are now identified as `cometchat-uid-1` to `cometchat-uid-5` (previously `superhero1` to `superhero5`), and the sample group is now identified as `cometchat-guid-1` (previously `supergroup`). These updates provide a more standardized and cohesive experience for new apps.

## Fixes
- Fixed an issue where `tags` and `parentId` were missing in real-time events when multiple messages were sent in quick succession. This ensures accurate event tracking during rapid message exchanges.
- Resolved an issue where the `scope` and `joinedAt` properties were missing in the `receiver` entity after joining a group and sending a message.    
<br/>


# Chat API v3.9.17 | 2024-08-07
## New

-   None

## Enhancements

-   None

## Fixes

-   Resolved an issue with caching that prevented the FCM device token from updating during login.   
<br/>


# Chat API v3.9.16 | 2024-08-07
## New

-   None

## Enhancements

-   None

## Fixes

-   Implemented a failsafe mechanism to handle connection failures with caching clusters.
-   Fixed an issue with an incorrect conversation.lastMessage in the list conversations API for the imported messages.   
<br/>


# Chat API v3.9.15 | 2024-08-07
## New

-   None

## Enhancements

-   None

## Fixes

-   Resolved an issue where the first message of the conversation is available as `conversation.lastMessage` in the list conversations API but missing in the list messages API.
-   Corrected the behavior where after resetting the conversation User A could see the old message as `conversation.lastMessage` in the list conversations API on receiving a new message with a category/type for which the update conversation is disabled.
-   Corrected the conversation ordering for group conversations with the `conversationType=group` filter.
-   Fixed the configuration settings to update the last message in group conversations correctly.
-   Modified the create auth token API to set the AuthToken in the cache, immediately after creating it.
-   Fixed an issue where the unread messages count was getting unset on blocking a user.   
<br/>


# Chat API v3.9.14 | 2024-08-07
## New

-   None

## Enhancements

-   None

## Fixes

-   Fixed an issue where email was not sent in private metadata to the system bus; failing the email notifications.
   
<br/>


# Chat API v3.9.13 | 2024-08-07
## New

-   None

## Enhancements

-   None

## Fixes

-   Resolved an issue where tags were not included in message payloads in real-time and via webhooks.
-   Prevented the unread message count from being cleared when a user is blocked.
   
<br/>


# Chat API v3.9.12 | 2024-08-07
## New

-   None

## Enhancements

-   Along with the message events the mentions will also be pushed to the system bus.

## Fixes

-   Fixed an issue where deactivated users were able to perform SDK operations.
   
<br/>


# Chat API v3.9.11 | 2024-08-07
## New

-   None

## Enhancements

-   Removed the action messages triggered on the permanent deletion of the message.

## Fixes

-   Fixed the error response issue in the update message API.
   
<br/>


# Chat API v3.9.10 | 2024-08-07
## New

-   Implemented AI-powered advanced moderation for the messages.

## Enhancements

-   Modified the import messages API to accept the interactive messages.

## Fixes

-   None   
<br/>
