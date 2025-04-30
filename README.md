# System Fetch Tool for Android 

---

Andfetch (Android Fetch) is an Android device information display script written in Nushell. It primarily shows manufacturer icons and device information on Android devices, with a layout inspired by Neofetch - featuring ASCII art icon on the left and device information on the right. Additionally, the script can output device information in JSON format.

Currently supported ASCII icon include:

1) Android
2) Google
3) Xiaomi
4) Redmi
5) Vivo
6) Samsung
7) Realme
8) Oppo
9) Huawei
10) Oneplus

Flags:

```
-i, --icon <string>: Specify the ASCII icon to display
--hide_icon: Hide the ASCII icon and only show information
--hide_info: Hide information and only display the ASCII icon
-v, --version: Display the version
-j, --json: Display in JSON format
-I, --indentation <int>: JSON Display indentation level (default: 4)
-s, --space <int>: The spacing between the ASCII icon and the information (default: 4)
-h, --help: Display the help message for this command
```

---

Andfetch (Android Fetch) 是一个使用 Nushell 编写的 Android 设备信息展示脚本，主要用于在 Android 设备上显示制造商图标以及设备的信息，该脚本参考了 Neofetch 的布局，左侧为 ASCII 图标，右侧为设备信息。除此之外该脚本也可以以 JSON 的格式输出设备信息。

目前收录的 ASCII 图标有：

1) Android
2) Google
3) Xiaomi
4) Redmi
5) Vivo
6) Samsung
7) Realme
8) Oppo
9) Huawei
10) Oneplus

参数与开关：

```
-i, --icon <字符串>: 指定显示的 ASCII 图标
--hide_icon: 隐藏 ASCII 图标，仅显示信息
--hide_info: 隐藏信息，仅显示 ASCII 图标
-v, --version: 显示版本信息
-j, --json: 显示为 JSON 格式
-I, --indentation <整数>: 设置 JSON 格式显示的缩进（默认: 4）
-s, --space <整数>: ASCII 图标与信息的间距（default: 4）
-h, --help: 显示该命令的帮助信息
```
