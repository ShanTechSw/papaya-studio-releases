# PAPAYA Studio 1.2.0

Everything in this folder belongs to release 1.2.0 and is never changed once
published. The installer for this version is attached to the GitHub release of
the same name, because GitHub does not keep files larger than 100 MB inside a
repository.

| File | What it is |
|---|---|
| `PAPAYA_VL_Firmware_1.0.0.pkg` | The firmware package for the PAPAYA VL board. Install it with the Firmware Updater in PAPAYA Studio; the procedure is in the repository README. |
| `PAPAYA_User_Manual.pdf` | The whole product: every tool, every dialog, the wiring rules, the block reference and the board datasheet. |
| `PAPAYA_Programmer_Manual.pdf` | Driving a board from your own program, and what the host side has to get right. |
| `PAPAYA_C++_and_Python_Reference.pdf` | Every call in the shipped libraries: signatures, parameters, units, order and return values. |
| `PAPAYA_Datasheet.pdf` | The board on its own: ranges, resolutions, limits and connectors. |
| `PapayaLibraries-1.2.0.zip` | The C++ and Python libraries a generated project uses. |
| `PapayaExamples-1.2.0.zip` | The example designs, ready to open and simulate. |
| `SHA256SUMS.txt` | The SHA-256 of every file above. |

To check a download arrived intact, compare it against the line in
`SHA256SUMS.txt`:

```
certutil -hashfile PAPAYA_VL_Firmware_1.0.0.pkg SHA256
```
