# Manjaro ARM Pinebook Pro
[![iso_build](https://github.com/manjaro-arm/pinebook-pro-images/workflows/image_build/badge.svg)](https://github.com/manjaro-arm/pinebook-pro-images/actions)

## description

Release Branch for Manjaro ARM images for the Pinebook Pro

## where can I download an iso?

Images are build and uploaded in a relatively regular interval to [github releases](https://github.com/manjaro-arm/pinebook-pro-images/releases)

## sources

- [image profile](https://github.com/manjaro-pinephone/arm-profiles)

## building

1. check out the arm-profiles
2. `sudo buildarmimg -d pbpro -e $EDITION`
