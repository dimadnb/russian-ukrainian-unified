# Russian - Ukrainian Unified

A Windows system keyboard layout based on Russian ЙЦУКЕН with the US symbol row on Shift. The English US layout remains separate and unchanged. It uses MSKLC 1.4 and does not require AutoHotkey or a background process.

`Right Alt` is `AltGr`.

## Ukrainian letters

| Shortcut                                | Output    |
| --------------------------------------- | --------- |
| `AltGr+Е` / `Shift+AltGr+Е`             | `є` / `Є` |
| `AltGr+Г` / `Shift+AltGr+Г`             | `ґ` / `Ґ` |
| `AltGr+Ы` / `Shift+AltGr+Ы`             | `і` / `І` |
| `AltGr+OEM_102` / `Shift+AltGr+OEM_102` | `ї` / `Ї` |

`OEM_102` is the extra key near the left Shift key. The main backslash key keeps `\\` and `|` on `AltGr` and `Shift+AltGr`.

## US symbols on physical keys

| Shortcut                                              | Output                |
| ----------------------------------------------------- | --------------------- |
| `Shift+1 2 3 4 5 6 7 8 9 0`                           | `! @ # $ % ^ & * ( )` |
| `Shift+- =`                                            | `_ +`                 |
| `AltGr+Х Ъ` / `Shift+AltGr+Х Ъ`                       | `[ ]` / `{ }`         |
| `AltGr+Ж Э` / `Shift+AltGr+Ж Э`                       | `; '` / `: "`         |
| `AltGr+Ё` / `Shift+AltGr+Ё`                           | `` ` `` / `~`         |
| `AltGr+Б Ю` / `Shift+AltGr+Б Ю`                       | `, .` / `< >`         |
| `AltGr+key right of Ю` / `Shift+AltGr+key right of Ю` | `/` / `?`             |

## Build and install

1. Install [Microsoft Keyboard Layout Creator 1.4](https://www.microsoft.com/en-us/download/details.aspx?id=102134).
2. Open `RUUA.klc` with `File` -> `Load Source File...`.
3. Run `Project` -> `Validate Layout`, then `Test Keyboard Layout...`.
4. Run `Project` -> `Build DLL and Setup Package`.
5. Run the generated `setup.exe` as administrator.
6. Sign out or restart Windows, then add `Russian - Ukrainian Unified` in the Russian language keyboard settings.

Keep the generated package folder if you need to install the layout on another computer.

## Remove

Switch to another layout, remove this keyboard from the Russian language settings, then uninstall `Russian - Ukrainian Unified` from `Settings` -> `Apps` -> `Installed apps`. Sign out or restart Windows if the old entry remains.

## Source details

- Source: `RUUA.klc`
- Internal name: `RUUA`
- Locale: `ru-RU` (`00000419`)
- Version: `1.0`
