<p align="center">
  <img src="https://i.imgur.com/YoZBnPt.jpg" />
</p>

# PixelPlusUI [![Download PixelPlusUI Builds](https://img.shields.io/sourceforge/dt/pixelplusui-project.svg)](https://sourceforge.net/projects/pixelplusui-project/files/eleven/)
### - Your Requirements Our Goals

PixelPlusUI is an another aftermarket aosp ROM Minimal UI & close to Stock Android ROM. What differentiates us from the rest, you ask? LET'S FIND OUT. Our main aim is to give user a better experience without compromising quality of Android experience so that no one struggles in any kind of difficulties while using their device. It brings a better UI/UX to Android with a seamless experience coupled with customisations and user security. Inshort its perfectly balaced between Great Performance, Security, Stability, Minimal UI & Awesome features including pixel goodies. Join us now and start enjoying the beauty of stock Android. Build and enjoy PixelPlusUI on your respective devices!

To get started, you'll need to get
familiar with [Repo](https://source.android.com/source/using-repo.html) and [Version Control with Git](https://source.android.com/source/version-control.html).

## Create a directory for the source files

* You can name this directory however you want, just remember to replace
* WORKSPACE with your directory for the rest of this guide.
* This can be located anywhere (as long as the fs is case-sensitive)

```bash
mkdir WORKSPACE
cd WORKSPACE
```

### Install Repo in the created directory

>> [Hint: This might take a long time]

```bash
repo init -u https://github.com/PixelPlusUI-SnowCone/manifest -b snowcone-12.1
```

>> [Hint: Want to save some space ? Then use this]

```bash
repo init --depth=1 -u https://github.com/PixelPlusUI-SnowCone/manifest -b snowcone-12.1
```

### Download the source
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash
# Set up environment
. build/envsetup.sh
# Choose a target
lunch aosp_$device-userdebug
# Build the code
mka bacon -jX
```

![Credit](https://i.imgur.com/Jm0O4d1.jpg "Credit")

 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**ProtonAOSP**](https://github.com/ProtonAOSP)
 * [**AOSiP**](https://github.com/AOSiP)
 * [**Dirty Unicorns**](https://github.com/DirtyUnicorns)
 * [**xDroid**](https://github.com/xdroidsp)

![Support and Donation](https://i.imgur.com/vfXdZIO.png "Support and Donation")

### Adding Support
 - For adding your device to the list of OFFICIALLY supported devices, you need to contact us on Telegram profiles below with device name and device, vendor, kernel trees.
* [**Saurav**](https://t.me/ugly_kid_af) 

### Follow  us for more
 * [**Telegram Group**](https://t.me/ppuichat)
 * [**Telegram Channel**](https://t.me/ppuich)
 * [**Screenshots**](https://t.me/ppui_ss)
 * [**Telegram Announcements**](https://t.me/ppuinews)

 * [**Website**](https://ppui.site/home)
 * [**Twitter**](https://twitter.com/pixelplusui)

### DONATION LINKS ------------------

If you have liked our work and want to support us please consider donating for servers

```bash
PAYTM UPI ID : dwarmachine24@paytm
GPAY UPI ID: dwarmachine24@oksbi
PAYPAL: https://www.paypal.me/uglykid24
```

# Happy Building :)
