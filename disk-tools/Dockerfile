FROM alpine:3.20

# Install disk tools
RUN set -xe; \
	apk add --no-cache \
    wipefs \
    lvm2  \
    lvm2-dmeventd  \
    thin-provisioning-tools  \
    lsblk  \
    mdadm  \
    parted  \
    btrfs-progs  \
    e2fsprogs  \
    xfsprogs;
