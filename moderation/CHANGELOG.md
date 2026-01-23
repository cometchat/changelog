# Moderation v1.0.10 | 2025-11-19
## New
- None
## Enhancements
- None
## Fixes
- Fixed an issue where manually approved messages that originated from previously flagged or blocked items did not appear in the Reviewed Messages list. These messages now display as expected.
- Resolved an issue where media files were not moderated when Token Based File Access was enabled.


# Moderation v1.0.9 | 2025-10-28
## New
- None
## Enhancements
- None
## Fixes
- Fixed an issue where the **blocked message event** in Moderation was not delivered in realtime to users and webhooks.
  This issue was introduced in **Moderation v1.0.8** in the **US region**.


# Moderation v1.0.8 | 2025-10-23
## New
- Added support for Flag and Review, allowing both users and AI to flag messages for review.
## Enhancements
- None
## Fixes
- None
<br/>

# Moderation v1.0.7 | 2025-08-05
## New
- None
## Enhancements
- Added support for real-time moderation events in the frontend, which will enable the UI to reflect moderation actions immediately.
## Fixes
- None
<br/>

# Moderation v1.0.6 | 2025-05-19
## New
- Added support for OpenAI integration, enabling automated moderation using stored OpenAI prompts.
- Introduced support for custom Moderation APIs, allowing developers to apply their own logic for content control.
## Enhancements
- None
## Fixes
- Fixed an issue where regex input validation failed when creating a list of regex with commas.
<br/>


# Moderation v1.0.5 | 2025-05-14
## New
- None
## Enhancements
- Enhanced the AI sentence similarity model to deliver more accurate and relevant results, improving response precision and overall user experience.
## Fixes
- None
<br/>

# Moderation v1.0.4 | 2025-03-28
## New
- None

## Enhancements
- None
## Fixes
- Added validation to ensure proper format and accuracy when creating regex-based keyword filters.   
<br/>

# Moderation v1.0.3 | 2024-11-26
## New
- AI Similarity Matching: Added support for AI-based similarity matching, allowing it to identify and match similar sentences effectively.
- Toxicity Detection: Added the ability to detect toxic content in chat messages.
- Sentiment Analysis: Added provision for sentiment analysis to gauge the emotional tone of chat messages.
- Filters Support: Added filters for Sender's and Receiver's messages based on properties like UID, GUID, name, created at, type, etc.
- Approve Blocked Messages: Provision to approve previously blocked messages.
- Enabled moderation support for edited messages.

## Enhancements
- None
## Fixes
- None   
<br/>


# Moderation v1.0.2 | 2024-08-07
## New

-   None

## Enhancements

-   None

## Fixes

-   Resolved the issue with the video moderation service so that it only processes when the video rule is active.   
<br/>


# Moderation v1.0.1 | 2024-08-07
## New

-   None

## Enhancements

-   None

## Fixes

-   Resolved an issue that prevented the moderation service from processing audio and file messages.   
<br/>


# Moderation v1.0.0 | 2024-08-07
## New

-   Introduced new AI-powered advanced moderation for text and media messages.

## Enhancements

-   None

## Fixes

-   None   
<br/>







