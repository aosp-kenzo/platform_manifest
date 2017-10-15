# Debugging #


### Preparing to Build ###

```bash

# Set up environment
$ source build/envsetup.sh

# Choose a target
$ lunch aosp_kenzo-userdebug

# Build with Gapps and Pixel(Optional)
$ WITH_GAPPS=true
$ WITH_PIXEL=true

# Build the code
$ make -jX otapackage
```
