---
layout: page
title: Privacy Policy
permalink: /privacy/
---

**Effective date:** 29 March 2026

This privacy policy explains what data The Wainwright Companion ("the app") collects, how it is stored, and how it is used. We believe in keeping things simple: the app collects only what it needs to work, stores your data within Apple's infrastructure, and never sells or shares your personal information with advertisers.

## What data the app collects

### Data you provide

- **Completion records** — When you log a fell as completed, the app stores the date, any notes you write, your rating, weather conditions, and the names of companions you choose to record.
- **Photos** — If you attach photos to a completion, references to those images are stored alongside your completion record.
- **Profile information** — If you use social features, your chosen display name, profile photo, and connection to other profiles are stored.

### Data collected automatically

- **Location data** — During active navigation, the app records your GPS position to provide route guidance, off-route alerts, and walk statistics (distance, ascent, pace). Location data is only collected while you are actively using the navigation feature. The app does not track your location in the background unless you have explicitly enabled background navigation.
- **Walk statistics** — Duration, distance, ascent, descent, altitude, and speed are calculated from your GPS track during a walk.

- **Health data** — If you complete a GPS-tracked walk and have granted Health permission, the app saves the walk as a Hiking workout in Apple Health. The workout record includes start time, end time, distance, and route data. The app also reads your existing workout history to avoid creating duplicate entries. Health data is stored in Apple Health on your device and, if you have iCloud enabled, in your iCloud Health database. We do not have access to your Health data.

### Data the app does not collect

- The app does not use analytics SDKs or tracking frameworks.
- The app does not collect advertising identifiers.
- The app does not track you across other apps or websites.
- The app does not collect your name, email address, or phone number (unless you contact us directly for support).

## How your data is stored

All your data is stored locally on your device using Apple's SwiftData framework. If you are signed into iCloud, your data is automatically synced to your private iCloud account using Apple CloudKit. This means:

- Your data is encrypted at rest by Apple.
- Your data is stored in Apple's data centres, subject to [Apple's privacy policy](https://www.apple.com/legal/privacy/).
- Your data syncs across your devices signed into the same iCloud account.
- We do not operate our own servers and do not have access to your iCloud data.

## What is shared publicly

Nothing is shared by default. If you choose to use social features, you can mark individual completions as public. Only the data you explicitly share is visible to other users — specifically your display name, the fell name, date completed, notes, rating, and any attached photo.

You can remove shared completions at any time.

## Third-party services

The app uses two external services:

- **Met Office Weather DataHub** — Your approximate location (latitude and longitude of the fell you are viewing) is sent to the Met Office to retrieve weather forecast data. No personal identifiers are included in these requests. The Met Office's privacy policy is available at [www.metoffice.gov.uk/policies/privacy](https://www.metoffice.gov.uk/policies/privacy).

- **BRouter** — Fell coordinates are sent to calculate walking routes. No personal identifiers are included. BRouter is open-source software; route calculations may use a local instance bundled with the app or a remote server.

- **Anthropic Claude (Companion Pro only)** — AI-powered features send your request through a proxy server operated by us (hosted on Cloudflare) to Anthropic's Claude API. Your request may include fell names, route details, or any text you type into the AI feature. A device identifier (a vendor UUID — not your Apple ID or name) is sent alongside each request for rate limiting. We do not log request content on our proxy. Anthropic's privacy policy is available at [anthropic.com/privacy](https://www.anthropic.com/privacy).

No other third-party services receive your data.

## Data retention and deletion

Your data remains on your device and in your iCloud account until you choose to delete it. You can:

- **Delete individual completions** from within the app.
- **Delete all data** using the "Delete All Data" option in the app's Settings screen. This removes all local data and initiates deletion from iCloud.
- **Delete iCloud data independently** via your device's Settings > Apple Account > iCloud > Manage Storage.
- **Uninstall the app** to remove all local data. iCloud data can be removed separately as described above.

## Children's privacy

The app is not directed at children under 13 and does not knowingly collect personal data from children under 13. If you believe a child has provided data through the app, please contact us and we will delete it.

## Changes to this policy

If we make material changes to this privacy policy, we will update this page and note the new effective date. We encourage you to review this page periodically.

## Contact

If you have questions about this privacy policy or your data, contact us at:

[support@wainwrightcompanion.co.uk](mailto:support@wainwrightcompanion.co.uk)
