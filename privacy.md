---
title: Privacy Policy
permalink: /privacy/
---

# MindStore — Privacy Policy

_Last updated: 1 September 2026_

## The short version

MindStore collects nothing. There is no server to collect it with.

Everything you write, say, or ask stays on your iPhone and in your own private
iCloud. No account, no sign-up, no analytics, no advertising identifiers, no crash
reporting, no third-party SDKs.

This is not a promise about how carefully we handle your data. There is no "we"
that ever receives it. The app contains no networking code at all, and the only
capabilities it requests from iOS are your own private iCloud database and a
container shared with its own share extension.

## What runs where

Every AI feature runs **on the device**, using frameworks built into iOS:

| Feature | Runs on | Leaves the device |
|---|---|---|
| Dictation (speech to text) | Your iPhone | No |
| Cleanup (tidying a rambled note) | Your iPhone | No |
| Semantic search | Your iPhone | No |
| Ask (answering a question from your notes) | Your iPhone | No |

There is no call to OpenAI, Anthropic, Google, or any other AI service, paid or
free. There is no API key in this app because there is nothing to authenticate to.

**Ask** deserves a specific word, because "an AI reads my notes" is exactly the
sentence that should make you suspicious. When you ask a question, the app searches
your own entries, selects a few hundred words of the closest ones, and passes them
to Apple's on-device language model to write the answer. That model runs inside your
phone. The excerpts are not uploaded, not logged, and not retained after the answer
is written. The answer is shown with the entries it came from, so you can always see
what it read.

Cleanup and Ask require Apple Intelligence, which needs an iPhone 15 Pro or newer.
On older iPhones those two features are unavailable — capture, search, sync and
everything else work normally.

The first time you dictate, iOS may download a speech model from Apple. That is a
download **from** Apple, not an upload of anything of yours.

## The one asterisk: Siri

MindStore can be driven by Siri and Shortcuts — "add a thought to MindStore", and so
on. When you do that, **Siri transcribes what you said, not MindStore.** Your words
go through Apple's speech stack rather than the app's, which on Apple Intelligence
hardware means on-device processing or Apple's Private Cloud Compute, under
[Apple's Privacy Policy](https://www.apple.com/legal/privacy/) rather than this one.

What MindStore then stores still never leaves your phone. But "transcription happens
on this device" is a claim about the app, and it stops being ours to make the moment
Siri is in the path. If that distinction matters to you, dictate inside the app
rather than through Siri, and it never applies.

## Where your data is stored

Your entries are stored in a database on your iPhone and synchronised through
**CloudKit**, using your own iCloud account's **private database**. This means:

- The data counts against your personal iCloud storage, not ours.
- We cannot read it. A private CloudKit database is accessible only to the Apple ID
  that owns it. The developer of this app has no access, no dashboard, and no
  ability to grant access to anyone else.
- Apple's handling of iCloud data is covered by
  [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

If you are signed out of iCloud, or turn iCloud off for MindStore, the app keeps
working and stores everything locally only. Nothing syncs, and nothing is backed up.

## Permissions the app asks for

- **Microphone** — to record what you dictate. Audio is transcribed on the device
  and is not retained after the transcript is produced.
- **Speech recognition** — to turn that audio into text on the device.
- **Notifications** — optional, and only used to remind you about tasks and home
  items you scheduled yourself. Nothing is sent from anywhere; the reminders are
  scheduled locally by the app.

Each of these can be refused or withdrawn in iOS Settings. Refusing any of them
disables that feature and nothing else.

## Sharing into MindStore

MindStore has a share extension, so you can send text or a link to it from another
app. What you share is written to a private container on your phone that only
MindStore and its extension can read, and the app files it as an entry the next time
you open it. It goes nowhere else.

## Taking your data out

MindStore can export everything it holds as a single JSON file. That file is yours,
and where it goes afterwards is entirely your decision — the app hands it to iOS's
standard share sheet and takes no further part. It is worth saying plainly that this
is the one path by which your entries can leave your phone, and that it only ever
happens because you chose it.

Export works whether or not you have paid. If you stop using MindStore, you can
always get your data out.

## Purchases

The one-time purchase that removes the free tier's entry limit is handled entirely
by Apple's App Store. We never see your payment details, name, address, or Apple ID.
The app checks whether the purchase exists using StoreKit's on-device verification —
there is no purchase server, and no record of your transaction is sent to us.

## Children

MindStore is a personal notes app with no social features, no user-generated content
shared with anyone, and no advertising. It collects no data from anyone, including
children.

## Deleting your data

Deleting an entry in the app removes it. Deleting the app removes the local
database; to remove the synced copy as well, delete MindStore's data in
**Settings → [your name] → iCloud → Manage Account Storage**.

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
