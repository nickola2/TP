# TP

Vous trouverez sur ce git, ma tentative de création et de configuration de Wiki media, mais j'ai arrêté en pleins milieu car mes fichiers ne fonctionnait pas et j'ai eu vraiment du mal au début à comprendre
le fonctionnement d'ansible.

Donc vraiment désolé, mais même si ce projet ne fonctionne pas comme demandé, j'aime beaucoup ansible pour son principe.

Voici les étapes à suivre pour construire le projet :

Pour générer la connexion aux machines par ssh il faut déposer la clé publique .pem dans les vms et tester la connexion avec ansible.

Pour faire ce tp, j'ai créer un vcenter sur un esxi pour vmware afin d'être au plus proche des réalités en entreprise.

Pour créer la VM, je n'ai pas réussi à créer à proprement parler la VM sur vcenter, mais j'ai réussi à les créer par duplication d'une VM déjà créé sur le vcenter.

 - Il faut donc exécuter avec ansible les fichiers crea_bdd_wiki / web / web_2

Puis dans l'ordre :

- hosts.yml
- mysql.yml
- conf_mysql

Et normalement, le serveur mysql soit être configuré.

Désolé de ne pas avoir terminé ce projet, mais merci pour cette découverte d'ansible !

Nicolas.
