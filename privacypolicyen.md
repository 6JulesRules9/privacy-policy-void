# Privacy Policy — VOID

**Last updated: May 27, 2026**

---

## 1. Overview

This Privacy Policy explains how Julius Krassa ("we", "us", "our") collects, uses, and protects information when you use the mobile game **VOID** ("the App"). We take the protection of your personal data seriously and handle it in accordance with the General Data Protection Regulation (GDPR) and applicable data protection law.

---

## 2. Controller

The party responsible for data processing within this App is:

**Julius Krassa**  
Friedrich-Engels-Straße 42  
14482 Potsdam, Germany  
E-Mail: void@julius-krassa.de

---

## 3. Data We Collect and Why

### 3.1 Game Progress & Local Data (stored on your device only)

When you use VOID, the following data is saved **locally on your device** using Unity PlayerPrefs. This data never leaves your device unless you actively participate in online features (see Section 3.2).

- Player level, experience points (XP), Dark Matter (DM), Prestige Matter (PM)
- Highscores (Wave, Classic Ranked, Endless Ranked)
- Upgrade levels, active skill selection
- Booster inventory and active booster states
- Lifetime statistics (total playtime, fragments dodged, runs played, deaths, waves completed, DM/XP earned)
- Tutorial progress
- In-app purchase status (e.g. Streamer Pack ownership)
- Audio and performance settings (FPS cap, volume)

**Legal basis:** Art. 6(1)(b) GDPR — necessary to provide the core game functionality you requested.

---

### 3.2 Username & Leaderboard (optional for casual play, required for Ranked)

VOID offers a global leaderboard. To appear on it, you choose a **username** at the start of the game. A random 4-digit tag (e.g. `#4728`) is automatically assigned to make your name unique.

- Your **username and tag** are stored locally on your device and transmitted to our leaderboard backend (see Section 5.1) whenever a ranked run is completed.
- If you play any **Ranked mode** (Classic Ranked, Endless Ranked), submitting your score — and thus your username — to the leaderboard is a required part of that mode. If you do not wish your name to be visible, you can enable **Anonymous Mode** in Settings at any time. Your score will still be recorded and your ranking preserved, but your name will be replaced with "Anonymous" on all public leaderboards.
- The following data is transmitted per submission:

| Mode | Data submitted |
|------|----------------|
| General Leaderboard | Username#Tag, best wave, level, total playtime (seconds), best DM score, anonymous flag |
| Classic Ranked | Username#Tag, wave number, base score, combo multiplier, anonymous flag |
| Endless Ranked | Username#Tag, score, time survived (seconds), anonymous flag |

**Legal basis:** Art. 6(1)(b) GDPR — processing is necessary to provide the leaderboard feature you use; Art. 6(1)(a) GDPR (consent) for the initial username setup.

**Right to deletion:** You can delete your leaderboard entry at any time via Settings → Account → Delete Account. This sends a deletion request to our backend and removes your username from your device.

---

### 3.3 In-App Purchases & Subscriptions

VOID offers the following purchases, all processed exclusively through **Google Play Billing**:

- **Prestige Matter packages** — in-game currency purchased with real money (one-time consumable purchases)
- **VoidPass** — monthly subscription (€4.99/month or €9.99/month)
- **Streamer Pack** — one-time purchase (€9.99, removes the rewarded-ad requirement)

All other in-game items (Boosters, Bundles, etc.) are purchased using Prestige Matter, the in-game currency. No additional real-money purchases are required for these items.

**VOID does not process or store any payment information.** All billing, payment data, and transaction records are handled exclusively by Google Play. Please refer to Google's Privacy Policy for details on how payment data is handled.

We only receive confirmation from Google Play that a purchase was completed, and update your in-game state accordingly (locally on your device).

**Legal basis:** Art. 6(1)(b) GDPR — necessary to fulfil the purchase contract.

---

### 3.4 Advertising (Google AdMob & Unity LevelPlay)

VOID shows **rewarded ads** — short video advertisements that you can watch voluntarily in exchange for in-game rewards. Players who own the Streamer Pack do not encounter mandatory ads.

We use the following advertising SDKs:

**Google AdMob** (Google LLC, 1600 Amphitheatre Parkway, Mountain View, CA 94043, USA)  
AdMob may collect the following data on your device independently of VOID: Advertising ID (Google Advertising ID / GAID), device information (model, OS version, screen resolution), IP address, app interaction data.  
Google's Privacy Policy: https://policies.google.com/privacy  
You can reset or opt out of interest-based advertising via your Android device settings under **Privacy → Ads**.

**Unity LevelPlay / IronSource** (Unity Technologies)  
This SDK may be used for ad mediation and may collect similar data to AdMob.  
Unity's Privacy Policy: https://unity.com/legal/privacy-policy

For EU users, these SDKs are subject to GDPR consent requirements. Where required by law, a consent dialog will be presented before any personalised advertising is shown.

**Legal basis:** Art. 6(1)(a) GDPR — consent; Art. 6(1)(f) GDPR — legitimate interest in providing a free-to-play experience funded by optional advertising.

---

### 3.5 Device Identifier (Discord Verification only)

If you choose to use the optional **Discord verification** feature, the App reads your device's unique identifier to generate a one-time verification code locally. The first 4 alphanumeric characters of this identifier are incorporated (obfuscated) into the code.

**This identifier is never transmitted to our servers.** The code is generated entirely on your device and must be manually entered by you in our Discord server. Once verified, Discord's own data processing applies.

**Legal basis:** Art. 6(1)(a) GDPR — consent (you actively initiate this feature).

---

## 4. Data We Do Not Collect

We do not collect:

- Your real name, email address, phone number, or any account credentials
- Location data (GPS or otherwise)
- Camera or microphone data
- Contact lists or any other device data outside of what is described above

---

## 5. Third-Party Services & Data Transfers

### 5.1 Leaderboard Backend (Google Apps Script / Google LLC)

Our leaderboard runs on Google Apps Script, which is part of Google's infrastructure. When leaderboard data is submitted (see Section 3.2), it is transmitted to and stored on Google's servers, which may be located outside the European Union.

Such transfers to the USA are based on the EU–US Data Privacy Framework (where applicable) and Google's Standard Contractual Clauses (SCCs) pursuant to Art. 46(2)(c) GDPR. Google acts as a data processor on our behalf.

### 5.2 Google Play / Google LLC

All in-app purchases and subscriptions are processed by Google Play. Google is an independent data controller for payment processing.  
Details: https://policies.google.com/privacy

### 5.3 Discord Inc.

The Discord verification feature is entirely optional. If you choose to use it, any data you share with Discord is governed by Discord's Privacy Policy: https://discord.com/privacy

---

## 6. Offline Data Queue

If your device loses internet connectivity during a ranked run, your score submission is temporarily stored in a local queue on your device. It contains the same data as described in Section 3.2. This queue is flushed automatically once connectivity is restored, and the local copy is deleted upon successful submission.

---

## 7. Data Retention

- **Local data (PlayerPrefs):** Stored on your device until you delete the App or reset your progress via Settings → Reset All Data.
- **Leaderboard data (server-side):** Retained as long as you have an active leaderboard entry. You may request deletion at any time (see Sections 3.2 and 8).
- **Advertising data:** Governed by Google AdMob's and Unity LevelPlay's respective retention policies.

---

## 8. Your Rights (GDPR)

If you are located in the European Economic Area (EEA), you have the following rights regarding your personal data:

- **Right of access** (Art. 15 GDPR) — You may request information about what data we hold about you. Note: we do not store data linked to your real identity. To identify your data, please provide your in-game Username#Tag.
- **Right to rectification** (Art. 16 GDPR) — You may request correction of inaccurate data.
- **Right to erasure** (Art. 17 GDPR) — You may request deletion of your data. For leaderboard data: Settings → Account → Delete Account. For local data: Settings → Reset All Data.
- **Right to restriction of processing** (Art. 18 GDPR)
- **Right to data portability** (Art. 20 GDPR)
- **Right to object** (Art. 21 GDPR) — In particular regarding advertising (see Section 3.4).
- **Right to withdraw consent** — You may withdraw any consent at any time without affecting the lawfulness of processing prior to withdrawal.
- **Right to lodge a complaint** — You have the right to lodge a complaint with a supervisory authority, in particular in your country of residence. The competent authority for us is: **Landesbeauftragter für Datenschutz und Akteneinsicht Brandenburg**, Stahnsdorfer Damm 77, 14532 Kleinmachnow, Germany.

To exercise your rights, contact us at: **void@julius-krassa.de**

---

## 9. Children's Privacy

VOID is not directed at children under the age of 13 (or 16 in the EEA where applicable). We do not knowingly collect personal data from children. If you believe a child has provided us with personal data, please contact us and we will delete it promptly.

---

## 10. Security

All data transmitted to our leaderboard backend is sent over HTTPS. Local data is stored using Unity's PlayerPrefs system on your device. We implement appropriate technical measures to protect your data, though no transmission over the internet can be guaranteed to be completely secure.

---

## 11. Changes to This Policy

We may update this Privacy Policy from time to time. The updated version will be made available within the App and on our store listing. We encourage you to review it periodically. Continued use of the App after changes constitutes acceptance of the revised policy.
