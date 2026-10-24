# daily-news-inbox

Inbox dữ liệu cho [sontvwork/daily-news](https://github.com/sontvwork/daily-news).

- **Grok Automation** chạy lúc 05:30 giờ VN, commit file `grok/<YYYY-MM-DD>.json` (schema `grok-inbox/1`), message `grok: <YYYY-MM-DD>`.
- **Routine Daily News** (07:00) đọc file qua `https://raw.githubusercontent.com/sontvwork/daily-news-inbox/main/grok/<DATE>.json`.

Repo này tách riêng để Grok không có quyền ghi vào repo pipeline. Nội dung ở đây là dữ liệu bên thứ ba, chưa kiểm chứng.
