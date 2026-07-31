# fontART Designer — trial version ✍️

**Your handwriting, as a real typeface.** Draw the letters with a mouse, a pen or your finger; fontART turns them into a `.ttf` file you install in Windows and then use in Word, LibreOffice or Canva.

This repository is the home of the **free trial** — in two flavours: a page that runs in your browser (on a phone too), and a program for Windows. Both are built from the same source and can do the same things.

![Browser](https://img.shields.io/badge/Browser-phone%20too-a21caf) ![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-c026d3) ![Export](https://img.shields.io/badge/Export-a%E2%80%93z%20only-e879f9) ![No install](https://img.shields.io/badge/No-installation-eac54f)

**→ [Open in your browser](https://dennismit2n.github.io/fontART-demo/)** · **[Download for Windows](https://github.com/Dennismit2n/fontART-demo/releases/latest)** · [Deutsche Fassung dieser Datei](README.de.md) · [Guide and news](https://dennismit2n.github.io/werkstatt.html#fontart)

## Which one for whom

| | |
|---|---|
| 📱 **In the browser** | One click and you are drawing — with a finger or a pen, which on a touchscreen is closer to handwriting than any mouse. No time limit. On an iPhone please use **Safari**: inside the in-app browsers of Instagram, Facebook or WhatsApp, downloading the finished font fails. |
| 🖥️ **For Windows** | The program sits closer to the full version and runs **60 minutes per start**. In exchange you can install the finished font right away and try it in Word — the proof that cannot happen on a phone. |

**About phones:** a font file cannot be installed as a system font on Android or iOS. What you draw on a phone you export as a `.ttf` and send to yourself — installing happens on a computer. The phone is the better drawing device, the computer the better installing one.

---

## Before you download the Windows version: Windows will warn you

The file is not signed with a code-signing certificate, so Windows SmartScreen shows a blue box saying **“Windows protected your PC — unknown publisher”**. Click **“More info”**, then **“Run anyway”**.

That warning is not about a virus; it means nobody paid for a certificate yet. If that is not good enough for you, do not run it — that is a perfectly reasonable position, and the honest thing is to say so here rather than to talk you past it.

## What the trial does — and what it does not

| | |
|---|---|
| ✏️ **Every tool is unlocked** | Drawing, construction lines, the ghost glyph for comparison, sidebearings, kerning suggestions, the kerning editor, the typing test, the maturity analysis, the character map. Nothing is greyed out to nag you. |
| 💾 **Saving and loading work fully** | Your project is a `.fontart.json` file. Save it, load it again, carry on — including after the clock has run out. |
| ⏳ **60 minutes per start — Windows only** | The clock starts with the program and cannot be paused; a minimised window keeps counting. When time is up, drawing and exporting stop. Saving keeps working, so you never lose your drawing. **In the browser there is no clock:** reloading would be the way around it anyway, and what is locked here is the result, not the time. |
| 🔤 **Export is a–z, nothing else** | The font file contains the lowercase letters only. You can draw capitals, digits, umlauts, ß and punctuation — they simply do not travel into the file. |
| 🏷️ **The font is always called “fontART DEMO”** | Whatever you type into the name field is ignored on export. Two demo fonts therefore cannot live side by side: Windows would see the same name twice. |
| 🚫 **One way out, not six** | `.ttf` only. No `.woff`, no specimen sheet, no complete package, no bold or italic companion, no practice sheet, no video capture — those are not disabled in this build, they are not in it. |

## In three steps

1. **[Open it in your browser](https://dennismit2n.github.io/fontART-demo/)** — or, for Windows, **[download the `.exe`](https://github.com/Dennismit2n/fontART-demo/releases/latest)** and start it. Either way, nothing gets installed.
2. Pick a character from the bar and **paint the black shape** of the letter, not its outline. Start with `n` and `o` — those two set the rhythm of the whole typeface. If your hand shakes, pull up the **stabiliser**.
3. **⬇ Export › .ttf.** In Windows, right-click the file and choose *install for all users*. Your typeface then appears in Word as **fontART DEMO**.

## Privacy

fontART sends nothing. Not in the sense of “we promise not to”, but: there is no code in it that could. A search across the whole program for `fetch`, `XMLHttpRequest`, `WebSocket` and `sendBeacon` returns **nothing**. There is no visitor counter — not even in the browser version, unlike every other tool in this workshop. No update check, no crash reporting, no font catalogue being consulted.

One difference deserves saying out loud: **the Windows version never touches the network at all.** The browser version has to be loaded once, and GitHub sees that somebody fetched the page — as with any website. After that it stops: what you draw stays in your browser. You do not have to take my word for it — open the developer tools, watch the network tab, draw and export: not one further request goes out.

The only address in the program is the link to the guide on the workshop page — and it only opens when you click it, in your own browser.

Your drawings live in memory and in the file you save yourself. Nothing is uploaded, because there is nowhere for it to go.

## The full version

The full version draws all **333 characters** instead of 26 — upper and lower case, digits, umlauts, ß, punctuation, plus Greek, Cyrillic and the Japanese syllabaries — it carries the name you type in, and it has the ways out that are missing here: `.woff` for websites, specimen sheet, complete package, bold and italic companions, ligatures, PUA symbols, colour shadows, practice sheets and video capture.

It is being worked on. **When it will be finished, and how it will be available, is not settled yet.** Watch this repository and you will see it when it happens. There is no waiting list, no newsletter, and the trial will never ask for your email address.

Why this one tool is meant to cost money at all, when the rest of the workshop is free and open: [the guide answers that honestly](https://dennismit2n.github.io/werkstatt.html#fontart).

## Rights

**This is not open source.** The source code of fontART is not published. What lives in this repository is the built and minified page — technically readable, because a browser has to run it, but neither the source nor meant for building upon. No licence is granted beyond the following: you may use the trial free of charge, privately and commercially, and pass the unmodified `.exe` on to whoever you like. Everything else — decompiling, modifying, reselling — is not permitted.

**What you draw belongs to you.** The fonts you export are yours without restriction: use them, sell things made with them, give them away. Neither the trial nor the full version claims anything on your work.

© 2026 Dennis (Dennismit2n) · [More small tools](https://dennismit2n.github.io/)
