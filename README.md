# Diamond

VB6 MDI warranty desk app ("Warranty") for a retail/stock Access database. Opens Stock, Warranty, and Suppliers tables via DAO 3.5, drives a stepped repair flow UI, barcode scan support, and sales forms. Company: Chips, Bits and Bytes. Output: `Diamond.exe`.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`Diamond.vbp`) | VB6 | WinForms exe | Warranty/stock MDI with barcode flow |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Diamond.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Microsoft DAO 3.5 Object Library
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `BarPic.ocx`
  - `Barcode.ocx`
  - `comctl32.ocx`
  - Windows Scripting Host Object Model

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/Diamond`.
Company names in project files: Chips, Bits and Bytes.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
