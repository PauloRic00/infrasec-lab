## 1 Adaptadores de Rede do pfSense (VirtualBox)

Para garantir a segmentação correta do laboratório, o firewall pfSense utilizará 4 adaptadores de rede virtuais configurados da seguinte forma no VirtualBox:

| Adaptador | Tipo | Nome da Rede |
| :--- | :--- | :--- |
| **1 (WAN)** | NAT Network | `natnet-wan` |
| **2 (Gestão)** | Internal Network | `intnet-gestao` |
| **3 (Servidores)** | Internal Network | `intnet-servidores` |
| **4 (Atacante)** | Internal Network | `intnet-atacante` |