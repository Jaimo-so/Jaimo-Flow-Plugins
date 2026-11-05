# 截图与贴图

这里保存 Jaimo Flow 截图与贴图功能的源码快照，包括区域截图、标注、复制、保存和贴图，以及快捷键管理。

当前功能内置于 Jaimo Flow，依赖主应用的设置界面和生命周期；本目录不是可独立安装的插件包。应用尚未实现从本仓库下载或加载插件，插件目录暂不列入该功能。

截图需要 macOS 屏幕录制权限。默认快捷键：Control + Option + A 截图，Control + Option + P 贴图。

源码来自 Jaimo Flow 工作区：ScreenshotExtension.swift、CaptureSession.swift 和共享的 HotKeyManager.swift。
