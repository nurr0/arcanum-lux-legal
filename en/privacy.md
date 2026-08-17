# Privacy Policy

**Last updated:** 17.08.2026

This Privacy Policy describes what data the "Arcanum Lux" mobile application
(the "App", "we") collects and processes. The App is developed by
Individual Entrepreneur R. I. Nuriyev (the "Developer").

---

## 1. What data we collect

### 1.1. Data you provide yourself

| Data | Why we collect it |
|---|---|
| Email and password (or Google/Apple sign-in details) | Creating and protecting your account |
| Name (optional) | Personalising how the App addresses you |
| Date of birth (optional) | Reserved for possible future features (e.g. zodiac-based personalisation); not actively used at present |
| Onboarding survey answers (interests: love, career, self-development, etc.) | Personalising prompts and advice |
| Interface language, notification time, theme | App settings |
| Questions you enter before a reading, and personal journal notes | Core App functionality — card of the day, readings, journal |

### 1.2. Data collected automatically

- Your reading history and cards of the day (dates, spread types, results)
- App usage statistics (consecutive-day streak, number of readings)
- Full-access status and purchase history (processed via RevenueCat — see section 3)
- Technical data when ads are displayed (via Google AdMob — see section 3)
- Technical crash reports if the App fails (via Sentry — see section 3)
- Your IP address at the moment you accept the legal documents — stored together
  with the record of consent as supporting evidence (see section 4.3)

### 1.3. Data we do **not** collect

We do not request or process health data, payment credentials (payment goes
directly through the App Store/Google Play, bypassing our servers), or precise
geolocation.

---

## 2. How we use data

- Providing App functionality (card of the day, readings, journal, full access)
- Personalisation — tailoring prompts based on the interests you indicated
- Tracking streaks and usage statistics
- Sending push notifications (if you enabled them) — e.g. a card-of-the-day reminder
- Processing the full-access purchase and ad rewards
- Improving the App and fixing errors

We do **not sell** your personal data to third parties.

---

## 3. Third-party services

The App uses the following third-party services, each with its own privacy policy:

| Service | Purpose | Data transferred |
|---|---|---|
| **RevenueCat** | Processing in-app purchases | User identifier, purchase status and history |
| **Google AdMob** | Displaying rewarded ads (an ad in exchange for a token to unlock a reading) | Device advertising identifier, technical data required to serve ads — per [Google's policy](https://policies.google.com/privacy) |
| **Google Sign-In / Apple Sign-In** | Signing in with a Google/Apple account | Email — to the extent you permit at sign-in |
| **Sentry** | Automatic reports of App errors and crashes | Device type, OS and App version, technical error description. Your email and the contents of your notes are not included in reports |

We recommend reviewing these services' privacy policies separately.
For the locations of their servers, see section 4.2.

---

## 4. Where data is stored and processed

### 4.1. Primary storage

The App runs on **Google Cloud Platform** infrastructure (Google LLC, USA):

| What | Service | Hosting region |
|---|---|---|
| Application backend (API) | Google Cloud Run | `asia-southeast1` — **Singapore** |
| Database (accounts, readings, journal) | Google Cloud SQL (PostgreSQL) | `asia-southeast1` — **Singapore** |
| Service secrets (access keys) | Google Secret Manager | `asia-southeast1` — **Singapore** |

Data transfer between your device and the server is protected by HTTPS/TLS encryption.

### 4.2. Third-party processors

Some data is processed by services whose servers are located outside Singapore
(typically in the USA and European Union countries):

| Service | Operator | What it processes |
|---|---|---|
| Google Sign-In | Google LLC (USA) | Verifying authenticity of Google account sign-in |
| Apple Sign-In | Apple Inc. (USA) | Verifying authenticity of Apple ID sign-in |
| RevenueCat | RevenueCat, Inc. (USA) | In-app purchase status and history |
| Google AdMob | Google LLC (USA) | Ad delivery, device advertising identifier |
| Sentry | Functional Software, Inc. (USA) | Technical App error reports |

### 4.3. Consent to cross-border data transfer

**Important.** You are located in one country, while the servers processing your
data are in others (Singapore, USA, EU countries). This is known as cross-border
transfer of personal data.

By installing the App, creating an account and continuing to use it, you give
your **explicit consent** to the transfer, storage and processing of your
personal data (listed in section 1) in the countries indicated above, by the
operators specified in sections 4.1 and 4.2, on the terms of this Policy.

You may **withdraw this consent** at any time by deleting your account in the
App (Settings → Delete account). Once deleted, processing of your data ceases
and the data itself is irreversibly erased (see section 5). Please note that
without such consent it is technically impossible to provide the App's
functionality, since it is built on the infrastructure listed above.


---

## 5. How long we keep data

We keep your account data for as long as the account is active. When you delete
your account (available in the App: Settings → Delete account), all data —
readings, journal, purchase records — is erased irreversibly and immediately.

---

## 6. Your rights

At any time you may:
- **View** your data — it is displayed in the App itself (profile, journal, reading history)
- **Change** your profile data — in the "Settings" section
- **Delete your account and all data** — in "Settings" → "Delete account". This action is irreversible.
- **Request an export or manual deletion of your data** — write to us at nurro.dev@gmail.com

### 6.1. Additional rights for users in the European Union (GDPR)

If you are located in the EU or EEA, you have the following rights under the
General Data Protection Regulation (GDPR):

- **Right of access** (Art. 15) — to obtain confirmation as to whether your
  data is being processed, and a copy of that data.
- **Right to rectification** (Art. 16) — to have inaccurate data corrected.
- **Right to erasure** (Art. 17, "right to be forgotten") — to request deletion
  of your data. Available instantly in the App: Settings → Delete account.
- **Right to restriction of processing** (Art. 18).
- **Right to data portability** (Art. 20) — to receive your data in a
  machine-readable format. Write to **nurro.dev@gmail.com** and we will provide an export.
- **Right to object** (Art. 21) — to object to processing, including the use of
  your data for personalised advertising.
- **Right to withdraw consent** (Art. 7(3)) — at any time, without giving
  reasons. Withdrawal does not affect the lawfulness of processing carried out
  before the withdrawal.
- **Right to lodge a complaint** — with the data protection supervisory
  authority of your country.

**Legal bases for processing** (Art. 6 GDPR): performance of a contract with
you (providing the App's functionality) and your consent — for cross-border
data transfer and personalised advertising.

To exercise any of these rights, write to **nurro.dev@gmail.com**.
We will respond within the period set by the GDPR — no later than one month.

---

## 7. Children and minors

The App is not intended for persons under 18 years of age. We do not knowingly
collect children's data. If you believe a child has provided us with their
data, write to nurro.dev@gmail.com and we will delete it.

---

## 8. Security

We apply reasonable technical protection measures: passwords are stored in
hashed form (not in plain text), access to data is protected by JWT
authorisation tokens, and the connection to the server is encrypted via HTTPS.
However, no system can guarantee absolute protection — use a strong password
and do not share your sign-in details with third parties.

---

## 9. Changes to this Policy

We may update this Policy. We will notify you of material changes via an in-app
notice or by email. The date of the last update is shown at the top of this document.

---

## 10. Contact

For questions regarding the processing of personal data, write to: **nurro.dev@gmail.com**

Individual Entrepreneur R. I. Nuriyev
Republic of Kazakhstan, Shymkent
