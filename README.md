sudo nmcli connection delete Hotspot





sudo nmcli connection add type wifi ifname wlan0 con-name PSPNet ssid PSPNet mode ap wifi-sec.key-mgmt wpa-psk wifi-sec.psk 12345678 wifi-sec.pairwise tkip wifi-sec.group tkip




sudo nmcli connection up PSPNet
