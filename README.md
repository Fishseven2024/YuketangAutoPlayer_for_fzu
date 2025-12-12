# 🌧️ 雨课堂公益助手 (FZU定制适配版)

> **⚠️ 郑重声明**
> 本项目基于 [YuketangAutoPlayer](https://github.com/Fishseven2024/YuketangAutoPlayer) 修改，遵循 **LGPL-2.1** 开源协议。
> **仅供技术学习与交流，严禁用于任何商业用途。请在下载体验后 24 小时内删除。**

## 📢 修改说明 (2025公益版)
本项目由 **Fishseven2024** 维护，主要针对 **FZU（福州大学）研究生** 环境进行了以下深度修复：
1.  **域名适配**：修复了登录失效问题，完美支持 `changjiang.yuketang.cn` 及 FZU 专用通道。
2.  **弱网优化**：将视频加载超时时间延长至 **30秒**，解决了校园网环境下因加载慢导致的脚本闪退。
3.  **代码纯净**：移除了原版中已失效的功能模块，保留核心自动播放逻辑。

## 🛠️ 环境准备
在使用前，请确保你的电脑已安装：
1.  **Google Chrome 浏览器** (最新版)
2.  **Python 3.x** ([点此下载](https://www.python.org/downloads/))

## 🚀 如何使用

### 第一步：下载与安装
1. 下载本项目代码（点击右上角 Code -> Download ZIP 并解压）。
2. 在解压后的文件夹地址栏输入 `cmd` 打开终端。
3. 安装依赖库：
   ```bash
   pip install selenium
