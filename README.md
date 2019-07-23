# cloud_factory_online_common_ansible

Il est possible d'étendre un peu ce role. 

Si vous souhaitez lancer ce playbook sur localement sur votre poste, vous pouvez lancer la commande :

ansible-playbook playbook.yml -i hosts.ini -c local -i '127.0.0.1,' 

Attention, la virgule à son importance au dessus ;) 

Vous pouvez définir un fichier d'inventaire hosts.ini dans ce répertoire directement pour étendre les possibilités.

Pour plus d'informations, je vous donne rendez-vous sur cloudfactoryonline.com.

Tous les packages suivants sont definies dans roles/common_setup/vars/mail.yml :

packages:
  - vim
  - htop
  - build-essential 
  - libssl-dev 
  - libffi-dev 
  - python-dev
  - python-setuptools
  - python3-pip

Libre à vous de les retirer, les garder, les modifier.
