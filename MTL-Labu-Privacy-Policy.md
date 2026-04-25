# MTL Labu — Privacy Policy

**Last updated:** 25 Apr 2026

MTL Labu (“**MTL Labu**”, “we”, “our”, “the app”) is a hymn reader and admin publishing tool. This Privacy Policy explains what data the app uses, where it is stored, and when it is shared.

## Information we collect and use

- **Hymn content and metadata (public content)**
  - **What**: Hymn text (lyrics), title, songbook, language, category/occasion, optional audio link, optional YouTube link, and related metadata.
  - **Why**: To show hymns in the app and keep them updated.
  - **Where stored**: On your device (local database). It may also be stored in **Firebase Realtime Database** if an admin uploads/publishes.

- **App settings (on-device)**
  - **What**: Theme, font size/lyrics scale, favorites, and reader scroll position.
  - **Why**: To personalize your reading experience.
  - **Where stored**: **Only on your device** (not uploaded by the app).

- **Usage data (view count)**
  - **What**: A view counter for hymns.
  - **Why**: To track total opens/reads.
  - **Where stored**: On-device. If an admin is signed in, view counts may also update in Firebase when the app syncs/pushes a hymn row.

- **Admin authentication**
  - **What**: When you use Admin login, the app uses **Google Sign-In** and then signs in to **Firebase Authentication** to allow admin-only publishing.
  - **Why**: To restrict writing/uploading to authorized admins.
  - **Where stored**: Your Firebase authentication session is handled by Firebase on the device.

- **On-device audit logs (admin actions)**
  - **What**: The app can store local logs such as publish attempts and a lyrics-change audit trail (timestamps and short previews/hashes).
  - **Why**: To help admins review changes and troubleshoot publishing.
  - **Where stored**: **Only on your device**, unless you choose to share them using Android’s Share sheet.

## What we share

- **Firebase Realtime Database**
  - If you are an authorized admin and choose to upload/publish, the app writes hymn and filter data to Firebase.
  - Reading/syncing of public hymn/filter data may occur when you are online.

- **Sharing from within the app**
  - If you tap **Share** (for hymns or logs), the app sends the selected text/file to the app(s) you choose via Android’s sharing feature.

## What we don’t do

- **No selling of personal data.**
- **No advertising SDKs** are required for the app’s core features.
- **No background access to contacts, SMS, or call logs.**
- The app does **not** upload your favorites, reading position, theme, or font size to the cloud.

## Data retention

- **On-device settings and logs** remain on your device until you clear app data or uninstall.
- **Firebase data** (if published) is retained according to the Firebase project’s configuration and the admin’s management of that database.

## Security

We use Firebase Authentication to protect admin write access and use Firebase database rules to restrict publishing. No method of storage or transmission is 100% secure, but we take reasonable steps to protect data.

## Children’s privacy

MTL Labu is not directed to children under 13 and does not knowingly collect personal information from children.

## Your choices

- You can use the app for reading without admin login.
- You can clear the app’s local data at any time from Android Settings.
- You control sharing: data is only shared when you initiate a Share action.

## Contact

If you have questions or requests about this Privacy Policy, contact the app administrator/publisher for your distribution of MTL Labu.

