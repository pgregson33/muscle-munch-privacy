---
title: Muscle Munch Privacy Policy
---

# Muscle Munch Privacy Policy

*Last updated: October 23, 2026*

Muscle Munch is a workout and nutrition tracker, currently in beta through Apple's TestFlight. This policy explains what the app collects, where it's stored, and the choices you have. It's written to match how the app actually works.

**The short version:**
- Your workouts, food diary, recipes and weigh-ins are stored **on your iPhone**, not on our servers. **Deleting the app can permanently erase them**, and signing back in does not bring them back.
- If you create an account, your profile and the **summaries of workouts you finish** are stored with our backend provider so friends can see them.
- Your food diary and Apple Health data are **never** uploaded.
- There are no ads, no tracking, no analytics tools and no selling of data.

## 1. Data stored only on your iPhone
The following stay in the app's storage on your iPhone:
- workouts, routines, programs and gym setups;
- your food diary, saved foods, recipes and saved meals;
- weigh-ins, body stats, goals and settings;
- data you import from other apps (such as Hevy or MacroFactor exports).

Photos you take to scan barcodes, recipes, workout plans or meals are read on your iPhone. The optional AI meal recognition and workout-plan reading use Apple's on-device model, so the photos aren't sent to us or to an AI service. Food names found this way may be looked up in the food databases described in section 5.

This data is included in your iPhone's own iCloud or computer backup if you have those turned on. **Muscle Munch does not currently back it up to our servers.**
- **Deleting the app deletes this data,** and it may be lost permanently.
- **Signing back in does not restore it,** even with the same Muscle Munch account on the same or a new iPhone. Your account holds only the data in section 2.
- **The only way to get it back** is to restore your whole iPhone from an iCloud or computer backup made before you deleted the app.

## 2. Data stored when you create an account (optional)
You can use the app without an account. If you sign in (with Sign in with Apple during the beta), the following is stored with Supabase, our backend provider, on servers in the United States:

- **Account:** your sign-in identifier and an internal user ID. Signing in with Apple gives us either Apple's private relay address or your email, as you choose. A few early testers signed in with an email link.
- **Profile:** your username, display name, optional profile photo, weekly workout goal, and your privacy choices.
  - New profiles start **private**, with **weights hidden** in posts.
  - You can turn either on when you set up your username, or later in Settings › Privacy.
- **Shared workouts:** when you finish a workout while signed in, its summary is shared with the people allowed to see it. Workouts you finish while signed out, or before you create an account, are never shared, now or later. The summary includes:
  - name, start and end time, and duration;
  - exercises, sets and reps, and the time or distance for timed exercises;
  - weights and total volume, unless you turn off "Show weights in my posts";
  - personal-record counts.
- **"Working out now":** a status that shows while a workout is in progress.
- **Social activity:**
  - follows and follow requests, blocks, Crew membership;
  - kudos, comments and nudges;
  - challenges you create, join or are invited to, with their scores;
  - notifications about this activity.
- **Notifications:** your device's push-notification token and your notification preferences, used to send the notifications you've allowed.
- **Beta access:** which beta features your account can use.

**Who can see this:**
- **Private profile (the default):** only people you approve as followers can see your workouts.
- **Public profile:** if you turn it on, any signed-in Muscle Munch user can see your profile and shared workouts.
- **What anyone signed in can see:** your username, display name and profile photo can be found in search, and your "working out now" status is also visible.
- **Profile photos** are stored at web addresses that can be opened without signing in.
- **Blocking** someone hides you from each other.

## 3. Optional photo-accuracy sharing (AI photo logging beta)
This is available only to testers given access to the AI photo logging beta. There are two separate choices in Beta Features, both off unless you turn them on:
- **Accuracy reports:** for each scan, the food names the app found, gram estimates, nutrition totals, your corrections, timings and your iPhone model.
  - They are labeled with a random tester ID, not your account.
  - They never include photos, your diary, your name, email or location.
  - They are kept for up to 180 days.
- **Meal photos:** one photo at a time, only when you confirm it.
  - Each photo is re-saved on your iPhone first, so location and camera details are removed.
  - It is stored in a private storage area and kept for up to 90 days.

Only you and the Muscle Munch team can view what you've shared. You can turn sharing off at any time and choose to delete what you've already shared.

## 4. Apple Health
With your permission, Muscle Munch:
- **reads** your weight, height, birthday and sex, to fill in your profile and calorie targets and to bring in weigh-ins from your scale;
- **saves** your weigh-ins and the calories and macros of meals you log.

Health data is never sent to our servers, never shown to friends, and never used for advertising. If you've turned on iCloud sync for Health, Apple syncs it.

## 5. Food lookups
Food searches and barcodes you scan are sent to:
- **Open Food Facts**;
- **USDA FoodData Central**.

These services return nutrition information. No account details are sent with these lookups, but like any internet request they see your IP address.

## 6. Feedback and diagnostics
- **Help & Feedback:** opens a message in Apple Mail (or another app you choose) that you review and send yourself. We receive what you send, and your email address.
- **Crash and freeze reports from Apple** (technical details only) are kept on your iPhone. They are shared only if you choose to send one.
- **The optional activity record** in Settings › About › Diagnostics stays on your iPhone unless you include it.
- **TestFlight:** if you send feedback or crash reports through TestFlight, Apple shares them with us under Apple's terms.

There are no analytics tools, advertising tools or third-party trackers in the app.

## 7. How we use data
We use data only to run the app's features: your profile, shared workouts, friends, challenges and notifications. We also use it to respond to feedback and to fix problems. We don't sell or rent personal data, and we don't use it for advertising.

## 8. Service providers
We rely on these providers, each under its own terms:
- **Supabase:** database, sign-in and storage.
- **Apple:** Sign in with Apple, push notifications, TestFlight, Apple Health and on-device intelligence.
- **Open Food Facts and USDA:** food data.

## 9. Keeping and deleting your data
- **Delete your account:** go to Settings › Account › Delete Account. This permanently removes the account data in sections 2 and 3: your profile, shared workouts, social activity, challenges, notification tokens and photo-accuracy reports.
- **Photos:** the app also deletes your profile photo and any shared meal photos.
  - If your profile photo can't be removed, the app tells you; contact us and we'll remove it.
  - Any shared meal photos left behind are deleted automatically within the 90-day period above.
- **What we keep:** if your account's beta-feature access was ever changed, an internal security log keeps your user ID and username with that change.
- **Provider systems:** copies may remain in our providers' systems for a limited time, under their own policies.
- **On your iPhone:** you can delete all data in Settings › Privacy › Manage Data, or by deleting the app.
- **Signing out** never deletes data from your iPhone. If your history belongs to your account, it's hidden after you sign out until you sign back in or unlock it with Face ID or your passcode.

## 10. Security
- Data is sent over encrypted connections.
- Server access is restricted so each account can read and change only what it's allowed to.
- No system is perfectly secure; please use a passcode on your iPhone.

## 11. Children
Muscle Munch isn't directed to children under 13, and we don't knowingly collect their personal information.

## 12. Changes
If this policy changes, we'll update the date above and, for significant changes, tell testers in the app or in the TestFlight notes.

## 13. Contact
Questions or requests (including access or deletion help): **musclemunchsupport@gmail.com**.
