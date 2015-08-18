
AOSP manifest for Optimus G
===========

To initialize your local repository using the AOSP trees, use a command like this:
````bash
repo init -u git://github.com/ProjectG/manifest.git -b master
```
Then to sync up:
````bash
repo sync
```
Finally to build:
````bash
. build/envsetup.sh
lunch aosp_geehrc-userdebug
make -j8 otapackage
```
