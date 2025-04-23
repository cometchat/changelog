# Management API v1.3.12 | 2025-04-22
## New
- None

## Enhancements
- None

## Fixes
- Resolved an issue where retrieving extension settings via multi-tenant APIs returned a 404 error when using an alternate management domain.
<br/>


# Management API v1.3.11 | 2025-04-10
## New
- None

## Enhancements
- None

## Fixes
- Fixed an issue with the webhook creation wrapper that caused unexpected behavior when called immediately after app creation.   
<br/>


# Management API v1.3.10 | 2025-02-25
## New
- None

## Enhancements
- None

## Fixes
- Resolved an issue where two-factor authentication (2FA) was disabled due to an email delivery problem. The email issue has been fixed, and 2FA has been reenabled to ensure continued account security.   
<br/>


# Management API v1.3.9 | 2025-02-25
## New

- None

## Enhancements

- None

## Fixes

- Temporarily disabled MFA due to email provider issues.   
<br/>


# Management API v1.3.8 | 2025-01-20
## New

- Added Two-Factor Authentication (2FA) for enhanced security during customer login.

## Enhancements

- None

## Fixes

- None   
<br/>


# Management API v1.3.7 | 2024-12-26
## New

- Implemented an endpoint to retrieve usage data across apps in a multi-tenancy setup. 
More details regarding the endpoint - https://api-explorer.cometchat.com/reference/fetch-multi-tenant-usage

## Enhancements

- None

## Fixes

- None   
<br/>


# Management API v1.3.6 | 2024-08-24
## New

- None

## Enhancements

- Removed the option to apply coupons when subscribing to an annual plan, as the plan will now automatically be created with the discounted amount.

## Fixes

- Handled the plan update for the app during subscription reactivation for the annual plans.   
<br/>


# Management API v1.3.4 | 2024-08-07
## New

-   None

## Enhancements

-   None

## Fixes

-   Fixed the list invoices API for apps with annual subscriptions.
   
<br/>


# Management API v1.3.3 | 2024-08-07
## New

-   Added a new API to retrieve a list of apps to archive.

## Enhancements

-   None

## Fixes

-   None   
<br/>


# Management API v1.3.2 | 2024-08-07
## New

-   None.

## Enhancements

-   None.

## Fixes

-   Corrected the list apps API that fetches the apps to be archived & deleted.   
<br/>


# Management API v1.3.1 | 2024-08-07
## New

-   Added new APIs for the advanced moderation service.

## Enhancements

-   Restricted the ability to disable token-based file access once enabled.

## Fixes

-   None
   
<br/>
