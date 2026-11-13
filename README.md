# Privacy Policy for Vibrator Pro

**Effective Date:** July 9, 2026  
**Last Updated:** November 14, 2026

## 1. Introduction

Your privacy is important to us. This Privacy Policy explains how **Vibrator Pro** (the "App"), developed by **ranjit pahan** ("we", "us", or "our"), handles information when you use our mobile application across supported platforms (Android and iOS).

The App is designed to provide customizable vibration patterns, massage rhythms, and haptic feedback. While all haptic sensations and pattern algorithms execute strictly locally on your device, the App integrates industry-standard third-party services—including **Google AdMob**, **Google Firebase** (Analytics, Crashlytics, and Remote Config), and **Google Play / Apple App Store In-App Billing**—to serve advertisements, monitor app stability, deliver dynamic updates, and process optional in-app purchases.

---

## 2. Information Collection and Usage

We do not require user account registration, login credentials, or personal profile creation. We do not collect or store personally identifiable information (PII) such as your name, physical address, email address, phone number, contacts, microphone audio, camera captures, or precise GPS location.

### A. Locally Stored Data
The App stores user preferences locally on your device using platform-native storage (`SharedPreferences` on Android, `UserDefaults` on iOS). This data remains exclusively on your device and includes:
- Vibration speed preferences, intensity levels, and selected patterns.
- Auto-stop timer duration configurations.
- App UI theme selection (Dark, Light, AMOLED) and language preferences.
- Session counters used to determine in-app review prompts and update dialogs.
- In-App Purchase state (e.g., whether permanent "Remove Ads" is active) and temporary ad-free reward expiration timestamps.

### B. Diagnostics and Crash Reporting (Firebase Crashlytics)
To maintain stability and promptly resolve bugs, technical diagnostic data is automatically collected via **Firebase Crashlytics** when an unexpected error or crash occurs:
- Stack traces, error logs, and exception details.
- Device state metrics at the time of an event (operating system version, device model, screen orientation, free RAM, and storage space).
- Crash diagnostics are retained for 90 days by Firebase and are used strictly for technical debugging and quality assurance.

### C. Usage and Product Analytics (Firebase Analytics & Remote Config)
We use **Firebase Analytics** and **Firebase Remote Config** to assess app performance, optimize feature delivery, and fetch dynamic app settings:
- Aggregated, non-personally identifiable app interactions (e.g., pattern selection frequency, screen navigation events, session duration).
- Device specifications (device model, OS version, locale/language, app build number).
- Firebase App Instance Identifiers.
- Dynamic feature toggles, ad frequency thresholds, and version update checks fetched securely over HTTPS.

### D. Advertising and Device Identifiers (Google AdMob)
Unless you have activated an ad-free tier (via the "Remove Ads" in-app purchase or by unlocking temporary ad-free access through a rewarded ad), the App displays advertisements provided by **Google AdMob** (banner ads, interstitial ads, app open ads, and rewarded video ads).

Google AdMob may collect and process:
- **Mobile Advertising Identifiers:** Google Advertising ID (GAID on Android) or Identifier for Advertisers (IDFA on iOS).
- **Device & Technical Identifiers:** IP address (used for approximate coarse location at country/city level), cellular carrier, and device hardware characteristics.
- **Ad Performance Metrics:** Ads served, viewed, clicked, and user engagement frequency.

This data is used to serve contextual or personalized advertisements, measure ad performance, prevent fraudulent clicks, and enforce ad frequency caps.

---

## 3. Required Device Permissions

The App requests only the device permissions strictly necessary for its features:

- **Vibration & Haptics Control (`android.permission.VIBRATE` / iOS `Core Haptics`):**
  - Enables the App to trigger and control the physical vibration actuator and haptic engine to deliver selected patterns.
- **Wakelock (`android.permission.WAKE_LOCK`):**
  - Keeps the processor and screen active during active vibration sessions, preventing the operating system from suspending the vibration engine while a pattern is running.
- **Network Access (`android.permission.INTERNET` & `android.permission.ACCESS_NETWORK_STATE`):**
  - Allows the App to verify network connectivity, fetch Remote Config settings, transmit crash logs, load advertisements, and validate in-app purchases.
- **In-App Billing (`com.android.vending.BILLING` / StoreKit):**
  - Facilitates communication with the Google Play Store or Apple App Store billing systems for processing purchases.
- **Advertising ID (`com.google.android.gms.permission.AD_ID`):**
  - Required on Android 13+ (API 33+) to allow Google AdMob to access the Google Advertising ID for ad frequency capping, fraud prevention, and compliant ad delivery.

The App does **not** request or access camera, microphone, contacts, SMS, phone call records, background location, or external media files.

---

## 4. In-App Purchases and Rewarded Access

The App offers options to enjoy an ad-free experience:

1. **Permanent "Remove Ads" Purchase:**
   - Available as a one-time In-App Purchase.
   - **Payment Security:** All transactions are securely processed by the Google Play Store (Google Play Billing) or Apple App Store (StoreKit). We never receive, process, or store credit card numbers, banking details, or billing addresses.
   - Once purchased, all advertising requests (banners, interstitials, and app open ads) are permanently disabled.
2. **Temporary Rewarded Access:**
   - Users may choose to watch a rewarded video ad to receive a temporary ad-free pass (e.g., 2 hours). No financial transaction or payment data is collected during this process.

---

## 5. European Economic Area (EEA), UK, and Switzerland (GDPR Compliance)

If you reside in the EEA, United Kingdom, or Switzerland, your data protection rights are governed by the General Data Protection Regulation (GDPR) and UK GDPR:

- **User Messaging Platform (UMP) Consent:** On your initial app launch, a Google-certified Consent Management Platform (CMP) dialog is displayed. You have the right to grant, customize, or decline consent for personalized advertising, device identifiers, and vendor processing.
- **Legal Grounds for Processing:** We process crash and analytical diagnostics under the legal basis of legitimate interest to ensure app reliability. Advertising identifiers and personalized ad delivery are processed solely upon your explicit consent where mandated by law.
- **Revoking or Modifying Consent:** You can review or change your privacy and ad consent preferences at any time directly within the App by navigating to **Settings > Legal > Ad Privacy Settings**.

---

## 6. United States State Privacy Laws (CCPA / CPRA)

For residents of California and other US states with applicable consumer privacy laws:
- We do not sell your personal information for monetary consideration.
- Device identifiers processed for cross-context behavioral advertising by third-party ad networks can be managed or opted out of via the in-app consent preferences (**Settings > Legal > Ad Privacy Settings**) or through your operating system's global ad tracking settings (*Settings > Google > Ads > Delete advertising ID* on Android).

---

## 7. Third-Party Services and Privacy Policies

We partner with reputable third-party providers that adhere to international privacy standards. We encourage you to review their respective privacy practices:

- **Google AdMob & Google Mobile Ads SDK:**  
  [https://policies.google.com/technologies/ads](https://policies.google.com/technologies/ads)  
  [https://policies.google.com/technologies/partner-sites](https://policies.google.com/technologies/partner-sites)
- **Google Firebase (Crashlytics, Analytics, Remote Config):**  
  [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)
- **Google Play Services & Google Play Billing:**  
  [https://policies.google.com/privacy](https://policies.google.com/privacy)
- **Apple Privacy Policy (iOS):**  
  [https://www.apple.com/legal/privacy/](https://www.apple.com/legal/privacy/)

---

## 8. Data Retention and User Deletion Rights

- **Local Storage:** All app preferences, vibration history, and purchase flags stored on your device can be completely erased at any time by clearing the App's storage/cache in your device settings or by uninstalling the App.
- **Crash Reports & Analytics:** Data stored in Firebase Crashlytics is automatically purged after 90 days. Firebase Analytics data is retained according to Google's standard retention schedules.
- **No Remote User Accounts:** Because the App does not maintain user account databases, we do not store personal profiles or login records on any remote server.

---

## 9. Children's Privacy

The App is designed and marketed for a general audience and is not directed at children under the age of 13 (or under 16 in the EEA). We do not knowingly collect personal identifiable information from children. If you believe that a minor has provided information through our third-party services without parental consent, please contact us so we can take immediate corrective measures.

---

## 10. Hardware and Device Health Disclaimer

The App operates the device's physical haptic vibration motor at various frequencies and intensities. Continuous and prolonged usage will consume battery power and may cause the device to warm up.

- **Auto-Stop Safety Timer:** The App includes a configurable Auto-Stop Timer (set by default to 5 minutes) designed to preserve battery and prevent motor strain.
- Users are advised to monitor device temperature and avoid continuous, unattended operation on soft or heat-insulating surfaces.

---

## 11. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect operational, legal, or regulatory requirements. Any modifications will be posted within the App and updated at our official privacy policy URL ([https://ranjit-git.github.io/vibrator-privacy-policy/](https://ranjit-git.github.io/vibrator-privacy-policy/)) with a revised "Last Updated" date. Continued use of the App following any changes indicates acceptance of the updated policy.

---

## 12. Contact Us

If you have any questions, concerns, or inquiries regarding this Privacy Policy or our data practices, please contact:

- **Developer:** ranjit pahan  
- **Email:** [pahan.ranjit.0201@gmail.com](mailto:pahan.ranjit.0201@gmail.com)  
- **Privacy Policy URL:** [https://ranjit-git.github.io/vibrator-privacy-policy/](https://ranjit-git.github.io/vibrator-privacy-policy/)
