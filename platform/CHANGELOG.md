# Platform v3.0.13 | 2025-10-23
## New
- None

## Enhancements
- Added support for app-level configuration to enable sequential execution of member management operations in the Add Members API.

## Fixes
- None
</br>

# Platform v3.0.12 | 2025-08-06
## New
- None

## Enhancements
- Added support for real-time moderation events in the frontend, which will enable the UI to reflect moderation actions immediately.
  
## Fixes
- None
</br>

# Platform v3.0.11 | 2025-05-07
## New
- None

## Enhancements
- Added support for generating token-based media URLs compatible with the UAE region.
  
## Fixes
- None
</br>

# Platform v3.0.10 | 2025-04-15
## New
- None

## Enhancements
- Added webhook support for the following call events: `call_ended`, `call_rejected`, `call_unanswered`, and `call_busy`

## Fixes
- None
   
<br/>

# Platform v3.0.9 | 2025-03-31
## New
- None

## Enhancements
- Improved the reliability of webhook data delivery by adding automatic retries for failed requests.

## Fixes
- None
   
<br/>


# Platform v3.0.8 | 2025-03-21
## New
- None

## Enhancements
- None

## Fixes
- Resolved an issue where edited messages were not undergoing moderation as expected.
- Improved validation for regex-based keyword filters in moderation to ensure correct format and accuracy.   
<br/>


# Platform v3.0.7 | 2025-03-19
## New
- Service for **Conversation & Advanced Search**, allowing users to quickly find specific messages and conversations with improved filtering options.

## Enhancements
- None

## Fixes
- None   
<br/>


# Platform v3.0.6 | 2025-02-24
## New
- None

## Enhancements
- None

## Fixes
- Fixed an issue where the threaded message count was included even when the **Include Thread Replies** setting was turned off.
- Resolved an issue where messages remained unread even after being marked as read.   
<br/>


# Platform v3.0.5 | 2025-02-14
## New
- None

## Enhancements
- Added support for moderation webhooks, enabling automated moderation workflows.

## Fixes
- None   
<br/>


# Platform v3.0.4 | 2024-08-28
## New

-   None.

## Enhancements

-   None.

## Fixes

-   Resolved an issue where the client-side libraries and web browsers were caching the pre-signed URL leading to Access Denied error.   
<br/>


# Platform v3.0.3 | 2024-08-07
## New

-   Introduced the new read by all and delivered to all events for the messages sent in a group.

## Enhancements

-   Optimized the performance for the unread message count service.

## Fixes

-   None.   
<br/>


# Platform v3.0.2 | 2024-08-07
## New

-   Introduced the insights that can allow the dashboard to show the following graphs:
    -   Messaging insights
        -   Messaging Activity
        -   Messages Sent
        -   Messages Delivered
        -   Messages Read
        -   Messages By Conversation Type
        -   Average Messages Across Conversations
        -   Message Types Sent
        -   Thread Messages
        -   Average Word Count
        -   Average Character Count
        -   New Conversations
        -   Active Conversation Distribution
        -   Message Engagement Frequency
        -   Number Of Messages Before First Image
        -   Engagement Progression By Message Type
        -   Average First Response Time
        -   Month Over Month New Messages
        -   Average Response Time Per Day
        -   Average Response Time
        -   Chat To Calls Conversion
        -   Month Over Month Active Conversations
        -   Pre-Call Messaging
        -   Reactions Count
        -   Number Of Mentions
        -   Messages Before Conversation Churn
        -   Conversation Churn Time Distribution
    -   Voice & Video insights
        -   Call Duration
        -   Call Participation
        -   Concurrent Calls Heatmap
        -   Call Duration Distribution
        -   Calls Per Day
        -   Calling Engagement Frequency
    -   Users & Groups insights
        -   Top 10 Users
        -   Top 10 Groups
        -   Average Group Size
        -   Concurrent Users Heatmap
        -   OS Usage
        -   New Users Created Month Over Month
        -   New Users Created Per Day
        -   Time To First Message
        -   Top 10 Users Who Reacted The Most
        -   Top 10 Users Whose Messages Received The Most Reactions
        -   New Friends Count
        -   Online Frequency Distribution
        -   Active Group Count
        -   Online Users Per Day
        -   User Retention Analysis
        -   Cohort Analysis Of User Abandons
        -   User Abandon Analysis Funnel
        -   User Abandon Analysis
        -   Groups Churn Per Day

## Enhancements

-   None

## Fixes

-   None   
<br/>


# Platform v3.0.10 | 2025-04-10
## New
- None

## Enhancements
- Updated the **webhooks create/update API** to support the `retryOnFailure` parameter. When enabled, failed events will automatically be retried, improving reliability.

## Fixes
- None   
<br/>


# Platform v3.0.1 | 2024-08-07
## New

-   Added token-based file access for better control over access to media files.

## Enhancements

-   Modified the typing indicators behavior to ensure that only five events/second will be delivered to the users thereby conserving network bandwidth.
-   Modified the behavior of the transient message to ensure that only five events/second will be delivered to the users thereby conserving network bandwidth.

## Fixes

-   None   
<br/>



