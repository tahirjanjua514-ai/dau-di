SEARX AI Downloader - Android starter project

BUILD APK WITH GITHUB ACTIONS
1. Create a new GitHub repository (Public or Private).
2. Upload all files and folders from this project ZIP to the repository root.
   Make sure the .github/workflows/build-apk.yml file is included.
3. Open the repository's Actions tab.
4. Select "Build SEARX AI Downloader APK" and click "Run workflow" if it has not started automatically.
5. Wait for the workflow to finish successfully.
6. Open the completed workflow run, scroll to Artifacts, and download "SEARX-AI-Downloader-APK".
7. Extract the downloaded artifact ZIP; it contains app-debug.apk.

The workflow installs JDK, Gradle and Android SDK on GitHub-hosted runner and builds the APK.
Package: com.searxai.downloader
Minimum Android: 8.0 (API 26)
Target SDK: 35

FEATURES IN THIS STARTER
- Dark blue/purple Compose UI.
- Detects YouTube, Facebook, Instagram and TikTok URL hosts.
- Downloads direct HTTP/HTTPS media-file URLs with Android DownloadManager.
- Android notification and Downloads folder destination.

IMPORTANT LIMITATION
This starter does NOT extract media from social-platform webpage links. Platform detection alone does not provide a downloadable media stream. Platform-specific downloading requires permitted, authorized integrations. No DRM, private-content or access-control bypass is implemented.
