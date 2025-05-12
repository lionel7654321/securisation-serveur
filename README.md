# securisation-serveur
🔐 Durcissement de serveurs Linux et Windows
Ce projet met en œuvre une série de techniques de sécurisation pour des environnements serveurs Linux (Ubuntu 16.04) et Windows Server (2019), en se basant sur les recommandations du guide CIS (Center for Internet Security).

🧰 Contenu du projet
Linux – Ubuntu 16.04
Configuration de SELinux en mode "enforcing"

Vérification du chargeur GRUB pour assurer la persistance de SELinux

Création d’un utilisateur avec contexte SELinux spécifique

Affichage d’un message de bannière à la connexion

Vérification et activation de l’ASLR

Mise en place d’une politique de pare-feu restrictive (iptables)

Windows Server 2019
Configuration réseau avec IP statique

Installation du rôle de contrôleur de domaine Active Directory

Renommage du compte Administrateur

Blocage de l’extinction sans authentification

Désactivation de la connexion avec des comptes Microsoft

Configuration du pare-feu pour bloquer les connexions entrantes par défaut

Toutes les étapes sont accompagnées de captures d’écran de validation et de documentation détaillée.





🔐 Hardening Linux and Windows Servers
This project implements a set of security hardening measures on Linux (Ubuntu 16.04) and Windows Server (2019) environments, following best practices from the CIS (Center for Internet Security) guidelines.

🧰 Project Content
Linux – Ubuntu 16.04
Configure SELinux in "enforcing" mode

Ensure SELinux is enforced via GRUB

Create a user with a specific SELinux context

Display a login warning banner

Verify and enable ASLR

Apply a strict firewall policy using iptables

Windows Server 2019
Set static IP address

Install Active Directory Domain Controller role

Rename Administrator account

Prevent shutdown without login

Block sign-in with Microsoft accounts

Configure firewall to block incoming connections by default

All tasks include validation screenshots and clear documentation of the process.
