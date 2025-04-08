# Atelier-ansible-stack-lamp-wordpress

# Structure 
On peut creer l'arborescence à l'aide de ansible galaxy: 

**ansible-galaxy init roles/apache_php**
**ansible-galaxy init roles/mariadb**
**ansible-galaxy init roles/bind9**
**ansible-galaxy init roles/wordpress**

lamp-ansible/
├── inventory.ini
├── playbook.yml
├── roles/
│   ├── apache_php/
│   │   ├── tasks/
│   │   │   └── main.yml
│   ├── mariadb/
│   │   ├── tasks/
│   │   │   └── main.yml
│   ├── bind9/
│   │   ├── tasks/
│   │   │   └── main.yml
│   └── wordpress/
│       ├── tasks/
│       │   └── main.yml


Une fois les differents fichiers contruits, executer la commande: **ansible-playbook -i inventory.ini playbook.yml**
