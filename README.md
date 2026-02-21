# yz4u-tweaks

Sileo/APT repository staging for the Yz4u JB Comfort Project.

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
