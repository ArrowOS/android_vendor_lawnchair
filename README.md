# Lawnchair AOSP based build system

## Disclaimer
- All credits go to the [Lawnchair](https://github.com/LawnchairLauncher) Team.
- Quickstep enablement is done with the help of QuickSwitch Magisk module made by [Skittles9823](https://github.com/skittles9823).

## Getting started
**1. Add this repository to your AOSP build root's `vendor/lawnchair`**

**2. Import vendor/lawnchair/lawnchair.mk**

`$(call inherit-product-if-exists, vendor/lawnchair/lawnchair.mk)`

**3. Remove existing launcher from the build**

This can be done by adding package name of such launcher in overrides for Lawnchair package definition in Android.bp

**4. Build Android**
