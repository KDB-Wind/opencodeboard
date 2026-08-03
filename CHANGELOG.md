# 68HUB Changelog

## v1.1.2

- **新增 macOS Intel (x64) 安装包**：GitHub Actions 自动构建 mac-x64 与 mac-arm64 DMG
  Added macOS Intel (x64) installer: builds both mac-x64 and mac-arm64 DMGs
- **OpenAI 模型图标改为本地内联 SVG**：不再依赖外部 CDN
  OpenAI model icons now bundled locally, no external CDN
- **修正输入 Token 统计**：输入包含缓存命中与缓存写入，与网页用量一致
  Fixed input token stats to include cache hit/write, matching the web
- **Token 明细悬浮窗**：首页总 Token 与统计页输入卡片悬浮查看明细与命中率
  Token breakdown tooltip on Dashboard and Token Stats
- **记录级缓存明细**：使用记录表格中悬浮每条记录的输入数值，即可查看该条的缓存命中与写入明细
  Per-record cache breakdown: hover any input token in the usage table to see cache hit/write details
- **用量解析与同步增强**：按字段名解析，同步自动更新已有记录
  Field-based parsing; sync updates existing records

## macOS 优化 | macOS

- 使用原生标题栏与交通灯按钮，自定义按钮仅保留在 Windows；品牌文字移至右上角
  Native title bar and traffic lights; custom buttons are Windows-only; brand moves to top-right
- 原生关闭按钮支持最小化到托盘，确认退出时真正退出
  Native close button supports minimize-to-tray and real quit
- 菜单栏图标改为 16x16 彩色小图标
  Menu bar icon is now a 16x16 colored icon
