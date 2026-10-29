# REVREN

Automotive garage, meets and crews. Expo SDK 58. English by default, with Czech available in Settings.

This repository contains a GitHub Pages launcher, a standalone Snack source with embedded photos and translations, and the complete native project in `REVREN-GitHub-Snack-SDK58.zip`.

GitHub Pages is enabled from `main`, `/ (root)`: https://oxvaa.github.io/revren/. Open the site and choose **Open REVREN in Snack**. The launcher requests SDK 58 and supplies the source and dependency versions. If Snack downgrades the runtime, that session cannot test this SDK 58 project.

`preview.html` is the browser preview. It is not a native Expo Go session. Data is stored locally; shared accounts and live group chat are not connected.

Extract the ZIP for the native source, tests and build instructions. The source has passed Expo doctor and platform export checks; physical-device testing is still required.

## EAS Update

Expo project: https://expo.dev/accounts/jipo7973/projects/revren

The native source ZIP is linked to this project. SDK 58, `expo-updates`, SDK runtime policy and a `publish:preview` command are configured. iOS and Android export succeeded. The first EAS Update is not published yet; EAS CLI device sign-in approval is pending because it requests account and organization access.
