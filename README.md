# Brutal Focus Lock

**Most focus apps ask. This one is stricter.**

A Windows focus and exam-lockdown tool with a floating timer, optional browser blocking, and stricter exam sessions. You can always use `Ctrl+Shift+Q` as an emergency exit.

**[⬇ Download the latest release](../../releases/latest)** · Windows 10/11 · Free · No account or telemetry

---

## Why this exists

Most focus tools assume you'll cooperate with yourself. This one is built for the twenty minutes where you won't: in Exam mode it blocks task-switching keys and the sites on your blocklist, and ending a session early takes a typed phrase.

Focus sessions can be stopped from the timer. Exam sessions add a keyboard hook and a panic phrase for ordinary early exit. The emergency shortcut remains available in either mode.

## What each mode enforces

- **Focus session** — floating timer; your blocklist is enforced in supported browsers only when the optional companion extension shows **PAIRED**. Without it, the list is a visible reminder, not an active block.
- **Exam session** — keyboard hook limits task switching. With a nonempty blocklist and your approval of the Windows prompt, the app adds hosts-file entries and removes them when the session ends.
- **Exam browser choice** — use your normal browser for the best sign-in compatibility, or opt into the locked app window. The optional extension can add browser-side blocking in your normal browser.

## The contract

1. The timer is the only clean exit.
2. Quitting an exam early means typing the phrase shown (capitals and extra spaces don't matter). By default it's picked at random from your own phrases and goals, or from built-in phrases if you haven't set any.
3. The anti-streak never forgets. Only a completed session resets it.
4. The exam setup shows which browser will open and what blocking is available before you start.
5. Closing your normal browser mid-exam starts a 30-second countdown.
6. **`Ctrl+Shift+Q` always works.** Safety is never gated.

## Emergency exit

Press **`Ctrl+Shift+Q`**. It force-quits everything instantly — no admin prompt, no phrase, and the keyboard hook never intercepts it.

The emergency exit itself skips cleanup, but during an exam with a blocklist the blocking helper notices that the app has closed and removes the blocks from your hosts file on its own. If that fails, your blocked sites can stay blocked in browsers that use Windows' own DNS: reopen the app (it warns you on startup) and use Settings → **RESET HOSTS FILE NOW**, which asks for one Windows admin prompt.

## Install

Download the `.msi` from [Releases](../../releases/latest). Windows will show a SmartScreen warning because the installer isn't code-signed yet. Click **More info → Run anyway**, and verify the SHA-256 published with each release first if you'd rather not take my word for it.

**Current release: [v0.3.3](../../releases/tag/v0.3.3)** · Windows 10/11, 64-bit. A session now has four named steps: PLAN, PREPARE, FOCUS, REVIEW. Under the goal you can list up to 5 outputs; at check-out you tick them and the app suggests HIT, PARTLY or MISSED, then suggests the next session with one button to plan it. "Keep open this session" leaves up to 5 blocked sites out of one session. Study files with a bracket or " - " in the name are now recognised, and a file whose window was never found is reopened only when you press OPEN AGAIN. The exit phrases fit any student and can name the blocked site you tried most (needs the companion extension). A goal with unfilled blanks no longer starts a session. Everything stays on your PC.

**Known limitations in v0.3.3:** with 3 or more study files open they alternate left and right, so the third covers the first (use the file switcher on the timer); a viewer that shows no file name in its window title is not recognised; while an app running as administrator (such as Task Manager) is the active window beside an exam, Windows-key shortcuts work in it; and Win+L still locks the PC.

## Privacy

No account, telemetry, or analytics. The app is designed to send nothing to us: settings and camera frames stay on your machine, and fonts are bundled (an automated test checks that the app and site contain no Google Fonts links). Opening an exam website uses your internet connection; the optional extension talks to the app over localhost. The only elevated action is writing and restoring your hosts file.

The optional camera self-view is off by default. It shows video only, with no audio, in the session timer window. No code path records, saves or sends camera frames. Every way a session ends turns the camera off: the timer running out, stopping a focus session, the exit phrase, and the countdown after you close your browser mid-exam.

## Feedback

This is early software. [Tell me what happened](../../issues/new/choose) — especially if a website or camera did not appear, or the lock held when you wanted out.

## License

Brutal Focus Lock is proprietary software, free for personal use under the license agreement in [LICENSE.md](LICENSE.md), which the installer also shows. It is not open source: please don't redistribute or re-host the installer — link to this page instead. Open-source components it includes are listed in `THIRD_PARTY_NOTICES.md`, installed next to the app.

Not affiliated with Microsoft or with any school, exam body or learning platform. All trademarks belong to their owners.

---

Copyright © 2026 the Brutal Focus project. All rights reserved.
