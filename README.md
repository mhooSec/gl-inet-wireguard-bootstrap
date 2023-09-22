# gl-inet-wireguard-bootstrap
Configure a WireGuard tunnel right after plugging in a GL iNet device (FW 4.0+)

Usage:
1.- Plug in your GL iNet device to the power. Allow a minute or two for the device to boot up.
2.- Connect your PC to the GL iNet device via an Ethernet cable (from LAN port of device to the PC), or via WiFi (wireless network credentials should be at the bottom of the device).
3.- Access the GL iNet device via SSH, with `ssh root@192.168.8.1`.
4.- Run the desired (client/egress) script. It is better to copy/paste it directly to the terminal, than trying to pull the script, as the GL iNet device is likely not to have Internet connectivity due to not having been initialised yet.
5.- Device will reboot. Upon restart, it should automatically connect to the specified WireGuard tunnel.
