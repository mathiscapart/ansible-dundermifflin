# Ansible DunderMifflin

## Prérequis 

- Avoir votre environnement python sur Linux (pour Windows WSL), avec les pip qui sont dans le requirements.txt
    ```sh
    pip install -r requirements.txt
    ```
- Avoir un utilisateur, le même nom que sur votre environnement, qui a les droits sudo sans mot de passe et votre clé ssh sur tous les serveurs.

## Installation
### Services et monitoring
```sh
 ansible-playbook -i inventory.yml deploy.yml
```

## Maintenance
```sh
 ansible-playbook -i inventory.yml maintenance.yml
```
