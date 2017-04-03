## openvpn-lightsail
Unattended OpenVPN server setup for AWS LightSail.

Installs OpenVPN server and automatically generates a single-user OpenVPN connection profile (.ovpn) in ec2-user's home directory.

1. Create a Lightsail VPS Instance
 - Choose "OS Only"
  - Amazon Linux
 - Click on "add launch script"
  - ```bash
  wget http://domain.com/openvpn-lightsail.sh && bash openvpn-lightsail.sh

Based on openvpn-install
