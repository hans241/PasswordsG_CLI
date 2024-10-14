# Gestionnaire de Mots de Passe

## Description

Ce projet est un **gestionnaire de mots de passe** développé en Python. Il permet aux utilisateurs de générer, stocker, modifier, supprimer et afficher des mots de passe en toute simplicité via une interface en ligne de commande. Les mots de passe sont enregistrés dans un fichier **JSON** pour une gestion persistante. L'application offre également la possibilité de générer des mots de passe sécurisés automatiquement.

## Fonctionnalités

- **Générer un mot de passe sécurisé** : Crée un mot de passe aléatoire de longueur personnalisée, contenant des lettres, des chiffres et des caractères spéciaux.
- **Ajouter un mot de passe** : Enregistre un mot de passe avec un nom, une description, et éventuellement une URL associée.
- **Modifier un mot de passe** : Permet de modifier un mot de passe enregistré.
- **Supprimer un mot de passe** : Supprime un mot de passe du fichier de stockage.
- **Lister les mots de passe** : Affiche tous les mots de passe enregistrés avec leurs descriptions et autres informations.
- **Sauvegarde et Chargement** : Les mots de passe sont sauvegardés et récupérés à partir d'un fichier JSON.

## Prérequis

- Python 3.x doit être installé sur votre machine.
  
## Installation

1. Clonez ce dépôt ou téléchargez les fichiers source.

   ```bash
   git clone https://github.com/votre-utilisateur/password-manager.git
   cd password-manager
   ```

2. Assurez-vous d'avoir Python installé, puis lancez le programme en exécutant le fichier principal :

   ```bash
   python gestionnaire_mots_de_passe.py
   ```

## Utilisation

1. Lorsque vous démarrez le programme, un menu apparaîtra avec différentes options :

```
--- Gestionnaire de mots de passe ---
1. Générer un mot de passe
2. Enregistrer un mot de passe
3. Modifier un mot de passe
4. Supprimer un mot de passe
5. Lister les mots de passe
6. Quitter
```

2. Sélectionnez une option en entrant le numéro correspondant et suivez les instructions.

### Exemple : Générer et ajouter un mot de passe

- Sélectionnez l'option `1` pour générer un mot de passe aléatoire, puis indiquez la longueur souhaitée.
- Sélectionnez l'option `2` pour enregistrer un mot de passe. S'il est laissé vide, un mot de passe sera généré automatiquement.

### Exemple : Lister les mots de passe

- Sélectionnez l'option `5` pour voir tous les mots de passe enregistrés. Vous verrez le nom, la description, l'URL (si applicable), et le mot de passe.

## Structure du projet

```
password-manager/
│
├── passwords.json          # Fichier où sont stockés les mots de passe
├── gestionnaire_mots_de_passe.py  # Script principal contenant la logique du gestionnaire
└── README.md               # Fichier décrivant le projet
```

## Améliorations futures

- **Chiffrement des mots de passe** : Ajouter un chiffrement pour sécuriser les mots de passe stockés dans le fichier JSON.
- **Masquage de la saisie des mots de passe** : Utiliser la bibliothèque `getpass` pour masquer la saisie du mot de passe dans la console.
- **Interface graphique** : Développer une interface graphique pour faciliter l'utilisation du gestionnaire.
  
## Contribuer

Les contributions sont les bienvenues ! Si vous souhaitez améliorer ce projet, n'hésitez pas à faire une pull request ou à ouvrir une issue.

## License

Ce projet est sous licence MIT. Consultez le fichier [LICENSE](LICENSE) pour plus de détails.

---
