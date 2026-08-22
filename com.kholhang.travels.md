# Privacy Policy

**App:** Kholhang Travels  
**Package name:** `com.kholhang.travels`  
**Effective date:** 23 August 2026  
**Last updated:** 23 August 2026  

This Privacy Policy explains how **Kholhang Travels** (“we”, “the app”) collects, uses, stores, and shares information when you use the Android application identified by package name **`com.kholhang.travels`**.

---

## 1. Who this policy covers

This policy applies to users of Kholhang Travels, including guests who browse the app, signed-in travelers (User / Both), and Driver/Owner accounts that list vehicles.

## 2. Information we collect

Depending on how you use the app, we may process:

- **Account details:** name, email address, mobile number, and account role (User, Driver/Owner, or Both).
- **Vehicle details (Driver/Owner):** registration number (RC), make/model, type, colour, year, fuel, seats, rental consent, and Vahan verification status.
- **Location (Driver/Owner only):** a one-time GPS check when you tap “Check my GPS location”, used to confirm you are in Churachandpur, Manipur (within about 25 km of town centre) or in Mizoram. We do not track your location in the background.
- **Bookings:** trip/rental details you create (for example pickup/drop, dates, route, seats, phone used for booking).
- **Listings:** vehicle listing information you publish for rental.
- **Device permissions:** approximate/precise location (only when you request a GPS check), internet access for Vahan verification and Firebase sync, and the ability to open the phone dialer (we do not place calls automatically).

## 3. How we use information

- Provide booking features (rent, ride, fleet, pool) and owner listing tools.
- Require sign-in (email) before completing a booking; guests may browse only.
- Verify Driver/Owner registration location (Churachandpur, Manipur or Mizoram).
- Optionally verify vehicle RC via an authorized Vahan/Parivahan data partner over HTTPS when you choose “Verify with Vahan portal”.
- Sync account, booking, listing, and GPS-check records to Firebase Realtime Database when your Firebase project is configured.
- Show your contact number to owners when you book online or choose Call owner.

## 4. Legal bases / consent

- You agree to this Privacy Policy when creating an account (privacy acknowledgment is required).
- Location is requested only after an in-app disclosure and your permission grant.
- Vahan verification is optional and shown with a disclosure before your RC is sent.
- Rental listings require explicit owner consent before a vehicle is shown to renters.

## 5. How we store and share information

- **On device:** profile, bookings, and GPS check logs are stored in local app storage (Room database).
- **Cloud (optional):** when Firebase is configured, copies may be stored under your Firebase Realtime Database project (for example profiles, bookings, listings, location logs).
- **Vahan partner:** if you verify RC, your registration number is sent over HTTPS to an authorized partner API that returns vehicle registry details. We do not sell this data.
- **Call owner:** opens your device dialer with the owner’s number via `ACTION_DIAL`. The app does not use the `CALL_PHONE` permission.
- We do not sell personal information.
- We do not use your data for third-party advertising in this app version.

## 6. Data retention and deletion

- Local data remains on your device until you clear app data or use in-app deletion.
- In the app: **Help → Delete my data** removes your profile, bookings, and GPS logs from the device and attempts to remove the matching cloud profile node when Firebase sync is available.
- You may also uninstall the app to remove local storage.
- If you need cloud data removed from a Firebase project you control, delete it in the Firebase Console as well.

## 7. Children’s privacy

Kholhang Travels is intended for general audiences arranging vehicle bookings. It is not directed at children under 13. Do not provide personal information for children if you are not authorized to do so.

## 8. Security

- Network traffic for Vahan and Firebase uses encrypted HTTPS connections.
- Cleartext HTTP is disabled in the app configuration.
- Local databases with personal data are excluded from automatic cloud backup where configured.
- Firebase Realtime Database access is protected by security rules requiring authentication and ownership checks when those rules are published.

## 9. Your choices

- Browse as Guest without creating an account (booking requires sign-in).
- Deny or revoke location permission in system settings (Driver/Owner GPS check will not work).
- Skip Vahan verification and enter vehicle details manually.
- Delete your data from Help, or clear app storage / uninstall.

## 10. Google Play Data safety summary

For Play Console Data safety, declare at least:

- Personal info: name, email, phone
- Location: approximate/precise (Driver/Owner registration check only; not continuous tracking)
- App activity / other: booking and listing data you create
- Data may be stored on device and, if configured, in Firebase
- Users can request deletion via Help → Delete my data

## 11. Changes to this policy

We may update this Privacy Policy when features change. The “Last updated” date at the top will be revised. Continued use of `com.kholhang.travels` after changes means you accept the updated policy.

## 12. Contact

For privacy questions about **Kholhang Travels** (package **`com.kholhang.travels`**), use the Help section in the app, or contact the publisher of the app listing on Google Play.

---

*File: `com.kholhang.travels.md` · Also available as `com.kholhang.travels.html` · Package: `com.kholhang.travels`*
