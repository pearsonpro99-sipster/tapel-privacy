# Privacy Policy for Tapel

**Last updated: May 27, 2026**

Tapel ("we", "our", "the app") is a padel and tennis scoring app for Apple Watch and iPhone. We respect your privacy and are committed to being transparent about the data we collect, why we collect it, and how it is used.

---

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
- **Local padel club** — free-text entry
- **Favourite padel brands** — selected from a predefined list
- **Matches played per week** — selected from a predefined range

This profile data is stored in our Supabase database and cached locally on your device. It is used to personalise your experience and to help us understand our user base so we can improve Tapel.

### 1.3 Match Data

Match scores, duration, calories, and related data are recorded on your Apple Watch during gameplay and synced to the iPhone app. This data is stored locally on your device.

### 1.4 Third-Party Integration Data (Strava)

If you choose to connect your Strava account, the following data is involved:

- **Strava OAuth tokens** (access token, refresh token, token expiry) — stored securely in the device Keychain, not in plain text or on any server
- **Strava athlete name and ID** — stored in the device Keychain to display your connected account
- **Match data shared with Strava** — when auto-publish is enabled, we send your match score, start time, duration, and calorie data to Strava's API to create an activity on your behalf

Connecting to Strava is entirely optional and requires your explicit consent via Strava's OAuth authorization flow. You can disconnect at any time from Settings, which immediately deletes all stored Strava tokens and athlete information from your device.

### 1.5 Analytics Data

We collect anonymous, non-personally-identifiable usage analytics to understand how the app is used and to improve the experience. This includes:

- App opens, tab views, and feature interactions
- Session duration
- Device model and operating system version
- App version
- Strava integration events (connect, disconnect, publish — no personal data is included)

Analytics data is collected via Mixpanel and cannot be used to identify you personally. We also receive aggregated, anonymous data through Apple's App Store analytics (installations, crashes, and performance metrics).

---

## 2. How We Use Your Information

| Data | Purpose |
|------|---------|
| Email address & name | Account creation and identification; future product communications (with your consent) |
| Apple user identifier | Authenticating your account securely |
| Profile information | Personalising your experience; understanding our user demographics to improve the app |
| Match data | Displaying your match history and statistics within the app; publishing to Strava if you have enabled this |
| Strava tokens | Authenticating with Strava on your behalf to publish match activities |
| Analytics data | Monitoring app performance, understanding feature usage, improving the app experience |

We do not use your data for advertising, behavioural profiling, or selling to third parties.

---

## 3. Third-Party Services

We use the following third-party services to operate Tapel:

| Service | Purpose | Data Shared |
|---------|---------|-------------|
| Supabase | User authentication, account storage, and profile storage | Email, name, date of birth, club, brand preferences, matches per week, Apple user ID |
| Mixpanel | Anonymous product analytics | Anonymous device and usage events (no personal data) |
| Apple (Sign in with Apple) | Secure authentication | Authentication tokens |
| Strava (optional) | Publishing match activities to your Strava profile | Match score, start time, duration, calories |

Each service processes data in accordance with their own privacy policies. Strava integration is optional and only activated when you explicitly connect your account. We do not share your personal data with any other third parties.

---

## 4. Data Storage and Security

- **Account and profile data** (email, name, date of birth, preferences) is stored securely in Supabase, which uses encryption at rest and in transit.
- **Strava tokens** are stored in the iOS Keychain on your device, which provides hardware-backed encryption. Strava tokens are never transmitted to our servers.
- **Match data** is stored locally on your iPhone and is not transmitted to any server unless you have enabled Strava auto-publish, in which case match summary data is sent directly to Strava's API.
- **Analytics data** is processed by Mixpanel and does not contain personally identifiable information.

---

## 5. Data Retention

- **Account and profile data** is retained for as long as your account exists. If you request deletion, we will remove your data within 30 days.
- **Match data** is stored on your device only. Deleting the app removes this data.
- **Strava tokens** are stored on your device only. Disconnecting Strava in the app or deleting the app removes this data immediately.
- **Analytics data** is retained by Mixpanel in accordance with their data retention policies.

---

## 6. Your Rights (GDPR & UK GDPR)

If you are located in the European Economic Area (EEA) or the United Kingdom, you have the following rights regarding your personal data:

- **Right of access** — request a copy of the data we hold about you
- **Right to rectification** — request correction of inaccurate data
- **Right to erasure** — request deletion of your account and associated data
- **Right to data portability** — receive your data in a machine-readable format
- **Right to object** — object to processing of your data for specific purposes
- **Right to withdraw consent** — withdraw consent at any time where processing is based on consent

To exercise any of these rights, please contact us at [bpsipandship@gmail.com](mailto:bpsipandship@gmail.com). We will respond within 30 days.

---

## 7. Marketing Communications

We do not currently send marketing emails. In the future, we may use your email address to send product updates or new feature announcements. If we do, you will always be able to opt out, and we will never send marketing without your prior consent where required by law.

---

## 8. Children's Privacy

Tapel is not directed at children under the age of 13. We do not knowingly collect personal information from children under 13. We enforce a minimum age of 13 during profile creation via a date of birth check. If you believe a child has provided us with personal data, please contact us and we will delete it promptly.

---

## 9. Changes to This Policy

We may update this privacy policy from time to time. Any changes will be posted on this page with an updated "Last updated" date. We encourage you to review this page periodically.

---

## 10. Contact Us

If you have any questions about this privacy policy, your data, or wish to exercise your rights, please contact:

📧 [bpsipandship@gmail.com](mailto:bpsipandship@gmail.com)
