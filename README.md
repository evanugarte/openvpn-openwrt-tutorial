# openvpn-openwrt-tutorial
For reference from the video I made at https://www.youtube.com/watch?v=UVNOy_GOzFE

## What are all these files?
- `20220830-initial-openwrt-setup.tar.gz`: An archive of the OpenWRT router after following Van Tech Corner's video
 to flash OpenWRT on an SD card and enable the ethernet to usb adapter on the Pi ([YouTube](https://www.youtube.com/watch?v=TsOpO6O4xDE))
   - the password to access the LuCI web interface is `pleasechangeme`
- `openwrt-router`: This matches `/etc/openvpn/ccd/openwrt-router` on the EC2 instance that created in the tutorial.
- `server.conf`: This matches `/etc/openvpn/server/server.conf` on the EC2 instance that created in the tutorial.
