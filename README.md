# ReportNewAsset-Ps

### STATUS: ALPHA
Working on it, its going to be a quick one, done in half a day.
- fix monitor, broke since refractoring of code.
- break from monitoring loop to return to main menu.

## DESCRIPTION
Soon...

### FEATURES
- **Customizable Cache Locations**: Set custom paths for different Second Life cache data types.
- **Dynamic File Monitoring**: Real-time directory monitoring for new file creations using FileSystemWatcher.
- **Automated File Tracking**: Updates and tracks the latest files in categories like Textures, Objects, Sounds, and Others.
- **Real-time Asset Reporting**: Displays updated information of the latest files, including names and sizes.

### PREVIEW
Main Menu..
```

                       -= Report New Asset =-





                    1. Set Data Cache Location

                    2. Set Sound Cache Location

                    3. Start Monitoring Assets






Select, Menu Options 1-3, Exit Program=X:

```
Monitoring..
```

                      -= Monitoring Assets =-

 Cache/Sound Dir:
R:\FireStorm\Data - 4,412.31 MB
R:\FireStorm\Sound - 36.62 MB

 Textures:
c13826bf-9ca4-6f18-f24f-c3161d92ba70.texture - 7.41 KB

 Objects:
objects_851_896.slc - 3,567.13 KB

 Sounds:
add38606-02d9-16db-c867-dff11df8aa72.dsf - 430.71 KB

 Other:
sl_cache_4e1511a9-36fb-495c-29dd-9b28bf6be69c_0.asset - 441.19 KB

 Refresh In 15 Seconds...

```

## USAGE
Soon...

### NOTATION
- After going to a few locations my 4GB ramdisk was used up even with the textures limited to 512px, then when I logged out by default SL deletes sound files, and then SL will end up not caching sound files because other data will use the cache to the limit, you will know this has happened because, as is shown in "ReportNewAsset", the space used by the, data and sound, cache will be relevantly, the maximum size you set the cache to and 0 MB, thus, under such circumstances, the user must re-download the sounds every time regardless of having a "reasonable" cache size, no, instead you must check the setting in SL to not delete the sound files upon exit.  

## DISCLAIMER
This software is subject to the terms in License.Txt, covering usage, distribution, and modifications. For full details on your rights and obligations, refer to License.Txt.
