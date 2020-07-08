# 32 位和 64 位版本

64 位版本可处理更大的文件（大于 2GB），但无论壁纸文件大小如何，它都始终占用更多内存。 例如，对于普通视频壁纸，与 32 位版本相比，64 位版本可能使用大约 50 MB 以上的 RAM，此外没有任何区别或改进。

::: tip 我们建议您坚持使用 32 位版本，除非您的壁纸非常大，会使 32 位版本崩溃。 绝大多数用户从未遇到此问题。 :::

如果 PC 上的视频系统出现仅影响 32 位程序的错误，您也可以选择 64 位版本。 如果您曾经安装过编解码器包或类似程序，它们可能已经永久损坏了 Wallpaper Engine 使用的 32 位 Windows 视频系统。 如果 64 位系统不受影响，您可以使用 64 位版本的 Wallpaper Engine，这样就不必修复任何损坏的内容了。

::: warning 注意 请注意，“Web”类型的壁纸将始终使用 32 位可执行文件 (webwallpaper32.exe) 来执行。 用户界面本身也是如此 (ui32.exe)。 仅当选择了“场景”或“视频”类型的壁纸时，才适用 64 位可执行文件。 :::

## 如何将 Wallpaper Engine 设置为在 Windows 启动时以 32 位或 64 位版本自动启动？

首先，通过托盘图标完全关闭 Wallpaper Engine（右键单击 Windows 托盘中的 Wallpaper Engine 图标 ->“退出”）。 请务必执行此操作，否则 Steam 不会启动 Wallpaper Engine，而只会将已经运行的版本置于前台。

关闭 Wallpaper Engine 以后，转到 Steam 并启动 32 位或 64 位版本，具体取决于您要自动启动的版本。 转到 Wallpaper Engine 设置，然后在“常规”选项卡顶部启用自动启动。 如果已启用该功能，则将其完全关闭，然后再重新打开。 这会将当前版本注册为要随 Windows 自动启动的版本。 