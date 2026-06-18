---
layout: page
title: Privacy Policy
permalink: /privacy.html
---

# Privacy Policy

**Last updated: June 18, 2026**

[Terms of Service](./terms.html)

This Privacy Policy describes what information Tally (also called TallyTogether) collects and how we use it. Tally is operated by Christy Lam, an independent iOS developer based in the United States.

We designed Tally to collect as little personal information as possible. We do not run any servers, do not use third-party analytics, do not show advertisements, and do not sell your data — to anyone, ever.

## What we collect

When you use Tally, the following information is created and stored:

- **iCloud Apple ID identifier**: An opaque, per-app identifier that Apple provides. This is NOT your Apple ID email — it's a randomized string that lets Tally know which account is yours. It cannot be used to identify you outside the app.
- **Display name**: The name you choose during onboarding (e.g., "Christy"). This is shown to your friends.
- **Username**: A unique handle you pick during onboarding. Used by friends to find you.
- **Habit and goal content**: The names of habits you create, your daily completion records, and any goal text you enter.
- **Friend connections**: Records of which other Tally users you've sent friend requests to or accepted requests from.
- **Direct messages**: Text messages you send to mutual friends within the app.
- **Avatar selection**: Which built-in icon and theme color you've chosen (these are SF Symbols, not photos).

## What we do NOT collect

We deliberately avoid collecting most of the data points other apps gather. Specifically, we do **not** collect:

- Your real name (unless you choose to use it as your display name)
- Your email address or phone number
- Your Apple ID email
- Payment or billing information (Apple handles all of this; we never see it)
- Photos, contacts, calendars, or any other content from your device
- Your location (we do not request location permission)
- Your browsing or app activity outside Tally
- Advertising identifiers (IDFA) — we do not show ads
- Third-party analytics data (Mixpanel, Google Analytics, Firebase Analytics, etc.) — we don't use any of these
- Crash reports beyond Apple's standard system-level reporting

## Where your data lives

Tally has no servers of its own. All your personal data is stored in **your own iCloud account** using Apple's CloudKit service:

- **Private data** (your habits, goals, account info): stored in your CloudKit private database. Only you and Apple can access this. We cannot read it from our end.
- **Shared data** (friend lists, leaderboard rows, DM threads): stored in CloudKit shared zones, accessible only to the specific friends involved in each share.

When you delete the app, your private data remains in your iCloud account until you delete it through iOS Settings → Apple Account → iCloud → Manage Account Storage → Tally.

## Subscription information

When you subscribe to Tally, Apple processes the payment via In-App Purchase. We use a service called RevenueCat to verify your subscription status with Apple. **RevenueCat receives**:

- Apple's anonymous IAP receipt (which proves you have an active subscription)
- An anonymous user identifier so we know which subscription belongs to which Tally account

**RevenueCat does NOT receive**:
- Your name, email, payment details, habit data, friend information, or any other personal content

RevenueCat's privacy policy is available at [revenuecat.com/privacy](https://www.revenuecat.com/privacy).

## How we use your data

We only use your data to operate the app — meaning, to:
- Display your habits and goals to you
- Show you on the leaderboard with your friends
- Deliver friend requests and messages to the right people
- Verify your active subscription status

We do not use your data to:
- Train any AI or machine learning models
- Build profiles for advertising
- Sell to data brokers
- Share with any third party for any reason other than the technical ones above (Apple for IAP, RevenueCat for subscription verification)

## Your privacy rights

Wherever you live, you have the right to know what we have about you, request its deletion, and stop using Tally at any time.

### Deleting your account

You can delete your Tally account from within the app. From the Today tab, tap your profile photo in the top-right corner to open your Profile, then tap **Delete account** and confirm. This removes your account record, habits, friend connections, group memberships you joined, outgoing friend requests, and other personal data from CloudKit.

Note: deleting your Tally account does not cancel your subscription. To cancel, go to **iOS Settings → Apple Account → Subscriptions → Tally → Cancel Subscription**, or use the **Manage subscription** button in your Profile.

### What we cannot delete

CloudKit's permission model means a small amount of data may persist even after you delete your Tally account. None of this can be used to reach you outside the app:

- **Messages you've posted in groups owned by other users**: when you send a message in a friend's group chat, that message becomes a record in their iCloud storage that only they can delete. Your username and the message content remain visible to the group's existing members. We have no technical way to reach into someone else's iCloud and remove records on your behalf.
- **Friend or group requests sent TO you that you never responded to**: these records were created by the sender, and only the sender can delete them through their own app. They will continue to point at your former account ID until they expire or the sender removes them.
- **Cached profile information on your friends' devices**: their app may continue to show your old display name and avatar briefly until it refreshes and discovers your account is gone.

For everything else — your own habits, goals, completion history, groups you own, the public username claim, your friend connections from your side, your membership in groups you joined — deletion is immediate and complete.

### If you live in the European Union (GDPR)

You have the right to:
- Access the personal data we hold about you (most of which is just in your own iCloud account)
- Correct inaccurate data
- Delete your data ("right to be forgotten")
- Restrict or object to processing
- Receive your data in a portable format
- Lodge a complaint with your local data protection authority

To exercise any of these rights, email **christyptlam459@gmail.com**. Because Tally stores most data in your own iCloud account, you can also exercise most of these rights directly through Apple's settings.

The legal basis for processing your data under GDPR is the performance of our contract with you (these Terms of Service) and your consent (which you give by using the app).

### If you live in California (CCPA / CPRA)

You have the right to:
- Know what personal information we collect (we've listed it above)
- Request deletion of your personal information
- Opt out of the sale or sharing of personal information (we do not sell or share your data, so there's nothing to opt out of)
- Not be discriminated against for exercising any of these rights

To exercise any of these rights, email **christyptlam459@gmail.com**.

## Children

Tally is not intended for children under 13 (or the minimum age of digital consent in your country, whichever is higher). We do not knowingly collect data from children below this age. If you believe a child has used Tally without consent, contact us at **christyptlam459@gmail.com** and we will delete the account.

## Data security

We rely on Apple's CloudKit infrastructure for data storage, which means your data is protected by:
- Encryption in transit and at rest using Apple's CloudKit security
- Apple's industry-standard server-side protections
- The same protections that apply to your other iCloud data

We do not store passwords (Apple handles authentication) and we have no centralized database that could be breached.

## International users

Tally is operated from the United States. If you use Tally from outside the US, your data may be processed in the US or wherever Apple's iCloud servers are located. By using Tally, you consent to this.

## Changes to this policy

We may update this Privacy Policy from time to time. We will update the "Last updated" date above. For material changes, we will notify you within the app or via the App Store listing.

## Contact us

For any privacy-related questions, email us at:

**christyptlam459@gmail.com**

---

[← Back to Terms of Service](./terms.html)
