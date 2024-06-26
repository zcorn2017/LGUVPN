# LGUVPN
A shell script to enable VPN access to the University of Long Gang (LGU. AKA the University of Hong Kong Shenzhen) under Linux.

## Installation

1. Ensure that the following dependencies are installed:
`ocproxy openconnect`
2. Move the `cuhksz` config file to your own `~/.config/openconnect`.
3. Move the `lguvpn` script to somewhere in your shell's `PATH`.
4. Replace `<password>` and `<student-id>` with your own password and student id.
5. Start the script by `sudo lguvpn start`.
6. If you need to accompany CUHKSZ's VPN access with the proxy (e.g. 科学上网) in one machine. Try adding a node in your config (That's why we need `ocproxy` in this shell script).
