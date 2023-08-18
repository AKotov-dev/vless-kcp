# vless-kcp - personal security server
+ Install the rpm or deb package on your VPS
+ Generate a personal `server.json` on your computer and connection string using `vless-kcp-gen`
+ Copy `server.json` to VPS `/etc/vless-kcp/server.json` and restart: `systemctl restart vless-kcp`
+ Copy the connection string from `vless-kcp-gen` and paste it into [XRayGUI](https://github.com/AKotov-dev/XRayGUI); Press `Start`
+ Enable the Socks5 proxy - `127.0.0.1:1080` in the browser on your computer
+ This completes the configuration of the secure connection