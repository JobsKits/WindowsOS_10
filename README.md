# WindowsOS_10

![Jobs出品，必属精品](https://picsum.photos/1500/400)

---

## 🔥 <span id="前言">前言</span>

Jobs 维护的 Windows 10 镜像资料子仓。父仓 [WindowsOS](../README.md) 管理 Git 子模块关联与按需下载，镜像附件来自 [**GitHub Releases**](https://github.com/JobsKits/WindowsOS_10/releases)，下载后位于本地 `Releases/<标签>/`，由本地 Git 排除规则忽略。

## 一、<span id="tools">本地分卷工具</span> <a href="#前言" style="font-size:17px; color:green;"><b>🔼</b></a> <a href="#🔚" style="font-size:17px; color:green;"><b>🔽</b></a>

本地 `Releases/v1.0.0/` 中的 [merge.command](./Releases/v1.0.0/merge.command) 和 [split.command](./Releases/v1.0.0/split.command) 在 macOS 终端交互运行，支持分卷校验与往返还原；具体布局、按键、上限、日志和删除保护见[分卷工具说明](./Releases/v1.0.0/README.md)。这些链接指向已下载的本地内容，不表示附件随 Git 克隆取得或远端已更新。

脚本只检查依赖，不自动安装或升级；同名输出保留，删除源文件或分卷必须精确输入 `YES`。下载未完成的断点不参与合并，不自动合并或安装系统镜像。

<a id="🔚" href="#前言" style="font-size:17px; color:green; font-weight:bold;">我是有底线的➤点我回到首页</a>
