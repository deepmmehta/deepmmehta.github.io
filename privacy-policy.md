# Privacy Policy — Gifter

**Last updated:** 19 June 2026  
**Effective date:** 19 June 2026

---

## 1. Who we are

Gifter is an AI-powered gift idea companion built for the Indian market. The app is developed and operated by Deep Mehta ("we", "us", "our"). You can reach us at **deepmehta49@gmail.com**.

---

## 2. What this policy covers

This Privacy Policy explains what information Gifter collects, how it is used, and your rights over that information. It applies to the Gifter mobile application available on Android (Google Play Store) and iOS (Apple App Store).

---

## 3. Information we collect

### 3a. Information you provide directly
- **People profiles** — names, relationships, birthdays, anniversaries, notes, and profile photos you add to "My People".
- **Gift history** — occasions, gift ideas, and reactions you log within the app.
- **Wishlists** — items you add to "My Wishlist" or to a saved person's wishlist.
- **Quiz answers** — your responses to the gift-finding questionnaire (recipient type, occasion, budget, preferences).

### 3b. Information generated automatically
- **App preferences** — whether you have completed onboarding, notification settings.
- **Device information** — device type and operating system version, used solely for rendering the app correctly.

### 3c. Information we do NOT collect
- We do not collect your name, email address, or phone number (there is no account or sign-in).
- We do not collect precise location data.
- We do not collect payment information.
- We do not use advertising SDKs or third-party analytics trackers.

---

## 4. Where your data is stored

**All personal data you enter into Gifter is stored locally on your device only**, using your device's secure local storage (AsyncStorage). We do not operate servers that store your personal data. If you delete the app, all data is permanently deleted.

A future version of Gifter will offer optional cloud backup (Supabase). This will be opt-in and clearly disclosed before any data leaves your device.

---

## 5. Third-party services

### 5a. AI gift suggestions (Anthropic / Gifter Proxy)
When you request gift ideas, the app sends the following to our secure Cloudflare Worker proxy:
- Gift recipient type (e.g. "Friend", "Parent") — no names
- Occasion and budget range
- General preferences you selected in the quiz

This request is forwarded to Anthropic's API (claude.ai) to generate gift suggestions. **No names, photos, contact details, or personally identifiable information are ever sent.** The Cloudflare Worker acts as a security layer — your Anthropic API key is never exposed to the app or to you.

Anthropic's privacy policy: [anthropic.com/privacy](https://www.anthropic.com/privacy)  
Cloudflare's privacy policy: [cloudflare.com/privacypolicy](https://www.cloudflare.com/privacypolicy/)

### 5b. Shopping links (Amazon, Flipkart, Myntra, Nykaa, Meesho, etc.)
Gift idea cards contain links to product searches on shopping platforms. When you tap a link, you are directed to that platform's website or app. Gifter participates in the **Amazon Associates Programme** — if you purchase a product via an Amazon link in Gifter, we may earn a small commission at no additional cost to you. This does not affect the gift ideas shown to you.

We do not share any of your personal data with these shopping platforms.

### 5c. Calendar and contacts (optional)
If you use "Import birthdays from contacts", Gifter requests access to your device contacts. **We only read birthday and name fields. We do not upload or transmit your contacts to any server.** Contact data is used only to pre-populate the "My People" section on your device.

If you use "Import from calendar", Gifter requests access to your device calendar. We only read event titles and dates relevant to birthdays and anniversaries. Calendar data is never uploaded.

### 5d. Push notifications (Expo / Firebase Cloud Messaging)
Gifter uses Expo's notification service to send birthday and festival reminders. A device push token is generated and stored locally. Expo's privacy policy: [expo.dev/privacy](https://expo.dev/privacy)

---

## 6. How we use your information

We use the information described above to:
- Display your saved people, gift history, and wishlists within the app
- Generate personalised AI gift suggestions for the occasions and budgets you specify
- Send birthday and festival reminder notifications (only if you grant permission)
- Improve the app based on aggregate, non-identifiable usage patterns

We do not sell your data. We do not share your data with advertisers. We do not build profiles for targeted advertising.

---

## 7. Your rights under the Digital Personal Data Protection Act, 2023 (India)

Under India's DPDP Act 2023, you have the right to:

- **Access** — know what personal data the app holds about you
- **Correction** — update or correct any inaccurate data (editable directly within the app)
- **Erasure** — delete all your data at any time via Settings → Delete all my data
- **Withdraw consent** — revoke calendar or contacts permission at any time via your device settings

Since all data is stored locally on your device, you exercise most of these rights directly within the app. For any queries, contact us at **deepmehta49@gmail.com**.

---

## 8. Children's privacy

Gifter is not directed at children under the age of 13. We do not knowingly collect personal information from children under 13. If you believe a child has provided personal information through the app, please contact us and we will delete it promptly.

---

## 9. Data security

All data is stored in your device's local encrypted storage. Data transmitted to our Cloudflare Worker proxy and to Anthropic's API is encrypted in transit using HTTPS/TLS. We do not store your personal data on any server.

---

## 10. Data retention

Your data remains on your device until you either delete the app or use the "Delete all my data" option in Settings. We do not retain copies of your data on external servers.

---

## 11. Changes to this policy

We may update this Privacy Policy from time to time. We will notify you of significant changes via an in-app notice. The "Last updated" date at the top of this page reflects the most recent revision. Continued use of the app after changes constitutes acceptance of the revised policy.

---

## 12. Contact us

If you have any questions, concerns, or requests regarding this Privacy Policy or your personal data, please contact:

**Deep Mehta**  
Email: deepmehta49@gmail.com  
App: Gifter (com.gifter.app)

---

*This Privacy Policy is governed by the laws of India.*
