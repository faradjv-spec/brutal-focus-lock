# Brutal Focus Lock

**Every other focus app asks. This one enforces.**

A Windows focus and exam-lockdown tool with a floating timer, optional browser blocking, and stricter exam sessions. You can always use `Ctrl+Shift+Q` as an emergency exit.

**[⬇ Download the latest release](../../releases/latest)** · Windows 10/11 · Free · No account or telemetry

---

## Why this exists

Forest can be closed. Freedom can be uninstalled. Cold Turkey stops at the browser. All of them assume you'll cooperate with yourself. This one is built for the twenty minutes where you won't.

Focus sessions can be stopped from the timer. Exam sessions add a keyboard hook and a panic phrase for ordinary early exit. The emergency shortcut remains available in either mode.

## What each mode enforces

- **Focus session** — floating timer; your blocklist is enforced in supported browsers only when the optional companion extension shows **PAIRED**. Without it, the list is a visible reminder, not an active block.
- **Exam session** — keyboard hook limits task switching. With a nonempty blocklist and your approval of the Windows prompt, the app adds hosts-file entries and removes them when the session ends.
- **Exam browser choice** — use your normal browser for the best sign-in compatibility, or opt into the locked app window. The optional extension can add browser-side blocking in your normal browser.

## The contract

1. The timer is the only clean exit.
2. Quitting early costs a 25–60 character panic phrase built from your own stated goals.
3. The anti-streak never forgets. Only a completed session resets it.
4. The exam setup shows which browser will open and what blocking is available before you start.
5. Killing your browser mid-exam starts a 30-second countdown.
6. **`Ctrl+Shift+Q` always works.** Safety is never gated.

## Emergency exit

Press **`Ctrl+Shift+Q`**. It force-quits everything instantly — no admin prompt, no phrase, and the keyboard hook never intercepts it.

After `Ctrl+Shift+Q` or a crash during an exam, your blocked sites stay blocked in every browser, because the emergency exit skips cleanup. Reopen the app (v0.1.11 and later warn you on startup) and use Settings → **RESET HOSTS FILE NOW**, which asks for one Windows admin prompt.

## Install

Download the `.msi` from [Releases](../../releases/latest). Windows will show a SmartScreen warning because the installer isn't code-signed — a certificate costs ~€300/year and this app is free. Click **More info → Run anyway**, and verify the SHA-256 published with each release first if you'd rather not take my word for it.

## Privacy

No account, telemetry, or analytics. Settings and camera frames stay on your machine, and fonts are bundled, so the app never contacts Google. Opening an exam website uses your internet connection; the optional extension talks to the app over localhost. The only elevated action is writing and restoring your hosts file.

## Feedback

This is early software. [Tell me what happened](../../issues/new/choose) — especially if a website or camera did not appear, or the lock held when you wanted out.

## License

Brutal Focus Lock is proprietary software, free for personal use under the license agreement in [LICENSE.md](LICENSE.md), which the installer also shows. It is not open source: please don't redistribute or re-host the installer — link to this page instead. Open-source components it includes are listed in `THIRD_PARTY_NOTICES.md`, installed next to the app.

Not affiliated with Microsoft or with any school, exam body or learning platform. All trademarks belong to their owners.

---

Copyright © 2026 Faraj Valizada. All rights reserved.
