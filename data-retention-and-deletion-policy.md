# Data Retention & Data Deletion Policy

**Last updated: 21 November 2026**

This page explains the intended retention approach for Desi Ladki. Actual retention periods must be configured, tested and periodically reviewed.

## 1. Local app data

Chat history, character selection, progress and related chat state are intended to be stored on the user's device. Users can clear app storage or uninstall the app. Local device backups may be controlled separately by Android.

## 2. Backend purchase/session records

The backend processes anonymous installation identifiers, purchase-token hashes, product/order references, character identifiers, session identifiers, timestamps, purchase state and session status as needed to verify purchases, prevent duplicate token use, activate sessions and manage disputes or fraud.

The purchase token itself is sensitive and must not be exposed in logs or support correspondence. The backend database may retain records for the period needed for these purposes, legal duties and dispute resolution. A specific retention schedule (for example, by record type and deletion trigger) must be adopted by the operator before launch.

## 3. Advertising data

AdMob and associated Google services may process data under Google's own retention and privacy practices. Review Google's documentation and the production SDK settings for precise categories and controls.

## 4. Deletion requests

Send a request to **indianfreelancerguy@gmail.com** with subject **Desi Ladki — Data Deletion Request**. We may request limited verification details. We will delete or de-identify data that is no longer required, subject to lawful retention needs and data held independently by third-party providers.

## 5. Security and backups

Backups and disaster-recovery copies may persist for a limited operational period after records are removed from primary systems. The operator must define and apply a backup expiry schedule. No service can promise immediate removal from every backup at the exact moment a request is received.

## 6. Review

This policy should be updated whenever the app adds accounts, cloud chat sync, analytics, additional advertising SDKs, live messaging or other data processing.
