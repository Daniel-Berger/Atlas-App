# Privacy Policy

*Last updated: November 23, 2026*

Atlas Global Intel ("Atlas," "we," "our," or "us") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, share, and safeguard information when you use the Atlas apps for iOS, iPadOS, and Android (the "App").

## Summary

- Atlas does not require an account. We do not ask for your name, email address, or phone number.
- When you use **Ask Atlas**, the text of your questions is sent to third-party AI providers (**Anthropic** and **OpenAI**) to generate answers. See [Ask Atlas and Third-Party AI](#ask-atlas-and-third-party-ai).
- We use analytics (**Mixpanel**, **Google Firebase**) and crash reporting (**Firebase Crashlytics**) to understand how the App is used and to fix problems. This data is linked to an anonymous ID, not to your identity.
- We do not sell your data, use it for advertising, or track you across other companies' apps and websites.

## Information We Collect

**Anonymous app ID.** When you first open Atlas, we create an anonymous session using Firebase Authentication. This gives the App a random identifier. It is not linked to your name, email address, or any other account.

**Ask Atlas questions.** When you ask Atlas a question, we process the text of your question and the earlier messages in the same conversation. Details are in the next section.

**Usage analytics.** We collect information about how the App is used, such as the screens you view, the features you use, the buttons you tap, your subscription status, the App version, your device model and operating system, and an approximate location (city and country) that our analytics provider derives from your IP address. This information is linked to the anonymous app ID.

**Crash and diagnostic data.** If the App crashes or encounters an error, we collect technical diagnostics (such as the device model, operating system version, and a stack trace) to fix the problem.

**Push notification tokens.** If you enable notifications, your device provides a push token. We store it with the anonymous app ID and your platform so we can deliver the notifications you have opted into, such as breaking news alerts.

**Purchases.** Subscriptions are processed by Apple (App Store) or Google (Google Play). We never receive your payment card or billing details. We receive confirmation of your subscription status so we can unlock premium features.

**Ad attribution (iOS).** If you installed Atlas after tapping an Apple Search Ads advertisement, the App may retrieve attribution information from Apple's AdServices framework (for example, which ad campaign led to the install). This does not use the advertising identifier (IDFA) and does not track you across other apps.

**Device attestation.** We use Firebase App Check (with Apple App Attest / DeviceCheck on iOS and Google Play Integrity on Android) to verify that requests to our services come from a genuine copy of Atlas. This does not identify you personally.

**Location.** Atlas does not request access to your device's location.

**Locally stored data.** Your Ask Atlas conversation history, alert rules, watched countries, and app preferences are stored on your device.

## Ask Atlas and Third-Party AI

Ask Atlas answers your questions using large language models operated by third-party AI providers.

- **What is sent:** the text of your question, the earlier messages in the same conversation (so the AI can follow up), and relevant Atlas news and risk data used to ground the answer.
- **Who receives it:** your request travels from the App to our servers (Google Firebase Cloud Functions and our automation server), which forward it to **Anthropic** (Claude), our primary AI provider. If Anthropic is unavailable, the request is sent to **OpenAI** instead.
- **What is not sent:** we do not send your name, email address, anonymous app ID, IP address, or device identifiers to the AI providers.
- **How the providers handle it:** the providers process your request to generate an answer, under their own terms and privacy policies ([Anthropic](https://www.anthropic.com/legal/privacy), [OpenAI](https://openai.com/policies/privacy-policy)). Under their commercial API terms, they do not use API inputs to train their models by default.
- **What we keep:** our servers keep a short log of each request's category (for example, the topic and whether it succeeded) for up to 90 days, to monitor reliability. We do not store the text of your questions or answers on our servers. Your conversations are saved only on your device, and you can delete them in the App.
- **Your choice:** Ask Atlas is optional. If you do not want your questions processed by third-party AI providers, do not use Ask Atlas. The rest of the App works without it.

Please do not include sensitive personal information in your questions.

## How We Use Information

We use the information described above to:

- Provide and operate the App's features (event tracking, intelligence briefs, risk scores, Ask Atlas)
- Deliver push notifications you have opted into
- Verify subscriptions and unlock premium features
- Protect our services from abuse (rate limiting and device attestation)
- Understand usage patterns, measure our marketing, and improve the App
- Diagnose crashes and fix bugs

## Data Sharing

We do not sell, rent, or share your information for advertising. We share information only with the following service providers, solely to operate and improve the App:

- **Anthropic** and **OpenAI** (generating Ask Atlas answers, as described above)
- **Mixpanel** (product analytics)
- **Google Firebase** (anonymous authentication, analytics, crash reporting, push notifications, app integrity, and cloud hosting)
- **Mapbox** (map rendering)
- **Apple** (App Store purchases, push notifications, App Attest, Search Ads attribution)
- **Google Play** (Google Play purchases and Play Integrity, on Android)
- **Hostinger** (hosting for our automation server, which relays Ask Atlas requests)

These providers process data in accordance with their own privacy policies and our instructions. We may also disclose information if required by law.

## Data Retention

- Ask Atlas request logs (categories only, no question text): up to 90 days.
- Analytics and crash data: retained according to Mixpanel's and Google Firebase's standard retention policies.
- Push tokens: kept until you disable notifications or the token expires.
- On-device data (including Ask Atlas conversations): kept until you delete it in the App or delete the App.

## Data Security

We use industry-standard security measures, including encrypted connections (TLS) for all network requests, device attestation for our services, and secure on-device storage for sensitive tokens.

## Children's Privacy

Atlas is not directed at children under the age of 13, and we do not knowingly collect information from children under 13.

## Your Rights and Choices

- **Ask Atlas:** using Ask Atlas is optional, and you can delete conversations in the App.
- **Notifications:** you can turn notifications off at any time in the App's settings or your device settings.
- **Deleting data:** deleting the App removes all data stored on your device. To ask us to delete analytics data associated with your anonymous app ID, or to ask any question about your data, contact us at the address below.
- Depending on where you live (for example, in the EU, the UK, or California), you may have additional rights to access, correct, or delete your personal data. Contact us to exercise them.

## Changes to This Policy

We may update this Privacy Policy from time to time. We will post the updated policy here and update the "Last updated" date. For material changes, we will also notify you within the App.

## Contact Us

If you have questions or concerns about this Privacy Policy, contact us at:

[daniel@pomonaappstudio.com](mailto:daniel@pomonaappstudio.com)
