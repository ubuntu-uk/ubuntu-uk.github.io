---
title: "Download Ubuntu"
description: "Get latest version of Ubuntu and install it on various environments."
image: "download.svg"
backgroundType: suru #light, dark, accent, suru, suru-topped, image
ubuntuVersions:
    ltsVersion: "24.04 LTS"
    normalVersion: "24.04"
    isLtsCurrent: true
    ltsReleaseNoteKor: https://blog.ubuntu-kr.org/2022/04/22/jamme-jellyfish-release-notes/
    ltsReleaseNote: https://discourse.ubuntu.com/t/ubuntu-24-04-lts-noble-numbat-release-notes/39890
    normalReleaseNote: https://discourse.ubuntu.com/t/mantic-minotaur-release-notes/35534

---

# Version and system requirements
## Ubuntu {{< param "ubuntuVersions.ltsVersion" >}}
Ubuntu {{< param "ubuntuVersions.ltsVersion" >}}, the latest LTS (Long term support) version, provides 5 years of maintenance and security updates for free.

<!-- The LTS version is recommended if you value stability over having newer software. -->

- [See Ubuntu {{< param "ubuntuVersions.ltsVersion" >}} release notes]({{< param "ubuntuVersions.ltsReleaseNote" >}})

<!-- ## Ubuntu {{< param "ubuntuVersions.normalVersion" >}}
If you like living on the edge, give Ubuntu {{< param "ubuntuVersions.normalVersion" >}} a go! It has all of Ubuntu's newest features to offer and provides 9 months of maintenance and security updates for free.

[See Ubuntu {{< param "ubuntuVersions.normalVersion" >}} release notes]({{< param "ubuntuVersions.normalReleaseNote" >}}) -->

## Ubuntu release and support cycle
New versions of Ubuntu are released every April and October at an interval of 6 months. LTS versions are released in April every couple of years (even-numbered years).

Maintenance and free security updates are provided for 5 years for the current LTS release and 9 months for interim releases.

More information can be found at the page linked below.

{{< button text="Ubuntu release cycle" href="https://ubuntu.com/about/release-cycle" icon="information" >}}

## System requirements

 - 2 GHz dual core processor and 4 GB system memory or better
 - 25 GB of free hard drive space
 - Internet access is helpful
 - Either a DVD drive or a USB port for the installer media

# Download

## From official website

{{< button text="Desktop" href="https://ubuntu.com/download/desktop" icon="begin-downloading" >}}
{{< button text="Server" href="https://ubuntu.com/download/server" icon="machines" >}}
{{< button text="Raspberry Pi" href="https://ubuntu.com/download/raspberry-pi" icon="switcher-dashboard" >}}
{{< button text="Internet of Things (Ubuntu Core)" href="https://ubuntu.com/download/iot" icon="switcher-dashboard" >}}

# How to install and use

## Desktop & Server
- Desktop: [Installation tutorial](https://ubuntu.com/tutorials/install-ubuntu-desktop)
- Server: [Installation tutorial](https://ubuntu.com/tutorials/install-ubuntu-server)
- [List of Certified Ubuntu hardwares](https://ubuntu.com/certified)
## Use on Public Clouds
- [Public cloud images](http://cloud-images.ubuntu.com/)
- Amazon Web Services: [Marketplace](https://aws.amazon.com/marketplace/seller-profile?id=565feec9-3d43-413e-9760-c651546613f2), [Documentations](https://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/EC2_GetStarted.html)
- Microsoft Azure: [Ubuntu on Azure](https://azure.microsoft.com/ko-kr/ubuntu/#overview), [Documentations](https://docs.microsoft.com/ko-kr/azure/virtual-machines/linux/quick-create-portal)
- Google Cloud Platform: [Marketplace](https://console.cloud.google.com/marketplace/product/ubuntu-os-cloud/ubuntu-focal), [Documentations](https://cloud.google.com/sdk/docs/quickstart-debian-ubuntu)

## WSL (Windows Subsystem for Linux)
If you are using latest version of Windows 10 or Windows 11, You can easily try out Ubuntu with WSL environment. 

{{< button text="Install Ubuntu on WSL" href="https://learn.microsoft.com/en-us/windows/wsl/install" icon="begin-downloading" >}}

## Linux Containers

Images for Application Containers: For building OCI images to use with Docker, Podman, Kubernetes.

{{< button text="Docker Hub" href="https://hub.docker.com/_/ubuntu" icon="begin-downloading" >}}
{{< button text="Amazon ECR Public Gallery" href="https://gallery.ecr.aws/ubuntu/ubuntu" icon="begin-downloading" >}}

Images for System Containers (VM Style Containers): Used with LXD and LXC for replacement of VM workloads.

{{< button text="See Container images for LXD, LXC" href="https://uk.lxd.images.canonical.com/" icon="begin-downloading" >}}
{{< button text="linuxcontainers.org" href="https://linuxcontainers.org/" >}}

# Get help
If you need help while using, You can get help on online community such as forums and online chat.

{{< button text="Forums" href="https://discourse.ubuntu.com/c/locos/ubuntu-uk/172" >}}
{{< button text="Mailing List" href="https://lists.ubuntu.com/archives/ubuntu-uk/" >}}
{{< button text="Chat (Slack, IRC)" href="../chat" >}}

{{< button text="Ask Ubuntu" href="https://askubuntu.com/" >}}
{{< button text="Ubuntu Forums" href="https://ubuntuforums.org/" >}}
{{< button text="Launchpad Answers" href="https://answers.launchpad.net/ubuntu" >}}

# Commercial technical support

{{< info title="Note" content="The Ubuntu UK Community is a non-profit community consisting of users and developers and is independent from Canonical Ltd. We do not provide any commercial technical support and answers for related inquiries. If you need commercial support for Ubuntu, have a look at the information provided underneath and get support from Canonical Ltd. or Canonical Partners.">}}

## Ubuntu Pro (Formerly Ubuntu Advantage)
Get commercial technical support from Canonical Ltd. the publisher of Ubuntu with Ubuntu Pro program.
Available plans are Free, Infra-only and Full Ubuntu Pro. You can get support for Desktops, Servers, VMs and applications(e.g. MySQL, MongoDB, NGINX, Kafka and more).


{{< button text="Ubuntu Pro" href="https://ubuntu.com/pro" icon="information" >}}

## Ubuntu Pro for Public Clouds
Using AWS, Google Cloud, Microsoft Azure? Create VM workloads with Ubuntu Pro, a premium Ubuntu image from Canonical Ltd. and get commercial technical support without additional contracts.

{{< button text="Ubuntu Pro for AWS" href="https://ubuntu.com/aws/pro" icon="information" >}}
{{< button text="Ubuntu Pro for Azure" href="https://ubuntu.com/azure/pro" icon="information" >}}
{{< button text="Ubuntu Pro for Google Cloud" href="https://ubuntu.com/gcp/pro" icon="information" >}}

## Canonical Partner
Partners of Canonical Ltd. also provides commercial technical support.

{{< button text="Find a Canonical partner" href="https://canonical.com/partners/find-a-partner" icon="information" >}}
