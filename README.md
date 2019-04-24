# Ansible
Projet Ansible
Ce projet à pour but de monter une infrastructure composé de 2 machines. Une servant de base de donnée et l'autre avec des applications qui tourne dessus :
FTP, Wordpress,Apache,Php. Et Mysql comme base de donnée.
Ansible est un logiciel qui permet le déploiement, l'automatisation de tache, d'installation et paramétrage de plusieurs serveurs en même temps.

Utilisation : 

git clone : https://github.com/John33000/Ansible.git
cd Ansible
Modifiez le fichier : inventory.ini afin d'y rajouter vos IP.
vi/nano inventory.ini

ansible_host <IP>
ansible_host <IP>

Une fois cela fait lancez la commande : ansible-playbook play-Infra.yml
