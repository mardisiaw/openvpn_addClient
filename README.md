# openvpn_addClient
a Simple Shell script to create client key with ccd (pre-define IP Address)
with key & cert inside .ovpn file (1 file)

Pre-Requisite: EasyRSA (tested v3.1.6) installed at /etc/openvpn/easy-rsa
Installation: put addClient.sh & ovpn_template.txt inside /etc/openvpn

USAGE: ./addClient.sh <client_name> <pre-define_ip_address>
Result: /etc/openvpn/client/<client_name>.ovpn

Limitation: NoPass / no passphrase
