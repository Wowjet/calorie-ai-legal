---
layout: default
title: Privacy Policy
---

# Privacy Policy

**Effective date:** June 21, 2026  
**Last updated:** June 21, 2026

This Privacy Policy describes how Biteva ("we", "our", "us") collects, uses, and shares information about you when you use the Biteva mobile application (the "Service").

By using Biteva, you agree to the collection and use of information in accordance with this policy.

---

## 1. Information we collect

### Account information
When you create an account, we collect:
- **Email address** (for authentication via email sign-in)
- **Apple account identifier** (if you sign in with Apple — a unique identifier provided by Apple, with email only if you authorize it)

### Profile information
To personalize your calorie targets and recommendations, we ask you to provide:
- First name (optional, used for personalization only)
- Year of birth
- Biological sex (used for metabolic rate calculation)
- Height and weight
- Fitness goal (e.g., lose weight, maintain, gain)
- Activity level
- Timezone (auto-detected from your device)
- Preferred units (metric or imperial)

### Meal data
When you log meals, we collect:
- Photos of your meals (uploaded to our servers for AI analysis)
- AI-generated estimates of calories, protein, carbohydrates, and fat
- Manual adjustments you make to AI estimates
- Meal timestamps and the date logged

### AI coach conversations
Biteva includes an optional in-app AI coach you can chat with. When you use it:
- We process the text of the messages you send and a short numeric summary of your recent activity (calories eaten, your daily target, the names and calories of your recent meals, and your most recently logged weight) in order to generate a reply.
- We do **not** store the content of your coach conversations on our servers. Your conversation history is kept only locally on your device.
- We record usage metadata (token counts, cost, timestamps) tied to your account, used to enforce per-user limits and monitor costs.

See "How we share your information" below for the third parties involved in generating coach replies.

### Device and usage data
To improve the Service and diagnose issues, we collect:
- Device type, operating system, and app version
- Crash reports and error logs (technical information about your device, without meal contents and no direct personal data such as your email or name; a hashed identifier is attached for debugging)

### We do NOT collect
- Your precise location (GPS)
- Your contacts
- Health data from Apple Health (unless you explicitly opt in to a future integration)
- Advertising identifiers (we do not show ads)

---

## 2. How we use your information

We use your information to:
- Provide the core calorie tracking and AI photo analysis Service
- Calculate your personalized daily calorie target (using a standard metabolic formula)
- Show you your meal history and daily progress
- Improve our AI analysis quality (aggregated, anonymized data only — see "Service improvement" below)
- Diagnose crashes and technical issues
- Respond to your support requests
- Comply with legal obligations

### Service improvement
We may use anonymized, aggregated meal data (with no personal identifiers) to improve the accuracy of our AI analysis. Individual photos are not used as training data for any third party AI model, and you can request that your data be excluded from this use by contacting us.

---

## 3. How we share your information

We share your information with the following third parties strictly as necessary to operate the Service:

| Service | Purpose | Data shared |
|---|---|---|
| **Supabase** (supabase.com) | Hosting, database, authentication, file storage | Account, profile, meal data, photos |
| **OpenAI** (openai.com) | AI analysis of meals (photo recognition and text nutrition lookup) | Meal photos and meal-related text (a food name, or a caption you add to a photo); no profile or account info attached |
| **OpenRouter** (openrouter.ai) | AI coach (chat) — routing your request to a language-model inference provider | Coach message text and a numeric context summary (calories, meal names, recent weight, targets); no account info attached |
| **DeepInfra, Fireworks AI, Together AI** (via OpenRouter) | Running the AI coach language model (inference) on US-based infrastructure | Same coach request data as the OpenRouter row above |
| **Sentry** (sentry.io) | Crash and error reporting | Crash logs, device type, app version; no meal or profile content and no direct personal data such as your email or name; a hashed identifier is attached for debugging |
| **Apple** (apple.com) | Sign in with Apple authentication (optional) | Apple account identifier only |

### How the AI coach uses these providers

When you send a message to the AI coach, your request is routed through **OpenRouter** to one of a fixed allowlist of US-based inference providers — **DeepInfra, Fireworks AI, or Together AI** — which run the open-weights DeepSeek V4 language model. The request is **not** sent to DeepSeek's own servers.

- We do **not** attach your email, name, or account identifier to coach requests. The request contains only the text of your recent coach messages and a numeric context summary (calories, meal names, recent weight, and targets).
- We set these requests to route only to inference providers that we instruct, via OpenRouter, not to retain or train on the input ("data collection: deny").
- Biteva does not log or store the content of your coach messages; we keep only usage metadata (token counts, cost, timestamps) tied to your account.
- Because your messages are free text, anything you type into the coach is included in the request that is processed. Please do not enter sensitive personal information you would not want processed by these providers.

We do NOT sell your personal information. We do NOT share your information with advertisers. We do NOT use your meal photos or coach messages to train any third party AI model.

We may disclose your information if required by law, court order, or to protect the rights, safety, or property of Biteva, our users, or others.

---

## 4. Where your data is stored

Your data is stored on servers operated by Supabase (which uses Amazon Web Services infrastructure). Data is primarily stored in the United States.

The third parties that perform AI processing for us are also located in the United States: **OpenAI** (meal photo and text analysis) and **OpenRouter** together with its allowlisted inference providers **DeepInfra, Fireworks AI, and Together AI** (AI coach). When you use these features, the relevant data described above is transferred to and processed in the United States.

If you are located outside the United States, your data will be transferred to and processed in the United States, where data protection laws may differ from those in your country.

---

## 5. How we protect your information

We use industry-standard security measures to protect your information:
- **Encryption in transit:** all data transmitted between your device and our servers uses HTTPS (TLS encryption)
- **Encryption at rest:** data stored in our database is encrypted at rest
- **Access controls:** only authorized personnel can access user data, and only as necessary for support or service operations
- **Row-level security:** our database enforces that you can only access your own data

No system is 100% secure. While we work hard to protect your information, we cannot guarantee absolute security.

---

## 6. Your rights and choices

### Account deletion
You can delete your account at any time from within the app:  
**Settings → Account → Delete Account**

When you delete your account, we delete all your personal information (account, profile, meals, photos) within 30 days. Anonymized aggregated data may be retained for service improvement.

### Access and correction
You can view and edit your profile information at any time in the app under **Settings → Profile**. To request a copy of all data we hold about you, contact us at the email below.

### Opt out of analytics
We do not collect usage analytics, so there is nothing to opt out of.

### California (CCPA) and other US state privacy rights
If you are a California resident (or resident of a state with similar privacy laws), you have the right to:
- Know what personal information we collect about you
- Access a copy of your personal information
- Request deletion of your personal information
- Opt out of any "sale" or "sharing" of personal information (we do not sell or share for cross-context behavioral advertising)
- Not be discriminated against for exercising your rights

To exercise these rights, contact us at the email below.

### Apple-specific rights
If you signed in with Apple, you can revoke Apple Sign-In access at any time via your Apple ID settings on iOS. This will also trigger deletion of your account on our side via Apple's required server-to-server notification.

---

## 7. Data retention

- **Active accounts:** we retain your data as long as your account is active
- **Meal photos:** retained while your account is active and deleted when you delete your account. We do not currently delete photos automatically after a fixed time period.
- **AI coach conversations:** not stored on our servers (kept only on your device); we retain only usage metadata (token counts, cost, timestamps) tied to your account
- **Deleted accounts:** we delete your personal information within 30 days of account deletion request
- **Crash and error logs:** retained for up to 90 days for diagnostic purposes

---

## 8. Children

Biteva is not intended for use by children under 13 years of age (or under 16 in the European Economic Area). We do not knowingly collect personal information from children. If you believe a child has provided us with personal information, please contact us and we will delete it.

---

## 9. Changes to this policy

We may update this Privacy Policy from time to time. When we do, we will:
- Update the "Last updated" date at the top
- Notify you via the app or by email for material changes
- Post the updated policy at this URL

Your continued use of the Service after changes take effect constitutes acceptance of the updated policy.

---

## 10. Contact

If you have questions about this Privacy Policy or your data, contact us at:

**Email:** supai_cal@outlook.com

For privacy-specific inquiries, you can also use the same address with the subject line "Privacy Request".

---

*This policy is provided in English and applies globally to all users of Biteva.*
