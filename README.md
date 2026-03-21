# About This Repository

如果您是中文母语者且不会英文，请[点击这个链接]()查看中文版说明，不过我现在还没做好，您先用机翻凑合看下。

This branch repository is a fork of [BtbN/FFmpeg-Builds](https://github.com/BtbN/FFmpeg-Builds) used to automatically build the nonfree version of FFmpeg, including commonly used codecs such as **fdk-aac** that do not comply with GPL or LGPL standards, while also supporting a relatively comprehensive range of hardware encoding and decoding capabilities. 

Under normal circumstances, this project automatically builds every 20 days. I would not spend much time or effort maintaining this repository, so submitted issues, pulled requests, and errors of Actions may not be addressed in a timely manner. You can also try forking the [upstream repository](https://github.com/BtbN/FFmpeg-Builds) and building the software that meets your needs yourself—it won't be too difficult.

You can click [here](https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/latest) to get the latest pre-built FFmpeg nonfree package, or obtain other versions from [Releases](https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases). Please note that the automated build process may sometimes create a new Release in advance without having had time to upload all the files. In such cases, you may encounter download issues—please wait a moment.

## Below is the README of the Upstream Repository

# FFmpeg Static Auto-Builds

Static Windows (x86_64) and Linux (x86_64) Builds of ffmpeg master and latest release branch.

Windows builds are targetting Windows 7 and newer, provided UCRT is installed.
The minimum supported version is Windows 10 22H2, no guarantees on anything older.

Linux builds are targetting RHEL/CentOS 8 (glibc-2.28 + linux-4.18) and anything more recent.

## Auto-Builds

Builds run daily at 12:00 UTC (or GitHubs idea of that time) and are automatically released on success.

**Auto-Builds run ONLY for win(arm)64 and linux(arm)64. There are no win32/x86 auto-builds, though you can produce win32 builds yourself following the instructions below.**

### Release Retention Policy

- The last build of each month is kept for two years.
- The last 14 daily builds are kept.
- The special "latest" build floats and provides consistent URLs always pointing to the latest build.

## Package List

For a list of included dependencies check the scripts.d directory.
Every file corresponds to its respective package.

## How to make a build

### Prerequisites

* bash
* docker

### Build Image

* `./makeimage.sh target variant [addin [addin] [addin] ...]`

### Build FFmpeg

* `./build.sh target variant [addin [addin] [addin] ...]`

On success, the resulting zip file will be in the `artifacts` subdir.

### Targets, Variants and Addins

Available targets:
* `win64` (x86_64 Windows)
* `win32` (x86 Windows)
* `linux64` (x86_64 Linux, glibc>=2.28, linux>=4.18)
* `linuxarm64` (arm64 (aarch64) Linux, glibc>=2.28, linux>=4.18)

The linuxarm64 target will not build some dependencies due to lack of arm64 (aarch64) architecture support or cross-compiling restrictions.

* `davs2` and `xavs2`: aarch64 support is broken.
* `libmfx` and `libva`: Library for Intel QSV, so there is no aarch64 support.

Available variants:
* `gpl` Includes all dependencies, even those that require full GPL instead of just LGPL.
* `lgpl` Lacking libraries that are GPL-only. Most prominently libx264 and libx265.
* `nonfree` Includes fdk-aac in addition to all the dependencies of the gpl variant.
* `gpl-shared` Same as gpl, but comes with the libav* family of shared libs instead of pure static executables.
* `lgpl-shared` Same again, but with the lgpl set of dependencies.
* `nonfree-shared` Same again, but with the nonfree set of dependencies.

All of those can be optionally combined with any combination of addins:
* `4.4`/`5.0`/`5.1`/`6.0`/`6.1`/`7.0`/`7.1` to build from the respective release branch instead of master.
* `debug` to not strip debug symbols from the binaries. This increases the output size by about 250MB.
* `lto` build all dependencies and ffmpeg with -flto=auto (HIGHLY EXPERIMENTAL, broken for Windows, sometimes works for Linux)
