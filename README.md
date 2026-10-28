# skills

我的 Claude Skill 合集。每个文件夹是一个独立的 Skill。

| Skill | 用途 |
|---|---|
| [wechat-cover-design](wechat-cover-design/) | 桥川公众号封面设计：输入标题和 IP 人物图，按 8 种排版 × 16 种风格生成公众号横版封面（2.35:1，900×383） |

## 怎么安装

**Claude 网页版 / 桌面版**

1. 点上面绿色的 **Code** 按钮 → **Download ZIP**，解压
2. 把里面的 `wechat-cover-design` 文件夹单独压缩成一个 zip
3. 打开 Claude → 设置 → Capabilities（功能）→ Skills → 上传这个 zip

**Claude Code**

把 `wechat-cover-design` 文件夹放到 `~/.claude/skills/` 下面。

## 公众号封面设计怎么用

装好后直接跟 Claude 说，比如：

> 帮我做公众号封面，标题是「我用 WorkBuddy 一键做的封面，跑出了几十万阅读」，人物用这张图，风格你推荐

附上你的 IP 人物图。Claude 会帮你选排版和风格、拆标题、拼好提示词；有生图工具就直接出图，没有就把提示词给你，贴到 GPT 生图、即梦等工具里用。

### 16 种风格

| | | | |
|---|---|---|---|
| ![](wechat-cover-design/assets/previews/style-01.webp)<br>01 C4D精致三维 | ![](wechat-cover-design/assets/previews/style-02.webp)<br>02 剪纸 | ![](wechat-cover-design/assets/previews/style-03.webp)<br>03 羊毛毡 | ![](wechat-cover-design/assets/previews/style-04.webp)<br>04 铅笔素描 |
| ![](wechat-cover-design/assets/previews/style-05.webp)<br>05 像素体素 | ![](wechat-cover-design/assets/previews/style-06.webp)<br>06 彩色波纹玻璃 | ![](wechat-cover-design/assets/previews/style-07.webp)<br>07 高级3D动画 | ![](wechat-cover-design/assets/previews/style-08.webp)<br>08 3D艺术盲盒 |
| ![](wechat-cover-design/assets/previews/style-09.webp)<br>09 复古未来主义 | ![](wechat-cover-design/assets/previews/style-10.webp)<br>10 Y2K | ![](wechat-cover-design/assets/previews/style-11.webp)<br>11 扁平插画 | ![](wechat-cover-design/assets/previews/style-12.webp)<br>12 陶土橡皮泥 |
| ![](wechat-cover-design/assets/previews/style-13.webp)<br>13 亮面金属 | ![](wechat-cover-design/assets/previews/style-14.webp)<br>14 机械朋克 | ![](wechat-cover-design/assets/previews/style-15.webp)<br>15 赛博朋克 | ![](wechat-cover-design/assets/previews/style-16.webp)<br>16 拼贴 |

在线版：[公众号封面工作室](https://culture-cover-studio.app.workbuddy.host/?sharecode=ZRPINQAU2V)
