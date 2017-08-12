## TWRP device tree for Blu Life One X2
------------

### How to setup build environment and compile TWRP for Blu Life One X2:

------------

Initializing a Build Environment:

    https://source.android.com/source/initializing.html

Initialize repo: 

    repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-7.1
    repo sync

Sync this repo to `/device/blu/blu_life_one_x2/`


------------

How to build:

    make clean && make clobber
    . build/envsetup.sh
    lunch omni_blu_life_one_x2-userdebug
    make -j# recoveryimage
" # Being the number of threads."
