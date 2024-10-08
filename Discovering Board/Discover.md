# Discovering the device

## Hardware
![PCB Picture](img/X96Q_PCB.png?raw=true "PCB")

### Board name
    BA301_627_ V1.3 20393

### Factory Label
    BA301 V1.3 -XR819
    HX-JA ZF202402

Seem to indicate a Board in Rev 1.3 created in Q1 2024 with a XR819 Wlan Chip.

### SOC
The SOC on the Picture above seem to be the AllWinner H313.

### ROM
The ROM is seem to be a JWA60 by Micron Technology Inc.

## Software

### Check compilation instructions set
> eros-p1:/ $ uname -m  
> armv8l

###  Architecture curent type
> eros-p1:/ $ getconf -a | grep LONG_BIT  
> LONG_BIT 32

### Check RAM
                    total        used        free      shared     buffers
    Mem:             1.9G        907M        1.0G        6.4M        524K
    -/+ buffers/cache:           906M        1.0G
    Swap:            1.4G        138M        1.3G
