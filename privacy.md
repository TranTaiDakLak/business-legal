---
title: Privacy Policy — Mind Business
permalink: /privacy.html
---

# Privacy Policy

**Mind Business** · Effective October 22, 2026

[Home](./)

## 1. Scope

This policy applies to the Mind Business desktop application for Windows, in particular to Google user data the app accesses when you use the **browser profile sync through Google Drive** feature. The feature is optional and only works after you connect your Google account yourself.

## 2. Google data the app accesses

| Data | Scope |
|---|---|
| Email address of the connected Google account | `openid`, `userinfo.email` |
| Files **created by Mind Business** in your Google Drive: encrypted content, file name, size, modified time, and technical metadata (profile ID, version, name of the computer using the profile) | `drive.file` |
| OAuth access and refresh tokens issued by Google | — |

The app does **not** access any other file in your Drive, nor Gmail, contacts, calendar or any other Google service.

## 3. How the app uses this data

Only to provide the sync feature visible in the app:

- upload encrypted copies of browser profiles to your Drive;
- list, download, update or delete those copies, at your request or according to the sync settings you enabled;
- show which computer currently has a profile open, so two computers do not overwrite each other;
- display the email of the connected account.

We do **not** sell the data, do **not** use it for advertising, do **not** use it to build user profiles, and do **not** use it to train artificial intelligence or machine learning models.

## 4. Storage and security

- **OAuth tokens** are stored on your computer, encrypted with Windows DPAPI (bound to your Windows account), and are only sent to Google.
- **Browser profiles are encrypted on your computer before upload** (AES-256-GCM, key derived from your sync password with scrypt). Without the sync password nobody can read the content, including us and Google.
- **The sync password never leaves your computer.** The app stores it locally, encrypted with Windows DPAPI. If you forget it, the copies in Drive cannot be recovered.
- All connections to Google use HTTPS.
- The app does not write tokens, passwords or cookies to logs.

## 5. Data sharing

Mind Business **has no servers that collect user data**. Your email, tokens and Drive files only travel between your computer and Google; we do not receive or hold this data, and therefore do not transfer it to any third party.

## 6. Compliance with Google's data policy

Mind Business's use and transfer to any other app of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## 7. Disconnecting and deleting data

- **Disconnect in the app**: the tokens on your computer are deleted immediately.
- **Revoke access** at any time on your [Google Account permissions page](https://myaccount.google.com/permissions).
- **Files in Drive belong to you** and are kept in the `Mind Business Sync` folder. You can delete them in the app or directly in Google Drive. Uninstalling the app or disconnecting does **not** delete these files automatically.
- Other local data (tokens, the encrypted sync password) is deleted when you disconnect or remove the app's data folder.

## 8. Other data in the app

Apart from the Google Drive feature, the data you manage in the app (assets, browser profiles, settings) is stored on your computer. While running, the app connects to services you specify, such as the platforms where you manage your assets, proxies and IP location services. Google user data is **not** sent to those services.

## 9. Children

Mind Business is a work tool and is not directed to children under 13.

## 10. Changes to this policy

When this policy changes, we update this page and the effective date at the top. Significant changes to how Google data is handled will be announced in the app.

## 11. Contact

Email: [{{ site.email }}](mailto:{{ site.email }})
