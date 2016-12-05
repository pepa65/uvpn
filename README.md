# uvpn
*a quick way to setup secure openvpn with easy-rsa on Ubuntu*

Clone or download, and configure the options in `vars` then run `build-server`.
The packages openvpn and easy-rsa will be downloaded, server-side certificates 
generated and the server configured. Client configuration files (.ovpn) can then 
easily be generated with `build-ovpn CLIENTNAME`.
