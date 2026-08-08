---
layout: default
title: Privacy Policy
description: What Bud Years collects, what it does not, and what you can turn off.
permalink: /privacy
---

# Privacy Policy

**DRAFT — not legal advice. Review with a qualified lawyer before publishing.**
Every `[SQUARE BRACKET]` below must be filled in or removed.

**Effective date:** `[DATE]`
**Last updated:** `[DATE]`
**Provided by:** `[LEGAL NAME]`, `[ADDRESS]`
**Contact:** `[PRIVACY CONTACT EMAIL]`

---

## The short version

Bud Years has no accounts. You never tell us your name, your email, or your
school. Everything about how you study — which courses you enrolled in, which
questions you got right, your streak — is stored **on your own device** and is
never sent to us.

We do not sell data. We do not run advertising. We do not track you across
other apps or websites.

Three things do leave your device, and all three are described in full below:
the app downloads its questions from our content server; in released versions
it sends a report if it crashes; and it can send anonymous usage statistics so
we can see how the app is being used and make it better.

The usage statistics are **optional in the UK and the EU/EEA**, where we ask
before switching them on, and can be turned off anywhere from
**Settings → Usage analytics**.

---

## 1. Who we are

Bud Years is provided by `[LEGAL NAME]` (“we”, “us”). For the purposes of the
UK and EU General Data Protection Regulation, we are the **data controller**
for the limited information described here.

## 2. What stays on your device and never reaches us

All of the following is written to storage on your phone or tablet and is not
transmitted anywhere:

- Which courses you are enrolled in
- Your position in each course, your daily plan, and the date you started
- Every answer you mark right or wrong, and your review queue
- Your practice streak and progress figures
- The downloaded copy of the questions themselves
- Your notification preference and the local schedule for the daily reminder
- Your time zone, read from the operating system so the reminder fires at 6 PM
  where you actually are

If you delete the app, all of it is deleted with it. There is no copy on a
server, so there is nothing for us to restore, export, or hand to anyone else.

## 3. What does leave your device

### 3.1 Downloading course content

The app fetches its catalogue and questions from Google Firebase Cloud
Firestore. These requests are **read-only** — the app has no ability to write
anything to our servers, and this is enforced by server-side security rules,
not merely by the app's own code.

As an unavoidable part of any internet request, Google's servers receive:

- Your IP address
- Standard request metadata (device type, operating system, timestamp)

We do not receive a report identifying you from this, and we do not attempt to
link these requests to any individual.

Some questions include diagrams, which are downloaded as images and cached on
your device. The server hosting those images receives your IP address in the
same way.

### 3.2 Crash reports

Released versions of the app use **Google Firebase Crashlytics**. If the app
crashes or hits an unexpected error, a report is sent containing:

- The technical stack trace of the failure
- Device model, operating system version, and app version
- A randomly generated installation identifier assigned by Firebase

We never attach your name, email, or any account identifier to a crash report,
because the app has none to attach. The identifier is specific to your
installation and is reset if you delete and reinstall the app.

Crash reporting is **disabled in development builds** and active only in
released versions.

**Legal basis (UK/EU GDPR):** our legitimate interest in diagnosing faults so
the app works for the students using it.

### 3.3 Usage analytics

We use **Google Firebase Analytics** to understand how the app is used in
aggregate. This is how we learn which subjects students actually study, when
they study, whether the daily reminder helps, and how far people get — the
questions that tell us what to build next.

**What is recorded**

- That the app was opened, and roughly when (morning, afternoon, evening,
  night), so we know when new content is worth publishing
- How long a session lasted, and how often the app is opened
- Which courses and subjects are enrolled in, and how many
- Whether a daily set or test was completed
- Whether the app was opened from the evening reminder
- How many vocabulary words have been learned, recorded in bands (for example
  “26–50”) rather than as an exact figure
- How long it takes to work through a course
- Whether the content being studied is free or paid
- Automatically: app version, device model, operating system version, and the
  country the request came from

**What is never recorded**

- Your name, email address, phone number, or any way to contact you
- The individual questions you answered, or whether you got them right
- Any advertising identifier. We do not collect one on any platform, we do not
  advertise, and we do not track you across other companies' apps or websites
- Your precise location. Country is inferred from the IP address of the
  request, which is then discarded

Firebase assigns a random **app instance identifier** so that two opens from
the same installation can be counted as one returning user rather than two new
ones. It is not linked to your identity, and it is reset if you delete and
reinstall the app.

**Your choice**

- **In the UK and the EU/EEA**, analytics is **off until you turn it on**. We
  ask once, in plain language, and “no” is remembered. Saying no does not limit
  the app in any way — every feature works identically.
- **Elsewhere**, analytics is on by default and can be switched off at any time
  from **Settings → Usage analytics**.
- Turning it off stops collection from that moment.

**Legal basis (UK/EU GDPR):** your consent. You may withdraw it at any time,
and withdrawing is as easy as giving it.
**Elsewhere:** our legitimate interest in understanding and improving the app.

### 3.4 The “rate this app” prompt

Occasionally the app asks your operating system to show a review prompt. That
request is handed to Apple or Google and handled entirely by them. We do not
see whether you reviewed the app or what you said.

## 4. What we do not do

- We do **not** collect your name, email address, phone number, photograph,
  contacts, location, or school.
- We do **not** require or offer an account, sign-in, or password.
- We do **not** show advertising, and we do not collect or use any advertising
  identifier on any platform.
- We do **not** sell, rent, or share personal information with data brokers.
- We do **not** track you across other companies' apps or websites, and the
  app contains no marketing or advertising trackers. Because of this, Apple's
  App Tracking Transparency prompt does not apply to Bud Years.
- We do **not** use your practice answers to build a profile, and we could
  not — they never leave your device. The analytics described in section 3.3
  count events, not people.

## 4A. Artificial intelligence

Some of the study content in Bud Years was drafted with the help of AI tools
and then checked, which is described in section 3A of the
[Terms of Use](/terms).

For privacy, the only points that matter are these:

- **Nothing about you is sent to an AI system.** The app does not run AI while
  you use it. There is no chatbot and nothing is generated in response to what
  you do.
- **We do not use anything from you to train an AI model**, and we do not
  provide anything from you to anyone else for that purpose. There is very
  little to provide: your answers and progress never leave your device at all.

## 5. Purchases

`[REMOVE THIS SECTION UNTIL PAID CONTENT IS ACTUALLY OFFERED.]`

If you buy access to a course, the purchase is processed entirely by Apple or
Google. We never see your card number, billing address, or payment details.
The app receives only a confirmation that a purchase exists, which it uses to
unlock content. Refunds are handled by the store you bought from, under their
policies.

## 6. Students, children, and age

**Bud Years is for students aged 13 and over**, from around 8th grade upward.
It is not directed to children under 13, we do not knowingly collect
information from anyone under 13, and it is rated accordingly on both stores.

If you believe a child under 13 has used the app in a way that sent us
anything, write to `[PRIVACY CONTACT EMAIL]` and we will delete whatever we
can identify.

That said, the honest position is that **there is very little to collect from
anyone, of any age**:

- There is **no account, no sign-in, no profile, no messaging, no
  user-generated content, no photo or contact access, and no social feature of
  any kind**. We do not ask any user for personal information.
- There is **no advertising**, and **no advertising identifier is collected on
  any platform**. We do not build advertising profiles and we do not share data
  with ad networks or data brokers.
- The only persistent identifiers involved are the random installation
  identifiers used by crash reporting (section 3.2) and usage analytics
  (section 3.3). They exist to keep the app working and to count usage in
  aggregate. They are not used to contact, profile, advertise to, or track
  anyone, and they are not disclosed for any other purpose.

**If you are under 18**

Most of our users are. Several countries treat everyone under 18 as a child
for data protection purposes, so:

- read this policy and the Terms of Use with a parent or guardian, and ask
  them to agree on your behalf;
- if you would rather send nothing at all, switch usage statistics off at
  **Settings → Usage analytics**. The app works identically either way, and no
  feature is withheld for saying no.

A parent or guardian may write to `[PRIVACY CONTACT EMAIL]` at any time to ask
what we hold and to have it deleted.

**India**

India's Digital Personal Data Protection Act, 2023 defines a child as anyone
**under 18** — not under 13 — and requires verifiable parental consent before a
child's personal data is processed. It also prohibits tracking and behavioural
monitoring of children.

Because most of our Indian users are under 18 by that definition, **usage
analytics are switched off by default in India** and stay off unless a parent
or guardian turns them on. Crash reports contain no personal data and no
behavioural information.

`[DEVELOPER: this paragraph describes behaviour the code must actually have.
India currently sits in the opt-out regime in analytics_consent.dart, meaning
analytics default ON. Either move India to ask-first, or do not publish this
paragraph.]`

**Canada**

Federal privacy law (PIPEDA) and, in Quebec, the *Act respecting the protection
of personal information in the private sector* as amended by Law 25, apply to
what little we collect.

Quebec's Law 25 requires that any technology used to profile, locate, or
identify a person be **switched off by default**. Usage analytics are therefore
**off by default in Quebec**, as they are in the UK and EU/EEA, and stay off
unless you turn them on. Crash reports contain no profiling information.

`[DEVELOPER: Quebec is not distinguishable from the rest of Canada by country
code alone. Either treat all of CA as ask-first, or read the locale's language
and region together. Do not publish this paragraph until the code does one of
them.]`

`[DEVELOPER: Law 25 requires a named person responsible for privacy protection,
whose title and contact must be published. Add them, or delete this sentence.]`

**Mexico**

Mexican data protection law requires a privacy notice (*aviso de privacidad*)
stating who is responsible, what is collected, why, and how you may exercise
your ARCO rights — **acceso, rectificación, cancelación y oposición**. This
document is that notice.

The responsible party is `[LEGAL NAME]`, `[ADDRESS]`. To exercise any ARCO
right, or to withdraw consent, write to `[PRIVACY CONTACT EMAIL]`. Because we
hold no information that identifies you, the usual answer will be that there is
nothing to access, correct, or delete beyond what uninstalling the app removes
— and we will say so rather than pretend otherwise.

`[DEVELOPER: Mexico replaced the LFPDPPP in 2025 and moved oversight away from
INAI. The requirements above are the long-standing ones and are unlikely to
have been dropped, but the current regulator, its name, and the complaint route
must be confirmed before publishing. Do not take this paragraph as current.]`

**Language**

This policy is written in English only. Quebec's *Charter of the French
Language* and Mexican consumer law both require consumer-facing documents to be
available in French and Spanish respectively.

`[DEVELOPER: translations are required before publishing in Quebec or Mexico.
The app itself is English-only, which is a separate question from the documents
and may matter to store review in those markets.]`

**A note for the UK**

The UK Children's Code (Age Appropriate Design Code) applies to services likely
to be accessed by under-18s, which Bud Years plainly is. We have written this
policy to be readable by the students who use the app, kept collection to the
minimum that answers a real question, defaulted analytics to **off** in the UK
and EU/EEA, and used no nudges to push anyone into turning it on.
`[A Data Protection Impact Assessment is REQUIRED under the Code. It must be
written, kept, and reviewed — it is not part of this policy.]`

## 7. Where information is processed

Our content and crash reporting are provided by Google Firebase. Information
handled by those services may be processed on servers in the **United States**
and other countries where Google operates, which may not offer the same level
of data protection as your own country.

Where required, transfers out of the UK or European Economic Area rely on the
European Commission's Standard Contractual Clauses, as incorporated into
Google's terms.

## 8. How long we keep things

- **On-device data:** until you delete it, or delete the app. You can clear
  your practice history at any time from **Settings → Clear practice history**.
- **Crash reports:** retained by Firebase Crashlytics for up to 90 days.
- **Usage analytics:** retained for `[2 or 14]` months, after which
  event-level records are deleted automatically by Firebase. Aggregate
  statistics that cannot identify any device may be kept longer.
- **Server request logs:** retained by Google under their own retention terms.

We keep nothing for longer than it is useful for the purpose it was collected
for, and we do not retain information indefinitely.

## 9. Your rights

Depending on where you live, you may have the right to access, correct,
delete, restrict, object to, or port your personal information, and to lodge a
complaint with a data protection authority.

In practice, for almost everything Bud Years touches, you already hold these
rights directly: the data is on your device, under your control, and deleting
the app deletes it. For crash reports, contact `[PRIVACY CONTACT EMAIL]` with
enough detail to identify the report and we will act on your request.

If you are in the UK, you may complain to the Information Commissioner's
Office (ico.org.uk). If you are in the EEA, you may complain to your national
supervisory authority.

**If you are in California:** we do not sell or share personal information as
those terms are defined by the CCPA/CPRA, and we do not use sensitive personal
information for inferring characteristics.

## 9A. If you write to us

There is one way you can give us personal information, and it is by choosing
to: emailing us a question, a correction, or a rights request.

If you do, we hold your message and your email address for as long as it takes
to deal with it, and for a reasonable period afterwards so we can recognise a
follow-up. We use it for nothing else. We do not add you to a mailing list —
there is no mailing list.

Please do not include anything sensitive in an error report. To tell us a
question is wrong we need the course, the subject, and the question. We do not
need to know anything about you.

## 10. Security

Content is delivered over encrypted connections (HTTPS/TLS). Data on your
device is protected by your device's own operating system security. Because we
hold no account and no server-side record of your studying, there is no
database of student information to breach.

## 11. Changes to this policy

If this policy changes materially, we will update the date at the top and note
the change in the app's release notes. Continued use after a change means you
accept the updated policy.

## 12. Contact

`[PRIVACY CONTACT EMAIL]`
`[LEGAL NAME]`, `[ADDRESS]`
