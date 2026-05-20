# Privacy Policy for AR Clean

**Last Updated: May 20, 2024**

AR Clean ("the App") is developed and operated by **ARH Community** ("we", "us", or "our"). We are committed to protecting your privacy and ensuring transparency regarding how the App works, particularly regarding sensitive Android permissions required for its core functionality as a utility and security tool.

By using AR Clean, you agree to the practices described in this Privacy Policy.

---

## 1. Information & Source Code
AR Clean adalah aplikasi utilitas sumber terbuka (open-source) yang dirancang untuk mengoptimalkan kinerja perangkat.

*   **Repository GitHub:** [https://github.com/1renwart1-byte/AR-Clean](https://github.com/1renwart1-byte/AR-Clean)
*   **Lisensi:** Kode sumber tersedia di bawah lisensi yang tercantum dalam repositori tersebut.

## 2. Important Disclosures & Compliance

AR Clean is a utility application designed to optimize device performance, manage storage, and improve battery life. To provide these services, we require access to specific sensitive data and device permissions.

**Our Commitment to You:**
*   **No Selling of Data:** We do **not** sell, rent, or trade your personal information or files to third parties for marketing purposes.
*   **Data Encryption:** All data transmitted (such as account credentials) is secured using industry-standard HTTPS/TLS encryption.
*   **Local-First Processing:** Scanning for junk files, large files, and duplicates happens strictly on your device. We do not upload your personal files to our servers.

---

## 3. Information We Collect

### A. Personal Information (Account Services)
When you sign in using your Google account (via Firebase Auth), we collect:
*   **Name and Email Address:** To create and manage your user account.
*   **Profile Information:** To sync your Premium subscription status across multiple devices.
*   **User Identifier:** A unique ID to manage your app preferences and settings.

### B. Financial Information (Purchases)
Through the Google Play Billing system, we receive:
*   **Transaction Details:** Order ID, purchase time, and subscription status to verify Premium features.
*   **Note:** We do **not** collect or store your credit card numbers, bank details, or billing address. All payments are processed securely by Google Play.

### C. Device & Technical Data
For analytics, stability, and security monitoring (via Firebase), we collect:
*   **Device Attributes:** Model, manufacturer, Android OS version, and system language.
*   **App Performance:** Crash logs, ANR (App Not Responding) reports, and performance metrics via Firebase Crashlytics.
*   **Identifiers:** Google Advertising ID (GAID) for advertising and attribution purposes. You can manage or reset this in your Android "Ads" settings.

---

## 4. Sensitive Permissions & Data Usage

To fulfill its purpose as a system cleaner and optimizer, AR Clean requires several high-priority permissions. We use these strictly for core features:

### A. All Files Access (`MANAGE_EXTERNAL_STORAGE`)
*   **Purpose:** Essential for the **Deep Clean** and **Junk Cleaner** features. It allows the App to scan the entire storage to find hidden cache files, obsolete APKs, and temporary system data that consume space.
*   **Protection:** The App only reads metadata to identify junk. It **never** accesses, reads, or uploads your personal photos, videos, or private documents to any external server.

### B. Media Permissions (Android 13+)
*   **Permissions:** `READ_MEDIA_IMAGES`, `READ_MEDIA_VIDEO`, `READ_MEDIA_AUDIO`.
*   **Purpose:** Allows the App to categorize and help you manage large media files and duplicate photos on newer Android versions.

### C. Package Visibility, Usage & System Optimization (`QUERY_ALL_PACKAGES`, `PACKAGE_USAGE_STATS` & `REQUEST_IGNORE_BATTERY_OPTIMIZATIONS`)
*   **Purpose:** 
    *   `QUERY_ALL_PACKAGES`: Used by the **App Manager** to list installed apps and detect potentially harmful or high-risk applications.
    *   `PACKAGE_USAGE_STATS`: Used by the **Boost Speed** feature to identify background apps consuming excessive RAM or battery.
    *   `REQUEST_IGNORE_BATTERY_OPTIMIZATIONS`: Used to ensure that critical cleaning or backup tasks are not killed by the system's aggressive battery saving modes.
*   **Data Handling:** This information is processed in real-time on your device and is not stored permanently or shared.

### D. Foreground Service (`FOREGROUND_SERVICE_DATA_SYNC`)
*   **Purpose:** Ensures that long-running tasks like deep system scanning or large file analysis are completed successfully even if you switch apps.

---

## 5. Third-Party Service Providers

We use trusted third-party services to enhance app functionality and show advertisements:
*   [Google Play Services](https://www.google.com/policies/privacy/)
*   [AdMob (Google Ads)](https://support.google.com/admob/answer/6128543?hl=en)
*   [Firebase Analytics & Crashlytics](https://firebase.google.com/support/privacy)
*   [Google Play Billing](https://payments.google.com/payments/apis-secure/u/0/get_legal_document?ldo=0&ldt=buyertos&ldc=ID)

---

## 6. Data Retention & Deletion Rights

*   **Retention:** We retain account-related data (Email/ID) only as long as your account exists to maintain your Premium status.
*   **Data Deletion:** You have the right to request the deletion of your account and all associated data.
    *   **In-App:** Go to Settings > Delete Account.
    *   **Web/Email:** Send a deletion request to **[1renwart1@gmail.com](mailto:1renwart1@gmail.com)**. We will process your request within 48 hours.
*   **Local Data:** Uninstalling the app or clearing app data will immediately remove all locally stored analysis and cache.

---

## 7. Security
We value your trust in providing us your personal information, thus we are striving to use commercially acceptable means of protecting it. But remember that no method of transmission over the internet, or method of electronic storage is 100% secure and reliable.

---

## 8. Children's Privacy
AR Clean does not address anyone under the age of 13. We do not knowingly collect personally identifiable information from children under 13. If we discover that a child under 13 has provided us with personal information, we immediately delete this from our servers.

---

## 9. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Last Updated" date. You are advised to review this page periodically for any changes.

---

## 10. Contact Us
If you have any questions or suggestions about our Privacy Policy, do not hesitate to contact us:

*   **Developer:** ARH Community
*   **GitHub Repository:** [1renwart1-byte/AR-Clean](https://github.com/1renwart1-byte/AR-Clean)
*   **Email:** [1renwart1@gmail.com](mailto:1renwart1@gmail.com)
*   **Address:** Jakarta, Indonesia
