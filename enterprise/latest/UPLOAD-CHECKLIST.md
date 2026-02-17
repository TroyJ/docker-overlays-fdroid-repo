# Managed Play Upload Checklist

1. Log into your EMM managed Google Play iframe (Private apps) or Play Console.
2. Upload `app-release.aab` (preferred) or `app-release.apk` if your enterprise workflow uses APK uploads.
3. Keep package name identical (`com.prado.treeviewer`) to deliver updates.
4. Assign to policy (`FORCE_INSTALLED` or `REQUIRED_FOR_SETUP` as needed).
5. Validate install/update/accessibility on target OEM firmware.
