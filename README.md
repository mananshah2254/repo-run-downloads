# Repo Run downloads

Repo Run checks what a public GitHub or GitLab project needs, compares those requirements with your computer, and helps you prepare and run supported projects after you review the commands.

## Download v0.1.1 preview

| Computer | Installer |
| --- | --- |
| Mac with Apple silicon (M1 or newer, ARM64) | [Download Mac DMG](https://github.com/mananshah2254/repo-run-downloads/releases/download/v0.1.1/Repo-Run-0.1.1-mac-arm64.dmg) |
| Windows on Intel/AMD x64 | [Download Windows installer](https://github.com/mananshah2254/repo-run-downloads/releases/download/v0.1.1/Repo-Run-0.1.1-win-x64.exe) |

[Release notes and checksums](https://github.com/mananshah2254/repo-run-downloads/releases/tag/v0.1.1) · [All releases](https://github.com/mananshah2254/repo-run-downloads/releases)

## Preview limitations

- **Google sign-in is open to Google users.** Repository checks require sign-in; people can explore the sample and computer inventory first. This is still a development preview rather than a stable release.
- Both installers are **unsigned**, and the Mac app is **not notarized**. Your operating system may warn or block installation. A signed release is still pending; do not disable system security protections.
- Mac launch, Google sign-in, account history synchronization, and persistence after restart have been verified. The Windows installer was built but has not yet been tested on a Windows computer.
- This release has no Intel Mac or Windows ARM64 installer. Those targets are supported by the build configuration but are not included here.
- Only public repositories on github.com and gitlab.com are supported. Private repositories cannot be inspected. Some tool versions and project setup steps require manual work.

## Install

**Mac:** download the DMG, open it, and drag Repo Run into Applications. If macOS blocks this unsigned preview, wait for the signed release or build the source in a development environment.

**Windows:** download the EXE and run the installer to choose an installation folder. Review any publisher warning; wait for the signed release if your system blocks the preview.

The app includes its desktop runtime. You do not need Node.js just to open Repo Run. Individual repositories can require additional tools; the app displays those requirements before any installation.

## Source, issues and license

All application source, database migrations, tests and build workflows are in [mananshah2254/repo-run](https://github.com/mananshah2254/repo-run). Report app issues [there](https://github.com/mananshah2254/repo-run/issues).

Repo Run is free and MIT licensed. Bundled components retain their respective licenses. Installers are stored as release assets, not committed to Git history. This preview has no automatic updater; download future versions from this repository's releases.
