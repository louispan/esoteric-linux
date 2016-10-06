https://wiki.debian.org/NetworkConfiguration

Edit `/etc/network/interfaces`

    auto eth0
    allow-hotplug eth0
    iface eth0 inet dhcp

https://wiki.debian.org/NetworkManager

Edit `/etc/NetworkManager/NetworkManager.conf`

    [ifupdown]
    managed=true
