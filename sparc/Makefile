#
# Copyright (C) 2010-2013 OpenWrt.org
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#
include $(TOPDIR)/rules.mk

ARCH:=sparc
BOARD:=sparc
BOARDNAME:=Sun UltraSPARC
CPU_TYPE:=ultrasparc
FEATURES+=fpu tgz ext4 squashfs broken

KERNEL_PATCHVER:=4.1
MAINTAINER:=Imre Kaloz <kaloz@openwrt.org>

include $(INCLUDE_DIR)/target.mk

$(eval $(call BuildTarget))
