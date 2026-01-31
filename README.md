# InstantV2Ray
Instantly turn any Linux machine to a V2Ray VPN Server!

With InstantV2Ray, you can pretty much any Linux machine into a V2Ray VPN server!

# Requirements
- A machine running a 64-bit Linux Distro
- A public IP with port forwarding capabilities
#### (You don't need to worry about it if you have a static IP // you use a VPS)
- Python 3

# How to use?
Simply run the following command and you'll have a ready V2Ray server using the VMESS protocol along with QR Code, TCP, and TLS:

`curl [TODO: put the actual link here] | python3 - -vm -ln YOURNAMEHERE --tcp --tls -qr`

Replace YOURNAMEHERE with the name you'd like the config to have or remove the `-ln` option completely to just have it set to default (`xray`).
