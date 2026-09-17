# netneighborhood

Twinsoft UK / Andy Doran VB6 WNet sample that reproduces a Network Neighborhood browser for Windows 9x and NT/2000. `fnEnum` drives `WNetOpenEnum`/`WNetEnumResource` and fills a ListView so you can drill from network provider through domain, server, share, and directory levels (down only). Working copy retained with third-party notices.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `NetNeighborhood` (`NetNeighborhood.vbp`) | VB6 | WinForms exe | WNet Network Neighborhood ListView browser |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `NetNeighborhood.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `mscomctl.ocx`

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/netneighborhood`.
Company names in project files: Twinsoft UK.
Original author note in `readme.txt`: Andy Doran (andy.doran@dial.pipex.com).
Third-party attribution: Twinsoft UK. See `THIRD_PARTY_NOTICES.md`.

## License

Third-party code remains under its original terms (or none, where none were supplied). See `THIRD_PARTY_NOTICES.md`. Do not treat this tree as VaderConsulting original MIT-licensed work.
