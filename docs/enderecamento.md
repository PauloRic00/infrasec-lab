## 1. Segmentação de Zonas e Gateways

| Zona | Rede | Gateway (pfSense) | Hosts Estáticos / DHCP |
| :--- | :--- | :--- | :--- |
| **WAN** | NAT Network (VirtualBox) | — | DHCP automático (`10.0.10.100–200`) |
| **Gestão** | `10.0.10.0/24` | `10.0.10.1` | Wazuh: `10.0.10.10` |
| **Servidores** | `10.0.20.0/24` | `10.0.20.1` | Ubuntu / Samba AD: `10.0.20.10` |
| **Atacante** | `10.0.30.0/24` | `10.0.30.1` | Kali Linux: `10.0.30.10` |