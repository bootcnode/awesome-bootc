# Awesome bootc [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Discover Awesome New bootc Projects

**bootc** (bootable containers) enables "transactional, in-place operating system updates using OCI/Docker container images." 

It blends traditional OS with the tooling and workflow of modern containers. 

**PR's ARE WELCOME** - [Submit your project](https://github.com/bootcnode/awesome-bootc/pulls)

## Contents

- [Official Resources](#official-resources)
- [Base Images](#base-images)
- [Tools](#tools)
- [Examples and Tutorials](#examples-and-tutorials)
- [Community Projects](#community-projects)
- [Videos and Demos](#videos-and-demos)
- [Community](#community)
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

## Tools

### Building and Deployment
- [bootc-image-builder](https://github.com/osbuild/bootc-image-builder) - Convert bootc container images into disk images (ISO, QCOW2, VMware, AWS AMI)
- [podman-bootc](https://github.com/containers/podman-bootc) - Streamline podman + bootc interactions for development workflows
- [system-reinstall-bootc](https://developers.redhat.com/articles/2025/how-install-image-mode-system-using-system-reinstall-bootc) - Tool to reinstall existing systems as bootc

### GUI Tools
- [Podman Desktop bootc Extension](https://podman-desktop.io/blog/bootc-release-1.6) - Graphical extension for Podman Desktop with interactive build configuration creator
- [podman-desktop-extension-bootc](https://github.com/deboer-tim/podman-desktop-extension-bootc) - Bootable container support extension for Podman Desktop

## Examples and Tutorials

### Getting Started
- [Red Hat Developer bootc Guide](https://developers.redhat.com/articles/2024/09/24/bootc-getting-started-bootable-containers) - Comprehensive getting started guide with video demos
- [Fedora bootc Building Guide](https://docs.fedoraproject.org/en-US/bootc/building-from-scratch/) - Creating "from scratch" bootc base container images
- [RHEL bootc Building and Testing](https://docs.redhat.com/en/documentation/red_hat_enterprise_linux/9/html/using_image_mode_for_rhel_to_build_deploy_and_manage_operating_systems/building-and-testing-the-rhel-bootable-container-images_using-image-mode-for-rhel-to-build-deploy-and-manage-operating-systems) - Building and testing RHEL bootc images

### Example Repositories
- [redhat-et/bootc-examples](https://github.com/redhat-et/bootc-examples) - Collection of bootc examples and Containerfiles (Archived - moved to comprehensive documentation)
- [Fedora bootc Base Images Repository](https://docs.fedoraproject.org/en-US/bootc/base-images/) - Reference documentation for official base images

### Automation Examples
- [Ansible and bootc](https://ryandaniels.ca/blog/ansible-and-bootc/) - Guide on using Ansible with bootc systems
- [BootcBlade](https://github.com/spmfox/BootcBlade) - Ansible automation for deploying KVM hypervisor using bootc and Fedora Server

## Community Projects

### Desktop Distributions
- [Universal Blue](https://universal-blue.org) - Community-driven project creating desktop and server operating systems using bootc
- [HeliumOS](https://almalinux.org/blog/2024-09-02-bootc-almalinux-heliumos/) - Desktop operating system based on AlmaLinux bootc

### Development Tools
- [bootc Community Examples](https://docs.fedoraproject.org/en-US/bootc/building-containers/) - Community-maintained examples repository

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
