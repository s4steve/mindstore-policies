---
title: Privacy Policy
permalink: /privacy/
---

# BrainClone — Privacy Policy

_Last updated: 24 September 2026_

## The short version

BrainClone collects nothing. There is no server to collect it with.

BrainClone runs on iPhone and on Mac. Everything you write, say, or ask stays on
your own devices and in your own private iCloud, which is also how your iPhone and
your Mac stay in step with each other. No account, no sign-up, no analytics, no
advertising identifiers, no crash reporting, no third-party SDKs.

This is not a promise about how carefully we handle your data. There is no "we"
that ever receives it. The app never makes a network connection of its own.

## What runs where

Every AI feature runs **on the device you are using**, using frameworks built into
iOS and macOS:

| Feature | Runs on | Leaves the device |
|---|---|---|
| Dictation (speech to text) | Your iPhone or Mac | No |
| Clean up (tidying a rambled note) | Your iPhone or Mac | No |
| Search | Your iPhone or Mac | No |
| Answers (a question answered from your notes) | Your iPhone or Mac | No |

There is no call to OpenAI, Anthropic, Google, or any other AI service, paid or
free. There is no API key in this app because there is nothing to authenticate to.

**Answers** deserve a specific word, because "an AI reads my notes" is exactly the
sentence that should make you suspicious. When you ask a question, the app searches
your own entries, selects a few hundred words of the closest ones, and passes them
to Apple's on-device language model to write the answer. That model runs inside the
device in your hand. The excerpts are not uploaded, not logged, and not retained
after the answer is written. The answer is shown with the entries it came from, so
you can always see what it read.

Clean up and answers require Apple Intelligence: an iPhone 15 Pro or newer, or a
Mac with Apple silicon. Without it those two features are unavailable — capture,
search, sync and everything else work normally.

The first time you dictate, iOS or macOS may download a speech model from Apple.
That is a download **from** Apple, not an upload of anything of yours.

## iPhone and Mac, kept in step by your iCloud

BrainClone on your iPhone and BrainClone on your Mac are the same app reading the
same entries. They do not talk to each other directly, and they do not talk to us.
Each one keeps its own copy of your entries on the device, and each one
synchronises that copy through **CloudKit**, using the **private database** of the
iCloud account the device is signed in to. Anything you add, change or delete on one
arrives on the other the next time it syncs.

That means:

- Both devices need to be signed in to the **same Apple Account**, with iCloud
  enabled for BrainClone. Nothing else links them — no code, no pairing, no account
  with us.
- The data counts against your personal iCloud storage, not ours.
- We cannot read it. A private CloudKit database is accessible only to the Apple
  Account that owns it. The developer of this app has no access, no dashboard, and
  no ability to grant access to anyone else.
- Apple's handling of iCloud data is covered by
  [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

If a device is signed out of iCloud, or iCloud is turned off for BrainClone, the app
on that device keeps working and stores everything locally only. Nothing it holds
syncs to your other devices, and nothing is backed up.

The Mac app is sandboxed by macOS, and is allowed to make network connections only
so that Apple's own frameworks can do their jobs for it: CloudKit sync, the App
Store purchase check, and that one-time speech model download. The app itself still
never makes a network connection of its own.

## The one asterisk: Siri

BrainClone can be driven by Siri and Shortcuts — "add a thought to BrainClone", and
so on. When you do that, **Siri transcribes what you said, not BrainClone.** Your
words go through Apple's speech stack rather than the app's, which on Apple
Intelligence hardware means on-device processing or Apple's Private Cloud Compute,
under [Apple's Privacy Policy](https://www.apple.com/legal/privacy/) rather than
this one.

What BrainClone then stores still never leaves your devices and your iCloud. But
"transcription happens on this device" is a claim about the app, and it stops being
ours to make the moment Siri is in the path. If that distinction matters to you,
dictate inside the app rather than through Siri, and it never applies.

## Permissions the app asks for

- **Microphone** — to record what you dictate. Audio is transcribed on the device
  and is not retained after the transcript is produced.
- **Speech recognition** — to turn that audio into text on the device.
- **Notifications** — optional, and only used to remind you about things you
  scheduled yourself. Nothing is sent from anywhere; the reminders are scheduled
  locally by the app.

Each of these can be refused or withdrawn in Settings on iPhone or System Settings
on Mac. Refusing any of them disables that feature and nothing else.

On the Mac, BrainClone also offers a keyboard shortcut for quick capture. It is
registered with macOS as a single shortcut; the app does not watch or record your
other keystrokes, and asks for no accessibility or input-monitoring permission.

## Getting things into BrainClone

- **On iPhone**, BrainClone has a share extension, so you can send text or a link to
  it from another app. What you share is written to a private container on your
  phone that only BrainClone and its extension can read, and the app files it as an
  entry the next time you open it. If it cannot be saved then, it stays in that
  container until it can. It goes nowhere else.
- **On Mac**, you can drop text or a text file onto the window, or use **Capture in
  BrainClone** from the Services menu of another app. Either way the app receives
  only what you chose to hand it, and files it as an entry.

## Taking your data out

BrainClone can export everything it holds as a single JSON file. You choose where
that file is saved, and where it goes afterwards is entirely your decision. It is
worth saying plainly that this is the one path by which your entries can leave your
devices and your iCloud, and that it only ever happens because you chose it.

Export works whether or not you have paid. If you stop using BrainClone, you can
always get your data out.

## Purchases

The one-time purchase that removes the free tier's entry limit is handled entirely
by Apple's App Store, and one purchase covers both the iPhone and the Mac app. We
never see your payment details, name, address, or Apple Account. The app checks
whether the purchase exists using StoreKit's on-device verification — there is no
purchase server, and no record of your transaction is sent to us.

## Children

BrainClone is a personal notes app with no social features, no user-generated
content shared with anyone, and no advertising. It collects no data from anyone,
including children.

## Deleting your data

Deleting an entry in the app removes it, and the deletion syncs to your other
devices. Deleting the app from a device removes that device's copy. To remove the
synced copy as well, delete BrainClone's data in iCloud storage:
**Settings → [your name] → iCloud → Manage Account Storage** on iPhone, or
**System Settings → [your name] → iCloud → Manage** on Mac.

Deleting is never restricted by the free tier's limit, and neither is reading,
searching or exporting. The limit applies only to creating new entries.

We have nothing to delete on our side, because we never had anything.

## Changes

If this policy ever changes, the updated version will be posted at this address with
a new date at the top. Since the app collects nothing, any change would be about
clarity rather than about new data collection — and if that ever stopped being true,
it would be announced in the app itself, not quietly here.

## Contact

Questions about this policy: **[steve.whittle@gmail.com](mailto:steve.whittle@gmail.com)**
