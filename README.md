# vagrantDWESUbuntuServer
## En Ubuntu Studio 20.04

- Ansible: 2.9.6
- Vagrant: 2.2.6

Existe una diferencia importante en la forma que se instala xdebug entre la versión 2.9 y 2.10 de Ansible.

Para la versión de Ansible 2.9 la instalación de xdebug se realiza con pear.

Para la versión de Ansible 2.10 Hay que instalar el paquete de ansible community.general.
> sudo ansible-galaxy collection install community.general

