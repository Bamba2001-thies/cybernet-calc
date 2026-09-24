# CyberNet Calc

CyberNet Calc est une application web statique pour apprendre, calculer et simuler des concepts de réseaux informatiques.

## Fonctionnalités

### Calculateurs réseau

- Calcul d'adresse IPv4 et de sous-réseau
- Adresse réseau, broadcast et plage d'hôtes
- Conversion automatique CIDR / masque
- Nombre total d'adresses et d'hôtes utilisables
- Génération de plages DHCP
- Identification de classe et de type d'adresse IP
- Planificateur VLAN avec nombre de machines différent par département
- Conversion entre les bases binaire, décimale, octale et hexadécimale

### Constructeur de topologie

- Ajout de routeurs, switches, PC, serveurs, pare-feu et points d'accès
- Icônes réseau détaillées pour les équipements
- Équipements multiports
- Création automatique de liaisons sur les ports disponibles
- Suppression d'un équipement et de ses liaisons
- Zoom, dézoom et réinitialisation de la vue
- Déplacement des équipements dans l'espace de travail
- Simulation de trafic entre équipements
- Flux de bits en boucle avec bouton d'arrêt
- Types de messages :
  - Machine à machine
  - Routeur vers équipement
  - Réseau vers réseau
  - Équipement vers LAN
- Diffusion d'un même message vers tous les hôtes atteignables

## Technologies

- HTML5
- CSS3
- JavaScript natif
- SVG pour les équipements, les ports et les animations
- Aucune dépendance externe
- Aucun serveur backend requis

## Utilisation locale

Depuis le dossier du projet :

```powershell
python -m http.server 8000
```

Puis ouvrir :

```text
http://localhost:8000
```

Le fichier peut aussi être ouvert directement dans un navigateur, mais un serveur local est recommandé pour un comportement plus fiable.

## Déploiement Vercel

1. Importer le dépôt GitHub dans Vercel.
2. Sélectionner le dépôt `Bamba2001-thies/cybernet-calc`.
3. Ne renseigner aucune commande de build.
4. Utiliser le dossier racine comme répertoire du projet.
5. Cliquer sur **Deploy**.

Le projet étant statique, Vercel peut le publier directement sans configuration supplémentaire.

## Dépôt

https://github.com/Bamba2001-thies/cybernet-calc

## Licence

Projet éducatif et expérimental.
