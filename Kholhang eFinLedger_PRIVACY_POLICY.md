# Privacy Policy — Kholhang eFinLedger

**Last updated:** 2026-04-28  
**App package:** `com.kholhang.efinledger`

This Privacy Policy explains how **Kholhang eFinLedger** (“the App”) collects, uses, and shares information.

## Overview

- The App is **offline-first**: your data is stored locally on your device.
- Optional **cloud sync** is available using **Firebase Realtime Database** when you sign in with Google.
- The App is designed to manage microfinance ledger data for lenders and borrowers.

## Data the App processes

### Data you enter

The App can store the following information that you provide:

- **Borrower profile**: name, email, phone, address, borrower type and other profile fields.
- **Loans**: principal, interest rate, repayment type, term, start date, currency, and related loan settings.
- **Repayments / ledger entries**: payment dates, amounts, notes, interest paid, principal paid, and remaining balances.
- **Documents metadata** (if you use the Documents feature): information you choose to attach/record.
- **GPS/Location entries** (if you use the GPS feature): coordinates, timestamp, and related notes.

### Account and device data

When you use cloud sync:

- **Google Sign-In / Firebase Auth** provides an account identifier (Firebase UID) and your email address to associate your data with your account.

## How we use data

We use the data to:

- Provide core features: borrower directory, loan tracking, repayment ledger, reminders, summaries, and PDFs.
- Sync your data across devices (only if you enable cloud sync and sign in).
- Provide basic diagnostics for stability (e.g., crash reports) if Firebase services are enabled in your build.

## Data storage

### Local storage (on your device)

Your data is stored locally using an on-device database (Room).

### Cloud storage (optional)

If you sign in and cloud sync is enabled:

- Your data is stored in **Firebase Realtime Database** under your Firebase user account (UID).

If you do not sign in, the App operates in **local-only** mode.

## Data sharing

We do **not** sell your personal information.

Data may be shared with service providers only as needed to provide app functionality:

- **Google / Firebase** (authentication, optional database sync, optional analytics/crash reporting depending on build configuration).

## Permissions

The App may request the following permissions depending on features you use:

- **Location**: only if you open the GPS/locations feature to capture borrower/location entries.
- **Notifications**: for reminders/notifications (if enabled on your device).
- **Internet**: for cloud sync and Google Sign-In (when enabled).

## Data retention and deletion

- Local data remains on your device until you delete it from within the app or uninstall the app.
- If cloud sync is enabled, data stored in Firebase remains associated with your Firebase account unless removed via the app’s sync/deletion flows or by removing the Firebase project data.

## Children’s privacy

The App is not intended for use by children under 13, and we do not knowingly collect personal information from children.

## Changes to this policy

We may update this policy from time to time. The “Last updated” date will reflect the latest version.

## Contact

If you have questions or requests about privacy, contact:

- **Email:** kholhangconnect@gmail.com

