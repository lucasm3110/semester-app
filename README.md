# Semester

A local-first academic workspace for macOS. Notes, tasks, your class schedule,
files and lecture recordings for the whole term — in one app, on your Mac.

**[Download Semester 1.2.0 →](https://github.com/lucasm3110/semester-app/releases/latest)**

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
- **Notebooks** — a place for everything that isn't coursework. The same
  notes, files and recordings, without a timetable, carried across terms.
- **Files** — PDFs and images with annotations, filed by course or left unfiled.
- **Textbooks** — hundreds of pages, scrolled properly, with a jump to any
  page number.
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
   [the latest release](https://github.com/lucasm3110/semester-app/releases/latest).
2. Open it and drag **Semester** into Applications.
3. Open it.

That is all. Semester is signed and notarised by Apple, so macOS opens it like
any other app — no warning, no right-click, no Terminal.

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
