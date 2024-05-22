# Build Kernel
## Sync ###
```bash
    repo init -u https://github.com/ramaadni/kernel_manifest -b android12-5.10
    repo sync
```
## Build ###
```bash
    LTO=thin BUILD_CONFIG=common/build.config.gki.custom build/build.sh
```
