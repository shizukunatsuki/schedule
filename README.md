# 一周二十一节

固定周课表：每天上午（07:00–12:00）、下午（13:00–18:00）、晚上（19:00–21:00）各一节，一周 21 节 = 14 大节 + 7 小节。六科（数学 / 语文 / 历史 / 政治 / 地理 / 日语）间隔按节数均匀，是穷举验证的全局最优；整周全局面貌直接显示，按今天是周几高亮。

- 线上：https://schedule.natsuki.cloud
- 页面：`public/index.html`（单文件，无构建步骤）
- 设计规则：`DESIGN.md`
- 部署：推到 `main` 后由 Cloudflare Workers Builds 执行 `npx wrangler deploy`；域名、workers.dev 和预览 URL 的开关都在 `wrangler.jsonc` 里
