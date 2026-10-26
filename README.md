# Interview Helper for Windows

Official customer downloads for **Interview Helper by Watto**. The app's source code and owner licensing tools are maintained in separate private repositories.

## Download

**[Browse Windows releases](https://github.com/crazycrafters/interview-helper-download/releases)**

Download the tested Windows installer from the latest published release:

**[Download the latest Windows installer](https://github.com/crazycrafters/interview-helper-download/releases/latest/download/InterviewHelper-Setup.exe)**

Choose **InterviewHelper-Setup.exe** under a release's **Assets**, rather than the source-code archive. Windows 10/11 x64; no Python installation needed. Windows Live Captions requires Windows 11; local speech models may require separate downloads. Recording requires FFmpeg.

## Install and try

1. Download the setup EXE; extract it first if you downloaded an archive.
2. Follow the setup wizard and choose whether to create a desktop shortcut.
3. Configure captions and your AI connection in Settings.
4. Try meetings up to three minutes without a license. Activate a PC-bound license for longer meetings.

Current builds are unsigned and Windows may display **Unknown Publisher**. AI-provider account/subscription or API usage is separate from the app license.

## Integrity

Each release includes **SHA256SUMS.txt**. In PowerShell, run:

```powershell
Get-FileHash .\InterviewHelper-Setup.exe -Algorithm SHA256
```

Compare the result with the published checksum.

## Website and community

- [Official website](https://interview-helper-site.vercel.app/)
- [Join the Discord community](https://discord.gg/d7qmC5h9NA)

Use assistance and recording only where permitted and obtain any required participant consent.
