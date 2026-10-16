## 1. Segmentação de Zonas e Gateways

| Zona | Rede | Gateway (pfSense) | Hosts estáticos | DHCP |
|---|---|---|---|---|
| WAN | NAT Network (VirtualBox) | — | — | automático |
| Gestão | 10.0.10.0/24 | 10.0.10.1 | Wazuh: 10.0.10.10 | 10.0.10.100–200 |
| Servidores | 10.0.20.0/24 | 10.0.20.1 | Ubuntu/Samba AD: 10.0.20.10 | sem DHCP |
| Atacante | 10.0.30.0/24 | 10.0.30.1 | Kali: 10.0.30.10 | sem DHCP |

## 2 Adaptadores de Rede do pfSense (VirtualBox)

Para garantir a segmentação correta do laboratório, o firewall pfSense utilizará 4 adaptadores de rede virtuais configurados da seguinte forma no VirtualBox:

| Adaptador | Tipo | Nome da Rede |
| :--- | :--- | :--- |
| **1 (WAN)** | NAT Network | `natnet-wan` |
| **2 (Gestão)** | Internal Network | `intnet-gestao` |
| **3 (Servidores)** | Internal Network | `intnet-servidores` |
| **4 (Atacante)** | Internal Network | `intnet-atacante` |