# Project Change & Update Log

**Timestamp:** `2026-07-23T19:55:31+07:00`

---

## Overview
Log of developer keyboard shortcut (`Shift + S`) addition for local testing/preview PIN bypass, user interaction gesture registration (`markUserInteraction()`), and project file modifications ([script.js](file:///C:/Users/Dika%20Rahmat%20Fadillah/Downloads/HAppyBirthdayAdelya/script.js)).

---

## Summary of Developer Shortcut Addition

| Feature | File(s) | Details |
| --- | --- | --- |
| **`Shift + S` PIN Bypass Shortcut** | `script.js` | Added global `keydown` listener that checks if `#pin-screen` is active when `Shift + S` is pressed, triggering `e.preventDefault()`, `markUserInteraction()`, and `pinSuccess()` to skip straight to the gift box screen. |
| **Explicit Developer Comment Block** | `script.js` | Marked clearly with `/* ─── DEV SHORTCUT — REMOVE BEFORE SENDING FINAL LINK ───────── */` for trivial removal prior to deployment. |
| **Purely Additive & Non-Breaking** | `script.js` | Preserved all existing PIN passcode logic (`'240805'`), keypad UI events, and error state reset loops untouched. |
| **Active Project Settings** | All | Preserved recipient name as **"Adelya"**, sender signature as **"dk"**, PIN as `"240805"`, 3x4 dial pad with transparent glassmorphism, dark glassmorphic card themes, and original Digital Bouquet stem structure. |

---

## Detailed File Modifications

### 1. [`script.js`](file:///C:/Users/Dika%20Rahmat%20Fadillah/Downloads/HAppyBirthdayAdelya/script.js)
- **Dev Shortcut Listener (Lines 341–352):**
  - Implemented `Shift + S` keydown handler invoking `markUserInteraction()` and `pinSuccess()`.

---

## Audio File Configuration Status

- **Playlist Tracks:** 3 external audio streams configured in `CONFIG.PLAYLIST`:
  1. *Shape Of My Heart* – Backstreet Boys (`https://smail.my.id/cloud/tvBJ12wx1`)
  2. *Angel Baby* – Troye Sivan (`https://smail.my.id/cloud/kf52BoRo1`)
  3. *My Love* – Westlife (`https://smail.my.id/cloud/E6qLnqZi1`)
- **Interactive Features:** Audio pre-warming on user gestures (`markUserInteraction()`), progress bar seeking, vinyl record rotation animations, floating button smooth navigation, and mobile autoplay fallback nudges are fully active.
