# Privacy Policy

**Notesidian** · Milkbar Software
Last updated: July 11, 2026

Notesidian is a native macOS menu-bar companion for [Obsidian](https://obsidian.md). It is
built to be private by design: it works entirely on your Mac, and **it collects no personal
data whatsoever.**

## The short version

- **No data collection.** Notesidian gathers no personal information about you.
- **No tracking, no analytics, no advertising, no third-party SDKs.**
- **No account and no sign-in.**
- **No servers.** Notesidian does not send your notes, or any other information, to Milkbar
  Software or to anyone else.

## What Notesidian accesses (and where it stays)

- **Your notes.** Notesidian reads and writes Markdown files in the Obsidian vault folder you
  choose. That content lives on your Mac (and in whatever file sync *you* have set up for that
  folder, such as iCloud Drive, OneDrive, Dropbox, or Obsidian Sync). Notesidian never copies
  your notes anywhere else. Access to the folder is granted by you through the standard macOS
  open panel and is confined by the App Sandbox.
- **App settings and tab layout.** Your preferences and per-vault tab configuration are stored
  locally on your Mac and mirrored through **your own iCloud account** (Apple's iCloud
  key-value storage) so your setup follows you across your Macs. This information moves only
  between your devices and Apple's iCloud; the developer has no access to it and never receives
  it. iCloud's handling of that data is governed by [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).
  The vault's location on disk is stored **only on the individual Mac** and is never synced.
- **Diagnostics.** If macOS reports a crash or hang via Apple's on-device MetricKit framework,
  Notesidian records it in the local system log for troubleshooting. This stays on your Mac and
  is not transmitted anywhere.

## Network use

Notesidian makes no network connections of its own. When you click a web link in a note, or
click a `[[wikilink]]`, Notesidian asks macOS to open it in your default browser or in Obsidian
— the same as clicking any link. Notesidian does not transmit any data in the process.

## Children

Notesidian collects no data from anyone, including children.

## Changes to this policy

If this policy changes, the updated version will be posted here with a new "Last updated"
date. Material changes will be noted in the app's release notes.

## Contact

Questions about privacy? Open an issue at
[github.com/milkbar/notesidian](https://github.com/milkbar/notesidian/issues), or email
**privacy@milkbar.com**.

— Milkbar Software
