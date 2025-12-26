# ponOS linux protype
# installation:
1. download files and extract
2. create partitons on disk
3. copy rootfs to root
4. check uuid of root disk and build custom initramfs init for u
5. copy kernel or use alpine kernel (check 6.)
6. chroot and install init (and kernel) by run:
apk update && apk add (may be openrc and linux, or other packages)
