# meta-orange
This is experimental repo. Do not use it

# How to build for orange
```sh
git clone --recurse-submodules https://github.com/buldo/meta-orange.git
cd meta-orange
source poky/oe-init-build-env ./meta-orange

# Build demo image
bitbake openhd-ground-image

# Create image file
wic create sunxi-sdcard-image -e openhd-ground-image
```

