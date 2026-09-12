#
# Target
#

CONFIG_TARGET_x86=y

CONFIG_TARGET_x86_64=y

CONFIG_TARGET_x86_64_DEVICE_generic=y



#
# EFI
#

CONFIG_GRUB_EFI_IMAGES=y

CONFIG_EFI_IMAGES=y



#
# Filesystem
#

CONFIG_TARGET_ROOTFS_SQUASHFS=y

CONFIG_TARGET_IMAGES_GZIP=y



#
# LuCI
#

CONFIG_PACKAGE_luci=y

CONFIG_PACKAGE_luci-base=y



#
# Wireless stack
#

CONFIG_PACKAGE_kmod-cfg80211=y

CONFIG_PACKAGE_kmod-mac80211=y



#
# Intel iwlwifi
#

CONFIG_PACKAGE_kmod-iwlwifi=y


#
# Intel 5000 firmware
#

CONFIG_PACKAGE_iwlwifi-firmware-iwl5000=y



#
# Wireless tools
#

CONFIG_PACKAGE_iw=y

CONFIG_PACKAGE_iwinfo=y

CONFIG_PACKAGE_wireless-regdb=y



#
# AP mode
#

CONFIG_PACKAGE_hostapd-common=y

CONFIG_PACKAGE_wpad-basic=y



#
# PCI support
#

CONFIG_PACKAGE_kmod-pci=y

CONFIG_PACKAGE_pciutils=y



#
# Kernel wireless options
#

CONFIG_PACKAGE_kmod-rfkill=y



#
# USB
#

CONFIG_PACKAGE_kmod-usb-core=y



#
# IPv6
#

CONFIG_PACKAGE_ipv6helper=y
