---
title: Mind Business
permalink: /
---

# Mind Business

**Mind Business** is a Windows desktop application that helps operations teams manage business assets and browser profiles in one place, on their own computer.

[Privacy Policy](privacy.html)

## What Mind Business does

- **Asset and operations management** in one place. Data is stored on your computer.
- **Isolated browser profiles**: each profile has its own browser fingerprint, proxy, cookies and cache, fully separated from other profiles.
- **Backup, export and import of browser profiles**, protected with a password.
- **Optional sync of browser profiles between your computers through your own Google Drive.**

## Google Drive sync

This feature is only active after you click **Connect Google Drive** in the app's browser settings and grant consent on Google's sign-in screen. The app requests:

| Scope | Purpose |
|---|---|
| `drive.file` | Create, read, update and delete **only the files created by Mind Business** (encrypted browser profile copies in the `Mind Business Sync` folder). The app cannot see or read any other file in your Drive. |
| `openid`, `userinfo.email` | Show the email address of the connected Google account, so you know which Drive is being used. |

Each profile is **encrypted on your computer with a sync password you choose** before it is uploaded. Mind Business has no servers of its own: files go directly from your computer to your Google Drive, and we cannot read their contents.

You can disconnect at any time in the app, or revoke access on your [Google Account permissions page](https://myaccount.google.com/permissions).

Details on how data is handled: [Privacy Policy](privacy.html).

## Contact

Email: [{{ site.email }}](mailto:{{ site.email }})
