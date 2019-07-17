# DeskClock
Android Pie 系统闹钟源码. 来自分支 origin/pie-release-2

直接下载后的源码是 `Eclipse` 工程结构, 我把他转成了`AS`工程结构.并且 添加了 缺失的依赖.

总之 项目完全可以云心了.

# 源码下载方式参考

https://blog.csdn.net/angcyo/article/details/96282646

# 系统代码包含的APP模块如下

```js
<project path="packages/apps/BasicSmsReceiver" name="platform/packages/apps/BasicSmsReceiver" groups="pdk-cw-fs,pdk-fs" />
<project path="packages/apps/Bluetooth" name="platform/packages/apps/Bluetooth" groups="pdk-cw-fs,pdk-fs" />
<project path="packages/apps/Browser2" name="platform/packages/apps/Browser2" groups="pdk-fs" />
<project path="packages/apps/Calendar" name="platform/packages/apps/Calendar" groups="pdk-fs" />
<project path="packages/apps/Camera2" name="platform/packages/apps/Camera2" groups="pdk-fs" />
<project path="packages/apps/Car/Dialer" name="platform/packages/apps/Car/Dialer" groups="pdk-fs" />
<project path="packages/apps/Car/Hvac" name="platform/packages/apps/Car/Hvac" groups="pdk-fs" />
<project path="packages/apps/Car/LatinIME" name="platform/packages/apps/Car/LatinIME" groups="pdk-fs" />
<project path="packages/apps/Car/Launcher" name="platform/packages/apps/Car/Launcher" groups="pdk-fs" />
<project path="packages/apps/Car/LensPicker" name="platform/packages/apps/Car/LensPicker" groups="pdk-fs" />
<project path="packages/apps/Car/LocalMediaPlayer" name="platform/packages/apps/Car/LocalMediaPlayer" groups="pdk-fs" />
<project path="packages/apps/Car/Media" name="platform/packages/apps/Car/Media" groups="pdk-fs" />
<project path="packages/apps/Car/Messenger" name="platform/packages/apps/Car/Messenger" groups="pdk-fs" />
<project path="packages/apps/Car/Overview" name="platform/packages/apps/Car/Overview" groups="pdk-fs" />
<project path="packages/apps/Car/Radio" name="platform/packages/apps/Car/Radio" groups="pdk-fs" />
<project path="packages/apps/Car/Settings" name="platform/packages/apps/Car/Settings" groups="pdk-fs" />
<project path="packages/apps/Car/Stream" name="platform/packages/apps/Car/Stream" groups="pdk-fs" />
<project path="packages/apps/Car/SystemUpdater" name="platform/packages/apps/Car/SystemUpdater" groups="pdk-fs" />
<project path="packages/apps/Car/libs" name="platform/packages/apps/Car/libs" groups="pdk-fs" />
<project path="packages/apps/CarrierConfig" name="platform/packages/apps/CarrierConfig" groups="pdk-cw-fs,pdk-fs" />
<project path="packages/apps/CellBroadcastReceiver" name="platform/packages/apps/CellBroadcastReceiver" groups="pdk-cw-fs,pdk-fs" />
<project path="packages/apps/CertInstaller" name="platform/packages/apps/CertInstaller" groups="pdk-cw-fs,pdk-fs" />
<project path="packages/apps/Contacts" name="platform/packages/apps/Contacts" groups="pdk-fs" />
<project path="packages/apps/DeskClock" name="platform/packages/apps/DeskClock" groups="pdk-fs" />
<project path="packages/apps/DevCamera" name="platform/packages/apps/DevCamera" groups="pdk" />
<project path="packages/apps/Dialer" name="platform/packages/apps/Dialer" groups="pdk-fs" />
<project path="packages/apps/DocumentsUI" name="platform/packages/apps/DocumentsUI" groups="pdk-cw-fs,pdk-fs" />
<project path="packages/apps/Email" name="platform/packages/apps/Email" groups="pdk-fs" />
<project path="packages/apps/EmergencyInfo" name="platform/packages/apps/EmergencyInfo" groups="pdk-fs" />
<project path="packages/apps/ExactCalculator" name="platform/packages/apps/ExactCalculator" groups="pdk-fs" />
<project path="packages/apps/Gallery" name="platform/packages/apps/Gallery" groups="pdk-fs" />
<project path="packages/apps/Gallery2" name="platform/packages/apps/Gallery2" groups="pdk-fs" />
<project path="packages/apps/HTMLViewer" name="platform/packages/apps/HTMLViewer" groups="pdk-fs" />
<project path="packages/apps/KeyChain" name="platform/packages/apps/KeyChain" groups="pdk-fs" />
<project path="packages/apps/Launcher2" name="platform/packages/apps/Launcher2" groups="pdk-fs" />
<project path="packages/apps/Launcher3" name="platform/packages/apps/Launcher3" groups="pdk-fs" />
<project path="packages/apps/LegacyCamera" name="platform/packages/apps/LegacyCamera" groups="pdk-fs" />
<project path="packages/apps/ManagedProvisioning" name="platform/packages/apps/ManagedProvisioning" groups="pdk-fs" />
<project path="packages/apps/Messaging" name="platform/packages/apps/Messaging" groups="pdk-fs" />
<project path="packages/apps/Music" name="platform/packages/apps/Music" groups="pdk-fs" />
<project path="packages/apps/MusicFX" name="platform/packages/apps/MusicFX" groups="pdk-fs" />
<project path="packages/apps/Nfc" name="platform/packages/apps/Nfc" groups="apps_nfc,pdk-fs" />
<project path="packages/apps/OneTimeInitializer" name="platform/packages/apps/OneTimeInitializer" groups="pdk-fs" />
<project path="packages/apps/PackageInstaller" name="platform/packages/apps/PackageInstaller" groups="pdk-cw-fs,pdk-fs" />
<project path="packages/apps/PhoneCommon" name="platform/packages/apps/PhoneCommon" groups="pdk-cw-fs,pdk-fs" />
<project path="packages/apps/Protips" name="platform/packages/apps/Protips" groups="pdk-fs" />
<project path="packages/apps/Provision" name="platform/packages/apps/Provision" groups="pdk-fs" />
<project path="packages/apps/QuickSearchBox" name="platform/packages/apps/QuickSearchBox" groups="pdk-fs" />
<project path="packages/apps/SafetyRegulatoryInfo" name="platform/packages/apps/SafetyRegulatoryInfo" groups="pdk-fs" />
<project path="packages/apps/SecureElement" name="platform/packages/apps/SecureElement" groups="apps_se,pdk-fs" />
<project path="packages/apps/Settings" name="platform/packages/apps/Settings" groups="pdk-fs" />
<project path="packages/apps/SettingsIntelligence" name="platform/packages/apps/SettingsIntelligence" groups="pdk-fs" />
<project path="packages/apps/SoundRecorder" name="platform/packages/apps/SoundRecorder" groups="pdk-fs" />
<project path="packages/apps/SpareParts" name="platform/packages/apps/SpareParts" groups="pdk-fs" />
<project path="packages/apps/Stk" name="platform/packages/apps/Stk" groups="apps_stk,pdk-fs" />
<project path="packages/apps/StorageManager" name="platform/packages/apps/StorageManager" groups="pdk-fs" />
<project path="packages/apps/Tag" name="platform/packages/apps/Tag" groups="pdk-fs" />
<project path="packages/apps/Terminal" name="platform/packages/apps/Terminal" groups="pdk-fs" />
<project path="packages/apps/Test/connectivity" name="platform/packages/apps/Test/connectivity" groups="pdk" />
<project path="packages/apps/TimeZoneData" name="platform/packages/apps/TimeZoneData" groups="pdk" />
<project path="packages/apps/TimeZoneUpdater" name="platform/packages/apps/TimeZoneUpdater" groups="pdk" />
<project path="packages/apps/Traceur" name="platform/packages/apps/Traceur" groups="pdk-fs" />
<project path="packages/apps/TvSettings" name="platform/packages/apps/TvSettings" groups="pdk-fs" />
<project path="packages/apps/TV" name="platform/packages/apps/TV" />
<project path="packages/apps/UnifiedEmail" name="platform/packages/apps/UnifiedEmail" groups="pdk-fs" />
<project path="packages/apps/WallpaperPicker" name="platform/packages/apps/WallpaperPicker" groups="pdk-fs" />
<project path="packages/experimental" name="platform/packages/experimental" />
<project path="packages/inputmethods/LatinIME" name="platform/packages/inputmethods/LatinIME" groups="pdk-fs" />
<project path="packages/inputmethods/OpenWnn" name="platform/packages/inputmethods/OpenWnn" groups="pdk-fs" />
<project path="packages/providers/ApplicationsProvider" name="platform/packages/providers/ApplicationsProvider" groups="pdk-fs" />
<project path="packages/providers/BlockedNumberProvider" name="platform/packages/providers/BlockedNumberProvider" groups="pdk-fs" />
<project path="packages/providers/BookmarkProvider" name="platform/packages/providers/BookmarkProvider" groups="pdk-fs" />
<project path="packages/providers/CalendarProvider" name="platform/packages/providers/CalendarProvider" groups="pdk-cw-fs,pdk-fs" />
<project path="packages/providers/CallLogProvider" name="platform/packages/providers/CallLogProvider" groups="pdk-fs" />
<project path="packages/providers/ContactsProvider" name="platform/packages/providers/ContactsProvider" groups="pdk-cw-fs,pdk-fs" />
<project path="packages/providers/DownloadProvider" name="platform/packages/providers/DownloadProvider" groups="pdk-cw-fs,pdk-fs" />
<project path="packages/providers/MediaProvider" name="platform/packages/providers/MediaProvider" groups="pdk-cw-fs,pdk-fs" />
<project path="packages/providers/PartnerBookmarksProvider" name="platform/packages/providers/PartnerBookmarksProvider" groups="pdk-fs" />
<project path="packages/providers/TelephonyProvider" name="platform/packages/providers/TelephonyProvider" groups="pdk-cw-fs,pdk-fs" />
<project path="packages/providers/TvProvider" name="platform/packages/providers/TvProvider" groups="pdk-fs" />
<project path="packages/providers/UserDictionaryProvider" name="platform/packages/providers/UserDictionaryProvider" groups="pdk-cw-fs,pdk-fs" />
<project path="packages/screensavers/Basic" name="platform/packages/screensavers/Basic" groups="pdk-fs" />
<project path="packages/screensavers/PhotoTable" name="platform/packages/screensavers/PhotoTable" groups="pdk-fs" />
<project path="packages/screensavers/WebView" name="platform/packages/screensavers/WebView" groups="pdk-fs" />
<project path="packages/services/BuiltInPrintService" name="platform/packages/services/BuiltInPrintService" groups="pdk-cw-fs,pdk-fs" />
<project path="packages/services/Car" name="platform/packages/services/Car" groups="pdk-cw-fs,pdk-fs" />
<project path="packages/services/Mms" name="platform/packages/services/Mms" groups="pdk-cw-fs,pdk-fs" />
<project path="packages/services/NetworkRecommendation" name="platform/packages/services/NetworkRecommendation" groups="pdk-fs" />
<project path="packages/services/Telecomm" name="platform/packages/services/Telecomm" groups="pdk-cw-fs,pdk-fs" />
<project path="packages/services/Telephony" name="platform/packages/services/Telephony" groups="pdk-cw-fs,pdk-fs" />
<project path="packages/wallpapers/LivePicker" name="platform/packages/wallpapers/LivePicker" groups="pdk-fs" />

```

下载方式:

```
git clone git://mirrors.ustc.edu.cn/aosp/`name`
-- git clone git://mirrors.ustc.edu.cn/aosp/platform/packages/apps/DeskClock
```
