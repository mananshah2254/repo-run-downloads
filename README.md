# Repo Run downloads

Repo Run checks what a public GitHub or GitLab project needs, compares those requirements with your computer, and helps you prepare and run supported projects after you review the commands.

## Download preview installers

| Computer | Installer |
| --- | --- |
| Mac with Apple silicon (M1 or newer, ARM64) | [Download Mac DMG](https://github.com/mananshah2254/repo-run-downloads/releases/download/v0.1.1-macos/Repo-Run-0.1.1-mac-arm64.dmg) |
| Intel Mac (x64) | [Download Intel Mac DMG](https://github.com/mananshah2254/repo-run-downloads/releases/download/v0.1.1-macos/Repo-Run-0.1.1-mac-x64.dmg) |
| Windows on Intel/AMD x64 | [Download Windows v0.1.2 installer with corrected desktop icon](https://github.com/mananshah2254/repo-run-downloads/releases/download/v0.1.2-windows/Repo-Run-0.1.2-win-x64.exe) |

[Mac release notes and checksums](https://github.com/mananshah2254/repo-run-downloads/releases/tag/v0.1.1-macos) · [Windows release notes and checksums](https://github.com/mananshah2254/repo-run-downloads/releases/tag/v0.1.2-windows) · [All releases](https://github.com/mananshah2254/repo-run-downloads/releases)

## Preview limitations

- **Google sign-in is open to Google users.** Repository checks require sign-in; people can explore the sample and computer inventory first. This is still a development preview rather than a stable release.
- The current Mac installers are **Developer ID signed and notarized by Apple**, with stapled tickets and verified Gatekeeper acceptance. macOS may still show its normal first-open confirmation for downloaded apps. The Windows installer remains **unsigned**.
- Mac launch, Google sign-in, account history synchronization, and persistence after restart have been verified. A Windows user reported that the earlier installer installed and ran successfully; the icon-corrected v0.1.2 installer still needs a Windows installation check.
- Apple silicon and Intel Mac installers are available. Intel launch on real Intel hardware remains untested. Windows ARM64 is not included.
- Only public repositories on github.com and gitlab.com are supported. Private repositories cannot be inspected. Some tool versions and project setup steps require manual work.

## Install

**Mac:** download the DMG, open it, and drag Repo Run into Applications. The current Mac downloads are signed and notarized. If you downloaded an older unsigned preview, download the current installer again.

**Windows:** download the EXE and run the installer to choose an installation folder. Review any publisher warning; wait for the signed release if your system blocks the preview.

The app includes its desktop runtime. You do not need Node.js just to open Repo Run. Individual repositories can require additional tools; the app displays those requirements before any installation.

## Source, issues and license

All application source, database migrations, tests and build workflows are in [mananshah2254/repo-run](https://github.com/mananshah2254/repo-run). Report app issues [there](https://github.com/mananshah2254/repo-run/issues).

Repo Run is free and MIT licensed. Bundled components retain their respective licenses. Installers are stored as release assets, not committed to Git history. This preview has no automatic updater; download future versions from this repository's releases.
