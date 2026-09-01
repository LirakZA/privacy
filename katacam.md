---
title: KataCam Privacy Policy
---

# KataCam Privacy Policy

**Last updated: 1 September 2026**

KataCam is a camera and media manager for Android, published by Steven Kilian. This policy
describes what the app does with your information. Where a feature could look like it collects
something and does not, that is said explicitly.

## The short version

KataCam has no accounts, no server that stores your content, and no advertising or analytics. Your
photos, videos and documents stay on your device unless you deliberately send them somewhere. The
only information that leaves your device automatically is a crash report, and only if you switch
that on yourself.

## What stays on your device

**Your photos, videos and scanned documents.** KataCam saves them to your device's own storage,
under `DCIM/KataCam` for photos and video and `Documents/KataCam` for scanned PDFs. The app reads
and writes these through Android's media system, and only for files it created or that you have
given it access to. They are never uploaded.

**Your phone's own camera folder.** KataCam can show the photos your phone's built-in camera app
took, in a "Camera Roll" album beside its own. That album is read-only: KataCam will not move,
rename or delete anything in it. Those files are read from your device's own storage and are never
uploaded.

**Deleted items.** Deleting inside KataCam moves the file to a "Deleted" album for three days before
it is removed permanently. During those three days it is still on your device and nowhere else.

**Location, if you turn geotagging on.** Geotagging is off by default. When you switch it on and
grant location access, the app records your position only while the camera screen is open, keeps
only the single most recent reading, and writes it into the photo's own GPS tags — the same tags
every camera app uses. That data lives inside the image file. It is not collected and not
transmitted. If you later share that photo, the location travels inside the file, as it would from
any camera.

**The photo map** reads those tags back to place pins. Android hides the location stored inside
photos that other apps took unless you allow it, so the map asks you once: allow, and it shows every
photo on the phone that carries a location; decline, and the map still works, showing the photos
KataCam tagged itself. Map imagery comes from OpenStreetMap; your photos and their coordinates are
never sent to OpenStreetMap or anyone else.

**The map's index.** Opening a photo to read its tags is slow, and the answer never changes, so
KataCam keeps a list on the device of which photo had which coordinates rather than re-reading your
whole library every time. It is held in the app's own private settings, is never transmitted, is
discarded and rebuilt if your answer to the permission above changes, and is removed when you
uninstall the app.

**Your settings**, such as the current album and whether geotagging is on, are stored on the device.

## What leaves your device, and when

### Transfers you start yourself

KataCam has two features for moving files off your phone. Both work only over your local network,
both require you to start them, and both stop automatically after five minutes of inactivity.

- **Send to PC** runs a read-only file server on your phone that your computer connects to over
  Wi-Fi. It is protected by a six-digit code shown on screen, which changes every session. Files are
  only ever read from your phone, never written to it. Nothing passes through the internet or any
  server operated by us.
- **Send to Phone** sends files directly to another phone running KataCam on the same Wi-Fi network,
  after the receiving phone accepts. The receiving device is shown a name for your phone that
  includes your device model and a short code derived from your device's Android ID, used only to
  tell two similar phones apart on the network.

These transfers are not encrypted, because they do not leave your local network. Treat them as you
would any file sharing on a network you control, and avoid using them on public Wi-Fi.

### Crash reports — off unless you turn them on

Automatic crash reporting is **disabled by default**. If you enable it in App Info, then when the app
crashes it sends a report containing the app version, your Android version, your device brand and
model, the technical stack trace of the crash, the app's package name, and when the app was started.

It does not include your photos, your videos, your file names, your location, your contacts, your IP
address, or anything that identifies you personally.

### Bug reports and feedback you send

App Info has "Report a bug" and "Send feedback" buttons. These send only when you press send, and
they include the text you typed plus the same technical details listed above. Please do not type
personal information into that box.

**Where reports go:** to a routing service (Pipedream) which forwards them to a private developer
channel on Discord. They are used only to diagnose faults and act on feedback, are visible only to
the developer, and are never sold, shared, or used for advertising. They are kept only as long as
they are useful for fixing the issue.

**These reports leave your country.** Pipedream and Discord are both operated from the United
States, so a report you send travels there, and the two companies handle it under their own terms.
Nothing in a report identifies you, and nothing is sent at all unless you switch automatic crash
reporting on or press Send yourself.

### Map tiles

Opening the photo map downloads map imagery from OpenStreetMap for the area you are viewing.
OpenStreetMap therefore sees a request for that map area and your IP address, as any website does.
Your photos and their coordinates are never sent. OpenStreetMap's policy applies to those requests:
<https://wiki.osmfoundation.org/wiki/Privacy_Policy>

### Document scanning

The document scanner is provided by Google's ML Kit and runs inside a Google-supplied component that
downloads on first use. Scanning happens on your device. Google's privacy policy covers that
component: <https://policies.google.com/privacy>

### Purchases

KataCam is free for seven days, after which continued use requires a single one-off purchase. That
purchase is handled entirely by the app store you installed from — Huawei AppGallery or Google Play
— through that store's own purchasing software, running on your phone. We never see or store your
payment details. The store tells the app only whether this installation has paid, and that answer is
remembered on the device so the app keeps working when you have no signal.

The store's own privacy policy covers the purchase itself:
<https://consumer.huawei.com/en/privacy/privacy-policy/> for AppGallery, and
<https://policies.google.com/privacy> for Google Play.

## Permissions, and why each one exists

| Permission | Why |
|---|---|
| Camera | To take photos and video |
| Microphone | To record sound with video. Not used for photos |
| Photos and videos | To show, organise and manage your media |
| Location (optional) | Only to write GPS tags into photos you take, when geotagging is on |
| Media location (optional) | To read the GPS tags already inside photos on this phone, so the map can include photos other apps took. Declining leaves the map working with KataCam's own |
| Network and Wi-Fi state | For local transfers, and to download map tiles |
| Notifications | To show the ongoing transfer notice and its Stop button |
| Vibrate | Shutter feedback |
| Hide overlay windows | To ask that floating bubbles belonging to other apps be hidden while KataCam is open, so nothing sits on top of the camera. It hides nothing of the system's own, and grants no access to anything |

KataCam may also ask, once, for access to its own folder (`DCIM/KataCam`) so it can remove empty
folders left behind when you delete an album. You choose that folder yourself in Android's file
picker, access is limited to it, and declining changes nothing except that the empty folders remain.

Location can be refused, or revoked later, and every other feature continues to work.

## Your choices in KataCam

- **Turn off crash reporting** at any time in App Info. It is off unless you turned it on.
- **Turn off geotagging** at any time in the camera settings, or revoke location access in Android
  settings.
- **Delete everything** by uninstalling the app. Uninstalling removes the app's settings. Photos and
  videos you took remain in your device's own storage, because they are your files.

{% include common.md %}
