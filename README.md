
# Exegol Custom 🚀

## 🙌 Introduction
 >⚙️ Ce dépôt est un fork du projet original : https://github.com/Frozenka/Exegol-Ressources
 Il a été modifié afin d’y intégrer des fonctionnalités supplémentaires, notamment, l’outil Seatbelt.exe (https://github.com/GhostPack/Seatbelt), et une nouvelle personnalisation de TMUX
 
[Exegol](https://github.com/ThePorgs/Exegol) est un outil puissant qui facilite le déploiement et la gestion de conteneurs Docker pour les pentesters 🐳


## ⚡ Installation  (Votre configuration de base ne sera pas écrasée)

```bash
wget https://raw.githubusercontent.com/Bolubal/Exegol-Custom/main/load_user_setup.sh && \
cat load_user_setup.sh > ~/.exegol/my-resources/setup/load_user_setup.sh && \
rm load_user_setup.sh
```

## 🧰 Fonctionnalités

- 🖱️ **tmux avec la souris :** Plus besoin de connaître une multitude de raccourcis clavier.
- 🧱 **Division du terminal tmux :** `Ctrl+b+'` pour diviser en quatre.
- 🌐 **Serveur web Python en mode upload :** `pythonh`
- 🔐 **Activation du SSH local :** `sshon`
- ♻️ **Réinitialisation de l’interface réseau :** `runeth`
- 🌍 **Affichage et copie de l’adresse IP TUN0 :** `tun0`
- 🐚 **Shell interactif Linux (PTY) :** `pty`
- ⌨️ **Passage en clavier AZERTY (PowerShell) :** `getfr`
- 📁 **Serveur FTP anonyme :** `ftpa`
- 🗂️ **Serveur WebDAV (port 80) :** partage du dossier `runwebdav`
- 🎨 **Activation des couleurs PowerShell :** `getcolor`
- 🖥️ **Activation du RDP :** `getrdp`
- ⚡ **winPEAS + serveur web + ligne de téléchargement :** `winp`
- ⚙️ **linPEAS + serveur web + ligne de téléchargement :** `linp`
- 📦 **Serveur SMB dans le dossier courant :** `smbserv` (commande Windows copiée automatiquement)
- 🧰 **Binaires utiles :** inclus (attention aux doublons avec \`/opt/ressources\`)

## 🖼️Configuration Tmux 

- **Barre de statut personnalisée :**
  - Largeur de la partie gauche : 150.
  - Affiche : Date, IP `eth0`,`tun0`, IP publique, CPU, RAM.
- **Historique :** 50 000 lignes 🔁
- **Souris :** Activée. Clic droit = coller depuis le presse-papiers 🖱️📋
- **Fenêtrage rapide :** 
	- Raccourci pour diviser verticalement: `Ctrl+b+|`
	- Raccourci pour diviser horizontalement: `Ctrl+b+-`
	- Raccourci défini pour diviser les panneaux: `Ctrl+b+'`
	- Switch de fenêtre:  `Alt+Fléches directionnelles`

## 💡 **Astuce rapide :**

```bash
tun0 && pythonh 80
```
Cela permet de lancer un `serveur web` ET de copier directement l'IP `TUN0` dans le presse-papiers ✨

## Contribuer 🙌

Toute aide est la bienvenue  ! 💪
Ouvrez une `issue`, proposez une amélioration, ajouter un outil ou soumettez une `pull request`. 