# Privacy Policy for MemoryAI

**Effective Date: 2026-03-10**
**Last Updated: 2026-03-17**

Thank you for using MemoryAI! This Privacy Policy explains how we handle your information when you use our mobile application. Your privacy is our top priority, and we are committed to protecting it. This policy is compliant with the General Data Protection Regulation (GDPR) and applicable Italian data protection laws.

This policy is available in [English](index.md) and [Italian](privacy-policy-it.md).

---

## The TL;DR

MemoryAI is a private, offline-first application. All your data — including notes, voice recordings, images, and AI interactions — is stored locally on your device by default. **We have no backend infrastructure that receives your information.** The app's network activity is limited to downloading AI model files from third-party repositories (e.g., HuggingFace) and, if you choose to enable it, backing up your data to your personal cloud storage (Google Drive on Android, iCloud on iOS).

---

## 1. Data Controller

The data controller for the MemoryAI app is:

**MemoryAI Development Team**
Email: alessandro.facchini@facchinits.it

If you are located in the European Union, you may also contact your local data protection supervisory authority. For users in Italy, this is the **Garante per la protezione dei dati personali** ([www.garanteprivacy.it](https://www.garanteprivacy.it)).

---

## 2. Legal Basis for Processing

We process your data based on the following legal grounds under GDPR Article 6:

- **Your Consent (Art. 6(1)(a)):** When you use our app and grant device permissions (microphone, camera, storage), you consent to the local processing of your data as described in this policy. If you choose to enable the cloud backup feature, you explicitly consent to your data being uploaded to your personal cloud storage account.
- **Contractual Necessity (Art. 6(1)(b)):** The processing is necessary to provide the app's core features, such as RAG, local AI model interactions, and voice transcription.

---

## 3. Information We Process

MemoryAI does **not** collect, transmit, or store any of your personal data or user-created content on **our** servers. All data you create and use within the app is processed and stored **on your device** by default. This includes:

- **Text and Document Inputs:** Any text you type or documents you import for the RAG (Retrieval-Augmented Generation) functionality.
- **Voice Inputs:** Voice recordings you create for transcription or to interact with the AI. These are processed entirely on-device.
- **Image Inputs:** Images you select from your device for text recognition or to be included in your notes.
- **AI Model Interactions:** Your conversations and interactions with the local large language models (LLMs), which run entirely on your device.
- **LoRA Adapter Files:** Custom LoRA adapter files (e.g., .gguf format) that you import into the app's local storage to customize AI model behavior.
- **Backup Data:** If you enable the cloud backup feature, the app creates a copy of your data and uploads it to your personal cloud storage account (Google Drive on Android, iCloud on iOS). See Section 5 for details.
- **App Preferences:** Settings and preferences you configure within the app (e.g., language selection, theme).

**We do not collect analytics, telemetry, or any form of anonymous usage data.** No user-created content is sent to any server owned or operated by MemoryAI. Data only leaves your device if you explicitly choose to back up to your personal cloud storage or share content via the Share feature (see Section 5).

---

## 4. Device Permissions

To provide its core features, MemoryAI may request the following device permissions:

| Permission | Purpose |
|---|---|
| **Microphone** | To record voice inputs for transcription and AI interactions. |
| **Camera** | To capture images for text recognition and note-taking. |
| **Storage / Photos** | To access images from your gallery, to import LoRA adapter files, and to store app data locally. |
| **Network / Internet** | To download AI model files from third-party repositories (e.g., HuggingFace) and, if enabled, to back up and restore your data via cloud storage. No data is sent to MemoryAI servers. |
| **Google Account (Android)** | Required only if you enable the Google Drive backup feature. Used to authenticate with your Google account and access your Google Drive storage. |

You can revoke any of these permissions at any time through your device's system settings. Revoking a permission may disable the corresponding feature but will not affect the rest of the app.

---

## 5. How We Use Your Information

All processing of your information happens **locally on your device**. We use the data you provide to:

- Enable the core features of the app, such as note-taking, RAG, and interacting with local AI models.
- Transcribe your voice recordings on-device.
- Recognize and extract text from your images on-device.

Since we have no access to your data, we do not and cannot use it for advertising, profiling, analytics, or any other purpose beyond providing the app's functionality to you.

### Cloud Backup and Restore

MemoryAI offers an **optional** cloud backup and restore feature to help you safeguard your data or transfer it between devices:

- **On Android**, your data is backed up to your personal **Google Drive** account.
- **On iOS**, your data is backed up to your personal **iCloud** account.

This feature is **not enabled by default** — you must explicitly choose to create a backup or restore from one. When you initiate a backup, a copy of your app data (notes, conversations, preferences, and related content) is uploaded to your personal cloud storage account. MemoryAI does not have access to your cloud storage account and cannot read, modify, or delete your backups. Your backed-up data is subject to the privacy policies and security practices of Google or Apple, respectively.

You can delete your cloud backups at any time through Google Drive or iCloud directly.

### Sharing and Exporting

When you use the **Share/Export feature**, your conversation data is passed to your device's native share functionality (via the operating system's share sheet). From there, the data may be sent to other apps or services that you choose. MemoryAI has no control over how those third-party apps handle your data.

---

## 6. Data Storage and Security

All your data is stored in a local database on your device by default. It is not encrypted by the app by default, but it benefits from your device's built-in security features (e.g., device encryption, lock screen).

If you use the cloud backup feature, your data is additionally stored in your personal Google Drive or iCloud account. The security of your backed-up data is governed by Google's or Apple's security practices, including their encryption standards for data in transit and at rest.

We recommend that you:

- Keep your device's operating system up to date.
- Use a strong device passcode or biometric lock.
- Do not install apps from untrusted sources.
- Secure your Google or Apple account with a strong password and two-factor authentication if you use the backup feature.

We take reasonable measures in app design to protect your data, but we cannot guarantee absolute security of your device or third-party cloud storage services.

---

## 7. Data Retention and Deletion

Your data is retained on your device for as long as you choose to keep it. You have full control over your data:

- **In-App Deletion:** You can delete individual notes, recordings, images, and conversation histories at any time from within the app.
- **Full Data Deletion:** Uninstalling the app will remove all app data from your device.
- **Cloud Backup Deletion:** If you have created cloud backups, uninstalling the app does **not** automatically delete those backups. You must delete your backups manually through Google Drive or iCloud. MemoryAI does not retain or have access to your cloud backups.

We do not retain any copy of your data on our own servers, as we do not operate any.

---

## 8. International Data Transfers

MemoryAI does not transfer any of your data to its own servers, as we do not operate any.

However, if you choose to use the cloud backup feature, your data will be stored on servers operated by Google (for Google Drive) or Apple (for iCloud). These companies may store your data in data centers located outside your country of residence, including outside the European Economic Area (EEA). Google and Apple have their own mechanisms for ensuring compliance with international data transfer requirements, including Standard Contractual Clauses and other safeguards. For more information, please refer to their respective privacy policies:

- Google: [policies.google.com/privacy](https://policies.google.com/privacy)
- Apple: [apple.com/legal/privacy](https://www.apple.com/legal/privacy/)

Additionally, the downloading of AI model files from third-party repositories (e.g., HuggingFace) involves network requests to servers that may be located internationally. No personal data is transmitted during this process.

---

## 9. Third-Party Libraries and Services

MemoryAI is built using third-party libraries. The majority operate **on-device** and do not transmit your data to external servers. Key third-party components include:

- **Flutter:** The cross-platform framework used to build the app. Flutter itself does not collect user data.
- **Google ML Kit (On-Device Text Recognition):** Used for recognizing text in images. This API runs entirely on-device. While Google may download model updates in the background, your images and recognized text are **not** sent to Google's servers. Google's privacy policy: [policies.google.com/privacy](https://policies.google.com/privacy).
- **Google Drive (Android Backup):** If you enable the backup feature on Android, the app uses the Google Drive API to upload and download backup files to/from your personal Google Drive account. This requires authentication with your Google account. Only your app backup data is stored; MemoryAI does not access any other files in your Google Drive. Google's privacy policy: [policies.google.com/privacy](https://policies.google.com/privacy).
- **iCloud (iOS Backup):** If you enable the backup feature on iOS, the app uses Apple's iCloud storage to upload and download backup files to/from your personal iCloud account. Only your app backup data is stored; MemoryAI does not access any other files in your iCloud. Apple's privacy policy: [apple.com/legal/privacy](https://www.apple.com/legal/privacy/).
- **HuggingFace Model Downloads:** The app downloads AI model files from third-party repositories (e.g., HuggingFace). These downloads require a network connection and may involve sending an authentication token to the repository provider. **No personal data or user-created content is transmitted during this process.** Only the model files are downloaded to your device. HuggingFace's privacy policy: [huggingface.co/privacy](https://huggingface.co/privacy).
- **LoRA Adapter Files:** The app allows you to import custom LoRA adapter files (e.g., .gguf format) from your device's storage. These files are copied into the app's local storage and are processed entirely on-device.
- **On-Device LLMs:** The AI models used for conversations and RAG run locally. No queries or responses are transmitted externally.
- **Share/Export (share_plus):** When you use the Share feature to export conversations, the app uses your device's native share sheet (via the share_plus library). The data is handed off to the operating system and then to whichever app you select. MemoryAI does not control or monitor this data once it leaves the app.
- **In-App Purchases:** We use the native in-app purchase APIs provided by Apple (App Store) and Google (Google Play) to handle premium feature unlocks. We do not have access to your payment or billing information — this is handled entirely by Apple or Google. Purchasing premium features **does not** change how your data is handled; all data remains local unless you choose to use the backup feature.

If we integrate any new third-party service in the future, we will update this policy accordingly.

---

## 10. Your Rights Under GDPR

As a user in the European Union, you have the following rights under GDPR. Since all your data is stored locally on your device (and optionally in your personal cloud storage), you can exercise most of these rights directly:

- **Right to be Informed (Art. 13–14):** This privacy policy fulfills our obligation to inform you about data processing.
- **Right of Access (Art. 15):** All your data is accessible to you directly within the app and, if backed up, within your Google Drive or iCloud account.
- **Right to Rectification (Art. 16):** You can edit any data within the app at any time.
- **Right to Erasure (Art. 17):** You can delete individual items within the app, remove all data by uninstalling, and delete cloud backups through Google Drive or iCloud.
- **Right to Restrict Processing (Art. 18):** You can revoke device permissions to restrict specific processing activities.
- **Right to Data Portability (Art. 20):** You can export your conversations as text or Markdown using the Share feature within the app.
- **Right to Object (Art. 21):** Since processing is local and under your control, you can stop processing at any time by revoking permissions or uninstalling.
- **Rights Related to Automated Decision-Making (Art. 22):** The AI features in the app assist you but do not make decisions that produce legal or similarly significant effects on you.
- **Right to Lodge a Complaint:** You have the right to lodge a complaint with a supervisory authority. In Italy, this is the **Garante per la protezione dei dati personali** ([www.garanteprivacy.it](https://www.garanteprivacy.it)).

To exercise any right that requires our assistance, please contact us at **alessandro.facchini@facchinits.it**.

---

## 11. Children's Privacy

MemoryAI is not intended for use by children under the age of 16 in the European Union, or under the age of 13 in other jurisdictions. We do not knowingly collect any personal information from children. Since all data is processed locally, we have no means to identify the age of our users. If you are a parent or guardian and believe your child is using the app inappropriately, you can delete the app data by uninstalling the app from the device and removing any cloud backups from Google Drive or iCloud.

---

## 12. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we do:

- We will update the "Last Updated" date at the top of this page.
- For significant changes, we will provide an in-app notification before the changes take effect.

We encourage you to review this Privacy Policy periodically.

---

## 13. Contact Us

If you have any questions, concerns, or requests related to this Privacy Policy or your data, please contact us:

- **Email:** alessandro.facchini@facchinits.it

We aim to respond to all inquiries within 30 days, as required by GDPR.
