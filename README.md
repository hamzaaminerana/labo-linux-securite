# Serveur Linux sécurisé – SSH, pare-feu iptables et supervision

Projet de formation réalisé sur machines virtuelles (VirtualBox, Kali Linux) dans le cadre de ma Licence Pro Réseaux & Cybersécurité (CY Cergy Paris Université).

## Objectif
Installer, sécuriser et superviser un serveur Linux.

## Ce que j'ai réalisé
- **SSH sécurisé** : authentification par clés `ed25519`, désactivation de la connexion root et de l'authentification par mot de passe ; diagnostic et réparation d'une panne réelle du service SSH
- **Pare-feu iptables** : politique par défaut `DROP` sur la chaîne `INPUT`, liste blanche SSH + HTTP ; prise en compte du double pile IPv4/IPv6 (`ip6tables`)
- **Serveur web Apache** : installation et test en accès distant
- **Journaux** : analyse avec `journalctl` (SSH) et des logs Apache (`access.log`, codes HTTP)
- **Administration** : gestion des utilisateurs, groupes et permissions ; script Bash de rapport système (détection de connexions SSH et de ports suspects)

## Environnement
VirtualBox · Kali Linux

## Compétences mobilisées
Linux · SSH · iptables / ip6tables · Apache · journalctl · Bash · permissions

## Auteur
Hamza Rana – étudiant en Licence Pro Réseaux & Cybersécurité, en recherche d'une alternance en administration systèmes et réseaux.
