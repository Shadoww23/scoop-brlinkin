# Brlinkin Scoop bucket

Scoop manifests for [Brlinkin](https://shadoww23.github.io/flow/) tools. Each
manifest downloads the official release archive; the applications themselves
are not hosted here.

## Install ReleaseGuard

```powershell
scoop bucket add brlinkin https://github.com/Shadoww23/scoop-brlinkin
scoop install brlinkin/releaseguard
```

The portable Windows app is unsigned. Verify the release checksum before
choosing **More info** then **Run anyway** in SmartScreen.

ReleaseGuard is proprietary freeware. See its
[license](https://github.com/Shadoww23/releaseguard/blob/main/LICENSE).
