---
title: Mind Business
permalink: /
---

# Mind Business

Phần mềm desktop chạy trên Windows, giúp đội vận hành quản lý tài sản kinh doanh và hồ sơ trình duyệt (browser profile) tập trung trên máy của mình.

[Chính sách quyền riêng tư](privacy.html) · [English](#english)

## Mind Business làm gì

- **Quản lý tài sản và quy trình vận hành** tập trung một chỗ. Dữ liệu lưu trên máy của bạn.
- **Hồ sơ trình duyệt riêng biệt**: mỗi hồ sơ có dấu vân tay trình duyệt, proxy, cookie và bộ nhớ đệm tách biệt hoàn toàn với các hồ sơ khác.
- **Sao lưu, xuất và nhập hồ sơ trình duyệt**, có mã hoá bằng mật khẩu.
- **Đồng bộ hồ sơ trình duyệt giữa các máy qua Google Drive của chính bạn** (tuỳ chọn).

## Đồng bộ qua Google Drive

Tính năng này chỉ hoạt động khi bạn tự bấm **Kết nối Google Drive** trong phần cài đặt trình duyệt của app và đồng ý trên màn hình đăng nhập của Google. Khi đó app xin các quyền sau:

| Quyền | Dùng để làm gì |
|---|---|
| `drive.file` | Tạo, đọc, cập nhật và xoá **chỉ những file do Mind Business tạo ra** (bản sao hồ sơ trình duyệt đã mã hoá, nằm trong thư mục `Mind Business Sync`). App không thấy và không đọc được bất kỳ file nào khác trong Drive của bạn. |
| `openid`, `userinfo.email` | Hiện địa chỉ email của tài khoản Google đã kết nối, để bạn biết mình đang đồng bộ vào Drive nào. |

Mỗi hồ sơ được **mã hoá ngay trên máy bằng mật khẩu đồng bộ do bạn đặt** rồi mới tải lên. Mind Business không có máy chủ riêng: file đi thẳng từ máy bạn tới Google Drive của bạn, và chúng tôi không đọc được nội dung.

Bạn có thể ngắt kết nối bất cứ lúc nào trong app, hoặc thu hồi quyền tại [trang quyền truy cập tài khoản Google](https://myaccount.google.com/permissions).

Chi tiết cách xử lý dữ liệu: [Chính sách quyền riêng tư](privacy.html).

## Liên hệ

Email: [{{ site.email }}](mailto:{{ site.email }})

---

## English

**Mind Business** is a Windows desktop application that helps operations teams manage business assets and browser profiles in one place, on their own computer.

[Privacy Policy](privacy.html)

### What Mind Business does

- **Asset and operations management** in one place. Data is stored on your computer.
- **Isolated browser profiles**: each profile has its own browser fingerprint, proxy, cookies and cache, fully separated from other profiles.
- **Backup, export and import of browser profiles**, protected with a password.
- **Optional sync of browser profiles between your computers through your own Google Drive.**

### Google Drive sync

This feature is only active after you click **Connect Google Drive** in the app's browser settings and grant consent on Google's sign-in screen. The app requests:

| Scope | Purpose |
|---|---|
| `drive.file` | Create, read, update and delete **only the files created by Mind Business** (encrypted browser profile copies in the `Mind Business Sync` folder). The app cannot see or read any other file in your Drive. |
| `openid`, `userinfo.email` | Show the email address of the connected Google account, so you know which Drive is being used. |

Each profile is **encrypted on your computer with a sync password you choose** before it is uploaded. Mind Business has no servers of its own: files go directly from your computer to your Google Drive, and we cannot read their contents.

You can disconnect at any time in the app, or revoke access on your [Google Account permissions page](https://myaccount.google.com/permissions).

Details: [Privacy Policy](privacy.html).

### Contact

Email: [{{ site.email }}](mailto:{{ site.email }})
