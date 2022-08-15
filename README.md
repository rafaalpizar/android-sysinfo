# Android Information Commands

## Show android screen
$ scrcpy (on PC)

## ADB shell commands

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


Other resources
1. [ADB Shell Commands List and Detailed Cheat Sheet](https://technastic.com/adb-shell-commands-list/)