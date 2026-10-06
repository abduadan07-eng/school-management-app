# School Management System — GitHub APK Build

This project is prepared for building the Android release APK with GitHub Actions.

## Build on GitHub from a phone

1. Upload the contents of this project to the GitHub repository root.
2. Open **Actions**.
3. Select **Build School Management APK**.
4. Tap **Run workflow**.
5. Wait for the job to finish.
6. Open the completed run and download the artifact named **school-management-release-apk**.

### Important
The workflow generates the Android platform files automatically. It also removes Flutter's generated template `test/widget_test.dart`, which otherwise expects a `MyApp` class that this project does not use.

The existing unit tests in `test/unit/` are kept and will still run.
