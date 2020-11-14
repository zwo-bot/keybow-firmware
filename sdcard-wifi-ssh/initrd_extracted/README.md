find . 2>/dev/null | cpio -o -H newc -R root:root | xz --check=crc32  > ../initrd
