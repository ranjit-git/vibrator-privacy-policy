# Privacy Policy for Vibrator Pro

**Effective Date:** July 17, 2026  
**Last updated:** September 3, 2026

## 1. Introduction

Your privacy is important. This Privacy Policy explains how "Vibrator Pro" (the "App") handles information.

The App is designed to operate primarily offline and locally on your device. However, the App uses **Firebase Crashlytics** and **Firebase Analytics** for crash reporting, diagnostics, and basic usage tracking. This means limited, anonymous technical information related to app crashes and feature usage is collected and transmitted to help improve app stability and user experience.

## 2. Data Collection and Usage

The App does not require you to create an account and is not designed to collect personal identifiable information (PII) such as your name, email address, contacts, photos, messages, or precise location through its core features.

### Local Data
The App stores certain preferences locally on your device, such as your selected vibration speed, chosen pattern, auto-stop timer, and UI theme. This locally stored data is used exclusively to remember your settings and support app functionality. 

### Analytics and Diagnostics
The App uses **Firebase Crashlytics** and **Firebase Analytics** to collect limited technical and diagnostic information. This includes:
- **Crash Data:** Crash logs, stack traces, and related diagnostic data if the App crashes or encounters errors.
- **Usage Data:** Anonymous event logs (such as clicks on the "More Apps" cross-promotion screen) to understand which features are most useful to users.
- **Device Information:** Device model, operating system version, and app version.

## 3. Required Device Permissions

To function properly, the App requires the following device capabilities:

- **Vibration / Haptics Control**
  - On Android, the App requests the `android.permission.VIBRATE` permission.
  - On iOS, the App uses the `Core Haptics` engine.
  - **Purpose:** These are used exclusively to trigger the device's physical vibration or haptic engine to deliver the patterns you select.

- **Wakelock (Keep Screen On)**
  - The App uses standard operating system wakelocks to help prevent the screen from turning off while a haptic pattern is actively running.
  - **Purpose:** This ensures the haptic session runs continuously as intended without being put to sleep by the operating system.

These permissions and capabilities are never used to track you.

## 4. Third-Party Services

The App uses services provided by **Google LLC** to monitor app health and usage:
- **Firebase Crashlytics:** For crash reporting and stability monitoring.
- **Firebase Analytics:** For measuring anonymous user interactions and app engagement.

More information about Firebase privacy and security is available here:  
[https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

## 5. Data Sharing

The App does not sell your personal data and does not share personal information for advertising or marketing purposes. 

Anonymous usage data, crash-related technical data, and diagnostic information are processed by Google's Firebase services as part of the analytics and crash reporting infrastructure used by the App.

## 6. Data Storage and Deletion

- **Local Storage:** Your app preferences (vibration settings, timers, themes) are stored locally on your device. You can delete this data at any time by clearing the App's storage/cache in your device settings or by uninstalling the App.
- **Remote Storage:** Crash and analytics information collected through Firebase may be transmitted to and stored on Google's servers. Because the App does not collect personally identifiable information or require user accounts, there is no personal account data to request deletion for.

## 7. Children's Privacy

The App is not directed to children under the age required by applicable law for independent consent in their jurisdiction. The App does not knowingly collect personal information from children.

## 8. Changes to This Privacy Policy

This Privacy Policy may be updated from time to time. Any changes will be reflected in a revised version of this policy with an updated effective date or last updated date.

## 9. Contact Us

If you have any questions or suggestions about this Privacy Policy, please contact the developer at:  
[pahan.ranjit.0201@gmail.com](mailto:pahan.ranjit.0201@gmail.com)

## 10. Disclaimer (Battery and Hardware Usage)

The App utilizes your device's physical vibration motor (haptic engine). Continuous or prolonged use of the vibration motor can consume battery power significantly faster than normal device usage and may cause the device to become warm. 

To help preserve device health and battery life, the App includes a default Auto-Stop Timer (set to 5 minutes) which will automatically halt the vibration. By using the App, you acknowledge and accept that you are responsible for monitoring your device's battery and temperature levels during prolonged use.
