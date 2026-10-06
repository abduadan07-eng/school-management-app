# School Management System

Flutter + Supabase multi-school School Management System.

## Included
- Existing school-management UI/design preserved from the selected project base.
- Super Admin dashboard for schools, payments, support and platform management.
- School Admin, Teacher, Student and Parent modules.
- Supabase PostgreSQL/Auth/Storage/Edge Functions/RLS project files.
- New Supabase project configuration only.
- One GitHub Actions workflow that generates Android files, runs `flutter analyze`, runs tests, and builds the release APK.

## Supabase
Project URL:
`https://syspfaiggqoopcyrxqvg.supabase.co`

The Flutter client uses the Supabase publishable key. No service-role key or database password belongs in the app.

## Build on GitHub
1. Upload/extract this project into the repository root.
2. Open **Actions**.
3. Select **Build School Management APK**.
4. Press **Run workflow**.
5. Wait for `flutter analyze`, tests and APK build to finish.
6. Download the artifact `school-management-release-apk`.

The workflow intentionally fails if analysis, tests, or the APK build fails; this prevents a failed build from being presented as a successful release.

## Important
The database migrations must be applied to the new Supabase project before real login/data use. RLS should be tested with separate school accounts before production release.
