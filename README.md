# scoop-crofty

**This bucket is archived. crofty is no longer distributed through Scoop.**
The last version published here is v0.17.2, and it will not be updated.

## Install crofty instead from

- **Click installer:** the `crofty-setup.exe` attached to the
  [latest release](https://github.com/ShiroDoromoto/crofty/releases/latest)
- **Terminal:** `irm https://github.com/ShiroDoromoto/crofty/releases/latest/download/install.ps1 | iex`

See <https://crofty.site> for the full instructions, including what to do when
SmartScreen warns you about an unsigned installer.

## Already installed from this bucket?

```powershell
scoop uninstall crofty
scoop bucket rm crofty
irm https://github.com/ShiroDoromoto/crofty/releases/latest/download/install.ps1 | iex
```

`crofty update` prints the same steps if you get there first.

## Why

The bucket existed to be the terminal user's route onto Windows, and to pull
Hugo in as a dependency. `install.ps1` serves the first purpose, and the click
installer now bundles Hugo, which retires the second. This repository stays up,
and stays archived, so that nobody's `scoop update` fails on a missing bucket.
