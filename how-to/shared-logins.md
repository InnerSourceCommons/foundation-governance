---
title: Shared Logins
type: docs
prev: foundation-governance/how-to/
---

# How We Run Shared Logins

Some Foundation services run on one shared account that several people use.
Each shared service has two parts:

- **A credentials sheet per service.**
  Each service has its own Google spreadsheet with its login details, shared individually with the people who use that service.
- **An email alias for the service.**
  The shared account's login email is an `@innersourcecommons.org` group address, and everyone who uses the service is a member of that group.
  Sign-in verification emails and one-time codes go to the alias, so they reach every member's own inbox.

## Getting access

Shared logins use your own `@innersourcecommons.org` address: the aliases accept only domain accounts, and the credentials sheets are shared to that same address.
If you don't have one yet, see [How to get an email address](get-email-address).

Ask in the [#google-admins](https://innersourcecommons.slack.com/archives/C06V6RGLBP1) Slack channel.
An admin adds your `@innersourcecommons.org` address to the service's alias and shares its credentials sheet with it.

## Signing in

1. Open the service's credentials sheet, shared with your `@innersourcecommons.org` address, for the login email and password.
2. Sign in to the service with those details.
3. When the service asks for a verification code, find it in your own inbox, sent to the alias.

## Current aliases

The list grows as more services move to a shared login.

| Service | Alias |
|---|---|
| [Zoom](schedule-zoom-meeting) | `zoom@innersourcecommons.org` |
| Eventbrite | `eventbrite@innersourcecommons.org` |
| Pretix | `pretix@innersourcecommons.org` |
