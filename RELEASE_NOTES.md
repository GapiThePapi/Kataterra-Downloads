# Kataterra 3.0.0-simple.22

Development release for Windows 10/11 x64.

- Adds **Check for updates** to the About window with installed/available versions, release notes and an explicit ZIP download action.
- Adds an optional once-daily update check in Settings. Network failures never block application startup and no update is installed automatically.
- Uses the public `Kataterra-Downloads` release feed and accepts only trusted GitHub HTTPS URLs.
- Retains the map, municipality, DOF, LiDAR, landscape, measurement, profile and CAD/GIS export improvements from `3.0.0-simple.21`.

## Verification

- 265 offline tests passed; 7 explicitly live-source tests skipped.
- 163 native WPF workflow checks passed.
- The extracted self-contained package starts with only `Kataterra.exe` and no installed .NET runtime.
- ZIP SHA-256: `38A17A42CD74DA48E5EB565A6BFC9A07779880E2C8AF04E91DA5BD3DDBBFA54F`

This development build is not yet Authenticode-signed, so Microsoft Defender SmartScreen may display an unrecognized-app warning.

---

Razvojna izdaja za Windows 10/11 x64.

- Pogled **O programu** vsebuje ukaz **Preveri posodobitve**, ki pokaže različici, opombe in neposreden prenos ZIP-a.
- Nastavitve omogočajo neobvezno dnevno preverjanje. Napaka omrežja ne prekine zagona, posodobitev pa se nikoli ne namesti samodejno.
- Ohranjen je celoten preverjeni uporabniški tok različice `3.0.0-simple.21`.
