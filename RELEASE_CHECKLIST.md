# India Talk final release checklist

## Accounts & infrastructure
- [ ] Google Play Console developer account
- [ ] Firebase project
- [ ] SMS/OTP provider
- [ ] Production API domain + HTTPS
- [ ] Managed PostgreSQL
- [ ] S3-compatible media storage + CDN
- [ ] FCM service account in secret manager
- [ ] TURN server for calls
- [ ] Monitoring/error tracking
- [ ] Automated database backups

## Backend
- [ ] Set production environment variables
- [ ] Run Prisma migrations
- [ ] Replace OTP placeholder endpoints with real provider
- [ ] Connect Firebase Admin/FCM
- [ ] Connect media presigned URLs
- [ ] Implement conversation membership authorization
- [ ] Implement group roles
- [ ] Implement call state + WebRTC signaling
- [ ] Add Redis if scaling Socket.IO horizontally
- [ ] Rate limits and abuse protection
- [ ] Security review
- [ ] Load testing

## Android
- [ ] Add `google-services.json`
- [ ] Set production API URL
- [ ] Implement FCM token registration
- [ ] Implement chat UI + offline cache
- [ ] Implement media permissions/uploads
- [ ] Implement WebRTC call UI
- [ ] Configure release signing
- [ ] Test Android 7+ and current Android versions
- [ ] Test slow/offline networks
- [ ] Crash-free smoke test

## Privacy & Play Store
- [ ] Privacy policy URL
- [ ] Terms of service
- [ ] Data deletion/account deletion flow
- [ ] Data Safety form
- [ ] Content rating
- [ ] App access instructions if required
- [ ] Store icon
- [ ] Feature graphic
- [ ] Screenshots
- [ ] App description
- [ ] Target API compliance
- [ ] Closed testing
- [ ] Production AAB upload
- [ ] Staged rollout

## Security
- [ ] HTTPS/WSS only
- [ ] No secrets in Git
- [ ] Strong JWT/refresh-token design
- [ ] OTP anti-abuse controls
- [ ] File type/size validation
- [ ] Malware scanning for uploads
- [ ] Backups tested
- [ ] Incident response plan
- [ ] E2EE protocol reviewed by a cryptography/security professional before claiming E2EE
