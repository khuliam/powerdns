Role Name
=========

`powerdns` est le rôle ansible qui est utilisé pour déployer un serveur powerdns dans des conteneurs docker.

Requirements
------------

Notthing

Role Variables
--------------
Les variables suivant seront à définir :

- `pdns_servername:` le nom d'hôte de votre serveur sur lequel sera lancé le conteneur
- `pdns_pdns_domaine`: le domaine de votre serveur pdns
- `pdns_pdns_ip`: l'adresse ip de votre hôte pdns

Dependencies
------------

Pas de dépendance pour ce projet

Example Playbook
----------------
    - hosts: servers
      roles:
         - powerdns
         
License
-------

BSD

Author Information
------------------

- Name : Huliam Kenfack (@khuliam)
- Profil : Cloud & DevOps Ingineer