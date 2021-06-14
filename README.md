
# Mi primera implementación de Ansible

Este repositorio se ira actualizando conforme estaré adquiriendo conocimientos sobre Ansible.

Estructura de directorio:  
.  
├── ansible.cfg  
├── group_vars  
│   └── all  
│       ├── secure  
│       └── vars.yml  
├── host_vars  
│   └── ansiblecliente.municarrillo.go.cr.yml  
├── inventory.yml  
├── playbooks  
│   └── dhcp.yml  
├── requirements.txt  
├── roles  
│   ├── apache2  
│   │   ├── defaults  
│   │   │   └── main.yml  
│   │   └── tasks  
│   │       ├── apt.yml  
│   │       └── main.yml  
│   ├── dhcp  
│   │   ├── defaults  
│   │   │   └── main.yml  
│   │   └── tasks  
│   │       ├── apt.yml  
│   │       └── main.yml  
│   └── nis  
│       ├── defaults  
│       │   └── main.yml  
│       ├── files  
│       ├── meta  
│       │   └── main.yml  
│       ├── tasks  
│       └── templates  
└── README.md   

------------------------------  
Desarrollado por: @carlosmmairena  
Instagram: https://www.instagram.com/carlosmmairena/  
StackShare: https://stackshare.io/carlosmmairena   
