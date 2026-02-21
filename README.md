# yz4u-tweaks

Sileo/APT repository staging for the Yz4u JB Comfort Project.

## Tweak Description (EN / JA)
`LockAlive` is a rootless ElleKit tweak that helps keep SSH/Wi-Fi reachable while the device is locked.

`LockAlive` は、画面ロック中でも SSH/Wi-Fi の到達性を保ちやすくする rootless ElleKit 向け tweak です。

## Current Package
- `debs/com.yz4u.lockalive_1.0.0_iphoneos-arm64.deb`

## Regenerate Repo Indexes
Run after adding/updating `.deb` files:

```bash
cd yz4u-tweaks
./scripts/generate_repo_indexes.sh
```

This regenerates:
- `Packages`
- `Packages.gz`
- `Release`

## Expected GitHub Pages URL
- `https://yz4u.github.io/yz4u-tweaks/`

## Sileo Source URL
- `https://yz4u.github.io/yz4u-tweaks/`
