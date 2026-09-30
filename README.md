# ❄️ rime.moe

> **"Subcooled until disturbed."**  
> 一个以“雾凇（Rime）、低温物理、冰霜妖精（琪露诺 ⑨）、Linux 内核与 eBPF 网络安全”为隐喻的赛博极客风格命令行（CLI）个人主页。

---

## ✨ 特性亮点

- **单文件零依赖**：纯原生 HTML5 + CSS3 + Vanilla ES6+ 编写，无任何 NPM 构建或外部 CDN 依赖，开箱即用。
- **Nord / Deep Ice 调色体系**：采用深邃夜色（`#0d1117`）、冰蓝（`#7dcfff`）、冷白与柔绿构建的冷冽极客视觉。
- **拟真终端交互**：
  - 随行透明代理 Input + 真实反色实心方块光标（`animation: blink`）。
  - 智能 Tab 补全（支持指令补全与虚拟文件名补全）。
  - 历史命令暂存与上下箭头浏览、`Ctrl+L` 清屏、`Ctrl+C` 中断、中文/日文 IME 输入法防误触保护。
  - 智能选区识别：划选复制文本时绝对不夺取焦点。
- **虚拟 Linux 文件系统**：内置虚拟文件系统（`ls -la`, `cat <file>`, `whoami`, `uname -a`, `ping`, `echo`, `reboot` 等）。
- **移动端深度适配**：视口防缩放（输入框字号 ≥ 16px），底部横向滑动快捷指令栏（Quick Chips Bar），触控即执行。
- **零配置极速部署**：完美适配 Cloudflare Pages、GitHub Pages、Vercel 等静态托管。

---

## ⌨️ 常用终端指令

| 指令 | 说明 |
| :--- | :--- |
| `about` | 个人身份、低温物理哲学与赛博孤岛心境 |
| `skills` / `tech` | 技术栈（Linux Zen/Hardened、eBPF/XDP、dae、BGP Anycast、低熵架构） |
| `status` | 绝对零度（0.000 Kelvin）系统遥测与网络策略 |
| `links` | 外部联络坐标（GitHub、主站域名、PGP 指纹） |
| `ls` / `ls -la` | 查看虚拟文件系统目录树 |
| `cat <file>` | 读取虚拟文件（支持 Tab 补全文件名，如 `cat kernel.bpf`） |
| `whoami` | 输出当前身份与内核 Capabilities 凭据 |
| `uname -a` | 打印内核架构与系统版本 |
| `ping <host>` | 模拟网络探测与 eBPF 物理隔离丢包动画 |
| `cirno` / `9` | 东方 Project 琪露诺 ⑨ 彩蛋与冰晶徽标 |
| `date` | 当前客户端原子时间与热力学时间 |
| `clear` / `Ctrl+L` | 清空屏幕缓冲区 |
| `help` | 显示完整指令清单 |

---

## 🚀 快速开始

### 本地运行
无需任何构建步骤，直接双击 `index.html` 在浏览器打开，或使用任意本地静态服务器：

```bash
# 使用 Python 快速预览
python3 -m http.server 8080
```
浏览器访问 `http://localhost:8080` 即可。

### 部署到 Cloudflare Pages
1. 将本项目推送到 GitHub 仓库。
2. 登录 [Cloudflare Dashboard](https://dash.cloudflare.com/) -> **Workers & Pages** -> **Create application** -> **Pages** -> **Connect to Git**。
3. 选择你的 GitHub 仓库：
   - **Framework preset**：`None`
   - **Build command**：留空
   - **Build output directory**：留空或 `/`
4. 点击 **Save and Deploy**，数秒内即可全球上线。

---

## 📄 License

本项目采用 [MIT License](LICENSE) 开源协议。
