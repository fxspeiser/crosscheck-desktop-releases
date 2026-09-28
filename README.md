# Crosscheck Desktop — installers

This repository holds **release builds only**: signed installers for macOS and
Windows, and the update feed the app checks. There is no source code here.

**Download:** [crosscheckagent.com/desktop](https://www.crosscheckagent.com/desktop)
— or pick a build from [Releases](../../releases).

| Platform | File |
|---|---|
| macOS, Apple silicon (M-series) | `Crosscheck-<version>-arm64.dmg` |
| macOS, Intel | `Crosscheck-<version>-x64.dmg` |
| Windows, x64 | `Crosscheck-Setup-<version>-x64.exe` |
| Windows, ARM | `Crosscheck-Setup-<version>-arm64.exe` |

Not sure which Mac you have? Apple menu → About This Mac. Anything with an
M-series chip is Apple silicon.

## Why a separate repository

The app's source is private, and GitHub does not serve release files from a
private repository to anyone who isn't signed in to it. Publishing installers
here, in public, is what lets the download links and the app's own
auto-updater work for everyone.

## Your keys

Crosscheck runs on your own AI-provider accounts. Your API keys are encrypted
on your machine and sent only to the provider they belong to — never to
Crosscheck. The app can show you every host it has contacted, under
Settings → *What this app has talked to*.

Questions: hello@crosscheckagent.com
