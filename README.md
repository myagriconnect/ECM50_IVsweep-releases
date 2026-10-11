# ECM50_IVsweep — Firmware Releases

Built firmware binaries for the [ECM50_IVsweep](https://github.com/myagriconnect/ECM50_IVsweep)
solar-panel IV-curve tester firmware (ESP32-S3).

**No source code here** — this repo exists only so ECM50 can pull OTA
updates over HTTPS without authentication. It's populated automatically
by that repo's `release.yml` GitHub Action whenever a `vX.Y.Z` tag is pushed.

ECM50's OTA always pulls the latest build from a fixed URL:
```
https://github.com/myagriconnect/ECM50_IVsweep-releases/releases/latest/download/firmware.bin
```
