# CSC UI
## 注意：自己弄着玩的，不是那种类原生！

## Getting Started

To get started with the CSCUI sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

### 1. Initialize your local repository
```bash
repo init -u https://github.com/CSC-UI/manifest.git -b 12.1
```

### 2. Sync up
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### 3. Clone your device sources repositories

### 4. Initialize the ROM environment with the envsetup.sh script
```bash
. build/envsetup.sh
```

### 5. Lunch your device
```bash
lunch csc_<$device_name>-<$buildtype>
```

### 6. Start compilation
```bash
mka csc
```

## Credits
- [AcmeUI](https://github.com/AcmeUI)
- [ArrowOS](https://github.com/ArrowOS)
- [LineageOS](https://github.com/LineageOS)
- [Project-Kaleidoscope](https://github.com/Project-Kaleidoscope)
- [ProtonAOSP](https://github.com/ProtonAOSP)
