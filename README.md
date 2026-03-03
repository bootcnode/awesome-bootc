# Awesome bootc [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Discover Awesome New bootc Projects

**bootc** (bootable containers) enables "transactional, in-place operating system updates using OCI/Docker container images." 

It blends traditional OS with the tooling and workflow of modern containers. 

**PR's ARE WELCOME** - [Submit your project](https://github.com/bootcnode/awesome-bootc/pulls)

## Contents

- [Official Resources](#official-resources)
- [Core Projects](#core-projects)
- [Base Images](#base-images)
- [Image Building Tools](#image-building-tools)
- [Universal Blue Ecosystem](#universal-blue-ecosystem)
  - [Official Images](#official-images)
  - [Gaming](#gaming)
  - [Developer Experience](#developer-experience)
- [BlueBuild Ecosystem](#bluebuild-ecosystem)
- [Community Desktop Images](#community-desktop-images)
  - [GNOME-based](#gnome-based)
  - [KDE-based](#kde-based)
  - [Tiling Window Managers](#tiling-window-managers)
  - [Retro/Themed](#retrothemed)
  - [Security-focused](#security-focused)
  - [Mobile/Embedded](#mobileembedded)
- [Bootc Multi-Distro](#bootc-multi-distro)
- [Server & Infrastructure](#server--infrastructure)
- [Hardware-Specific Images](#hardware-specific-images)
- [Examples and Tutorials](#examples-and-tutorials)
- [Documentation & Learning](#documentation--learning)
- [Videos and Demos](#videos-and-demos)
- [Community](#community)
- [Templates](#templates)
- [Related Projects](#related-projects)

## Official Resources

### Core Projects

- [bootc](https://github.com/containers/bootc) - Official bootc project repository
- [bootc-dev/bootc](https://github.com/bootc-dev/bootc) - Development repository for bootc
- [Fedora bootc Documentation](https://docs.fedoraproject.org/en-US/bootc/) - Comprehensive official documentation
- [bootc Getting Started Guide](https://docs.fedoraproject.org/en-US/bootc/getting-started/) - Official getting started documentation

### Documentation

- [RHEL Image Mode Documentation](https://docs.redhat.com/en/documentation/red_hat_enterprise_linux/9/html/using_image_mode_for_rhel_to_build_deploy_and_manage_operating_systems/) - Red Hat Enterprise Linux bootc documentation
- [bootc Manual Pages](https://linuxcommandlibrary.com/man/bootc) - Complete command reference
- [Building bootc Images](https://docs.fedoraproject.org/en-US/bootc/building-containers/) - Guide to building derived bootc container images

## Core Projects

The foundational projects that make Fedora Atomic and bootc possible.

| Project | Stars | Description |
|---------|-------|-------------|
| [bootc-dev/bootc](https://github.com/bootc-dev/bootc) | 1,897 | Boot and upgrade via container images - the core bootc project |
| [ostreedev/ostree](https://github.com/ostreedev/ostree) | 1,588 | Operating system and container binary deployment and upgrades |
| [coreos/bootupd](https://github.com/coreos/bootupd) | 186 | Bootloader updater for OSTree systems |

## Base Images

* **AlmaLinux**
  - [AlmaLinux bootc Images](https://quay.io/repository/almalinuxorg/almalinux-bootc?tab=tags) - AlmaLinux bootc image

* **CentOS Stream**
  - [quay.io/centos-bootc/centos-bootc:stream9](https://quay.io/repository/centos-bootc/centos-bootc) - CentOS Stream 9 bootc image
  - [quay.io/centos-bootc/centos-bootc:stream10](https://quay.io/repository/centos-bootc/centos-bootc) - CentOS Stream 10 bootc image (in development)

* **Fedora**
  - [quay.io/fedora/fedora-bootc:42](https://quay.io/repository/fedora/fedora-bootc) - Official Fedora bootc base image

* **Red Hat Enterprise Linux**
  - [registry.redhat.io/rhel9/rhel-bootc:9.4](https://catalog.redhat.com/software/containers/rhel9/rhel-bootc/) - RHEL 9 bootc base image (requires Red Hat subscription)

## Image Building Tools

Tools for creating custom bootc and Fedora Atomic images.

| Project | Stars | Description |
|---------|-------|-------------|
| [osbuild/bootc-image-builder](https://github.com/osbuild/bootc-image-builder) | 411 | A container for deploying bootable container images |
| [podman-desktop/extension-bootc](https://github.com/podman-desktop/extension-bootc) | 467 | Podman Desktop extension for bootc and disk image generation |
| [coreos/coreos-assembler](https://github.com/coreos/coreos-assembler) | 382 | Tooling container to assemble CoreOS-like systems |
| [blue-build/cli](https://github.com/blue-build/cli) | 154 | BlueBuild's command line program for building custom Fedora Atomic images |
| [FyraLabs/readymade](https://github.com/FyraLabs/readymade) | 64 | Install ready-made distribution images |
| [ublue-os/bootc-image-builder-action](https://github.com/ublue-os/bootc-image-builder-action) | 10 | GitHub Action for bootc image building |
| [system-reinstall-bootc](https://developers.redhat.com/articles/2025/how-install-image-mode-system-using-system-reinstall-bootc) | - | Tool to reinstall existing systems as bootc |

## Universal Blue Ecosystem

[Universal Blue](https://universal-blue.org/) is a community project building custom Fedora Atomic images with enhanced hardware support and developer tooling.

### Official Images

| Project | Stars | Description |
|---------|-------|-------------|
| [ublue-os/bluefin](https://github.com/ublue-os/bluefin) | 2,344 | The next generation Linux workstation, designed for reliability, performance, and sustainability |
| [ublue-os/aurora](https://github.com/ublue-os/aurora) | 585 | The ultimate productivity workstation (KDE-based) |
| [ublue-os/cosmic](https://github.com/ublue-os/cosmic) | 209 | Fedora Atomic with the COSMIC desktop environment |
| [ublue-os/image-template](https://github.com/ublue-os/image-template) | 656 | Template for building your own custom Universal Blue image |

### Gaming

| Project | Stars | Description |
|---------|-------|-------------|
| [ublue-os/bazzite](https://github.com/ublue-os/bazzite) | 7,900 | Gaming-focused image for desktop PCs, handhelds, tablets, and HTPCs |
| [ublue-os/bazzite-arch](https://github.com/ublue-os/bazzite-arch) | 177 | Ready-to-game Arch Linux OCI for use in distrobox |

### Developer Experience

| Project | Stars | Description |
|---------|-------|-------------|
| [ublue-os/bazzite-dx](https://github.com/ublue-os/bazzite-dx) | 243 | The Bazzite Developer Experience |
| [ublue-os/bluefin-lts](https://github.com/ublue-os/bluefin-lts) | 98 | Bluefin LTS, built on CentOS with bootc |
| [ublue-os/bazzite-gdx](https://github.com/ublue-os/bazzite-gdx) | 68 | Bazzite for Game Developers |
| [projectbluefin/wolfifin](https://github.com/projectbluefin/wolfifin) | 24 | Building Bluefin with Wolfi |

## BlueBuild Ecosystem

[BlueBuild](https://blue-build.org/) is a toolkit for creating custom Fedora Atomic images using simple YAML recipes.

| Project | Stars | Description |
|---------|-------|-------------|
| [blue-build/template](https://github.com/blue-build/template) | 217 | Template for making your own OS image using BlueBuild |
| [blue-build/cli](https://github.com/blue-build/cli) | 154 | BlueBuild's command line program |

## Community Desktop Images

### GNOME-based

| Project | Stars | Description |
|---------|-------|-------------|
| [sodaliterocks/sodalite](https://github.com/sodaliterocks/sodalite) | 212 | A Pantheon experience for rpm-ostree |
| [jokokucing/Origami-Linux](https://github.com/jokokucing/Origami-Linux) | 44 | Next-gen Linux inspired by Japanese paper folding |
| [alotlikebeans/silvernobara](https://github.com/alotlikebeans/silvernobara) | 38 | Fedora Silverblue with Project Nobara enhancements |
| [jitcos/cabos](https://github.com/jitcos/cabos) | 13 | Hyper opinionated Fedora Silverblue spin aimed at creators |
| [Lumaeris/vedaos](https://github.com/Lumaeris/vedaos) | 8 | Opinionated custom image with GNOME, Steam, and other goodies |
| [fizzyizzy05/fizzyblue](https://github.com/fizzyizzy05/fizzyblue) | 5 | Silverblue with batteries included, focus on dev and gaming |

### KDE-based

| Project | Stars | Description |
|---------|-------|-------------|
| [travier/fedora-kinoite](https://github.com/travier/fedora-kinoite) | 19 | Custom Fedora Kinoite images with overlayed packages |
| [aleskandro/my-ostree-config](https://github.com/aleskandro/my-ostree-config) | 16 | OSTree-native container configs for custom Fedora Kinoite |
| [silverhadch/bazzite-kde-dx](https://github.com/silverhadch/bazzite-kde-dx) | 6 | Bazzite with KDE Plasma master and dev tools |
| [whelanh/myKinoiteNightly](https://github.com/whelanh/myKinoiteNightly) | 3 | Custom Kinoite Nightly with Universal Blue features |

### Tiling Window Managers

| Project | Stars | Description |
|---------|-------|-------------|
| [wayblueorg/wayblue](https://github.com/wayblueorg/wayblue) | 293 | Fedora Atomic images for Wayland compositors (Sway, Hyprland, River) |
| [zirconium-dev/zirconium](https://github.com/zirconium-dev/zirconium) | 173 | Opinionated Niri bootc image |
| [Zena-Linux/Zena](https://github.com/Zena-Linux/Zena) | 118 | Immutable Linux with Niri, MangoWC, and Dank Material Shell |
| [gabeklavans/bazzite-hyprland](https://github.com/gabeklavans/bazzite-hyprland) | 13 | Bazzite-dx with Hyprland WM |
| [KiKaraage/cosmoneer](https://github.com/KiKaraage/cosmoneer) | 12 | COSMIC + Niri + Bluefin goodies |
| [koitorin/bazzite-cosmic](https://github.com/koitorin/bazzite-cosmic) | 12 | Experimental Bazzite with COSMIC DE |
| [ergolyam/atomic-niri](https://github.com/ergolyam/atomic-niri) | 8 | Custom Fedora Atomic with Niri compositor |
| [gabeklavans/bazzite-niri](https://github.com/gabeklavans/bazzite-niri) | 8 | Custom bazzite-based image with Niri WM |
| [tulilirockz/piperita](https://github.com/tulilirockz/piperita) | 7 | Zirconium with cool stuff |

### Retro/Themed

The [winblues](https://github.com/winblues) project creates nostalgic desktop experiences:

| Project | Stars | Description |
|---------|-------|-------------|
| [winblues/blue95](https://github.com/winblues/blue95) | 985 | A desktop for your childhood home's computer room (Windows 95 theme) |
| [winblues/blue9](https://github.com/winblues/blue9) | 35 | A modern desktop with an OS9 look |
| [winblues/winblues7](https://github.com/winblues/winblues7) | 34 | A glassy sheen for your Steam Machine (Windows 7 theme) |
| [winblues/bluexp](https://github.com/winblues/bluexp) | 31 | Fedora XP theme |
| [winblues/vauxite](https://github.com/winblues/vauxite) | 27 | Modern and lightweight Xfce desktop |
| [bluebootsy/os](https://github.com/bluebootsy/os) | 7 | A Fedora BootC OS themed like 2003, updated like 2025 |

### Security-focused

| Project | Stars | Description |
|---------|-------|-------------|
| [secureblue/secureblue](https://github.com/secureblue/secureblue) | 844 | Security-focused desktop and server Linux operating system |
| [secureblue/secureblue.dev](https://github.com/secureblue/secureblue.dev) | 17 | secureblue's static website |
| [os-images/workstation](https://github.com/os-images/workstation) | 1 | Fedora Atomic with more secure defaults (independent secureblue fork) |

### Mobile/Embedded

| Project | Stars | Description |
|---------|-------|-------------|
| [pocketblue/pocketblue](https://github.com/pocketblue/pocketblue) | 356 | Fedora Atomic for mobile devices |
| [J3RN/basalt](https://github.com/J3RN/basalt) | 3 | Immutable Linux for the PinePhone based on Fedora Silverblue |
| [philbudden/blueberry](https://github.com/philbudden/blueberry) | 2 | Light-weight server OS for aarch64-SBCs like Raspberry Pi |
| [renner0e/fedora-pi-bootc](https://github.com/renner0e/fedora-pi-bootc) | 2 | Raspberry Pi4 Fedora bootc image |

## Bootc Multi-Distro

The [bootcrew](https://github.com/bootcrew) organization is porting bootc to multiple Linux distributions:

| Project | Stars | Description |
|---------|-------|-------------|
| [bootcrew/arch-bootc](https://github.com/bootcrew/arch-bootc) | 96 | Arch Linux with Bootc composefs-native backend |
| [bootcrew/debian-bootc](https://github.com/bootcrew/debian-bootc) | 68 | Debian Bootc experiment with composefs native backend |
| [CentOS/centos-bootc](https://github.com/CentOS/centos-bootc) | 47 | CentOS Stream bootable container images |
| [bootcrew/ubuntu-bootc](https://github.com/bootcrew/ubuntu-bootc) | 31 | Ubuntu Bootc experiment |
| [bootcrew/opensuse-bootc](https://github.com/bootcrew/opensuse-bootc) | 13 | OpenSUSE bootc with composefs native backend |
| [bootcrew/steamos-bootc](https://github.com/bootcrew/steamos-bootc) | 10 | SteamOS Bootc image (WIP) |
| [bootcrew/gentoo-bootc](https://github.com/bootcrew/gentoo-bootc) | 8 | Gentoo bootc with composefs native backend |
| [bootcrew/linuxmint-bootc](https://github.com/bootcrew/linuxmint-bootc) | 3 | Linux Mint Bootc with composefs native backend |

## Server & Infrastructure

| Project | Stars | Description |
|---------|-------|-------------|
| [poseidon/matchbox](https://github.com/poseidon/matchbox) | 1,399 | Network boot and provision Fedora CoreOS and Flatcar Linux clusters |
| [centos-workstation/main](https://github.com/centos-workstation/main) | 13 | CentOS Stream-based base image |
| [centos-workstation/homeserver](https://github.com/centos-workstation/homeserver) | 13 | CentOS Homeserver appliance with Portainer, Cockpit and ZFS |
| [tuna-os/tunaOS](https://github.com/tuna-os/tunaOS) | 31 | Modern cloud-native experience for Enterprise Linux Desktop |
| [Venefilyn/veneos](https://github.com/Venefilyn/veneos) | 13 | Bootc images based on Fedora Atomic & Fedora CoreOS |
| [yureutaejin/yob](https://github.com/yureutaejin/yob) | 12 | YOB: Your own OS using bootc |

## Hardware-Specific Images

| Project | Stars | Description |
|---------|-------|-------------|
| [lauretano/t2-atomic](https://github.com/lauretano/t2-atomic) | 24 | T2 hardware enablement for Fedora Atomic Desktops (Apple T2 Macs) |
| [BrickMan240/ublue-tuxedo-tcc](https://github.com/BrickMan240/ublue-tuxedo-tcc) | 15 | Universal Blue images with Tuxedo Control Center |
| [ublue-os/framework](https://github.com/ublue-os/framework) | 14 | OCI Images for Framework hardware |
| [askpng/atomic-t480s](https://github.com/askpng/atomic-t480s) | 7 | Atomic Fedora for Lenovo T480/s devices |
| [kansei-os/t2-atomic](https://github.com/kansei-os/t2-atomic) | 5 | Fedora Atomic optimized for T2 Macs |
| [serandel/bluefin-dx-slimbook](https://github.com/serandel/bluefin-dx-slimbook) | 4 | Custom Bluefin DX image with Slimbook laptop support |
| [achhabra2/fw13-amd-kinoite](https://github.com/achhabra2/fw13-amd-kinoite) | 3 | Customized Kinoite Image for AMD Framework 13 |

## Examples and Tutorials

### Getting Started

- [Red Hat Developer bootc Guide](https://developers.redhat.com/articles/2024/09/24/bootc-getting-started-bootable-containers) - Comprehensive getting started guide with video demos
- [Fedora bootc Building Guide](https://docs.fedoraproject.org/en-US/bootc/building-from-scratch/) - Creating "from scratch" bootc base container images
- [RHEL bootc Building and Testing](https://docs.redhat.com/en/documentation/red_hat_enterprise_linux/9/html/using_image_mode_for_rhel_to_build_deploy_and_manage_operating_systems/building-and-testing-the-rhel-bootable-container-images_using-image-mode-for-rhel-to-build-deploy-and-manage-operating_systems) - Building and testing RHEL bootc images

### Example Repositories

- [redhat-et/bootc-examples](https://github.com/redhat-et/bootc-examples) - Collection of bootc examples and Containerfiles (Archived - moved to comprehensive documentation)
- [Fedora bootc Base Images Repository](https://docs.fedoraproject.org/en-US/bootc/base-images/) - Reference documentation for official base images

### Automation Examples

- [Ansible and bootc](https://ryandaniels.ca/blog/ansible-and-bootc/) - Guide on using Ansible with bootc systems
- [BootcBlade](https://github.com/spmfox/BootcBlade) - Ansible automation for deploying KVM hypervisor using bootc and Fedora Server

## Documentation & Learning

| Project | Stars | Description |
|---------|-------|-------------|
| [Malix-Labs/Awesome-Atomic](https://github.com/Malix-Labs/Awesome-Atomic) | 1,187 | Awesome curated knowledge-base about atomic systems |
| [coreos/docs](https://github.com/coreos/docs) | 880 | Documentation for CoreOS projects |
| [mikeroyal/Fedora-Guide](https://github.com/mikeroyal/Fedora-Guide) | 250 | Comprehensive Fedora/CentOS/RHEL Guide |
| [iaacornus/silverblue-postinstall_upgrade](https://github.com/iaacornus/silverblue-postinstall_upgrade) | 79 | Tips, tricks & tutorials for OSTree based systems |
| [fedora-silverblue/silverblue-docs](https://github.com/fedora-silverblue/silverblue-docs) | 66 | Official Fedora Silverblue documentation |
| [coreos/fedora-coreos-docs](https://github.com/coreos/fedora-coreos-docs) | 62 | Documentation for Fedora CoreOS |
| [ublue-os/docs.bazzite.gg](https://github.com/ublue-os/docs.bazzite.gg) | 30 | Documentation website for Bazzite |
| [Szwendacz99/fedora-immutable-cheatsheet](https://github.com/Szwendacz99/fedora-immutable-cheatsheet) | 17 | Cheatsheet for immutable Fedora variants |
| [get-aurora-dev/aurora-web](https://github.com/get-aurora-dev/aurora-web) | 15 | Website for the Aurora workstation |

## Videos and Demos

### Official Videos

- [bootc: Hands on Demo](https://www.youtube.com/watch?v=fccox6sGCWA) - Valentin Rothberg demonstrates bootable containers concepts
- [bootc: Generating an ecosystem around bootable OCI containers](https://www.youtube.com/watch?v=XzdLxJZ0Lto) - All Systems Go! 2024 conference talk
- [Universal Blue revolutionizes the Linux desktop experience](https://www.youtube.com/watch?v=XpKFcLqbd-A) - Community spotlight on Universal Blue project

### Educational Content

- [Red Hat Developer Video Demos](https://developers.redhat.com/articles/2024/09/24/bootc-getting-started-bootable-containers) - Interactive video tutorials and hands-on demos

## Community

### Forums and Discussion

- [Fedora Discussion - bootc-initiative tag](https://discussion.fedoraproject.org/tag/bootc-initiative) - Official Fedora discussion forum
- [bootc GitHub Discussions](https://github.com/bootc-dev/bootc/discussions) - Upstream bootc project discussions
- [CNCF Slack #bootc channel](https://cloud-native.slack.com/) - Real-time community chat
- [Matrix Channel](https://docs.fedoraproject.org/en-US/bootc/community/) - Matrix-based community discussions

### Meetings and Events

- **Weekly Meetings**: Tuesdays, 14:00 UTC
- **Location**: Matrix #meeting-1 channel
- **Video Meetings**: meet.google.com/poh-xmxm-qyc (when scheduled)
- **Meeting Notes**: Available in the [issue tracker repo](https://github.com/bootc-dev/bootc/discussions)

### Support Channels

- [bootc Issue Tracker](https://github.com/bootc-dev/bootc/issues) - Bug reports and feature requests
- [Reddit /r/redhat bootc discussions](https://www.reddit.com/r/redhat/comments/1gjbnby/bootc_questions/) - Community Q&A

## Templates

Ready-to-use templates for creating your own custom images:

| Project | Stars | Forks | Description |
|---------|-------|-------|-------------|
| [ublue-os/image-template](https://github.com/ublue-os/image-template) | 656 | 137 | Official Universal Blue template |
| [blue-build/template](https://github.com/blue-build/template) | 217 | 41 | BlueBuild template with recipe.yml |
| [blue-build/legacy-template](https://github.com/blue-build/legacy-template) | 126 | 160 | Legacy BlueBuild starting point |

---

## Specialty Images

### ROCm/AI Focused

| Project | Stars | Description |
|---------|-------|-------------|
| [BTekV4/bazzite-gnome-rocm](https://github.com/BTekV4/bazzite-gnome-rocm) | 6 | Bazzite GNOME with ROCm support |
| [Sir-Mudkip/ucore-rocm](https://github.com/Sir-Mudkip/ucore-rocm) | 0 | Custom uCore image with ROCm for LLM support |

### Enterprise/Professional

| Project | Stars | Description |
|---------|-------|-------------|
| [L0g0ff/KompassOS](https://github.com/L0g0ff/KompassOS) | 6 | Aurora for DevOps engineers, SysAdmins, and Network Engineers |
| [EpicOfficer/quantix](https://github.com/EpicOfficer/quantix) | 4 | Personal distro based on Bazzite with VFIO by default |
| [large-farva/outpost](https://github.com/large-farva/outpost) | 1 | Fedora Kinoite with DoD CAC support |

### Nix Integration

| Project | Stars | Description |
|---------|-------|-------------|
| [alyraffauf/bazznix](https://github.com/alyraffauf/bazznix) | 12 | Bazzite, but Nixified |
| [DXC-0/daemonix](https://github.com/DXC-0/daemonix) | 7 | Custom Fedora/ublue image with Nix integrated out of the box |
| [DXC-0/Nix-Dotfiles](https://github.com/DXC-0/Nix-Dotfiles) | 6 | Fedora Atomic/Immutable dotfiles with Nix and Home Manager |
| [randogoth/deinonyxus](https://github.com/randogoth/deinonyxus) | 2 | Bluefin DX spin with Nix and sprinkles |

---

## Related Projects

### Container Technologies

- [OSTree](https://ostreedev.github.io/ostree/) - Git-like versioning for filesystem trees (underlying technology)
- [Podman](https://podman.io/) - Daemonless container engine compatible with bootc
- [Skopeo](https://github.com/containers/skopeo) - Command line utility for container image operations

### Immutable OS Projects

- [Fedora Atomic Desktops](https://fedoraproject.org/atomic-desktops/) - Related immutable desktop operating systems
- [openSUSE MicroOS](https://microos.opensuse.org/) - Immutable OS with transactional updates
- [NixOS](https://nixos.org/) - Declarative Linux distribution

### Cloud Native

- [Cloud Native Computing Foundation](https://cncf.io/) - bootc is a CNCF Sandbox project
- [OCI Runtime Specification](https://opencontainers.org/) - Open Container Initiative standards

## Contributing

Contributions welcome! Read the [contribution guidelines](https://github.com/bootc-dev/bootc/blob/main/CONTRIBUTING.md) first.

Please ensure your pull request adheres to the following guidelines:
- Search previous suggestions before making a new one
- Make an individual pull request for each suggestion
- Use the following format: `[Resource Name](link) - Description.`
- Keep descriptions short and simple, but descriptive
- Check your spelling and grammar
- New categories or improvements to the existing categorization are welcome

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
