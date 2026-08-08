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
we can see how the app is being used and make it better. **Both of the last two
can be switched off** at **Settings**.

The usage statistics are **off unless you turn them on or tell us you are 13
or over**, and can be switched off again at any time from **Settings → Usage
analytics**. Nothing in the app depends on them: every feature works
identically either way, so if you would rather send nothing, that is a
complete answer.

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
- Whether you have told us you are 13 or over. The **answer**, not the year of
  birth you gave to reach it, and not a date. See section 3.3
- If that answer was “under 13”, the year we should ask again — which is the
  year you turn 14. It is your birth year plus fourteen, so anyone who read it
  could work the birth year out; we keep it because it is the date the answer
  stops being reliable, not because it hides anything. It is deleted the moment
  it is reached

If you delete the app, all of it is deleted with it.

**One qualification, because it would otherwise be misleading.** Both Apple and
Google back up app data as part of their ordinary device backups — iCloud
Backup and Android Auto Backup — and we leave that switched on, so that a
student who replaces a phone does not lose months of work. That backup lives in
**your** account, under your own credentials and your own encryption. We cannot
read it, we are not sent it, and we cannot restore, export, or hand it to
anyone. But it does mean a copy exists outside the device, and you control it
from your Apple or Google account settings rather than from us.

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

Crashlytics also records that a session happened without crashing. It has to:
“this fault affects 2% of students” is a fraction, and a fraction needs a
denominator. So a small amount of information travels on ordinary launches and
not only on the bad ones, and we would rather say so than let the paragraph
above imply otherwise.

Crash reporting is **disabled in development builds** and active only in
released versions.

**You can switch it off** at **Settings → Crash reports**. Nothing obliges us
to offer that — crash reports exist to keep the app working, which is a purpose
both the US children's privacy rules and UK/EU law permit without asking. We
offer it because being entitled to something is not the same as taking it, and
because a switch you can find is worth more than a paragraph promising
restraint.

If you do switch it off, a crash that only affects you may never be found —
unless you tell us otherwise after the fact. With reporting off, Crashlytics
still writes a report on your device when the app stops unexpectedly; it just
does not send it. So the next time you open the app we will say what happened
and ask whether that one report may be sent. Answering does not change your
setting: say yes and only that report goes, say no and it is deleted from your
device. We ask once per version of the app, and if you say no, later reports
from the same version are deleted without asking again.

It is **not** governed by the age question in section 3.3, and we would rather
say so than let you assume otherwise. A crash report describes what broke, not
who was using the app when it broke, and it is often the only way we learn the
app has stopped working for someone. The installation identifier in it exists
to keep the app working and for nothing else — it is not used to contact,
profile, advertise to, or track anyone, at any age.

**Legal basis (UK/EU GDPR):** our legitimate interest in diagnosing faults so
the app works for the students using it.

### 3.3 Usage analytics

We use **Google Firebase Analytics** to understand how the app is used in
aggregate. This is how we learn which subjects students actually study, when
they study, whether the daily reminder helps, and how far people get — the
questions that tell us what to build next.

We also publish totals drawn from the same figures when describing the app —
how many students use it, how many words have been worked through. Those are
population counts: they say nothing about you, they are never sold or handed
to anyone for their own use, and we do not publish a figure small enough to
point at one person. Anything drawn from a group too small to hide in is not
published at all.

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
- Your age, or the year of birth you gave. The answer decides whether anything
  is sent at all; it is not itself sent

Firebase assigns a random **app instance identifier** so that two opens from
the same installation can be counted as one returning user rather than two new
ones. It is not linked to your identity, and it is reset if you delete and
reinstall the app.

**It is optional, and turning it off costs you nothing**

No feature depends on it. Every question, every figure and every screen works
identically whether statistics are on or off, we will not ask again if you
decline, and we will not make the app harder to use to change your mind. If
you would rather send nothing at all, that is a complete answer.

**When it runs**

Statistics are switched off in the app's own build configuration rather than
only in its code, so the first session is silent. They stay off until:

- **you have told us you are old enough.** At the end of the introduction we
  ask what year you were born. Thirteen is the line in most of the world; in
  India and Canada it is eighteen, and two further conditions apply — see
  section 6. We do not keep the year — only whether it puts
  you at 13 or over, and that answer stays on your device. Skip the question
  and no statistics are collected at all; **Settings → Usage analytics** will
  say so rather than offering a switch that does nothing;
- **and, in the UK and the EU/EEA, you have said yes.** We ask once, in plain
  language, and “no” is remembered.

Everywhere else, once an age of 13 or over has been given, statistics run and
can be switched off at any time from **Settings → Usage analytics**, which
stops collection from that moment.

**An answer of “under 13” is not permanent, but it never expires upward on its
own.** Someone who answers at twelve is fifteen three years later, so we keep
the year they turn 14 and, when it arrives, forget the answer and go back to
collecting nothing until we are told again. Reaching that year never starts
collection by itself — it can only stop it and put the question back. You can
answer, or change your answer, at any time from **Settings → Your age**.

If you were using Bud Years before this changed, you were never asked — so
your age is unknown to the app and statistics are off until you answer.
**Settings → Replay the intro** puts the question back in front of you.

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
It is not directed to children under 13 and is rated accordingly on both
stores.

**If someone younger uses it anyway.** We would rather find out than not, so
the app asks — at the end of the introduction — what year you were born. If
the answer puts you under 13, usage statistics are switched off and there is
nothing to switch back on. We do not keep the year, and we do not lock a
younger student out of the questions: this is a study app, and the safe
response to a young user is to collect less from them, not to refuse to teach
them. Skipping the question produces the same outcome.

This replaces a promise we used to make here — that we do not *knowingly*
collect from anyone under 13. Asking means we may now know, which is the
point: a service that avoids asking in order to keep saying it does not know
has arranged its own ignorance. The commitment is the stronger one, that
knowing changes what we do.

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
  (section 3.3). The analytics one exists only where statistics are running at
  all, so for a user under 13 there is none. Both exist to keep the app working
  and to count usage in aggregate. They are not used to contact, profile,
  advertise to, or track anyone, and they are not disclosed for any other
  purpose.

**If you are under 18**

Most of our users are. Several countries treat everyone under 18 as a child
for data protection purposes, so:

- read this policy and the Terms of Use with a parent or guardian, and ask
  them to agree on your behalf;
- if you would rather send nothing at all, either skip the year-of-birth
  question or switch usage statistics off at **Settings → Usage analytics**.
  The app works identically either way, and no feature is withheld for saying
  no.

A parent or guardian may write to `[PRIVACY CONTACT EMAIL]` at any time to ask
what we hold and to have it deleted.

**India**

India's Digital Personal Data Protection Act, 2023 defines a child as anyone
**under 18** — not under 13 — and requires verifiable parental consent before a
child's personal data is processed. It also prohibits tracking and behavioural
monitoring of children.

So in India **usage analytics are off, and three separate things have to be
true before they are not**: your own answer to the year-of-birth question puts
you at 18 or over; your device's operating system independently reports that
you are 18 or over; and you have then agreed. Any one of the three missing, or
the first two disagreeing, and nothing is collected.

We ask the operating system separately rather than trusting our own question
twice. Apple and Google can report an age range set on a parent-managed
account, which is different evidence from an answer typed by whoever is holding
the phone, and we require both.

**In practice this means nothing is collected in India today**, because those
operating-system age APIs are not yet connected — Apple's needs an entitlement
we have not applied for and Google's is still rolling out. We would rather say
that than imply a working mechanism.

Crash reports are separate and are described in section 3.2. They carry no
personal data and no behavioural information, they are sent only to find out
what broke, and they can be switched off at **Settings → Crash reports**.

**Canada**

Federal privacy law (PIPEDA) and, in Quebec, the *Act respecting the protection
of personal information in the private sector* as amended by Law 25, apply to
what little we collect.

Quebec's Law 25 requires that any technology used to profile, locate, or
identify a person be **switched off by default**, and that consent for a minor
come from a parent.

**We apply the same rule to the whole of Canada, and we apply it at 18.** Two
deliberate choices, both stricter than required. Quebec cannot be told apart
from the rest of Canada by the country setting on a device, and the
alternatives are guesses based on your language that would be wrong for
anglophone Quebecers and for francophones elsewhere — so we cover everyone.
And Quebec's own line is 14, not 18; we use 18 because it is the more
protective number and because it matches India, rather than running two
different rules for the same idea.

So the test is the same as India's: your answer, your operating system's
answer, and your agreement — all three, or nothing is collected. It costs us
the statistics of every Canadian student under 18, which we think is the right
way round.

Crash reports contain no profiling information, and can be switched off at
**Settings → Crash reports**.

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

## 7A. If the app changes hands

If Bud Years is ever sold, merged, or transferred to someone else, the crash
and analytics data described above may transfer with it. Whoever receives it
would be bound by this policy until they published their own, and we would say
so in the app before it happened.

Nothing on your device transfers, because nothing on your device is ours to
transfer.

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

## 9B. Decisions the app makes about you automatically

The app does make automated decisions — which problems you see next, how big a
day's set is, when a problem you got wrong comes back, when a course is
considered learned. That is the whole design.

All of it runs **on your device**, from answers you marked yourself, and none
of it reaches us. It produces no legal effect and nothing of similar
significance: the worst consequence of the algorithm being wrong is a day's
practice that is too easy or too hard.

We do not profile you, we do not score or rank you against anyone else, and no
decision about you is made anywhere except on your own phone.

## 9C. If you live in a US state with a privacy law

California, and around twenty other states, give residents rights over their
personal information — to know what is held, to have it corrected or deleted,
to obtain a copy, and to opt out of its sale or of targeted advertising.

Most of those laws only bind businesses above a size threshold, and we are an
independent developer well below them. Rather than argue about whether they
apply, here is the position:

- **We do not sell personal information**, and we do not share it for
  cross-context behavioural advertising, as those terms are defined by the
  CCPA/CPRA and its equivalents. There is no advertising in Bud Years at all.
- **We do not collect sensitive personal information**, and we do not use or
  disclose any for a purpose that would trigger a right to limit it.
- **We do not discriminate** against anyone for exercising a privacy right.
  There is nothing to withhold: declining analytics changes nothing about what
  the app does.
- To exercise any right, write to `[PRIVACY CONTACT EMAIL]`. We will answer
  within the period your state's law allows, and if we cannot link a request to
  any record — which is likely, because we hold nothing that identifies you —
  we will tell you that plainly rather than ask for identifying information we
  would then have to keep.

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
