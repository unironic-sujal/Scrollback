# Scrollback

> **Browse every photo and video from your Instagram DMs — organized like a gallery.**

<div align="center">

![Scrollback](./banner-image)

[![Live](https://img.shields.io/badge/Live%20at-scrollback.in-a855f7?style=for-the-badge&logo=vercel&logoColor=white)]([https://scrollback.in](https://scrollback.vercel.app/))
[![Status](https://img.shields.io/badge/Status-Active-22c55e?style=for-the-badge)]()
[![Privacy](https://img.shields.io/badge/Privacy-100%25%20Local-38bdf8?style=for-the-badge&logo=shield&logoColor=white)]()

</div>

---

## The Problem

You sent an important photo in an Instagram DM three years ago. Now you want it back.

Instagram gives you no way to browse your media. No gallery view. No search. Just endless scrolling through thousands of messages hoping you find it.

Instagram *does* store everything — in your data export. But the export is a mess of JSON files and folders that's practically unusable.

**Scrollback fixes that.**

---

## What It Does

Scrollback turns your Instagram data export into a clean, searchable media gallery — entirely in your browser. Nothing is uploaded. Nothing leaves your device.

<div align="center">

| Before | After |
|---|---|
| Scrolling forever in the Instagram app | Gallery view, sorted by date |
| No way to find who sent what | Filter by sender |
| Can't browse by time | Filter by year, month, or date range |
| Saving photos one by one | Bulk select + download as ZIP |
| Export files unreadable | Instant gallery from your folder |

</div>

---

## Features

- **📁 Instant gallery** — open your export folder, see everything immediately
- **🗓 Sorted by date** — chronological view with month dividers, just like your camera roll
- **👤 Filter by sender** — see only photos from a specific person
- **📅 Filter by time** — year, month, or custom date range
- **⬇️ Download media** — single file from the lightbox, or bulk select + ZIP
- **🔒 100% private** — runs entirely in your browser, zero server involvement
- **📱 Mobile friendly** — works on phones too
- **🎬 Videos too** — photos and videos in one seamless gallery

---

## How It Works

```
1. Request your Instagram data export
   Settings → Your Activity → Download Your Information
   (select JSON format — takes a few hours to arrive)

2. Extract the ZIP and open Scrollback
   scrollback.in → Choose Folder → select your extracted folder

3. Done
   Every photo and video from every DM, organized instantly
```

No account linking. No API access. No uploads. Just your local files.

---

## Privacy

Your data never leaves your device. Scrollback reads your local folder directly in the browser using the File System Access API. There is no server that receives your photos, videos, or any personal data.

The only network requests Scrollback makes:
- Authentication (Clerk) — for saving your plan
- Payment processing (Dodo Payments) — if you upgrade

That's it. Your media stays on your machine.

---

## Pricing

| Plan | Price | Chats |
|---|---|---|
| Free | $0 forever | 1 chat gallery |
| Unlimited | $5 one-time | All chats, forever |

No subscription. No monthly fees. Pay once.

---

## Built With

- **Next.js 14** — framework
- **Clerk** — authentication
- **Supabase** — user plan storage
- **Dodo Payments** — one-time payments
- **JSZip** — client-side ZIP generation
- **Lucide** — icons
- **Vercel** — hosting

> Source code is private. This repository is the public project showcase.

---

## Roadmap

- [x] Media gallery from Instagram DM export
- [x] Filter by sender, year, month, date range
- [x] Sort newest / oldest
- [x] Grid size toggle (small / medium / large)
- [x] Single file download from lightbox
- [x] Bulk select + ZIP download
- [x] Mobile responsive
- [ ] Search by filename / date
- [ ] Stats page (total media, top senders, most active months)
- [ ] WhatsApp export support
- [ ] Telegram export support

---

## Links

- 🌐 **Live app:** [scrollback.vercel.app](https://scrollback.vercel.app/)
  
---

## Contact

Built by [@unironic-sujal](https://github.com/unironic-sujal)

Found a bug or have a feature request? [Open an issue](https://github.com/unironic-sujal/scrollback/issues) in this repo.

---

<div align="center">

**If this is useful to you, consider starring the repo ⭐**

</div>
