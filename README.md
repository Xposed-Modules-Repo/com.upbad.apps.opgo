# Oneplus No Red One
基于Xposed，去除一加系统锁屏和AOD时钟红色字体样式的模块。

An Xposed module to prevent Oneplus from making red "1" digits on the clocks.

If you hate the red "1" characters on the lock screen clock and AOD (Always-On Display) clock like me, you may try this Xposed module to get rid of it.

For the clock on the lock screen, it should work just fine. For the AOD clock, I only modified the "Digital 2". However, it should be fairly simple for other clocks.

## Some details
The work was based on
- App and version: com.android.systemui, v30
- Test phone: Oneplus 8T
- Build number: Oxygen OS 11.0.8.11.KB05AA
- Android version: 11
- Tested on LSPosed but should work on other Xposed-like frameworks

## Download
[Latest Release](https://github.com/Xposed-Modules-Repo/com.upbad.apps.opgo/releases/latest)

[Xposed Repo](https://repo.xposed.info/module/com.upbad.apps.opgo)
