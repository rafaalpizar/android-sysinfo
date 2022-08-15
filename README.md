## Android Information Commands

### Show android screen
$ scrcpy (on PC)

### ADB shell commands

$ adb shell dumpsys
```
What it is possible to dump:
- dumpsys cpuinfo
- dumpsys batterystats
- dumpsys battery
- ACCESSIBILITY MANAGER (dumpsys accessibility)
- ACTIVITY MANAGER PENDING INTENTS (dumpsys activity intents)
- ACTIVITY MANAGER BROADCAST STATE (dumpsys activity broadcasts)
- ACTIVITY MANAGER CONTENT PROVIDERS (dumpsys activity providers)
- ACTIVITY MANAGER SERVICES (dumpsys activity services)
- ACTIVITY MANAGER RECENT TASKS (dumpsys activity recents)
- ACTIVITY MANAGER ACTIVITIES (dumpsys activity activities)
- ACTIVITY MANAGER RUNNING PROCESSES (dumpsys activity processes)
- DISPLAY MANAGER (dumpsys display)
- DREAM MANAGER (dumpsys dreams)
- INPUT MANAGER (dumpsys input)
- MEDIA PROJECTION MANAGER (dumpsys media_projection)
- MEDIA ROUTER SERVICE (dumpsys media_router)
- MEDIA SESSION SERVICE (dumpsys media_session)
- POWER MANAGER (dumpsys power)
- PRINT MANAGER STATE (dumpsys print)
- VOICE INTERACTION MANAGER (dumpsys voiceinteraction)
- WINDOW MANAGER LAST ANR (dumpsys window lastanr)
- WINDOW MANAGER POLICY STATE (dumpsys window policy)
- WINDOW MANAGER ANIMATOR STATE (dumpsys window animator)
- WINDOW MANAGER SESSIONS (dumpsys window sessions)
- WINDOW MANAGER DISPLAY CONTENTS (dumpsys window displays)
- WINDOW MANAGER TOKENS (dumpsys window tokens)
- WINDOW MANAGER WINDOWS (dumpsys window windows)
```

```
$ adb shell getprop
$ adb shell cat /proc/buddyinfo
$ adb shell cat /proc/cpuinfo
$ adb shell cat /proc/meminfo
$ adb shell cat /proc/zoneinfo
$ adb shell cat /proc/zraminfo
```

### Examples
```
$ adb shell getprop | grep 'model\|cpu\|gpu\|platform\|product\|mem'
[persist.sys.fake.cpu]: [MT6592]
[persist.sys.fake.cpu_cores]: [10]
[persist.sys.fake.memory]: [4]
[ro.board.platform]: [mt6592]
[ro.build.product]: [sf6592_wet_l]
[ro.mediatek.platform]: [MT6592]
[ro.mtk_mem_comp_support]: [1]
[ro.product.board]: [K1006P9C]
[ro.product.brand]: [NERLMIAY]
[ro.product.cpu.abi2]: [armeabi]
[ro.product.cpu.abi]: [armeabi-v7a]
[ro.product.cpu.abilist32]: [armeabi-v7a,armeabi]
[ro.product.cpu.abilist64]: []
[ro.product.cpu.abilist]: [armeabi-v7a,armeabi]
[ro.product.device]: [K1001P95]
[ro.product.locale.language]: [en]
[ro.product.locale.region]: [US]
[ro.product.manufacturer]: [alps]
[ro.product.model]: [k10]
[ro.product.name]: [K1001P95]
[ro.romtool.fake_memory]: []
[ro.ty.fake.cpu_cores]: [8]
[ro.ty.fake.cpu_freq]: [2.0]
[ro.ty.fake.cpu_model]: [MT6592]
[ro.ty.fake.cpu_platform]: [MT6592]
[ro.ty.fake.gpu_mode]: []
[ro.ty.fake.gpu_platform]: []
```

### Other resources
1. [ADB Shell Commands List and Detailed Cheat Sheet](https://technastic.com/adb-shell-commands-list/)