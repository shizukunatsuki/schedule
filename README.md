# 一日十二节

07:00–18:00 的作息时刻表，块高即时长，带实时红线、下课倒计时、−7h～+6h 整体偏移和可移动的 80 分钟休息。

- 线上：https://schedule.natsuki.cloud
- 页面：`public/index.html`（单文件，无构建步骤）
- 部署：推到 `main` 后由 Cloudflare Workers Builds 执行 `npx wrangler deploy`；域名、workers.dev 和预览 URL 的开关都在 `wrangler.jsonc` 里
