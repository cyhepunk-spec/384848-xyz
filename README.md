# 384848.xyz · 主站导航页

主域名 384848.xyz 的静态导航页，部署在 Cloudflare Pages，绑定 apex 域名。

## 内容

- Muse 提示词生成器 → https://catji.de5.net
- 梯子订阅转换器 → https://ladder.384848.xyz

API 入口与状态监控已预留子域名，不在主站公开（仅资源汇总可见）。

## 部署

纯静态单页（`index.html`），无构建步骤。Cloudflare Pages 项目直接连本仓库，
Framework preset 选 None，Build command 与 Build output directory 留空，
Custom domain 绑 384848.xyz。
