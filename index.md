# Privacy Policy for Tapel

**Last updated:** 14th October 2026

Tapel ("we", "our", "the app") is a padel and tennis scoring app for Apple Watch and iPhone. We respect your privacy and are committed to being transparent about the data we collect, why we collect it, and how it is used.

For any questions about this policy, your data, or to exercise your rights, please contact Ben Pearson at [bpsipandship@gmail.com](mailto:bpsipandship@gmail.com).

## 1. Information We Collect

### 1.1 Account Information

When you sign in using Sign in with Apple, we receive and store:

- **Email address** — provided by Apple (you may choose to use Apple's private relay email)
- **Full name** — only if you choose to share it during sign-in
- **Apple user identifier** — a unique, anonymous ID assigned by Apple for your account

This information is used solely to create and manage your Tapel account.

### 1.2 Profile Information

After signing in, we ask you to complete a profile. The following information is collected and stored:

- **First name and last name**
- **Email address**
- **Date of birth** — used to verify you meet the minimum age requirement (13+) and to understand our user demographics
- **Gender** — optional
- **Local padel club** — free-text entry
- **Home nation** — for UK users only (England, Scotland, Wales, or Northern Ireland)
- **Favourite padel brands** — selected from a predefined list
- **Favourite non-padel brand** — optional free-text entry
- **Matches played per week** — selected from a predefined range

This profile data is stored in our Supabase database and cached locally on your device. It is used to personalise your experience and to help us understand our user base so we can improve Tapel. Brand and frequency data may also be used for aggregated commercial audience insights.

### 1.3 Match Data

Match scores, duration, player names, venue, and related data are recorded on your Apple Watch during gameplay and synced to the iPhone app. This data is stored locally on your device and synced to our Supabase database for your match history.

### 1.4 Health Data

Tapel uses Apple HealthKit on your Apple Watch to record workout sessions during matches. The following HealthKit data is involved:

- **Active energy burned (calories)** — displayed on your match result screen and, if you have connected Strava, included in the Strava activity description
- **Heart rate** — displayed during the match on your Watch screen to track workout intensity; not stored or transmitted outside your device

HealthKit data is never sent to our servers or to any analytics service. HealthKit data is never used for advertising or marketing purposes. Workout sessions are saved to the Health app on your device under Apple's own privacy controls.

### 1.5 Strava (optional)

If you choose to connect your Strava account, the following data is involved:

- **Strava OAuth tokens** (access token, refresh token, token expiry) — stored securely in the device Keychain, not in plain text or on any server
- **Strava athlete name and ID** — stored in the device Keychain to display your connected account
- **Match data shared with Strava** — when auto-publish is enabled, we send your match score, start time, duration, and calorie data to Strava's API to create an activity on your behalf

Connecting to Strava is entirely optional and requires your explicit consent via Strava's OAuth authorisation flow. You can disconnect at any time from your Profile tab, which immediately deletes all stored Strava tokens and athlete information from your device.

### 1.6 Analytics Data

We collect pseudonymous usage analytics using a randomly generated device identifier to understand how the app is used and to improve the experience. This includes:

- App opens, tab views, and feature interactions
- Session duration
- Device model and operating system version
- App version
- Integration events (connect, disconnect, publish)

Analytics data is collected via Mixpanel using a random identifier stored on your device. This identifier does not contain your name, email, or Apple ID. We do not link this identifier to your account or personal information. We do not send health data, names, email addresses, or match opponents to our analytics service.

We also receive aggregated, anonymous data through Apple's App Store analytics (installations, crashes, and performance metrics).

## 2. How We Use Your Information

- **Email address and name:** account creation and identification; future product communications (with your consent)
- **Apple user identifier:** authenticating your account securely
- **Profile information:** personalising your experience; understanding our user demographics and commercial audience insights
- **Date of birth:** age verification (13+ minimum)
- **Match data:** displaying your match history and statistics; publishing to Strava if you have enabled this
- **HealthKit data (calories):** displaying calories on match results; including in Strava activities if connected
- **Strava tokens:** authenticating with Strava on your behalf to publish match activities
- **Analytics data:** monitoring app performance, understanding feature usage, improving the app experience

We do not use your data for advertising, behavioural profiling, or selling to third parties.

## 3. Third-Party Services

We use the following third-party services to operate Tapel:

- **Supabase:** user authentication, account storage, profile storage, and match history. Data shared: email, name, date of birth, gender, club, region, country, brand preferences, matches per week, Apple user ID, match results.
- **Mixpanel:** pseudonymous product analytics. Data shared: random device identifier, device model, OS version, app version, feature interaction events. No names, emails, or health data.
- **Apple (Sign in with Apple):** secure authentication. Data shared: authentication tokens.
- **Apple HealthKit:** recording workout sessions during matches. Data shared: active calories and heart rate (read); workout sessions (written to Health app). Calorie count shared with Strava if connected. Never sent to our servers or analytics.
- **Strava (optional):** publishing match activities to your Strava profile. Data shared: match score, start time, duration, calories.

Each service processes data in accordance with their own privacy policies. The Strava integration is optional and only activated when you explicitly enable it. We do not share your personal data with any other third parties.

## 4. International Data Transfers

Supabase processes data in the EU region. Mixpanel processes analytics data in the EU (api-eu.mixpanel.com). Strava is based in the United States. Where your data is processed outside the United Kingdom, appropriate safeguards are in place in accordance with UK GDPR requirements.

## 5. Data Storage and Security

- Account and profile data is stored securely in Supabase, which uses encryption at rest and in transit.
- Strava tokens are stored in the iOS Keychain on your device, which provides hardware-backed encryption. Strava tokens are never transmitted to our servers.
- Match data is stored locally on your iPhone and synced to our Supabase database. If you have enabled Strava auto-publish, match summary data is also sent directly to Strava's API.
- HealthKit data is managed by Apple's Health app on your device and is subject to Apple's own security and privacy controls.
- Analytics data is processed by Mixpanel and does not contain personally identifiable information.

## 6. Data Retention

- **Account and profile data** is retained for as long as your account exists. You can delete your account at any time (see section 8).
- **Match data** stored on your device is removed when you delete the app. Match data stored in our database is retained for as long as your account exists and deleted when you delete your account.
- **Strava tokens** are stored on your device only. Disconnecting Strava in the app or deleting the app removes this data immediately.
- **Analytics data** is retained by Mixpanel in accordance with their data retention policies.

## 7. Your Rights (UK GDPR)

If you are located in the United Kingdom or the European Economic Area, you have the following rights regarding your personal data:

- **Right of access** — request a copy of the data we hold about you
- **Right to rectification** — request correction of inaccurate data
- **Right to erasure** — request deletion of your account and associated data
- **Right to data portability** — receive your data in a machine-readable format
- **Right to restrict processing** — request that we limit how we process your data in certain circumstances
- **Right to object** — object to processing of your data for specific purposes
- **Right to withdraw consent** — withdraw consent at any time where processing is based on consent (including Strava and analytics)
- **Right to complain** — you have the right to lodge a complaint with the Information Commissioner's Office (ICO) at [ico.org.uk](https://ico.org.uk) if you believe your data has been handled unlawfully

To exercise any of these rights, please contact us at [bpsipandship@gmail.com](mailto:bpsipandship@gmail.com). We will respond within 30 days.

We process your personal data on the following legal bases:

- **Contract:** to provide and maintain your Tapel account, store your match history, and sync data between your devices
- **Consent:** to connect and publish to Strava, to send marketing communications, and to collect usage analytics. You can withdraw consent at any time from your Profile tab
- **Legitimate interests:** to maintain the security and functionality of the app

## 8. Account Deletion

You can request account deletion by emailing [bpsipandship@gmail.com](mailto:bpsipandship@gmail.com).

## 9. Marketing Communications

We do not currently send marketing emails. In the future, we may use your email address to send product updates or new feature announcements. If we do, you will always be able to opt out, and we will never send marketing without your prior consent where required by law. You can control your marketing preference from your Profile tab at any time.

## 10. Children's Privacy

Tapel is not directed at children under the age of 13. We do not knowingly collect personal information from children under 13. We enforce a minimum age of 13 during profile creation via a date of birth check. If you believe a child under 13 has provided us with personal data, please contact us and we will delete it promptly.

## 11. Changes to This Policy

We may update this privacy policy from time to time. Any changes will be posted on this page with an updated "Last updated" date. We encourage you to review this page periodically.

## 12. Contact Us

If you have any questions about this privacy policy, your data, or wish to exercise your rights, please contact:

**Ben Pearson**
[bpsipandship@gmail.com](mailto:bpsipandship@gmail.com)

---

*© 2026 Benjamin Pearson. All rights reserved.*
