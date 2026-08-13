# Firebase production setup

1. Create a Firebase project named `India Talk`.
2. Add Android app package: `com.indiatalk.app`.
3. Download `google-services.json` and place it at:
   `android/app/google-services.json`
4. Enable Cloud Messaging.
5. Create a service account for the backend and store its credentials in a secret manager.
6. Backend should use Firebase Admin SDK to send push notifications.
7. Never commit `google-services.json` secrets or service-account private keys to public repositories.
8. Configure Play Integrity/App Check where appropriate.

## Notification design
Use data-only or minimal notification payloads. Do not put sensitive message plaintext into FCM payloads if the product promises end-to-end encryption.
