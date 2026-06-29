# CachyOS-Kernel-Bazzite-Dx
MIRROR FROM ORIGINAL REPO, please don't use until this message is gone and updated

> [!WARNING]This repo/distro is under HEAVY development for now. Existing changes will be noted below, currently this is a 1:1 mirror of the original it was forked from. 

My system: Framework 13 Laptop (12th Gen Intel)

Base image: [Bazzite DX](https://bazzite.gg/)

Modifications:
- Replaced kernel with [CachyOS Kernel](https://copr.fedorainfracloud.org/coprs/bieszczaders/kernel-cachyos/)
- [CachyOS ksmd](https://copr.fedorainfracloud.org/coprs/bieszczaders/kernel-cachyos-addons/)
- [kwin-effects-better-blur-dx](https://copr.fedorainfracloud.org/coprs/infinality/kwin-effects-better-blur-dx/)
- Removed steam in favour of flatpak steam

# Installation instructions:
Install any atomic fedora (Silverblue, Kinoite, Bazzite, Aurora, ... etc)

Run:
`rpm-ostree rebase ostree-image-signed:docker://ghcr.io/sihawken/cachyos-kernel-bazzite-dx`
