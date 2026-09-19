# Amethyst-Offline
[![Android](https://img.shields.io/badge/Download-Android-green?style=for-the-badge&logoSize=auto&link=https%3A%2F%2Fgithub.com%2FDumDum192%2FAmethyst-Offline%2Factions%2Fworkflows%2Fandroid.yml)](https://github.com/Linux8081/Amethyst-Offline/releases)
&nbsp;

An offline version of [Amethyst](https://wiki.angelauramc.dev/), a MC Launcher based on PojavLauncher.

## Getting Amethyst

You can get Amethyst via three methods:

1. **Releases:** Download the prebuilt app from [Releases](https://github.com/Linux8081/Amethyst-Offline/releases).
2. **Obtainium:** Download [Obtainium](https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/%7B%22id%22%3A%22org.angelauramc.amethyst%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2FLinux8081%2FAmethyst-Offline%22%2C%22author%22%3A%22Linux8081%22%2C%22name%22%3A%22Amethyst%22%2C%22preferredApkIndex%22%3A1%2C%22additionalSettings%22%3A%22%7B%5C%22includePrereleases%5C%22%3Afalse%2C%5C%22fallbackToOlderReleases%5C%22%3Atrue%2C%5C%22filterReleaseTitlesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22filterReleaseNotesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22verifyLatestTag%5C%22%3Afalse%2C%5C%22sortMethodChoice%5C%22%3A%5C%22date%5C%22%2C%5C%22useLatestAssetDateAsReleaseDate%5C%22%3Afalse%2C%5C%22releaseTitleAsVersion%5C%22%3Afalse%2C%5C%22trackOnly%5C%22%3Afalse%2C%5C%22versionExtractionRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22matchGroupToUse%5C%22%3A%5C%22%5C%22%2C%5C%22versionDetection%5C%22%3Afalse%2C%5C%22releaseDateAsVersion%5C%22%3Afalse%2C%5C%22useVersionCodeAsOSVersion%5C%22%3Afalse%2C%5C%22apkFilterRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22invertAPKFilter%5C%22%3Afalse%2C%5C%22autoApkFilterByArch%5C%22%3Atrue%2C%5C%22minimumUpdateAgeDays%5C%22%3A%5C%22%5C%22%2C%5C%22appName%5C%22%3A%5C%22%5C%22%2C%5C%22appAuthor%5C%22%3A%5C%22%5C%22%2C%5C%22shizukuPretendToBeGooglePlay%5C%22%3Afalse%2C%5C%22allowInsecure%5C%22%3Afalse%2C%5C%22allowedSigningCertHashes%5C%22%3A%5C%22%5C%22%2C%5C%22exemptFromBackgroundUpdates%5C%22%3Afalse%2C%5C%22skipUpdateNotifications%5C%22%3Afalse%2C%5C%22about%5C%22%3A%5C%22%5C%22%2C%5C%22refreshBeforeDownload%5C%22%3Afalse%2C%5C%22includeZips%5C%22%3Afalse%2C%5C%22zippedApkFilterRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22includeTarballs%5C%22%3Afalse%2C%5C%22tarballedApkFilterRegEx%5C%22%3A%5C%22%5C%22%7D%22%2C%22overrideSource%22%3Anull%7D
) and get the updates automatically.
3. **Build from Source:** Follow the [building instructions](#building) below.

## Building

Clone the repository: `git clone --recursive https://github.com/Linux8081/Amethyst-Offline.git`

### Android
Patch and build the launcher: `./android-build` (Use `android-build.bat` on Windows).

The built APK will be located in `Amethyst-Android/app_pojavlauncher/build/outputs/apk/debug/`.

## License & Credits
[Amethyst-Android](https://github.com/AngelAuraMC/Amethyst-Android/tree/v3_openjdk?tab=readme-ov-file#license) | [Amethyst-Offline](https://github.com/DumDum192/Amethyst-Offline)
