# Comment accéder au projet

## Prérequis

- Assurez-vous que les playbooks ont été exécutés avec succès et que les services sont en cours d'exécution.

## Étapes

1. Ouvrez un navigateur web.

2. Accédez aux URL suivantes pour tester l'application :

    - Page d'accueil :
    
        ```
        http://<webserver_ip>:5000
        ```

    - Page de salutation :
    
        ```
        http://<webserver_ip>:5000/how%20are%20you
        ```

    - Page de lecture de la base de données :
    
        ```
        http://<webserver_ip>:5000/read%20from%20database
        ```

Remplacez `<webserver_ip>` par l'adresse IP de votre serveur web.