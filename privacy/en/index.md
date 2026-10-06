---
layout: default
title: Privacy Policy — Sacra Confraternita del Passo
description: Privacy Policy for the private beta of Sacra Confraternita del Passo.
lang: en
alternate_url: /privacy/it/
alternate_lang: it
alternate_label: Italiano
permalink: /privacy/en/
---

# Privacy Policy — Sacra Confraternita del Passo

> **DRAFT — not reviewed by a lawyer.** This policy is written for the
> invite-only iOS and Android beta of Sacra Confraternita del Passo. It is a
> good-faith, GDPR-aware description of the app as it currently works. It
> must receive a legal review before public distribution, monetization, or
> any material expansion beyond the founder's closed circle of invitees.

**Version:** 2.3 · **Prepared:** 2026-09-27 · **Effective:** with the app release presenting version 2.3

## 1. Who we are

Sacra Confraternita del Passo ("SCP", "the app", "we", "us") is a private,
invite-only step-challenge app for a closed group of friends and
friends-of-friends. For this beta, SCP's founder/operator is the data
controller.

Contact for any privacy question or request:
**sacraconfraternitadelpasso@gmail.com**.

## 2. Data we process

We process the following categories of data:

- **Account and consent data:** email address, Supabase authentication user
  identifier, nickname, account creation date, invitation relationship, and
  the date and version of the privacy consent you gave.
- **Step data:** on iOS, automatically recorded daily counts from Apple Health
  (HealthKit), excluding manual entries; on Android, daily step aggregates from
  Health Connect, which may include manual entries that SCP cannot distinguish.
- **Derived fitness data:** synced daily totals, lifetime totals from the whole
  Rome calendar day you joined, cycle XP, Rango and related progress. The server
  calculates progress from saved daily totals; the phone does not upload a
  separate lifetime count. Consecration is deferred in this version.
- **Challenge and social data:** challenges you create or join, invitations,
  participation status, Confratello relationships, teams, fixtures, scores,
  standings, results, trophies, achievements and other competition history.
- **Communications and preferences:** in-app and remote push notifications,
  activity-feed events, read status, the Apple Push Notification service
  (APNs) device token used to reach your signed-in device, daily goal,
  visibility choices and notification preferences.
- **Technical and security data:** normal authentication and service logs
  produced by our providers, which may include timestamps, IP address, device
  or network information, and anti-cheat records when a newly read step total
  conflicts with a previously synced total.

Language, the local daily-reminder schedule and completion of the first
Health-permission introduction are stored on the device and are not
intentionally uploaded to SCP's database. SCP does not include advertising or
third-party analytics SDKs.

### Apple Health / HealthKit

SCP requests read-only access to the **Step Count** category in Apple Health.
It does not request heart rate, sleep, location, workouts, clinical records or
any other Health category, and it never writes data to Apple Health. Steps
entered manually in the Health app are excluded from SCP's counts.

When you grant access, SCP reads recent and missing daily step totals in the
foreground. These daily totals are synced to SCP's Supabase database for
challenges, standings and social features. Rango is calculated on the server
from saved days. SCP does not read HealthKit again just to display Rango.

HealthKit permission is controlled by Apple and can be changed at any time in
the Health app or iOS privacy settings. Apple deliberately does not tell an app
whether read access was denied; SCP may therefore see no step data both when
access is denied and when no matching data exists. Revoking HealthKit access
stops future reads but does not automatically erase totals already synced to
SCP. You can erase or request access to those copies as described in §7.

We do not use HealthKit-derived data for advertising, marketing or data
mining, and we do not sell it.

### Android / Health Connect

SCP requests **READ_STEPS only**, for the official aggregated daily step count.
It never writes health data, and requests neither background health access nor
extended history. It does not read heart rate, sleep, locations, workouts or
other health categories, and does not directly collect motion sensor data.
Health Connect needs a source that records steps; SCP is not a standalone
pedometer. Provider availability and readable history vary by Android version
and permission history. Aggregates may include manual entries or third-party
sources; SCP does not claim to reliably exclude them on Android.

Permission is requested only after you choose to connect. Refreshing Home or
another step-syncing screen reads available recent/missing days in the foreground
and uploads daily totals to the same Supabase database. The Health Connect panel
itself shows a local daily reading. SCP does not upload raw health records or
source-device identifiers. Rango screens only read server totals and dates.
Denied/revoked access, missing provider, absent data or errors are not uploaded
as invented zero steps. Older saved days remain when no longer readable.

You can browse existing SCP data without connecting Health Connect. Revoke the
permission in Health Connect settings at any time; revocation stops future
health reads but does not delete totals already synced to SCP. Export/deletion
and withdrawal requests are described below. Use one SCP device per account;
this beta does not merge totals from multiple phones or support automatic
cross-platform transfer.

Android has optional local reminders, enabled separately from health access.
They use inexact system alarms and may be delayed by power management; they do
not sync steps in the background. SCP sends no remote Android push notifications
and uses no FCM. Notification preferences and the Health Connect introduction
state are stored locally. No advertising, sale, marketing or data mining uses
are made of Health Connect data; use is limited to the stated SCP features.

## 3. Why we process data and our legal bases

- **Provide your account and the challenge service:** account, challenge,
  social and preference data are needed to perform our agreement with you.
- **Read, sync, compare and show step data:** we rely on your explicit consent
  for the specified fitness and challenge purposes. We treat step data as
  sensitive health/fitness data and, where the GDPR applies, rely on Articles
  6(1)(a) and 9(2)(a).
- **Protect the service and competition integrity:** we use access controls,
  logs and step-mismatch checks for our legitimate interest in preventing
  abuse and keeping standings reliable. Where those checks process step data,
  your explicit health-data consent also applies.
- **Send service communications:** sign-in codes, in-app messages and their
  matching remote push alerts are used to operate the service. Optional
  notification categories can be disabled in Settings, and remote alerts can
  also be disabled in iOS Settings (remote push is iOS-only); the daily device reminder remains optional
  and local.

You give explicit step-data consent by selecting the consent checkbox after
being shown this policy. Device permission is separate: iOS asks for HealthKit
Step Count access; Android asks for Health Connect Steps access after you choose
to connect. Declining device access still allows browsing saved SCP data.

You may withdraw consent at any time by revoking HealthKit or Health Connect access and
contacting us, or by using account deletion in Settings. Withdrawal does not
affect processing that was lawful before it. Since step processing is
necessary for SCP's core challenge service, we cannot currently keep an active
non-step account after consent is withdrawn.

## 4. Who can see data inside SCP

SCP is invite-only, but it includes social features and some data is shared
with other authenticated members:

- The current closed-beta **profile directory is readable by every signed-in
  member**. It includes nickname, email, Rango/lifetime progress, daily goal,
  visibility and notification preferences, and consent metadata. Normal app
  screens do not display every field, but the current beta access rule permits
  authenticated members to read them. This broad rule must be narrowed before
  SCP expands beyond the trusted invite-only group.
- The invite list, including invited email addresses and inviter identity, is
  readable by signed-in members so duplicate invitations can be avoided.
- A synced **daily step total** is readable only by you and by accepted members
  who share a challenge with you, and only for dates within that challenge.
- Challenge membership, teams, fixtures, scores and standings are visible
  according to each challenge's access rules. Community boards and shared
  historical results can be visible to all signed-in members.
- Your completed results, trophies and achievement-related activity are
  visible to other members when your **Bacheca dei Vanti** setting is on.
  Turning it off hides records governed by that setting and prevents new
  public activity-feed items, but it may not remove activity or notification
  snapshots that were already created.
- Personal in-app notifications are readable only by their recipient. The
  community activity feed is readable by all signed-in members.

Nothing in SCP is intended to be visible on the open web. We do not sell or
rent member data, run ads, or share health-derived data with advertisers or
data brokers.

## 5. Service providers and data location

We use these providers to operate SCP:

- **Supabase:** authentication, an EU-hosted Postgres database and server-side
  functions. Database Row Level Security restricts access by authenticated
  user and feature context.
- **Google / Gmail:** outgoing delivery of one-time sign-in codes through a
  dedicated SCP Gmail account.
- **Google Fonts:** the app can fetch the Inter and Playfair Display font files
  from Google's font delivery service. Google may receive ordinary connection
  information such as IP address and request metadata. Font requests do not
  contain your SCP step totals.
- **Google / Android:** Health Connect supplies on-device health aggregates.
  Android manages local notifications and any Google Play distribution under
  its own terms; SCP does not send health data through FCM.
- **Apple:** HealthKit provides the on-device Step Count source and Apple may
  process TestFlight/App Store distribution and diagnostic information under
  its own terms. Apple Push Notification service receives the device token and
  alert payload needed to deliver a remote notification. SCP does not send
  your synced step database to Apple through TestFlight or APNs.

These providers may process limited account or technical data in other
countries under their own data-protection terms and transfer safeguards. You
can contact us for more information relevant to your data.

## 6. Retention and account deletion

We keep active-account data while it is needed to provide SCP. This beta does
not yet apply a fixed automatic deletion period to inactive accounts,
competition history, in-app notifications or activity-feed records.

The self-service **Delete my account** action permanently:

- deletes the Supabase authentication user and SCP profile, including email,
  nickname, account identifiers, consent record, preferences and entitlement;
- deletes synced daily steps, anti-cheat mismatch records, individual
  challenge participation and results, sprint and consistency ledgers,
  tournament seeds and match-step values, achievements, friendships, received
  notifications, Member of the Month records and the invitation for the
  account's email;
- removes notifications, activity-feed events and group-record snapshots that
  contain the member's nickname;
- removes the account's APNs device-token registrations, while normal sign-out
  detaches the current physical device from the signed-in account;
- removes league fixtures involving the member and removes their identity and
  recorded steps from shared tournament matches; and
- cancels SCP's scheduled reminders and clears account-scoped preferences on
  the device that performed the deletion.

A challenge created by the deleted member may still be needed by its other
participants. In that case SCP keeps only its shared mechanical structure:
the creator identifier and user-authored challenge/trophy text are removed.
Team-level totals or other shared aggregate outcomes can remain when they no
longer identify or link to the deleted member. There is no placeholder profile:
the deleted profile and its original user identifier no longer remain in SCP's
public database.

Supabase, Apple or Google operational logs and backups may remain for the
limited periods set by those providers before being overwritten or deleted.

## 7. Your rights

Where applicable, you may ask us to:

- access the personal data we hold about you;
- correct inaccurate data;
- erase data;
- restrict or object to processing;
- provide portable data; and
- withdraw consent at any time.

Settings includes links to this policy and the Terms, and a self-service JSON export containing the authentication and
profile record, consent and preferences, invitations, daily steps, anti-cheat
history, every direct challenge/league/team/tournament record, notifications,
APNs device-token registrations, activity-feed snapshots, Confratello
relationships, achievements, group titles and the shared challenge structures
needed to understand those records. It does not include unrelated members'
private records.

Send requests to **sacraconfraternitadelpasso@gmail.com**. We may need to
verify that the account is yours. You may also complain to the data-protection
authority where you live or work, such as Italy's Garante per la protezione dei
dati personali.

## 8. Security

SCP uses encrypted network connections, Supabase's encryption-at-rest platform
defaults, authenticated access and database Row Level Security. The app is
invite-only and does not expose direct database service credentials with
administrative privileges to members. No system can guarantee absolute
security; please contact us if you suspect unauthorized access.

## 9. Children

SCP is not directed at, and must not be used by, anyone under 16.

## 10. Changes to this policy

We update the version and effective date when this policy changes. SCP stores
the policy version and consent timestamp associated with each account. When a
material update requires renewed consent, the app blocks normal navigation and
asks the member to review and explicitly confirm the new version first.
