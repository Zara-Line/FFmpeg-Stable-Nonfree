# About This Repository

如果您是中文母语者且不会英文，请[点击这个链接](README.zh-CN.md)查看中文版说明。

**TL;DR** jump to the [Download Table](#download-from-github).

This branch repository is a fork of [BtbN/FFmpeg-Builds](https://github.com/BtbN/FFmpeg-Builds) used to automatically build the **nonfree** version of FFmpeg, including commonly used codecs such as **fdk-aac** that do not comply with GPL or LGPL, while also supporting a relatively comprehensive range of hardware encoding and decoding capabilities. Of course, if you're willing to sacrifice functionality and convenience in the name of "*freedom*", you can always get the GPL and LGPL versions from the repositories recommended by the [FFmpeg](https://ffmpeg.org/download.html) official.

Under normal circumstances, this project automatically builds every 14 days. Due to limited time and personal energy, issues and PRs are only accepted on **GitHub** and **Gitea**, and I would not spend much time or effort maintaining this repository, so submitted issues, pulled requests, and errors of Actions may not be addressed in a timely manner. You can also try forking the [upstream repository](https://github.com/BtbN/FFmpeg-Builds) and building the software that meets your needs yourself—it won't be too difficult.

You can check the [table below](#download-from-github) to get the latest pre-built FFmpeg nonfree package, or obtain older versions from [Releases](https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/). Please note that the auto builds process may sometimes create a new Release in advance without having had time to upload all the files. In such cases, you may encounter download issues—please wait a moment.

We strongly recommend using the **Shared** version, as it can be directly called by most of apps via its API and occupies less disk space. However, if you prefer portable apps or if you already have the Shared version installed on your computer and need to ensure compatibility, then the **SA** (*abbr* of Standalone) version is more suitable.

## Download from GitHub

<table>
    <thead>
        <tr>
            <th>Arch</th>
            <th>System</th>
            <th>Nightly</th>
            <th>8.1</th>
            <th>8.0</th>
            <th>7.1</th>
            <th>6.1</th>
            <th>5.1</th>
            <th>4.4</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="2">x64</td>
            <td class="system-col">Windows</td>
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-master-latest-win64-nonfree-shared.zip">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-master-latest-win64-nonfree.zip">SA</a></td>  <!--Nightly-->
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n8.1-latest-win64-nonfree-shared-8.1.zip">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n8.1-latest-win64-nonfree-8.1.zip">SA</a></td>  <!--8.1-->
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n8.0-latest-win64-nonfree-shared-8.0.zip">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n8.0-latest-win64-nonfree-8.0.zip">SA</a></td>  <!--8.0-->
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n7.1-latest-win64-nonfree-shared-7.1.zip">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n7.1-latest-win64-nonfree-7.1.zip">SA</a></td>  <!--7.1-->
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n6.1-latest-win64-nonfree-shared-6.1.zip">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n6.1-latest-win64-nonfree-6.1.zip">SA</a></td>  <!--6.1-->
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n5.1-latest-win64-nonfree-shared-5.1.zip">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n5.1-latest-win64-nonfree-5.1.zip">SA</a></td>  <!--5.1-->
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n4.4-latest-win64-nonfree-shared-4.4.zip">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n4.4-latest-win64-nonfree-4.4.zip">SA</a></td>  <!--4.4-->
        </tr>
        <tr>
            <td class="system-col">Linux</td>
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-master-latest-linux64-nonfree-shared.tar.xz">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-master-latest-linux64-nonfree.tar.xz">SA</a></td>
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n8.1-latest-linux64-nonfree-shared-8.1.tar.xz">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n8.1-latest-linux64-nonfree-8.1.tar.xz">SA</a></td>
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n8.0-latest-linux64-nonfree-shared-8.0.tar.xz">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n8.0-latest-linux64-nonfree-8.0.tar.xz">SA</a></td>
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n7.1-latest-linux64-nonfree-shared-7.1.tar.xz">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n7.1-latest-linux64-nonfree-7.1.tar.xz">SA</a></td>
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n6.1-latest-linux64-nonfree-shared-6.1.tar.xz">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n6.1-latest-linux64-nonfree-6.1.tar.xz">SA</a></td>
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n5.1-latest-linux64-nonfree-shared-5.1.tar.xz">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n5.1-latest-linux64-nonfree-5.1.tar.xz">SA</a></td>
            <td rowspan="3">Not provide</td>  <!--4.4-->
        </tr>
        <tr>
            <td rowspan="2">ARM64</td>
            <td class="system-col">Windows</td>
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-master-latest-winarm64-nonfree-shared.zip">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-master-latest-winarm64-nonfree.zip">SA</a></td>
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n8.1-latest-winarm64-nonfree-shared-8.1.zip">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n8.1-latest-winarm64-nonfree-8.1.zip">SA</a></td>
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n8.0-latest-winarm64-nonfree-shared-8.0.zip">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n8.0-latest-winarm64-nonfree-8.0.zip">SA</a></td>
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n7.1-latest-winarm64-nonfree-shared-7.1.zip">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n7.1-latest-winarm64-nonfree-7.1.zip">SA</a></td>
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n6.1-latest-winarm64-nonfree-shared-6.1.zip">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n6.1-latest-winarm64-nonfree-6.1.zip">SA</a></td>
            <td rowspan="2">Not provide</td>  <!--5.1-->
            <!--4.4 Not provide-->
        </tr>
        <tr>
            <td class="system-col">Linux</td>
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-master-latest-linuxarm64-nonfree-shared.tar.xz">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-master-latest-linuxarm64-nonfree.tar.xz">SA</a></td>
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n8.1-latest-linuxarm64-nonfree-shared-8.1.tar.xz">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n8.1-latest-linuxarm64-nonfree-8.1.tar.xz">SA</a></td>
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n8.0-latest-linuxarm64-nonfree-shared-8.0.tar.xz">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n8.0-latest-linuxarm64-nonfree-8.0.tar.xz">SA</a></td>
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n7.1-latest-linuxarm64-nonfree-shared-7.1.tar.xz">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n7.1-latest-linuxarm64-nonfree-7.1.tar.xz">SA</a></td>
            <td><a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n6.1-latest-linuxarm64-nonfree-shared-6.0.tar.xz">Shared</a> <a href="https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/download/latest/ffmpeg-n6.1-latest-linuxarm64-nonfree-6.1.tar.xz">SA</a></td>
            <!--5.1 Not provide-->
            <!--4.4 Not provide-->
        </tr>
    </tbody>
</table>

**Notes**: If you would like to download releases from other websites, please click: [Gitea](https://gitea.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/latest) [Codeberg](https://codeberg.org/Zara-Line/FFmpeg-Stable-Nonfree/releases/latest) [Gitlab](https://gitlab.com/Zara-Line/FFmpeg-Stable-Nonfree/-/releases/latest)

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

* `4.4`/`5.0`/`5.1`/`6.0`/`6.1`/`7.0`/`7.1`/`8.0`/`8.1` to build from the respective release branch instead of master.
* `debug` to not strip debug symbols from the binaries. This increases the output size by about 250MB.
* `lto` build all dependencies and ffmpeg with -flto=auto (HIGHLY EXPERIMENTAL, broken for Windows, sometimes works for Linux)


