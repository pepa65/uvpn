# uVPN
*a quick way to setup secure OpenVPN with easy-rsa2 on Debian, Ubuntu and Linux Mint*

- Download/clone `build-ovpn`, `build-server` and `vars` to the same directory
- Edit `vars` file (instructions in comments)
- Run `sudo bash build-server`
  * Packages `openvpn` and `easy-rsa` will be installed if not present
  * Server-side certificates will be generated
  * OpenVPN server configuration will be (over)written [if confirmed]
  * The OpenVPN server will be (re)started [if confirmed]
- Run `sudo bash build-ovpn` to generate a OpenVPN client configuration file
