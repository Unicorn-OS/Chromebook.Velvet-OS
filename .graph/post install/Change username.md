>in case one want to have another default username than linux of the provided
bootable sd card images, just boot the image once from sd card, loging, set
a password for root (passwd root), reboot, switch to the first virtual console
(ctrl-alt-f1 - important: before logging into xorg) and login there as root
(mind the default us keyboard layout for the default password changem). now
run /scripts/rename-default-user.sh mypreferredusername and afterwards reboot.
—https://github.com/hexdump0815/imagebuilder/blob/main/doc/install-to-emmc-with-luks-full-disk-encryption.txt
