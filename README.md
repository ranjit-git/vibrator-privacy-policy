# Privacy Policy for Vibrator Pro

**Effective Date:** July 17, 2026  
**Last updated:** October 12, 2026

## 1. Introduction

Your privacy is important to us. This Privacy Policy explains how "Vibrator Pro" (the "App") collects, uses, and discloses information when you use our mobile application.

The App is designed to provide customizable vibration and haptic sensations. The core haptic features operate locally on your device. To provide and support our services, the App integrates **Google Firebase (Crashlytics & Analytics)** for diagnostics and app improvement, **Google AdMob** for advertising, and **Google Play In-App Billing** for processing in-app purchases.

## 2. Data Collection and Usage

The App does not require user account registration, login, or personal profile creation. We do not collect personally identifiable information (PII) such as your name, email address, physical address, phone number, contacts, photos, audio, or precise GPS location.

### A. Locally Stored Data
The App stores certain user preferences locally on your device using local storage (`SharedPreferences`). This includes:
- Vibration speed preferences and selected pattern.
- Auto-stop timer configurations.
- App UI theme preferences and language selections.
- In-App Purchase status (e.g., whether the "Remove Ads" feature has been unlocked).

This data never leaves your device and is used solely to maintain your settings across app sessions.

### B. Diagnostics and Crash Data (Firebase Crashlytics)
If the App encounters an error or crash, technical diagnostics are automatically collected via **Firebase Crashlytics** to help us identify and resolve issues. This includes:
- Stack traces, error logs, and crash timestamps.
- Device state information at the time of the crash (operating system version, device model, orientation, available memory).

Crash logs are used strictly for bug fixes and stability improvements and are not shared with third-party advertisers.

### C. Usage and Analytics Data (Firebase Analytics)
We use **Firebase Analytics** to understand general app performance and user engagement. This includes:
- Anonymous app interactions (e.g., frequency of pattern usage, taps on the cross-promotion screen).
- General device metrics (device model, OS version, locale, app version).
- Firebase App Instance Identifiers.

### D. Advertising and Device Identifiers (Google AdMob)
Unless you have purchased the "Remove Ads" premium feature, the App uses **Google AdMob** to display advertisements (banner ads, interstitial ads, and app-open ads). AdMob may collect and process:
- **Google Advertising ID (GAID / IDFA):** A unique, resettable advertising identifier assigned to your device.
- **Device Identifiers:** Hardware specifications, network provider, and general IP-derived location (country/city level).
- **Ad Interaction Data:** Information regarding ads served, viewed, or clicked.

This data is used to deliver relevant ads, measure ad performance, prevent ad fraud, and comply with advertising standards.

## 3. Required Device Permissions

The App requests the following permissions to operate:

- **`android.permission.VIBRATE`:** Enables the App to trigger and control the physical vibration motor and haptic feedback engine.
- **`android.permission.WAKE_LOCK`:** Keeps the CPU and screen active while a vibration session is in progress, preventing the operating system from interrupting your selected pattern.
- **`android.permission.INTERNET`:** Enables the App to load advertisements, verify in-app purchases, and transmit crash reports and analytics.
- **`android.permission.ACCESS_NETWORK_STATE`:** Allows the App to verify network connectivity before requesting ads or processing in-app purchases.
- **`com.android.vending.BILLING`:** Allows the App to interface with the Google Play Store billing system for in-app purchases ("Remove Ads").
- **`com.google.android.gms.permission.AD_ID`:** Required on Android 13 (API 33) and above to enable Google AdMob to access the Google Advertising ID for ad personalization, frequency capping, and fraud prevention.

None of these permissions are used to collect personal communications, media files, or confidential personal data.

## 4. In-App Purchases ("Remove Ads")

The App offers an optional, one-time In-App Purchase to permanently remove all advertisements ("Remove Ads"). 

- **Payment Processing:** All transactions are processed directly and securely through Google Play In-App Billing. We do not collect, process, or store your credit card details, bank information, or payment credentials.
- **Ad Disablement:** Once the "Remove Ads" product is purchased or restored, all AdMob ad units and related ad tracking requests are permanently disabled within the App.

## 5. European Economic Area (EEA) & UK Privacy (GDPR Compliance)

If you are located in the European Economic Area (EEA) or the United Kingdom, your data is protected under the General Data Protection Regulation (GDPR) and UK GDPR:

- **User Messaging Platform (UMP):** On your initial launch of the App, Google's UMP consent form is presented. You have the right to grant, manage, or refuse consent for personalized advertising and data processing cookies/identifiers.
- **Legal Basis:** We process analytics and crash reporting on the basis of our legitimate interest in maintaining and improving the App. Advertising identifiers and ad personalization are processed based on your explicit consent where required by law.
- **Revoking or Changing Consent:** In compliance with Google's EU User Consent Policy, European users may change or revoke their consent choices at any time. Simply navigate to **Settings > Legal > Ad Privacy Settings** within the App to re-open the consent management form and adjust your preferences.

## 6. Third-Party Services and Data Sharing

We do not sell your personal data. However, limited technical data and advertising identifiers are shared with third-party service providers as described below:

- **Google Firebase (Crashlytics & Analytics):**  
  Privacy Policy: [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)
- **Google AdMob (Google Mobile Ads):**  
  Privacy Policy: [https://policies.google.com/technologies/ads](https://policies.google.com/technologies/ads)  
  Google Partner Policy: [https://policies.google.com/technologies/partner-sites](https://policies.google.com/technologies/partner-sites)
- **Google Play Billing:**  
  Privacy Policy: [https://policies.google.com/privacy](https://policies.google.com/privacy)

## 7. Data Retention and Deletion

- **Local Data:** App preferences and purchase statuses stored on your device can be removed at any time by clearing the App's data in your device settings or by uninstalling the App.
- **Crash & Analytics Data:** Crash data in Firebase Crashlytics is automatically deleted after 90 days. Analytics data in Firebase Analytics is retained in accordance with Google's default data retention schedule.
- **No User Accounts:** Because the App does not maintain user accounts or collect personal profiles, there is no personal account data stored on our servers to request deletion for.

## 8. Children's Privacy

The App is not directed toward children under 13 years of age (or the minimum age of consent in your jurisdiction). We do not knowingly collect personal identifiable information from children. If you believe that a child has provided us with personal information, please contact us immediately so we can remove it.

## 9. Hardware and Battery Disclaimer

The App operates your device's physical vibration motor (haptic actuator). Continuous or prolonged operation of the vibration motor will consume battery power faster than normal usage and may cause your device to become warm.

To assist with device health and battery preservation, the App includes an Auto-Stop Timer (configured by default to 5 minutes) that will automatically halt the vibration. You acknowledge and agree that you are responsible for monitoring your device's battery and temperature during extended use.

## 10. Changes to This Privacy Policy

We may update this Privacy Policy periodically to reflect changes in our legal obligations, features, or advertising practices. Any updates will be posted with an updated "Last updated" date at the top of this document.

## 11. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy, please contact us at:

- **Developer:** ranjit pahan
- **Email:** [pahan.ranjit.0201@gmail.com](mailto:pahan.ranjit.0201@gmail.com)
