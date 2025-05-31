# 🛡️ Sécurisation Réseau avec IPFire

Ce projet vise à déployer une architecture réseau sécurisée basée sur IPFire, intégrant Suricata pour la détection/prévention d’intrusions (IDS/IPS), un pare-feu, et une DMZ. Il a été réalisé dans un environnement virtualisé pour simuler un réseau d’entreprise.

## 🎥 Démonstration vidéo

👉 [Clique ici pour voir la vidéo de démonstration](https://youtu.be/ExMEIlC5-64)  

## 🏗️ Architecture du projet

- **Zone RED** : Machine attaquante (Kali Linux)
- **Zone ORANGE** : DMZ avec serveur Web Apache
- **Zone GREEN** : Poste utilisateur interne (Windows)
- **IPFire** : Pare-feu central + IDS/IPS Suricata

## 🧪 Tests réalisés

- Scan Nmap depuis la zone RED
- Détection et blocage par Suricata
- Redirection de ports (HTTP) vers la DMZ
- Règles de pare-feu pour segmenter les flux
## 📄 Rapport
👉 [Télécharger le rapport PDF](./Rapport_ipfire.pdf)


