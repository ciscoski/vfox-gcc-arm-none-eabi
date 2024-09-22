# vfox-gcc-arm-none-eabi

[GNU Arm Embedded Toolchain plugin](https://developer.arm.com/downloads/-/arm-gnu-toolchain-downloads) for [vfox](https://vfox.lhan.me/).

## Install

After installing vfox, install the plugin by running

``` shell
vfox add gcc-arm-none-eabi
```

Install the latest stable version with `latest` tag.

``` shell
vfox install cc-arm-none-eabi@latest
```

## Architecture selection

This plugin exposes allows to select the SDK architecture.
The user can select the atchitecture by adding a "~<arch>" at the end of the version.
`amd64`,`i386` and `arm64` are valid architectures.

By default the plugin will select the best architecture for the host.
