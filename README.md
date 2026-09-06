# Corner IQ — downloads

Public download host for [Corner IQ](https://corneriq.kindofabigdill.com), a
digital track engineer and telemetry companion for riders and drivers.

**This repository holds no source code.** It exists because installers are
larger than GitHub allows inside a repository, and release assets on a private
repository cannot be downloaded without signing in. The app itself is developed
privately; only the built downloads live here.

## Downloads

Get them from the [Releases](../../releases) page, or from the
[website](https://corneriq.kindofabigdill.com), which links to the same files.

| Platform | File |
|---|---|
| Windows 10/11 (64-bit) | `Corner IQ Setup <version>.exe` |
| Android | published on the [website](https://corneriq.kindofabigdill.com) |

## A note on the Windows warning

The Windows installer is not yet code-signed, so on first run SmartScreen shows
**"Windows protected your PC"**. Click **More info → Run anyway**.

This is expected and it is not a judgement about the file — it is what Windows
shows for any installer from a publisher it has not seen enough of yet. Signing
it requires a commercial code-signing certificate, which is on the roadmap.

## What the desktop app adds

Two things a browser tab cannot do:

- **Live iRacing telemetry.** iRacing publishes into Windows shared memory,
  which no browser can read. The desktop app reads it directly — nothing to
  install, no console window to leave open.
- **Direct folder access** for watching a logger's data folder without
  re-granting permission every session.

Everything else matches the web app at
[trackengineer.kindofabigdill.com](https://trackengineer.kindofabigdill.com).

---

Kind of a Big Dill — Racing & Engineering
