# Desi Ladki — Legal & Policies

Public policy website for the Desi Ladki Android app.

**Publisher / company name supplied:** Xenon  
**Publisher structure:** Registered company  
**Registered office / contact address supplied:** C1/7, Block D, Jamia Nagar, New Delhi, Delhi 110025, India  
**Contact email:** indianfreelancerguy@gmail.com  
**Policy review date:** 21 November 2026

> **Draft status:** These are working policy drafts, not legal advice. The publisher has confirmed that Xenon is a registered company. Before publication, ensure “Xenon” is written exactly as it appears on the company's registration certificate (including any legal suffix such as Pvt. Ltd. or LLP, if applicable), and obtain legal review.

## Pages

- [Privacy Policy](privacy-policy.md)
- [Terms & Conditions](terms-and-conditions.md)
- [Product Disclaimer](product-disclaimer.md)
- [Refund & No-Refund Policy](refund-policy.md)
- [Recharge & Payment Policy](recharge-and-payment-policy.md)
- [Cookie & Tracking Technologies Policy](cookie-and-tracking-policy.md)
- [Acceptable Use Policy](acceptable-use-policy.md)
- [Account Deletion Policy](account-deletion-policy.md)
- [Grievance Redressal Policy](grievance-redressal-policy.md)
- [User Safety & Content Policy](user-safety-and-content-policy.md)
- [Intellectual Property Policy](intellectual-property-policy.md)
- [Data Retention & Data Deletion Policy](data-retention-and-deletion-policy.md)

## Known product facts

- Desi Ladki is an entertainment app with scripted, pre-written or predefined chat-style content.
- The developer says chat messages are stored locally on the user's device.
- The app has an anonymous installation identity and a backend that processes purchase verification and paid session records.
- The configured Play product is `chat_5min_49`, a five-minute character-specific session.
- The Android manifest currently contains Google's AdMob **test** application ID. The developer says no AdMob account has been created and production advertising is not yet configured. Do not claim production ads are running until this changes.

## Publication checklist

1. Confirm that “Xenon” is the exact registered company name and add its legal suffix exactly as shown on the registration certificate, if any.
2. Confirm that the supplied address is the company's correct registered/contact address: C1/7, Block D, Jamia Nagar, New Delhi, Delhi 110025, India.
3. Identify the person formally designated as the Grievance Officer and publish their correct name and designation where required by applicable law.
4. Before enabling AdMob, review the SDK, consent flow, advertising ID use, ad personalisation, privacy disclosures and Google Play Data safety form; update these policies before release.
5. Set actual retention periods and implement deletion/cleanup procedures for backend purchase/session records. At present the backend schema has persistent user, purchase and session tables; no automatic expiry/deletion schedule is evident in the reviewed storage code.
6. Implement and test a backend deletion request process and a user-facing route if the app's account model or Play requirements require it.
7. Confirm app behaviour, privacy disclosures and Google Play Data safety declarations match production.

## What “retention” means

Retention is how long information is kept. For example, an expired five-minute session may still have a database record after the chat session ends. A retention schedule decides when records can be deleted or anonymised. The current backend code stores purchase/session records but does not show an automatic cleanup schedule. Do not promise deletion after a particular number of days until that schedule is chosen and implemented.

## References for legal review

- [Google Play User Data and Privacy Policy requirements](https://support.google.com/googleplay/android-developer/answer/10144311)
- [Digital Personal Data Protection Act, 2023 — commencement notification](https://egazette.gov.in/WriteReadData/2025/267647.pdf)
- [Digital Personal Data Protection Rules, 2025](https://egazette.gov.in/WriteReadData/2025/267650.pdf)
- [Consumer Protection (E-Commerce) Rules, 2020](https://consumeraffairs.gov.in/public/upload/files/E%20commerce%20rules_1732703966.pdf)

These references are starting points for review; applicability depends on the actual service and facts.
