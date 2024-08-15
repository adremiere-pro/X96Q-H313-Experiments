# Backup
For many reasons and before starting to modify the android version and/or the operating system, I want to start with a backup.

According to my research, the X96Q can be restored via a software called PhoenixCard v3.09 and a backup in IMG format seems to exist on Yandex Storage, at least that's what I can translate from the Russian forum: 4PDA.  

I have downloaded these programs, but having seen several users having encountered errors in their use, I prefer to create a backup from a TWRP image found on XDA.  


## Install TWRP Recovery
    C:\ > fastboot flash recovery TWRP_recovery.img
    Warning: skip copying recovery image avb footer (recovery partition size: 0, recovery image size: 33554432).
    Sending 'recovery' (32768 KB)                      OKAY [  1.289s]
    Writing 'recovery'                                 OKAY [  1.371s]
    Finished. Total time: 2.738s

## Create the backup
![TWRP](img/twrp.png?raw=true "TWRP")