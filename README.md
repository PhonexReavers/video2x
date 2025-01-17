<p align="center">
   <img src="https://github.com/user-attachments/assets/5cd63373-e806-474f-94ec-6e04963bf90f"
        alt="Video2X: A machine learning-based video super resolution and frame interpolation framework."/>
   </br>
   <img src="https://img.shields.io/github/v/release/k4yt3x/video2x?style=flat-square"/>
   <img src="https://img.shields.io/github/downloads/k4yt3x/video2x/total?style=flat-square"/>
   <img src="https://img.shields.io/github/license/k4yt3x/video2x?style=flat-square"/>
   <img src="https://img.shields.io/github/sponsors/k4yt3x?style=flat-square&link=https%3A%2F%2Fgithub.com%2Fsponsors%2Fk4yt3x"/>
   <img src="https://img.shields.io/badge/dynamic/json?color=%23e85b46&label=Patreon&query=data.attributes.patron_count&suffix=%20patrons&url=https%3A%2F%2Fwww.patreon.com%2Fapi%2Fcampaigns%2F4507807&style=flat-square"/>
</p>

## 🌟 Version 6.0.0

Video2X 6.0.0 highlights:

- Complete rewrite of the Video2X project in C/C++.
- Faster and more efficient architecture.
- Cross-platform support for Windows and Linux.
- Vastly improved output quality.
- New GUI and installer for easy setup on Windows.

<details>
<summary>Click to see more details</summary>

Version 6.0.0 is a complete rewrite of this project in C/C++. It:

- genuinely works this time, with much less hassle compared to the 5.0.0 beta;
- is blazing fast, thanks to the new optimized pipeline and the efficiency of C/C++;
- is cross-platform, available now for both Windows and Linux;
- offers significantly better output quality with Anime4K v4, RealESRGAN, and RIFE;
- supports two modes: filtering (upscaling) and frame interpolation;
- supports Anime4K v4 and all custom MPV-compatible GLSL shaders;
- supports RealESRGAN (all three models) via ncnn and Vulkan;
- supports RIFE via ncnn and Vulkan; and
- requires zero additional disk space during processing, just space for the final output.

Support for RealCUGAN is coming soon.

</details>

![6.2.0-screenshot](https://github.com/user-attachments/assets/68c6d65b-89a2-4553-a783-f5e663aa1313)

## [🪟 Install on Windows](https://docs.video2x.org/installing/windows-qt6.html)

**[Download the Latest Windows Installer Executable (6.2.0)](https://github.com/k4yt3x/video2x/releases/download/6.2.0/video2x-qt6-windows-amd64-installer.exe)**

You can download the latest Windows release on the [releases page](https://github.com/k4yt3x/video2x/releases/latest). For basic GUI usage, refer to the [documentation](https://docs.video2x.org/running/desktop.html). If you're unable to download directly from GitHub, try the [mirror site](https://files.k4yt3x.com/Projects/Video2X). The GUI currently supports the following languages:

- English (United States)
- 简体中文（中国）
- 日本語（日本）
- Português (Portugal)

## [🐧 Install on Linux](https://docs.video2x.org/installing/linux.html)

You can install Video2X on Arch Linux using the [video2x-git](https://aur.archlinux.org/packages/video2x-git) AUR package or on Ubuntu/Debian using the `.deb` package from the [releases page](https://github.com/k4yt3x/video2x/releases/latest). If you'd like to build from source, refer to the [PKGBUILD](packaging/arch/PKGBUILD) file for a general overview of the required packages and commands. If you'd prefer not to compile the program from source, consider using the container image below.

## [📦 Container Image](https://docs.video2x.org/running/container.html)

Video2X [container images](https://github.com/k4yt3x/video2x/pkgs/container/video2x) are available on the GitHub Container Registry for easy deployment on Linux and macOS. If you already have Docker/Podman installed, only one command is needed to start upscaling a video. For more information on how to use Video2X's Docker image, please refer to the [documentation](https://docs.video2x.org/running/container.html).

## [📔 Google Colab](https://colab.research.google.com/drive/1gWEwcA9y57EsxwOjmLNmNMXPsafw0kGo)

You can use Video2X on [Google Colab](https://colab.research.google.com/) **for free** if you don't have a powerful GPU of your own. You can borrow a powerful GPU (NVIDIA T4, L4, or A100) on Google's server for free for a maximum of 12 hours per session. **Please use the free resource fairly** and do not create sessions back-to-back and run upscaling 24/7. This might result in you getting banned. You can get [Colab Pro/Pro+](https://colab.research.google.com/signup/pricing) if you'd like to use better GPUs and get longer runtimes. Usage instructions are embedded in the [Colab Notebook](https://colab.research.google.com/drive/1gWEwcA9y57EsxwOjmLNmNMXPsafw0kGo).

## [💬 Telegram Discussion Group](https://t.me/video2x)

Join our Telegram discussion group to ask any questions you have about Video2X, chat directly with the developers, or discuss super resolution, frame interpolation technologies, or the future of Video2X in general.

## [📖 Documentation](https://docs.video2x.org/)

Comprehensive documentation for Video2X is available at [https://docs.video2x.org/](https://docs.video2x.org/). It offers detailed instructions on how to [build](https://docs.video2x.org/building/index.html), [install](https://docs.video2x.org/installing/index.html), [use](https://docs.video2x.org/running/index.html), and [develop](https://docs.video2x.org/developing/index.html) with this program.

## 📽️ Video Demos (Outdated)

![Spirited Away Demo](https://user-images.githubusercontent.com/21986859/49412428-65083280-f73a-11e8-8237-bb34158a545e.png)\
_Upscale demo: Spirited Away's movie trailer_

- **Spirited Away**: [YouTube](https://youtu.be/mGEfasQl2Zo) | [Bilibili](https://www.bilibili.com/video/BV1V5411471i/)
  - 360P to 4K
  - The [original video](https://www.youtube.com/watch?v=ByXuk9QqQkk)'s copyright belongs to 株式会社スタジオジブリ
- **Bad Apple!!**: [YouTube](https://youtu.be/A81rW_FI3cw) | [Bilibili](https://www.bilibili.com/video/BV16K411K7ue)
  - 384P 30 FPS to 4K 120 FPS with waifu2x and DAIN
  - The [original video](https://www.nicovideo.jp/watch/sm8628149)'s copyright belongs to あにら
- **The Pet Girl of Sakurasou**: [YouTube](https://youtu.be/M0vDI1HH2_Y) | [Bilibili](https://www.bilibili.com/video/BV14k4y167KP/)
  - 240P 29.97 to 1080P 60 FPS with waifu2x and DAIN
  - The original video's copyright belongs to ASCII Media Works

### Standard Test Clip

The following clip can be used to test if your setup works properly. This is also the standard clip used for running performance benchmarks.

- [Standard Test Clip (240P)](https://files.k4yt3x.com/Resources/Videos/standard-test.mp4) 4.54 MiB
- [waifu2x Upscaled Sample (1080P)](https://files.k4yt3x.com/Resources/Videos/standard-waifu2x.mp4) 4.54 MiB
- [Ground Truth (1080P)](https://files.k4yt3x.com/Resources/Videos/standard-original.mp4) 22.2 MiB

The original clip came from the anime "さくら荘のペットな彼女."\
Copyright of this clip belongs to 株式会社アニプレックス.

## ⚖️ License

This project is licensed under [GNU AGPL version 3](https://www.gnu.org/licenses/agpl-3.0.txt).\
Copyright (C) 2018-2024 K4YT3X and [contributors](https://github.com/k4yt3x/video2x/graphs/contributors).

![AGPLv3](https://www.gnu.org/graphics/agplv3-155x51.png)

This project includes or depends on these following projects:

| Project                                                                               | License         |
| ------------------------------------------------------------------------------------- | --------------- |
| [bloc97/Anime4K](https://github.com/bloc97/Anime4K)                                   | MIT License     |
| [FFmpeg/FFmpeg](https://www.ffmpeg.org/)                                              | LGPLv2.1, GPLv2 |
| [nihui/rife-ncnn-vulkan](https://github.com/nihui/rife-ncnn-vulkan)                   | MIT License     |
| [Tencent/ncnn](https://github.com/Tencent/ncnn)                                       | BSD 3-Clause    |
| [xinntao/Real-ESRGAN-ncnn-vulkan](https://github.com/xinntao/Real-ESRGAN-ncnn-vulkan) | MIT License     |

More licensing information can be found in the [NOTICE](NOTICE) file.

## 🌺 Special Thanks

Special thanks to the following individuals for their significant contributions to the project, listed in alphabetical order.

- [@ArchieMeng](https://github.com/archiemeng)
- [@BrianPetkovsek](https://github.com/BrianPetkovsek)
- [@ddouglas87](https://github.com/ddouglas87)
- [@lhanjian](https://github.com/lhanjian)
- [@nihui](https://github.com/nihui)
- [@sat3ll](https://github.com/sat3ll)
