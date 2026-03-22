---
title: "FlowState AI — Privacy Policy"
description: "Privacy Policy for FlowState AI"
showDate: false
showReadingTime: false
showTableOfContents: true
---

**Effective date**: March 2026
**Last updated**: March 22, 2026

CodeCompose ("we", "us", or "our") operates the FlowState AI mobile application. This page informs you of our policies regarding the collection, use, and disclosure of personal data when you use our app.

---

## 1. Information we collect

### 1.1 Account information

If you create an account, we collect the following information through Firebase Authentication:

- **Google Sign-In**: email address, display name, profile photo URL
- **Apple Sign-In**: email address, display name

This information is used solely for authentication and syncing your data across devices.

### 1.2 Usage data

We collect usage statistics through Firebase Analytics to improve the app experience, including app version, device type, and feature usage patterns.

Firebase Analytics may use device identifiers and usage data to generate aggregated analytics. You can opt out of analytics data collection through your device settings. We do not use this data for advertising or share it with third parties for marketing purposes.

### 1.3 Device and session data

We store the following data linked to your account in Firebase Firestore:

- **Device information**: device model, OS version, platform, app version, Firebase Installation ID (used to manage up to 10 devices per account)
- **Session data**: focus scores, session duration, interruption count, daily/weekly statistics

### 1.4 Camera and facial data

FlowState AI uses your device's front-facing camera to detect facial presence and estimate focus levels.

**Important**:

- **All facial analysis is performed entirely on your device** using Google ML Kit Face Detection.
- **No images, video frames, or facial data are ever uploaded to any server.**
- **No facial data is stored on your device.** Camera frames are analyzed in real time and immediately discarded.
- We do not use facial recognition (identifying who you are). We only detect facial presence and orientation.

### 1.5 Subscription data

Subscription purchases are processed through Apple App Store and Google Play Store. We use RevenueCat to manage subscription status. We do not have access to your payment details.

---

## 2. How we use your information

- **Authentication**: To sign you in and sync data across your devices.
- **Analytics**: To understand app usage patterns and improve the product.
- **Device management**: To identify devices linked to your account and sync data.
- **Crash reporting**: To diagnose app errors and improve stability (Firebase Crashlytics).
- **Focus measurement**: To provide you with real-time focus scores and reports (processed entirely on-device).

---

## 3. Data storage and security

- Account and session data is stored in Firebase Firestore with security rules that restrict access to the authenticated user only.
- Local data is stored on your device using local storage.
- We use industry-standard encryption for data in transit (TLS) and at rest.

---

## 4. Third-party services

We use the following third-party services:

| Service           | Purpose                                                             | Privacy Policy                                                                     |
| ----------------- | ------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| Firebase (Google) | Authentication, database, analytics, crash reporting, remote config | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| Google ML Kit     | On-device face detection                                            | [developers.google.com/ml-kit](https://developers.google.com/ml-kit/terms)         |
| RevenueCat        | Subscription management                                             | [revenuecat.com/privacy](https://www.revenuecat.com/privacy)                       |

---

## 5. Children's privacy

FlowState AI is not intended for children under 16. We do not knowingly collect personal information from children under 16. If we become aware that we have collected personal information from a child under 16, we will promptly delete that information. If you become aware that a child has provided us with personal data, please contact us.

---

## 6. Data retention and deletion

- Your personal data is retained for as long as your account remains active and as necessary to provide you with our services.
- You can delete your account and all associated data at any time from the app's Settings.
- Upon account deletion, all your data in Firebase Firestore will be permanently removed within 30 days.
- Aggregated, anonymized analytics data that cannot identify you may be retained beyond account deletion for product improvement purposes.
- To request data deletion outside the app, please contact us at [dev@codecompose.net](mailto:dev@codecompose.net).
- Local data is removed when you uninstall the app.

---

## 7. International data transfer

Your data is stored on servers located in Seoul, Republic of Korea, operated through Google Firebase. If you access FlowState AI from outside the Republic of Korea, your data may be transferred to and processed in Korea. Such transfers are protected by Google Firebase's Standard Contractual Clauses (SCCs) and other appropriate safeguards in compliance with applicable data protection laws.

---

## 8. Information for EEA/UK users (GDPR)

If you are located in the European Economic Area (EEA) or the United Kingdom, the following additional provisions apply:

### Legal basis for processing

We process your personal data based on the following legal grounds:

- **Consent**: For optional features such as analytics data collection. You can withdraw consent at any time.
- **Contract performance**: To provide the services you have requested, such as account creation and data synchronization.
- **Legitimate interests**: To improve our app, diagnose errors, and ensure security, where such interests are not overridden by your rights.

### Additional rights

In addition to the rights listed in Section 9, EEA/UK users have the right to:

- **Data portability**: Request a copy of your personal data in a structured, commonly used, machine-readable format.
- **Restriction of processing**: Request that we limit the processing of your data under certain circumstances.
- **Object to processing**: Object to processing based on legitimate interests.
- **Lodge a complaint**: File a complaint with your local Data Protection Authority (DPA).

### Data Protection Contact

For GDPR-related inquiries, please contact us at [dev@codecompose.net](mailto:dev@codecompose.net).

---

## 9. Your rights

You have the right to:

- Access the personal data we hold about you.
- Request correction of inaccurate data.
- Request deletion of your data.
- Withdraw consent for data processing.

---

## 10. Changes to this policy

We may update this privacy policy from time to time. We will notify you of any changes by posting the new policy on this page and updating the "Last updated" date.

---

## 11. Contact us

If you have questions about this privacy policy, please contact us:

- **Email**: [dev@codecompose.net](mailto:dev@codecompose.net)
- **Business**: CodeCompose (코드컴포즈)
- **Address**: 4F #433, 133 Hannaru-ro, Yeonsu-gu, Incheon, Republic of Korea
