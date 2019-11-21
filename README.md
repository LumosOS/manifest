# LumosOS #

# Create the Directories #
You will need to set up some directories in your build environment.

To create them run:

   $ mkdir -p ~/bin
   $ mkdir -p ~/Lumos
   
### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/LumosOS/manifest -b pie

# Sync
repo sync -c -jx --force-sync --no-clone-bundle --no-tags
```

-j8 -Set jobs by just replacing # with what you wish

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch lumos_$device-userdebug

# Build the code
$ mka bacon -j8
```
# WARNING: #
# To compile AOSP use pie branch #

# Applying for Maintainership #
If you have successfully built for your device and want to apply for maintainership then drop in a message to Basiczero on Telegram or XDA.

Credits
-------
* [**Pixel Experiance**](https://github.com/PixelExperience)
* [**COSP**](https://github.com/cosp-project)
* [**LineageOS**](https://github.com/LineageOS)
* [**AOSP EXTENDED**](https://github.com/AospExtended)
* [**Cosmic OS**](https://github.com/Cosmic-OS)
* [**LiquidRemix**](https://github.com/LiquidRemix)
