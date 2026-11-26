# Sony Xperia 1 V (`pdx234`) — LineageOS 24.0 (Android 17) Kernel (ReSukiSU + SUSFS)

Cloud-compiled custom kernel for **Sony Xperia 1 V (`pdx234`)** running **LineageOS 24.0 (Android 17)**, based directly on `LineageOS/android_kernel_sony_sm8550` (`lineage-24.0`) and the exact `IKCONFIG` extracted from official LineageOS 24.0 `boot.img`.

## Features
- **ReSukiSU** (pinned commit with full KPM + SUSFS v2.1.0 compatibility)
- **SUSFS v2.1.0** (filesystem & root hiding)
- **KPM** (Kernel Patch Module support via `patch_linux`)
- **Baseband-guard LSM** (modem/baseband partition protection)
- **LZ4 1.10.0 + LZ4KD ZRAM** & **TCP BBR**
- Outputs both **AnyKernel3 zip** and a ready-to-flash **Boot Header v4 `boot.img`** (`fastboot flash boot ...`)

## Credits
Adapted from `spacealtctrl/a16_sony_sm8550_SukiSU_SUSFS` for LineageOS 24.0 (`lineage-24.0`), with upstream thanks to LineageOS, ReSukiSU, simonpunk (SUSFS), ShirkNeko, vc-teahouse (Baseband-guard), zzh20188, sidex15, and WildKernels.
