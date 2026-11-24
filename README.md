# Vestnil

**Uninstall with proof.** A free uninstaller for Windows 10 and 11, made in India with love from Odisha.

This repository hosts downloads only. Vestnil's source code is private.

**Website:** https://vestnil.netlify.app

## Download

Please read the [terms](TERMS.txt) first. From 0.4.0 on, every public version stays available here.

| Version | Date | Status | Download | Notes |
|---|---|---|---|---|
| **0.4.0** | 24 November 2026 | Early preview, newest | [VestnilSetup-0.4.0.exe](https://github.com/SMRUTIRANJAN30/vestnil/releases/download/v0.4.0/VestnilSetup-0.4.0.exe) | [What changed](https://github.com/SMRUTIRANJAN30/vestnil/releases/tag/v0.4.0) |

[See all releases](https://github.com/SMRUTIRANJAN30/vestnil/releases). To hear about new ones, choose **Watch > Custom > Releases** at the top of this page.

## What it does

- Lists installed desktop programs, with search, sorting and filters
- Runs a program's own uninstaller and checks that its entry is gone
- Shows leftover folders, shortcuts, registry keys, scheduled tasks and startup entries, with the reason for each
- Finds portable programs and Python scripts that Windows doesn't list
- Finds broken entries whose uninstaller is missing
- Backs up what it removes itself, with Undo in History
- Makes no internet connections of its own. No accounts, ads or tracking

## Known limits

This is an early preview that has been tested on few PCs. The installer isn't digitally signed yet, so Windows may show a SmartScreen warning. Leftover services are shown but can't be removed. Store apps aren't listed. It can't undo what another program's uninstaller does.

## Check your download

Run `Get-FileHash .\VestnilSetup-0.4.0.exe` in PowerShell and compare it with `SHA256.txt` in the release. If it's different, don't run the file. Don't turn off your antivirus to install Vestnil.

## Phone version

An Android app (APK) is planned and coming soon. **No Vestnil APK exists yet.** If another site offers one, please don't install it.

## Report a problem

Your reports help us decide what to fix first. Email us what you did, what you expected and what happened, or use [the form on the website](https://vestnil.netlify.app/#report). Ideas and complaints are welcome too.

## Contact

Smrutiranjan Sahoo, smrutiranjansahoopikun@gmail.com. Please report security problems by email, not in a public issue.

Copyright (c) 2026 Smrutiranjan Sahoo. All rights reserved.
