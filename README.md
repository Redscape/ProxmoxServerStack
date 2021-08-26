# ProxmoxServerStack
A repository who contains my configuration of my Proxmox Server that I mounted on 2021.

This configuration is functional for me, it means that some elements are specific to me, like for example the IP range of the subnet dedicated to the VM, or the communication ports with Traefik, the reverse-proxy allowing the VMs to communicate to the outside.
This stack is composed of the following elements:
- Proxmox on a dedicated machine hosted at OneProvider.
- A pfSense VM, in front of the Proxmox thanks to iptables rules.
- A Traefik VM for the reverse proxy, with only ports 80 and 443 open.
- A VM containing Wordpress sites.
- A VM containing Nextcloud.
- A VM containing various services: Wallabag, Ghost (for my blog), Joplin Server (note taking-app), and soon, Bitwarden.
- A future VM for Azuracast (audio streaming service).

![](https://nextcloud.glarose.fr/s/Hc3MrJns3tXmc47/preview)
