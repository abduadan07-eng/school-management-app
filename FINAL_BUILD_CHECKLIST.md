# Final Build Checklist

Automated by GitHub Actions:
- Flutter project structure check
- Android project generation
- Dependency resolution
- `flutter analyze`
- `flutter test`
- Release APK build

Manual before production:
- Apply Supabase migrations
- Confirm Super Admin UID is in `platform_admins`
- Test Super Admin login
- Create a test School A and School B
- Verify cross-school RLS isolation
- Test School Admin / Teacher / Student / Parent login flows
- Test offline/sync behavior where implemented
- Test Storage policies if private documents are enabled

Never add a Supabase service-role key or database password to Flutter.
