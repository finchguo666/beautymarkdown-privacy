# 隐私政策 / Privacy Policy

**MD真优雅-BeautyMarkdown** 浏览器扩展

最近更新日期 / Last updated: 2026-09-28

---

## 中文

### 1. 我们收集哪些数据

本扩展**不收集、不上传、不共享任何个人数据**。所有功能均在你的浏览器与本地设备上离线运行,扩展本身不提供任何后端服务器,也不包含数据分析、广告或第三方追踪 SDK。

在使用过程中,以下信息仅保存在你的**本地设备**上:

- 你主动打开的 Markdown 文件内容(本地 `file://` 文件,或 `http://` / `https://` 上的 `.md` 文件)——仅用于在页面中渲染显示;
- 你的阅读偏好设置(主题、字号、开关项等),通过浏览器 `chrome.storage` 在本地保存;
- 最近打开的文件/目录历史(文件路径与名称),仅用于侧边栏快速重开。

### 2. 数据如何被使用与传输

- 上述内容**不会离开你的设备**,不会被发送给开发者或任何第三方服务器。
- Markdown 解析、代码高亮、KaTeX 公式与 Mermaid 图表渲染均在本地完成,所用库与字体均已打包在扩展内,运行时不会向外部请求脚本。
- 导出 Word / PNG、保存本地文件等操作同样在本地完成;保存 `file://` 文件时会调用浏览器/系统的另存对话框,由你确认目标位置。
- 扩展通过 `externally_connectable` **仅响应来自 `http://127.0.0.1` 的安装探测**(供 JetBrains / VS Code 启动器判断扩展是否已安装),回复内容只有"已安装"状态,**不包含任何文件内容或设置信息**。

### 3. 第三方服务

设置页与捐赠弹窗中包含指向 **PayPal、微信、支付宝** 的捐赠链接/收款码。仅当你主动点击或扫码时才会跳转至相应第三方,与这些服务的交互受其各自隐私政策约束,本扩展不参与其数据处理。

### 4. 权限说明

| 权限 | 用途 |
|------|------|
| `storage` | 在本地保存阅读偏好设置 |
| `activeTab` / `scripting` | 在当前 Markdown 页面注入渲染与编辑能力 |
| `sidePanel` | 提供侧边栏文件浏览面板 |
| `file:///*`、`http(s)://*/*.md` 主机权限 | 读取并渲染你打开的本地或在线 Markdown 文件 |
| `externally_connectable` (仅 127.0.0.1) | 响应本机 IDE 启动器的安装探测 |

### 5. 数据删除

卸载扩展即会清除扩展保存的本地设置与历史数据;你也可以随时在扩展设置中重置偏好。

### 6. 联系我们

如对本隐私政策有任何疑问,请联系:**deboywang@126.com**

---

## English

### 1. Data We Collect

This extension **does not collect, upload, or share any personal data**. Every feature runs entirely on your device and in your browser. The extension has no backend servers and contains no analytics, advertising, or third-party tracking SDKs.

During use, the following information is stored **locally on your device only**:

- the content of Markdown files you choose to open (local `file://` files, or `.md` files over `http://` / `https://`) — used solely to render them on the page;
- your reading preferences (theme, font size, toggles, etc.), saved locally via `chrome.storage`;
- recently opened file/folder history (paths and names), used only for quick reopening from the sidebar.

### 2. How Data Is Used and Transmitted

- None of this content **leaves your device**; it is never sent to the developer or any third-party server.
- Markdown parsing, syntax highlighting, and KaTeX / Mermaid rendering all happen locally. The libraries and fonts are bundled with the extension; no external scripts are requested at runtime.
- Exporting to Word / PNG and saving local files also happen locally; saving a `file://` file invokes the browser/system save dialog, and you confirm the destination.
- Via `externally_connectable`, the extension **only answers installation probes originating from `http://127.0.0.1`** (so JetBrains / VS Code launchers can detect whether it is installed). The reply contains only an "installed" status — **never any file content or settings**.

### 3. Third-Party Services

The options page and donation dialog contain donation links/codes for **PayPal, WeChat, and Alipay**. You only reach these services if you actively click or scan the code; your interaction is governed by their respective privacy policies, and this extension is not involved in that processing.

### 4. Permissions

| Permission | Purpose |
|------------|---------|
| `storage` | store reading preferences locally |
| `activeTab` / `scripting` | inject rendering and editing into the current Markdown page |
| `sidePanel` | provide the sidebar file-browser panel |
| `file:///*`, `http(s)://*/*.md` host permissions | read and render the local or online Markdown files you open |
| `externally_connectable` (127.0.0.1 only) | answer the local IDE launcher's installation probe |

### 5. Data Deletion

Uninstalling the extension removes the local settings and history it stored. You may also reset preferences at any time in the extension settings.

### 6. Contact

For questions about this privacy policy, contact **deboywang@126.com**.
