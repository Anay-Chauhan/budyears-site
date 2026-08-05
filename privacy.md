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

## 5. Purchases

`[REMOVE THIS SECTION UNTIL PAID CONTENT IS ACTUALLY OFFERED.]`

If you buy access to a course, the purchase is processed entirely by Apple or
Google. We never see your card number, billing address, or payment details.
The app receives only a confirmation that a purchase exists, which it uses to
unlock content. Refunds are handled by the store you bought from, under their
policies.

## 6. Students, children, and age

Bud Years is rated **4+** and carries material for competitions that primary
and middle school students enter — Math and Science Olympiad participants are
often nine or ten years old. We therefore expect a meaningful number of users
to be **under 13**, and we do not pretend otherwise.

Under the US Children's Online Privacy Protection Act (COPPA), that makes Bud
Years a **mixed-audience service**: not aimed exclusively at young children,
but knowingly used by some. We treat every user as though they might be a
child.

**What that means in practice**

- There is **no account, no sign-in, no profile, no messaging, no user-generated
  content, no photo or contact access, and no social feature of any kind**. We
  do not collect personal information from anyone, of any age, so there is
  none to collect from a child.
- There is **no advertising**, and **no advertising identifier is collected on
  any platform**. We do not build advertising profiles and we do not share data
  with ad networks or data brokers.
- The only persistent identifiers involved are the random installation
  identifiers used by crash reporting (section 3.2) and usage analytics
  (section 3.3). Under COPPA these are used **solely to support the internal
  operations** of the app — keeping it working, diagnosing faults, and
  understanding in aggregate how it is used so we can improve it. They are not
  used to contact, profile, advertise to, or track any child, and they are not
  disclosed to third parties for any other purpose.
- Bud Years is **not** submitted to Apple's Kids Category or Google Play's
  Designed for Families programme. It is general study material that children
  also use, and we do not present it as a children's product.

**For parents and guardians**

You do not need to create anything or consent to anything for your child to
use Bud Years, because there is nothing about them for us to hold. If you would
prefer no usage statistics at all, switch them off at
**Settings → Usage analytics**; the app works identically either way.

If you believe we hold personal information about a child, write to
`[PRIVACY CONTACT EMAIL]` and we will delete it.

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
