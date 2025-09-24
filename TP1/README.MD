# 🔒 TP IPSec - Tunnels VPN avec StrongSwan

Ce projet implémente la configuration de tunnels **IPSec** en deux parties :

### 🔹 Partie 1 - IPSec Statique
- Configuration manuelle avec `ip xfrm`
- Modes **Transport** et **Tunnel**
- Clés statiques, Security Associations/Policies

### 🔹 Partie 2 - IPSec Dynamique (IKEv2)
- Automatisation avec **StrongSwan**
- PKI locale et certificats X.509
- Tunnels **Host-to-Host** et **Site-to-Site**
- Roadwarrior sans et avec EAP (Authenfication, Id)

## 🛠️ Outils
- **IPSec** (ESP/AH, Transport/Tunnel modes)
- **IKEv2** avec StrongSwan
- **PKI** intégrée (certificats RSA 4096)
- **Linux** + NetNS
