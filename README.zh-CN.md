# 关于本项目

If you are not a native Chinese speaker, please click [here](README.md) to return to the English version of README.

**我赶时间** ，点击跳转到 [下载页面](#在-github-下载最新版) 。

这里是 [BtbN/FFmpeg-Builds](https://github.com/BtbN/FFmpeg-Builds) 的分支项目，用于编译 **非自由 (nonfree)** 版本的 FFmpeg 。该版本包含一些常用且不符合 GPL 或 LGPL 的编解码器，例如 **fdk-aac** ，并支持较为全面的硬件编解码。当然，如果您愿意承受“自由”的代价，如功能缺失带来的不便，您可以随时前往 [FFmpeg](https://ffmpeg.org/download.html) 的官方下载页面获取符合 GPL 与 LGPL 的软件包。

正常情况下，本项目每隔 14 天自动构建并发布一次。由于时间精力有限，我只在 **GitHub** 和 **Gitea** 平台处理 Issues 和 PR ，并且我不会花太多的时间与精力维护这个项目，因此提交的 Issue 和 PR 以及自动构建错误可能不会得到及时解决。您也可以自己分叉 [上游项目](https://github.com/BtbN/FFmpeg-Builds) 自行构建符合您自己的需求的软件，这不会很难。

你可以查看 [下方的表格](#在-github-下载最新版) 来获取最新构建的 FFmpeg 非自由版本软件包，也可以在 [Releases](https://github.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/) 中自行获取较旧的版本。需要注意的是，自动构建有时会提前创建新的 Release ，而来不及上传所有文件，此时您可能会遇到下载问题，请您稍等片刻。

我们强烈推荐您使用 **共享库** **(Shared)** 版本，因为它可被绝大部分程序直接调用API，并且占用更少的磁盘空间。不过，如果您习惯使用便携式软件，或者因为电脑上已经安装了共享库版本，您需要保证兼容性，那么 **单文件** **(SA)** 版本更合适。

## 在 GitHub 下载最新版

<table>
    <thead>
        <tr>
            <th>架构</th>
            <th>系统</th>
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

**注意**：如果你想在其他网站下载，请点击： [Gitea](https://gitea.com/Zara-Line/FFmpeg-Stable-Nonfree/releases/latest) [Codeberg](https://codeberg.org/Zara-Line/FFmpeg-Stable-Nonfree/releases/latest) [Gitlab](https://gitlab.com/Zara-Line/FFmpeg-Stable-Nonfree/-/releases/latest)

## 以下是上游项目的 README (暂未翻译)

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

* `4.4`/`5.0`/`5.1`/`6.0`/`6.1`/`7.0`/`7.1`/`8.0`/`8.1`  to build from the respective release branch instead of master.
* `debug` to not strip debug symbols from the binaries. This increases the output size by about 250MB.
* `lto` build all dependencies and ffmpeg with -flto=auto (HIGHLY EXPERIMENTAL, broken for Windows, sometimes works for Linux)


