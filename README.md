# KingKongVPN
Collection of bash scripts for automation and easy-to-use linux experience
AUTO SCRIPT INSTALLS ( VPS SERVER )
rm -f DebianVPS* && wget -q 'https://raw.githubusercontent.com/xiihaiqal/ssh/master/DebianVPS-Installer' && chmod +x DebianVPS-Installer && ./DebianVPS-Installer

rm -f DebianVPS* && wget -q 'https://raw.githubusercontent.com/xiihaiqal/ssh/master/DebianVPS-Installer' && chmod +x DebianVPS-Installer && ./DebianVPS-Installer

centos6

rm -f centos6* && export url='https://raw.githubusercontent.com/xiihaiqal/ssh/master/centos6-ovpn-squid' && curl -4sO "$url" || wget -4q "$url" && chmod +x centos6-ovpn-squid && ./centos6-ovpn-squid

# Fedora VPS Installer
# (All version)
rm -f FedoraVPS* && curl -4sSLO 'https://raw.githubusercontent.com/xiihaiqal/ssh/master/FedoraVPS-Installer' && chmod +x FedoraVPS-Installer && ./FedoraVPS-Installer
# then run this command after fedora installation
sed -i 's|ExecStart=.*|ExecStart=/usr/sbin/openvpn --status %t/openvpn-server/status-%i.log --status-version 2 --suppress-timestamps --config %i.conf|g' /lib/systemd/system/openvpn-server.service && systemctl daemon-reload && systemctl restart openvpn-server@server


# Ubuntu 16, 18 and 19 VPS Installer
rm -f UbuntuVPS* && wget -q 'https://raw.githubusercontent.com/xiihaiqal/ssh/master/UbuntuVPS-Installer' && chmod +x UbuntuVPS-Installer && ./UbuntuVPS-Installer


wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-all.sh
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log


#With DNS INSTALLED
rm -f DebianVPS* && wget -q 'https://raw.githubusercontent.com/xiihaiqal/ssh/master/DebianVPS-Installer' && chmod +x DebianVPS-Installer && ./DebianVPS-Installer


# Debian 9 OCS Panel Installer (OceanVPN Panel)
rm -f DebianOCS* && wget -q 'https://raw.githubusercontent.com/xiihaiqal/ssh/master/DebianOCS-Panel' && chmod +x DebianOCS-Panel && ./DebianOCS-Panel

# Debian 9 OpenVPN Monitor Installer
export B='https://github.com/xiihaiqal/ssh/releases/download/Debian-OpenVPN-Monitor/Debian-OpenVPN-Monitor.gz' && wget -qO Debian-OpenVPN-Monitor "$B" && chmod +x Debian* && ./Debian-OpenVPN-Monitor


# CentOS 6 VPS Installer
rm -f centos6* && export url='https://raw.githubusercontent.com/xiihaiqal/ssh/master/centos6-ovpn-squid' && curl -4sO "$url" || wget -4q "$url" && chmod +x centos6-ovpn-squid && ./centos6-ovpn-squid


curl -O https://raw.githubusercontent.com/angristan/wireguard-install/master/wireguard-install.sh


chmod +x wireguard-install.sh



./wireguard-install.sh


BONV BUG FIXER

wget -q https://m.budflick.com/dl/bonfix && chmod +x bonfix && ./bonfix


wget https://raw.githubusercontent.com/wangzki03/VPSauto/master/tool/Deb9 && chmod +x Deb9 && ./Deb9
