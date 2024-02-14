# NavaDroid

 Getting Started
---------------
To get started with the NavaDroid sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

 To initialize your local repository, use command:

```bash
repo init -u https://github.com/NavaDroid/manifest -b 14 --git-lfs
```

Then sync up:

```bash
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```

Building the System
-------------------
 Initialize the ROM environment with the envsetup.sh script.

```bash
. build/envsetup.sh
```

Lunch your device after cloning all device sources if needed.

```bash
lunch nava_devicecodename-buildtype
```

Start compilation

```bash
mka nava 
```
Thanks section
---------------

Here's my thanks to people who made this possible:

* AOSPA
* ArrowOS
* BananaDroid
* Bianca Project
* DirtyUnicorns
* DerpfestOS
* NitrogenOS
* Nusantara-ROM
* PixelExperience
* PixelOS
* RiceDroid
