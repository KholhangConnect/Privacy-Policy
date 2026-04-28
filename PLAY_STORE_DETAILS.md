# Play Store Details — Kholhang eFinLedger

**Package:** `com.kholhang.efinledger`  
**Category suggestion:** Finance / Business  
**Target audience:** Adults

## App name

Kholhang eFinLedger

## Short description (max ~80 chars)

Offline-first microfinance ledger for borrowers, loans, repayments & summaries.

## Full description

Kholhang eFinLedger helps lenders manage borrower profiles, loans, and repayment ledgers with clear summaries.

### Key features

- Borrower directory with quick search
- Create and manage loans (principal, interest, term, frequency)
- Record repayments and track remaining principal + accrued interest
- Loan list per borrower with search, filter, and “New Loan” action
- Summary popups for borrower profile and total loan/outstanding amounts
- Generate PDF reports/receipts (where supported)
- Offline-first storage on your device
- Optional Google Sign-In + Firebase sync (when configured)

### Offline-first, optional cloud sync

Your data is saved locally on your device. If you enable cloud sync and sign in, the app can sync your data using Firebase Realtime Database.

## What's new (release notes template)

- UI improvements and simplified sign-in
- Borrower loan list enhancements (search/filter + quick summaries)
- Tools screen scroll and other fixes

## Privacy policy URL

Publish the contents of `playstore/PRIVACY_POLICY.md` on a public URL and paste it here:

- `<PASTE_PRIVACY_POLICY_URL_HERE>`

## Contact details (for Play Console)

- **Support email:** `<REPLACE_WITH_SUPPORT_EMAIL>`
- **Website (optional):** `<REPLACE_WITH_WEBSITE_URL>`

## Data safety (notes for Play Console questionnaire)

This section helps you answer Play Console’s Data safety form. Validate against your exact Firebase configuration and what you ship.

- **Data collected**: Borrower profile data, loan/repayment ledger data, and optionally account identifiers (Google/Firebase) for sync.
- **Data shared**: Only with Google/Firebase services to provide authentication/sync (and optional crash/analytics depending on build).
- **Data encrypted in transit**: Yes (Firebase uses TLS).
- **Data deletion**: Users can delete local data by uninstalling; synced cloud data depends on your Firebase data management.

## Permissions justification (for Play Console)

- **Location**: Used only if the user uses the GPS/locations feature to capture locations.
- **Notifications**: Used for reminders/notifications.
- **Internet**: Required for Google Sign-In and cloud sync (when enabled).

