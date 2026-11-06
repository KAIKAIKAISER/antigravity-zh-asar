# Google Antigravity 全量深度汉化包 (`app.asar`)

- **当前适配客户端版本**：`v2.29.0`
- **精准词库词条数**：`2179` 条
- **文件大小**：`4.97 MB`
- **最后编译更新时间**：`2026/11/6 23:20:27`

---

## 🚀 在别的电脑上极速汉化（2 种方式任选）

### 方式一：浏览器直接下载覆盖（无需安装任何工具）
1. 点击上方文件列表中的 **[app.asar](./app.asar)** -> 点击右侧下载按钮（**Download raw file**），或在右侧 **Releases** 中直接点击下载 `app.asar`。
2. 关闭目标电脑上的 Antigravity 客户端。
3. 按 `Win + R` 输入以下命令并回车打开资源目录：
   ```text
   %LOCALAPPDATA%\Programs\antigravity\resources
   ```
4. 将下载好的 `app.asar` 粘贴进去覆盖原文件，重新打开客户端即为完整中文。

### 方式二：PowerShell 一行命令拉取替换（已登录 GitHub CLI 的电脑）
在 PowerShell 中直接运行：
```powershell
Copy-Item "$env:LOCALAPPDATA\Programs\antigravity\resources\app.asar" "$env:LOCALAPPDATA\Programs\antigravity\resources\app.asar.bak" -ErrorAction SilentlyContinue; gh release download latest -R KAIKAIKAISER/antigravity-zh-asar -p "app.asar" -D "$env:LOCALAPPDATA\Programs\antigravity\resources" --clobber
```
