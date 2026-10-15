---
title: Privacy Policy — Ryesoma
permalink: /privacy/
---

# Privacy Policy — Ryesoma

**Last updated: 7 October 2026**

## The short version

Ryesoma is made by Weft Witch Labs ("we" below). It has no accounts and no server. Everything you record — what you ate, your
symptoms, medications, measurements, recipes, photographs — is stored on your device and stays
there. We do not collect it, we cannot see it, and there is nowhere for us to send it.

That is not a promise about intent. It is a description of how the app is built: there is no
backend to receive anything.

## What the app stores, and where

| | |
|---|---|
| Your food log, symptoms, medications, measurements, habits, notes, workouts, places you name, pantry, shopping list, recipes and plans | An encrypted database file on your device |
| Data you choose to bring in from Apple Health or a Strava export | The same encrypted database |
| Photographs and videos you add | Files on your device, in the app's own storage |
| Your preferences, and your PIN if you set one | On your device |

Deleting the app removes all of it. Settings also offers **Erase everything and start fresh**, which
deletes your data, your photographs, and any stored sync credentials from the device.

## What leaves your device

Two things, neither of which carries anything about you, and both only when you use them.

**Food recall notices.** If you turn on food recalls, the app fetches public recall lists from the
US FDA (`api.fda.gov`), the US FSIS (`fsis.usda.gov`) and, for UK alerts, the Food Standards Agency.
Those requests carry only a date range and a status — never your pantry, your shopping list, or
anything else about you. **The matching happens on your device**, against a copy of the list the app
has downloaded. We never send anyone a list of what is in your kitchen.

**Recipes you import from a web address.** When you paste a link to a recipe, the app fetches that
one page directly from the site it is on, the way a browser would, and keeps a copy on your device.
The site sees an ordinary request for its page. Pictures in an imported recipe may be loaded from
that site when you view it. Nothing about you or your other data is sent with either.

**Nothing else.** The app contacts no analytics service, no crash reporter and no advertising
network. It contains no tracking SDKs. Its privacy manifest declares no collected data and no
tracking domains.

## If you choose to share a pantry or a cookbook

This is optional and off unless you set it up.

If you turn it on, you choose where the shared file lives — a repository or storage account you
control, or a file or folder in iCloud Drive or another provider on your device. The app writes
**one AES-256 encrypted file** there. The passphrase is yours, is set by you, and is never sent
anywhere: without it the file cannot be read, including by us.

We are not a party to that arrangement. Your data goes to storage you already own, under a
passphrase we never see. The credentials you give the app to reach that storage (for example an
access token) are kept on your device and are removed by "Erase everything and start fresh".

## Camera and photos

The app asks for the camera when you photograph a recipe, a product label, or an exercise, and when
you scan a barcode. It asks for your photo library only when you choose an existing picture.

Photographs you add stay in the app's own storage. They are not copied to your camera roll unless
you ask for that. **Location and other metadata are removed from photographs** the app stores.

## Health information

The app can record symptoms, medications, menstrual cycles and body measurements. This is health
information and it is treated the same way as everything else: it is stored on your device and it
is not transmitted.

## Apple Health

If you connect it in Settings, the app **reads** heart rate (including resting and walking
averages), heart-rate variability, blood oxygen, respiratory rate, body temperature, VO2 max, steps,
distance, flights climbed, active and resting energy, sleep and workouts from Apple Health, so they can appear alongside the
rest of your day. It never writes to Apple Health. You choose which of these to allow, and can change
that at any time in the Health app.

What it reads is stored in the same encrypted database as everything else and never leaves your
device. It is not sent to us or anyone else, it is not included in a shared pantry or cookbook, and
it is never used for advertising, marketing or any purpose other than showing it back to you. It is
included in a backup you export, because a backup is meant to be complete, and that file goes only
where you send it.

You can also import a Strava activity export (a file you download from Strava yourself). The app
reads that file on your device and does not connect to Strava.

## Children

The app is not directed at children and does not knowingly collect information from anyone.

## Backups you make yourself

You can export a backup file, optionally including your photographs. Where that file goes is up to
you — your Files app, your computer, wherever you send it.

You can set a passphrase when you make one, and the file is then encrypted with AES-256 before it
leaves the app. The passphrase is yours and is never sent anywhere: without it the file cannot be
opened by anyone, including us, and there is no way to recover it. Without a passphrase the backup
is plain text you can read yourself — which is sometimes what you want — so keep it somewhere you
are comfortable with.

There is also a **readable copy** — a spreadsheet, or plain CSV files — for opening in Excel,
Numbers or anything else, or for showing to a clinician. It can be put in a password-protected zip
if you want. That copy is for reading and does not restore.

Your device's own backup (iCloud or a computer) may include the app's data, under Apple's terms
rather than ours. The food database is not part of that backup: it ships inside the app itself, and
iOS does not back up app bundles.

## Your rights

Because we hold nothing about you, there is nothing for us to disclose, correct or delete on your
behalf. Your data is in your hands: exportable from Settings, and erasable from the same screen or
by deleting the app.

## Changes

If this policy changes, the date at the top changes with it, and every earlier version stays public
in the history of the repository this page is published from.

## Contact

Questions about this policy: **[support@weftwitchlabs.com](mailto:support@weftwitchlabs.com)**
