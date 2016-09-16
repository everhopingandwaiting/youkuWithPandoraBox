dest root /
dest ram /tmp
lists_dir ext /var/opkg-lists
option overlay_root /overlay
src/gz 14.09_base http://downloads.openwrt.org/snapshots/trunk/ralink/packages/base
src/gz 14.09_telephony http://downloads.openwrt.org/snapshots/trunk/ralink/packages/telephony
src/gz 14.09_oldpackages http://downloads.openwrt.org/snapshots/trunk/ralink/packages/oldpackages
src/gz 14.09_packages http://downloads.openwrt.org/snapshots/trunk/ralink/packages/packages
src/gz 14.09_routing http://downloads.openwrt.org/snapshots/trunk/ralink/packages/routing
src/gz 14.09_management http://downloads.openwrt.org/snapshots/trunk/ralink/packages/management

