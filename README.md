## Automated Recovery compilation

Orange fox build, TWRP and PBRP SHRP

## Parameter Description (ORANGE FOX)

| Name                 | Description                                       | Example                                                      |
| -------------------- | ------------------------------------------------- | ------------------------------------------------------------ |
| `Deploy Type (BETA/UNOFFICIAL/OFFICIAL)`    |Deploy Type                                      |UNOFFICIAL 
| `MANIFEST_URL`       | Source address                                    | https://gitlab.com/OrangeFox/sync.git |
| `MANIFEST_BRANCH`    | Source branch                                     | 12.1                                                    |
| `DEVICE_TREE_URL`    | Device address                                    | https://github.com/OrangeFoxRecovery/android_device_asus_I003D         |
| `DEVICE_TREE_BRANCH` | Device branch                                     | android-12.1                                                 |
| `DEVICE_PATH`        | Device location                                   | device/asus/I003D                                            |
| `DEVICE_NAME`        | Model name                                        | I003D                                                        |
| `MAKEFILE_NAME`      | Makefile name                                     | twrp_I003D                                                   |
| `BUILD_TARGET`       | Build Target Partition (boot/recovery/vendorboot) | recovery                                                     |

-----


## Parameter Description (TWRP)

| Name                 | Description                                       | Example                                                      |
| -------------------- | ------------------------------------------------- | ------------------------------------------------------------ |
| `Deploy Type (BETA/UNOFFICIAL/OFFICIAL)`    |Deploy Type                                      |UNOFFICIAL 
| `MANIFEST_URL`       | Source address                                    | https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp.git |
| `MANIFEST_BRANCH`    | Source branch                                     | twrp-12.1                                                    |
| `DEVICE_TREE_URL`    | Device address                                    | https://github.com/TeamWin/android_device_asus_I003D         |
| `DEVICE_TREE_BRANCH` | Device branch                                     | twrp-12.1                                                 |
| `DEVICE_PATH`        | Device location                                   | device/asus/I003D                                            |
| `DEVICE_NAME`        | Model name                                        | I003D                                                        |
| `MAKEFILE_NAME`      | Makefile name                                     | twrp_I003D                                                   |
| `BUILD_TARGET`       | Build Target Partition (boot/recovery/vendorboot) | recovery                                                     |
| `RECOVERY_INSTALLER`       | Include recovery installer zip | false                               |

-----

## Parameter Description (PBRP)

| Name                 | Description                                       | Example                                                      |
| -------------------- | ------------------------------------------------- | ------------------------------------------------------------ |
| `Deploy Type (TEST/BETA/OFFICIAL)`    |Deploy Type                                      |TEST 
| `MANIFEST_URL`       | Source address                                    | https://github.com/PitchBlackRecoveryProject/manifest_pb.git |
| `MANIFEST_BRANCH`    | Source branch                                     | android-12.1                                                    |
| `DEVICE_TREE_URL`    | Device address                                    | https://github.com/PitchBlackRecoveryProject/android_device_asus_I003D         |
| `DEVICE_TREE_BRANCH` | Device branch                                     | android-12.1                                                 |
| `VENDOR_NAME`        | manufacturer                                   | asus                                            |
| `DEVICE_NAME`        | Model name                                        | I003D                                                        |
| `MAKEFILE_NAME`      | Makefile name                                     | twrp_I003D                                                   |
| `BUILD_TARGET`       | Build Target Partition (boot/recovery/vendorboot) | recovery                                                     |

-----

## Parameter Description (SHRP)

| Name                 | Description                                       | Example                                                      |
| -------------------- | ------------------------------------------------- | ------------------------------------------------------------ |
| `Deploy Type (TEST/BETA/OFFICIAL)`    |Deploy Type                                      |TEST 
| `MANIFEST_URL`       | Source address                                    | https://github.com/SHRP/manifest.git |
| `MANIFEST_BRANCH`    | Source branch                                     | android-12.1                                                    |
| `DEVICE_TREE_URL`    | Device address                                    | https://github.com/SHRP/android_device_asus_I003D         |
| `DEVICE_TREE_BRANCH` | Device branch                                     | android-12.1                                                 |
| `VENDOR_NAME`        | manufacturer                                   | asus                                            |
| `DEVICE_NAME`        | Model name                                        | I003D                                                        |
| `MAKEFILE_NAME`      | Makefile name                                     | twrp_I003D                                                   |
| `BUILD_TARGET`       | Build Target Partition (boot/recovery/vendorboot) | recovery                                                     |

-----

