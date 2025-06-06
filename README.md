# ansible-bootcamp

Repositorio de aprendizaje para automatización de infraestructura con Ansible en AWS.

# 🚀 Descripción

Este repositorio está diseñado para ayudarte a aprender y practicar la automatización de tareas de infraestructura utilizando Ansible. A través de ejemplos prácticos, podrás desplegar y configurar instancias EC2 en AWS, gestionar roles y variables, y aplicar buenas prácticas en la gestión de configuraciones.

# 📁 Estructura del repositorio

ansible.cfg: Archivo de configuración principal de Ansible.
site.yml: Playbook principal que orquesta la ejecución de roles.
inventories/: Contiene archivos de inventario para diferentes entornos (por ejemplo, prod).
group_vars/: Define variables específicas para grupos de hosts.
roles/: Contiene roles reutilizables que encapsulan tareas específicas.

# 🛠️ Requisitos previos

Cuenta activa en AWS.
Llave SSH válida para acceder a las instancias EC2.
Instancia de control con Ansible instalado.
Configuración adecuada de las credenciales de AWS (por ejemplo, mediante variables de entorno o archivos de configuración).
