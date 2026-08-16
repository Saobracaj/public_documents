# Privacy Policy

**The "Saobraćaj" app** is a trainer for the theory part of the driving licence exam in the Republic of Serbia (a mobile app for Android and iOS and a web version at <https://saobracaj.gleb.at>; hereinafter the **App** or the **Service**).

This Privacy Policy explains which personal data we collect, why we process it, whom we entrust it to, how long we keep it and what rights you have. It is drawn up in accordance with the **Serbian Personal Data Protection Act** (Zakon o zaštiti podataka o ličnosti, "Službeni glasnik RS", No. 87/2018; hereinafter the **PDPA**) and, to the extent it applies to users from the European Economic Area, with the General Data Protection Regulation (GDPR).

The [Serbian version](https://docs.saobracaj.gleb.at/privacy_policy.html) is the legally binding one. This English translation is provided for convenience; a [Russian translation](https://docs.saobracaj.gleb.at/privacy_policy_ru.html) is also available.

## 1. Controller

The controller of personal data is:

**Gleb Klimov**, independent developer and publisher of the App  
Address: _[address and registration details of the controller — to be completed by the operator before publication]_  
E-mail for data-protection matters: <info@gleb.at>  
Telegram: [@GlebKl](https://t.me/GlebKl)

No data protection officer has been appointed, as the controller is under no legal obligation to appoint one. For all questions please use the e-mail address above.

## 2. Basic principles

The App is designed to collect as little data as possible. The questions, correct answers, the law text and most learning material ship with the App and **do not require an account**. Without an account, all your progress is stored only on your device and is not accessible to us.

An account is needed only for features that inherently require identification: syncing progress between devices, question lists, groups, public comments, the support chat, the AI assistant and the subscription.

We do not sell personal data and do not use it for third-party advertising.

## 3. What data we process

### 3.1. Use without an account (guest)

- **Local data on the device:** your answers, test results, statistics, question lists and settings (language, theme). Stored only on the device (in the web version — in the browser's local storage). We have no access to it; it is deleted when you uninstall the App, clear its data, or clear the site data in your browser.
- **Usage analytics** (see 3.7).
- **Server technical data** (see 3.6) — only when the App contacts our server (e.g. to load explanations, summaries or question-difficulty statistics).

### 3.2. Account

On registration we process:

- **e-mail address** — for sign-in, account confirmation, password recovery and notifications about the account and orders;
- **password** — we store only its cryptographic hash (Argon2); we do not know the password itself;
- **display name** — if you provide one; it is visible to other users in groups and next to public comments;
- **Google / Apple sign-in identifiers** — if you sign in this way, we receive your identifier and e-mail address from the provider (Apple may supply an anonymised relay address); the provider's token is used once to issue our session and is not stored;
- **session and device data** — identifiers of issued sessions (JWT), sign-in time, and for push notifications the device token (Firebase Cloud Messaging), platform and device language;
- **account settings** — content language, optional modules switched on/off (feature flags), notification settings.

### 3.3. Learning

When you are signed in, the following data is synced to our server so you can continue on another device:

- answers and results of tests and exam simulations (which question, which answer, correct/incorrect, time);
- your **question lists** (names, contents);
- read status of summaries and explanations.

From aggregated, de-identified answer data of all users we compute question-difficulty statistics ("how many users get this question wrong"). These statistics contain no data identifying you.

### 3.4. Social features

- **Groups:** group name, membership, role (owner/member), invitations and group events (e.g. "a member finished a test"). This data is visible to all members of that group.
- **Public comments on questions:** the comment text, your display name and posting time. **Public comments are visible to all users of the App.** Do not put personal data in them. You can delete a comment; a "deleted" marker replaces the text.
- **Report a problem / chat with the developer:** the messages you send, attachments (screenshots, images) and technical information you attach (App version, platform). Attachments are stored in private storage (Google Cloud Storage) and are available only to you and to support.

### 3.5. AI assistant

The "Ask AI" feature runs on services of **Anthropic, PBC** (USA). When you send a question to the assistant, the following is transmitted to Anthropic's servers: the text of your message, the text of the exam question the conversation is attached to and — when you ask for an analysis of a test result — your answers in that test. **Not transmitted** are your e-mail, name or other account identifiers: Anthropic receives only the conversation content. Under our agreement with Anthropic this data is not used to train models.

The AI conversation history is stored with your account so you can return to it; it is deleted together with the account.

### 3.6. Technical data

Our server (API) records standard technical data about requests: IP address, time, requested address, App and OS version (User-Agent), server response. This data serves security, abuse detection and troubleshooting and is kept for a limited time (section 6).

### 3.7. Usage analytics (Firebase Analytics)

To understand which features are used and where users run into difficulties, the App uses **Google Analytics for Firebase**. Collected are: screen views, selected events (e.g. test started/finished, sign-in), a pseudonymous App-instance identifier, device model, operating system, language, App version and approximate location at country/city level (derived from the IP address, which is not stored). Analytics **do not contain** your name, e-mail or the content of your answers. In the web version Google Analytics cookies (e.g. `_ga`) are used for this.

### 3.8. Subscription and payment

If you order a subscription (available only in the web version):

- we store **order** data: the chosen tariff, amount in dinars, the payment reference ("poziv na broj"), status (awaiting payment / paid / cancelled / expired), time, and the **subscription periods** granted to you;
- payment is made by **bank transfer** (payment slip — "uplatnica" — or IPS QR code) to our account. We do not collect your card or bank-account details — the payment happens in your bank. Our bank statement shows the data your bank forwards with the transfer (payer name, amount, reference, purpose); we use it solely to match the payment to the order and for bookkeeping;
- we send e-mails about the order, the payment, the subscription expiry (reminders 14 and 3 days before — they can be switched off in settings) and about resuming the subscription.

## 4. Purposes and legal bases

| Purpose | Data | Legal basis (Art. 12 PDPA / Art. 6 GDPR) |
|---|---|---|
| Providing the Service: account, sync, lists, groups, comments, AI assistant | 3.2–3.5 | performance of the contract with you (terms of use) |
| Subscription, billing, bookkeeping | 3.8 | performance of the contract; compliance with legal obligations (accounting and tax rules) |
| Account and order notifications (e-mail) | e-mail address | performance of the contract |
| Push notifications about group events and replies | device token | consent (the permission you grant in the operating system; revocable in device settings) |
| Subscription-expiry reminders | e-mail address | legitimate interest; can be switched off in settings |
| Security, abuse prevention, error diagnostics | 3.6 | legitimate interest of the controller |
| Usage analytics | 3.7 | legitimate interest in understanding usage and improving the App; in the web version, for analytics cookies — your browser settings |
| Question-difficulty statistics | aggregated de-identified data | legitimate interest; the result contains no personal data |
| Answering your requests | request content, contact | legitimate interest / performance of the contract |

## 5. Recipients and processors

We do not disclose data to third parties for their own purposes. Processing on our behalf (processors) is carried out by:

| Processor | What it does | Data location |
|---|---|---|
| EDIS GmbH (Austria) | rented server running our API and database | data centre in **Belgrade, Serbia** |
| Google Ireland Ltd. / Google LLC | Firebase Authentication (Google/Apple sign-in), Firebase Cloud Messaging (push), Google Analytics for Firebase, Google Cloud Storage (support attachments) | EU (region `europe-west1`, Belgium) for storage; EU/USA for the other services under Google's terms |
| Apple Inc. | "Sign in with Apple" | under Apple's terms |
| Anthropic, PBC | processing of AI-assistant requests (3.5) | USA |
| Resend, Inc. | transactional e-mail (confirmations, codes, orders) | USA / EU |
| GitHub, Inc. | hosting of these documents and of the web version | USA |
| Banks | receiving subscription payments | Serbia |

Data is disclosed to public authorities only where a legal obligation exists (e.g. a court order).

## 6. Transfers outside the Republic of Serbia

Our database and server are located in Serbia. Some processors (section 5) process data in the European Union — states which the Government of the Republic of Serbia has determined to ensure an adequate level of protection — or in the United States. For transfers to states without an adequacy determination we rely on standard contractual clauses and data-processing agreements in accordance with Art. 65 PDPA (Art. 46 GDPR).

## 7. Retention

| Data | Period |
|---|---|
| Account and data tied to it (progress, lists, settings, AI conversations, sessions, device tokens) | until account deletion |
| Public comments | until the comment or the account is deleted (the text is then replaced by a "deleted" marker) |
| Support messages and attachments | until account deletion; on your request at deletion time they are removed as well |
| Orders and subscription periods | 10 years from the end of the business year — the retention period for accounting records under Serbian law; this data is **not deleted** with the account but is detached from your identity (see section 8) |
| Server technical logs | up to 12 months |
| Analytics data (Firebase Analytics) | up to 14 months (Google Analytics retention setting) |
| Local data on the device | until you delete it yourself |

## 8. Account deletion

You can delete your account yourself: **Settings → Profile → Delete account** (confirmed with a code sent by e-mail), or by sending a request to <info@gleb.at> from the account's e-mail address. Detailed instructions: <https://docs.saobracaj.gleb.at/delete_account.html>.

On deletion: e-mail, password, name and access rights are irreversibly anonymised; progress, lists, AI conversations, sessions, grants and device data are deleted; group memberships end (a group you founded passes to its longest-standing member or is closed); comments are replaced by a "deleted" marker; support messages remain anonymous unless you also request their removal at deletion time. Order records remain in the accounting records without any link to your identity.

Local data on the device can be kept at deletion (as guest progress) or deleted — your choice.

## 9. Your rights

Under the PDPA (Art. 21–38) and the GDPR you have the right:

- of **access** — to learn whether we process your data and to receive a copy;
- to **rectification** of incomplete or inaccurate data;
- to **erasure** ("right to be forgotten");
- to **restriction of processing**;
- to **data portability** — to receive the data you provided in a structured, machine-readable format;
- to **object** to processing based on legitimate interest;
- to **withdraw consent** at any time (e.g. switch off push notifications), without affecting the lawfulness of earlier processing.

Send requests to <info@gleb.at>. We will respond without undue delay and at the latest within **30 days** of receipt (the period may be extended in complex cases, of which we will inform you). To protect your data we may ask you to send the request from the account's e-mail address.

If you believe the processing of your data is unlawful, you have the right to lodge a complaint with the **Commissioner for Information of Public Importance and Personal Data Protection** of the Republic of Serbia (Poverenik za informacije od javnog značaja i zaštitu podataka o ličnosti): Bulevar kralja Aleksandra 15, 11120 Belgrade, <https://www.poverenik.rs>, <office@poverenik.rs>. Persons in the EU may also contact the supervisory authority of their own state.

## 10. Security

We apply technical and organisational measures proportionate to the risk: encrypted connection (HTTPS/TLS) between the App and the server, password hashing (Argon2), restricted access to the server and database, regular backups, data minimisation in integrations (e.g. the AI assistant does not receive your identity), access logging. No system is absolutely secure; we will notify you and the Commissioner of a data breach likely to result in a high risk to your rights, as required by the PDPA.

## 11. Children

The App is intended for people preparing for the driving exam and is not directed at children under 15. We do not knowingly collect data of children under 15; if we learn of such a case, we will delete the account. Parents and guardians can contact us at <info@gleb.at>.

## 12. Cookies and local storage (web version)

The web version at <https://saobracaj.gleb.at> uses the browser's local storage (localStorage, IndexedDB) for essential functions: keeping your session, settings and local progress — the App cannot work without it, and no consent is required for that. For analytics, Google Analytics for Firebase cookies are used (`_ga` and related, lifetime up to 2 years). You can block analytics cookies in your browser settings or with a tracking-blocker extension; the App will work without them.

## 13. Changes to this Policy

We may change this Policy from time to time. The current version is always published at <https://docs.saobracaj.gleb.at/privacy_policy.html>, and the **complete change history — with the date and content of every change — is publicly available in the repository history**: <https://github.com/Saobracaj/public_documents/commits/main/privacy_policy.md>. We will notify you of material changes in the App or by e-mail.

## 14. Contact

Gleb Klimov — <info@gleb.at> — Telegram [@GlebKl](https://t.me/GlebKl)

_Last updated: 16 August 2026._
