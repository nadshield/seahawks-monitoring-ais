# seahawks-monitoring-ais
#   SeaHawks Monitoring

Projet de certification – Administrateur d’Infrastructures Sécurisées (AIS)

##  Objectif

Conception et déploiement d’une infrastructure virtualisée multi-sites sécurisée permettant la supervision, la maintenance à distance et la gestion des incidents.

Architecture simulant :

- Datacenter Roubaix
- Siège Kansas City
- Franchises NFL

---

##  Infrastructure

- Virtualisation : Proxmox VE (RAID-Z3, ZFS)
- Segmentation : VLAN & DMZ
- Firewall : pfSense (moindre privilège)
- VPN : IPsec (site-to-site) & WireGuard (client-to-site)
- Supervision : Grafana, Prometheus, Loki
- Sauvegarde : Veeam Backup & Replication (3-2-1)
- Ticketing & inventaire : GLPI
- Cluster web : HAProxy + NGINX
- Développement : Python (Harvester & Nester)

---

##  Sécurisation

- Segmentation stricte des flux
- NAT/PAT contrôlé
- Accès SSH par clés
- Interfaces admin restreintes LAN/VPN
- Journaux centralisés

---

##  Documentation

- [Voir le dossier technique](documentation/dossier-projet-seahawks.pdf)
- [Voir la soutenance](documentation/soutenance-seahawks.pdf)

---

##  Compétences mobilisées

Administration systèmes & réseaux  
Virtualisation  
Segmentation réseau  
VPN & firewalling  
Supervision & monitoring  
Stratégie de sauvegarde  
Architecture sécurisée multi-sites  
