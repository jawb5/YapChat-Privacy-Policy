# YapChat Privacy Policy

**Last updated: 22 July 2026**

YapChat ("the app") is built and operated by James Woodhall-Black ("we", "I"). This policy explains what data the app handles, where it goes, and your choices. The short version: **your chats live on your device, there are no accounts, and we never sell data.**

## Third-party AI processing — in short

YapChat's analysis is performed by **Anthropic PBC** ("Anthropic"), the provider of the Claude AI models, acting as our data processor.

| Question | Answer |
|---|---|
| **What is sent?** | The **text of the messages** in the chat you selected, the **timestamps** of those messages, and the **sender names exactly as they appear in your exported file**. Nothing else. |
| **Who is it sent to?** | Anthropic PBC, via our own relay server (Cloudflare Workers). No other AI provider receives your data. |
| **How is it collected?** | Only from a chat export or screenshots **you** actively import, and only when **you** trigger an AI feature (a report, an AI chat message, or building Memory). |
| **When is permission asked?** | Before anything is sent. The app shows an in-app consent screen after your first import that names Anthropic and lists exactly what will be sent. **If you do not agree, no message data leaves your device and the imported chat is deleted.** You can withdraw consent at any time by deleting your data in Settings. |
| **What is it used for?** | Solely to generate the report, AI chat reply, or Memory dossier you asked for. |
| **Is it used to train AI?** | **No.** Under Anthropic's commercial terms, data submitted through their API is not used to train their models. |
| **Retention by Anthropic** | Anthropic may retain inputs and outputs for a limited period for trust-and-safety purposes under their commercial terms, after which they are deleted. |
| **Equivalent protection** | Anthropic is contractually bound by their Commercial Terms of Service and Data Processing Addendum to protect this data to a standard equivalent to that described in this policy, to process it only on our instructions, and not to sell it or use it for advertising. Details: https://www.anthropic.com/legal/commercial-terms and https://privacy.anthropic.com |

**What is never sent to Anthropic or anyone else:** your name, email address, phone number, contacts, photos, or location. Screenshots are read using Apple's on-device text recognition and the images themselves are never uploaded. No account is created.

## What YapChat does with your chats

- **Imported chats stay on your device.** When you import a WhatsApp export or screenshots, the messages are parsed and stored locally on your iPhone. We do not run servers that store your conversations.
- **Screenshot text recognition happens on your device.** Reading text out of screenshots uses Apple's on-device recognition — the images are not uploaded anywhere.
- **AI features send transcript excerpts for processing.** When you generate a report or use the AI chat, relevant parts of the selected conversation are sent over an encrypted connection, through our relay server, to Anthropic (the provider of the Claude AI model) to produce the response. This happens only when you actively use an AI feature, and only for the conversation you chose.
  - Anthropic processes this data to generate the response and does **not** use it to train its models. It may be retained briefly by Anthropic for trust-and-safety purposes in line with their commercial terms, then deleted.
  - Our relay server does not store your messages. It passes the request through and records only anonymous usage counts (see below).

## Data we do collect

- **Anonymous usage limits.** The app generates a random device identifier (not linked to your name, phone number, or Apple ID). Our relay server keeps a count of AI requests and their approximate cost against this identifier to enforce fair-usage limits. These records are deleted automatically after 45 days.
- **Purchases.** Subscriptions are handled by Apple and our subscription partner RevenueCat. RevenueCat receives purchase receipt data and an anonymous identifier so your subscription unlocks correctly. We never see your payment details — Apple handles all billing.
- **Product analytics (Amplitude).** We use Amplitude, a third-party analytics provider, to understand how the app is used — for example which onboarding steps people complete, which features they use, and whether AI requests succeed or fail. These events contain **no message content**. They are tied to the same random device identifier described above and, if you subscribe, to the anonymous subscription identifier from RevenueCat, so we can measure conversion and diagnose problems. They are never linked to your name, email, or phone number. Amplitude processes this data on our behalf under their terms.
- **Crash and error diagnostics.** We may use a crash-reporting service to record anonymous technical details when the app crashes or an operation fails, so we can fix bugs. These reports contain no message content.

## Every third party we share data with, and their protection

We use four processors. Each is contractually bound, under the agreements linked below, to process this data **only on our instructions**, to protect it to a standard **equivalent to that described in this policy**, and never to sell it or use it for advertising. We share data with no one else.

| Processor | What they receive | Why | Their terms |
|---|---|---|---|
| **Anthropic PBC** | Message text, timestamps and sender names from the chat you chose | To generate your report, AI replies and Memory | https://www.anthropic.com/legal/commercial-terms · https://privacy.anthropic.com |
| **Cloudflare, Inc.** | The same request in transit, plus the anonymous device identifier and usage counts | Our relay server, which holds the AI key and enforces fair-usage limits. It does not store your messages | https://www.cloudflare.com/privacypolicy/ |
| **RevenueCat, Inc.** | Purchase receipt data and an anonymous subscriber identifier. **No message content** | To unlock your subscription and purchases correctly | https://www.revenuecat.com/privacy/ |
| **Amplitude, Inc.** | Feature and funnel events tied to the anonymous device identifier, and approximate location derived from IP (country/city level). **No message content** | To understand which parts of the app work and diagnose failures | https://amplitude.com/privacy |

Apple processes all payments; we never receive your payment details.

## What we never do

- We never sell or share your data with advertisers.
- We never read, store, or transmit your conversations except as described above (your explicit use of an AI feature).
- We show no third-party ads.
- We do not require an account, email address, or phone number.

## The other people in your chats

Chats you import naturally include messages written by other people. That content is processed only as described above and stays under your control on your device. Please be thoughtful about the conversations you import and share — share cards you create are shared entirely at your discretion.

## Data deletion

- **On-device data:** delete a person from your roster, or use **Settings → Delete all data** (which also removes your iCloud backup), or delete the app — the imported chats, reports, AI conversations and Memory go with it.
- **Withdrawing AI consent:** deleting all data in Settings also clears your consent, so the app will ask again before anything is sent next time.
- **Server-side usage records:** these expire automatically after 45 days. To request earlier deletion, email us (address below) — include the "device ID" shown in the app's settings so we can find the anonymous record.

## Children

YapChat is not directed at children and is rated for users 17+.

## Your rights (UK/EU)

If you are in the UK or EU, you have the right to access, correct, or erase personal data we hold, and to complain to your supervisory authority (in the UK, the ICO). Given the design above, the only personal data we hold server-side is the anonymous usage record. Contact us to exercise any right.

## Changes

If we change this policy we will update this page and the "last updated" date. Material changes will be flagged in the app.

## Contact

**James Woodhall-Black**
Email: YapChatMobileApp@gmail.com
