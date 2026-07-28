# Semester

A local-first academic workspace for macOS. Notes, tasks, your class schedule,
files and lecture recordings for the whole term — in one app, on your Mac.

**[Download Semester 1.0.0 →](https://github.com/lucasm3110/semester-app/releases/latest)**

Apple Silicon · macOS 10.15 or later · Works offline

---

## What it is

Semester is one place for a term's worth of work, built around the way a
semester actually runs rather than around a generic notebook.

- **Today** — what is behind, what is due, what is on the clock, on one screen.
- **Notes** — a real editor with wikilinks, callouts, tables, maths and code.
  Every note is mirrored to plain Markdown on disk as you type.
- **Tasks** — typed in one line. "essay friday 5pm 2h" parses as you write it.
- **Calendar** — your class timetable and events together, with per-day
  exceptions for the week a class moves online or gets cancelled.
- **Files** — PDFs and images with annotations, filed by course or left unfiled.
- **Recordings** — record a lecture from anywhere in the app, and transcribe it
  on this Mac only when you ask.
- **Focus** — a timer that lives in the menu bar.

## What it does not do

- No account, no sign-in, no cloud, no telemetry, no analytics.
- Nothing touches a network unless you turn on quick answers or Reminders sync,
  and then only what you asked for goes out.
- Your notes are Markdown files in a folder. If you stop using Semester
  tomorrow, your writing is still readable without it.

## Install

1. Download the `.dmg` from
   [the latest release](https://github.com/lucasm3110/semester-app/releases/latest)
   and drag **Semester** into Applications.
2. Open it once. macOS will say it cannot check the app for malicious
   software — click **Done**. This is expected.
3. Open **System Settings → Privacy & Security**, scroll to **Security**, and
   click **Open Anyway** next to the message about Semester. Authenticate when
   asked. You only do this once.

Or, in one line:

    xattr -dr com.apple.quarantine /Applications/Semester.app

Both do the same thing.

### Why macOS blocks it

Semester is not notarised by Apple. Notarising requires a paid Apple Developer
account, which this app does not have, so macOS cannot confirm who built it.

The warning is about the **absence of a signature Apple recognises**, not about
anything found in the app. The source is not public, so if you are not
comfortable running un-notarised software, do not install it — that is a fair
call to make.

On macOS 15 and later the old right-click → Open trick no longer works for
un-notarised apps. **Open Anyway** in System Settings replaced it.

## Transcription

Transcription is optional and off until you ask for it. Pressing **Install** in
Settings → Recordings builds [whisper.cpp](https://github.com/ggml-org/whisper.cpp)
on your machine and downloads a speech model once. Everything then runs
offline, and no audio leaves the Mac.

## Requirements

- Apple Silicon (M1 or later). There is no Intel build.
- macOS 10.15 or later.

## Support

Found a problem? [Open an issue](https://github.com/lucasm3110/semester-app/issues).

This repository hosts the downloads. The source is kept privately.
