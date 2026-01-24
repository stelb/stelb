### Hi there 👋

Me on
* <a rel="me" href="https://mastodon.social/@stelb">Mastodon</a>
* <a rel="me" href="https://bsky.app/profile/stelb.bsky.social">Bluesky</a>
* <a rel="me" href="https://www.linkedin.com/in/stefanlebreton">LinkedIn</a>

I am working as DBA (Oracle, postgres) since 1999. But I always do more than only Databases.

Linux administration, mail servers, application servers, firewall, loadbalancer, storage, virtualization, monitoring, docker, kubernetes, ansible, certificates.

I am interested in far too much topics, not enough time for all :)


# Non-Business Projects
I am plugging together technologies to make things work.

## 'Production' important stuff for me
### Mailserver
* [Mailcow](https://mailcow.email/)
* added https://mta-sts.*/.well-known/mta-sts.txt URLs ([HOWTO](https://gist.github.com/stelb/ad50185bebf3147a9a16a7bbf4df83d0)) soon after this, there was an official integration.. 
* added backup with borgmatic
* oauth2 with kanidm

### Passwordsafe
* [Vaultwarden](https://github.com/dani-garcia/vaultwarden)
* nothing special, just automatic paranoid backup, because it will be a major pain to lose data 😅
* oauth2 with kanidm in testing... waiting for integration in vaultwarden release

### Document Management
#### Documents
Just started, no more paper, all digital documents in one place and not cluttered on disks or in mails.
* [paperless-ngx](https://docs.paperless-ngx.com/)
* [scanservjs](https://github.com/sbs20/scanservjs) (scan directly to consume folder)
* Integration with kanidm
* Sharelinks accessible from outside (wireguard tunnel, [caddy](https://caddyserver.com/), [opnsense](https://opnsense.org/]))
* Let's encrypt Certificates at home (DNS-01 validation, RFC2136, technitium DNS)
* import via mail rules/share/directly from scanner to share

#### Books/Manuals & similar
* Moving from calibre-web to [calibre-web automated](https://github.com/crocodilestick/Calibre-Web-Automated)
* -> automated imports from share & mail

### Push notifications
* [ntfy](https://ntfy.sh/) used by monitoring and automated updates/reboots

### Identity Management
* [kanidm](https://kanidm.com/)
* everything via commandline :)
* for oauth2, unix users on hosted boxes and maybe even internally soon
* todo: replicated setup..

### Routing/Firewall
* [OpnSense](https://opnsense.org/) with HA setup
* wireguard
* cloudflare tunnel
* mikrotik cloud router switches, cloud smart switches, several APs (cAP ax + wAP ax for home wifi, several map(lite) and hAP ax lite to do experiments, RB5009 is planned)
* still some old zyxel gs1900 switches

### NAS
* [TrueNAS CORE](https://www.truenas.com/truenas-core/) (TrueNAS mini is still on CORE)
* [TrueNAS SCALE CE](https://www.truenas.com/truenas-community-edition/) the seem to have ditched the "SCALE".. 2 UGREEN Boxes
  * [DXP 4800+](https://nas-de.ugreen.com/products/ugreen-nasync-dxp4800-plus-network-attached-storage) 4 Disks (temporary setup right now), 2x 4TB NVMe, 64GB RAM
  * [DXP 480T](https://nas-de.ugreen.com/products/ugreen-nasync-dxp480t-plus-network-attached-storage) All-Flash 4*4TB NvME, 64GB RAM
  * Both in small 2.5G Storage Network (not Mikrotik yet..)
* Letsencrypt Certs with custom shell authenticator [truenas_acme_hetzner](stelb/truenas_acme_hetzner)

### DNS
* [technitium](https://technitium.com/)

## Lab
### [Proxmox VE](https://www.proxmox.com/en/proxmox-virtual-environment/overview)
### Kubernetes
* [talos](https://www.talos.dev/)
* k3s
* kind
* minikube
* [cilium](https://cilium.io/)
* etc.
### OS
* ubuntu/debian
* CentOS
### Misc
* [netbootxyz](https://netboot.xyz/) (PXE Booting in lab)
* [oxidized](https://github.com/ytti/oxidized) (router/switch config backup)
* [traefik](https://traefik.io/traefik/)
* [netscaler](https://www.netscaler.com/) Loadbalancing
* [authelia](https://www.authelia.com/) Authentication
* [checkmk](https://checkmk.com/) Monitoring
* [dnscontrol](https://dnscontrol.org/) DNS Management
* [adguard](https://adguard.com/) DNS Filter
* [ZenArmor](https://www.zenarmor.com/) "AI-based Cloud threat intelligence" for opnsense
* [HomeAssistant](https://www.home-assistant.io/)
* docker

<!--
**stelb/stelb** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
