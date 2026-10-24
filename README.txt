SAMI PHARMACIST ACADEMY — VOLUME 1

WHAT IS INCLUDED
- Offline-ready web app with a 1,000-item MCQ bank.
- Answer choices, correct answers, explanations, subject/chapter tags, search, practice mode, exam mode, score, bookmarks and mistake review.
- questions-volume-1.json as a separate editable question bank for future volumes.
- Android WebView project and GitHub Actions workflow that builds an installable debug APK.
- All learning content is bundled locally; normal app use does not require internet.

IMPORTANT HONEST LIMITATION
This package includes the Android source project and an automated build workflow, but does NOT include a precompiled APK. This environment has no Android SDK/Gradle installation, so a binary APK could not be compiled here. The workflow can compile the APK after the project is pushed to a GitHub repository and the workflow is run. The debug APK can be installed on Android after downloading it from the workflow artifact. A Play Store release requires a signed release build and publishing steps.

USE THE BROWSER APP
Open index.html in a browser to use it now. For Chrome's Install app option, the app must be hosted on HTTPS (or localhost); opening a local file alone does not meet PWA installation requirements. The Android wrapper project loads the same HTML from local app assets and works offline.

ANDROID BUILD
1. Create a GitHub repository and upload the contents of this folder, including the android folder and .github/workflows/build-apk.yml.
2. Open the repository's Actions tab.
3. Run “Build Android APK” (workflow_dispatch), or push a change under android/.
4. Open the completed run and download the “Sami-Pharmacist-Academy-APK” artifact. Extract it and install app-debug.apk on your Android phone. Android may ask you to allow installation from that source.

FUTURE VOLUMES
Keep Volume 1 as a separate question bank. For Volume 2, Volume 3, etc., add separate JSON banks and assign unique IDs (V2-0001, V3-0001, etc.) so progress can be managed by volume. The current app embeds Volume 1 data inside index.html; update that embedded data or merge new banks when building a later version.

CLINICAL SAFETY
Questions are for education and exam practice, not a substitute for current Ethiopian national guidelines, facility SOPs, product information, or clinical judgement. Some items are foundational or general and should be checked against current references before formal teaching or clinical use. For patient care, verify current recommendations and individual patient factors.
