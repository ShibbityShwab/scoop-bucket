# scoop-bucket

Scoop bucket for **LightSpeed**, the zero-cost global network optimizer for
multiplayer games: <https://github.com/ShibbityShwab/lightspeed>.

## Install

```powershell
scoop bucket add lightspeed https://github.com/ShibbityShwab/scoop-bucket
scoop install lightspeed
```

That installs the `lightspeed` CLI client (`lightspeed.exe`) plus its bundled
WinDivert driver files.

## Update

```powershell
scoop update lightspeed
```

The manifest carries a `checkver`/`autoupdate` block, so Scoop picks up new
GitHub releases automatically; the bucket does not need a commit per release.

## What ships

| Command                | Source asset                                  |
|------------------------|-----------------------------------------------|
| `lightspeed` (CLI)     | `lightspeed-client-x86_64-pc-windows-msvc.zip` |

The tray GUI is distributed as an MSI installer on the
[releases page](https://github.com/ShibbityShwab/lightspeed/releases), not
through Scoop.

## License

LightSpeed is licensed under the custom noncommercial **LightSpeed-NC-1.0**.
