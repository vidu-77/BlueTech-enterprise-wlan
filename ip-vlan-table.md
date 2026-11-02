# IP, VLAN and SSID Table

| VLAN | Name | Network | SSID | Used for |
|------|------|---------|------|----------|
| 10 | Management (native) | 192.168.10.0/24 | - | WLC, APs, admin PC |
| 20 | Employee | 192.168.20.0/24 | WLAN-20 | Employee laptops |
| 30 | Guest | 192.168.30.0/24 | WLAN-30 | Guest laptops |

| Device | Address |
|--------|---------|
| WLC-3504 management | 192.168.10.254  |
| Router gateways     | .1 on each VLAN |