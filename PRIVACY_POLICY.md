# Privacy Policy

**Bankroll Buddy**

**Effective date: 17 August 2026**
**Last updated: 29 October 2026**
**Version: 2.2** (see Change log at the end of this document)

> **Note on the previous version.** The version of this policy dated January 2025 said that
> all data stayed on your device and that no data was sent to any server. That was wrong:
> Bankroll Buddy backs your data up to the cloud by default, and has done for some time.
> This version describes what the App actually does. We are sorry for the inaccuracy.

---

## 1. Who we are

The controller of your personal data is:

> **KAWI SOFTWARE AS**
> Organisation number: 933 580 873
> Fredrik Meltzers gate 13B, 5007 Bergen, Norway
> Email: **support@kawisoftware.com**

We have not appointed a Data Protection Officer; privacy questions go to the address above.

## 2. The short version

- Your data is stored **on your device**, and — unless you turn it off — is also **backed
  up to our cloud service** so you can restore it on a new device.
- To do that, the App **creates a pseudonymous account for you automatically** on first
  launch. You do not have to enter anything, and we do not know who you are unless you
  choose to sign in with Google or Apple.
- **You can turn cloud backup off** at any time in Settings, and you can **export or delete
  your data** at any time.
- Anything you deliberately publish through the social features (profile, shared sessions,
  comments) is visible to other users. Everything else is private to your account.
- We do not sell your data, we do not use it for advertising, and we do not track you
  across other companies' apps or websites.

## 3. What we process, why, and on what legal basis

### 3.1 Account identifier

When you first open the App it signs you in anonymously to Firebase Authentication and
receives a **pseudonymous user ID (UID)**. Your IP address and authentication tokens are
processed as an inherent part of that request. The UID is what links your backup, your
profile and your diagnostics together.

*Purpose:* to give you an account that can hold a backup.
*Legal basis:* performance of our contract with you (GDPR Art. 6(1)(b)).

If you choose to **sign in with Google or with Apple** — which we recommend, so that your
backup survives losing your device — we additionally receive your **email address** (or an
Apple private-relay address) and, where you allow it, your **name and profile picture**.
These are held in the Firebase Authentication record. Signing in is optional.

### 3.2 Your poker and gambling records (cloud backup)

**Cloud backup is on by default and can be turned off in Settings.** While it is on, the
data you enter is copied to our cloud database under your UID. That includes:

- **Sessions:** start and end time, buy-in, cash-out, rebuys, expenses, rake, game type,
  format, stakes, currency and exchange rate, hands played, your free-text notes and tags,
  live buy-in and chip-stack timelines, and breaks.
- **Location of play, where you record it:** the venue name, its postal address, its Google
  Place ID, and its **GPS coordinates**.
- **Wellbeing entries you choose to make:** mood rating, tilt flag and hours slept.
- **Tax fields you choose to enter**, such as whether a W-2G was issued and any amount
  withheld.
- **Bankrolls and transactions:** names, balances, currencies, deposits, withdrawals,
  adjustments and their notes.
- **Staking arrangements:** the names of backers, stakers and swap partners you enter,
  percentages, markup and notes.
- **Opponents you record:** the names or nicknames you give them, your free-text notes
  about them, play-style labels and tap-counter statistics.
- **Hands you record:** cards, board, positions, actions, results and notes.
- **Trips, session templates, streak and challenge state, and your settings.**

> **Please note:** if you enter another person's real name — as an opponent, a backer or a
> home-game player — you are entering someone else's personal data. Please only record what
> you need, and be aware that you are responsible for what you write about other people.

*Purpose:* to back up your records and restore them to your devices.
*Legal basis:* performance of our contract with you (Art. 6(1)(b)).
*Turn it off:* Settings → cloud backup. Turning it off stops further syncing.

Photos you attach to a session stay **on your device** — only the file reference is backed
up, not the image.

### 3.3 Your public profile and the social features

The social features (profile, clubs, leagues, the feed and comments) are **switched off
by default** and are only shown once you turn them on in Settings. If you use them, the
following is stored in our cloud database and is visible to other users according to your
privacy setting:

- display name, username and short bio;
- your **profile photo**, stored inside your profile record;
- who you follow and who follows you, and follower counts;
- any sessions you choose to share, and comments you post.

Profiles are private by default. You control what you share.

**Reporting, blocking and filtering.** Every comment, post and profile has a *Report* and
a *Block* option. A report stores who reported (your UID), who or what was reported, the
reason you chose, any details you typed and a short copy of the reported text, and is
emailed to our support mailbox; the reported person cannot see who reported them. Your
list of blocked players is stored privately under your account and also cached on your
device. Text you publish (comments, bios, display names, usernames) is checked by an
automated filter and may be removed or reset if it contains slurs or incitement; we log
that action together with an excerpt of the removed text. *Legal basis:* our legitimate
interest in keeping the community safe (Art. 6(1)(f)) and our legal obligations as a
platform for user content.

*Purpose:* to operate the social features you choose to use.
*Legal basis:* performance of our contract with you (Art. 6(1)(b)).

### 3.4 Subscriptions

We use **RevenueCat** to manage subscription entitlements. RevenueCat receives a purchase
identifier and your subscription status; we store that RevenueCat identifier alongside your
profile so the App knows whether Pro is active. **We never receive your card details** —
Apple and Google process the payment.

*Purpose:* to give you what you paid for, and to support you if billing goes wrong.
*Legal basis:* performance of our contract (Art. 6(1)(b)); legal obligation for accounting
records (Art. 6(1)(c)).

### 3.5 Crash reports, diagnostics and product analytics

To find and fix faults, the App sends:

- **Crash and error reports** (Firebase Crashlytics and our own error log): the error
  message and type, the full stack trace, the app version and build, the platform, the
  operating system version, a coarse device model, the screen you were on and the last few
  screens you visited. Crashlytics reports carry your UID.
- **Diagnostic events** (our own log): a category and event name, a short message, a
  severity, and the same device and screen context. These carry your UID.

- **Usage fields on your profile record** (so we can tell whether the App works for
  people and which versions are affected): the app version and build, the platform
  (iOS or Android), the language, whether you have Pro (`free` or `pro`), the time you
  finished onboarding and logged your first session, how many sessions you have saved and on
  how many days, whether notifications are enabled and simple counters of how many reminders
  were scheduled, tapped or switched off, whether you are signed in with Google
  or Apple, and when you were last active. They contain **no names, no email addresses, no
  amounts and no session content**. They are stored in your profile record, which other
  signed-in users of the App could technically read; they are not shown anywhere in the App.

- **Product analytics and screen recordings** (PostHog, from version 1.6): which screens
  you open and which features you use (for example "session saved", "paywall shown" or
  "report opened"), with coarse details such as the game type or the plan you picked, plus
  the app version, device model, operating system, language and the region set on your
  device. Your IP address is not stored and is not used to work out your location. These
  events carry your UID. The App
  also records how you move through its own screens (a "session replay": a sequence of
  pictures of the App, never of other apps). Everything you type into a text field
  (names, notes, venues, codes, feedback) is masked in these recordings; amounts and other
  text shown on screen can be visible, so switch on Discreet mode if you want amounts
  hidden. Recordings are kept for 30 days.

These are not marketing analytics and are not shared with advertisers. Stack traces and
context can occasionally contain fragments of text you typed; we do not seek that out and
we delete diagnostic data on the schedule in section 6.

*Purpose:* to keep the App working, diagnose failures and protect against abuse.
*Legal basis:* our legitimate interest in a functioning, secure product (Art. 6(1)(f)).
You may object to this — see section 7.

### 3.6 Community benchmarks (opt-in)

If — and only if — you switch on the benchmark feature, your already-backed-up results are
included in a server-side calculation that produces **anonymous** percentile distributions
across many players. Only aggregate figures are published, and only for groups above a
minimum size. No individual results are shown to anyone.

*Purpose:* to let you compare your results against other players.
*Legal basis:* your consent (Art. 6(1)(a)). You can withdraw it at any time in Settings.

### 3.7 What we do **not** do

- We do not sell personal data.
- We do not use your data for advertising, and there are no advertising SDKs in the App.
- We do not track you across other companies' apps or websites, and we do not ask for the
  iOS App Tracking Transparency permission.
- We do not read your photo library; the App only receives a photo when you pick one.

## 4. Who processes data for us

| Recipient | What they do | Where |
|---|---|---|
| **Google (Firebase Authentication, Realtime Database, Cloud Firestore, Crashlytics)** | Account identifiers, cloud backup, profiles, crash and diagnostic reporting | EU and United States |
| **RevenueCat, Inc.** | Subscription entitlement management | United States |
| **PostHog, Inc.** | Product analytics and session recordings (section 3.5) | United States |
| **Apple / Google Play** | Sell and bill subscriptions as merchant of record; they are independent controllers for the payment | Global |

Each acts as our processor under a data-processing agreement, except Apple and Google Play
in their role as sellers, where they act as independent controllers under their own privacy
policies.

**International transfers.** Some of these providers process data outside the EEA,
including in the United States. Those transfers rely on the European Commission's Standard
Contractual Clauses and, where applicable, the EU–US Data Privacy Framework. You can ask us
for details.

## 5. Public disclosure

Content you publish through the social features is visible to other users, and to anyone if
your profile is public. Please do not put anything in a public profile, bio, shared session
or comment that you would not want to be seen.

## 6. How long we keep data

- **Your backup and profile:** for as long as your account exists. If you delete your
  account (Settings → Account → Delete account), we delete them immediately from our
  databases, and they disappear from our backups within 90 days.
- **Reports and moderation records:** reports about other people, and the log of content
  removed by the filter, are kept for as long as needed to protect other users and for no
  longer than 12 months.
- **Crash and diagnostic data:** up to 90 days, then deleted or fully anonymised.
- **Product analytics:** events up to 12 months; screen recordings 30 days.
- **Aggregated benchmark statistics:** kept indefinitely, but they contain no personal data.
- **Accounting records for purchases:** as long as Norwegian bookkeeping law requires
  (currently five years).

If you turn cloud backup off, we stop syncing new data. Ask us if you also want the
existing backup erased — see section 7.

## 7. Your rights

Wherever you live, you can email **support@kawisoftware.com** to exercise any of these. If
you are in the EEA or the UK, they are rights under the GDPR:

- **Access** — a copy of the personal data we hold about you.
- **Rectification** — correction of anything inaccurate.
- **Erasure** — deletion of your account and data. See "Deleting your account" below.
- **Restriction** and **objection** — including objecting to the diagnostic processing in
  section 3.5, which relies on legitimate interests.
- **Portability** — your data in a machine-readable form. You can also export it yourself
  from the App at any time.
- **Withdraw consent** — for example the benchmark opt-in, at any time, without affecting
  processing already carried out.

We answer within 30 days. There is no charge.

### Deleting your account

You can delete your account yourself, inside the App: **Settings → Account → Delete
account**. The App first explains what will happen, asks you to confirm twice and, if you
signed in with Apple or Google, asks you to sign in again. Nothing is deleted if you cancel.

**Deleted:** your cloud backup (sessions, bankrolls, transactions, hands and everything
else in section 3.2); your profile, username, bio, photo, followers and the people you
follow; the sessions and comments you published; your club, league and home-game
memberships and the clubs and games you host; your referral records; your pseudonymous
account itself; and, on the device you used, the ledger and local backups. If you signed in
with Apple, we also revoke the Sign in with Apple token.

**Kept:** purchase records held by Apple, Google Play and RevenueCat under their own
policies and our bookkeeping duties (section 6); reports and moderation records for up to
12 months; diagnostic logs that contain only a pseudonymous ID, for up to 90 days; and the
likes you gave other people's publications, which carry no name or profile once your
account is gone. Copies in our backups are overwritten within 90 days.

**Deleting your account does not cancel your subscription.** Subscriptions are billed and
managed by Apple or Google; cancel yours in your store account settings, otherwise it will
keep renewing. The delete screen links to the right page.

**If you cannot open the App** (for example you uninstalled it, or lost the device), email
**support@kawisoftware.com** from the address on your Apple/Google sign-in, or follow the
instructions at our account-deletion page, and we will delete the account for you.
Anonymous accounts cannot be identified without the device, so for those the in-App option
is the only way.

**Complaints.** If you think we have handled your data badly, please tell us first. You may
also complain to the Norwegian Data Protection Authority, Datatilsynet
(https://www.datatilsynet.no), or to the supervisory authority where you live.

### Rights in other regions

- **California (CCPA/CPRA):** we do not sell or share personal information as those terms
  are defined, and we do not use it for cross-context behavioural advertising. You have
  rights to know, delete and correct — use the contact address above. We will not
  discriminate against you for exercising them.
- **Brazil (LGPD), Canada (PIPEDA), UK GDPR, and similar regimes:** the rights in this
  section are available to you on the same terms.
- **Nevada:** we do not sell covered information.

## 8. Security

Access to your backup is restricted to your own account by server-side security rules.
Data is encrypted in transit, and encrypted at rest by our infrastructure providers. We
keep our dependencies current and limit who can access production systems.

No system is perfectly secure. If a breach occurs that is likely to result in a risk to
your rights and freedoms, we will notify Datatilsynet within 72 hours and tell you directly
where the law requires it.

## 9. Children

The App is intended for adults aged 18 and over. We do not knowingly collect personal data
from anyone under 18. If we learn that we have, we will delete it. A parent or guardian can
contact support@kawisoftware.com.

## 10. Changes to this policy

We will update this policy when the App changes. For material changes we will give notice
in the App at least 30 days before they take effect, and we will update the version and
date above. Past versions are summarised in the change log below.

## 11. Contact

**KAWI SOFTWARE AS**
Organisation number: 933 580 873
Fredrik Meltzers gate 13B, 5007 Bergen, Norway
Email: **support@kawisoftware.com**

---

## Change log

| Version | Date | Summary |
|---|---|---|
| 2.2 | 2026-10-29 | Adds PostHog product analytics and screen recordings from version 1.6 (sections 3.5, 4 and 6). |
| 2.1 | 2026-10-04 | Describes the 1.4.0 behaviour: social features off by default; report, block and automated text filtering (section 3.3); the usage fields kept on the profile record (section 3.5); retention of reports (section 6); and the in-App "Delete account" flow with exactly what is deleted and kept (section 7). |
| 2.0 | 2026-08-17 | Complete rewrite for accuracy. The previous version stated that no data left the device and that we had no access to it; in fact the App creates a pseudonymous account on first launch and backs the user's records up to Firebase by default. This version identifies KAWI SOFTWARE AS as controller with a working contact address, describes every category of data actually processed (including venue GPS coordinates, wellbeing and tax fields, opponent names and notes, staking counterparties, profile photos and diagnostics), names the processors (Google Firebase, Crashlytics, RevenueCat), states the Art. 6 legal bases, retention periods, international-transfer safeguards, and the full set of data-subject rights. Removed the unverifiable transparency-report and "we cannot experience a data breach" claims. |
| 1.0 | 2025-01 | Initial version (inaccurate — see note at the top). |
