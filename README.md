# 🎬 YSZY 影视资源仓 (Movie/TV Source Repository)

> 这是一个个人维护的影视资源源配置集合，旨在为各类影视播放器（如 TVBox 系列、LunaTV 等）提供稳定、高质量的资源站点配置。

---

## 📦 仓库结构概览

| 文件名 | 用途说明 | 核心关键词 |
| :--- | :--- | :--- |
| `LunaTV.json` | 专为 **LunaTV (原 MoonTV)** 应用程序设计的资源源配置文件。 | 🌙 LunaTV 专用 |
| `tvbox-repos.json` | **TVBox 系列壳子软件**（如影视仓、OK影视 等）的**通用**资源站点配置列表。 | 📺 通用站点 |
| `tvbox-private.json` | 专为 TVBox 壳子系列准备的**个人定制**、非公开站点资源配置。 | 🔒 个人定制 |
| `tvbox-multiple.json` | 基于上述配置文件 (`repos` 和 `private`) **聚合而成的多仓接口**。 | ✨ 多源聚合 |

---

## 🚀 如何使用

您可以通过将对应文件的 **Raw 链接** 复制到您的播放器设置中，即可快速导入资源源。

### 1. 导入通用资源（TVBox）

如果您是**普通用户**，推荐使用这个文件：

➡️ **`tvbox-repos.json`**：适用于大多数人，包含主流、稳定的影视站点。

### 2. 导入聚合资源（TVBox）

如果您想**一次性**导入所有站点（包括通用和定制内容），请使用：

🔗 **`tvbox-multiple.json`**：该文件已集成了 `tvbox-repos.json` 和 `tvbox-private.json` 的所有内容。

### 3. LunaTV 用户

专为 LunaTV 准备：

🌙 **`LunaTV.json`**：请导入到 LunaTV 相关的配置入口。

---

## ⚠️ 免责声明

本仓库仅提供资源的**配置链接**，所有内容均来源于互联网，请遵守当地法律法规使用。
