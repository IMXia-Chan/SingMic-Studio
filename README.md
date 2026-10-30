# 声麦 Studio Pro（SingMic Studio）

本仓库是《声麦 Studio Pro》的公开页面，只放两样东西：

1. **隐私政策** —— https://imxia-chan.github.io/SingMic-Studio/
   英文版 —— https://imxia-chan.github.io/SingMic-Studio/en.html
2. **插件支持包下载** —— 见 [Releases](https://github.com/IMXia-Chan/SingMic-Studio/releases)

程序源码不在本仓库。

---

## 插件支持包

VST3 插件由单独的「插件支持包」提供，不与主程序一起分发。

1. 从 [Releases](https://github.com/IMXia-Chan/SingMic-Studio/releases) 下载
   `SingMicVstHost-<版本>-win64.zip`
2. 打开 声麦 Studio Pro → **设置 → 插件支持**
3. 点「打开支持包文件夹」，把 zip 里的 `SingMicVstHost` 整个文件夹解压进去。
   最终应当是 `...\SingMic\data\vst_host\SingMicVstHost\SingMicVstHost.exe`
4. 回到程序打开插件页即可，不需要重启

没有安装支持包时，主程序其余功能不受影响；插件页会明确提示缺少支持包。

支持包按 GPL-3.0 分发，完整对应源码随包附在 `src\` 目录下。

---

© 2026 IMXia-Chan
