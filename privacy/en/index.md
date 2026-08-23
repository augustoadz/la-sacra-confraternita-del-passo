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
> invite-only TestFlight beta of Sacra Confraternita del Passo. It is a
> good-faith, GDPR-aware description of the app as it currently works. It
> must receive a legal review before public distribution, monetization, or
> any material expansion beyond the founder's closed circle of invitees.

**Version:** 2.1 · **Effective date:** 2026-08-23

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
- **Step data from Apple Health (HealthKit):** automatically recorded step
  counts for the days and date ranges needed by the app. Manual entries are
  excluded.
- **Derived fitness data:** synced daily totals, lifetime totals since you
  joined SCP or began your current Rango cycle, cycle XP, Rango and related
  progress values.
- **Challenge and social data:** challenges you create or join, invitations,
  participation status, Confratello relationships, teams, fixtures, scores,
  standings, results, trophies, achievements and other competition history.
- **Communications and preferences:** in-app notifications, activity-feed
  events, read status, daily goal, visibility choices and notification
  preferences.
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

When you grant access, SCP reads the totals needed to calculate recent and
missing daily scores and Rango progress from the date you joined, or from the
start of the current Rango cycle. Reads occur on your device when the app needs
to refresh those features. The resulting daily and derived totals are then
synced to SCP's Supabase database so challenges, standings and social features
can work across members and devices.

HealthKit permission is controlled by Apple and can be changed at any time in
the Health app or iOS privacy settings. Apple deliberately does not tell an app
whether read access was denied; SCP may therefore see no step data both when
access is denied and when no matching data exists. Revoking HealthKit access
stops future reads but does not automatically erase totals already synced to
SCP. You can erase or request access to those copies as described in §7.

We do not use HealthKit-derived data for advertising, marketing or data
mining, and we do not sell it.

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
- **Send service communications:** sign-in codes and in-app messages are used
  to operate the service. Optional categories of in-app notifications can be
  disabled in Settings; the daily device reminder is also optional and local.

You give explicit step-data consent by selecting the consent checkbox after
being shown this policy. iOS then asks separately whether SCP may read Step
Count through HealthKit.

You may withdraw consent at any time by revoking HealthKit access and
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
rent member data, run ads, or share HealthKit-derived data with advertisers or
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
- **Apple:** HealthKit provides the on-device Step Count source and Apple may
  process TestFlight/App Store distribution and diagnostic information under
  its own terms. SCP does not send your synced step database to Apple through
  TestFlight.

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

Settings includes a self-service JSON export containing the authentication and
profile record, consent and preferences, invitations, daily steps, anti-cheat
history, every direct challenge/league/team/tournament record, notifications,
activity-feed snapshots, Confratello relationships, achievements, group titles
and the shared challenge structures needed to understand those records. It
does not include unrelated members' private records.

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
