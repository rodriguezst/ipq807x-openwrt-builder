# ipq807x-openwrt-builder
Automated builds of robimarko's IPQ807x OpenWRT repository using GitHub Actions

- robimarko's fork is pulled daily and if last commit is less than a day old a new build is triggered.
- Manual build can also be triggered.
- Build artifacts are stored as releases.
- Build options are embedded in [ipq807x.yaml](/.github/workflows/ipq807x.yaml) file.
