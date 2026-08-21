# Brutal Focus Lock

**Every other focus app asks. This one enforces.**

A Windows focus and exam-lockdown tool that holds your session at the operating-system level — keyboard hook, hosts-file blocking, always-on-top HUD — with a typed confession as the only early exit.

**[⬇ Download the latest release](../../releases/latest)** · Windows 10/11 · Free · Runs 100% offline

---

## Why this exists

Forest can be closed. Freedom can be uninstalled. Cold Turkey stops at the browser. All of them assume you'll cooperate with yourself. This one is built for the twenty minutes where you won't.

| | Can you close it mid-session? | Where it stops |
|---|---|---|
| Forest | Yes — the tree dies, nothing else happens | Your conscience |
| Freedom | Yes — quit or uninstall | App + site blocking |
| Cold Turkey | Hard, on the paid tier | The browser |
| **Brutal Focus** | **No — the hook is live, and the exit costs a typed confession** | **Keyboard, network, every browser at once** |

## Three layers of enforcement

- **OS · Keyboard** — Win32 low-level hook kills Alt+Tab, Win, Win+D, Win+Tab, Alt+F4, Ctrl+Esc.
- **OS · Network** — your blocklist goes into the Windows hosts file. Blocked everywhere, not just one browser. Backed up and restored on session end, even after a crash.
- **Browser** — optional companion extension blocks redirect-sneaking inside Chrome, Edge and Brave.

## The contract

1. The timer is the only clean exit.
2. Quitting early costs a 25–60 character panic phrase built from your own stated goals.
3. The anti-streak never forgets. Only a completed session resets it.
4. Contradictory settings resolve toward the stricter option.
5. Killing your browser mid-exam starts a 30-second countdown.
6. **`Ctrl+Shift+Q` always works.** Safety is never gated.

## Emergency exit

Press **`Ctrl+Shift+Q`**. It force-quits everything instantly — no admin prompt, no phrase, and the keyboard hook never intercepts it.

Sites still blocked afterwards? Open Settings → **RESET HOSTS NOW**.

## Install

Download the `.msi` from [Releases](../../releases/latest). Windows will show a SmartScreen warning because the installer isn't code-signed — a certificate costs ~€300/year and this app is free. Click **More info → Run anyway**, and verify the SHA-256 published with each release first if you'd rather not take my word for it.

## Privacy

No account. No telemetry. No analytics. No network requests. The camera feed stays in the renderer and never touches a network. The only elevated action is writing and restoring your hosts file.

## Feedback

v0.1.0 is the first public release and there is no telemetry, so I know nothing about how anyone uses this. [Tell me what happened](../../issues/new/choose) — especially if the lock held when you wanted out, or if you found a way around it.

---

© 2026 Faraj Valizada
