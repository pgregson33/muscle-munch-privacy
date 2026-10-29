---
title: Muscle Munch Privacy Policy
---

# Muscle Munch Privacy Policy

*Last updated: October 29, 2026*

Muscle Munch is a workout and nutrition tracker, currently in beta through Apple's TestFlight. This policy explains what the app collects, where it's stored, and the choices you have. It's written to match how the app actually works.

**The short version:**
- Your workouts, food diary, recipes and weigh-ins are stored **on your iPhone**. If you turn on the optional **Cloud Backup**, a copy is also kept with our backend provider so you can restore it. Without a backup, **deleting the app can permanently erase them**, and signing back in does not bring them back.
- If you create an account, your profile and the **summaries of workouts you finish** are stored with our backend provider so friends can see them.
- Your food diary is uploaded only as part of an optional Cloud Backup. Apple Health records are **never** uploaded; some values that come from Health can be included in an optional backup (section 4).
- There are no ads, no tracking, no analytics tools and no selling of data.

## 1. Data stored on your iPhone
The following are kept in the app's storage on your iPhone:
- workouts, routines, programs and gym setups;
- your food diary, saved foods, recipes and saved meals;
- weigh-ins, body stats, goals and settings;
- data you import from other apps (such as Hevy or MacroFactor exports).

Photos you take to scan barcodes, recipes, workout plans or meals are read on your iPhone. The optional AI meal recognition and workout-plan reading use Apple's on-device model, so the photos aren't sent to us or to an AI service. Food names found this way may be looked up in the food databases described in section 5.

This data is included in your iPhone's own iCloud or computer backup if you have those turned on. Muscle Munch backs it up to our servers **only if you turn on Cloud Backup** (section 4A).
- **Deleting the app deletes this data from your iPhone.** Without a cloud backup, it may be lost permanently.
- **Signing back in does not bring it back by itself.** With a cloud backup, you can restore it from Settings › Cloud Backup (section 4A). Without one, the only way to get it back is to restore your whole iPhone from an iCloud or computer backup made before you deleted the app.

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

**Apple Watch workout matching (optional):** if you turn on Match Apple Watch Workouts in Settings › Apple Health, Muscle Munch asks separately to **read** your workouts, heart rate and active calories. It then:
- adds the average and highest heart rate and the active calories from a matching Apple Watch workout to the workout you logged (your exercises, sets and times never change);
- adds your other Apple Watch workouts to your workout history in the app.

It never writes workouts, heart rate or active calories to Apple Health.

**Health records and what Muscle Munch keeps:**
- Your records in Apple Health stay in Apple Health. Muscle Munch changes or deletes only the Health records it saved itself (for example, when you delete a meal it logged).
- Some values that come from Health are saved in Muscle Munch on your iPhone: the height, birthday, sex and weight in your profile, the weigh-ins brought in from your scale, and the heart rate, active calories and workout details added from Apple Watch workouts.

Apple Health records are never sent to our servers, never shown to friends, and never used for advertising. The values from Health that Muscle Munch saves are never shown to friends or used for advertising either. They're sent to our servers only if you turn on Cloud Backup, as part of your private backup (section 4A); weigh-ins brought in from Apple Health are left out of backups. If you've turned on iCloud sync for Health, Apple syncs it.

## 4A. Optional Cloud Backup
Cloud Backup is **off unless you turn it on** in Settings › Cloud Backup, after reading what it does. You need to be signed in.

**What a backup contains:**
- finished workouts, routines, programs, gym setups and the exercises you created or changed;
- your food diary, saved foods, recipes, saved meals and food corrections you've made;
- weigh-ins you entered, body stats, goals, settings and some display preferences;
- values from Apple Health that Muscle Munch saved (section 4): your profile's height, birthday, sex and weight (whether you entered them or they came from Health); for workouts matched to an Apple Watch workout, the average and highest heart rate, active calories and the Health workout's identifier; the Apple Watch workouts added to your history (their name, start and end time, heart rate, active calories and identifier); the identifiers of Watch workouts you said weren't a match; and whether Apple Health is turned on in the app.

**Left out:** workouts still in progress, weigh-ins brought in from Apple Health (they come back from Health after a restore; for ones you removed, only a one-way code made from the date and weight is kept, not the date or weight themselves, so they stay hidden), label photos, and the app's upload queue. No Apple Health records themselves are included.

**Also stored with each backup:** your account ID, a random ID for the iPhone install, the app version, your iPhone model, the backup's size, counts of each kind of record, checksums used to check the backup, and when it was made and checked.

**When:** the app aims to back up about once a week when something has changed, and you can choose Back Up Now up to twice a day. iOS decides when apps can run in the background, so timing isn't guaranteed. Each backup is downloaded again and checked before it counts as complete.

**Where and how it's protected:**
- Backups are stored with Supabase, our backend provider, on servers in the United States, in a private storage area under your account.
- They are encrypted in transit and at rest. They are **not end-to-end encrypted**: authorized Muscle Munch service administrators and our hosting provider may technically be able to access them.
- **Other user accounts can't access your backups.** Server rules let each account read, list and restore only its own backups.
- Backups are used only to store and restore your history.

**Restoring:** you can restore a backup in Settings › Cloud Backup, signed in to the account that made it. A restore only works on an iPhone with no workout or food history yet, so it never replaces workouts or food entries already there. You confirm before anything changes, and the app finishes the restore when it restarts. Until then you can cancel and nothing changes. If the restore doesn't complete correctly, the app automatically puts back the app data that was on your iPhone just before it (such as your settings). It keeps that safety copy on your iPhone for 7 days after a restore, then deletes it the next time the app opens.

**How long backups are kept:** for each iPhone you back up from, we keep **up to** your two most recent backups and one older recovery point, subject to storage limits. Older backups may be removed automatically, and all your devices share your account's storage limit. Unfinished uploads and backups that are no longer kept are removed by an automatic cleanup process, without a guaranteed time.

**Turning it off and deleting:**
- Turning Cloud Backup off stops new backups and **keeps** your existing cloud backups until you delete them.
- **Delete All Cloud Backups** in Settings › Cloud Backup turns backup off and asks our servers to delete your cloud backups. The app tells you whether it finished.
  - If it couldn't finish (for example, you're offline), some or all of your backups may still be stored. Cloud Backup stays off, and you can tap Try Again.
  - Backup files our servers have already released but couldn't remove right away are removed later by an automatic cleanup process, without a guaranteed time.
- Neither changes the history saved on your iPhone.

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
We use data only to run the app's features: your profile, shared workouts, friends, challenges, notifications and, if you turn it on, Cloud Backup. We also use it to respond to feedback and to fix problems. We don't sell or rent personal data, and we don't use it for advertising.

## 8. Service providers
We rely on these providers, each under its own terms:
- **Supabase:** database, sign-in and storage, including Cloud Backup.
- **Apple:** Sign in with Apple, push notifications, TestFlight, Apple Health and on-device intelligence.
- **Open Food Facts and USDA:** food data.

## 9. Keeping and deleting your data
- **Delete your account:** go to Settings › Account › Delete Account. This permanently removes the account data in sections 2, 3 and 4A: your profile, shared workouts, social activity, challenges, notification tokens, photo-accuracy reports and cloud backups.
- **Photos:** the app also deletes your profile photo and any shared meal photos.
  - If your profile photo can't be removed, the app tells you; contact us and we'll remove it.
  - Any shared meal photos left behind are deleted automatically within the 90-day period above.
- **Cloud backups:** the app deletes your cloud backups first. If that can't be confirmed, your account isn't deleted and the app asks you to try again. Backup files left behind after your account is deleted are removed by the automatic cleanup process, without a guaranteed time.
- **What we keep:** if your account's beta-feature access was ever changed, an internal security log keeps your user ID and username with that change.
- **Provider systems:** copies may remain in our providers' systems for a limited time, under their own policies.
- **On your iPhone:** you can delete all data in Settings › Privacy › Manage Data, or by deleting the app.
- **Signing out** never deletes data from your iPhone. If your history belongs to your account, it's hidden after you sign out until you sign back in or unlock it with Face ID or your passcode.

## 10. Security
- Data is sent over encrypted connections, and our backend provider encrypts stored data at rest.
- **Other user accounts** can read and change only what server rules allow, and never your cloud backups.
- **Service access:** authorized Muscle Munch service administrators and our hosting provider can technically access data stored on our servers, including cloud backups, which aren't end-to-end encrypted.
- No system is perfectly secure; please use a passcode on your iPhone.

## 11. Children
Muscle Munch isn't directed to children under 13, and we don't knowingly collect their personal information.

## 12. Changes
If this policy changes, we'll update the date above and, for significant changes, tell testers in the app or in the TestFlight notes.

## 13. Contact
Questions or requests (including access or deletion help): **musclemunchsupport@gmail.com**.
