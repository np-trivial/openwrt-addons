# openwrt-addons
At present, just one addon. The /etc/rc.button/wps script runs when the WPS button on the device is pressed (and released). This particular script starts the redsocks proxy (which must already be installed) and redirects all traffic from the specified source addresses to the proxy for 2 minutes, then return to normal.
