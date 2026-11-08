# Đọc Sách Bằng Giọng Nói

Web đọc sách bằng giọng nói, chạy trên Cloudflare Workers.

- Worker: `worker.mjs` (entrypoint), cấu hình tại `wrangler.toml`.
- Triển khai tự động qua Cloudflare Workers Builds từ kho này (nhánh `main`).
- URL: https://doc-sach.nguyenhailinh140101.workers.dev/

Chưa đặt `GOOGLE_CLIENT_ID` / `GOOGLE_CLIENT_SECRET` — kích hoạt Google Drive sau.
