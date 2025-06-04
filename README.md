
# Emotion Assistant – Deployment Instructions

## Firebase Cloud Functions Deployment

1. Navigate to `functions` directory.
2. Run `npm install firebase-admin firebase-functions`
3. Deploy with Firebase CLI:
   firebase deploy --only functions

## Flutter Integration

- Use `api_service.dart` for connecting to Firebase endpoints.
- Adjust `baseUrl` if deploying to production.

## Emulator Setup (Optional)

Use `firebase emulators:start` to run locally.
