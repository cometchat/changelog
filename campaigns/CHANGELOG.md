# Campaigns v0.1.1 | 2026-08-20
## New
- None

## Enhancements
- None

## Fixes
- The variables editor previously offered an example name containing a dot (such as `user.name`), which the server does not accept, so following it caused the template to fail to save with no explanation. Invalid names are now rejected as you enter them, and the examples show names that work.
- Templates whose variables have a display label different from the variable name can now be edited and saved repeatedly. Previously, saving such a template renamed the variable behind the scenes, and a label containing a space could leave the template permanently unsavable.
- Values entered for template variables are now correctly filled into the delivered message when the variable has a display label. Previously these were saved against the label rather than the variable name, so the placeholder was left unfilled in the sent notification.
- Creating a template with a name that already exists now shows an error message. Previously the error appeared far below the visible area of the page, so the save appeared to do nothing.
<br/>

# Campaigns v0.1.0 | 2026-05-27
## New
- Campaigns - create and send notification campaigns to a selected set of users, either immediately or scheduled for a later date and time, with the option to cancel before they go out.
- Recipients - add recipients by searching and selecting users directly, or by uploading a CSV. Per-recipient values can be supplied as CSV columns so each person receives a personalised message.
- Templates - build reusable message templates with separate content per channel. Templates are versioned, so editing one does not alter campaigns that were already sent. They can be organised into categories, labelled, and moved through draft, approved and archived states.
- Template variables - define placeholders such as `{{name}}` that are replaced with real values for each recipient at send time. Supports text, image and action-link values, with optional defaults when a recipient has no value of their own.
- Multi-step sequences - chain several template steps that advance automatically after a configurable wait, and stop early once the recipient has engaged. Stop conditions match the channel: delivered, read or engaged for the in-app feed; delivered or clicked for push.
- Channels - deliver to the in-app notification feed and to mobile push, configured per app.
- Push provider setup - configure Apple (APNs), Firebase (FCM) and custom push providers from the dashboard.
- In-app notification feed - delivered messages appear in an in-app feed with per-user unread counts, and a configurable retention period that purges older items automatically.
- Send Notification from the Users page - send a one-off transactional notification to a specific user, or a group of users, using an existing template.
- Analytics - delivery and engagement reporting across the whole app, with drill-down by campaign, by template, by channel and by individual user.
- Plain-text fallback - templates carry alternative text used when push is suppressed or rich content cannot be rendered.

## Enhancements
- None

## Fixes
- None
<br/>
