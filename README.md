<div align="center">
  <img src="https://edu-image.nosdn.127.net/32a8dd2a-b9aa-4ec9-abd5-66cd8751befb.png?imageView&quality=100" width="128" height="128" alt="Project Logo">
  <h1>中国大学MOOC(慕课)功能增强脚本</h1>
  <p><strong>Chinese University MOOC Enhancer</strong></p>
  <p>一个旨在增强中国大学MOOC的视频学习体验的油猴脚本。</p>
  
  <p>
    <a href="https://github.com/zhumengstarsandsea/Chinese_University_MOOC_Enhancer">
      <img src="https://img.shields.io/badge/GitHub-仓库-blue?style=flat-square&logo=github" alt="GitHub Repo"></a>
    </a>
    <a href="https://greasyfork.org/zh-CN/scripts/543446-%E4%B8%AD%E5%9B%BD%E5%A4%A7%E5%AD%A6mooc-%E6%85%95%E8%AF%BE-%E5%8A%9F%E8%83%BD%E5%A2%9E%E5%BC%BA-chinese-university-mooc-enhancer"> <img src="https://img.shields.io/badge/GreasyFork-发布-green?style=flat-square&logo=git" alt="GreasyFork"></a>
    </a>
    <a href="https://openuserjs.org/scripts/your-username/your-script-name"> <img src="https://img.shields.io/badge/OpenUserJS-发布-orange?style=flat-square&logo=javascript" alt="OpenUserJS"></a>
    </a>
    <br>
    <img src="https://img.shields.io/github/package-json/v/zhumengstarsandsea/Chinese_University_MOOC_Enhancer?style=flat-square" alt="Version">
    </a>
    <img src="https://img.shields.io/badge/JavaScript-100%25-yellow?style=flat-square" alt="Language">
    <a href="https://github.com/zhumengstarsandsea/Chinese_University_MOOC_Enhancer/blob/main/LICENSE">
      <img src="https://img.shields.io/github/license/zhumengstarsandsea/Chinese_University_MOOC_Enhancer?style=flat-square" alt="License">
    </a>
  </p>
</div>

---

## 📖 简介 (Introduction)

本脚本尝试提升**中国大学MOOC**网站的视频观看和课程导航效率，为此拥有多项实用的小功能。

## ✨ 核心功能 (Key Features)

| 功能点 | 描述 |
| :--- | :--- |
| **🔓 解除页面限制** | 解除网站对`鼠标右键`的限制。 |
| **🔊 音量增强控制** | 在播放器顶部添加音量增益控件，允许将音量放大到超过100%，解决课程音量过小问题。 |
| **🧠 自动播放记忆** | 自动记忆并同步“自动播放下一视频”的设置，免去重复勾选的麻烦。 |
| **🚫 阻止冲突交互** | 阻止空格键`空格`和上下方向键`↑`/`↓`在未全屏视频播放器时进行页面滑动，保证其只对播放器的的交互。  |
| **▶️ 智能视频导航** | 在播放器下方添加“上一个/下一个”按钮，无需返回目录即可快速切换。 |
| **🎯 感知边界检测** | 能智能识别不同课程不同学期，并自动检测章节边界，在第一个/最后一个视频处禁用相应按钮，防止误操作。 |
| **⌨️ 键盘快捷键** | `B`键上一个视频，`N`键下一个视频。 |
| **🗄️ 多级缓存** | 内置`课程(90天)`/`学期(30天)`/`视频(7天)`三级缓存机制，缓存边界检测结果，极大提升导航性能。 |
| **⚙️ 控制台输出** | `F12`打开控制台即可查看详尽的日志输出。 |

---

## 🚀 安装 (Installation)

1.  首先，您的浏览器需要安装一个用户脚本管理器。推荐使用 <img src="https://www.tampermonkey.net/images/icon.png" height="16" alt="Tampermonkey Logo" style="vertical-align: -0.2em;"> **Tampermonkey**。
    * <img src="https://upload.wikimedia.org/wikipedia/commons/9/98/Microsoft_Edge_logo_%282019%29.svg" height="16" alt="Edge Logo" style="vertical-align: -0.2em;"> [Edge 安装链接](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd)
    * <img src="https://upload.wikimedia.org/wikipedia/commons/e/e1/Google_Chrome_icon_%28February_2022%29.svg" height="16" alt="Chrome Logo" style="vertical-align: -0.2em;"> [Chrome 安装链接](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
    * <img src="https://upload.wikimedia.org/wikipedia/commons/a/a0/Firefox_logo%2C_2019.svg" height="16" alt="Firefox Logo" style="vertical-align: -0.2em;"> [Firefox 安装链接](https://addons.mozilla.org/firefox/addon/tampermonkey/)

3.  然后，从以下任一地址安装本脚本：

    *  <img src="https://github.com/greasyfork-org/greasyfork/blob/main/public/images/blacklogo32.png" height="16" alt="GreasyFork Logo" style="vertical-align: -0.2em;"> **[GreasyFork](https://greasyfork.org/zh-CN/scripts/543446-%E4%B8%AD%E5%9B%BD%E5%A4%A7%E5%AD%A6mooc-%E6%85%95%E8%AF%BE-%E5%8A%9F%E8%83%BD%E5%A2%9E%E5%BC%BA-chinese-university-mooc-enhancer)** (推荐，稳定发布版)
    * <img src="https://github.com/fluidicon.png" height="16" alt="GitHub Logo" style="vertical-align: -0.2em;"> **[GitHub](https://github.com/zhumengstarsandsea/Chinese_University_MOOC_Enhancer/releases/tag/new)** (获取最新开发版)
    *  <img src="https://github.com/OpenUserJS/OpenUserJS.org/blob/master/public/images/favicon32.png" height="16" alt="OpenUserJS Logo" style="vertical-align: -0.2em;"> **[OpenUserJS](https://openuserjs.org/scripts/your-username/your-script-name)** (备用发布地址)
---

## 🛠️ 使用说明 (Usage)

-   **自动运行**: 脚本是全自动的。安装后，在任意中国大学MOOC的视频学习页面 (`/learn/` 或 `/spoc/learn/`)，脚本将自动加载并生效。
-   **功能控制**: 您可以通过播放器上新增的UI控件使用音量增益和导航功能，使用键盘快捷键 **B** 或者 **N** 进行切换上一个或者下一个视频操作。
-   **缓存管理**:
    -   **自动管理**: 脚本会自动创建和清理过期缓存。
    -   **手动清除**: 如果遇到课程内容更新导致边界检测不准的情况，可以通过油猴菜单命令 **“🗑️ 清除视频边界缓存”** 来手动清除所有课程的缓存数据。
-   **内存管理**: 可以通过油猴菜单命令 **“♻️ 释放边界检测内存”** 来手动释放边界检测的相关进程内存而不清除课程的缓存数据。
-   **查看日志**: 按 `F12` 打开浏览器开发者工具，切换到 `Console` (控制台) 标签页，即可查看脚本输出的详细工作日志，便于了解脚本运行状态或排查问题。

---

## 🤝 贡献与反馈 (Contributing & Feedback)

欢迎通过 <img src="https://github.com/fluidicon.png" height="16" alt="GitHub Logo" style="vertical-align: -0.2em;"> **[GitHub Issues](https://github.com/zhumengstarsandsea/Chinese_University_MOOC_Enhancer/issues)** 来报告BUG或提出功能建议！

如果您觉得这个脚本对您有帮助，请给这个项目一个 ⭐ Star！您的支持是作者更新的最大动力！

## 📄 许可证 (License)

本项目采用 [AGPL-3.0](https://github.com/zhumengstarsandsea/Chinese_University_MOOC_Enhancer/blob/main/LICENSE) 许可证。
