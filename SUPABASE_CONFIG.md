# Supabase configuration

Project URL (the URL Flutter uses):
`https://syspfaiggqoopcyrxqvg.supabase.co`

JWKS URL (authentication verification endpoint; do NOT use as the Flutter project URL):
`https://syspfaiggqoopcyrxqvg.supabase.co/auth/v1/.well-known/jwks.json`

REST API endpoint (for REST requests only):
`https://syspfaiggqoopcyrxqvg.supabase.co/rest/v1/`

The app uses the Project URL with `Supabase.initialize()`.
The JWKS URL is not used as the app's Supabase URL.

The supplied key is a Supabase publishable key and is used as the client key. Never put a Supabase secret/service-role key in Flutter.
