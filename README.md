# 抢票助手 Pro（iPhone 可用 PWA）

这是一个可部署到 Vercel 的静态 PWA，适合在 iPhone 上通过 Safari 打开后“添加到主屏幕”。

## 文件说明
- `index.html` 主页面
- `manifest.json` PWA 配置
- `service-worker.js` 离线缓存
- `icons/` 应用图标

## Vercel 部署步骤
1. 登录 Vercel
2. 新建项目时选择 `Other`
3. 直接上传整个项目文件夹，或者把本目录上传到 GitHub 再导入
4. 这是纯静态项目，不需要构建命令
5. 部署完成后，用 iPhone 的 Safari 打开链接
6. 点击“分享”→“添加到主屏幕”

## iPhone 使用
- 推荐用 Safari 打开
- 首次进入后点击“开启通知”
- 添加抢票项目后，页面会在开票前 30 秒 / 5 秒 / 开票时提醒
- 可以导入/导出项目 JSON

## 说明
这是合规的抢票辅助工具，只做提醒、倒计时和一键跳转，不做绕过平台风控的自动刷票。