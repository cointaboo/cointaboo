# cointaboo

免费在线工具 + 技术指南。所有工具在浏览器本地运行，不上传文件。

## 在线工具

| 工具 | 说明 |
|---|---|
| [代理链接转换](https://yuantou.one/tools/proxy/) | VMess/VLESS/SS/Trojan/Hysteria2 → Clash/sing-box/Surge 等 11 种格式 |
| [2FA 验证码生成器](https://yuantou.one/tools/account-card/) | TOTP（RFC 6238），支持批量导入，本地生成不上传 |
| [字幕格式转换](https://yuantou.one/tools/subtitle/) | SRT / VTT / ASS / LRC 互转，支持时间轴平移 |
| [Favicon 生成器](https://yuantou.one/tools/favicon/) | 一张图生成 ICO + 全尺寸 PNG |
| [文本格式转换](https://yuantou.one/tools/convert/) | TXT / MD / HTML / CSV / JSON 互转 |
| [二维码批量生成](https://yuantou.one/tools/qr-batch/) | 每行一条，批量出图打包 ZIP |
| [PDF 工具](https://yuantou.one/tools/pdf/) | 合并 / 拆分 / 提取 / 删页 |
| [手机页面预览](https://yuantou.one/tools/mobile-preview/) | 真 iframe 模拟 iPhone / Android 视口 |

全部免费、免注册、纯前端。

## 技术指南

- [字幕格式详解](https://github.com/cointaboo/subtitle-format-converter) — SRT/VTT/ASS/LRC 结构、时间轴陷阱、编码问题
- [Favicon 完全指南](https://github.com/cointaboo/favicon-generator) — ICO 结构、尺寸用途、引用写法
- [PDF 合并拆分](https://github.com/cointaboo/pdf-merge-split-guide) — 页面树结构、pdf-lib 实现、六个常见坑
- [图片压缩到指定大小](https://github.com/cointaboo/image-compress-guide) — JPEG quality 曲线、二分查找、EXIF 方向
- [批量二维码生成](https://github.com/cointaboo/qr-batch-generator-guide) — 容量上限、纠错级别、ZIP 结构
- [TOTP 二步验证](https://github.com/cointaboo/totp-2fa-guide) — RFC 6238 实现、时间偏差排查、备份策略
- [JSON 格式化与校验](https://github.com/cointaboo/json-formatting-guide) — 大整数精度、大文件流式解析、转 TypeScript
- [批量文本清洗](https://github.com/cointaboo/text-cleaning-guide) — 去重算法选择、账号列表解析、正则与 CSV 陷阱
- [Telegram 账号购买指南](https://github.com/cointaboo/telegram-account-buy-guide) — 老号/新号/直登号的区别与验证方法
- [美区 Apple ID 购买指南](https://github.com/cointaboo/apple-id-purchase-guide) — 独享/共享/免税州怎么选
- [短信接码平台选择指南](https://github.com/cointaboo/sms-verification-guide) — 虚拟号、实体卡、续租的区别
- [海外账号平台甄别指南](https://github.com/cointaboo/overseas-account-platform-guide) — 四类渠道的优缺点与试单方法

## 开源项目

- [web-tools-collection](https://github.com/cointaboo/web-tools-collection) — 上面这些工具的源码
- [phone-mockup](https://github.com/cointaboo/phone-mockup) — Chrome 扩展：手机页面模拟器（自定义状态栏、真手机视图）

## 原则

- 工具不上传文件，所有处理在浏览器本地完成
- 指南只讲判断方法，不推荐具体商家
- 不收集用户数据，不用 Cookie 做追踪
