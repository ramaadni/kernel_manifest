# Build Kernel
## Sync ###
```bash
    repo init -u https://github.com/ramaadni/kernel_manifest -b wakacaw --depth=1
    repo sync
```
## Build ###
```bash
    LTO=thin BUILD_CONFIG=common/build.config.gki.custom build/build.sh
```
