# rhel9_network_config

`sudo nmcli connection modify <interface_name> ipv4.method manual ipv4.addresses <desired_static_ip>/<subnet_mask> ipv4.gateway <gateway_ip> ipv4.dns <primary_dns_server_ip> <secondary_dns_server_ip>`

`sudo nmcli connection up <interface_name>`

`nmcli connection show <interface_name>`

`ip addr show <interface_name>`
