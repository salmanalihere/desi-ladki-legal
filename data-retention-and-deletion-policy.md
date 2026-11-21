# Data Retention & Data Deletion Policy

**Last updated: 21 November 2026**

## 1. What retention means

Retention is simply how long information is kept. For example, a five-minute paid session can expire, but the database record describing that session may remain afterwards. Session expiry and record deletion are two different things.

## 2. Local app data

Chat history, character selection, progress and related chat state are intended to be stored on the user's device. Users can clear app storage or uninstall the app. Device backups may be controlled separately by Android.

## 3. Backend records currently stored

The reviewed backend database schema contains:
- anonymous installation records (installation identifier and creation time);
- purchase records (installation identifier, product/character identifiers, order reference, purchase-token hash, verification state, session reference and timestamps);
- session records (installation identifier, character identifier, purchase-token hash, session start/expiry timestamps and status).

The backend stores a hash of the purchase token rather than the raw token in these database records.

## 4. Current deletion status

The reviewed backend storage code does not show an automatic cleanup job or fixed expiry period for old purchase/session records. Therefore, we cannot honestly promise that expired records are automatically deleted after a specific number of days. A retention schedule and deletion mechanism still need to be chosen, implemented and tested.

## 5. Deletion requests

For a request concerning backend records, email **indianfreelancerguy@gmail.com** with subject **Desi Ladki — Data Deletion Request**. Do not include passwords, OTPs or purchase tokens. We may ask for limited information to locate records and verify the request. This contact route is provided, but the backend deletion workflow must be implemented before promising that all records can be deleted on request.

## 6. Legal and operational retention

Some purchase/accounting, fraud-prevention or dispute records may need to be retained where required by law or reasonably necessary to resolve a dispute. Where data must be retained, the reason and applicable retention basis should be explained to the requester.

## 7. Advertising

The developer has confirmed that no AdMob account or production advertising setup exists yet. If ads, analytics or other tracking SDKs are enabled, this policy must be updated to identify relevant data and providers.


## Publisher details

**Publisher:** Xenon (registered company)  
**Registered/contact address:** C1/7, Block D, Jamia Nagar, New Delhi, Delhi 110025, India  
**Email:** indianfreelancerguy@gmail.com
