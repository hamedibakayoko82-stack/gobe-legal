# GoBe — Privacy Policy

**Last updated:** 22 August 2026

> This is the hosted version of GoBe's Privacy Policy. It is generated from and kept in sync with the in-app version.

## 1. Introduction

This Privacy Policy explains what information Hamed Bakayoko, an individual sole trader (trading as "GoBe," "we," "us," or "our") of 124 City Road, London EC1V 2NX, United Kingdom, collects through the GoBe mobile app (the "App"), how we use and store it, who we share it with, and the choices and rights you have. We are the data controller for your personal data and are registered with the UK Information Commissioner's Office (ICO) under registration number C1991885. This is a privacy notice, not a contract. Creating an account confirms that you were shown this notice; where we rely on consent, we ask for that consent separately.

GoBe's core feature lets you record a "Trail" — the path you walk, run, or travel — and drop "Traces" — short notes, optional photos or videos, any text you add on top of them, and pinned locations — along the way, then view them on a map. Because that feature depends on your real-world location and movement, this policy gives specific detail about location, motion, and content data.

## 2. Account & Sign-In Information

GoBe offers two ways to create and authenticate your account.

- Sign in with Apple — Apple shares your name and email address with us, including the private, randomly generated "relay" email Apple provides if you choose to hide your real email address.
- Email and username sign-up — we collect the email address you give us (confirmed with a one-time code sent to it), and the username and password you choose. Passwords are handled by our authentication provider and are never stored in plain text.

We use this information to create your GoBe account, to sign you in, and to identify you across sessions.

Authentication and session management are handled by Supabase (specifically its GoTrue auth service). Supabase issues and stores the access and refresh tokens that keep you signed in, and associates them with your account record.

## 3. Profile Information

When you set up your profile, we collect the display name and username you choose, your date of birth (the App requires you to confirm you are at least 16 years old), and, optionally, an avatar photo you upload. This information is shown to you within the App and, depending on the feature, may be visible to other users — for example, your display name and avatar on a Trail or Trace.

Being found. Other signed-in users can search for people by display name or username, so your profile can be reached by someone who has not crossed paths with you in the App. The App may also suggest your profile to other signed-in users as somebody they could connect with, either because you left a Trace near them or simply because you have an account; a suggestion shows the same details a search does and never says where you are or have been. Search results and suggestions show only your display name, username, avatar and profile line — never your location. Anyone you have blocked, and anyone who has blocked you, is excluded from your search results and you from theirs.

## 4. Location Information

GoBe is built around your real-world location. We request "precise" (full-accuracy) location access and background location access. Background access lets the App keep logging your location while you are actively recording a Trail, so a Trail captures your complete route even when your phone is locked or the App is in the background.

We use location data to: draw the path of the Trail you're recording; place Traces at an approximate location near where you created them; show your trails and traces on the map; improve the accuracy of recorded routes; and warn you before you post a Trace inside one of your protected areas. You can stop a recording, or revoke location permission at any time in iOS Settings, though doing so will prevent Trails and Traces from being recorded.

Approximate Traces. To avoid revealing exactly where you are, GoBe never stores the exact coordinate of a Trace. Before a Trace is saved — both on your device and on our servers — its location is rounded to a coarse grid (roughly 30 metres), so a Trace shares a place, not your precise whereabouts. Your recorded Trail path is more detailed, but Trails are private to you by default and are not shown to other users.

Protected areas. You can mark one or more places as "protected areas" — your home, your workplace, the gym, or anywhere else you'd rather keep off the map. You choose each area yourself on a map in the App; GoBe does not detect or learn them for you. Each protected area is stored only on your device — it is never uploaded to our servers or shared with anyone. When you go to post a Trace inside an enabled protected area, GoBe warns you first so you can choose to move away. You can add, rename, switch off, or delete your protected areas at any time in the App's profile screen.

Crossed paths (off by default). If you switch on "Crossed paths" in the App's profile screen, GoBe can tell you when another person walked a street that you also walked. This never shares your Trail with anyone. Instead, when you record a Trail after switching the setting on, our server reduces that Trail to a coarse grid of roughly 55-metre cells and keeps only those cells and the dates you were in them. A crossing is shown only when the other person has switched the same setting on, only for a cell that you walked yourself, and never with a date or a time of day — only a vague interval such as "a few days apart". The cells you pass through most often, which are typically your home or your workplace, are excluded and never form a crossing. Your Trail's route, its timestamps, and how far or how often you walk are never shown to another user. Switching the setting off deletes the cells we derived from your Trails. Crossed paths is off unless you turn it on, and Trails you recorded before you turned it on are never used for it.

Because GoBe records where you go, your location data can sometimes reveal sensitive ("special category") information about you — for example, a place of worship, a health clinic, or a demonstration. We do not seek to infer special category information about you, and we ask you not to use locations to reveal such information about yourself or others. For users we understand to be under 18, we apply more protective defaults (see "Children & Users Under 18").

## 5. Motion & Fitness Information

GoBe reads step-count data from your device's motion co-processor (via Apple's Core Motion / pedometer APIs) to show step counts associated with your activity. We do not access your broader Health app data beyond step counts surfaced through Core Motion.

## 6. Your Content

GoBe stores the content you create:

- Traces — text notes, an optional photo or short video, any caption or text you place on that photo or video (before or after posting), and an approximate (coarsely rounded) location near where you created them. We do not store the exact coordinate of a Trace.
- Trails — the sequence of GPS coordinates and timestamps that make up a recorded route, along with any title or metadata you add.

This content is stored on our servers (described below) so it can sync across your sessions and, where the App's sharing features allow it, be viewed by other users. Traces may be visible to other signed-in users; Trails are private to you by default.

Choosing photos. When you set a profile picture, Apple's system photo picker lets you browse your Photos albums without giving GoBe general access to your library. GoBe receives only the individual image you choose, and only that image is uploaded. If another photo feature asks for library permission, iOS lets you limit access to selected photos.

Reports and blocks. If you report a Trace, a note about a place, or a community or event, we keep a record of the report: your account, a copy of the reported content and its author, the reason you chose, and when you filed it. We keep the copy so the report stays reviewable even if the content is deleted afterwards. We use this to review the report and to meet our content moderation duties under the Online Safety Act 2023. Reports are visible only to us, never to other users. If you block someone, we store your block list (your account and the accounts you have blocked) so that their content stays hidden from you. Your block list is private to you, and the people you block are not told about it.

Friends, invites and your GoBe Score. When you add another user as a friend (a mutual "bond"), we store the connection between your two accounts so we can show it to you both and deliver friend requests. If you invite someone with your personal invite code, or join using a friend's code, we store the link between the inviting account and the joining account so we can attribute the referral. We also calculate a "GoBe Score" — a single number derived from your own activity (traces, trails, retraces, likes, comments, the people you are connected with, and successful invites) and the reactions your traces receive. Your GoBe Score is shown on your profile and is visible to other signed-in users; it does not reveal your location or the content of any private Trail.

Notes about places. You can leave one short note about a place on the map, with an optional score out of five. We store what you wrote, the score if you gave one, the name the place had when you wrote it, and the coordinate of the place itself (not of you). A note is shown to other signed-in users on that place's board alongside your username and profile picture, so please do not write anything there you would not want strangers to read. Writing a second note about the same place replaces the first. You can change or delete your note at any time, and notes are deleted with your account. Notes from people you have blocked, and from people who have blocked you, are not shown to you.

Communities and events. You can start a "community" (a standing group) or an "event" (a dated one) and pin it to a place on the map. We store its name, the short description and character you choose for it, the coordinate and radius you place it at, when an event starts and finishes, whether anyone may join or you approve each person, and who has joined or asked to join. A community or event you start is visible on the map to any signed-in user, so please do not give one a name or description you would not want strangers to read, and do not pin one to your home. Who has joined is shown to the people who have joined it, and to whoever started it; a request to join is visible only to you and to whoever started it.

What joining changes. When you leave a Trace you may choose to leave it to one community or event you belong to. Doing so lets everyone who has joined that community or event open that Trace from anywhere, instead of having to be near it. It changes nothing else: your other Traces keep their normal visibility, your Trails stay private, and nobody gains access to your location or your account. The choice is made on each Trace as you leave it and is never applied to a Trace retrospectively, so joining a group can never open Traces you left before you joined. If you leave a community or event, its Traces close to you again. An event only accepts a Trace left inside its area while it is on. Whoever started a community or event can call it off; the Traces left to it remain yours and stay on the map, but stop being shared through it.

Achievements. We record the milestones your account passes — for example your first Trace, ten Trails, or a number of steps walked — along with the date each was reached. They are worked out from activity we already hold (your traces, trails, steps, friends, the likes and retraces your traces receive, and your GoBe Score) and are shown on your profile to other signed-in users. An achievement shows what you have done, never where: it does not name a place or reveal the content of any Trace or Trail.

## 7. How We Use Your Information

We use the information described above to: operate the App's core features (recording trails, placing traces, displaying your map); create and secure your account; authenticate you across devices and sessions; display your profile and content to you and, where applicable, to other users; moderate content and keep the service safe; maintain and improve the App's reliability and features; respond to support requests; and meet legal obligations. We also use it to send you notifications about activity that involves you — such as a like, comment, or retrace on your trace, or a friend request — and occasional GoBe progress or exploration prompts such as territory recaps, ranking movement, milestone prompts and return reminders. These are controlled together by the single Notifications switch in the App's profile screen and by iOS Settings. GoBe's progress and exploration prompts use your activity, GoBe Score and area standing.

Email. We use the email address on your account for two different purposes, and only one of them is optional.

- Service email, which we send because you have an account: confirming your address, resetting your password, security notices, a reply when you contact us, and notice of a material change to this policy or our Terms. These are not marketing and cannot be switched off while your account exists.
- Marketing email, which we send only if you ask us to: occasional word about new features and what's happening near you, no more than once a month. This is off unless you turn on "Emails from GoBe" under Settings → Notifications in the App. Every marketing email carries a one-click unsubscribe link that works without signing in, and you can also switch it off in the App at any time. We record when you turned it on, which version of this policy was in force at the time, and every later change, so that we can show the consent we are relying on.

We do not sell your personal information, we do not share your email address with advertisers or data brokers, and we do not use your location or content data for third-party advertising.

## 8. Our Legal Bases for Using Your Data

Where the UK GDPR, EU GDPR, or a similar law requires a legal basis, we rely on:

- Contract — to create and run your account and provide the core features you request.
- Consent — for device access to precise and background location, motion/step data, optional promotional notifications, and marketing email, where consent is required. Marketing email is sent only with your consent under regulation 22 of the Privacy and Electronic Communications Regulations 2003; we do not rely on the "soft opt-in" exception, because GoBe does not sell you anything. You can withdraw consent in the App, in iOS Settings, or through the unsubscribe link in any marketing email, without affecting earlier lawful processing, although the related feature may stop working.
- Legitimate interests — to secure and improve GoBe, prevent abuse, calculate service statistics, and moderate content, after balancing those interests against your rights.
- Legal obligation — to comply with privacy, safety, consumer, and other applicable laws and lawful requests.
- Vital interests or public interest — only in the exceptional circumstances in which applicable law permits and the basis genuinely applies.

Where another privacy law uses different grounds, we process information only for purposes permitted by that law.

## 9. Where Your Information Is Stored

GoBe's backend runs on Supabase. Your account record, profile, trails, and trace data are stored in a Supabase Postgres database. Photos you upload — avatars and trace photos — are stored in Supabase Storage, in buckets named "avatars" and "post-images." Our Supabase project is hosted in the EU (eu-central-1 / Frankfurt region).

These photo storage buckets are private: photos are not publicly accessible and can only be retrieved by signed-in users through an access-controlled endpoint, governed by row-level security policies. A photo cannot be viewed by someone simply because they have guessed or obtained a storage link.

## 10. Third Parties & Sub-Processors

We share information with a limited number of service providers who help us run GoBe:

- Apple — provides "Sign in with Apple" authentication and, if you choose, relays your email through its private-relay service.
- Supabase — provides our database, file storage, and authentication (GoTrue) infrastructure, and stores the data described in this policy on our behalf, hosted in the EU.
- PostHog — provides anonymous usage statistics and crash reporting, hosted in the EU. We record a small set of app events (for example that a trail was started, or that the app crashed and where in the code it happened) so we can fix problems and see which features are used. These events are anonymous: we configure PostHog so that no user profile is built about you, and no event ever includes your location, your content, your name, or your email.
- Cloudflare — provides DNS, content delivery, and security filtering for our public website, which hosts this policy, our terms, and our support pages. When you visit that website, Cloudflare processes your IP address and basic request information (such as the page requested and your browser type) in order to serve the page and to block abusive traffic. Cloudflare has no access to your GoBe account, trails, or traces.

We do not share your personal information with advertisers or data brokers. We may disclose information if required by law, to protect the rights and safety of GoBe or its users, or in connection with a sale of the business, in which case we'll make reasonable efforts to notify you.

## 11. Data Retention

We keep your account, profile, trail, and trace data for as long as your account is active, so the App can show you your history and keep your content in sync. If you delete your account (see below), we delete or anonymise this data within 30 days, except where we are required to keep limited records longer for legal, security, or fraud-prevention purposes — in which case we keep only what is necessary, for no longer than required.

Marketing consent records. If you turn marketing email on or off, we keep a dated record of that change for as long as your account exists, so that we can evidence the consent we relied on when we sent you something. The record holds the change itself, its date and how it was made — it does not hold the content of any email. It is deleted with your account.

## 12. Your Rights & Choices

Depending on where you live, you may have rights to know or access the information we hold about you; correct, delete, or receive a portable copy of it; object to or restrict processing; withdraw consent; opt out of certain disclosures, targeted advertising, or profiling; appeal a refused request; and complain to a privacy authority. We do not sell personal information or use it for third-party targeted advertising.

You can review and edit profile information in the App, delete your account using "Delete Account," revoke device permissions in iOS Settings, and stop marketing email either with the unsubscribe link in any such email or by switching off "Emails from GoBe" under Settings → Notifications. You may also email contact@gobeapp.co.uk. We may verify your identity before completing a request and will respond within the period required by the law that applies to you. We will not discriminate against you for exercising a privacy right.

## 13. Children & Users Under 18

GoBe is not for anyone under 16. We use the date of birth entered at sign-up to enforce that rule and do not permit an account to be created when the stated age is under 16. If we discover that we collected information from an under-16 user, we will close the account and delete the information unless law requires limited retention.

For users aged 16 or 17, we apply high-privacy defaults, minimise collection, and limit location sharing by default. In the UK we take account of the ICO's Age Appropriate Design Code. In the United States, GoBe is a general-audience service and is not directed to children under 13; if we gain actual knowledge that we collected a child's information, we will delete it and take the action required by COPPA. Parents or guardians may contact contact@gobeapp.co.uk.

## 14. Security

We use reasonable technical and organisational measures — including encrypted connections (HTTPS/TLS) and database and storage access controls — to protect your information. Supabase maintains its own security programme for the systems it operates on our behalf. No method is completely secure. If a personal data breach occurs, we will notify affected people and the appropriate authorities where and within the time required by applicable law.

## 15. International Data Transfers

Our primary Supabase servers are hosted in the EU (eu-central-1 / Frankfurt). Information may also be processed in other countries by the providers listed above. Depending on the originating country, we rely on adequacy decisions, contractual safeguards such as approved standard contractual clauses or the UK International Data Transfer Agreement/Addendum, or another lawful transfer mechanism. You may contact us for information about the safeguard relevant to your data.

## 16. Changes to This Policy

We may update this Privacy Policy when our practices or legal obligations change. We will update the "Last Updated" date and notify you in the App or by email when a change is material. If a change requires consent, we will ask for it separately. Continued use is not treated as consent to new processing that legally requires consent.

## 17. Regional Privacy Information

United Kingdom. UK residents may exercise UK GDPR rights and complain to the Information Commissioner's Office at ico.org.uk.

European Economic Area. If the EU GDPR applies, you may exercise the rights described above and complain to the supervisory authority where you live, work, or believe an infringement occurred. Before specifically offering GoBe to people in the EEA, we will publish the details of any EU representative required by Article 27. EEA launch remains subject to completing that appointment assessment.

United States. Residents of states with applicable comprehensive privacy laws may request access, correction, deletion, or portability and may opt out of sale, targeted advertising, or qualifying profiling as provided by their state law. GoBe does not sell personal information, share it for cross-context behavioural advertising, or use it for third-party targeted advertising. We process precise route location only to provide requested GoBe features, security, and legal compliance. Where required, you may appeal a decision by replying to our response. California residents may also request the categories of information, sources, purposes, and recipients described in this Policy. These rights apply when the relevant law covers GoBe.

Canada. You may request access to and correction of personal information and challenge our compliance through the contact below. We use consent or another lawful basis recognised by applicable federal or provincial law.

Brazil. Where the LGPD applies, you may request confirmation of processing, access, correction, anonymisation, blocking or deletion where applicable, portability, information about sharing, withdrawal of consent, and review of qualifying automated decisions. Contact is available at contact@gobeapp.co.uk.

Australia. Where the Privacy Act 1988 and Australian Privacy Principles apply, you may request access or correction and complain to us. If unresolved, you may contact the Office of the Australian Information Commissioner.

Japan. Where the APPI applies, you may request disclosure, correction, suspension of use, or deletion as provided by law and ask about cross-border handling through the contact below.

## 18. Contact Us

If you have questions about this Privacy Policy, want to exercise your privacy rights, or want to request deletion of your data, contact Hamed Bakayoko, trading as GoBe, of 124 City Road, London EC1V 2NX, United Kingdom, at contact@gobeapp.co.uk.
