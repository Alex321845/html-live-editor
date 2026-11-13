# html-live-editor

一个 Windows 单文件桌面工具。下载 `html-live-editor.exe` 后直接运行即可，无需安装，也无需额外配置运行环境。

## 下载

前往 [Releases](https://github.com/Alex321845/html-live-editor/releases) 页面，下载 `v1.0.0` 中的 `html-live-editor.exe`。

## 使用

1. 把 `html-live-editor.exe` 保存到本地任意目录。
2. 双击运行。
3. 首次运行时，Windows SmartScreen 可能对未签名的可执行文件给出安全提示；确认文件确实下载自本仓库后，选择「仍要运行」即可。

## 文件校验

| 文件 | 大小 | SHA-256 |
| --- | --- | --- |
| `html-live-editor.exe` | 6,818,304 字节（约 6.6 MB） | `9e5220cfd01096633e939435bd6c258b39c38facb14f803e37b270874602ff04` |

在 PowerShell 中校验：

```powershell
Get-FileHash .\html-live-editor.exe -Algorithm SHA256
```

## 关于本仓库

本仓库用于发布构建产物。`exe` 以 Release 附件的形式提供，不纳入 git 版本控制，避免二进制文件让仓库体积随每次更新持续增长。

> 功能介绍、界面截图与源码说明由作者后续补充。
