# OrangeFox device tree for taro devices (Poco F5 Pro)
This tree is for building OrangeFox Recovery for the _taro_ platform: Poco F5 Pro

The POCO F5 Pro (codenamed _"mondrian"_) are medium-high range smartphone from Xiaomi.

## Other mikona devices
Other _taro_ devices include Poco F5 (_marble_) and Xiaomi 12T Pro (_diting_). This tree cannot be used to build for these devices due to missing change of partition size values and use of correct device files.

# Device specifications

| Device       | Poco F5 Pro                                                |
| -----------: | :----------------------------------------------------------|
| SoC          | Qualcomm SM8475 Snapdragon 8+ Gen 1 5G                     |
| CPU          | 8x Qualcomm® Kryo™ up to 3.2GHz                            |
| GPU          | Adreno 730                                                 |
| Memory       | 8GB / 12GB  (LPDDR 5)                                      |
| Shipped Android version | 13 (_mondrian_)                                 |
| Storage      | 256GB/512GB  (UFS 3.1)                                     |
| Battery      | Li-Ion 5160 mAh, non-removable                             |
| Dimensions   | 162.8 x 75.4 x 8.6 mm                                      |
| Display      | 1440 x 3200px (20:9), 6.67 inches                          |

## Features

**Works**

- Booting.
- **Decryption** (Android 12+)
- ADB
- MTP
- OTG (Testing)
- vA/B partition functions
- Vibration

POCO F5 Pro use a Virtual A/B Partition Scheme!

## Building

You can find a full compile guide for OrangeFox [Here](https://wiki.orangefox.tech/en/dev/building)

_Lunch_ command :

**mondrina** :
```
lunch twrp_mondrian-eng && mka adbd recoveryimage
```

## Credits
- [Nebrassy](https://github.com/nebrassy)
- [DarthJabba](https://github.com/DarthJabba9)
- between more people, *Credits to their respective creators*.
