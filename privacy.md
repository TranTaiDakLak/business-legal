---
title: Chính sách quyền riêng tư — Mind Business
permalink: /privacy.html
---

# Chính sách quyền riêng tư

**Mind Business** · Có hiệu lực từ ngày 22/10/2026

[Trang chủ](./) · [English](#privacy-policy-english)

## 1. Phạm vi

Chính sách này áp dụng cho phần mềm desktop Mind Business trên Windows, và đặc biệt cho dữ liệu người dùng Google mà app truy cập khi bạn dùng tính năng **đồng bộ hồ sơ trình duyệt qua Google Drive**. Tính năng này là tuỳ chọn và chỉ hoạt động sau khi bạn tự kết nối tài khoản Google.

## 2. Dữ liệu Google mà app truy cập

| Dữ liệu | Quyền (scope) |
|---|---|
| Địa chỉ email của tài khoản Google đã kết nối | `openid`, `userinfo.email` |
| Các file **do Mind Business tạo** trong Google Drive của bạn: nội dung đã mã hoá, tên file, kích thước, thời gian sửa, và thông tin kỹ thuật đi kèm (mã hồ sơ, phiên bản, tên máy tính đang dùng hồ sơ) | `drive.file` |
| Mã truy cập và mã làm mới (OAuth token) do Google cấp | — |

App **không** truy cập các file khác trong Drive của bạn, cũng không truy cập Gmail, danh bạ, lịch hay bất kỳ dịch vụ Google nào khác.

## 3. App dùng dữ liệu đó để làm gì

Chỉ để cung cấp tính năng đồng bộ mà bạn thấy trong app:

- tải bản sao hồ sơ trình duyệt đã mã hoá lên Drive của bạn;
- liệt kê, tải về, cập nhật hoặc xoá các bản đó, theo thao tác của bạn hoặc theo cài đặt đồng bộ bạn đã bật;
- báo hồ sơ đang được mở ở máy nào, để tránh hai máy ghi đè lên nhau;
- hiện email của tài khoản đã kết nối.

Chúng tôi **không** bán dữ liệu, **không** dùng cho quảng cáo, **không** dùng để lập hồ sơ người dùng và **không** dùng để huấn luyện mô hình trí tuệ nhân tạo hay học máy.

## 4. Lưu trữ và bảo mật

- **OAuth token** được lưu trên máy của bạn, mã hoá bằng Windows DPAPI (gắn với tài khoản Windows đang dùng), và chỉ được gửi tới Google.
- **Hồ sơ trình duyệt được mã hoá trên máy trước khi tải lên** (AES-256-GCM, khoá dẫn xuất từ mật khẩu đồng bộ bằng scrypt). Không có mật khẩu đồng bộ thì không ai đọc được nội dung, kể cả chúng tôi và Google.
- **Mật khẩu đồng bộ không bao giờ rời khỏi máy**. App lưu nó cục bộ, mã hoá bằng Windows DPAPI. Nếu quên mật khẩu này, các bản trên Drive không khôi phục được.
- Mọi kết nối tới Google đều qua HTTPS.
- App không ghi token, mật khẩu hay cookie vào nhật ký (log).

## 5. Chia sẻ dữ liệu

Mind Business **không có máy chủ thu thập dữ liệu người dùng**. Email, token và các file Drive chỉ đi giữa máy của bạn và Google; chúng tôi không nhận, không lưu giữ và vì vậy không chuyển giao các dữ liệu này cho bất kỳ bên thứ ba nào.

## 6. Tuân thủ chính sách dữ liệu của Google

Việc Mind Business sử dụng và chuyển giao sang bất kỳ ứng dụng nào khác thông tin nhận được từ Google API tuân thủ [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), bao gồm các yêu cầu về Giới hạn sử dụng (Limited Use).

## 7. Ngắt kết nối và xoá dữ liệu

- **Ngắt kết nối trong app**: token trên máy bị xoá ngay.
- **Thu hồi quyền** bất cứ lúc nào tại [trang quyền truy cập tài khoản Google](https://myaccount.google.com/permissions).
- **File trên Drive thuộc về bạn**, nằm trong thư mục `Mind Business Sync`. Bạn có thể xoá trong app hoặc xoá trực tiếp trên Google Drive. Gỡ app hoặc ngắt kết nối **không** tự xoá các file này.
- Dữ liệu cục bộ khác (token, mật khẩu đồng bộ đã mã hoá) bị xoá khi bạn ngắt kết nối hoặc xoá thư mục dữ liệu của app.

## 8. Dữ liệu khác trong app

Ngoài tính năng Google Drive, dữ liệu bạn quản lý trong app (tài sản, hồ sơ trình duyệt, cài đặt) được lưu trên máy của bạn. Khi vận hành, app kết nối tới các dịch vụ do bạn chỉ định, như nền tảng nơi bạn quản lý tài sản, proxy và dịch vụ tra vị trí IP. Dữ liệu người dùng Google **không** được gửi tới các dịch vụ đó.

## 9. Trẻ em

Mind Business là công cụ dùng cho công việc, không hướng tới trẻ em dưới 13 tuổi.

## 10. Thay đổi chính sách

Khi chính sách thay đổi, chúng tôi cập nhật trang này và ngày hiệu lực ở đầu trang. Thay đổi đáng kể về cách xử lý dữ liệu Google sẽ được thông báo trong app.

## 11. Liên hệ

Email: [{{ site.email }}](mailto:{{ site.email }})

---

## Privacy Policy (English)

**Mind Business** · Effective October 22, 2026

### 1. Scope

This policy applies to the Mind Business desktop application for Windows, in particular to Google user data the app accesses when you use the **browser profile sync through Google Drive** feature. The feature is optional and only works after you connect your Google account yourself.

### 2. Google data the app accesses

| Data | Scope |
|---|---|
| Email address of the connected Google account | `openid`, `userinfo.email` |
| Files **created by Mind Business** in your Google Drive: encrypted content, file name, size, modified time, and technical metadata (profile ID, version, name of the computer using the profile) | `drive.file` |
| OAuth access and refresh tokens issued by Google | — |

The app does **not** access any other file in your Drive, nor Gmail, contacts, calendar or any other Google service.

### 3. How the app uses this data

Only to provide the sync feature visible in the app:

- upload encrypted copies of browser profiles to your Drive;
- list, download, update or delete those copies, at your request or according to the sync settings you enabled;
- show which computer currently has a profile open, so two computers do not overwrite each other;
- display the email of the connected account.

We do **not** sell the data, do **not** use it for advertising, do **not** use it to build user profiles, and do **not** use it to train artificial intelligence or machine learning models.

### 4. Storage and security

- **OAuth tokens** are stored on your computer, encrypted with Windows DPAPI (bound to your Windows account), and are only sent to Google.
- **Browser profiles are encrypted on your computer before upload** (AES-256-GCM, key derived from your sync password with scrypt). Without the sync password nobody can read the content, including us and Google.
- **The sync password never leaves your computer.** The app stores it locally, encrypted with Windows DPAPI. If you forget it, the copies in Drive cannot be recovered.
- All connections to Google use HTTPS.
- The app does not write tokens, passwords or cookies to logs.

### 5. Data sharing

Mind Business **has no servers that collect user data**. Your email, tokens and Drive files only travel between your computer and Google; we do not receive or hold this data, and therefore do not transfer it to any third party.

### 6. Compliance with Google's data policy

Mind Business's use and transfer to any other app of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

### 7. Disconnecting and deleting data

- **Disconnect in the app**: the tokens on your computer are deleted immediately.
- **Revoke access** at any time on your [Google Account permissions page](https://myaccount.google.com/permissions).
- **Files in Drive belong to you** and are kept in the `Mind Business Sync` folder. You can delete them in the app or directly in Google Drive. Uninstalling the app or disconnecting does **not** delete these files automatically.
- Other local data (tokens, the encrypted sync password) is deleted when you disconnect or remove the app's data folder.

### 8. Other data in the app

Apart from the Google Drive feature, the data you manage in the app (assets, browser profiles, settings) is stored on your computer. While running, the app connects to services you specify, such as the platforms where you manage your assets, proxies and IP location services. Google user data is **not** sent to those services.

### 9. Children

Mind Business is a work tool and is not directed to children under 13.

### 10. Changes to this policy

When this policy changes, we update this page and the effective date at the top. Significant changes to how Google data is handled will be announced in the app.

### 11. Contact

Email: [{{ site.email }}](mailto:{{ site.email }})
