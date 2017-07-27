# **LineageOS**
###### Initializing
*1.* copy project.xml into .repo/local_manifests (if the folder does not exist - create it)
```
either use STRG/CTRL + H to make hidden folders visible, or cp it via terminal
```
*2.* sync your setup again
```
repo sync
```

###### Building
```
. build/envsetup.sh
lunch lineage_<device>-userdebug
make -j<thread count> bacon
```

device support: vns (Huawei P9 Lite)
