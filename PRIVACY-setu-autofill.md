# Setu Autofill — Privacy Policy

_Last updated: 28 October 2026_

Setu Autofill is a Chrome extension published by **Setu CRM (mysetucrm.com)** for authorised Aaple Sarkar / MahaOnline service-centre operators ("operators") in Maharashtra, India, who use the Setu Desk desktop app.

## What the extension does

It fills the operator's own applications on `cscservices.mahaonline.gov.in` (forms, document and photo uploads, and — only if the operator turns it on — VLE wallet payment) using data the operator has already entered and reviewed in Setu Desk. It also reads the operator's Application Status page and passes it to Setu Desk on the same computer.

## Data the extension handles

| Data | Where it comes from | Where it goes | Why |
|---|---|---|---|
| Operator's Setu login session (email, access token) | Operator logs in via the extension popup | Stored in Chrome local storage on the operator's PC; sent only to the Setu backend (Supabase) | To load the operator's own application queue |
| Applicant details (name, address, dates, certificate details) | Operator's Setu account / Setu Desk | Typed into the MahaOnline portal form in the operator's own browser session | To fill the application |
| Documents and photo | Setu Desk on the same PC (`127.0.0.1`) | Uploaded to the MahaOnline portal page | To complete the application |
| VLE wallet password | Saved by the operator in Setu Desk on the same PC | Entered only on the MahaOnline wallet payment page; never sent to Setu servers | Optional auto-payment, off by default |
| Application status rows and approved certificates | MahaOnline Application Status page | Setu Desk on the same PC (`127.0.0.1`) | To track applications and save certificates to the customer's folder |
| Settings (auto mode, payment on/off, daily limit, Setu Desk link code) | Operator | Chrome local storage on the operator's PC | Extension settings |

The extension works only on `cscservices.mahaonline.gov.in`. It does not read other websites, browsing history, cookies of other sites, or saved browser passwords.

## What we do not do

- We do not sell or rent any data.
- We do not use data for advertising, analytics profiling, credit scoring or lending.
- We do not share data with third parties, except our hosting provider (Supabase) that stores the operator's Setu account data on our behalf.
- No full Aadhaar number is stored by Setu; only the last four digits are kept.

## Security

Network calls to the Setu backend use HTTPS. Calls to Setu Desk stay on the same computer (`127.0.0.1`) and require a link code. The extension contains no remotely loaded code.

## Retention and deletion

Session data stays in Chrome until the operator logs out or removes the extension. Applicant data in the operator's Setu account is kept while the account is active; when an operator deletes a customer in Setu Desk, that customer's files are deleted locally and in the cloud. Operators can ask for account deletion using the contact below.

## Law

We aim to follow India's Digital Personal Data Protection Act, 2023 and UIDAI rules on Aadhaar data.

## Contact

Setu CRM — https://mysetucrm.com
