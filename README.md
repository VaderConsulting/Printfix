# Printfix

CSC VB6 Printer Fix for Clients (`PrintFix.exe` / `Printfix.vbp`): two-pass logon helper that clears stale `w32x86\2` spool drivers (`con2prt /f`, stop/start Spooler) and forces logoff so printers remount correctly. Open `Printfix.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`Printfix.vbp`) | VB6 | WinForms exe | PrintFix |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Printfix.vbp`

## Requirements

- Visual Basic 6.0 IDE

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Printfix`.
Company names in project files: CSC.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
