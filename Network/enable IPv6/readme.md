# IPv6 is needed for Waydroid container networking to work!

relation->: https://github.com/Unicorn-OS/Waydroid/tree/main/Network

Thread: https://github.com/hexdump0815/imagebuilder/issues/15

# Solution:
>hexdump0815 commented on Mar 9
>@p0358 - oh, then its not that easy - this should give you an idea of how you can adjust it based on the regular kernel and how you can test it: https://github.com/hexdump0815/imagebuilder/blob/main/doc/install-to-emmc-with-luks-full-disk-encryption.txt#L247-L279 ... this is then even with initrd, but you can also omit it (which is the default for the kernels in the images) - this is the corresponding part from the kernel build: https://github.com/hexdump0815/linux-mainline-mediatek-mt81xx-kernel/blob/master/readme.mt7#L48-L57 with this being the cmdline file: https://github.com/hexdump0815/linux-mainline-mediatek-mt81xx-kernel/blob/master/misc.cbm/misc/cmdline
>
>good luck and best wishes - hexdump
—https://github.com/hexdump0815/imagebuilder/issues/15#issuecomment-1462987641

>Okay, thanks for your directions and links I was able to actually rebuild the image properly. Pasting my final steps here for future reference, maybe would help someone:
—https://github.com/hexdump0815/imagebuilder/issues/15#issuecomment-1463089929
