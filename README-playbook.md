# Comment exécuter les playbooks

## Prérequis

- Assurez-vous d'avoir Ansible installé sur votre machine de contrôle.
- Assurez-vous d'avoir un accès SSH aux machines cibles.

## Étapes

1. Clonez le dépôt :

    ```sh
    git clone https://github.com/mmumshad/simple-webapp.git
    cd simple-webapp
    ```

2. Mettez à jour le fichier d'inventaire avec les adresses IP ou les noms d'hôte de vos machines cibles.

3. Exécutez le playbook site :

    ```sh
    ansible-playbook -i inventory playbooks/site.yml
    ```

Cela exécutera les rôles pour le serveur web, le serveur de base de données et le serveur d'application sur les hôtes respectifs.